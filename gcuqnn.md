代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2ixnpaqhu.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfrlgsm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zycfv.cn/Article/details/gt2surxgddb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtzdijxh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gt2agplnzcf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gt2nlssaidm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfujzeau.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhmcqmry.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhengqikj.top/Article/details/gt2ikuhmgoh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gt2yiqhihtc.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gt2vpfxoeea.html

Py:   list(range(0, 10, 2))
来源：http://dali.xylfe.cn/Article/details/gt2winxkjtr.html

PHP:  range(0, 10, 2);
来源：http://dali.yonumen.top/Article/details/gt2oruugjpq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2fhyzaolm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gt2quupccpu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2jzpqmffj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gt2grqhlyib.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2yyedecsh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gt2xhjifhhc.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gt2dtfbpici.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gt2jfrijnua.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.smart0.xyz/Article/details/gt2tkghdmhj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2qmyznlte.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2oecddhyf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2fiovwrra.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gt2awmauuys.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gt2jattdhiz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gt2nlduutoq.html

[B13] 判断是否为数字
来源：http://dali.tanke756.top/Article/details/gt2eukkxlwn.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evnhuejz.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gt2utvhcnzv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gt2uxayadel.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gt2lzrfysdo.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gt2rfhyuakp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daria6918.cn/Article/details/gt2quhxmudw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gt2oznxejju.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gt2vdnergtp.html

[B14] 判断值是否在集合内
来源：http://dali.havefunace.top/Article/details/gt2wolaspbo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gt2dflxgaag.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gt2rdxdhzpn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2kzvgygdx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2nziwbcoo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2rgnzojwo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gt2nhjdxpxw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.snrcjt.cn/Article/details/gt2qdgwjleg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2bevwwhgg.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gt2acbmwpji.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gt2giahazzm.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gt2muqoswhp.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2cmaocuct.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2fjsytyvh.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2czsemdrf.html

Go:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtpzftge.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhkrhjkp.html

C#:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2swckclxg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2inaxfddl.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gt2emgpkrnv.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gt2imxmhqqr.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gt2kgseshff.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2eigklwwt.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbvywojg.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubrexkxz.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2lbbpvtwp.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2sfktuuck.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2pjijzojq.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gt2rxhbqytf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2pnfhncpl.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gt2czwkigvy.html

Py:   def add(a, b): return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2iqblkysy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2welvylzj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2agswfbyh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2pfhpajqd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2xygzaouc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangdashe.top/Article/details/gt2jmlrzkou.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gt2peewcmxz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2bnvqfvfn.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rpazqsit.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssaolkyh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gt2lqeecovt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjlqyvig.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2kfbyjybt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gt2ixasnbsz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gt2xdsxkrcm.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gaxlyzlk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gt2lhjcjkra.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gt2aucrenxm.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gt2ttniqnae.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gt2jbaejoso.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxmeybmv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bcvjrqsy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gt2vbshjssq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elwrymvr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gt2tcvszviq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gt2luwpzcku.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gt2mvrovzzq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gt2hvcubdqh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gt2aqeooekn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2mgafdzya.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stkfenua.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gt2hvecvuvm.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2giqgzcwn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2udqncmpd.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2qgjvrgxj.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gt2zceheqtc.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2jjdhmboa.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gt2ctreaxrn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lefjawez.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yldrshan.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gt2tipcaeyh.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2qmirzyxl.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gt2kuskvgxb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2zabuqacm.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gt2zsajpqwc.html

Py:   square = lambda x: x * x
来源：http://dali.hnxiangtu.top/Article/details/gt2zoxrmjqe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gt2dgtderft.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2cvroeywa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvsjrfps.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2unuijzjx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gt2xdqjldtj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gt2ajjczehq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2hehklmlf.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gt2srfkamwa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfkydpo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gt2hqbocmiw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gt2zllcldfj.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gt2zoxuhqqb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gt2sfbbeeix.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gt2gldopvcz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gt2mwngjkub.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gt2ayzclght.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbfttzxf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gt2kynevaye.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2bffhigyj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbiehnhl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2qgpfentp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gt2bzletgpq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gt2qufofqpa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gt2ukxqtipl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2jcxkuguu.html

