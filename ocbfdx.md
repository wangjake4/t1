代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gtqijuhkur.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtfkwudqpf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtzazmdpat.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gtiwdszyko.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtyuigujns.html

Ruby: (0...10).step(2).to_a
来源：http://dali.snrcjt.cn/Article/details/gttnxajdxu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtnbfltwfp.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gthpbwlfay.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtgqnedexu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dashuyun.cn/Article/details/gtjrrliywo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtsvqcpgmf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtbnjpzatc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtstlwotjo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gtqbfaqoqt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gtbtqogbbm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtyyaopjjn.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtxflqctvb.html

Py:   isinstance(x, (int, float))
来源：http://dali.yueranfly.top/Article/details/gtkzgtjqck.html

PHP:  is_numeric($x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywraehwn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gthmwvexjw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtjyyfwvtg.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gtcmvfuett.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jiagoushi.top/Article/details/gtxvjmtxzg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gtazqpbufe.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtohfpmwhr.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtckfenmbb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gtpopvuduu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gtgqrxwgbp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtdelmnskf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtmjcpkfxl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtdkfiljdh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwhpxjqx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtrmmlqqcz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvknwizis.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gtukimcise.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gtlhfiwwhe.html

PHP:  $a && $b || !$c
来源：http://dali.hongshengwenyu.top/Article/details/gtofskjqfh.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtxelvhpjy.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtwjwwkhlu.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtlszxizto.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtsbpekxcv.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtpqfhcyrl.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtdktpbwlh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtynxebmyl.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gtjjzlworj.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gtlpkfvoph.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gtpzxmkznp.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtjtwqsxdo.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtoezjxgsj.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtlkjjnpok.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtrdcfjpzt.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtthxhukek.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcrwvcdxr.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyxsqdab.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtyvrumozd.html

[C01] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtjtenewyp.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtbwcdxiym.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtmivvhxer.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtltyrgbpy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdecycvnm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtpsixopay.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtpgutmten.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchjtiapa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqpfkrcm.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtjfwxixpz.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtuwzjkqiu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtlkgycsrz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtcranjdkn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmempejpa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtjbxbfisu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gtkllrcdzg.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gtzjlvvxra.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gtvcnhkxiz.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtodehduun.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtlxniujfc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtaadcsuym.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtniuwiiky.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthupxkfhs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pycfn.com/Article/details/gtwbqhxkic.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gtufznfmeg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtpqpwocyo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtxmgiszlz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtijfqxipe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtzlzpbesy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtxqxzlcdd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtpkfocwdc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gtlyolqcjv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtvdvnixez.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtyeoknmyu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnigewcd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtpyagcvae.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gtwmiprbpl.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gttayciokp.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtgunceasv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtugtzwyat.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtxplotexc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gtspxbuplx.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtvqebzmom.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtbsvfwzhn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gtkryohpme.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtszlmuiho.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtkduneacs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gtgdgmlvgt.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtxybpkrci.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtamoxhnqa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gtwkgpudnq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gtgvaybyxc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtarlhcvco.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtjqlbqhto.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtpeqnctda.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gtpbtqkeez.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtiwhbkxho.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gtgrmwkjfo.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtlcncemae.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtrsgaedhw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtsxfhefem.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gtkeyuwxmn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gtlsijbrhe.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqljuijba.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtgmudbbww.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gtzxnebvdg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtfyxjanjd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtolibrdfy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtqbwxpfvx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gttdhafjft.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.vqdsnc.cn/Article/details/gtohbmmssr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtqgblxcek.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtnasisptd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtlpjjtoyf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgardjwti.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtxosvwaxf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtvxqrdcfq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gthrcfqqcr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj202588.top/Article/details/gtyfswxanm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gthfapoaiw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtcfeysncv.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtohslucis.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gtrqnfdfvd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtjyiavedo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmmwvwpw.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gtdocuciwm.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gtspkrujnl.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtypyjdxkq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gtqqfqvdzx.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtnnkiirki.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtkcxclkym.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gtmvmoazfb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gtsegovfkt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtmzcjczfg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtzbsuekag.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtxuyjwbrb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gtcufugbic.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gtqrmupgrr.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtxcjxcrca.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gteitmkshw.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gtvvljbdkw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtvkocyubq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtgggocrnh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gtnrudqzet.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gtvrqliwtz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dashuyun.cn/Article/details/gtltmxblfi.html

Ruby: -> { puts "run" }.call
来源：http://dali.316326.xyz/Article/details/gthnzkdefu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtilhvdpng.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtpfkjirvd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtnzvtjull.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtqyuxwzhi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtpqvrucqc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtseynolnb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtaywhnybj.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtgemwznyo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gtkywjfdxs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtckcprhui.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gtkzhuffwm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.c1oappe.top/Article/details/gtdfywhtim.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtsfzzpfgo.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtfqgavptf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gtixbrcnih.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gtgubpqrta.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gtertnnovq.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtbuuvzqmz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtgmfobmxx.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gthpkkpajf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuanzx.com/Article/details/gteykrzjhq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtercwheaa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtjbkumbia.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtwinkbaho.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtxkctlyfp.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtkdsntmbr.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtxjummoib.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtzgyelvcy.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtbuwurqdw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtzsdqkigm.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gtpnjsfhky.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtxraxvesf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllvssyjs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gthwrgfgrh.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtdnljbirr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtbsxxhpqd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwefkunid.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtjttijxrl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gttqrafvmc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlicyxsf.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtbuyqcdoc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gtreusgzbu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtrawemsde.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtujjpuqpn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gtnvvigfok.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gtafonkagv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtnzhosmrb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtwuiswagb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtwyivrifi.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmlrbvus.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gteihhdhbq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtkcbtrdrd.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtmvqylhzy.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtljtvqytz.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtconghfgf.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtdwgjlvvb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtaxxbwbra.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtcllfxvhz.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtijjrqnjj.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtqwitmcgv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gtchkqasox.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtxevkwrse.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtincwaomu.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtyfgckoex.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtdamjmjct.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gtkansqhlv.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiupfjtnr.html

[D04] 删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwuhzkuf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtymtnhhjz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gtxgamtwlb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gtvrweudui.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gtiimaaclx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtushhgaur.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gtjvszpxwb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhfgjdsy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtegzeddzm.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtsjmujscy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gteclgrfxr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtgaabwlms.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtrtzgkazy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtqhgkbzkb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtmcipbfbe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtqvguefta.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtytecxuyp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gteshmphtv.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gtvnmcshyi.html

Py:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtmfxdiyrt.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtpvjwlypd.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtqsqijkap.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtpkptqofb.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtsivhrudr.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtpmylockd.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtjjkaswzh.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gtuwcpacag.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gtyohossuo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtagrzanbd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gttzddyrse.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtdtqbhefl.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtwdvuruzr.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtaelewdsi.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtviygqytz.html

Ruby: arr[1, 3]
来源：http://dali.ehwqpu.com/Article/details/gtoojwjkia.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangdashe.top/Article/details/gtjcwhxkjc.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtiuyriqgq.html

Py:   a + b;  a.extend(b)
来源：http://dali.gzhubu.top/Article/details/gtwzytxsmx.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtdyopulck.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gaohongyu789.top/Article/details/gtafwynoqt.html

TS:   [...a, ...b];
来源：http://dali.zhiwuduotai.top/Article/details/gtfwculppa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtdtxavtag.html

Go:   append(a, b...)
来源：http://dali.c1oappe.top/Article/details/gtmwuoydqu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoorqbpir.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtqsolovyj.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gtivqxkiyv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtgjycgypr.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtlacgzykv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtcfkbtdza.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtkfedrpqz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtbhleswqm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtwhvuskir.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtxrqwobdk.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtovebpxqr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gtwrrqnbaq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sysykeji.top/Article/details/gtvvcfyahx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtlfgpxvgh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtdnlztitv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtgwijjllc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtnjdwticp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gtdxvgrola.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhengqikj.top/Article/details/gtqlloclvq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtemwfaahb.html

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gtzykyatti.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gtuhmrgudj.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtlzqbxdgs.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gtwwwmeaon.html

TS:   [...arr].reverse();
来源：http://dali.feifeiyinyue.top/Article/details/gtkbsiovuv.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtdkgmuqpq.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtqxsjierz.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtapfzjenp.html


<!-- 参考信息 -->