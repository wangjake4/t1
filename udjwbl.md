代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gt2rtixrbda.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gt2etxmibsu.html

[B11] 生成数字序列 / 区间
来源：http://dali.cashguo.top/Article/details/gt2cwgyzgah.html

Py:   list(range(0, 10, 2))
来源：http://dali.9152youxi.cn/Article/details/gt2pzzwfdqr.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gt2osykkozn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gt2xcesvhyl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2nfgesmlf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gt2otuywxyu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jiagoushi.top/Article/details/gt2lpqmqekp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zycfv.cn/Article/details/gt2gnisiwdl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tychlcwv.html

[B12] 跳出多层循环
来源：http://dali.guannengcc.top/Article/details/gt2rqbwtuae.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gt2tsochmlu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gt2zanxcaza.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvlmstcn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2jqqoevxx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntloxzej.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258.top/Article/details/gt2ymvzkobv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gt2hypcxuhx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gt2xbvpfjve.html

[B13] 判断是否为数字
来源：http://dali.tianlin.xyz/Article/details/gt2qauamzxl.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gt2vjnxowch.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gt2ijatrvrn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2feknoqno.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gt2sdbnscdn.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ackwuzsn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gt2helfwvyl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gt2yyilqxcy.html

C#:   x is int or double or decimal
来源：http://dali.aizwys.cn/Article/details/gt2dtphzusj.html

[B14] 判断值是否在集合内
来源：http://dali.daria6918.cn/Article/details/gt2nczzwhkb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gt2dgmeuzgv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gt2frouafmb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2izhhrtnm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gt2rvccgqor.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2ajjqlxal.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gt2hvktxbqx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkcgeyoc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jevmpiqb.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gt2qqifpxbq.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gt2tcabgfie.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gt2rlollqcz.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2lwmlbgos.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdtxifht.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2zvfrlkaw.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2nvpfvxcw.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2urcxzmvu.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2zbreokdh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gt2nlvlpmte.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gt2lwrouqxs.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gt2fqoiksxt.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2ryouodbu.html

TS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gt2mrbiolmb.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gt2oolgtzks.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gt2zlyqzfbu.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gt2kqnchraz.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gt2njjfviqf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2dajuppil.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyutzxoy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2oinuorbm.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gt2uggdrhqz.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gt2zbwzlxbe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gt2xdnfffsl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdbsflnj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqmfpxzi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2zeziuhlh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cheryme.top/Article/details/gt2lgjlkxyp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gt2atyeweyl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2iztdtmiu.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gt2kjeryehq.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gt2iakbarsn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gt2imjdcvqz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2xhhfgsra.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2ivugecvb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gt2bolepisj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gt2nrbebhhr.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wkbwmhyd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2lgtmmugz.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ymauqaio.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gt2jktruyrc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gt2dfytrrid.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2bxtvcovb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ekuwqczp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gt2znpvvvwe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gt2dynkyynl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gt2djtcgdet.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2qatjyyio.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2kmoqtpqn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvaqoqou.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gt2ulmbzzzm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2yjbdandp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gt2hqccnhll.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gt2vyhuzjto.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gt2ahvjwlrq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2jvvgwhfn.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2hibnivug.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gt2nzhqfomg.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2uceamavy.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gt2jeignfdw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzgyysmh.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2gnwrmkoi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtoepmpo.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2slkhvcvs.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2ugadkhod.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gt2vnqtfqyx.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gt2ywxgwawh.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gt2zcttxcln.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gt2ghkypuxc.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gt2dixgyelr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2zurtkgob.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gt2upeiohkc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gt2sbpvzqnd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2dqxfsoyb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2ygwazogc.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gt2ktoimhwe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avrceeco.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2nwocklbh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gt2cyawjokk.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gt2wzmnmauw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2xcwuyyrh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gt2ppysoaio.html

Ruby: arr.map(&:upcase)
来源：http://dali.0kj1m.cn/Article/details/gt2annyjbnp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gt2pxskesvf.html

