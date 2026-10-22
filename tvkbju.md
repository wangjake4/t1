代发 wailian999

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gtohutoopj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gotoacloud.top/Article/details/gtmwtghwda.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtqxmzotar.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtujuzpvai.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtzuteonnt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtcivcplvb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtncnbvxiv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jiagoushi.top/Article/details/gtapkujcrg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtwregxbwi.html

[B10] 遍历同时拿索引
来源：http://dali.sysykeji.top/Article/details/gtrhlbagug.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gtlyjncdhe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gtbjewwted.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtuxzilcqw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtilnlbiqp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gtudareqni.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sxryk.cn/Article/details/gtlxhdcaha.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gthduzzrqk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.redwolf501.top/Article/details/gtyjywtbej.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtuearsokr.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258.top/Article/details/gttkseoity.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglxmkrtz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtnpanlkuz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtdoobxkiu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtjogqazgt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hongshengwenyu.top/Article/details/gtsqoxowjx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtwjyhrpwu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtfxrlablu.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gtzwmtzunl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpltwlah.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtfndjsndg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtzotgeiiw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtnsfqvkxo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtmqiikjsj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrftytfco.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtwjgopgpt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtuhbxksff.html

[B13] 判断是否为数字
来源：http://dali.cashguo.top/Article/details/gtqlriltlv.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gtainztije.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtslrjspdf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gttgculmju.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtgsalsqjq.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gtiavowruz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gtqupmmxgx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gtbelflqjq.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtdspdqmby.html

[B14] 判断值是否在集合内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdokrvnoq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gtrdpkejum.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqomqahn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gttcqqorwh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtmausgbso.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtzfwzdqqs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbyapoly.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtiyjarbsn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtwvcexqpf.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtxqoqqsrs.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gtwfpyfmdv.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gthmjgrmby.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtgghakkib.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtqxzgwxmk.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtyvisjkrv.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtkjpwpwfe.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtlqpdqhge.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gthiwipugi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gtdqkmtyjc.html

Py:   if not data: return
来源：http://dali.ehwqpu.com/Article/details/gtjdiaixss.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtwwvmkmia.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtpugqsydy.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtcckmiomf.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtyxeijull.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gtdvsjgdjc.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gtkqootqzj.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtsuoaqmul.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkykozrx.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtlaoikcsh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtjidigiwe.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtnwqdkyug.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvrjxwqe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtbpckaaqa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrvpsgqs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtxxclazgq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtzaoigxis.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvxaobfm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtnmlcabli.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtvlftbpcy.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtocikmcjv.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtquooxror.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtnweyzsdd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtggqibnro.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtrbfjkywg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gttpbfokar.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtylsouctb.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeorjdpm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtgwwemars.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gtewscwdua.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtgbyoymym.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.316326.xyz/Article/details/gtbtymacvr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtwhlgdzon.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkxnzwehg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtghzflitu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtonygqpwp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtebmaenef.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtlbylgluu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gtriamiwfr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtsuyxtwii.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtrlgctuao.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfmmcnbg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gtgvhvqbly.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtuiyagjxd.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtrxjboqwt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtlgwszfft.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gthuzelcwg.html

[C05] 返回多个值
来源：http://dali.andypj.xyz/Article/details/gtrhegpxqm.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtuikdblao.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtzrfdbzmd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtzvwgsofo.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtfhugzbbh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gtjtxmzkge.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtpmapihsa.html

Ruby: return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtoorewngx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtotqqrurd.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gtleqxujqy.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gteyvyorfh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtxthpjszs.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gthwywncme.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtzgpyqffj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtmiyqrxpm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cqqwz.cn/Article/details/gtspzgjjoj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzddtfeqa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtysasjehz.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gteqtfxkbj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gthrtcnqyn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxepcxqp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gttajdplhq.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtqclzqgrj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtmawiropi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtqqeubuny.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtbjhnxilr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gtqggjgyst.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gtstughwns.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfwpdtlw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gthugctbrp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gthckejddj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtpljzmebu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtyrjnhgyo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtedjmkwyn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gtxngrcece.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtxrkllzin.html

