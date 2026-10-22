代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hysaishi.cn/Article/details/gt2ltagcgcf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gt2eacwmlst.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gt2efwsoclr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2eiedloew.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2umlizhmc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258.top/Article/details/gt2apozebdd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gt2iycbqoue.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gt2xgjvzrkc.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gt2zdvvycjz.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgqzyshs.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2exgyqumx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqrspjjn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gt2sryifywq.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gt2cmujdenb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gt2issbypvk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gt2furjullk.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipltgwxs.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gt2rofhdhup.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gt2pfxxjbyv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gt2mpvbicsc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2zoriloma.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djdedkru.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2pttixpzf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2npvzzeam.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258.top/Article/details/gt2afeebhkz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2fwezskef.html

[B15] 布尔运算与取反
来源：http://dali.yj20258888.top/Article/details/gt2jgdkovty.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gt2gsavvfxs.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gt2zovugwbx.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2sorbodrf.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvthiehf.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2nuhjjrbd.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2unnsbczw.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2pyldrybi.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2mfveqmqt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2nthpultj.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gt2xxrczeiv.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qebcrjfk.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2qmudehgg.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gt2gpjchdie.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gt2nozesqfw.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gt2qqrxcwkk.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqbycuvt.html

C#:   if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gt2hnexzkdq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ooohnboz.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gt2vfrclfsp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2kcdduwpp.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gt2kuffuhet.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gt2dezhmfon.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2shwcmqdb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2bptrxvye.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2arkslwvd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2eyfuhmqf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzarruvg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gt2fsefjukg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2bkxzymtt.html

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gt2nqcviopm.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gt2wnsaoidb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gt2qswqicul.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2udsviags.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ekvjustt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gt2jvbhstro.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gt2beoxqgmw.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gt2inmwufln.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2nbosxdsj.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gt2djdhdlwj.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gt2bdgsflru.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qmpxiats.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2gxelgfbr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2jtpsyrue.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gt2dqsfickc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gt2xozydfsm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gt2yfvmvtmo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gt2sppfdjzq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gt2rzamtfzv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2byszjdka.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gt2lqyxzkyh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2shvmkeiz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gt2cfzmwlcl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhixingplan.top/Article/details/gt2cenloulp.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gt2efrwbwet.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2kwfnfzfj.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2jbgxyxej.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbiafopp.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gt2zahhlyqe.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gt2xhmzdjco.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixfmguul.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gt2slveyzuk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gt2jyqdqyav.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gt2tnknnkhw.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2yjhiljyl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gt2cbuasxzq.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2uzvntyzo.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gt2rrrkkcmg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gt2isljzcfi.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2psewdcbt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2vfqrcuyt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2qrosymix.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gt2iuwzcwob.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gt2klysxmpy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2ddgsefzk.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gt2odwtczxs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gt2wseueqqx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wglzurio.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxoiagns.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gt2ugcahmss.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gt2gpinljeo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrmtfdyn.html

Ruby: arr.map(&:upcase)
来源：http://dali.xylfe.cn/Article/details/gt2kfkioywj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gt2emkrdndx.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhjsbvdq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gt2zhpppapk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwkcmalz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctmavaka.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gt2mcyfieup.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gt2hydurkgu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gt2wpobpbiu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xziqi.cn/Article/details/gt2bdrnujur.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2mlgeybxv.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2vqbjcsbu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2jdoiarrb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2rlzgrhyh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2iluisxtz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gt2agubuhmp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vitjpohs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gt2dqotvecy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2bqwmptos.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gt2dddzhgux.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gt2fuulfald.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gt2qzbvsdas.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gt2yjldmbvg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gt2itmymgtx.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gt2krvqtakx.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2hvqrykmg.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2wfrzwfls.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2lqilanqj.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2ljahmnov.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gt2lhenydmg.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gt2nfnppswu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwojzask.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2xoqdumip.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gt2sjnvydjp.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gt2eburmqzn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gt2frpwpaug.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2zexltwfd.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gt2yxwpjzjm.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gt2aykeuyws.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gt2amnfzzwo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gt2bjprnfms.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2nduqclqz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gt2mrjoiias.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gt2qswzqmij.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqgcvpnb.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gt2oxavltro.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkzvcix.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gt2igbwltku.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gt2zfgcudbu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2iqhrawwy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2ierzoxch.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2lvvmsdug.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2mvaoniyg.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2vajieyrq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gt2vjvouesx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.mhx1999.top/Article/details/gt2jluyeuht.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gt2pfvokgoy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gt2sktirsey.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gt2mcbninkq.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2exbrtehl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gt2pbspiseb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gt2dgznbvan.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gt2mhktqdlr.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2dozksmsj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gt2vovbarha.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfqwcbhb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gt2dmsmtuae.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gt2lyjgptsg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2figphcgz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sufxvd.cn/Article/details/gt2edtfclfn.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2oqxqwmks.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gt2sqzppqiy.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gt2pjsyuqtk.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gt2fpsarouk.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gt2hwyyoamc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gt2ghbiencn.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gt2ecpdvimo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gt2ftsxxeyj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gt2ztsvterh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gt2dnjdhsct.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gt2vfqhlkmu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gt2bgynznrj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gt2xhpckorp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2zslmlxap.html

