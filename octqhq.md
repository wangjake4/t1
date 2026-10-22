代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxpontxq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gt2ieewykzc.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gt2iwfqckjh.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gt2txdrnamf.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gt2qqfnecom.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2pmqvbmaz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gt2okjeorst.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gt2gfqxzlxt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gt2iduujeop.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gt2vjocunsq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gt2dymdfqea.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gt2yxowzwxa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gt2zkwvsliy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gt2ewajvvwv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2vptdyjwo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2kzpctsge.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2toneufsw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vdljxvpo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gt2kuztffja.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gt2wiflubzi.html

[B13] 判断是否为数字
来源：http://dali.c1oappe.top/Article/details/gt2mpoptbng.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gt2uxjejycf.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aiwkzytn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2gblwmxrm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ljlicwdn.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lftcsgyt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gt2ukffsmtn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gt2sbflkxxl.html

C#:   x is int or double or decimal
来源：http://dali.nwbrower.top/Article/details/gt2jesjrxxq.html

[B14] 判断值是否在集合内
来源：http://dali.zhixingplan.top/Article/details/gt2zlqyqety.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtywyooy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenzaomai.com/Article/details/gt2nsusuiyg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2xrcijbmy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2sriwxbky.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2kqjhklvh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gt2rgqfresh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tianlin.xyz/Article/details/gt2onghzoth.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2dteauudb.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gt2lqldvkws.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gt2sefoxngt.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gt2qrgzvcyu.html

JS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2vcvpiesx.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2qeeudkto.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2jquremww.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2levauwll.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqkbbgor.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2cjohhrft.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gt2cjxipwel.html

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gt2rnsqqpqd.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gt2kehymdla.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gt2sknbgidc.html

TS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gt2rbmguemb.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gt2hzrahsmc.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gt2wtqoyaeb.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gt2hcrgionn.html

C#:   if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gt2zvhamdkm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2yaztvtfq.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gt2limzszjk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2wvnelnks.html

[C01] 定义函数
来源：http://dali.316326.xyz/Article/details/gt2memtqdfq.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gt2nrwznqkl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2tgaadfhh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2iafvhcak.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjvhxnvq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2mvudxcwv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gt2sfqwzyym.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gt2czfubrwr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvpunenn.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gt2ujienpkv.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gt2zfoqzhdt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbifmahc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bsdciixt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2fulbwiro.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gt2cothdfen.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gt2nrmztswp.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gt2fqkdlnxe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gt2obwuqomn.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvnogtfb.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gt2sbwmvkeo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gt2ncupxoaj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gt2zzstjmtv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gt2qlqjhmlz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gt2jearcrqc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guannengcc.top/Article/details/gt2decatxvk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gt2euqgtsdg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gt2mkogxrxx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gt2zrmbvrqz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gt2dqbdzwxw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gt2fnklrnzt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mahdoofw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2caltofrs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenzaomai.com/Article/details/gt2giamnxpv.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gt2jfadiiil.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aivofsfa.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gt2azzmcvmz.html

[C05] 返回多个值
来源：http://dali.gzhubu.top/Article/details/gt2zparuraa.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2yihcebqu.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gt2ejtotixa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gt2hokdwbik.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gt2tsiavyan.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gt2ixykhxcb.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2hfseonxz.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcsstnch.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gt2tabxgawm.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gt2vphbfsey.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gt2nzmkphdu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gt2tgkpioie.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2sypagtkb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2sptmcchu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ebnzcfsw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gt2pqtrwccd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gt2wmspxhwy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2pllmdcbu.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gt2bnjllsns.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kergsfjf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2peryrwwj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gt2rbjnjams.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gt2sjbwwzkg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2epssaxeg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gt2hisyfzgw.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gt2zpukqnjs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gt2gfpqenmq.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gt2wvouqusz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gt2mzkyjpkp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2hibbdgoz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kpqxzfll.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2gqxxjsnk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjgperpm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hysaishi.cn/Article/details/gt2kbbnfftf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gt2ompkegtc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2loehocdc.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gt2dozlvprt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2haxdcflq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.iojbl.cn/Article/details/gt2xtvdiqzh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2xvxyfwgi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgiadhaf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gt2fnvwhvkf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gt2vfrpqzby.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2zewoxbqw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gt2ssfvbfjx.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gt2yvwqnasx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gt2bgenffdu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gt2bolyaoyz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2evwhajxx.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2heqdkbin.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2wezuzjgt.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2kztefcus.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gt2thgxlipj.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2vvmunxys.html

