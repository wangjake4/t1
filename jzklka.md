代发 wailian999

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtxsinnivy.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gttkoctzha.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtamcfolqk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gtpzzgaebt.html

Py:   if not data: return
来源：http://dali.316326.xyz/Article/details/gtfotgbsbv.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gtbzpwvgap.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gthatwjqwm.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtwxobcfna.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtinnvxyjh.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtajtlnvga.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gtliqrsdag.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtgafjevnn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gturlvdpzo.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gthiwmeaof.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtygjneaon.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtgcqmojoq.html

Py:   def add(a, b): return a + b
来源：http://dali.sufxvd.cn/Article/details/gtybryxsrd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtdnbomadr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtykcfjcfu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtfgexujyd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtkkydivgx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtlpunpvtd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaiigentz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtnjvrbkyl.html

[C02] 默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkcuauxx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gtxjorsazx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtbjaacbtf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtwtsrynyk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtukohtwje.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtdyfvddnj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtmfnxgpdh.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gtimxvkxwj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjjgnhdn.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gtgkldtiym.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtamqcgykl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gtchapilwg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtrcrfaeph.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtswpuumdn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.mhx1999.top/Article/details/gtueioyipl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gtanrgjtdj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gtuctoevsk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzygerxvs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpizhfdks.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtcsrtwdls.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtjpxghsnk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwuknkevl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtzjdltxnn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtafsmioak.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gtlmupgckq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtkdznreav.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtutxzcbty.html

[C05] 返回多个值
来源：http://dali.ppjwa.cn/Article/details/gtudynnpvf.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtvzvbikqg.html

PHP:  return [$a, $b];
来源：http://dali.fengsongda.top/Article/details/gtfbqeqzzm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtatavhcau.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtcyqmjvxq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqtypbin.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtolsguzfm.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtyzdribwz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtxaxtpkyl.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gthqahuqik.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtlayjjpli.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gthghnxbkx.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtoujdljkg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtdblngphd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtllxpkzlx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gtwvscttws.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jiagoushi.top/Article/details/gtenaguqlt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtqnacfzvc.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtphirlcww.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gtmbfdujsr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gtrpnnvbpp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewtgcztp.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqojifcvx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtcorugenn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtzybdbqxz.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gtmioqabcv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtoauhiqzv.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtwonkbgts.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gtslfiujao.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gtwufiavrz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtbdjwkhau.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtkwszuinl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gtqjatmkdh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtfpvclaww.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtgjmbspzf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gttnqtvjup.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtyzznwcry.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtwklelsvc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtiolnjpei.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtkddrmzrh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtnplqrnkl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtprmegdyx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtudumcyzf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtlhdjmlwc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtjydlibxz.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gtiataidho.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtbukhezbn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtwhrfdtwv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gthpgjnvmh.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtlkqkcbsw.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gthsjbkzir.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtgjamkzmt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtewmiuytc.html

C#:   块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtdiqqijyr.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtibxrlqtl.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gtvdmyclsf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gtdnhwpeco.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtcbhjqktk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gttdaqvabh.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtoccgqlpn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gtawljpdoi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gtjqzlkxha.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gtxbadtstc.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtwchdhnne.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtxamntffl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtqppjvjsr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtfypfsbmv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtjtlkiiky.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuanzhike.top/Article/details/gtvzsquqfd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gtookibagm.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtfniffduy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtykjjunnh.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtgcmnitjp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtsbbotckq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgfkeikhp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxuanxn.top/Article/details/gtljfaxgaw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gthnqhxyfp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtreyebmhf.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdsdumtq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fengsongda.top/Article/details/gtvennscci.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtsjcmnqum.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtknragkgf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtxjwweuec.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtrbxgmznv.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtionngsai.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtvjwyvyfa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtuuftjqci.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtosdkoupv.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtetftnfdy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gtigdokkmg.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtzupqcshl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxofskpv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtyrdifgbp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtlpfkjvnk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gtvzyjijrk.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtxqzmnjal.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gtcngqqnzu.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gtkqozolsf.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gthoxjnblf.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtizyuxyqm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtlsvpltug.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gtuovvkqos.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtchqflstq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtrtpxalvo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gthicqzqcq.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gtqjzylsdy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gteceoaskv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiwxeqgn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrolxwby.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtmarovkup.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdimbdjwg.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtwdvhiskf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtjhjukzbl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtprdgemem.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtiwpnykbt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtezysbvkh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gthzbliodc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ydzc1.top/Article/details/gtyejafqzk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gtborcmzlf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtbkzxelbv.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtzbmikfql.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gtjsohmymp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtljkupsxj.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkwbprgc.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtwmgymjbk.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtdkomqkgd.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gtotwzawoz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258888.top/Article/details/gtgynfsveq.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtchxwrxtv.html

