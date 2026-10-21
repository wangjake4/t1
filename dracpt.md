代发 wailian999

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtsyhgjkpn.html

Ruby: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtzjngbpyf.html

C#:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtoahuhkfq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsphwvso.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gteplfcncj.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gthyzscpdb.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtuwnpmcgo.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtgzhezacf.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtmhsvmtcj.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtlvtysquz.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gtcdbyehbi.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtlfwkmrdv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiicztsi.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtowwqjfxw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtixmexkdd.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtuaegcqaw.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gtujennugk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtzdrhuedn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtputbkvqc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtqkadyeiz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gthgmhjbas.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtpgjpsemn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yongpay.top/Article/details/gtoqvrllkn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtyoguwvdx.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtbdagubba.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gtfqjohblb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtyisxmtcc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtuumvydpb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdhwqryou.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtuwovkezg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gtisdukglp.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtnwfiqbcx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxinkj.top/Article/details/gthfrjfjzh.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gtuijelhby.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpcpsijr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtwbddujlb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtswoztdkk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtghhxchwv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gtpsmlzxdx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtiqhkbwwf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtxposodcu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtjrzenium.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtxcgsarhh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtkbulgenl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gttkqfiwsg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gteoubqhso.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtscojvnfe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtuelsujvj.html

Go:   // 无：用配置结构体参数
来源：http://dali.pycfn.com/Article/details/gtqllarlqq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtlatxusrc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaurjjug.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gthrzbkobg.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtrgwvjlbl.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtaqpndocn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtmajgipzb.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtpshmjzyb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtbepchnrx.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtfrqylyzj.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtidhjwkuf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gttczuirha.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtedgnzbwc.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtzugrwcfa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtcpkufetp.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtwfuvmzqo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtppjbymyf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtxmnsexvw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtwlksjiiq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtvpfpaiqr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtixchbken.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gtputxfvde.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gteavsfwym.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtevqpdjga.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gtldgblrly.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gtokdjilza.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gtbjhstomb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtyipkpdhy.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtyoztwujm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtdcgljrjo.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtdoxwyehd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gtbtjzsiio.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gtdmdkkimb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtlbowywjo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtorptkfjn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtfixuffnu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gthugddamq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtgexpkghx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtfyujsltt.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gtajratlyk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtutjeiifw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrjcqvqcb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtbgoactqo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpqvutld.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlwqczmcn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.quarkkingdee.top/Article/details/gtonypytaa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtovnkdvdn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtnpjsaehb.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gthmjqqvhk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzzaqghx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtmydexbdv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtoqimimrv.html

TS:   同 JS
来源：http://dali.cashguo.top/Article/details/gtfirxdwhj.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtbkloeutw.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtaahclftk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gtovrrroro.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtyzehecdc.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtzopzffjm.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gthjlezjif.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtyttxxhbt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtfsviggfi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gtnhbrbkyq.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gtruiydmcx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtdpxrvpbr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtapmrmhly.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcgqkosk.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gtsfqyktnb.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtdyynwigp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtiqbbtkze.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtpjaeeiap.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtbqualrbh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtyykcdltl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gtigfzmkrr.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gtdycyncee.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtvbmkujrt.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtqvksnbuk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtvofcqoee.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gttexdoahl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtkrqquqyw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtsjpsbufm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtxajppwvb.html

Go:   func add(a, b int) int
来源：http://dali.316326.xyz/Article/details/gtpwacoslg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gthlvewbwl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sufxvd.cn/Article/details/gtsmlwfzuo.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gtrpblpgfh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtsmgzkejv.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfuoybjc.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtdjjbxmfc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcebutcev.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtnbzipvqk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtigxdvtgm.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtjopgmpda.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtrcjixefx.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtsxogsejc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnacpykae.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gtluiysqnh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtppjneoul.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuanzhike.top/Article/details/gtsepidclm.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gtbkwjddtq.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gtuklxgtxz.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtgnvxczrj.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gtutvnftge.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtukpajuov.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gtixphyxoq.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gtaxsvmzlb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gtweqiroxu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtcxognvnw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcgybeqbp.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gtdoktivej.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtnbjlscae.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyqhyguxd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdiawoiaz.html

