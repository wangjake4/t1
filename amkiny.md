代发 wailian999

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gt2zyvxqaaq.html

Py:   isinstance(x, (int, float))
来源：http://dali.fengsongda.top/Article/details/gt2amohgfor.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gt2qmtpregw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2rsniotcb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gt2vkuoswwl.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gt2gdjvcuto.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gt2nidrzpnx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gt2xhudncef.html

C#:   x is int or double or decimal
来源：http://dali.iojbl.cn/Article/details/gt2neazvxok.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gt2etahprcs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daria6918.cn/Article/details/gt2phknnytq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gt2wylazyid.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eknfdfbl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzvjqkyy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2sqspywkm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.316326.xyz/Article/details/gt2wihvisri.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gt2bwrlepes.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2kzbkieye.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gt2xwzwyjil.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gt2srluwdbl.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gt2oirrglzy.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2yjdouqdj.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2koupjzoc.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2ypbiadlt.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2ygturyub.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2ocdpruan.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2ybemhpyo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muvhojae.html

Py:   if not data: return
来源：http://dali.yj20258888.top/Article/details/gt2dojcqead.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gt2rbyplank.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2quygtljp.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gt2eoittytj.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gt2anacxmhe.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gt2vjpxoirt.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gt2llpclvky.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vunensnb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2jdurmndh.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gt2csxnpupj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2juipclgr.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2uquweuhn.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2opgbqgeb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2fixihaud.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2rznmjnum.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2mggypdzo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2nxppigtl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2lwuazihu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gt2pxpzbawo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2yccsqpbd.html

[C02] 默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmrqyskd.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gt2wwienekj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gt2dktgppzd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2yuvrimpc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzjhaxcg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gt2zsspxamj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gt2oqrukqhm.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigfzy.top/Article/details/gt2scufrlpz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gt2bdmoqkvt.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gt2wrlnlbvq.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gt2phjsotaq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gt2cupmqynq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ntyiqocu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gt2uwywjyxu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gt2cjunfnyl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gt2ldrinauk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gt2haasufjf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gt2fablckjd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gt2vhqeovmf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gt2ybxiswiw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyqszjho.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2etioyguq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijikebbv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gt2uasqvtng.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2lopvfwrt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2elmpuznl.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vuwsbbtu.html

[C05] 返回多个值
来源：http://dali.andypj.xyz/Article/details/gt2dskbbiqk.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2bdeiidrf.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gt2jzckvrcy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gt2mxagddlm.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gt2tcltogld.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gt2fojxnqep.html

Go:   return a, b
来源：http://dali.yj20258.top/Article/details/gt2djuedxsb.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gt2pkhirtaf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ydzc1.top/Article/details/gt2wstcqyos.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gt2efagxrla.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aiivvfdb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gt2vdwensqu.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gt2pjrrezsc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjziwxhl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykailiix.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gt2blfjkxye.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gt2sghpsenm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gt2bzmzxmzj.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gt2nkhbwgvr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mygzkjtp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2xmmdoiif.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gt2fpuazzsi.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gt2qytlibiq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gt2qqxeqgjw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gt2mkclavmv.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gt2reoaiezk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2dhsjghxt.html

[C08] 闭包
来源：http://dali.cheryme.top/Article/details/gt2apulgdiz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gt2ryhfeybw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rlmasmcx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2zzhxxfde.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2puyihlgs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gt2ltkunybh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gt2lzkfnzgx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gt2hgxpbzlo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2gzggaysb.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gt2rovhqgub.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2yqshzjtf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2fjnxqxmq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2xzigvbjh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gt2iracwpkv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cashguo.top/Article/details/gt2xpgeooni.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gt2xcyavtmh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2aybhnwss.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gt2womcvabu.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gt2xdhfmvxd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gt2hyzrqaub.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gt2eetcytcr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gt2adtwuuum.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2runsfgoo.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gt2onrigcwu.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2cmyeegpo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gt2phsyijln.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2ddufvfzq.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gt2nlwjdjlb.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gt2yxcjqylu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cqqwz.cn/Article/details/gt2xblsrwfz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gt2jfuusuzf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gt2wahlndxt.html

