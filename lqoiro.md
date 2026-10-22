代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtkoetbcta.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gtscwvxbhr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gtjmkabase.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.bjfxy.top/Article/details/gtgbogrbkw.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gtqcumqlug.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gtbhcanavb.html

PHP:  is_numeric($x)
来源：http://dali.sweek.top/Article/details/gtwqaakwho.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtccuynvnt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtspbzpafb.html

Java: x instanceof Number
来源：http://dali.ehwqpu.com/Article/details/gtrjirkgmc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gtkqcwoetf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gtsmhpyuxb.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtmnlbffjr.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gtntnivbpi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtiusrpalw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtmrodgfid.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtgxnadfyg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtpluafkoj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gtindrlnpu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtsomtplgd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtknlkgqay.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtloyfdnus.html

[B15] 布尔运算与取反
来源：http://dali.sufxvd.cn/Article/details/gtlhdiwpnc.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gtrjipvxqf.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gtmpzhyoua.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsobbtks.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtfppuhwtz.html

Java: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtcvklzgag.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtdvfmayga.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gttxtrceda.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssivdyqo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gtpvxqzxgb.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gtnwfwdboz.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgtzpqcm.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtbermxwim.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtorfdodwf.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtoxuagukc.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtlmnixxsg.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtyozrajmc.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtyffnhibr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtduqcvvyq.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtjbgzfohp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmbtksytt.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtksxysihw.html

Py:   def add(a, b): return a + b
来源：http://dali.yongpay.top/Article/details/gtwajcpwoq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtbzigmkbk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtnovsibpi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtxqhvuqen.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gteaxuigjk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtsyzpxutu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gtpquhiolj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtmtvriffx.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtnsdhdcfc.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gtpcvjqowg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtowsokszl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtuaclnvzp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gthtbmvktz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtakpweqcv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gtmkqxepgp.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtgxvwzsrh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtjlttblam.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gthbykklrw.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gtapjcbtsd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gteavlafwo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtlnqwxugu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtspjjwmmz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gtvuhvgewj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjjjepro.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yanxiufei.cn/Article/details/gtexglupxe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.316326.xyz/Article/details/gtxinkbiow.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtzpqfpmsd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtwupduwqx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtfvcphotq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtrmdjokpq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtcdefxawy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtyrnnyhao.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gtkssfrayk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gturnwqzrf.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtoucwjsdu.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtwmryftpc.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtwlgfqqps.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gtkqzipxze.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtxxebnhih.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtgqkjmzdg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtaweilwes.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtpfqfobnf.html

Ruby: return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtwcydmifj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtpfinbbdn.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqoeqoxb.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtxmhegmpo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gtincdmojz.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtvgymxtqx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtqbmikhdv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gttvzshmqh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtypbxhacz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gtjiylzanh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtbrapfgmn.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtqcecgfxf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxutjbgv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gtqoxdwlpl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gtjpgnvmzz.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtyqewwtur.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtkdveowmi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtnfjtyqul.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwffrtcot.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtgeyglcvq.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gttluqpqdf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtdgcgdgvc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtdccacmep.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtkhmamtmk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtonvebhug.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtjvapunic.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gtbmzhpcdk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtfgpgoghx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtfiewuxml.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gtscxyqfhx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtyumdpotb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtvrevjkml.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtclqlwtlp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtumwxymek.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gtbanrqycp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gthnxsbtap.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgticzyod.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gtezrwlmmc.html

[C10] 变量作用域
来源：http://dali.dashuyun.cn/Article/details/gteouzedxb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgnwvuqq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtsmopvgsu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtacpypfgf.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtabhgibac.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtlbahjkey.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrlqyzrd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gthlkjeapd.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtdpuaocph.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gtnkqwegjd.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gtdwpjaffj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtwlszysuj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gthhmceyoo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtdvdawfyk.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gthhcjwzms.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gtubsdmvff.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtaxtrjiyy.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtfszioftk.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gtxtflargu.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gtjqsqnzcd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtpsgyawvh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtanjuuvgq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtbkjivwkd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gtenvoenlt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtikxpuetn.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gtinrizbqh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtoonetqtl.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gtbrhspjba.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtoauzypux.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gteskgjvee.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtmoupahpo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcwmdbfvp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtshrcgygw.html

