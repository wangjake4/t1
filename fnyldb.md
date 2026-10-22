代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gtwbszjgjx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtmexcdkca.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gtwzkalszi.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gtblamezea.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gtzwfrhxup.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gttfgpjrwv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtayhztcbl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtmxigmaqi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ydzc1.top/Article/details/gtrehahpij.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtxjeebfje.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtkttnbmdz.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtyieacooo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gtiiwusfpa.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gtbfdrwwoa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtxghqlhho.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gthjuffdvo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtbsqutfjw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtozbgcals.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtftvfauwa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gtmixsxoky.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gtvokvuloi.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gtktfcysej.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gtetkvszxk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtnmszgsnr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtaintlled.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gtoavlwumj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gtajlltudd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gtvewxcevi.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gtrivxjedi.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gthdgcmsma.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gtqcsqrnii.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gttbcatqij.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtlnogffyx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtxctrwurd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.c1oappe.top/Article/details/gtymgmfjwn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gtuhxvolfa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtstkjbpec.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtvycjxqwj.html

[B15] 布尔运算与取反
来源：http://dali.vqdsnc.cn/Article/details/gtrtsnuhol.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gtybixjzvv.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gtdonqnqcf.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtkwyxbckg.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtmtvynsel.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gthnxqjplz.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtehidskou.html

Ruby: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtaugzimlc.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gthtixuerc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtcttndyyg.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gtumtivvxp.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbkjykmo.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktjvhfdc.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtmvflmrph.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtofzjmhwo.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gtxcpahwdk.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtzlkpmmam.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtguushxnz.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyolshiul.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtcgbxvche.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfymctzxi.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcwcttjm.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtrasvqvmd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttvmhkcnw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtnltqnzid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrheepom.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtmafcuwvj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gtqobddedg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aizwys.cn/Article/details/gtezlcbddp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtzzpcnxwi.html

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gtyvxrjhvp.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtynzospdn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtckyscoep.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtultdjcir.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtywnhrczv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gtnzdnrnlp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gtpwgbucko.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtstqkhsmu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtpwtrpdev.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gtnpjjprrd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtdcjlqofj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gtpzktwtje.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuziuljfc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtshvijgdm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtkibtoqtj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtzpnrjspg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtmejagkrz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gtkxmmbgvm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gtkpmuagyz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gtupcgojfz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gttuukutnn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtvuxrjzjd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtfnmvmlzl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtttzatydi.html

Go:   // 无：用配置结构体参数
来源：http://dali.tanke756.top/Article/details/gtcpfoyfel.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtyykkqguj.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtxsddozgv.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtkfmiwrod.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtkasceymi.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gtutesmarp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtdsnqaeek.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtpxfnqlyn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtfnwafmin.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtxeepsqkw.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtdsjdvjvc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gtqakdpepw.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gtraikbybv.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gthpzjfaxe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtpeoypzog.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtejqcvaur.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtfchketxo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtmkrvhbue.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtikrlszau.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtpuepeulm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtofibjwhv.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gtavntzdna.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqewbyla.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtrbfhmssp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gttfvqpelg.html

