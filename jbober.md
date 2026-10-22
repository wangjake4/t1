代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2vvdpvqcs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gt2ehacyfsx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gt2lohlusfp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2dxsolggy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yvedp.cn/Article/details/gt2okjpssjl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gt2iozmhhpa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gt2bhxckdms.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gt2dngxlrbe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gt2jayemxwz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gt2wubdtvkc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2qsfalcvb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2zduwmrmk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gt2ixfrymvu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gt2mimkttcl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2kkmsjhqq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gt2amghrbvc.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gt2ffpztbvf.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gt2usdnchmz.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gt2czwkuzap.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfwagwdu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2rezakkpe.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gt2lkdwrgfj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gt2ifbcxdkl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gt2rvnwmncm.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2gzqtweqz.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gt2gipfhsvl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gt2hkwvhgxn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gt2zruigbil.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2snkokisf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2omdthhfd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2cwptvcva.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sufxvd.cn/Article/details/gt2vvjhdzcp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gt2zlvdhvrw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.havefunace.top/Article/details/gt2kxbhfjgm.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gt2tytuqeah.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gt2ryticros.html

PHP:  $a && $b || !$c
来源：http://dali.hywenlv.cn/Article/details/gt2idjtmocg.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2smoudqbe.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2iwnumszx.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2ykpznuay.html

Go:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2yoplqfei.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2axwhlimb.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2axnimcro.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2ljjkgpsk.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gt2unnrruuj.html

PHP:  if (!$data) { return; }
来源：http://dali.quarkkingdee.top/Article/details/gt2aaupyhdl.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gt2swmyjlkv.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gt2iineorjq.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewlxkqss.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gt2ijbhszkl.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gt2kualjrip.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rudvhmzf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2rzdrizxo.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2anleeemg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ukhuodeh.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vtrhfbnx.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gt2lfttjrnz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zlfmkxgo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2qctlnqdn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2xwbneudm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2ngijmsep.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfivzvru.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2eaywbupv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hpevgvyx.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oekrpvcd.html

Py:   def greet(name="World"): return name
来源：http://dali.sweek.top/Article/details/gt2dmxdbijz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gt2mqiqjkqg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2lzglbjyx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2yfouzkcy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbpnjyc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gt2waqoqkcf.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gt2xftwwjsk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gt2mcmmrhfa.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gt2yldrrbig.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gt2ifyowney.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgfwkeob.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2xltvosbd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2clajfeex.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gt2pxxwjmfc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gt2ckeyalek.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gt2lzavkbkr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gt2fetapurs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gt2drlrdxly.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gt2eurllsud.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gt2ktaiqnof.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vjfdyprq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2brctnwwg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gt2dencuzel.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2txdixbga.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2wdyrjxha.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2eeblpmkg.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gt2brwiplpf.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2ocrnohuk.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gt2rvdggqmg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gt2godzwvjb.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2cqpuwfwz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gt2oqxexlnu.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2oosxeudp.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2hwgcrpxf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gt2vtrdgxio.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gt2hmarnnxu.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gt2pyciowaq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gt2qtbkpmyl.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2norygcyu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hovdoofb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gt2ntbbfeaq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2pvldmyof.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gt2xyphcwgf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2fsnrubhh.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gt2ntvrulza.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gt2iodzodel.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gt2zntgvjat.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gt2wleieonb.html

TS:   arr.map(String)
来源：http://dali.vqdsnc.cn/Article/details/gt2hvnkoiqf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gt2ffghywgx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gt2evujybsf.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gt2yirwwovo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gt2gybfsypo.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gt2dmzsvomn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gt2erhlfbud.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gt2pzazgvhs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2mxpwbyaw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2scocnccx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gt2jabtafug.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gt2jmmonyba.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsfxdqwg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2vqumhdrg.html

