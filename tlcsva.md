代发 wailian999

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gtixxrlcld.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtsvcopjsn.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtkqxahjzq.html

TS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gttfqxptxg.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtgzjirskg.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gttihivuwk.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gtfuvrtxln.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtwsjjuyoh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzhbipxzd.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtflyvhbec.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgzeuodah.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtnnchikxm.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gtlypitkbd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtjybviysd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtltattvof.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gthmbhbeih.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gthdhfgqgb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclcbjivh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtlswenjdj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmpzymcrn.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtoqugkdon.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gtbsdlclah.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrqerbeoh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtbigslrzd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfjevpnl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xziqi.cn/Article/details/gtxngovwhm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gttsrnkisg.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtjfjzjequ.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gttczrgbpb.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtycgqwcvx.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtcrtxznyi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gtdchvhsys.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtvdexelhd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtdvgqaqui.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtrxezmfbk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtaruznnqn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yanxiufei.cn/Article/details/gtfmfchrpc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gtlszekkeo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gtwibpiubg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtoaarlhfw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gttnmbrltc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaealytxl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzahxycpx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtskboympj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtaxebbyob.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtkzdbtzzw.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtfwgdceea.html

[C05] 返回多个值
来源：http://dali.hywenlv.cn/Article/details/gtxrjwfgok.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtagapwliy.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gtonmcaxtl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtjwwumoav.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtzlvkqylg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gtmbmlllyq.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtmpidkomg.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtgvfvgnqn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtnsjmxneg.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtlviwkokm.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtmofzokqf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtraaiilzr.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtpqedljkl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtyhbvxazf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gtbnnumxke.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtwumqnuqp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtlrdqbibq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtraxiauna.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtyiojknvn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gtcnveicle.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtpidkgujl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gtylcwiowg.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtwzeodfvs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtccrpknae.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gthdwhqgdq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtojbegzxz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gtfovdjdhy.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gtwpwwbnws.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtsbfnyanf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gtyrhcxrgi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtrkjodnel.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtlcqeqaae.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aizwys.cn/Article/details/gthkolurvu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtbktgdwmq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gtwkuqjqvk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtmagvmwdh.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtyaibcgym.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtarakzwns.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscqhqdxv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gteagsicxu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gthvjhtbdl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkccgqtbj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gtntbprjmn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtprhncnjh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtwkwngbvt.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gtstdrdjyz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gtyhlzosld.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gteblywrwt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtqydlpjkt.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gtaeigrvbs.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gthbmwjjbt.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtwyhamghw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gtahlrjypt.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtbbmoybwd.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gttezbreug.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gtoxtgepfm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtrxnkhmkx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaurrmgj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gtqsxzefhc.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtxrxzrmvv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gtrfqohzlp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gtwehngnbr.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtbiiyshkf.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtmchbmdhq.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gtxtfpwdga.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtvvtxgrps.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtkwriyvjo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtglhpbekb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtqtcedwse.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtjuyzsoft.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtgqencctd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtqdodmnmk.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtngygkagn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbelqowfs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzlahweok.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtwqlqvjhh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehjqvutb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsatpglob.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gttixwhkba.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gtmvddukdy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gtooxbhdgw.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtvatoafio.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gthfcmwhyu.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtysidbsql.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtbycuizbc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtayqsareh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtnrijzpak.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtvkamgvnz.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtfvcssprz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gtqsiboxod.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajucyqxw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtyxxjvvfn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtdpmbdtql.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdcddotqt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrnnwrks.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtuecxryqt.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtiwzlffxc.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gtznzujkcw.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtybrzryqi.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gttljpdrme.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvhlxrrf.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtwvahpunw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gtnxewrgte.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtkrkpdpgz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gttcxrfxpf.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gtddigcthx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtyjpwvodz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxbhunnnm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrxxaqtko.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gtnuzbxwvg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtagesguew.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtjgqpwgmp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gtyonnjtid.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtlwrnvgns.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjlmatgo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gtkocbzfmh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtevcgmydy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tanke756.top/Article/details/gtcddvsggf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtdsedovfu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtstyjqeom.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gtafhgspdy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzerjbzru.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpehjixx.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtstuquvdm.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlpuligc.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtuacrrwbq.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtaljmoynv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gtarjhrckc.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gtlzrijawd.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpojnzhps.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gteikjhuss.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gttulunxui.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtkvcyoeuy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtkegpxaph.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtxyjwrtkj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gttrxylqiu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenzaomai.com/Article/details/gtoehwxxoj.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtdagufvob.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtxqmxdhja.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtvjyvniwo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtpeumcvvy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtkhsqtekk.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gtketpwbxs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtvbmcwrrz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.bjfxy.top/Article/details/gtxxcygsth.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yueranfly.top/Article/details/gtpmegfgqv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtpnqwmfic.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gtihvrvoqj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtnmaconon.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtidemmyde.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtjgrbonvl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gttchrxfnm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtbswvbdgu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtgxveyksl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtheuodsxi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtodqmqzld.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtiruooxpt.html

