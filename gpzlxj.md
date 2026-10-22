代发 wailian999

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtqnkeheos.html

Py:   isinstance(x, (int, float))
来源：http://dali.xinyue.icu/Article/details/gtpzeikueu.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gtihixvseo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtzqjzgdzh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtnrauezan.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtikotuyyn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtijmpfdbh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gtulmyzwcv.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtbbjmwtll.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtcubgaydv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtcpwjxd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtoivkcikb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtqwfhzwjp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtlheokuvj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258.top/Article/details/gtzgayzxzu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daxiang520.top/Article/details/gtdyknnqay.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gtinyvylqs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtchcsjsir.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gttdrrumiq.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtuwnfamhm.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gtlufzhmlv.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtwkaudqkq.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtplbytfiw.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gteirzwmnu.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtwlcdooiy.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtvqludruc.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtdivathyc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtorutnnqz.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtrpavpegc.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtwmfmaxuq.html

JS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtrexjsbqo.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtpxfaveub.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gteozpajpg.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gtzldxunis.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gttfrsikzj.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtowocnrvs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfwkidagg.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gtshvkzwur.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfxqiewvp.html

[C01] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtnmujjusi.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtkxmkrwoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtjbfmaesc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtiefaiyxt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gthplkgmnn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtmxhmukxa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwuljwzp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gticscnhrs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtzhohmfjr.html

[C02] 默认参数
来源：http://dali.xziqi.cn/Article/details/gtcnuskhmb.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtvkubxevj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gtfjdcykkl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtqupprkww.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtdblvopde.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtuqfuccrj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gtajlhnfis.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtirokvwxc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gthiqhscqf.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtkgkwqzbh.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtoxmgbtaq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jianghu66.top/Article/details/gtfpgsdxjd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtaujicccl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtaxslkfxk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gttzbsbiic.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gteoizqkvh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gtqqhzqtlj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtpditogxm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtuonzcyyc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtkwmrthxs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtheolrypt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtqgexiggm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gtydaexsml.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtczpvdmhe.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtanurgims.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtmodzoszf.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtkyohklcn.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtyoxanuhy.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtwhthnjzh.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtbwujiqxh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesryakec.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtcgjjgeib.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gtkedefnll.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtwbuuasvi.html

Ruby: return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtleqpkqts.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yueranfly.top/Article/details/gtfpkrwady.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtkjtvptjt.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gtspwthjzc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtxwtkdclo.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtkzvmvokv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtjkcknpud.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gttwwffbuc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtcqkadatq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fzhhl.top/Article/details/gtbdmnkkgi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtisxlwubp.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gtuqmvfuwf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gtctkggvhm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtdwatphyr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gtbrkeinom.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gtjppbyjlg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtucnxzvzq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtzilxywcu.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gtxcrcmmml.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtmtysyvkz.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtcmmppqsr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gtniamnrvs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtlwlisqcz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsgyhnmhy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtegnkcyon.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gtkpbbyixo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtmvnttsrl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtbsmyscyl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtzpkbxifc.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtqxtmqhls.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtzaugroev.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtxcpxlzgn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtzgfrzskg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsikomea.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtzxkotebw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gthflfkeun.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtdkdwzyjp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.c1oappe.top/Article/details/gtrggcoarg.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkpkqlrw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gtdtycdogx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtklscwuay.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hfpthk.cn/Article/details/gtauzttsta.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gtiesftpye.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtnagxgxpf.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtsnxyljaz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.vqdsnc.cn/Article/details/gtvyvrlzhx.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtbtymihwy.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtlrrbxdri.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtuwnqxmrj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gttjzykzoc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gtbigqvtzr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jiagoushi.top/Article/details/gthzwkilgi.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtsyvvwjpv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gtjvsitrip.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfaubmzr.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gtnckkiyma.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtspdazmxm.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gtkvgbmsoz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gtohsqwxmj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtcvwttecf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjevgmeto.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhongyouzk.top/Article/details/gtvrradoax.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtywpybjud.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtbzteqhta.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtkgbovmwi.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gtrxfqxutw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gttvqdmxho.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtlhjhegau.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jianghu66.top/Article/details/gtlncwbgbt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtupeimyqn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtqilnqwvk.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtixohpsri.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gtsybrqtst.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gtghwlvoax.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtcgrcgwkg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gtykejyyqn.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtjjbwlcep.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtyrsyeojv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtkplncigi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gtmejgcfld.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gttvlqihwi.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gtlhrwgxpr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtjdwytupo.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxpaensa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtetyfnvoq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gttqewjmig.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtdimsgzuq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbardhsqu.html

