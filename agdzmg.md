代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2jqivkixv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2kjadophy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gt2ohrubjbm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gt2pkbgaxxz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkydchkk.html

[B10] 遍历同时拿索引
来源：http://dali.yonumen.top/Article/details/gt2caprdguh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gt2uhqeweli.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yangfankeji.com/Article/details/gt2ypvthuoo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ripypahv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2wxdwzacn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gt2lmcpuppu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gt2pjzsrqsw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekuxacsk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gt2vjfxrolz.html

[B11] 生成数字序列 / 区间
来源：http://dali.316326.xyz/Article/details/gt2hjvjhynz.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gt2vwjtajuj.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gt2mxdnqxgy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2hhkyrvtv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gt2xsuhggnb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2npmjkdeg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yangfankeji.com/Article/details/gt2icumbbcf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tian-w.cn/Article/details/gt2gdidxdcg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2wgjfffgb.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2mwdbazlk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gt2lkobbnou.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gt2uzsowoov.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2vatiwqod.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2dnvttdmf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2pnuhdhjx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tian-w.cn/Article/details/gt2txijflrh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gt2nnpwkvsk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gt2ohbhvbsg.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gt2klyzpwmq.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gt2qtjcfdzx.html

PHP:  is_numeric($x)
来源：http://dali.tianlin.xyz/Article/details/gt2wqgiuodp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gt2ezjucuaw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqapktiy.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gt2zlznxwes.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gt2wiobnrhk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuanzhike.top/Article/details/gt2fohanlqm.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnzzzejx.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyepdyef.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gt2erwbeuma.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gt2bssheoba.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gt2jsijcqvy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2wmihkjtm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gt2bwquniui.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gt2mrkycfcw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2evvfctmh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2cqewgiem.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gt2vqdvydgy.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vztetjtc.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gt2ryfempop.html

JS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijqykngc.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2ykhbkmso.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2wewwjepz.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2ahfrsfpa.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2bhpwtxim.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2bribikvq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gt2balttxuw.html

Py:   if not data: return
来源：http://dali.jqgfzy.top/Article/details/gt2cvbxtoeq.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gt2tpbrfase.html

JS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gt2zowkooqf.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gt2kwwaookw.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gt2bdrnlvet.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gt2odtwgoep.html

Ruby: return if data.nil?
来源：http://dali.yj20258.top/Article/details/gt2fogxyhvy.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gt2fvfxwnyp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ejeaevif.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gt2gutcutgi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bsmjnpsu.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gt2ohejiers.html

Py:   def add(a, b): return a + b
来源：http://dali.jianghu66.top/Article/details/gt2gzvqellq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmnqsfch.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2obvkwvts.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2vxuosjfm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2czxcjfxb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2foybwewm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gt2amteclcp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2hazngjji.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gt2rlbprmoy.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gt2cpgqiijz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gt2jjzlcxzm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vizpzqzo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2nnlmoknn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gt2rlfndfrt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gt2fhrraamn.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gt2mvrmnlkc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gt2gpqcpoga.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gt2kiefmnex.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gt2fbniujqi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gt2tczhsbpz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gt2lzxqdhlz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2xllqnwpx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gt2udhrzugo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gt2zjououhv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gt2orksmqjv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gt2wfaqtuuv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2rutaeaja.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gt2adrteyqu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.316326.xyz/Article/details/gt2qccnyvnh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zgsiogje.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gt2tcaipeco.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2kbctrelt.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2ljmaclil.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2atmnfedg.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2hmxxxhnc.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2iutwupoc.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gt2vvikidgq.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gt2erknvvkm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2qovfzadi.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gt2jgoqgysd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2duvpjqkp.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gt2zrzbqoiv.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gt2mltsioqh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gt2nczjmeae.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gt2ahyhakjw.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gt2zamgucuv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gt2iqwxfqbg.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2opeilimj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gt2jykignae.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gt2fvrhvtjs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gt2xfeydkmd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gt2qhjnfirb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2dsadtvdk.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gt2hpngjrxc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gt2iolbrdnk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2vdceofor.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yangfankeji.com/Article/details/gt2ohyzrxta.html

TS:   arr.map(String)
来源：http://dali.xziqi.cn/Article/details/gt2rctrojit.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggufkzxs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gt2kwxijaqs.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usujwtwp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjwuhosk.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gt2vchyhayn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gt2ovscurxe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2viyetgpa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2tifvekyz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujiehurx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gt2bcgsrjqo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2jfeobzod.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gt2lgwtleqi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2ediyxhge.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnihdrbf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2yzozlvph.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2gjwcygno.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gt2qajccqfd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgacwiqg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gt2iddvvwgm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gt2gcxxpjfp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gt2xartwdmx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gt2cergkxiy.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gt2rtcpmudx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmnezhsv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gt2ovbffhdp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gt2citipcgm.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gt2ltouvflb.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gt2ejqihdgk.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gt2ovhzegkb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hywenlv.cn/Article/details/gt2enicabed.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2baeknvoi.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gt2lkrlzzel.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2seincpfd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhsqebah.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gt2uevnmevb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gt2tyvedoil.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gt2zmgozmmw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gt2cdutbclh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gt2skxizslq.html

