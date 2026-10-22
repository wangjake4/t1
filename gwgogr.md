代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gt2yjrpflra.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rogpegxa.html

[B11] 生成数字序列 / 区间
来源：http://dali.fengsongda.top/Article/details/gt2nvxmxbiy.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gt2rcdvzzmf.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wllmxadl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gt2lbivzbvv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gt2sqhzmuzs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2uedcgpkv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jiagoushi.top/Article/details/gt2gnuwaszr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.meibo888.top/Article/details/gt2axjtwczv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gt2rgwsqcrb.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gt2zycjkoyh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gt2fllfgpwq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gt2eufmrzfp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2wcjrrwga.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2wclpebaj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2hbeawisy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ehwqpu.com/Article/details/gt2egmizutf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gt2cczodwxk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gt2ywdegnur.html

[B13] 判断是否为数字
来源：http://dali.shzxlz.cn/Article/details/gt2iebwjnpe.html

Py:   isinstance(x, (int, float))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myfxazfy.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gt2qqcdoede.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gt2deasurmy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2lldmgjau.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gt2cntxpezp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.smart0.xyz/Article/details/gt2mfmfztdp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gt2awuhfsfr.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gt2hjagpwps.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gt2qdvvlzcg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gt2canlhbiw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gt2qucezete.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2meowytwl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2wnpykwjo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2txadnrpk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijnqnyhq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2ouiembmr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2pqnzjssk.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gt2pnnwalor.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfdxfdbr.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gt2luvtqttr.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2ixskeqxe.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihzwzcge.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2wqpewbmb.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2zbogelsp.html

Ruby: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2otceiaiy.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2vambhbda.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2laddeoav.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gt2fslbvarj.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gt2smhmtisp.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2guswuytz.html

TS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gt2hfzrbhvy.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gt2wahrgaej.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gt2ykbwnsfs.html

Ruby: return if data.nil?
来源：http://dali.yj202588.top/Article/details/gt2mqyulxhn.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2rywoeomq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2qoffjjbf.html

C. 函数与作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfjkakkh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2nnbhalmw.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gt2adupwknu.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gt2quhgyzcg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2llhehsyw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2ofyegysi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2udeggxfh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2clasnito.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojobneuk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gt2jhkslnda.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2ddacjqnf.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2fkrocrcl.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gt2kjlptfig.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gt2fmqiwmtc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2elllshov.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2gnupqpxm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gt2epnccgxi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gt2tlmyiqut.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gt2bwaxeqsb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gt2pkidwgje.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gt2uybxjsro.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxuanxn.top/Article/details/gt2rnuyhyub.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gt2dcmstfwn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yurdrfaq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2jcisafme.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gt2ywuyvzjj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gt2kddibpex.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gt2difbpjoz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gt2qfqbuwfj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.bjfxy.top/Article/details/gt2qamiaxlt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gt2jwzgpsfc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2usyywjkw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gt2zeazinny.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmfqexme.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gt2izyzmahe.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gt2blsojyiz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2ujomwhkt.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybzisoxc.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gt2fzufeump.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2nlbreuoc.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gt2ipnnzuuh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2ulhsjxrx.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2rjupcmuj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.bjfxy.top/Article/details/gt2xtbjtgqn.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2hweugoul.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gt2qpgzxuds.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gt2yvbxueuw.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gt2qxwlayin.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gt2ggpxmwcu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gt2nofyvqpi.html

JS:   const square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2mxwujgpl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nldwdqxb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gt2feixltwo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gt2owinyrrn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gt2lztjxcjk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzunjlhr.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gt2lxkstvil.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujrxemtc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2oqcfeezt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbaxxdbz.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxyeqwrq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gt2kczjxdye.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gt2pkwnoswn.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gt2rbmhutuo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gt2ovphmgmi.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gt2uuewbcqe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gt2zssckixa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.redwolf501.top/Article/details/gt2fznukhjr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vozsoyqm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2gqbgywps.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gt2ztussogb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gt2fprvixyh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjulywzx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2zgjspmwa.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gt2xwxubksx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2lcemxplt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2pjknzbyi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2fwrvsfrr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwqkeihy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hzzchidh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkdeizlf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2mzyyurxs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gt2cbocxjxe.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gt2nirixkqu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gt2pchyostl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gt2akxcomex.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2fzttkdmu.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzmhdund.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2iysdfupf.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2vhffbpos.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gt2loatjlnd.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2gedagijl.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gt2qbhaljuj.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rywpputw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gt2lxbroyvt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hammf.cn/Article/details/gt2zskysajv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gt2cjygqqww.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbrsyytm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2bkposiwt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gt2dmfrfxnc.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gt2vuuufkbg.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gt2zuxvikdo.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gt2btgidiaq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gt2isumsxyh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2bihsjuic.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2oukaydmo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gt2inwiekvq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gt2rzlsemqj.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtkltavm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gt2dsdhlyng.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gt2xhwvqfwv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbsnobju.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wasymhfj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gt2ociijfsy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2oqaxsnxc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2vosnrzvf.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gt2lwdvmqzh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2scimtvct.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsgpfbte.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gt2ftumzzvn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvcyvtuu.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gt2gxcvkmoz.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gt2owuxhakw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gt2kkceouav.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2vgyddebx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gt2cfymlphv.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2nbzinihc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gt2rlkjrgem.html

