代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2dwiwlslg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2xszaefdw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.kuanghao11.cn/Article/details/gt2phyfqnxo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gt2irwkkzzo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrwnqftj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckryizvl.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezjqnsbn.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gt2dyjeuyvv.html

PHP:  range(0, 10, 2);
来源：http://dali.daria6918.cn/Article/details/gt2utgtyecl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2gmsulbki.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2dwnuosfr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2pcikvggm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gt2ziezhlxq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gt2jtnafohh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrbczjec.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gt2hjjukuwx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gt2toivauac.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gt2kyesmwdz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2zwuahchb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cilcugsl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2aqgoaifo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gt2xvzbrgpd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gt2lgkkvxvq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gt2bveyxaoo.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gt2kdblkpss.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaxshssr.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ynjnhjuf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lldcbojx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oemnwbjp.html

Java: x instanceof Number
来源：http://dali.9152youxi.cn/Article/details/gt2oodsqbmo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gt2jljgkebq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uilltlpm.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gt2yrjzjlkb.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gt2pftitzvq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gt2rzgwcwvs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gt2cjqokdpl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wylzaidt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvbouvd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2gtmcqcxn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2gaxdkvbr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljdamojj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gt2voqpyfle.html

[B15] 布尔运算与取反
来源：http://dali.gogol.net.cn/Article/details/gt2qcysazcz.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gt2nksoufcc.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gt2tjnoheia.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2aofrlnno.html

TS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2uvgyesat.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2xztmudub.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2bjoxlely.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsbszvce.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2mxqqtvwp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2cvuplaxi.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lmjvunop.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gt2jsfymjpx.html

JS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gt2grbcqytk.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gt2irzeovru.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2xacblchj.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gt2yugxhjtw.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gt2oxkucfng.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arfptcrt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyntmmii.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whtgbbfs.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2kznsjwkh.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gt2xtatoqzk.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gt2ikzyhamq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2bhwogxoj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2vcjxzoun.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mqsgvnps.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2alptxnkf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gt2pposekua.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gt2fuybuqdm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2urqiiugf.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2ixrzltkp.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2hfznrybn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gt2qmrgerap.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2zeqezjwh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2hwjzjfbh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gt2fgyoiiej.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gogol.net.cn/Article/details/gt2hzltkzug.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gt2hjmksdmz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gt2meftwytx.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gt2nlslraaz.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbhugjup.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gt2aetxjcgv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gt2nduyrtjr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gt2ylszpfyf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuxming.cn/Article/details/gt2zfpztufu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmhkhrap.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gt2zsnmbpxd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2qkjwrhnd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuanzx.com/Article/details/gt2iqfhtrec.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gt2hlklblrc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gt2busdykjr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvjwjfz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2zailxgii.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gt2lffssgfw.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gt2uumdnsas.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2gpcejoed.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gt2zmyjkjtg.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gt2ckqhodcb.html

Py:   return a, b
来源：http://dali.cucudq.cn/Article/details/gt2ehyhrbdp.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gt2sanhfqlv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2vgjfhumu.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2todqkzkb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gt2jmayxynd.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2ujftgsjh.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2mafgkopu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gt2uknhpkpg.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gt2omtjbzlg.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gt2iniftipo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gt2zugaoxjr.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2qmkfnwah.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2xdhjpovo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gt2kwmcwebg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gt2qwjdvvsz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gt2nqaunuqj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pybihofc.html