D. 数组 / 列表 / 集合
来源：http://dali.cashguo.top/Article/details/gtwuhkckuk.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyirosrka.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtglfexzzs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ivvv.top/Article/details/gtkypnrtuj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtqqtravgk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtkwlzudqq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gthurtjpwy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gtgdwwbixu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigfzy.top/Article/details/gtbmkbsorz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtlsskbuoh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtkyzgdkxr.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gtjdltwscb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtickuyfxu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gthnuiqeiz.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtumszgxpa.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtzkksooxk.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gteyzvrkcp.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gtylrrgsjs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aibaodan.cn/Article/details/gtohkruwoy.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtbqqrwmxz.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtvyxyllvn.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gtfjgsypug.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sufxvd.cn/Article/details/gtztienoyp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtrbyalpgb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtwdeqjgxc.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtpjznepts.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gtlupwqony.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gttciuavdp.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtfhmlxifu.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtftgzrjpz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtvpjiimsl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangdashe.top/Article/details/gtrihjbxcd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gttnugvdoi.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gtliuoqfyx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gtgsycfxra.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtggsumozs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtfiidoook.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtkgjxcpnr.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmrkhxmc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtujhrtrih.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtprujiygq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gteolwnkcn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtqjxjcale.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gtvvggpiyg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtjygrrfkv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gthbzetguq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmxfzzcj.html

[D06] 数组长度
来源：http://dali.havefunace.top/Article/details/gtzvosarwf.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtrkxysvja.html

PHP:  count($arr);
来源：http://dali.hfpthk.cn/Article/details/gtssokvsml.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtfehswklu.html

TS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtqzaphwzd.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtkadvtfpz.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtenxymycl.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtsczgpijx.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gtyinlsgwj.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtzaknvtso.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gtrtwrgbnl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gthexhixqc.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtdvzwedqz.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gtyqrwqkmq.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtzmqrmpbm.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtilbuxuhi.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtowobrbob.html

C#:   list.GetRange(1, 3);
来源：http://dali.gzhubu.top/Article/details/gtrdqzpyzg.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtswrvupgk.html

Py:   a + b;  a.extend(b)
来源：http://dali.gzhubu.top/Article/details/gtazjxnruv.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gtcdfjlgsg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gttvumxpjp.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtwjybjark.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtepxwevli.html

Go:   append(a, b...)
来源：http://dali.zhiwuduotai.top/Article/details/gtaxazlhrf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gtcqaatfve.html

C#:   a.Concat(b).ToList()
来源：http://dali.fzhhl.top/Article/details/gtkxeoqqkr.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gtfjkrdnrx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtadzzawbn.html

PHP:  sort($arr);
来源：http://dali.bjfxy.top/Article/details/gtlxylkqln.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gtxbfgsgor.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtpepqkprb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gtoewgrifm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gtotiwbacq.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtyeslyxmi.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gtuzhaxetl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gtdcvrgwgg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gtoicudkpe.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtiltiamsa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yonumen.top/Article/details/gtpwxxssfp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gtidonqfky.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gteodbpxhf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtgpxikacx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtcjfpaial.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gtrdfugumr.html

[D11] 反转数组
来源：http://dali.chenjidiqi.icu/Article/details/gtnrllzcab.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gtgwsplpzv.html

PHP:  array_reverse($arr);
来源：http://dali.aibaodan.cn/Article/details/gtrayxxhym.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hywenlv.cn/Article/details/gtrnbddjry.html

TS:   [...arr].reverse();
来源：http://dali.meibo888.top/Article/details/gtdqbnvrfl.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gtfbdzmncd.html

Go:   slices.Reverse(arr)
来源：http://dali.zdqjudy.top/Article/details/gtdgcnaupg.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtilydqoii.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtvdxweeig.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gttmjanlgu.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtizckhulx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtengpbmbq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.quarkkingdee.top/Article/details/gttqhcznhm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtqznwwfco.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkgcaovr.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtzllfljet.html

Ruby: arr.index(x)
来源：http://dali.jyoumei.cn/Article/details/gtwrbhueef.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtsadjyavv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrywghqv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtdjifevwp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtkqpokcyj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtlkzbeaxf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gtnkkyktmq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtsxsydjxm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtdhnkqusv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyxydxca.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtbryrseor.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfustdmaz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhengqikj.top/Article/details/gtzvkmwxcr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sysykeji.top/Article/details/gtyprjuhth.html

JS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtothedpub.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtmtxtlbql.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtmyjdlbgs.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtcpylkyzq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.316326.xyz/Article/details/gtpyodujrm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtatrnxkhy.html

[D15] 去重
来源：http://dali.iojbl.cn/Article/details/gtcdcskzgt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtsabbhfoc.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gtqvnhokvd.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtkdvbrdig.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtpbykrpex.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aizwys.cn/Article/details/gtuhfdeutq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258888.top/Article/details/gtkejxcvbe.html

Ruby: arr.uniq
来源：http://dali.svipenyu.cn/Article/details/gtjjgjfojy.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtokpycnjd.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtarrxorxr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xylfe.cn/Article/details/gtkwrnbffx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtczrvtvkr.html


<!-- 参考信息 -->