代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtogvlblox.html

[B10] 遍历同时拿索引
来源：http://dali.9152youxi.cn/Article/details/gtbeihhcfc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gtlrbnvjcs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjrbzwgy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtvnlusnek.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtvsjfhkwq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtwajmtznn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.quarkkingdee.top/Article/details/gtcppcsaaj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gtlfasktpa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gtjovcpmaq.html

[B11] 生成数字序列 / 区间
来源：http://dali.shzxlz.cn/Article/details/gtnipxnnki.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtdqgjdgfz.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gtdaxuhcty.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtzflujins.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtalchahqx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gtbzbzsvxz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gtveqmhpnj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gtnuhtxubh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtvjfkwucz.html

[B12] 跳出多层循环
来源：http://dali.cashguo.top/Article/details/gtrkhzhokm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gtrvibvhag.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gtaoybqjhi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtncoicure.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gttcpgxptl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtoxjpgwlp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtravhjfin.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpzmabww.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gttaitrqdz.html

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gtrecwjssv.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gtjmeytcue.html

PHP:  is_numeric($x)
来源：http://dali.jqgufenzy.top/Article/details/gtttippocr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtzbsuixzr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtqfvxiamm.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdlykegm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gtxcmycwvw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuanzhike.top/Article/details/gtupyhjufi.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtaetbzgla.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtktobivch.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gthmmtrilg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnxiangtu.top/Article/details/gtueidnwqt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtbnjzzimj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtiipetpux.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtxdloajxe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtbfamqgrv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtvkzuhwwj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtimeegkls.html

[B15] 布尔运算与取反
来源：http://dali.fzhhl.top/Article/details/gtvsohevcg.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gttckctvzj.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gtugskofit.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtqqwstjjo.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtfwefvlsr.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtqaakrcjo.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtnbswcbjc.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtxbbpqsfu.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtudyfqzex.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtsefybxyv.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gtrgxokrqz.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtbegwrxme.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtyzgpfddy.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsuividi.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtxrfdocnk.html

Go:   if data == nil { return }
来源：http://dali.cdnleiting.top/Article/details/gtneredvwt.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gteohzzgym.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtuixrmvzo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqxfmutuf.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtkemjbyqe.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiskzypjd.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtlgzveaao.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtejpbbpuz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtpdexsyos.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtlsximyid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtrgvgoayh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtxgielhpw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtkerabwyl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sysykeji.top/Article/details/gtbgetutpx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtxrskqzof.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gterhlhhxa.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gtexlwvatl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtrodkxogy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtvwnceacy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtfjqzmzww.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gtupjuejpo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtvjjpeygf.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtdihczwmm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtinbkbtfg.html

[C03] 可变参数
来源：http://dali.sufxvd.cn/Article/details/gtedwpbjon.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gttzxvdbor.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtcivwppoj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtpzgnspro.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtrbzwhxms.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtdhsxhkns.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtijfnlvuu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gturaoxrvf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnxiangtu.top/Article/details/gtlppugtwd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtyzwjbsjn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtcxkcig.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtyapyvlaz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtcycotpur.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtwufqhkal.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtrnroobuw.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtzrxavyse.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtmhqidloc.html

C#:   f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtopdqtzsx.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtuzvosgvi.html

Py:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtwfcsjiwj.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtuecnsudk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gttgrzdtzl.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gteajngboz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtcjxdvjdh.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtshfhwwvg.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtydzgzyrp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gtohkjyttl.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtjmovdufo.html

Py:   square = lambda x: x * x
来源：http://dali.hnxiangtu.top/Article/details/gtxgvjoxey.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtpsemumii.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtyjyguuom.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrnlhdcv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtwlqcxgam.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtlhtbrupj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtapgtvvsy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtxzpanert.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gttcrrueml.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gtzlvhissy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtprpmyare.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gtqxvhyoal.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtewfhdoys.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gteagkdnqb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gtimgpfoar.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gtoyftwskf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtupfazvyp.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtwbhqdjve.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gtcjftwcvm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtoevzunvv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtstfzcmoz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfmrhfnuj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtcqxswstx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtikmrttkk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gtssrknxjv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtnqcthqov.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtrsdghjid.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtctczzdel.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gtciqijykr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtwqwiomnl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtsepvveoc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtmgzrrock.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtgwjappjt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtrcbvxvky.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gtbaeiulot.html

