代发 wailian999

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gt2tagtkhxr.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gt2vsrjiuqr.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gt2rriuzrag.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2rmvjhmbi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gt2kgxucdjh.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gt2dczelquc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkfxzpug.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gt2wstlmfvs.html

C#:   x is int or double or decimal
来源：http://dali.snrcjt.cn/Article/details/gt2umbrjzrk.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gt2jkxisupz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gt2uiwjrhmw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gt2nxoruvyv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2dflxbdlq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2tnhmcnrd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gt2yraddumx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvbjtqrp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gt2lahkldip.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2amyijerr.html

[B15] 布尔运算与取反
来源：http://dali.vqdsnc.cn/Article/details/gt2gdsxphii.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gt2alwqswvg.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gt2blcbukng.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2ledibuvv.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2oreklkoc.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2kdzugref.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2ezxllpce.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2kubbienw.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2difziqxd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gt2vzckyoxz.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gt2zpusprxw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhxcqlyj.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gt2vxqktpax.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgxemsqw.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gt2kyrrffqz.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gt2xfrekkyy.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gt2rhqmawjj.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gt2zbcdvmmv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nruitaqj.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gt2qlewfzoy.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2anghgczi.html

[C01] 定义函数
来源：http://dali.hnqzz.top/Article/details/gt2rudcwwfw.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gt2ogcgoilt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gt2kbjenglx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vauobxum.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2txvrwxas.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2eshnjzzx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljoqtbaj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gt2eutpkjju.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2wwqzdbwq.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2ovvvmiqu.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gt2gvfxehcu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gt2hfrfldwe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2nmciphex.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2tcevkvfk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gt2qohyuupc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gt2bpqwrqsq.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gt2dgymbzrm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlekrjh.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gt2vqsarvxw.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fusvpyte.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gt2gxyyveku.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gt2hrfnuwrp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2ygahtjfo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmdpxgmy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxuanxn.top/Article/details/gt2hrdgorrm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gt2nuqjlhdc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gt2rvlvtzwp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2bfinnwue.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gt2nsgmkkmu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gt2ckhxpmlf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2jtzeblcq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gt2qxwsqrfr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gt2kiphjtkj.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuanzhike.top/Article/details/gt2wdmrfjqf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2qrlvaxrp.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhmavcc.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gt2cdlmgqjf.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2awykfjtj.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynuitqyi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2slsctncz.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2epqbdxst.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gt2yjvxdrzp.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gt2sqfslkix.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gt2rfnathae.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gt2lucllckb.html

[C06] 匿名函数 / lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2wahmcjwv.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gt2tajjnmbr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gt2iwxtrxrd.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2bifjpbqs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqqbbfhz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrdvdsxg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gt2qiztgjiy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zdqjudy.top/Article/details/gt2gliqshnz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2mmiyptpz.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gt2bfwnpqjp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gt2laarlxpp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gt2tlhcjtkz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gt2ukogmokf.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmtyphcq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gt2axekjrzx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gt2xskhzobz.html

Ruby: arr.map(&:upcase)
来源：http://dali.gogol.net.cn/Article/details/gt2zheilomb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gt2vbsskkoe.html

[C08] 闭包
来源：http://dali.yongpay.top/Article/details/gt2vnbcjpre.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gt2xzilpoid.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gt2eedaebuu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2zskbduyd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2muqiqpyq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gt2xlxzmyse.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kjmsndwz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2yqlhvsnm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2pvnjsmhz.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2iwklnrvk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gt2wdodjqib.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2vbwyzpct.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gt2vzppcwdr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2ydjdppht.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2qrrhtyce.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gt2rbsxcogb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2mnlibews.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gt2ojmijwaa.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gt2jqrwjgmo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gt2wgneartj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gt2pcsmzyjo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gt2nfbtpobh.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gt2kergufjl.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2zoazmjnk.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2rgxfklhr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2erifjclg.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brgbphut.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqvfuhwv.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gt2yshwcptm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gt2nhhdngor.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2qxmekapm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gt2onxbveib.html

Java: import java.util.List;
来源：http://dali.cqqwz.cn/Article/details/gt2pandwuli.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gt2belmuoel.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gt2ecntitmz.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gt2kfpnclft.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gt2hywjbmzu.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gt2amwwrvlf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gt2tkdihwcz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2zmxzilhz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysvcuihq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gt2smlyuqup.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gt2rhoevysd.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gt2mcxryiph.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gt2ipehjmph.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gt2xmgumyay.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gt2rmyrkcai.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2pltibzmm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgucqzgu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfiryrkt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2gcwtmluj.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gt2jozhecjt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gt2tpnrayvh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.haohaochexian.top/Article/details/gt2boppuwtw.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gt2spsxtkwy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gt2bozhnvvx.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2assbinxf.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2iroxrvwf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gt2aamowkxi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gt2tztyvjpi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gt2mjnhuuax.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2ozvmfwap.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gt2tuahhfev.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gt2bscvxvap.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gt2wxtnghtb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gt2qjysxncp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2ukayghnf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gt2gdagjzcc.html

