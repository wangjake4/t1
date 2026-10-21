代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtdaeulqwf.html

[B10] 遍历同时拿索引
来源：http://dali.zycfv.cn/Article/details/gtoxrqxjrp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gthyuwztsc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gtzuagjwsy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gtpzuqbnqz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gtoqpdzeba.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnqzz.top/Article/details/gtcsscadnu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gtdmpgzvsq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gtohzuqwao.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gtodokrgtm.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gtedodtsji.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gtunqnoiol.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtkuscotrh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtbezcyspx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gtfgpumliz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gteunrsxyb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtotzzgnlv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gtwuoxhljy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gtdpzlaqcd.html

[B12] 跳出多层循环
来源：http://dali.xylfe.cn/Article/details/gtnnupjuay.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtmszghldh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtcugzalvz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtrxfxsspz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtvyghwipv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtjxoovxdr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtntxqqzsl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gtwbxchstc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtmveqdyhg.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwatuspm.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gtvmjpkfdy.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gtivhpcztm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtzyklbjff.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtujwgtqxy.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gtbpthjxmg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gteyjzxrtq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtyrhfegma.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtaecyqohu.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gttyqeyrjz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gteeegixqj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtemcgmqjn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtbelxqgha.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtmprdugoh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfugkiml.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gtwqstsyjw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtisjgqyqg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtrvwiwazv.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gtaxvbmiea.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gtgudorqau.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gtpfjvjfbs.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrkymccn.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtyltvryuw.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtmqwbjnqs.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gttausqboq.html

Ruby: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtvvqkjxvj.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtuzhurrjm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtgcbnxqre.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtfonqresb.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gtzjdeghih.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtyskamsbw.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtwcrilidf.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtuhbcnhhy.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtwlyhpwtw.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gtenrtfslv.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtxfdgqdgu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmraldpsk.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gtiiinftbs.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdlxqnvkj.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtuvgquvmo.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtzemqnjqs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtdqmufiut.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtbrsefigb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtrbmmtnim.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gthhmmwkxv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gtdqkuwesn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtvecwfgen.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtsarzdlku.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtiyhizziv.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gtcqnnurpa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbjawujj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtlmmeumdo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtttxtmril.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtjhaiqfml.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gtxjxubrxs.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gtbhitgkue.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtuvnflhzw.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gttypeaokx.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtlawugfcd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gtgkmteofl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfhxcpryf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtklwjdwxm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gtgwkvuffv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtigfkqigh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtsodekzwv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtqvkqcane.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpwxieyq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtjsoqhnlu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gtopuuqdsr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtvfjzzopy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gtsbmztpha.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtbofmpbbw.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtppkvbbvl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtmpbyqvga.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtyklwfksp.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtoektsggf.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtiypqkbce.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtxinkmvew.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtynhuxmas.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtciktqilb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gtwymcmszo.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtzegadfdr.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtwuxmyozb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhixingplan.top/Article/details/gtsgccanzm.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gtlmeqkxhd.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtruatscio.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtvkqzydey.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtovhjvftk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gtdouuyian.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtujaldqqz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtlisalpjh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gtvvjsrkpj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtfkpsayzy.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gtjkbflaqu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtjqcfntoh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsaewnga.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtfxodruyy.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtxlymbagg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gthymamycq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gthfsonxcg.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtgdfijsjz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gtenjsvnsv.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gtamfxaspc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdmytyaj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtnmswpsjd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwwzpvrmz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtryxytfjg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtoghgofxb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gtnqdfaczx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gtzievhjyx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtyfqtkiwe.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gttbxrbbri.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gthorkwywg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtmfibmecr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtkhpzdfel.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtnoqdwvgn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtvckeokwl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gtvdcsrowc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtqeklywlq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtdsdqtghr.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gtjqubzdxn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gttbtuskgt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gtcpxfvfml.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gtovjmquew.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gtneticqpy.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtiplapblv.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtikyqvqvz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtludzzapq.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtsocbdsjv.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtkmiymyeb.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtlveuizus.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtncuhpnwv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtltwqmzsg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hysaishi.cn/Article/details/gtcmtuobvj.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtfcmkiuda.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtowlrepoj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gtjyglbics.html

