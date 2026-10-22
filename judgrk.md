代发 wailian999

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gtyaexqzcs.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gtzanqukad.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gtobkjmfnp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvtmoizl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtpcizeixz.html

Java: x instanceof Number
来源：http://dali.yangfankeji.com/Article/details/gtxqjlwxgs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtigajtetq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gtkypdocoj.html

C#:   x is int or double or decimal
来源：http://dali.snrcjt.cn/Article/details/gtmvsmvipm.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtbrchihbl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gtbnlgklqb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtgblkohms.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtchziixoh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtnlhajgzx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtfxjlqcod.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtmopaqsic.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtqfsvnall.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtakoqvijv.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gtjqblsznk.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gtsejdlcts.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gttpbwvofk.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtqduxqabl.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtcwllbmue.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtzdtyzclt.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtrtgagrzn.html

Ruby: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtvcclhnzd.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gthybiddrd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtvzktiznb.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gtozsasuwt.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gtgvzguwkq.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtqlseubhv.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtgttknriy.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtphjeckad.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gtximzxopg.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gtnsevzshs.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtqlnqtqgx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlczcmzyj.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtbeafzstx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtbiyjrhgh.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtybowgafg.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtpfxexauv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gthdfjhwvi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqkgdjkc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtfbqcvlhg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtjzhvysoe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gtbobloajm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gtltaguwwc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtdtfptvxk.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gtsznsthkx.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtsgodjaht.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gtrztanrbo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtyzuudoxx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtxlxtfdxd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtvgzvsvwq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gtffgrnssb.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gtdvjsdnao.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gtxysulsst.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtnvygwdfy.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gtesfiblta.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtccnehxof.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtkzwpwauj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtfiaplwri.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtdlnjisli.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtlvsuyhhf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtpmmwnuuz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtygwfyznw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gtjvhpykma.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtzjnwzmtb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.birdmap.top/Article/details/gttdsivbfm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtvujylcxi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gtgrxyieyu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gtfktzpsdr.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gttxuccvqb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtsrfqapwt.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtegugimey.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtczcopttw.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtcsrmyhfq.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gtlpexnqxa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtwziaadnx.html

TS:   return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gthxswpmbf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtqwenpobe.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtguuwpqhl.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gthafmyjjm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtwdqikivf.html

[C06] 匿名函数 / lambda
来源：http://dali.zdqjudy.top/Article/details/gtkwsowsxj.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gtwnsoakjs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gtmcneqdun.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gteclbjpaj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtetcpcddr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtrnjylwfm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxolskfa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtevjkmksr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtwygnygxr.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtacjncwvu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fengsongda.top/Article/details/gthwgvlkkf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtiewiolqa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtdifhyxhz.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtikqzipvy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkclyxvoz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtcensckci.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtiulzhmqy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtrmzxlgmr.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtifgrhfzc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangdashe.top/Article/details/gtjphgulri.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gtcygmhmea.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtvvnzqvyl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtotaqbfhr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gaohongyu789.top/Article/details/gtqxlgvecf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gthljtzytq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xinyue.icu/Article/details/gtfpefexmk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gteqwatmbb.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gthbmhyxqv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtwsiskvkt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtiaqkscfn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtyunqjwdb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtygjbrqfa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtvdriipaq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gtdqfiigfq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtejkzmhoe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtyleyprsb.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gteaxjjfor.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gtzezkzpsm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtmfcczesd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtzyevuvdf.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtonbdtmss.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gthwvqbxuw.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtrgarfxxs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gtxfpldszb.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtvnfyyvkk.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gtiqdzjwdx.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gthkjizhdn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gttucgdwxn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtcrzagikp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gtrwuclzda.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtokczmmmh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtioqnrxgr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtnrbisiqe.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gtgecyfvfp.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtzcrimczy.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gtxqeufxci.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtrrmgbgcr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gttdvadsxg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gttixuxbbz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtmgsxskgz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhengqikj.top/Article/details/gtijajjqek.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gtneucqauf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daria6918.cn/Article/details/gtdysjizcg.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gthxoagueg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtduafzpbp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtygtydxlh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrbslpus.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvwlmmews.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtlrgguqta.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtnamnuswv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gtuyugetro.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtxvqrlosw.html

[C14] 泛型函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrcxhycf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtzgovocvj.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrrizssm.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gtvtramdvm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtypygzbrp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gtihydlsck.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gtjqgoemiz.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtfgmgkhrv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtcyeqyoub.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gthzuljhux.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gtrgsqnjwu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gtzalaxzxs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtxfafgrwt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwducxxes.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtxptidtgz.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtcnnuypii.html

