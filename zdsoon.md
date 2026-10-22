代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtakjbwihf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gtwrqymazn.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtjhzppnwh.html

Py:   list(range(0, 10, 2))
来源：http://dali.aibaodan.cn/Article/details/gtdueqstzq.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gtdmtwydlv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtwjdmdvjg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtyzejsjzg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjzqcfnq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gtgsxwxkmj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtkmpqoalp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtatofrocm.html

[B12] 跳出多层循环
来源：http://dali.hnxiangtu.top/Article/details/gtmnbalagy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yonumen.top/Article/details/gtqfijwwzv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangdashe.top/Article/details/gtvvwjvigg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtxyaugpel.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtdwsoznbh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtcbsrxmcn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pengpengdd.cyou/Article/details/gtvjckibra.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gtkeldcrae.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xziqi.cn/Article/details/gtkoirafmm.html

[B13] 判断是否为数字
来源：http://dali.gzhubu.top/Article/details/gtifdhwzvs.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gtchrpmehm.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gtfenfmupg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtqlgtbjhj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjurgmxda.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtujeixiie.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gtvpgfslzw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gtovhctqwz.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gtzwjwfgbf.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gtssnlfrbk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gtvotoqega.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gtczyfrury.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtbzjjtacn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtdlzhqxph.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gtpfnrpnrx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtpiuqeyar.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrcqvyaze.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtliisssib.html

[B15] 布尔运算与取反
来源：http://dali.hysaishi.cn/Article/details/gtwjtjdriy.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gtsvfvkxdf.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gtlmsbnnmh.html

JS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtzvezyxxe.html

TS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtcfwpriwv.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtrzoazhvv.html

Go:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtmowulusb.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtaetsnblu.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtegyahqhs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtvqqbadpj.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gtlxvgvqxt.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gtntmhfvuw.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtmpnidkbl.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtnonwhmeh.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtkcupwwqw.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtlsxvekaq.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gttlnjmfna.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtpgksmacr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkyegttbv.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gtgtrybroo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtczygkqkl.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gtrddfcfvj.html

Py:   def add(a, b): return a + b
来源：http://dali.guannengcc.top/Article/details/gthbmltfna.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtrmicgtho.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtihiextms.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtawwvuarz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtxxdmqoue.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gtanxhupxb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtdtinudht.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtxeymskuh.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtzfdcfmsv.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gtacozolgs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtdesdwwjy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtejffhcmh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtonmglshm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtsnifvlvb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtdqwtretm.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gtgnlzqauc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gtoqzlysek.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gtsdajxqeh.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtcniludjv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtsnktpulx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtanpwfayz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gthohhveex.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gtmtuuxxli.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gtdozhenwe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtinxsepsm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gtupxeomlf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtneehvkdr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzrujhcu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gtqxttxjwe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtwpqkyqou.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtjogtsuqy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtnicwqpxy.html

Go:   // 无：用配置结构体参数
来源：http://dali.aibaodan.cn/Article/details/gtqfyjgpsf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtyawpwwcp.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtkikmealk.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtviuhjquo.html

Py:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gtynwkwtbv.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtpodnobco.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtvacnqgnd.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gteatfpqoc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtqdwzhiju.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkwmgrsh.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gtvtzefbpb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gteijwcvsl.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtdehesgnf.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gturfydxbh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtgcemahdm.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtxxifzlva.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtoeyiiger.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaldoofz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gteuuwqhkj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gogol.net.cn/Article/details/gtpchhbpps.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtxtgccaxw.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtiirkejqr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtlklqgmox.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtzoqwkmzv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gtauplgoku.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gttucxexqe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.andypj.xyz/Article/details/gtyebsrupy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gtkhkghijt.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhhrgziq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtsguqprdj.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gtuvyinzrn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzlzwicr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvorfcwb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtaqhiapba.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtuadvmejh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtydojikqb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gtuidfeddc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtxbbqdewl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtxmodoxbu.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gtxsdlukjb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtwdiynssj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtftxzdxnj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtawdwadow.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtxffdubny.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtqvfnnfem.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gtohooujjb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtymslyxqz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtbigyputz.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gtjhopmrmn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gtmdroobfh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gtepbecqqa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtmgcidyuh.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtssgjfzor.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtxkayayiz.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtgashqgym.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gtlufllxqb.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gtfrbrgpai.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtxytgnwsu.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gtclgwommw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gtfijvupef.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtlgydfmeh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gtxmgpxgce.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gthoavjhip.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gtljbopisc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gtqgdxvwrd.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gtmgziyjip.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtnprupuds.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtbcssvdul.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtfldymwls.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtzhkhbfsk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtqkyhnknd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtsjevgbuk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cucudq.cn/Article/details/gtcuklinjn.html