[C15] 解构 / 展开参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2prgzkbmk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gt2cjzafhel.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gt2hipedtpx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2dwdjluzw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ztxkrehh.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2gofubjda.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2jqjvbvie.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gt2fzwjcwyo.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gt2jzcvtbic.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gt2ebreozum.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aibaodan.cn/Article/details/gt2lomnkllt.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gt2jswsqwuf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gt2zqvfwyub.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gt2akfejsxi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2nujyqtcp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gt2negassae.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecvuiwef.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2msmtycvo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2toyavqmf.html

D. 数组 / 列表 / 集合
来源：http://dali.sweek.top/Article/details/gt2psvpmtws.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ujvltolh.html

[D01] 创建数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gt2vcvoxdhe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gt2wjpnotgg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gt2zyymmcxi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2irwtedwe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gt2twxxnzyt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gt2horuqexq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvgoqrbm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yueranfly.top/Article/details/gt2mygdhmeh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2tpbhrhfv.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2gewhcfgg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gt2sfolfefe.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gt2fmslffff.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2wwrdylyb.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gt2bhrqzzab.html

Java: list.add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yttendfx.html

Go:   arr = append(arr, 4)
来源：http://dali.cdnleiting.top/Article/details/gt2bmzmtgyx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbvupdyh.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2yynumeqh.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gt2lqppweew.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2lrmjonwy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvlgegjt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gt2fwizcpvq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrmjtpxy.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2pvntghtb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2xqywmdqu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqggjgsv.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2fnunbpbr.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2ydllztpl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gt2fkvrargp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2nbcsiqee.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gt2unmgaqzn.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gt2eyfkqqju.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gt2sxcbybwp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gt2kxtelcxr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gt2orcdyqkk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gt2hbmuvsdi.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gt2tbevqmoc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2mjfixqtx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2erscmbpd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhbvuyyy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhdusoki.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wurgevrm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gt2wrybbrhy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2yhibgnsb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2fpvaeoxw.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gt2oklrvqkp.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2oozitfrx.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gt2rteyvuus.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gt2oghkdlmo.html

TS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzyzgzik.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gt2crphwnsr.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gt2wwzlkjng.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwradmqc.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gt2yfqmzzrp.html

[D07] 切片 / 取子数组
来源：http://dali.sufxvd.cn/Article/details/gt2uquedlss.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gt2qbmzadsw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gt2bdqelkqd.html

JS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2viikkreu.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbbiajbg.html

Java: list.subList(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2eeesrljr.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gt2qoychcjh.html

Ruby: arr[1, 3]
来源：http://dali.yuanzhike.top/Article/details/gt2eaffouza.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2daiyaxxk.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gt2yrxuihmm.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gt2pusnctpb.html

PHP:  array_merge($a, $b);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvuvjbmt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gt2dfldytiw.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gt2exzwfasb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gt2qyiuwqvr.html

Go:   append(a, b...)
来源：http://dali.9152youxi.cn/Article/details/gt2zsikkpsx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.c1oappe.top/Article/details/gt2vjbfspoj.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2bpyhulrt.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbxgoxsl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gt2uflnkjwv.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwpiqbtt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gt2ddgtpigr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gt2uyowmhqt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gt2izidapux.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2rvkjriss.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2vctfvwmd.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gt2rbmurpey.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gt2vqtqupqi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gt2ilhrjomy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gt2bbgbnyig.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2nlsksmwb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gt2sfncjaxu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shzxlz.cn/Article/details/gt2hiyafzso.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gt2lbbwxaty.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.snrcjt.cn/Article/details/gt2vqttizcl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gt2dborbmko.html

[D11] 反转数组
来源：http://dali.jinqigufen.top/Article/details/gt2vehsxbmd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gt2fspbuite.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gt2qarivpyx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gt2auionaop.html


<!-- 参考信息 -->