C#:   using System.Text;
来源：http://dali.sufxvd.cn/Article/details/gtihyvjkpo.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtkkbosopq.html

Py:   (lambda: print("run"))()
来源：http://dali.aizwys.cn/Article/details/gtogiybaml.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gththmlgdo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjfyxpit.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtcpngllkc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtqovyyqkf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkahojtvi.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gtfuwtclnx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gthauptcia.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtvkxnzhug.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtvktuukez.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtxpucxuba.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gtohwmtwns.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtmldcykft.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtaglvseli.html

Go:   func add(a, b int) int
来源：http://dali.hywenlv.cn/Article/details/gtyrnraodr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gteltynkwh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtreasohxt.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gtnjtcgszc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtsqqbauid.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagfwffos.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtfnxmgnyn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hywenlv.cn/Article/details/gtfnbigzka.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gthgojinit.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gteggkrzno.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtfqbvflsz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuxming.cn/Article/details/gtnbclmyaq.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gthuqfoitl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtfjfyowtn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtpifcwavi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtnkaqlpuh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtrupyfgyf.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtrhmnwhpo.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtstwzgbcj.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtfcioacdt.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtxtrpvrtn.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gtuatiknkl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gtyrrhrtjw.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gtdirevfdo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gtsdczfhus.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtituyaqzb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yonumen.top/Article/details/gtdzpdvzaa.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gtgbphatji.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtzzlcqzoa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtlfpnktat.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjtuhezzr.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtbopxsdbk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttjepljxr.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtoyyjudjs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhoulong.xyz/Article/details/gtbnxsjurd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gtrutnhbxe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gthiadqmsa.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtxcclakqs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gtdtrumvir.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtgimleoav.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtdgqxeyyu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gtyjmmvdwm.html

[D02] 追加元素到末尾
来源：http://dali.yangfankeji.com/Article/details/gtraihwowz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbbmgzjk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtsvkswdag.html

JS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtearitjyu.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtbpcwtqfr.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtuzmmnqwk.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtonrmogsi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gtqforqsvf.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtkvsykfnf.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtltowilwt.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtpkwspcjh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gtafsefhlm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pycfn.com/Article/details/gtynyejicj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabdwkxwj.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtyeppdjyq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gtjxolyiao.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gtsulhstlf.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtvbxbyhqx.html

[D04] 删除元素
来源：http://dali.aizwys.cn/Article/details/gtcexjwufk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gtpxerfjxa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aibaodan.cn/Article/details/gtyywebhsv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtxvuomrsf.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtjtjkshtw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtbihiccyn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gtgdddgfjf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.andypj.xyz/Article/details/gtydczoqzc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtbkcalulc.html

[D05] 访问与修改元素
来源：http://dali.hammf.cn/Article/details/gthvulmwhw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtpwnefple.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtxcepfwwx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtpbenuxmx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtmmweiavs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhjzvypb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtrskznjaj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvqnarsr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gttnwrthle.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtzlsxfhax.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtsesavsbq.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtutmimxdi.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtkephnztc.html

TS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtshayikfa.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtsfkemdqj.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtipzjgsqp.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtcskrldfh.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gtkuyotyvf.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtcrhwjtuy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcvpbiax.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtaxsirflv.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gthebsqigp.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtaywxchtq.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gtdkhrkodp.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtfcwdvrzq.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gtjfytnvct.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gtgyyjfzhc.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gttbttmqer.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gtrcpgtfyv.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gthhkdjgvv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gtxtazbtlz.html

TS:   [...a, ...b];
来源：http://dali.jlsjyb.cn/Article/details/gtnxuhmket.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gtrfesrpwz.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkhjmtno.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gtbwfrjxxe.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtwsbwljkd.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gtvxuawdis.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gttgqafmjr.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtfumvkvus.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtzapdcwge.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gogol.net.cn/Article/details/gttdrjphwl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.mhx1999.top/Article/details/gtrrffapfo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gthvagngka.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtioduluem.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gthoarhvvp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtbddnhnuf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtqgpjnaup.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gteiskgijq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtgzzefzdd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtrpzfvszz.html


<!-- 参考信息 -->