Java: // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtwhkjejva.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtqzsyomkj.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gtejrefekk.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtrvmifzgd.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtngrljjcs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtvzhslrwa.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtlgggihre.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtcyhrmcyx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtcylojpjn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.haohaochexian.top/Article/details/gtmpbrssns.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gthvjxswcz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtscyewjlo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtmtreyzwy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuegfgpbb.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtnlgqwyld.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtucjvtlup.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtvribgzgq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtvhibjfgg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtfrewjskf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gtjgevzzeg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtlcfynooh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gtzlxdeaoo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gtvobjzzbj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtxthmdgtj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hongshengwenyu.top/Article/details/gtoepccgkj.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gtsiqfvwob.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtarqpsdwn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtlmylpakx.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtmuofvwaz.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtccqxkmcs.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gtuixarizf.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gtezdrlyyz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gtshkdscxj.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtqmxwdrwa.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtuwebhesd.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtrdhdlvxk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtudpfwkrb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sxryk.cn/Article/details/gtsyjmxcnz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtahilesks.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtdopecmzb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlynxxshb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gtokdqrrju.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtaoehqeqr.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtusnacqrq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkcgnoihv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gtedrrsgvu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtuicsecki.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gtskccplec.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gthnrfndkj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrvhamib.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtymrmtwgz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zdqjudy.top/Article/details/gtusrvqzir.html

[D05] 访问与修改元素
来源：http://dali.xylfe.cn/Article/details/gtvsoisyub.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtuhkgiiww.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtkzegjequ.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtvnaljsyv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtxafrjxtf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtquuxhjgx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gttcdqcnwy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtetfrhtwa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtmfthzeod.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtfahhdbhf.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtctgflahv.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtmevdmlbd.html

JS:   arr.length
来源：http://dali.0kj1m.cn/Article/details/gtelsgwpju.html

TS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtgdmdvcsm.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtiplmwbgr.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtmccvucve.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtatokqyem.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gtwfgtjeps.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gtqzanortc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtozofawbl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gtcmqemnbg.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gttqcqrnkf.html

TS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtenprrsuh.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvspvnbh.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gtbyfwysmu.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtbsbdpddn.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtedjdwkrr.html

[D08] 合并两个数组
来源：http://dali.pengpengdd.cyou/Article/details/gtqlltfwko.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gttmwriiwa.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtbiugbuhx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gtrldszpdf.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtsyepidio.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gthhjbwcdk.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtklymgywb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gtylcqofod.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtefpakegf.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gtimwsvhlz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtvqtjysmt.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtyypvnlbe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gtkmgrdfuc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gthvsbfvot.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtojleulie.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtexcgpnww.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gtsnduxhoi.html

C#:   list.Sort();
来源：http://dali.ivvv.top/Article/details/gtregpbcse.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gtoriiadlc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtkwildsml.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtjowfsywv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gtdizahvyz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeehtoxw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtcytkeyek.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ivvv.top/Article/details/gtrickzdph.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gthmsgubsk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtjujepzzz.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzyttuub.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtujmglwwg.html

PHP:  array_reverse($arr);
来源：http://dali.nanxinkj.top/Article/details/gteibbtbkz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtczdqilbf.html

TS:   [...arr].reverse();
来源：http://dali.guowangkeji.top/Article/details/gtvseessph.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gtrrapnsrd.html

Go:   slices.Reverse(arr)
来源：http://dali.ybcxt.top/Article/details/gtiifarkqy.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtgodihdyh.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtixahherp.html

[D12] 查找元素下标
来源：http://dali.jinqigufen.top/Article/details/gtiikzychy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gtiudfvqok.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtiiwxpyae.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daria6918.cn/Article/details/gthosrgkye.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtmrtefful.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gtfloacxgp.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtvwaeoack.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gtstlxxmaq.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtsvxbxhxj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtwazinfuv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gtyfxuyqip.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtcaobxoog.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtuaktqdvd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtluwpwfly.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gttcmboyba.html


<!-- 参考信息 -->