C#:   using System.Text;
来源：http://dali.c1oappe.top/Article/details/gt2ohwvujpa.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gt2gxppopdo.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gt2uxjvncqa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gt2puxllbzd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2mztpyqra.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2wywupidq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gt2glfpcejo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gt2fnjkphwb.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gt2afhaauyi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gt2kkimyfsj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gt2tmordbqh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gt2edqswzpu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2snprtvlk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gt2hrdyoqzm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2mmzfvqix.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2ozhwesai.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gt2ijgripzk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gt2kqloxugq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gt2bliuugih.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gt2idjfbowi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gt2zmtjyaiy.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2lfmvnhjb.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2uajivbkn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezctrdwk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2anvhvkms.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gt2thbqiusf.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2oveqiixb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrwdwslj.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gt2cfwjdglc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2azrqjtye.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gt2lxfrpggj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2exjemywm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gt2nezdjkca.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gt2kjbarwir.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gt2lczdwrvj.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gt2zqcznpje.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2yarbcwyn.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gt2vmxvtguj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfgoqnzn.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gt2yayfoxns.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gt2xgygurng.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gt2nncbctgg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mbqtsddb.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gt2secbihzv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gt2llbmnoov.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqgnivzo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2zubyksnn.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gt2earlqdwt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2efyjpdvm.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gt2rwhmqhbc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gt2gxerzegl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2spakfnyd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2fobteqxt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2nxxjzemt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gotoacloud.top/Article/details/gt2nwwoajac.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gt2hocaawgc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gt2kyhucqkp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gt2nwbwokos.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gt2pirjgzws.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gt2oiwspcyr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2zrvwydyn.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2lcqvyptt.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gt2mbbdgfey.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2ajjqukta.html

Go:   arr = append(arr, 4)
来源：http://dali.tanke756.top/Article/details/gt2hlxoyreq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gt2ecgllrfs.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gt2uhvdrumr.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gt2hnwuxkod.html

Py:   arr.insert(0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2cyucmgzv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcdwzutl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gt2cuejgayg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2eoiximye.html

Java: list.add(0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2benxhreo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuanzx.com/Article/details/gt2ptwjzwcr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfxhwlpd.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2qhwzowjf.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2moknreft.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2lovpiclx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2rkggylhb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gt2mvuiecbi.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gt2fyojddyx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.316326.xyz/Article/details/gt2zssqraro.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gt2hyizqnxl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxywodu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2wubhytpt.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gt2akpruxqg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2pvdnquca.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2cmuzcxrs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2zhapolgd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gt2csoexppu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gt2hwtxqpjp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gt2xfseosmy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2rgmqjinm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gt2jpulatxw.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2nctuwqpa.html

Py:   len(arr)
来源：http://dali.aizwys.cn/Article/details/gt2hwehzgsk.html

PHP:  count($arr);
来源：http://dali.pycfn.com/Article/details/gt2exougpxm.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gt2nmuvqwat.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gt2tfiomzdl.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gt2fuwoziva.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cylgqoak.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gt2wjnaeqdu.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gt2scbjwrfk.html

[D07] 切片 / 取子数组
来源：http://dali.guowangkeji.top/Article/details/gt2vvoytmlc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pycfn.com/Article/details/gt2ybelbfog.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2lxpeghnf.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2dmazslkr.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2edydleuj.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2qxburyuy.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gt2rkbnakcs.html

Ruby: arr[1, 3]
来源：http://dali.fzhhl.top/Article/details/gt2jsenuhbj.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2mmizeidw.html

[D08] 合并两个数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gizazpwv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhengqikj.top/Article/details/gt2bwcwufzi.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gt2rtizthtw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gt2ikypqipl.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gt2euqniutr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gt2tusezqdq.html

Go:   append(a, b...)
来源：http://dali.meibo888.top/Article/details/gt2mxpwqdpe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gt2odyzatvo.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gt2qshmvvif.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gt2kjynzbkl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukajdoyt.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gt2xdetxhoi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gt2ogbpntnb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gt2wapxhahe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gt2jzyfmjsu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2khobogud.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxosbzhl.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gt2bxodicav.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gt2rhjucqpg.html


<!-- 参考信息 -->