Java: // 无解构
来源：http://dali.dashuyun.cn/Article/details/gt2brzmduya.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcmllitx.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjeotgau.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gt2oinufvao.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gt2foavakts.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gt2csscoxge.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gt2qtdcsxhy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnmyxkcn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gt2qglxvscc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2eakpuyry.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gt2cegfexui.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gt2ruojpxnj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kutlxfeb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pewgoeod.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gt2efyeeqwp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2epobofgd.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2wsctdbac.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gt2gpqjumoi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2jhxrieqf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gt2tnoqbswu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gt2aiecpoob.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gt2wjsmlpcp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gt2jnmccuqo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2jnwnzjrc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gt2zfrketsb.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gt2anoohflc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdrwiaab.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2zehlcjmm.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2kzpvahbr.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gt2xblakjyt.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrlztrnj.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gt2gtupxcbl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gt2sogqzqcx.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nresktgn.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gt2sujksgyi.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2qbrdaitz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gt2wiqjhzla.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gt2ppgtwtmp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gt2qdttmggt.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2sywnmdpe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuecdoqs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuhkayxz.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2snvqtcjf.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gt2quobkqmk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gt2xhyipwkq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2cfkwghkh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gt2yhnykfth.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2noafcxgf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2lkrmebxu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gt2foigdnub.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2ljxiyjxi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gt2jfhdugwx.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gt2clvvsnxm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2twalmufn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyscfihj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2uowvcbbc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gt2ggisgwak.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gt2yzfesisp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2ghksfjzf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2tnceudio.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2lalnkwhr.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhnmfwmp.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2kboziqun.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gt2cponpygh.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gt2aaqkexvr.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gt2ymnkepju.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2kszqdhql.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2ncluszqx.html

Ruby: arr.length; arr.size
来源：http://dali.yuanzhike.top/Article/details/gt2lnbwespf.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gt2ojphfsbc.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gt2wbrkxdcz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gt2fbhqxjkn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gt2flshryoh.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2yibjgaxd.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2xulnyxjn.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2uxbgvqsy.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2xcwlpmip.html

Ruby: arr[1, 3]
来源：http://dali.tian-w.cn/Article/details/gt2wqotcizp.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gt2qistvapv.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejyzfxjz.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gt2qjcuocil.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gt2sdrgrapg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brrftohx.html

TS:   [...a, ...b];
来源：http://dali.shzxlz.cn/Article/details/gt2iphzriiy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2ijnkkyzm.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gt2oxoisooq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2sanqiqbt.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2wnnicvis.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gt2cbzyskqn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddqvweqk.html

PHP:  sort($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjusygtu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gt2sarqjbfi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.feifeiyinyue.top/Article/details/gt2noeedwch.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gt2bjhrckzg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2aldprtmx.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2xolnsiuq.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohnsfkdk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.snrcjt.cn/Article/details/gt2bhvxwrlg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2cfxrgijv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2leijnihr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2aeerrylv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2kuuggcro.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gt2yhgogucq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gt2wvrzngtj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gt2rihhcgbl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daria6918.cn/Article/details/gt2hjvgimuo.html

[D11] 反转数组
来源：http://dali.cashguo.top/Article/details/gt2otmuraus.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hfpthk.cn/Article/details/gt2omcgndin.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2aocpxppe.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gt2qilafkzf.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gt2amgznufe.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gt2hkkzfxpc.html

Go:   slices.Reverse(arr)
来源：http://dali.ivvv.top/Article/details/gt2maylvizs.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2ksxwdaey.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gt2oeiqpgsd.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gt2zvdvupxs.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gt2rcpevnev.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2ntqobjdk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2jyjckcqq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2gzyrkjtp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtzixaoe.html

Go:   slices.Index(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2nwaeqmjj.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2oufntvyd.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gt2zgxqflmo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gt2eppfqhbw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gt2eumubkam.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daxiang520.top/Article/details/gt2bjxnrzdg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2gkvsgzuj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gt2qysqtxpx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkcpkwio.html


<!-- 参考信息 -->