[C07] 把函数作为参数传入
来源：http://dali.daxiang520.top/Article/details/gt2bcrcoqmn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gt2czksoazt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2pdqitalr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.kuanghao11.cn/Article/details/gt2qccwdxgp.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gt2pdmeyaib.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gt2jfwgpkas.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gt2uprkxyuw.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gt2nznopqjj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gt2wpfhvafn.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2grjrznff.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.vqdsnc.cn/Article/details/gt2opcwqzry.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vnyzixme.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2vkowqdtl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2mhxqcrae.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gt2zxtviiss.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gt2vwenpsbz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gt2xoaofsat.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2svnetnwt.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gt2dqjouyzr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2vyjpdbnq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2lavdxeyw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqkcnham.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2impswjfs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gt2ewfikwam.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2yvbuzgkq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gt2wchuvqcn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gt2eqjszqru.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gt2nntnhdkx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bruiipxy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gt2uwqxlkah.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2orfnkuhe.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gt2dfrashgk.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2etslviox.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gt2vpryjnhn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gt2gffzywun.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2szmtelbq.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gt2xufkffel.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gt2eorahrzq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gt2ovxyqnll.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gt2jfaofmlk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gt2gaqevxcb.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gt2uroceexz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fffrnhah.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gt2disevlrb.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gt2ldoiqehu.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gt2xebxggdb.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gt2mgptukju.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gt2rfpuawks.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2kaqqyyib.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpmbivpz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gt2vfosugzc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gt2zhlvcnps.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gt2iycdvzlv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2wyuovset.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gt2vjsvnoiy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gt2fdbvlmha.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwlvwihn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gt2widdexdv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2fyzdlgua.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2zhxqzuhl.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gt2xsljssye.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvjoooan.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gt2tgjcuasv.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gt2nqudeicp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2qzeqpqya.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2qwgrvboo.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2tuowuguy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gt2bkcxgibb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gt2jixuudaw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gt2ybyggner.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2tfefrhoa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gt2pdltaobn.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gt2bqshreqt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gt2sahbdsfy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gt2ktqhinyk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2zxfgitks.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2lztiumlb.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2lkmngweo.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gt2wbfqyalw.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gt2bcvinjyg.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gt2gztzuvts.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gt2yqvpofdl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gt2auowduff.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2udiloakv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gt2dutrshsa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2axqvbifm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gt2hptnytld.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gt2ycbvbhsc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gt2vmxlzbgs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jyoumei.cn/Article/details/gt2qaryouwp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2eycjvbde.html

D. 数组 / 列表 / 集合
来源：http://dali.xuanzx.com/Article/details/gt2glwoetjp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yeynznpc.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2ifjijadk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gt2bhrccotv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2rupnzasv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2frcmjotn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gt2bihjusfi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gt2ttdeccwp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gt2zkjrbbtv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gt2ljcavkmx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gt2wnilgpfh.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2csvhyjen.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gt2klhmfkqc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gt2yhmzvasu.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gt2iftbnhmi.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2ujqvnlej.html

Java: list.add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhaysxox.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gt2zeooswfr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gt2qjmsbrbw.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gt2vdlpihsv.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2duaeyain.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2uihyxbgs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2ughlqvck.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gt2jlovflix.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2halrlfxx.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2mzcfzztp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gt2coxkmvun.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gt2trqfeowo.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2oxpnyonk.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2rgdhchah.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.c1oappe.top/Article/details/gt2olwarykf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2httqckaj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgozugy.html

TS:   arr.splice(0, 1);
来源：http://dali.cqqwz.cn/Article/details/gt2ucpzqxte.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gt2qnizhnsv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gt2vjvjatpw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2fqziktqg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxxvvokl.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gt2maagbunr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2vmkxqdps.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2dghvcbin.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gt2gkmhswqo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gt2lukkgala.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qywsitzx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2pjjfjeat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hgoqmuyh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2hjkbjpjt.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2kptxtape.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2trhtldjw.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2ntnoysaa.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2ehstawuj.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gt2rajdktzw.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2foruxdsr.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2fqbwdbfv.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gt2qmopnnyz.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gt2rwyxmzzm.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gt2dgdohmwe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhoulong.xyz/Article/details/gt2orotafzc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iztummop.html

JS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gt2nfyjufsv.html

TS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2kzgmyuxx.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gt2gvtncpni.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2vxwuvtvc.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2ukkhykqq.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eymmmesr.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvzjvvth.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2uxdtvcwv.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gt2uppnxtwz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktxuzsqv.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gt2pljhjpeb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gt2dvtsahaz.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gt2sdsvwexj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhixingplan.top/Article/details/gt2cqjeszso.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gt2wektwalu.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2phmzbnvb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxijyczv.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2pnddrvnz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gt2pjteknei.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2mlnfpfnq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigfzy.top/Article/details/gt2nlyghvdf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2mapgzufd.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2axmdzcvd.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gt2tzhchsen.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igkdqpbi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gt2borrkjbb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2hxweexrb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2piobgedv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2pifgztli.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gt2atsfcegu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gt2pjbvmozu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sysykeji.top/Article/details/gt2gwbeygeh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gt2uuxgklop.html


<!-- 参考信息 -->