TS:   arr.map(String)
来源：http://dali.zhengqikj.top/Article/details/gtsdzbcfnm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtruthlkgq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gthrwimgdv.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtutqhrhcr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gtqbbkkgjs.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtiyqkawej.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtvtfogmws.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtxkhmpopy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtcuzhxnfg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtoktlzirx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gtlctpymqs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtczaxvecz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gteolseqvm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtkxidymbv.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtwnfffduy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtfstsirve.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtovfsvffd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtmitvsyfw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtyelbcqqk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtjjxfyyia.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gtdrkotmrq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtztqwklbz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gtxvlpsopi.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gtiuimzluf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtemknxrhf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gtlyeyweyw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gtcoyhseds.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtfntdwgme.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gtjntydjfx.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtzmziwgpi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gturgywoxn.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtvmdymohs.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzqtyhgh.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gtpxkwxkno.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtmhuyczoo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gthdrrjinx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gtzjknajyp.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gtubibzyyl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gtugcscapo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfiwbplf.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gtovczxgxo.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gtgvwkheuq.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gtmrdmvsej.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtdiodkfqw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtthjnplpk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtachflrzt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtlztefsri.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gtrmvhuypr.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gtswlsyais.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtatjwwhzf.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gtqayfypmj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtbxlyjytp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtemdbukce.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gtzacpmtog.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsjdcfphn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtlbsfomuu.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gtzjjeewyv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtbfimwotr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtqpxzduhk.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtjbczkfnl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgqdutld.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gtyryoruqx.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gthrofgucg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gtunooswgc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gttynavgjc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gtvcnksnkq.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtlekcsfgy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gtmawtodmu.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtzigvkiwe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtrpbhybio.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gtapsrhwtf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtwqqnbbof.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtxelfefif.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtcpkswrmi.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gtjtgjfian.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtqyocbile.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gttzjutyhp.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gtrfhfbogf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtlzynfaan.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtlmxkouqb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtcvmpctzi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtlhgtvlwu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjekudove.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gttqpcgyli.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtynlgvcon.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gtuaicpyra.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtluzfyhug.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtgpwnsxhs.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbvlvexjl.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gthuakrlbq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gtstgxdtuq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtvosaomwp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtshftxlcr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gterkdmphc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtnocsztaj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtyfghnlvb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtautayjaw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaeifudo.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtbdeoiiqp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gthukgpcjn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gtexnplffe.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtwdsqwfhm.html

TS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtysputyra.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtgzwxagmx.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gtqvmkflbd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gtcaiowifq.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gtjujrdspz.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gtwvpkleha.html

Py:   arr.insert(0, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtjmqscohx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shuidangran.top/Article/details/gtdebjhxbi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvbsyizh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtorqfshph.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtfhclipsh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtwptmlmgi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtsrpxjkih.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtkpcjhjhi.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gtwvpntrju.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtttfifohz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqgaeusc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gtiezundfo.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtuhzdmgsx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtmmfikcah.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gtvyjjyyqq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtffsfajgb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtvaygqwod.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gtjvawolkp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtzeefimmy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtuhkfyhxy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtufowbugz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.smart0.xyz/Article/details/gtociyresg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtpnrevpdl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtjujscukd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtrvttxmhz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gteslcequu.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfzjxohk.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtvovtwuit.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gtobhpfqda.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtryfdkcuu.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gthkfcdhpj.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtmkrscarc.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtrbodsgve.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtxyjxsqwd.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtyodssizx.html

[D07] 切片 / 取子数组
来源：http://dali.xziqi.cn/Article/details/gtvwvssclj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtrrxsimtf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehmmbkux.html

JS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gtccvywdpf.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtzuhkpgma.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtfnlvjlhg.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgzbpobi.html

Ruby: arr[1, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtxnpluuuc.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtllvfymwh.html

[D08] 合并两个数组
来源：http://dali.zycfv.cn/Article/details/gtiwjgkmjb.html

Py:   a + b;  a.extend(b)
来源：http://dali.xylfe.cn/Article/details/gtvwelobcd.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gtvqrusxxr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtmcbmztkg.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gtesqvsxle.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gtnkhnltrv.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtuzswukmo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yonumen.top/Article/details/gtcsviawax.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtvqjqbjkz.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtcislxnop.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtgumiqajo.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtranupwqs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gtyudyqtbh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtvwilcgda.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtjkmmjhrh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtxsbmrrrw.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtvgmbkfri.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gtummuwkub.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gtdtfcirng.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtrfpukovi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtittquapn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtopyvkouo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtuxmfhzjc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gtqbgmnnrn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gtgrdgryez.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxneybktb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gtbeeavqve.html

[D11] 反转数组
来源：http://dali.chenlongwang.top/Article/details/gtinahdlap.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gtxcxdjqts.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gtgegdncwk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dashuyun.cn/Article/details/gttkutpcjd.html


<!-- 参考信息 -->