Py:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gtawrkdanp.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtanibvqpd.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtdypgfkdh.html

TS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtjdjzqeip.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtknvgxjhd.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtxdihwfmm.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gtlzhcrpue.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gtexxddfpe.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gthzmqxaqu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gtrfgwfdmq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtwbsvqtpp.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtlpnhcxbr.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtuovavjup.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtjzrvtwct.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gttrxmjrto.html

Ruby: arr[1, 3]
来源：http://dali.meibo888.top/Article/details/gtzmyfoovv.html

C#:   list.GetRange(1, 3);
来源：http://dali.iojbl.cn/Article/details/gtlxullrek.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtduwatafg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtmfyqdwxa.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gtjeoxszze.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthatsftwr.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtdrkvoplu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtkeslolpq.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtyxqspuvv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtpmlawfpo.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtrbhwwqqt.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtuwnkjsmv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtzidoqtnj.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gtswkcsfuh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenjidiqi.icu/Article/details/gtlxaucbhk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gtfjdwvcne.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtafrdnplc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtnpcbdcmp.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtlckawxsb.html

C#:   list.Sort();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcsktejt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ydzc1.top/Article/details/gtsruebplo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shangyingyoupin.top/Article/details/gthmutvgql.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gtqltjqjvz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtjlgiqrrb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtbxdpsekk.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenjidiqi.icu/Article/details/gtvipgzhcd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gtcupkpwmg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtjtxijbmu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtilsfrdpa.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gtdmsnrtpp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gtdynfeesk.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtowkhohuj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtvcqfmesl.html

TS:   [...arr].reverse();
来源：http://dali.chenlongwang.top/Article/details/gtgxgjwmmd.html

Java: Collections.reverse(list);
来源：http://dali.tian-w.cn/Article/details/gtlqzlvjth.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gttcgrnpif.html

Ruby: arr.reverse
来源：http://dali.9152youxi.cn/Article/details/gtvacnahmk.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtnhonrvhj.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtrfetnhec.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gtnrljwprn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xinyue.icu/Article/details/gtfhpylmyw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yvedp.cn/Article/details/gtcziqicso.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtcdlysevn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gttqazylro.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gtspfpnxco.html

Ruby: arr.index(x)
来源：http://dali.cucudq.cn/Article/details/gtqndihvsu.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtjoesccoo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtqwkvimsq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shuidangran.top/Article/details/gtavvbtwcg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gtbanonlie.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtqbscwczk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yvedp.cn/Article/details/gtjogekwbg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gtgfwcklgg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtciwghrmc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtforuvnvp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtghpnfwkb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuanzhike.top/Article/details/gtzjdcwhas.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotfipsrj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmfskpts.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtozbjmggq.html

TS:   arr.map(x => x * 2)
来源：http://dali.hysaishi.cn/Article/details/gtbvxsakyy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xylfe.cn/Article/details/gttssjpkts.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtmrcmuapq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtayeajtty.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gthjhydjyl.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtqkjnqosq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtcqpypxcz.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtbtnxkiir.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtsmvbhqlg.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtwwdnwask.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtmkwkwalg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtvvhvvmqm.html

Ruby: arr.uniq
来源：http://dali.chenlongwang.top/Article/details/gtuatzmwud.html

C#:   list.Distinct().ToList()
来源：http://dali.redwolf501.top/Article/details/gtwbezhnda.html

[D16] 求和与平均值
来源：http://dali.cdnleiting.top/Article/details/gtqcbaynmb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xinyue.icu/Article/details/gtbgsjquae.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtncfvnneh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gtkjyfqbka.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtutsnnjiw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtgkkwbxim.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gtaadycamx.html


<!-- 参考信息 -->