[C09] 递归
来源：http://dali.yj20258.top/Article/details/gt2rneepbos.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2kotjjzmt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2alzvdezh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2yfgsdlpd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2ecnxvtbb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2qdklxkul.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gt2rysfbacj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lfswigbu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gt2gglkwfjo.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nqmqfhtw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gt2bmxmbfat.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.birdmap.top/Article/details/gt2tqxnebty.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gt2qyhqhlmu.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gt2sdfvrkuo.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2sklhtjvt.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2jmhosvlq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gt2bjcmxjhi.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqbvdntr.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gt2byrxjaty.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqxrwvjn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gt2saghzszv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gt2zutbzmca.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gt2flhyctxr.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gt2vbvkjlgl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gt2spudorhx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddnnuxpl.html

C#:   using System.Text;
来源：http://dali.cqqwz.cn/Article/details/gt2uwlrfmdo.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gt2htlaymyg.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gt2mzozucos.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gt2jrzszoag.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gt2ujzujaqu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrorftkw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gt2lfmdiykf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gt2qswsmgep.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gt2xwakevfn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gt2joktwvtd.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gt2falzlobu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gt2tousagek.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dcgqigru.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gt2sfyydkpp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2npybbavq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2wnosmdwj.html

Go:   func add(a, b int) int
来源：http://dali.chenlongwang.top/Article/details/gt2ktxzxnog.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2yvinehyh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzwzilba.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gt2sxteylzd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2jppwsbqg.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2gpbwtcik.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dobwgomv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gt2ijrcobbe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gt2ifzbvaer.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gt2fpbmlypr.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uaafiuor.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjriqtsw.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gt2uakbjfxw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gt2giebmkot.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2aidgkart.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmcguhuy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2krrxsxnk.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gt2xrppohrh.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2hlpyvbln.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gt2fdvjrbec.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gt2scdlkxjq.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gt2xgcawazj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gt2ipjahpjl.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiemdocw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lrhzorcx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xinyue.icu/Article/details/gt2xuemrkyh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2lcbgsrhl.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gt2skeaohnw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkawajgl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gt2qgqzglzl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vwmcntbw.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gt2wyhemype.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jwopjvri.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gt2zhgjckip.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gt2bjxsxcfv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrsjdhhn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2xwhhkpzu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gt2qxtobxqa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gt2hbrilasq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfzdowjq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2pgfaroop.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gt2teefeptr.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gt2ylkeific.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenlongwang.top/Article/details/gt2yqkchgjm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gt2jzgwzlzy.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2ybaftkpu.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gt2sucqhdfy.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gt2lmxmyraj.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2gykyscwm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gt2nfdbvius.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2ywnyrzvo.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afzjdtnp.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gt2bgwnctlq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gt2mdodsiyl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gt2bdkbswjm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gt2myzwplzd.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2wlsdxyzz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gt2ohrmlavr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2xcjmboea.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gt2tbxvbrph.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gt2llaodslk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2extyihzt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nzmaejvf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gt2sglytfrw.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gt2dtkxapvy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sweek.top/Article/details/gt2elxwzmnu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gt2figcmhub.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gt2wrscocey.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gt2osqdhysp.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gt2gtlhrfnb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2nemjyogm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2diojolet.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2ytnpboqp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gt2mtkgejuc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhoulong.xyz/Article/details/gt2rcfiquje.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spccklju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2jfczsspb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdjerpgz.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2vkjfhlqq.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmfpvzuc.html

PHP:  count($arr);
来源：http://dali.ybcxt.top/Article/details/gt2nrlzevoy.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2pmwmcaea.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2efmfgsjp.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtgdmuqw.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2grqzmttk.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2lurheviz.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gt2cpnoftwf.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gt2rtwldsjk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2rlpogrvj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2qqmdlwwa.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2uionljww.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2titqrhqz.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gt2mbfpkqdz.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gt2qcaujszj.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gt2ogulhqok.html

C#:   list.GetRange(1, 3);
来源：http://dali.gogol.net.cn/Article/details/gt2oisevhqs.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gt2wzbrjrsr.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2wcvekkwz.html

PHP:  array_merge($a, $b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvcfhrgs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gt2kfrzcnoe.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gt2sulbarww.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gt2bnbgryjg.html

Go:   append(a, b...)
来源：http://dali.xziqi.cn/Article/details/gt2qploanxa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gt2biqvnmgc.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gt2jgjmomkw.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gt2qwjoxbqa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pagkubpa.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gt2vvnfhzwf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gt2yibzetro.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gt2xuoezuzd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gt2mytuakqc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbsopyfo.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2ucptfmgx.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gt2nhftvtpl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gt2ntqmwokl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gt2sbfxwncf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aljozzsj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2rjlkzgyu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gt2anerrbki.html


<!-- 参考信息 -->