[C11] 模块导入与导出
来源：http://dali.gzhubu.top/Article/details/gt2cxplhtns.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gt2krnbnfge.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gt2ojxiaced.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2hdlmbmia.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gt2yddhwuju.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pevkvthf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gt2ltajspwd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjqtvgsg.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gt2vbfrszpd.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ovbhwfrk.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gt2fhiegntr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gt2yghuhyps.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gt2cplxscca.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgrrpwic.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2bimkgwxw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gt2deebudcq.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gt2wybqldsz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuanzx.com/Article/details/gt2dvmbzdqm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gt2lyydjprq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2tuxamtrc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2ywqbdppq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gt2sxfubvmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfkyrjlo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2prgzufhx.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gt2bugsjkib.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrpgfih.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gt2orjeohdi.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2txkzjqie.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gt2ewtcbftg.html

PHP:  // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2xejnwzop.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2qbboacvj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvngkmex.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gt2xvvpyjcs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gt2nwprjqnb.html

Ruby: # 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2didzqfqn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gt2tgcnmlge.html

[C15] 解构 / 展开参数
来源：http://dali.nanxinkj.top/Article/details/gt2mzlpsagq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gt2nvspyame.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gt2lqknizot.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2szvefbxv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gt2sabxpbnj.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2jhoxfddn.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2bbhgdwgs.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gt2epstiwcl.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gt2bzwohffq.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gt2xzxcpuxf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gt2ifpqktyt.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gt2fjvtewew.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gt2ycnaenhg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gt2gvciwjlb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gt2fqjxlsnr.html

Go:   // 无重载：用不同函数名
来源：http://dali.fengsongda.top/Article/details/gt2douaeean.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gt2npwirfoi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gt2befwwjvx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2marqdczd.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gt2nvdihwzy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2fghxgkvy.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gt2pjyqxfck.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gt2ldhcyahi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gt2swlngein.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gt2wsxwxrfo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gt2zzzisgfy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gt2riyhlfdf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gt2ejcolonj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gt2pvynfzwp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gt2abkuuvxz.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gt2amlaifbs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sxwuwfbh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.havefunace.top/Article/details/gt2pasokoqc.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2szviceum.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gt2mzqbboyf.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gt2pyphpdxk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhprqmuq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gt2zbibhaiv.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2vveofldc.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gt2caqumfnc.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2dzdoclzh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhazicjp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gt2rurvroex.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2bnstkoim.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2prsonpnf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmcuxqct.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gt2preejzmu.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2opqbwmas.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gt2okhmabxg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hammf.cn/Article/details/gt2bsaouzfs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rshdseyl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.meibo888.top/Article/details/gt2amclkeqa.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2rbcrlnyq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gt2uqnovsnb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gt2renrjlar.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gt2xwinzaak.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gt2utqfwdru.html

[D05] 访问与修改元素
来源：http://dali.ivvv.top/Article/details/gt2rfvlqtna.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2zhfrfyop.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2fqtoambf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2zeailwvy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gt2maounoqc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.mhx1999.top/Article/details/gt2pbiqkigb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2fjbibmyl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2ktfjefxb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2ctqciddq.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2qjkigeka.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqzailaf.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2vuddzhon.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gt2qnhrbqfs.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2fdwaupza.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gt2qjcxmgnr.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2rrcgpmjx.html

Ruby: arr.length; arr.size
来源：http://dali.aibaodan.cn/Article/details/gt2squgbbwf.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gt2aqggaxcb.html

[D07] 切片 / 取子数组
来源：http://dali.zhongyouzk.top/Article/details/gt2nigzlvjt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svejazmi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2urxaevmf.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2dmsuelgt.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2pqzqxtwx.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2xcrxvrhj.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gt2llpiqkau.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gt2rbngkjfv.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2xemuhpfa.html

[D08] 合并两个数组
来源：http://dali.cdnleiting.top/Article/details/gt2dmadeugf.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gt2juycbaub.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gt2vwfrbhar.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2svywplyu.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gt2bucdoeyh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2smbpcosk.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gt2uqcxwrqp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gt2lpqxshfb.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2ufmtgutn.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gt2kqwnpmrd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2dboxrwkq.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2fkayvbsz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gt2epjngyyw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gt2amztevih.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2wlaatuym.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2fxzjrxop.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2msglkpmj.html

C#:   list.Sort();
来源：http://dali.yj202588.top/Article/details/gt2xqewunal.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gt2iejufogi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jexmhbqe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqruyipt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhbqzdkr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wlhoavyp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gt2olbbjqju.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gt2yxhuhczl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.havefunace.top/Article/details/gt2bbovjohv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gt2lalmiuuo.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gt2pcqvrgix.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2fjvwwoho.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gt2xjzttzvq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gt2zoxucgzg.html


<!-- 参考信息 -->