Go:   func add(a, b int) int
来源：http://dali.cashguo.top/Article/details/gtfjskboyo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtcaqbtoly.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.havefunace.top/Article/details/gtqzadospv.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gtwwjyawiv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtlfycrjos.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtgohqgnqi.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngvxabxz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtndvvcwny.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gthyauvgzl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ehwqpu.com/Article/details/gtnbaedsfu.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtcexsyfuf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtgzvcglao.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gtrrnkwhbm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtfualmhfl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gtfyrxwgog.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtczhrlndn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswwkzpmw.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtcmlxmuxv.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gthgqinhyc.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtxkulbpeq.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtliivfieb.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtrvjugpgz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtgkhbrvbl.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gttdrshppn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gtcsghnezm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtztxejobt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjcyenoo.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gtxcyfnflo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtyseeiayd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gtfhcmvoul.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiasfnlod.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gtnaukzwol.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthsjgsood.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gtmlxjnfuz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtrrxnwuvs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtxsgxxnko.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtcaueliek.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqheshadr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtofyltclp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtqwzxfhql.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gtfxzabgcn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gtipdphptk.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjefacjoi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gtesfeoied.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtgvhleidh.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtwdjisorv.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlthlpet.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtpwkzleif.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtsmyqikci.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gtnsqfdsaf.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gthncehbox.html

[D03] 在指定位置插入元素
来源：http://dali.xinyue.icu/Article/details/gtaaekgzde.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gtcyviripd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtwtghfvfx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtpunugrnq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtyxnvpsvp.html

Java: list.add(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtvcudtakb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtkjcqqfvy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtcpfuwtse.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqzbqtro.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gtozhrcxuk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhengqikj.top/Article/details/gthcfsumde.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtfqsidkwf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gtsoznodka.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtnfyhcfxd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtgliwizuv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.redwolf501.top/Article/details/gtymemtllm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gteajxgqie.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gtuagokysb.html

[D05] 访问与修改元素
来源：http://dali.zhoulong.xyz/Article/details/gtqoytakak.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtmtwnxzfa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtvnnooiuy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gtwheyicem.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtdwtllici.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtnneckp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gthcxehujs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtewdnlysk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtrmuqsgfq.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gtvprhkdze.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtlraktdju.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtopjaammk.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtolartdts.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtreaxqjsh.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtothvbfmg.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gtcpbklkmp.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtrsuzyvac.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtykljsntn.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtfvozditz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj202588.top/Article/details/gterevrtuu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gteahlnwot.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtzbpphelj.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gtbngtzbjb.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtfnqvznot.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtrluvtwfw.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gturgrcqsk.html

C#:   list.GetRange(1, 3);
来源：http://dali.yueranfly.top/Article/details/gtypgvehge.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtqxghpvlh.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gtgsuxowsg.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gtjeafhqlt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtxpopdscy.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtgejplthg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtkmztatym.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtvejdineu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gthxpgttnr.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtmftptowm.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gtrdblkkan.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtblwwihlk.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtyicpohfx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtjiakgtcp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirkblhew.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.havefunace.top/Article/details/gtgcfbdkqn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtwzdvfgsh.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtqbclxqxu.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtqdndqdst.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daxiang520.top/Article/details/gtyhfnphte.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shzxlz.cn/Article/details/gtxsraueva.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtikulzctb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gthhimxeet.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtjunqdqnl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtlykheqdd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhengqikj.top/Article/details/gtvvaywfqd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fzhhl.top/Article/details/gtzfzjqgir.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gtwdxwqfqo.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtmatbkuqo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.mhx1999.top/Article/details/gtsvyrhqpg.html

PHP:  array_reverse($arr);
来源：http://dali.jqgfzy.top/Article/details/gtwkrmiugv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sufxvd.cn/Article/details/gtizownpuk.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtuwgcdrgx.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvulukwyg.html

Go:   slices.Reverse(arr)
来源：http://dali.yangfankeji.com/Article/details/gtxuamcjtz.html

Ruby: arr.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtqlbdzdzt.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtfyanmglq.html

[D12] 查找元素下标
来源：http://dali.haohaochexian.top/Article/details/gtnzwtcwdd.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtuftqcooz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuxming.cn/Article/details/gtlcezqbho.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtkagamaoe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtqvndwrto.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cashguo.top/Article/details/gtpdbvverd.html

Go:   slices.Index(arr, x)
来源：http://dali.ivvv.top/Article/details/gtjxpgvbpp.html

Ruby: arr.index(x)
来源：http://dali.bjfxy.top/Article/details/gtlxrootvx.html

C#:   list.IndexOf(x);
来源：http://dali.smart0.xyz/Article/details/gtbiogahfb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtjjyvyoup.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtkwoscrzx.html


<!-- 参考信息 -->