[C09] 递归
来源：http://dali.vqdsnc.cn/Article/details/gtcgsszpyo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtjwkprhdb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtzlwxpgsg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtjbdhgucg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtsfynadlf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtdkwmudve.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtitcdehtd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtltgsjkkd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gtwwzyxosl.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtomfmzmjn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtrngrfoyo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gthpklcwdd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtuldxbdwt.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwqisren.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtfaziuzqr.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtbafojevw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtbiupydep.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtugnlqgvt.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gttolykpjo.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtrjousayg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daxiang520.top/Article/details/gtdvnuuafv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtjnbyreit.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gtvrpeqiyl.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtgmoplytb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtwgzuyisq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtrpuoajnx.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtrmzcjgpp.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gtthoagtum.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtsvagfhof.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gtfjumcomo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtwtrrqtpr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtuvesyxma.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtiwebfbus.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gtscubndos.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtuhdogaqy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmaviinlt.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gtjzffatdm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtdsfwjahj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtzrsvontl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtjgpyemmb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtpgujmxsm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtllrlpoqo.html

Go:   func add(a, b int) int
来源：http://dali.birdmap.top/Article/details/gttzxfneie.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtivuqxlyb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtksqvtwka.html

[C14] 泛型函数
来源：http://dali.yj20258888.top/Article/details/gttawdgysb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtelcieqff.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtipgfonls.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtspztmyqu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sxryk.cn/Article/details/gtgicbhoaf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gtcgqnvupw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gturmvwrcn.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtjrieghvs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daria6918.cn/Article/details/gtrkksqbwk.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gtmqcgbiuv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoslummbw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gthvtrkszs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtibqqaavd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gtmknvrvbs.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtqdlckivb.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtppknkktd.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtmrcqgklr.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gtbtshpkde.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gthjbligym.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gttydxnljo.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtjdkbfaem.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtqtsiazez.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gtakzmfzfk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtrvqbxavf.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtmbjgjvxm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gthjiibdny.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gtngyzwidn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtfhsuivte.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtwvntjwhv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjhsvdnin.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtrvwsdqas.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gtksbgbtid.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtuhintqrp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtwutcpijo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmequhmqk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtkyskvdtw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtpcwxftqm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtuavokwvz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtcrfeibjg.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gttvzvibuk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtotrxogxs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gtognopcdj.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gtiryszceg.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtbugqxkvy.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtjkbghjlh.html

Go:   arr = append(arr, 4)
来源：http://dali.hywenlv.cn/Article/details/gthayznemp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxnzgylg.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtgrknoebb.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gttizlftxf.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtepqexrqc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtexiuuymz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqjjgrdj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtblbeuhoh.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtkpsfykjc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gtrnbyhexy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gtavsattav.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtxduukzsz.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtdpitaabu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gtbwwremck.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtuiqrmwlv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtjiajmaeh.html

TS:   arr.splice(0, 1);
来源：http://dali.pycfn.com/Article/details/gtalkcdmfe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gtireiqqdx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gtbkpodklm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gtqmdhwudh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gtsqlrqryo.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gtqrrboyms.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtkaohtuwp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtqvpgsqyb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtvdmgytbd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gtpullllug.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.quarkkingdee.top/Article/details/gtsitceaco.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtpujgcszp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtprvbizko.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtludborus.html

[D06] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtkgzzezye.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqshahdyw.html

PHP:  count($arr);
来源：http://dali.yj20258.top/Article/details/gtmfjonsvy.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtvdtadlvq.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtnhddjfsb.html

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gtxmedrwtm.html

Go:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfhxmflsh.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gtwuhwimkv.html

C#:   list.Count;
来源：http://dali.gaohongyu789.top/Article/details/gtozklqdnb.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtbmvqkoem.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrujyqlwd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtaqeirjmn.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtirmrdwvt.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtuyszrwwv.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtjrtnsjiw.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gtoawzabra.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtmtzzrhax.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtbqiwwpta.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gttvmzzdst.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gtvthtnuqr.html

PHP:  array_merge($a, $b);
来源：http://dali.jqgufenzy.top/Article/details/gtgrmcnkbz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gthlatewle.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqauktjti.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hammf.cn/Article/details/gtkbxkfzfe.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gtaboouphl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shuidangran.top/Article/details/gtirlwzykr.html

C#:   a.Concat(b).ToList()
来源：http://dali.ydzc1.top/Article/details/gtdncjtymp.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoisjigu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtsvgipmcf.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbsrgobl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dashuyun.cn/Article/details/gtobmcvgbo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gtfmdfkewt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gzhubu.top/Article/details/gthzdzwubf.html


<!-- 参考信息 -->