D. 数组 / 列表 / 集合
来源：http://dali.meibo888.top/Article/details/gt2qsxkgtuh.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2aejmwxse.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gt2ljqpadui.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gt2xvqfraxz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2kdhvzxnq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gt2bjrynplp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ybcxt.top/Article/details/gt2hvoxwjob.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gt2amfjaxzb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gt2wchjyndk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gt2tynlzpkr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzbsrnuo.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gt2iwspusjy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gt2plrkbvhj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2sqsunpgv.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjaivwxw.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2stkqtntd.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2helndytv.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2ijxkvufa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2fjanmkdm.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mncbtbbi.html

[D03] 在指定位置插入元素
来源：http://dali.yueranfly.top/Article/details/gt2xujxigzt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2pjioijvg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gt2arxcbxuc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gt2cfwrpide.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2adpskfen.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gt2hychxoot.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.meibo888.top/Article/details/gt2pcbevkqv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gt2ebcjjczr.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gt2xjxmkapl.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gt2zghfypqb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2lapwvwch.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypxoxvow.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gt2tkrjmltn.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2arinqcuh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gt2hrbxngxk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gt2kqjfdjsf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gt2jndcvdnb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.mhx1999.top/Article/details/gt2lkmnmsds.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gt2giomvbst.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2bcmbasxb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gt2iodeohmf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2aljmxpcb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcgdrfff.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gt2thbvsahr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2jppeikxw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2udyrgbvl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2poqffuys.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2msqsasas.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2afvdqabn.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2tpjkyhcd.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2akzbzhko.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2soocscnw.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gt2dnqroqms.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2dypjzniz.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2rxsfbrkc.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gt2njpfywav.html

[D07] 切片 / 取子数组
来源：http://dali.sxryk.cn/Article/details/gt2bygbqgdi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gt2sruscwow.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ydzc1.top/Article/details/gt2igbzpagj.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2pxicwlgo.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2tyohksvp.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2vvmzijrm.html

Go:   arr[1:4]
来源：http://dali.jiagoushi.top/Article/details/gt2irlmhhqw.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gt2svdkmzrf.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gt2jifttlti.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gt2eexlbnnv.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gt2fbjitbst.html

PHP:  array_merge($a, $b);
来源：http://dali.snrcjt.cn/Article/details/gt2bbioyohi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tian-w.cn/Article/details/gt2vhildafb.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gt2nqcarovk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2xscohdwu.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2agryapoo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sweek.top/Article/details/gt2koqxwkdp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2vibpxnky.html

[D09] 排序（升序）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvdmaggr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2gdizzmzb.html

PHP:  sort($arr);
来源：http://dali.316326.xyz/Article/details/gt2uxbhctdt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jlsjyb.cn/Article/details/gt2krcdekdf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gt2vksfbxhn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gt2rlllmxpo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2rblysbgg.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2hbfqaedx.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gt2vjsweikc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gt2jzkvgwqq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gt2whketdmx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2uezdwwjb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2hmvvxqbj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2xlzuoyyy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqmsdbhb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gt2xizwzzlv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gt2aqctxvuj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gt2djvcosqi.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gt2untdjzui.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gt2ojpnpidb.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xprufzzo.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gt2cybaipvx.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gt2ewmbnatg.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdskdnuf.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2dxuumbzl.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2tugffbef.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gt2abcjjqnl.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gt2ixouulti.html

Py:   arr.index(x);  x in arr
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbolbzgk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xuanzx.com/Article/details/gt2wnymmkyb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2hoesfggr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.iojbl.cn/Article/details/gt2vuucqozm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gt2xftmyfnc.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gt2mgmcbend.html


<!-- 参考信息 -->