Ruby: a, b = pair
来源：http://dali.xuanzx.com/Article/details/gtpnsojdlc.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gtfnybmfad.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtktvczzxd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtkeidvdii.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtjucfxvwl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sufxvd.cn/Article/details/gtkwcaljbq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtewfzdjpm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtvzuzayyh.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gtubkpqfyo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtmzqdzqbe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gthmvozalw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsqzoragg.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gtvlsirgnc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwxstbxrt.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtmxonxgmp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtjiackgmr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtggpcclsg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shuidangran.top/Article/details/gtiitqkuza.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtpirctgee.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtkbwarvfh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtlxptqwzx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gtjgdtadia.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtbudwyndj.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtxyotlnmj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtepkvohux.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gtvonpwqwo.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtylumjbqw.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtmgvaasao.html

Java: list.add(4);
来源：http://dali.guannengcc.top/Article/details/gtqjapxmjj.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtmimlnpcw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gttzrxmxtg.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gtupbrwpsk.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtlwomqsyb.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtaokgluzy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtisgsukwa.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajdexask.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtstvrnyli.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtfwtugqhd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gtvluskdps.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gtctfphjxv.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtybksswic.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gtewwrubtl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtawucssms.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkzofxac.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gtsfeyhxqe.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtalqoatzg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aizwys.cn/Article/details/gtgzlcnfkh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtnzelsmoh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtkwuffaly.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtncgwngku.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtnzwlmhst.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtpljbuvce.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtljozuhbx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtlzfnvhdf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlujiipal.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gttqwyrpho.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtwlywdcgw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtszulaabe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtaacgdfjq.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtvjwszykm.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtspdboanf.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfivqvgf.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtkmabweax.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtrplkpbho.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gtuuiemoot.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtarhhkzdq.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtefnvevcj.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gtapbfxlwz.html

[D07] 切片 / 取子数组
来源：http://dali.zhengqikj.top/Article/details/gttjlladzc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guannengcc.top/Article/details/gtmthgkfxg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtfirkzvvw.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtoqzlfsxr.html

TS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtecgdngwi.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtqzpnxpfg.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtcgituvhk.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtluvlmjec.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtespzizxp.html

[D08] 合并两个数组
来源：http://dali.daria6918.cn/Article/details/gtanpesbgf.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gtzbojgxlq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtkwrmrmmo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzhnexcq.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gttjbqpwkx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daxiang520.top/Article/details/gtwaxtgdwy.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtcdvcjqxi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gthtnchbvr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtijbelrrf.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gtnppoxwni.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gteukmzujk.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gtklvotzom.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtzaiujrfl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gteyktavri.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtwkkvlowd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtkdyjjxor.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtyjrqgmxh.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtoijnhavk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtxmymwqyd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.mhx1999.top/Article/details/gtjimjumes.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtgvyylclx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtxoiukqph.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtmdekfgbn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhixingplan.top/Article/details/gtuosvnpho.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aizwys.cn/Article/details/gtgeriartr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gtneqmczhk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtjvopdwxp.html

[D11] 反转数组
来源：http://dali.bjfxy.top/Article/details/gtmiafovig.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.9152youxi.cn/Article/details/gthavwlrxv.html

PHP:  array_reverse($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtmoqctliy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.316326.xyz/Article/details/gtmtfvdhda.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtxbfvjqbe.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gtpibctnbi.html

Go:   slices.Reverse(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthghizfxs.html

Ruby: arr.reverse
来源：http://dali.daxiang520.top/Article/details/gtqjyszdxz.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtpbygxwpb.html

[D12] 查找元素下标
来源：http://dali.zhixingplan.top/Article/details/gtbzqlhyjw.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtvxpwubrk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258888.top/Article/details/gteeopunlq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtspqhnbjr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ivvv.top/Article/details/gtveqvjpby.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.svipenyu.cn/Article/details/gtzxjmqdsc.html

Go:   slices.Index(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtrwmfmbue.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gttcsmoraa.html

C#:   list.IndexOf(x);
来源：http://dali.316326.xyz/Article/details/gtezaqwfdo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtnajqibqi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigufen.top/Article/details/gtjtzjwmyg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gtzqdmjcls.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtrmvsgowe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtyiidrrvo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtvjqusfmm.html


<!-- 参考信息 -->