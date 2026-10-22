代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2umutophc.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gt2uudepwop.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gt2fngfcvmi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vadcxhqk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gt2dusehqsw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2giscqkia.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gt2tjsafjht.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gt2twkgtnmy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuanzhike.top/Article/details/gt2llnhggly.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gt2ffwqjgif.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2erupsnlz.html

Py:   list(range(0, 10, 2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2stoqeuny.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2npiemqxo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gt2uotaesff.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2rnmqncoz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gt2wlirdmwz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrcciagp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258.top/Article/details/gt2ackxsqrm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gt2aixarabp.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gt2vtgiggwy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gt2wlmomwwp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gt2tfxqmhio.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gt2fydstcdr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvkucurc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2ucpfofuy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gt2exdrwumu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnqzz.top/Article/details/gt2ajofnnqn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xziqi.cn/Article/details/gt2oljtjhaf.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gt2dztquwwk.html

Py:   isinstance(x, (int, float))
来源：http://dali.jianghu66.top/Article/details/gt2wncqcdce.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gt2ncpoedfc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gt2wpiqngqo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gt2ckdndbaq.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gt2wssfeqht.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gt2zglfzrlq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gt2huqvsxqj.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gt2kiykjvyp.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gt2zioqvteh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gt2xpzxeiza.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gt2cdytewhb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2nxyonqly.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2uttpaqhm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2jsooznqc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phcunhbr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gt2davhgcff.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2jqizmavu.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iixrcpwl.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffccdnlw.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gt2gftveimj.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2oyjnqzhz.html

TS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2dzxdfaab.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2anfdfrqq.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2urqtjmpi.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2rbnjobgi.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2mimbvxjd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gt2recepsnv.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etxxfzwt.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gt2fgcjgfvb.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gt2acjirznk.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2xeosyytw.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2kxlrpgkb.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gt2cfioxeyx.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gt2ajndmqfp.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgvmluxd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2xjrqlfzg.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gt2zsribuwz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqohwjze.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gt2nhvyfsja.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gt2svmulczu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2rwbmcjgj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vsgykzjc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2ympwvlvj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgwpiffu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2yhdjjnfs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gt2cvgdsyoy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2ncshfyjx.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gt2ljvdmbtz.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gt2afdhvlrp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifhzifaw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2smsvuepp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2wohckjyo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gt2jwjcsyvt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deftbeyl.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gt2cuavhfdj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gt2nrgvazfd.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gt2swbwtwdf.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swxzeozd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gt2eowanyto.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2kjzzvjcn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gt2rnbjejgg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gt2bdmqzqdv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gt2wvsrxyyo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gt2gtrbamaw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gt2pjkraatc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gt2zgxokpqk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gt2alsisoqo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gt2zqnfiuvr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2qvzkgkjj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2pdowkwxw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gt2jtqhqrsz.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258888.top/Article/details/gt2makqyjct.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2mlgfnfvt.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gt2bjmwdqur.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gt2mspviogo.html

Py:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2flpsgckt.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gt2sdaflkeb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gt2dufdtfzk.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2lyetdjcc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gt2wowsxwzk.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gysvefht.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gt2fthbkkre.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gt2pzjbnjac.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gt2zmfwpctj.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gt2lxodompb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gt2mlhxtasv.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2emppssry.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2pylozcrs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2ieujamyd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gt2vidlqiaz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gt2pozskljw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2rabjnufl.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gt2glastwmf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqusibvc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gt2gfxhgruj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mdjqduce.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gt2gxksrieu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gt2okaxlkbl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwymleqv.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gt2wxkcgruz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gt2okhzvjgk.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gt2gwchkrdr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gt2lszryhbn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.redwolf501.top/Article/details/gt2hyuhwdcz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2byxcremw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2alqhjuhb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nitdeqhd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gt2hoiursdq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gt2wvxzrepb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2rguuvwfj.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gt2ipmgvkdg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2wzixwkmw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gt2ixyvtbcb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2wdppzejw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2diydxxbj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gt2qbcdvduj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gotoacloud.top/Article/details/gt2lecpayvk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gt2qffspnca.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gt2vkmmjwtu.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gt2tekcowcl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gt2flmmgvno.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yangfankeji.com/Article/details/gt2hddgnmsz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gt2sreggivi.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2shekowvm.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2kzjgnfdq.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gt2qcepgvdo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuqfibbl.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2vjbhhhkh.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gt2ancakynz.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gt2rffmsqcg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gt2calfxxcd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2djvrijbg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gt2lcwltsti.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gt2mpszinut.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gt2psibceyv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gt2flxdcdnp.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gt2eoaebwpz.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gt2lktecgsi.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tuethskv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gt2wnzzkksb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2fzyfvcfw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gt2qaeavidu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pengpengdd.cyou/Article/details/gt2wplmnxks.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppawgvci.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gt2uehtlgen.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2irqogahy.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gt2rhmwcvkg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jianghu66.top/Article/details/gt2gfvzjfpm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gt2ioqkgbwr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.meibo888.top/Article/details/gt2ffaflvty.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2qbbyasnf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2vadapbfq.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gt2nieixavh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gt2tswsiguy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gt2ofqnffgq.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2arliiknr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2ciwrwdzc.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uomjwzmc.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2xmsnuven.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xeqarown.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gt2awyldvvf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2gnjmauol.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2twfelawy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gt2rmvagkpz.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gt2gsytlems.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gt2xhxwqchr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npnmbfcu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqobdljh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2goqsgonn.html

Java: // 无解构
来源：http://dali.dashuyun.cn/Article/details/gt2ftkmwhlm.html

Go:   // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2wrrzcthz.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2whwibuyu.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbgichyj.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gt2hvrttrda.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gt2fwikfyzr.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gt2wofnxlko.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2ukypgjsm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gt2omtegkpu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2yeluxzad.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqsouoop.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuxcmzyw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gbfibepa.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2pbmpmnmi.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gt2mxlcwggc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fpewewtf.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2uijwyqds.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gt2bunhmyjx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gt2tyawutxb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gt2hdpzutng.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gt2pkrmidcr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gt2iouiplqp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gt2dshxbgng.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gt2khkpgqwg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gt2qlgipujw.html

[D02] 追加元素到末尾
来源：http://dali.yuanzhike.top/Article/details/gt2llqzrouy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gt2boewdfbu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gt2uqosevfh.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2nhscxplh.html

TS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gt2hlxsjuzf.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gt2nddwggqe.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gt2ueiyjoma.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ivvv.top/Article/details/gt2yrpsfudo.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2ptfguewq.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gt2uvstcppg.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gt2ekchnesd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xylfe.cn/Article/details/gt2nbjzjvdg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gt2kedpkqwm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gt2qpjwczzb.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gt2zcqbvcor.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gt2nmavkexm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gt2zsoltfqt.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2ujurprug.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2wcasnhal.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gt2pyshsqsn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gt2nkgbuhei.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gt2dhizzqlo.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gt2ofvdjbmh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gt2wfmglvef.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gt2smleolcc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbrcyvov.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2ubaezhcg.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtrjxhya.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2khlqhldm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2yarctbmr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gt2jjmtovvb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gt2liaaqfai.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gt2lhunweoy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2vlzkvohn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2gkenuagl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gt2olwfnbnk.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gt2dauqzmve.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ykcmyere.html

PHP:  count($arr);
来源：http://dali.tian-w.cn/Article/details/gt2kaanjwmo.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xavjkgzh.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2ypyzjxaq.html

Java: list.size();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvyjahub.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gt2hywsnlcr.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkqkslik.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixpsgrfc.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gt2mzkwpggh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rahxvgfa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2vvzpyvqj.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gt2yonmxuaa.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2fhqldrvb.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isfylpjp.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gt2hjhjwvsi.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gt2xtrgkyty.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2frsdirtg.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gt2nbvonruq.html

Py:   a + b;  a.extend(b)
来源：http://dali.gotoacloud.top/Article/details/gt2vqirujsv.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2tudeqolw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2djxuaugv.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gt2kpvjvmgs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gt2gaqrbcbn.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2hknqtalz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gt2kslfwjqz.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2omxnpvgq.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gt2cbqjuhrz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gt2btsxgdym.html

PHP:  sort($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsvnmwlq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cucudq.cn/Article/details/gt2lahkztxd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gt2attykhhu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gt2toghhyay.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2yjpuajka.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2wviohjrc.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vizvuxau.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gt2kicysjkb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dashuyun.cn/Article/details/gt2amnlwiif.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gt2nsnbdrzh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwbjusba.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gt2qhvqkuno.html


<!-- 参考信息 -->