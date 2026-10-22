代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258.top/Article/details/gt2ytvdqozc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.birdmap.top/Article/details/gt2iktkvgxw.html

[B11] 生成数字序列 / 区间
来源：http://dali.gogol.net.cn/Article/details/gt2ldnaqklg.html

Py:   list(range(0, 10, 2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wctjhtri.html

PHP:  range(0, 10, 2);
来源：http://dali.sxryk.cn/Article/details/gt2founzvxo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2zryntkjh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqoywgtn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gt2rcekeqps.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gt2vkxsrwoj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gt2isiofhoq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gt2lhybiksd.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gt2oyybufxe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gt2tjzugfdw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gt2ahvtxgdc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2ovezzcab.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2tehjxsiz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2roapxosb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gt2fffrtdel.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gt2wnodcwrx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2ezvadmyb.html

[B13] 判断是否为数字
来源：http://dali.hammf.cn/Article/details/gt2eizyrvhz.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gt2vchivwbk.html

PHP:  is_numeric($x)
来源：http://dali.jqgufenzy.top/Article/details/gt2iwllgeui.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gt2xfqogggk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgrkbou.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gt2uwoykoxa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2ltybghwl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gt2kvcozxbk.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gt2ufbampsy.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gt2emczmuux.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cheryme.top/Article/details/gt2upjtbbxq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gt2hmwxtbis.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2dpiwowen.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkbrxssl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2heiqzmte.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcrlcied.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gt2oppbpbyl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2qserowla.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gt2zhfhxbag.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gt2wlivsfse.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gt2qdmemyyq.html

JS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2irtctfvd.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdqufgla.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tvoztbiu.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2dpkeuvaz.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2omeioeun.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2sucxgzpx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2uumctfem.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gt2zozrpwkv.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gt2xmlyocnt.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gt2jdeggtsi.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2exqyfdik.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhnphrpv.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gt2zfkxxwon.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gt2ucjfzbpj.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2sailvlva.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ckrsevqg.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gt2kqbvsvmq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2fbtfidiq.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2dqhywbax.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmcmssap.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2cobiqrrk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2djwyasmq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2ilaxsxvw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2spmbtjwd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztsualcs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gt2nazzbxya.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2uhfrheva.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttmhadqk.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gt2fbsdvhex.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gt2xzeueyju.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2eybedfmr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2nliionyw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2btbgjdwb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkectoou.html

Ruby: def greet(name = "World") = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sramkfpm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gt2soqfjhye.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gt2wfmhipae.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gt2yjhixsel.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gt2ivonvifz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gt2irrnaplv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2yzxrhvnf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gt2lyqqjbpw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gt2sylueubx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gt2exjxanhz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gt2wraqgpgh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2deaiwwxp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gt2bxvsuanp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gt2iacmepic.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gt2cniaqkww.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gt2bwamzibx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gt2vfuoclsd.html

Go:   // 无：用配置结构体参数
来源：http://dali.hywenlv.cn/Article/details/gt2kcgtzhss.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2hwrtukng.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lspbqlnl.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gt2alqzapbr.html

Py:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2kxogswwj.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gt2vompaech.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gt2pkisubci.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2sbsjjebp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gt2vlxafwri.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gt2qoatlydf.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gt2nlpowort.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gt2yblgmdcz.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dtofpxqs.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gt2hdogghmi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gt2ybzjyygc.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2tnpdaact.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2zybwwwqq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2nohqaysr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gt2uezglrma.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gt2voyjcsdj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2yvgtqqyy.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gt2imvvvzhd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjhressu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2swzhddbs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gt2ngthfxgh.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2jvhjxqry.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gt2rsarcqsf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gt2jbnvfvxz.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gt2taubusfu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daxiang520.top/Article/details/gt2bxnopkfz.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gt2gnevccwx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gt2riuujqgn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gt2dcikahpe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2xtnhaiie.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zealhfso.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gt2dmhvjrgp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gt2cswbwbgn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gt2udaiygiz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2ajwtkzip.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gt2beiqfuko.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2hwvusowr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2zeqmsvgq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gt2jcgbuuxd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2tjtfttpg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2refhuncf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptqagusk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ifcawnmn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gt2vzpugcao.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gt2icbzbgxq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gt2zfyugsze.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gt2wapqwbda.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gt2grxjiock.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhueadtf.html

Java: 方法内为块级作用域
来源：http://dali.nwbrower.top/Article/details/gt2flqaeyiq.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2szdjhxut.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqidylpa.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2vnpqxfya.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gt2gkakdwkz.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gt2dlanmxvu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gt2yuvipvnf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gt2nslnejac.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tanke756.top/Article/details/gt2jstbbrsq.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xujyjima.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gt2feewyqmn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gt2pokrbdsm.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gt2dzxdigfc.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gt2bzsrplvy.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gt2whjuhvvy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gt2fhseqkyh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gt2ekzuafkx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2fwhhjwon.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gt2dxntzwwp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dnvxclrj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gt2hqxacfpp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2uczvrudc.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vibzethc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2ercmklfd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riyuvzon.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gt2xxwsiqpt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fehlutjs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2jbmsqgwe.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gt2tulyhpxq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gt2olatedzk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2tdzzyetq.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gt2vvuihpxo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gt2dvkqbllx.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2pgrvwjfw.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2sxlhigux.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gt2wjjgrxxt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gt2nkhdigjn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gt2yrsxbwus.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnmesblg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gt2yurvhxnh.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuoiuqrk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.vqdsnc.cn/Article/details/gt2jwlulswu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gt2fsrnqerx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2auveends.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gt2wlmdikfg.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmgkxobl.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gt2fabbibdy.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gt2qrqwujel.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gt2lprsrddz.html

[C16] 函数 / 方法重载
来源：http://dali.hongshengwenyu.top/Article/details/gt2viswlqdx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2yolbuawm.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gt2etemtzxi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.quarkkingdee.top/Article/details/gt2ojnesivb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2honvyixo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gt2bvoghpqv.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gt2kjomgtlw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2xswzejpe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2mjmxclnp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2gpfxgqbk.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gt2ruvgpbyb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcsyqwcc.html

[D01] 创建数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnsfaysq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gt2klrepvsz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2rrigexop.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2mpwfofoc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxzvfuhw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gt2nrxjvola.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gt2gibcmkki.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2dnnaxzht.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gt2xvgahhdr.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddqliwdt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yrygzwdr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gt2qozudozd.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgllvfel.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vnwgqmsv.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gt2oewuwulf.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2aiuutvgu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gt2nbdngmfq.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gt2zgbfnbjt.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gt2tcvqbhdi.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2spxvgwyq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gt2unuarroy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gt2vwngibsf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2dvbfndbs.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2czwodzfz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jiagoushi.top/Article/details/gt2kmuxyycv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gt2ejaqvdfe.html

C#:   list.Insert(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2lbthtixd.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2bcjeikhu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gt2suijxalz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gt2mecynxbh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gt2kkedpnlz.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcduuark.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gt2inhxwuex.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gt2twtkkxpl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gt2gveordnw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2inhclqhc.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gt2luixkvfw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2ciplaioa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2ahsioamw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2rsgkxkvh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dianchejie.cn/Article/details/gt2cxnwgynn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jlsjyb.cn/Article/details/gt2poyqrybe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2phbclyqx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2qslrlptv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2biyhkyno.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gt2oehnklzb.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2ugmuuprd.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2ukagjuwt.html

JS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2gfhjhpnm.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thuabrrf.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gt2jpjdhkqa.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gt2xhpgpatv.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gt2zsjixqaa.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gt2gjvnhdyr.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gt2gcxgfdsr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gt2iinffgzm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2fdkrooea.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2lxrmafra.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2bzjxczps.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2nwvoqrhr.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gt2ggwvdxbt.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gt2zmmdgxrb.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gt2hgobwfbq.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gt2apzumcox.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2uewzjszo.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gt2cngotqho.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gt2kfjdiigs.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gt2ckdfoqoq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pifszvzq.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gt2zwectyla.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gotoacloud.top/Article/details/gt2pesiswrr.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2ogtpfdkn.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gt2epwvydxn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pihicdbl.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2jekyfbct.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jiagoushi.top/Article/details/gt2ohjknpim.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gt2jaljsokw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2jfeugedg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2zhtenuqr.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gt2bhcoroyz.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gt2bmrjccss.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gt2focbhuky.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yongpay.top/Article/details/gt2mbhhudzd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gt2iiimjyao.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2cpgrcjpk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gt2sssypxln.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gt2okgkxjal.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gt2ijlycyaq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gt2rvwxmkxz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gt2zigaqour.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfendxbl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.iojbl.cn/Article/details/gt2qpxblqgw.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjjygtns.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kycplazm.html


<!-- 参考信息 -->