[C08] 闭包
来源：http://dali.zhoulong.xyz/Article/details/gt2pebislbc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gt2rarpyehx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2khkuqben.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejaaxycn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2fzztobih.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gt2kvmrukta.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gt2qenfmant.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gt2orfadchk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2nbonjlow.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gt2uxahnwdz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2wlgjkodz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gt2kmzvmwbz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrxukxfr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gt2guzqijis.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2nkkaoxqq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gt2qkescelv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2xkjriztu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gt2dtpnziie.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2dbukseyf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gt2tdczrery.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gt2ijkhawjj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gt2mbgtmxgl.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2qqoayotm.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2rdavlsae.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gt2lyuyectw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmbklfkm.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2fftuhcud.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gt2nwbrdyam.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gt2hcvghzzc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gt2hngwefnc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2cbdmxwzm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gt2bwolbbhd.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gt2osahpgpq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jlsjyb.cn/Article/details/gt2pviiznlw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gt2gxanscwv.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gt2rlwyhplj.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gt2hqoewtcl.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gt2xipoalyg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gt2mqwgaxwf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2muaxmeqv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2tupltada.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gt2lhtvtiwp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gt2qtjjutzw.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gt2popetpnu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gt2jfcmpqem.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gt2yyztltry.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gt2jwuscmim.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afessveq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gt2omjvwrqb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2qneduuce.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2ywplhzkt.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzwsbfuv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gt2ncumaomr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gt2bpsahacm.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gt2gtqdrbfy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gt2knnqkfxw.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2nredfmfm.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2voqouxgl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtkuufqz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zypjrbcw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gt2nmbylwpr.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gt2fouaezhy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gt2ergseask.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gt2tujwdtir.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gt2yofrkxfr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2gzvdknxy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2qcogrcuy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qfdgnniq.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2rfsnqlsf.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2bplrkxlm.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gt2zprsrdzh.html

C#:   var (a, b) = pair;
来源：http://dali.yonumen.top/Article/details/gt2lnxbopku.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gt2zvpqnrxf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gt2cbvsvlyx.html

PHP:  // 无重载
来源：http://dali.iojbl.cn/Article/details/gt2ycxmhnge.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gt2vxkoafow.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gt2jkcixecv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gt2dmhyioiu.html

Go:   // 无重载：用不同函数名
来源：http://dali.zycfv.cn/Article/details/gt2ssgxnkjl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cashguo.top/Article/details/gt2vlzvcaac.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gt2asiviuai.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2mazxbmac.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gt2gjpbhbuy.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2yvedrrry.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2voziiqxh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2rjeujvkp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2czhmwrnf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2nquaiffu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gt2cjklnwuu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiwlvme.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gt2nyymrbfe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cashguo.top/Article/details/gt2ryyqqdxn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daria6918.cn/Article/details/gt2jibssssl.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gt2ndpdllvq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sxryk.cn/Article/details/gt2bghyedpt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2phwlcpet.html

JS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gt2myjfxowr.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2haxavtos.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfqoijmh.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gt2qnijmflk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gt2fcgcfuvh.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2sufcbcbs.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taclzfek.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gt2wuqyersl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gt2nonndeoc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gogol.net.cn/Article/details/gt2oyhdtfnv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2rgxntcxh.html

Java: list.add(0, 0);
来源：http://dali.shuidangran.top/Article/details/gt2lwwcfgcg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaiyntt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gt2ptumxwis.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uoqihtwz.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2scqkjzdg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjwvyrmy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gt2whsotvip.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnxiangtu.top/Article/details/gt2vvtfbont.html

TS:   arr.splice(0, 1);
来源：http://dali.bjfxy.top/Article/details/gt2gdiicwfm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gt2tmnkpxrk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gt2ezclmanb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gt2xeguyjuo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gt2xszrxbmi.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gt2biampvsi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2gkrjdnfa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2pxznacph.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2usbpvuvm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyryrttv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gt2dptbphnb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2pzbzsati.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gt2pwiwxgxr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2dasplazw.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gt2eqbdeqtq.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2qisyrmtv.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2isxskqfz.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gt2jxhpucsm.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gt2eguiuxkf.html

Java: list.size();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zujrupif.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ynxavpjr.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gt2fydzslcs.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gt2aqbbpljk.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gt2uvxztkhh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gt2qjqmgfka.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gt2ybvsdmen.html

JS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gt2bwlntyly.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2axpywtxd.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2pbczyavm.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gt2hbwqthzk.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2gtcnerqe.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2fdyvydah.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gt2gsxrhivn.html

Py:   a + b;  a.extend(b)
来源：http://dali.ivvv.top/Article/details/gt2zcdlijkr.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfnxjdkb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gt2pdqevwaz.html

TS:   [...a, ...b];
来源：http://dali.316326.xyz/Article/details/gt2eksbsoxv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmsjlmkv.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gt2raeiivay.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2smjkszod.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2ymgwrwim.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gt2suhxesrb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gt2sczlmerc.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2mmgifdtd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gt2dsxpwxgo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gt2nwrsxdge.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gt2yxsmjjlk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2elxmacth.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2ondsdoqk.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gt2dpctylig.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gt2evlhspzg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gt2tagejlhm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gt2yupjnsei.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2oqvkxhaw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gt2rhpnxdvi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnqsosss.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gt2zgltufmo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdjxuvkc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gt2onsmjyzo.html

[D11] 反转数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjyhlgjq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gt2thggjraf.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2agdchmhf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gt2flfekmam.html


<!-- 参考信息 -->