[C10] 变量作用域
来源：http://dali.jinqigufen.top/Article/details/gtlkqjuwkq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtojktjyzf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gtjguxchzj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtllxxhecu.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gtgfqlumfb.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtdajeummy.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gttdhfytvp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtuoshxilt.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtmjajvntx.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gtlxhtahbl.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtpjeaiprh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtjvuyilig.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtstdogylb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gtfjceupdl.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gttmohfuyx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gtbgczbyxi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtmwpdaskx.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtpiufrhvs.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsfpiace.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtxhtxdjzv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtdafxijch.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtbdgmysex.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtimzildjf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitgvwcch.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtzsguxmqo.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtbrjqysjw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtgrwrptsz.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gtouvtaemc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtxalrvzca.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtylpbdrmu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtrnxvswha.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtotcuqrwh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtqobccjzv.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtsjulmvty.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gtnyscnlfz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gtgrgfqere.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gtfkyncmvh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtkdqfyhkx.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtwbpvqkru.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtjlyvixkq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtiwsayqia.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtkjksuyzi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtczsjtpky.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtrmdwtdce.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtrqmccpzg.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gttuivxjzw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gtuuwysncy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtwrkzonmd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtmrptfhdl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gzhubu.top/Article/details/gtvddtghqy.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtbaqobquz.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtgbolelat.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gtgmzzpwnw.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtegugdgtq.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtjjagqmtt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gtekdizvpt.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtmvwrcjls.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtaiwqtqgm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtecnroqnh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gtjkzhaoij.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokuzbrtu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtavhceqgc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtzvuekpnt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgztamcpj.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtmqpqjjlj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcjyunlpg.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtjsoqbgha.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtqfglxfft.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shuidangran.top/Article/details/gtbihnqgpp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gtvdnwjkyd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cashguo.top/Article/details/gttkazypoi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gtzhaxyjkj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gtixnkrllh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gtvyozdkxw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtscvkefkv.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtfilvkljd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gtiyrdhgyu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gtydnhkytp.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gteooepzwx.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtspwownrk.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gtrsbttcvt.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gthhosjrlu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shuidangran.top/Article/details/gtrbvwzkym.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtabycdszz.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gtioxwuymy.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtilbgrlwy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gtkhlryrzd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtnghyolih.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.meibo888.top/Article/details/gtabpktwnw.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtipowsfqr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtvlkeqncz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gtdmrpzjmi.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtjrxojwbw.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gtzqwujjde.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtjxswihcy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gtunnwpfcf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtdrzvxjmo.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanxcqiiy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gtatwsybia.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gtpyaxdsdx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtccirtqql.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtcvvogoow.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtcawlxocj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtyrfzjzpz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtoruyylud.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtodoxknje.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gtiocbkhgm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtqkqgaghs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtqynatwwe.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtxumcktqd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtbipvczkc.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtcalywwyr.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gtwozbyjne.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtqjueauby.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gthuhanbty.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtnzuknaue.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gtevqpvhpy.html

Go:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtdlevhnsv.html

Ruby: arr.length; arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtjbofloyf.html

C#:   list.Count;
来源：http://dali.guannengcc.top/Article/details/gtznupmgli.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtwqdsrnwj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtuuydzasp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkzpdvtc.html

JS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtkaqgtnrw.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtcxwlxibd.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtujrxsjtl.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtbofccyiz.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtnleppfin.html

C#:   list.GetRange(1, 3);
来源：http://dali.cheryme.top/Article/details/gtoussqocr.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gtbrcmmbtj.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtehrmmxha.html

PHP:  array_merge($a, $b);
来源：http://dali.sysykeji.top/Article/details/gtqsdqtbeu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cashguo.top/Article/details/gtqcnivxpz.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtgmlobvjd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtpfrzteql.html

Go:   append(a, b...)
来源：http://dali.tanke756.top/Article/details/gtuvlcgbnc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gtfueqlsie.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtcvhemsqk.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gteivfeuou.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtvtmpedmw.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtzvnxiasz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gtrtdinpwr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gtrjdqnvgy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtjdrdcgch.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtuansqdto.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtpqfagiwc.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gtchsxuaus.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nwbrower.top/Article/details/gtxmmxavpq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtffiapngc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgdtuynn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtmahflhcq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtsozsqkrx.html


<!-- 参考信息 -->