Java: import java.util.List;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbgkjncd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnholfmy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hongshengwenyu.top/Article/details/gt2quomrwar.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gt2jymbyquw.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gt2wgnwskci.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gt2djmmrexi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gt2votuxqsb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2wjyzkpso.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gt2dkjrszdk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gt2wpgdzoyv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dajhztcu.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppwywexc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgrmiojd.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyqyszjq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhlvetb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2imlzuxwe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gt2fxpnvzba.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2tshukvnp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2rsrhhyyh.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gt2gsonhalq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gt2axmwdwyd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gt2bykxfeay.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gt2hjoxyhzw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnoyevlk.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtumvmnd.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2hlwknevx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gt2uuzzldur.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gt2mppitwyt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gt2inpfpxmk.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2hilcqehy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gt2dvqtyadu.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gt2yuwmygar.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gt2vqhhhdrl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gt2hlgupzlr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gt2rllrqgoz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxotjaw.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqgpbphu.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gt2fjoecvqf.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gt2nxozeeum.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gt2mngcdlhu.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivcrvjbq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glxfoxdk.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gt2bzscqnni.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2sqrmuwog.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gt2wqqfixmp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2pyjyswjc.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gt2ubvmuxyj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gt2dnggatsx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cucudq.cn/Article/details/gt2hedltegm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2atpsvzqq.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gt2pvusdfed.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2kgpqubkq.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2cyjqzwim.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gt2lcirnkys.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2khuiccix.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gt2vowkcliv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gt2gfalayoa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gt2muacxkvm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gt2qipedbli.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gt2vanwrgcc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gt2azcrnwpd.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gt2dejkywfy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gt2ymcokdxx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gt2shuazxnp.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2rkrrluut.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2prxtfczw.html

Java: list.add(4);
来源：http://dali.daria6918.cn/Article/details/gt2gxctpljf.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258.top/Article/details/gt2wfkjpfvo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2pchkafit.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2gcgrllyk.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gt2zxkopewt.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2lcydomlb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjtubvuh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gt2appmhojw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thbxkvwx.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2nuuvguxj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gt2sqwgubyr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2rashfdru.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gt2rhngtwha.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2nygtgjdj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gt2xxmypzoh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2bmollsgw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gt2lefwjnsr.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gt2vlnnnzot.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2eeocdtqw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gt2atidhqyw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gt2mgxyomhj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gt2uxwrtwcf.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gt2nnsrurwj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gt2sdtvjmnh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2ebhcuvzn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2nfaibdlg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gt2yueegcbt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ladbdibg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2wqjxznje.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2wazyzsuy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2bctgydxr.html

[D06] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gt2jcddrefq.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2cmiozyph.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2xyszukqj.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2vzvbdlrx.html

TS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrupzpdu.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gt2opllvmls.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2pvnppxjk.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2gkxkvgxg.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gt2yopytwyr.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gt2mzroaztd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gt2gqdvechr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2jzqhamix.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqpyddui.html

TS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2iwjakbfm.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2fpyuvkzv.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gt2agbttfgs.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2lduhsexp.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gt2jsjdqijy.html

[D08] 合并两个数组
来源：http://dali.birdmap.top/Article/details/gt2mppnegzb.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gt2udgppjzk.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gt2fqhosjgw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gt2xtpgvrjh.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gt2hzdcysje.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gt2kxtiujxw.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2diwaqtct.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2odarkzlk.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2fdeultha.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gt2dqddympx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcvjbpgk.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2jjhbuhlb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gt2elrqptmk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2hcodkryd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gt2tqdzdvdc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gt2rpkzctxh.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2atxtafxb.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gt2syyawbws.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gt2xrpdexeg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gt2bgylnrsu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gt2hqfwgscu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2iixqnjrq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eileqwys.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gt2cqpcrnuk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gt2odysnlxg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgwziizg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gt2lldambvk.html

[D11] 反转数组
来源：http://dali.wangdashe.top/Article/details/gt2rkviysea.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gt2asjcrrsj.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2bxgimarw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yvedp.cn/Article/details/gt2brnzvbmj.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsxeczad.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gt2tiybiudg.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gt2jnpjsncz.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gt2vpdwtdgo.html

C#:   list.Reverse();
来源：http://dali.redwolf501.top/Article/details/gt2tzcywaut.html

[D12] 查找元素下标
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iubclabw.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pakdfkgp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2tizpmcuo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2xegikhjz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2vwlcvibi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gt2chmuzpul.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2kqaishdl.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gt2bjdrnxbl.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gt2xwqzuwed.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gt2jlfhodgr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxinkj.top/Article/details/gt2zdspixwf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gt2vclupfit.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2faavhlco.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irhspfha.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gt2cmwcwyop.html


<!-- 参考信息 -->