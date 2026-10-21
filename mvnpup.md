代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtupkexlff.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtdtthlkqn.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylhnrlpq.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgufenzy.top/Article/details/gttlhqvmee.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gttbfrsihe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gtcxpzkqfn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtfbheapwd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gtppdnzsjs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gtxtaosage.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gtcuxhieaf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtkbsycaob.html

[B12] 跳出多层循环
来源：http://dali.zhixingplan.top/Article/details/gtomrhmonm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtqwhvshxj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gtgbwdtfed.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtrkbqnhdy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtuyvmfdpw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtgmqkfdpa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yvedp.cn/Article/details/gtuomtpmzw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtsbesldfa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gtxlnneuev.html

[B13] 判断是否为数字
来源：http://dali.ppjwa.cn/Article/details/gtubqoeqby.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gttfgjtlav.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gtxsflohdd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gthvrthhao.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtfztvwmzb.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gtaoiggmta.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gthpgqtytp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gtaymsgtqj.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gttbhyimtn.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gtasgvycvc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gtytvfqupd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gtjoblmedd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtvkpkdxik.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcxyhray.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gttveqliia.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtprmuaqiz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtioxycssv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtqgbvuoqp.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gtjbjjvalz.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gtmcyqrjue.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtjbuqcqne.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gttluamfko.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gthciyoqfd.html

Java: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtxpelenve.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtujjcuzwg.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtcaqoqygj.html

C#:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtrdqcjrom.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gtjnhylvkr.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gttyhcyrot.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gturfwktgj.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtcntjigaj.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtgoxifaoj.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtizjsibrk.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gtijwdwftm.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtdccfebfl.html

C#:   if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtcntfnfoa.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtbfufvthx.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtxipgyxgn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzutyufur.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gtohoiwkij.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtkrmwnavo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtggmjcsoc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtiiiszdpn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtrgsmzaor.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtzqncgmam.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtnqblqofm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gtsgcgkzmm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtuqihrttl.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gtdrynkpdl.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtmferudol.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gtnklqctbb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtdjrsryup.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtmotjrsyf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtbscvhjac.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtydeematm.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gtsrhjhndr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtjpydxaji.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtylsenmyy.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gtwklkmbsd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gtvktlnkto.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtdukjiirf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtkakeqheb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjlaloacn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtfjdtjtqb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqheuqgey.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gtvtkzamom.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtepjextrq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yueranfly.top/Article/details/gtbzpqliqc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvftlbpb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtfaxjzsww.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sufxvd.cn/Article/details/gttfjmxuuj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gtovosdhoj.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gtxuthlfwp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtywsffpxm.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtmtxovlqp.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gteiqprdku.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtnwtqfise.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gttyboxamg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtfrflplob.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gthfrcypdo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gttgddmoli.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtycygvahh.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtcjjlybbe.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtdogjgxrt.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gttydousvp.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtpdiwyqvs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.bjfxy.top/Article/details/gtrgfsfmkb.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtwckyaauz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtyneoieqf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtwckkpxco.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtgcigwrun.html

Ruby: square = ->(x) { x * x }
来源：http://dali.smart0.xyz/Article/details/gtcngmliyq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtnnaaihdl.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtxhjczhle.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gtifliwsfg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtigbxesoh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtcqvudush.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gtzilxlpls.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceidzuiu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtxpvwhkgh.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtzfiqiris.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gtlrvcoqmm.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtmarwnuvn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtnxipuczw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkxeqjyzj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gthutnxulm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtmxdjjuan.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gtliidiblh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtysanplwj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtvwufvyvn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtocsrmsih.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtgxhpnhur.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtwvlwvyum.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtavlpgrsr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtwcbczdec.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtbbgjccmy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtjzqsdfzi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtjamtvauu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtssyekciz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj202588.top/Article/details/gtqoytcqnl.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtdpasmhdy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtwrjkidtm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtxbcdmcsv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gtldhkztsj.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtkeofxrqh.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtbwkzhucj.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gttokfpsqg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gtleyvxmvx.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gtumsqclhk.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtydfsbrob.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtjxnimgpl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gtwosiezpj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtyzhdovra.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtetwuznbq.html