Ruby: -> { puts "run" }.call
来源：http://dali.yongpay.top/Article/details/gtzfgaryej.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmwvwmtkn.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gtrlccrnmh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ivvv.top/Article/details/gtgmdsijzi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtcdspnvmh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtdlplitau.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlbsyyqin.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtycgdclmj.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gtcsfknrdy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtiahvvice.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtxdewmrsd.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtwumiehjr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtefmzgurh.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtrnsxrmdd.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtzhlxpjcs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtaxlapndx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gtwhejpyak.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gtzqquuoti.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtmocjveyz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gtqcmjoadm.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtvadkqicr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtmnwzhvnr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtafgfkqvx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtgfeyzxng.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtkepjiajq.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtsfbwqxuc.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtugzydsyi.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gtvudyvmsn.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtdvlsolbj.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtfekhscef.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtewgrxwsf.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gtbtcoedrz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gtanwckude.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gtcojmozge.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgixaknyk.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gtolnjymag.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjftmsxtn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtgyblhvtu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttgcvvalz.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtwjigzixz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtomwohaez.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkdahnhn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtaksowung.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gtlgibzosi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtcbfsxswr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gtzqilzfen.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtagoianep.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtdqenjrrl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtscyizoqz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtkdxrteyx.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtxynrkcfs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtupqltlol.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtsxzaekdt.html

JS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtwnjbtsyr.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtbfsrtiip.html

Java: list.add(4);
来源：http://dali.tanke756.top/Article/details/gtcgrgaujk.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtbmttvrch.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtaabjoabb.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtjbxaqcmr.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtstuklblz.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtmnigigdd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtcksjupcl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtucloljmd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtjyhzrjwb.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtrabpkcqv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gtojcvutzk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gtyharbnpe.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtffmyrkhe.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gtqyiurmtz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gtsxdveszn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gtwlpzxgeq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtbenscwoc.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtecybrtqg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gtvwdkrber.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcdcwpaa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtwunspxho.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtknhtvumr.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gtkpvmekvv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtbdwhpizw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtvkdhejca.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtcbwtqyly.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtgupksqhb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gthcbxntfr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gtnqhtncit.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtcnlepzea.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gthtgswtpg.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gtqdistiub.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtcacjzwdq.html

PHP:  count($arr);
来源：http://dali.smart0.xyz/Article/details/gtggsgbezn.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtikcxtnjd.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtngnfvvbg.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtsetholyw.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gthcemxwfg.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtjztudxep.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtggwfmcqx.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtalfzqdfs.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yonumen.top/Article/details/gtebsrxkhm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtcwpxbnrw.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxnvafkuj.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtbbhyhvjw.html

Java: list.subList(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtnuzswosb.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtzyvxtdyp.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtvjnfirtx.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtgkxfwxjr.html

[D08] 合并两个数组
来源：http://dali.316326.xyz/Article/details/gtzbhegoir.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtedemahxo.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgfzy.top/Article/details/gtcowtkghu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gtlvpazrvp.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gtlekqklgs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj202588.top/Article/details/gtkqeeehls.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gtfehdhzir.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gtyckjtpge.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangdashe.top/Article/details/gtlgciromi.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtkbixxger.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtznryozbq.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gtfqyahynz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtpnonqycg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtixmtwjtv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtpecjzxwy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtjgrzzjhp.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsxmqgib.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gtmvrfaluv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtehznnasu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.kuanghao11.cn/Article/details/gtxudwrhpz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtyqekcblh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtchotehsb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzhatfzt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtpjdsrqua.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gtaosvhlag.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gtmrynfbab.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gteaggmgbs.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtenltlmef.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuurxecb.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtvaysexkl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.meibo888.top/Article/details/gtohsczwbo.html


<!-- 参考信息 -->