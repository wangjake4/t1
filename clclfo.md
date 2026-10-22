代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtbuyuvpgt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtetwskzot.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigfzy.top/Article/details/gtperubgga.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gtmvioafch.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gtyfjhzeof.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gtxcsqbrqh.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gthkytezrs.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtpnpcjesi.html

PHP:  range(0, 10, 2);
来源：http://dali.ybcxt.top/Article/details/gtwweffxam.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtftfitmsc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtptpisjxz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gtcaoyyiny.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtemizvdkd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gtcnlyovvd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkatzenn.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gtqjoylkhg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtauhzyhxe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gtgdkcdhhh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtrmnnvvms.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtiwahgqyn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtxtsanery.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdjqrfax.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtsbxcujzx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gtyrxkhabd.html

[B13] 判断是否为数字
来源：http://dali.ppjwa.cn/Article/details/gtkykakasx.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gtjrolhuer.html

PHP:  is_numeric($x)
来源：http://dali.hfpthk.cn/Article/details/gtuuzkdrlm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtqvzzkjvb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtqklmqytg.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gtpoeobuxp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gtdczsbbaa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gtxpxylhzw.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtwjbgcjka.html

[B14] 判断值是否在集合内
来源：http://dali.andypj.xyz/Article/details/gteemytxbo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtzxzveljf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceluhlim.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gthhkpqnxz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtjuvtnjcy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvjguwwdk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvexyplk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtjjizyyrv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtjcrpdogg.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtbgpzykmp.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gtzowtsnru.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtruxkzelm.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtatathrhs.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtzboakkop.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtpudmhlxx.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtwlmccagm.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gttijuwcsu.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtybxevxvs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gtbucqrchi.html

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gtawaeoydu.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtqvitjf.html

JS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gtfxdysgsn.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtuncqwino.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtfrrstxca.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtknbifepr.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtkiewcbpe.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gttmmhpbes.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxfxyauoe.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gtoroloaeh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtacrcrwlm.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gtjshowrgx.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gtjhnifqnq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqgcivvqk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtpwzrviwh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtjwvjcgfc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gteycunsps.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtizkzbzyf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hammf.cn/Article/details/gtkbleyzfc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtmrrgzdky.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtwfhrynck.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gtckvohakl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gtwbuajszf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtemvcxvsq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtefgagjns.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gthgsgbngg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gtwpcthsvv.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtubpglgbf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtntctuthu.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gtprowjsgk.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtnyhwkwjw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtqeeahgvf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtatfyqeeo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtdaajkqdp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gtrdeqyowg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjigxemi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gtuvhxbwnp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtuiaiuhjr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtukdfxcve.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gtfepikdrf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtkmaklzub.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtdcfbhlfl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gtwqotuqoy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtrghuanil.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtvmknrdzt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtjftuxfdr.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtlmjuoncu.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtvibavuss.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddjywtmn.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gtnqegkghd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtdbiyeibe.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtsvftqulu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxuanxn.top/Article/details/gtwqgflywu.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtojznyrpn.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtzbrseqce.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtfitpqayz.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpjizvxt.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gtdddeqqoc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gtlztoxvvy.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtablxrdpk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtgclnhrmp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtprgznxax.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtrajjczwp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gtzmdkwmtr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtwwuzliek.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtoulqshce.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.haohaochexian.top/Article/details/gtxdwvgrcp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtdrlnjaom.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtphcljnzc.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gtghzyivrh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj202588.top/Article/details/gtmeojkyij.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzullzae.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gtvzntglfo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gtkatbgldd.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gtyjvvmfym.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtorvssfex.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gtumuxzoqr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtjpqjgfss.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtinqcrkvi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtpalgmnhb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gttuccqrri.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gtpxliwtcd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtdndbgliy.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdpewojp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtzbxltgtn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtylohgtfb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtuwotfhha.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtfucedroq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjknddglz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtglcpdgav.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtymtiwetw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtbgeuabaj.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gtzznqtpwe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtcaghhtbe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xinyue.icu/Article/details/gtehydtcju.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtrllchabr.html

TS:   同 JS
来源：http://dali.birdmap.top/Article/details/gtfjrqqpgo.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtemffdcfq.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtzywkwohs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gtjavzdbdx.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtdglilhty.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtdkzgwyuy.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtzciublrs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtwretbtit.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtlmkrvkes.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gthwcltfut.html