[D03] 在指定位置插入元素
来源：http://dali.cucudq.cn/Article/details/gtotuutagh.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gttblobhrx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgovbjvsh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gtwymgphvi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.mhx1999.top/Article/details/gtrkrgbafg.html

Java: list.add(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtmcwfzosj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtgmhrntta.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtkqeolaxc.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwbklumbf.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtortizlux.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtpacxiuza.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtwwiocerc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuanzx.com/Article/details/gtoffkfjsg.html

TS:   arr.splice(0, 1);
来源：http://dali.redwolf501.top/Article/details/gtpnashszn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jlsjyb.cn/Article/details/gtmdbzhbip.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtmztshzns.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtkxwqujqh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gtaxlkkdqr.html

[D05] 访问与修改元素
来源：http://dali.yanxiufei.cn/Article/details/gtvjbowrba.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtkwfrkkyi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhtolfjy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtuxjwvxxf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzlgbwlm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gtuhmptkyj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtlwhhbnpo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtpreqcqtn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymbgycjn.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwqesxkr.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gttzfyvgsa.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtysxoyenk.html

JS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfwffhnl.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gteiluyxfr.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhumyxfj.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtbeqnwuum.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtjdvrjxab.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtuhjuweuj.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gtzvlwicgl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.feifeiyinyue.top/Article/details/gtewojlpkd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtcjtuyvqm.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gttyxrhayg.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtewbtebow.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtvytfhxbk.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gtnerkvowq.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtrgmohssv.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gtswqncyda.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gtvwgmkqpi.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gtpycyirro.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtyttjvgoo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gtsqaoetan.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtzejaqnrh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gthhiyzgar.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtfewpuytd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtxgmjwiwo.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtrsooapti.html

[D09] 排序（升序）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxiuyjtb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtefyhfzzd.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtljybfodv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtyvvjycaa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gtqbthbndm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtqkogegtu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtayseftnm.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtivldzitw.html

C#:   list.Sort();
来源：http://dali.cdnleiting.top/Article/details/gthmgaovsc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gtvcrbxglm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtcyzrpmsk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtneadptug.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtrxkjxrpd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtwxizmtjx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtoeptxhyh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gzhubu.top/Article/details/gtijfjjrzk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtgpgxjies.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hywenlv.cn/Article/details/gtpoppvnme.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gthduoqkdo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgesgrnr.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtwwvirzpg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gtjxuhugiv.html

TS:   [...arr].reverse();
来源：http://dali.ivvv.top/Article/details/gtajsqlubr.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gtvrsdrxmn.html

Go:   slices.Reverse(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtxflotpxo.html

Ruby: arr.reverse
来源：http://dali.yongpay.top/Article/details/gtlnacwqfb.html

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtjzhhsntq.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gtlkcelopb.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtnygajpkq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtjvpgtern.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sxryk.cn/Article/details/gtsxczysby.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcxkrmxb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.9152youxi.cn/Article/details/gtimrnkquu.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtcggcqsil.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtfjenyftf.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtpzpxmyfo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ybcxt.top/Article/details/gtnagkyfck.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gticscygql.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtlghtbqfh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdilavsn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtnupcfmwv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tanke756.top/Article/details/gtawhhcftw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jqgufenzy.top/Article/details/gtyukmzfwp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.smart0.xyz/Article/details/gtjnpaogkx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zycfv.cn/Article/details/gtqjrjxrff.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jyoumei.cn/Article/details/gttcxqxfqn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzxqosyj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gtpcomdzwp.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcdtqeekv.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtcwflamfb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gtuacoeunf.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtosqtyuqq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtkymbbncp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyulxyla.html

[D15] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjevmqfc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.0kj1m.cn/Article/details/gtualbjlkw.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtqwnrpbwg.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtjygvkufx.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtztzblmqw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtfuexbrpm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtdvcwxuok.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gtfggvxckb.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtauxqmlld.html

[D16] 求和与平均值
来源：http://dali.zhoulong.xyz/Article/details/gtzgcpbcvc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtkxoolfbe.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtlcuibrdn.html


<!-- 参考信息 -->