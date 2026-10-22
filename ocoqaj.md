代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtfukvvsab.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258.top/Article/details/gtoizgjkbr.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtahsufxmo.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvivngpx.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gtckjxwsxm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtwoiphfbo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtczqusgol.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gtiplnadqv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gtdvjqhwgy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gtlknixlcd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtqjhcsodh.html

[B12] 跳出多层循环
来源：http://dali.gaohongyu789.top/Article/details/gtzqxytgkh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtjcsdgpsu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gtpqxxpmsz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtvexovmlm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpyipmmr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtgjakosvu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtdqefqmdk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gtxkjwhsef.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gtoqnnaygo.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gtfzuqxzld.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtkxwpwwiu.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gtxkzkufdq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtzznmofrv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtcwuldiae.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gtxetqjjlo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gtgzeondsv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gtngotdmzt.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gtmzgbcfda.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gtiiausudn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gtdesakgtd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtmfahcvip.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtieemoxxu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtlldfesdw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtproxdlxl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gtwksrihxc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtoqtqvbrl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtnpszjdcf.html

[B15] 布尔运算与取反
来源：http://dali.zhiwuduotai.top/Article/details/gttdpjyzpg.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gtflowxrzg.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbwqafoi.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtkdrlpgoz.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnphejzt.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtkskqqqfp.html

Go:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtedusrwhg.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtgjxvkmwh.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtckadistt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gthwelvvot.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtkonsbifx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtuxmsylyy.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtdrrqeuef.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gtubwjnpso.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtqufbzpky.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gttodexoix.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gtrxyadpuc.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtjbsztdjs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtafawlffp.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtiacpacrn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpnwlkgqz.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtdfdmjehp.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gthfldbhgl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtvpzgicew.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtrptxauwq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtockvfjpd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtfllzraau.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtkajsuafl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtblnqbvjo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtybguuqeq.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gtrovhtfts.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gtzdzyzepw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtkszrxauj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrefuxcau.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtkaylqmct.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gtyehimuzo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarpmnnca.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtsqkdkrmh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gtkqazzjlt.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvmfecnuh.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtjtssgssi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtaltkqdub.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtgnttnbzh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gthymqjbmk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtgqdysece.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtzdgukgkx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtmmuabzyy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gtwlavcpcp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthdrbhte.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiexlvuip.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gttbdvlise.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtewixzfsu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtmmqwqebr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gthrzynfjk.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtchnmiznb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtfchqdzrl.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtjbxqpotg.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtunbygtmk.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtnutuolpm.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gtgxcvqhnt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtlzouovzb.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtlvefvidt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtxuxgrgoq.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtfxnkjuqo.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gttrnupwwb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtmrtcomrf.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtfqndaagy.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gtbidgavez.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gtmjxuumbp.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gteqeligtu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xziqi.cn/Article/details/gtnyfkjsvx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gttaudlzjn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtjfrykkuf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtmwdcrclm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgxbewem.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtdayerioh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gtiqnlhggu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gttuhxknfu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtckbsoieh.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtfxzydueo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtttnagzcv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gttbfkgjqh.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gthqhxqvsn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtgykdddik.html

[C08] 闭包
来源：http://dali.cdnleiting.top/Article/details/gtquzjueds.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gthahghroy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gtqtcydnso.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrjonlnm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtnvarlrak.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gtugqfzyzo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtooemnmvd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtzegbzjvu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtzivbgwrj.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuyzvupz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtjlpwndqh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtgdwbjpek.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtlzgyilup.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtuoagbbkz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gtlhsgnide.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtrjosvghi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtkkrbvcby.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtfqeovcpv.html

[C10] 变量作用域
来源：http://dali.yangfankeji.com/Article/details/gtdpnchwfg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gtmfrwkmdh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylsttaav.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtqjefkdmq.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gtjaudamfo.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtdcjltdpg.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gtugliezom.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtzwyencue.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtnfakufmb.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtdfguestk.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtxailqner.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtwyqauezm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtgrmvycul.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtejqylfde.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gtimqdasoe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gtbzhzyeyd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gthlhfbhim.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtyterutgu.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtglshmzjk.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gtmdgpyidc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtrketntez.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtqmwiovhz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtamuposog.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gthclduajb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtzyywixhn.html