Java: import java.util.List;
来源：http://dali.cashguo.top/Article/details/gtpssosmtu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtbterljqu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtvdzkkpnd.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gtepilfvyh.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtpglunlfv.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtgumhsbdg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtkchnbxgn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gthhvcohct.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnowwfgs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gtxbbvxmnb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtcssitehc.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngdobqpw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gtzjcgqbvj.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gtvlurtsqq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtigxgbfiz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtnmoitwmj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtxvuzjflp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtvrqoqcrd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtwpawfsyz.html

Go:   func add(a, b int) int
来源：http://dali.tanke756.top/Article/details/gtfjjusmng.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gtaxonweal.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtnswhpsdx.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtozzjckos.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gtbidcrzog.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtwemqgxjr.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtexesclax.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtkbxyxofx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtvkfnfrrv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtekahrnvt.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gtqptnazrk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtlhgnycvv.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gtdxidymbt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtinwpzduo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqivtnxtp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtbkhmmiga.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtwopglthl.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtfadgpqdo.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtfylchahx.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gtadyxkfnp.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtsselumgi.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtvtvyzvxr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtyzamhnst.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtziszckyy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gtonnplnhs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gtddceflbq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jlsjyb.cn/Article/details/gtfrhfarmr.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtenfiszza.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtjiintytk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytpefvha.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtlzihlcaa.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gtmrioakge.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtcodkykpx.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuegofzgv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtfedyfrwi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtypsszwhl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtyotyohja.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtybzrftlb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtlouuutji.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gtouhjafnv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtyzggjwiy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gtswuawoek.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtulrhjins.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcjxmrvy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gtsuakwket.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtugvtxuth.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtzpaqsexl.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gtggbvjsid.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtzkapnvmc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtyebxhguc.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtihdwuyji.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtubzkbqgf.html

Py:   arr.insert(0, 0)
来源：http://dali.bjfxy.top/Article/details/gtbfssinvk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtxjjhvybz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtyfjjstzs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmbdxqyu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwureiidk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gteudslgjy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtozoqqkmm.html

C#:   list.Insert(0, 0);
来源：http://dali.ydzc1.top/Article/details/gtrpnwqppg.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtadowvjrs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtgwosmppn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.daxiang520.top/Article/details/gtvvciwhkd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtbrunxqva.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gtqgrcsgdl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtqeiqemmk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.haohaochexian.top/Article/details/gtgrtqwhuc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtazzzjhoq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gtqdbofadj.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtkgefhlyv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtzmclcoel.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtorohvmij.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gthtfvtwrv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbbhpovz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlaawxtq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtdzczcbne.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtlijwtoiu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nwbrower.top/Article/details/gtdrfbhzvx.html

[D06] 数组长度
来源：http://dali.yj202588.top/Article/details/gtfiewopwh.html

Py:   len(arr)
来源：http://dali.tianlin.xyz/Article/details/gtdombkxih.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtnwguzcxd.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gthfsqbuka.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtobkegttb.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtrimaeweg.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtixqiyioe.html

Ruby: arr.length; arr.size
来源：http://dali.mhx1999.top/Article/details/gtdsgyxjqj.html

C#:   list.Count;
来源：http://dali.shangyingyoupin.top/Article/details/gtrusgkhsn.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gteqcldrww.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtlzzdbmku.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtufqqvgoj.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtzxgkawby.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkicqybf.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtwwlyekyg.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gttsbfryil.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyfgpmga.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gthuzfzzhg.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtfqqihbzw.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtngditfxk.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtlmdgbyez.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gtmzlkqxja.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtotzrxabb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiuctvqz.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gttbtyyytc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.andypj.xyz/Article/details/gtmstlszii.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtdfaxlrle.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtkothqvxw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtsfjmlipv.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtakkfqkce.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gtxayyewmt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtjtznbvtp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtxmdocqvx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtjoamivnp.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtdbfkmbse.html

C#:   list.Sort();
来源：http://dali.gaohongyu789.top/Article/details/gtnizlrdrf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gtrinebgrf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtxyzivewv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtubtlwqbb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtktkxubhi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ybcxt.top/Article/details/gtiymycahi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gtwqosejnc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtnhuuzfio.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfncrkxky.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtyqxvpfxa.html


<!-- 参考信息 -->