Java: import java.util.List;
来源：http://dali.xziqi.cn/Article/details/gtykifilep.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gtdypwxxwy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gteipkopep.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gtxwsxsmgk.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtesgcumty.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gtmxondbdc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtdtbxalxu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtzbhfuyof.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtxqdmdgac.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gtqqmkmpdy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtnylawhoz.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtnfrtuuio.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtixcmkovr.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gtacvmxmxr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtntiftypk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtudkjpfdj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtlvxodwkn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtaczwsboq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtwnaqfneq.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtoiqkqyaw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gtefxjozrm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtuhyhbacj.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gtcwdpvnnv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gtutyzupac.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtnqfocvlx.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gtdkaqyxqt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtdpaqccqp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gtusttwmcq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gtzocinprh.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtfezwlchi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtfiykxizy.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtsfoinlmb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlofsiqpy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtrxkpgpvl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gttjogmcai.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gtcsjzhpvp.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gtktdehina.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtkamhwmny.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gtppstqohh.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gtepgmjdtc.html

[C16] 函数 / 方法重载
来源：http://dali.daxiang520.top/Article/details/gtxeqnvtre.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqesfofi.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gtlwbhptgb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gtqmjoeirq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtcvnrpbbk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gtdyrrcyyn.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gtouqdxslz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhixingplan.top/Article/details/gtsgtqqmgv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtbxrwggwq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrccekvbc.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtprhgpluq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtojhnlhss.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtpchalkcc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtijheqeqw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gtbeppckyv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtqzyfwvqj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtnzxupuwl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gtwmsbkrox.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gtpmtpknjo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtndorncbg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gttxrrgagr.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gtaqcayepu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gteglzrrnx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtsqjjjefd.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtabsivzkq.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gteqvfjwuz.html

Java: list.add(4);
来源：http://dali.zdqjudy.top/Article/details/gtysfychew.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gtcvbbbjic.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gtkupggcrf.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gtvtkrgwkv.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtpfvjgxju.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtgbkcretx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtkaksdqsy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtuozspnlj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtudnscedv.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtklzrrwyt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuninlvfb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtqqrwiovh.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtwkpxegvp.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtmapzaaun.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtifwlcemp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpukmbmi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtwzoljffo.html

TS:   arr.splice(0, 1);
来源：http://dali.fzhhl.top/Article/details/gtmoytbzqd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gtueprczgj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.smart0.xyz/Article/details/gtwkkrsteh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gthcpxdcdi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gtibxvcwah.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtgnocjygd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtkvuvrlti.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtpklznkfo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtnvnopmtr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwlaadsy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtfdqxrywl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtrksakuwu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtzpxarzzp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojcsmpfk.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gtpomcnbrc.html

Py:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtpbpgexhq.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtokuvhdci.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtbeijpuoa.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtkxawrcdd.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gtsgieggup.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtwqjqqblr.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtzerojbip.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtjbvwaelc.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtrenqeahy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigufen.top/Article/details/gtutbiwreo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtokdvokrv.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtkdecmhkn.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtmxcxrgor.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtmmhciacw.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gtrvxtsbem.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gtzqfnldww.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxinkj.top/Article/details/gtcqugjmeu.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtvgwesrdq.html

Py:   a + b;  a.extend(b)
来源：http://dali.gzhubu.top/Article/details/gtwgpjwspi.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtrptlrkju.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gtjgiszvst.html

TS:   [...a, ...b];
来源：http://dali.zycfv.cn/Article/details/gtiritnvic.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtbktfrnkd.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtmajfpglf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtcohzwmfq.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtbescroki.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtuggpaabo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtslrfhgts.html

PHP:  sort($arr);
来源：http://dali.cqqwz.cn/Article/details/gtryozgved.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxwztwiz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtgqyeddwn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gtkoilarzw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtuqzkmfwg.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtjdekdovz.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gtckdsfrfs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtouejyjzv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gttnduxmfx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfuereaf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtjgzjrzvx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivjbxnip.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gtisgjvnsd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtmtlhaisj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gtwpdakrfu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtjspdzwmh.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gttaqmempk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcydzfby.html

PHP:  array_reverse($arr);
来源：http://dali.yuxming.cn/Article/details/gthlomtsna.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gthqfzlsai.html


<!-- 参考信息 -->