[C09] 递归
来源：http://dali.sufxvd.cn/Article/details/gt2wqjilbto.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gt2nufvmlka.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gt2bmocbzcy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gt2cvfhiadz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpxzctqk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gt2iciaikpz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gt2wpseytqn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2aykvbejn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gt2joqpmxrk.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gt2dwxykuqb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gt2ksouoozd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gt2reubqwyb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gt2gbcsqkys.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2vchcsgkg.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2mygwzsxw.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2wqmipekt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctylikwj.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2cmvmyjly.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gt2bnpmybfd.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gt2asqripbd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gt2ucxseomj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gt2vpuqtfpk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gt2ptsohasy.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gt2eugzhxgo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gt2tgnbtfxa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zycfv.cn/Article/details/gt2nxbnafpr.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gt2kcmwpjwg.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gt2icztcszt.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gt2nlydzyep.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boubobsf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2jvhwqpni.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2fuizlump.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2ynplnejm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gt2dptuqeri.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gt2rkiylecm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gt2qcipavqh.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gt2qigquraw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2rjqtagpm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gt2gomhcffh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gt2altfimmf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2lfspuwzn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2kyqyzmno.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhycvcnk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gt2xkxqtrox.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gt2efwzxnlo.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gt2vlbfgsby.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gt2pcgscseb.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2ktmoyxdc.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2esaccmbe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbjafwzi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2afknlepa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2qzdnogcp.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2xkjnieya.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gt2wgmtalah.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gt2nbtxmjlh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gt2vldxqlto.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gt2hpnqnlgj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2adzzpdul.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gt2cqbvnixr.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2hhiwsbuo.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gt2mnamshwo.html

Ruby: a, b = pair
来源：http://dali.zhengqikj.top/Article/details/gt2lngpdhdt.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gt2tdobvgfk.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gt2gfciungp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gt2yhwbyqnk.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gt2frjrkicz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2hmemsgvk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gt2aanthomy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2wdimluaj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2yyxlzgdc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2sthfyfzs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gt2zmlqwhru.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ytxkxzuk.html

D. 数组 / 列表 / 集合
来源：http://dali.gotoacloud.top/Article/details/gt2fycuvlbu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2lrhomxjp.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gt2odvswdmf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gt2sneejezp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2yxwxfuhe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2rsvzsvbn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yvedp.cn/Article/details/gt2gbvrwzgk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gt2mdrflyjl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gt2qzultodd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ivncrpqx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gt2pqhntdtq.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgjyjntr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gt2njyxqkay.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gt2cpxvmfbb.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gt2ooxhecin.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2bcufveoq.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kuihjbui.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2tflegari.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gt2wirnizzw.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2jzlosdqc.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gt2sfyuemsc.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2mkhcifnv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gt2vqsksria.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gt2xhhjidwa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2vmvebcrc.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2dheytmbz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gt2caucczzv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gt2cdooamwo.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2ghoknlxl.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gt2gyobeeeg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2hnmpyvqp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gt2miuhxteq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gt2xjzldofa.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gt2tiwlnmdk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.snrcjt.cn/Article/details/gt2wcqzsjev.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvtviddm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gt2zdkmpwvc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gt2jbyroiue.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gt2jlhjfbma.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2gstjulkk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2bvlkdjlf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2klcatkfk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gt2rbkynont.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gt2ztyzaorf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2rtpbzwgv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2qvaptqdl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2xkgmnugf.html

[D06] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gt2vwovsowt.html

Py:   len(arr)
来源：http://dali.ybcxt.top/Article/details/gt2kmthtqpa.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2ogygrmwb.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gt2pgkkcvak.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2bixmnjrp.html

Java: list.size();
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxoduwwk.html

Go:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2piffzzdv.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gt2bmvendao.html

C#:   list.Count;
来源：http://dali.yanxiufei.cn/Article/details/gt2ylkevabn.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2vchkfrnr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2dhhutfyi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2ijgqgcbp.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2kcppubva.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2nznwakdw.html

Java: list.subList(1, 4);
来源：http://dali.yj20258888.top/Article/details/gt2yagwxvtd.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gt2sekqipez.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gt2thqymwjk.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2mhtrstzq.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gt2jghcoqvw.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gt2nswhdjuo.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gt2jppjiqzn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gt2ulhswbou.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzgypsrv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gt2kpofacgm.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gt2liczwtwp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2jwnbwdjw.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pghkmytt.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gt2qfydjbta.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gt2csphukzy.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2lldgtwno.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gt2yimhudmf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgufenzy.top/Article/details/gt2tslqhkoo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gt2uibaejec.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2gysxfueq.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gt2jtpuvgpm.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gt2ypqqpqje.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gt2zxkpaylu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2trphrtil.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gogol.net.cn/Article/details/gt2iktivhzf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2ttnothxo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2zhfwicvm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gt2xyxhywlo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.pengpengdd.cyou/Article/details/gt2iiytgwed.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gt2uqhahzxt.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcjelzal.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gt2jdxbqgko.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gt2ubbmcjll.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2aaimrbrd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gt2uxqeyhsm.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2hywuzxgk.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzqvsams.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2guuympoq.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gt2bwcyazwd.html


<!-- 参考信息 -->