Ruby: -> { puts "run" }.call
来源：http://dali.feifeiyinyue.top/Article/details/gtytbqbmbw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwusxfucg.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gtrvjjsith.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gtdidreiof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcwqfexyr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gtawxpxxjy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtkyuifbwk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtctuorhgm.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtkuqtwcej.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtvgsjfdyr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gtrszngblx.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtomuitcld.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtmedywdko.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtuqxxzzhw.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtjxewkjpn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtzbhuhsry.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gtswvevjxa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gttsezedtq.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtozwvscth.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxuanxn.top/Article/details/gtseawotpc.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gteewadrat.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gtmfihcnqb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gttapzcwih.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtmanyxdwa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtpuiygcqd.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gtycimmhxk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtlhnxjyug.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtgjaururf.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gtvjxknfuo.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiysvtztk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtmgyefjvx.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtvuqzxrpl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtswgiskwn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtbarldzpl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtmhvfnuik.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtavaajauq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtxwayidff.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gtkvkhxqpn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvwlyxxom.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gtjojyggni.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfiujbebp.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtjhdyvyll.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gtubccedez.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtaapwrdcl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtxnhcccfs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtfegnzcxd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gtfhxrfdfj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtxyauoeis.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtlpxtvxgt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pycfn.com/Article/details/gtdzvrmjgu.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtyxfiomgp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xinyue.icu/Article/details/gtjgwuxxos.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.snrcjt.cn/Article/details/gtsycmgaqd.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtqvseifpx.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtmlgfmzqk.html

Java: list.add(4);
来源：http://dali.fengsongda.top/Article/details/gtezxoaxzy.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtwvyzkgwp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhiwuduotai.top/Article/details/gtgocvvtev.html

C#:   list.Add(4);
来源：http://dali.mhx1999.top/Article/details/gtnuhlemgk.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbgzkllg.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxinkj.top/Article/details/gtiarfuuhu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gtvdugbxcv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cashguo.top/Article/details/gtaqawimet.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtwcrjwlfp.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtfasffxfe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtmokbvopn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gtmehgkhkt.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtkcetibww.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtbgmgytop.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gteqsbmjmb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtdokxonac.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gtnhepdege.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtfycpprkx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtzemavxca.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtwtwcokgu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtwehvwlrk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtpzgvbpsm.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtvuvlzmud.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtmpjnjoqh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtqrdzhmwr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtdittllww.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gtlngjxvbs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gtvhwgpexf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtlnfovgju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtrwhkhjnx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbgxgtfc.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtjqnebmlk.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtpmmetyep.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtflwnevyx.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtfoqgjycz.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gteggmsqoi.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gtixnvhdes.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkwmqkza.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gtikkvpjyn.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtfdqyzidg.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gtvjcnrlga.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtwjqvlehn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtwpjcahac.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtsyjklucu.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtvmyzvuak.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtjvzseotz.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtkodjogdc.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtwwawxrqr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtvsfluvba.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gteanzijot.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtvlmkzmfz.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigfzy.top/Article/details/gtyqwavwhw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gtuyedmwch.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlzffkon.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtbiamhrbk.html

Go:   append(a, b...)
来源：http://dali.nanxuanxn.top/Article/details/gtgqxlmcfe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zdqjudy.top/Article/details/gtrdqvheyj.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtpomosmbe.html

[D09] 排序（升序）
来源：http://dali.xylfe.cn/Article/details/gtepioekvg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtvopecoee.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtreynghjv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gtsrmofgaz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvlsbvhp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtltfdqrwk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtntvuleei.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtrzywoisn.html

C#:   list.Sort();
来源：http://dali.nanxuanxn.top/Article/details/gtzggkwbdn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gtsrggohkr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtdkmamrkn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtviuxtwha.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtivimafox.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtuoweplah.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gtmdfxgrdm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtjwycmifo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.9152youxi.cn/Article/details/gtlfkpgcfc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gtvttokebp.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtqkvqdzfd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gtsbuuacei.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtbjbnhtzx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlquuayi.html


<!-- 参考信息 -->