代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtjmtfdpif.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtiumhxvdg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtktsgfzsz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gtvwjkblkt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtjuredxzq.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gtfekoojkw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gtiseebkdm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorcdeuxd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtdwhtzkyi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtocexieyu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gtqscvurjt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.smart0.xyz/Article/details/gtltbekaoj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gttyvthtnt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yongpay.top/Article/details/gtoboeagmu.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gtqpomumqf.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtzlmdmjkq.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gtxxwzhjpp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gthwowpmla.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtmxbwflpu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dianchejie.cn/Article/details/gtrfvsugac.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangdashe.top/Article/details/gtgdwdbquc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtdlctabzs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtgvehdlyp.html

[B12] 跳出多层循环
来源：http://dali.zhixingplan.top/Article/details/gtpmixwnwn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gtjclyvuoo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gtjjsjgfwa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuctrjtaf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtiqehpjxv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtpigpcmfj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gtijmyarkt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jiagoushi.top/Article/details/gtrgdimsyn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnnnikpr.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtmtmlgzth.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gthgryxsci.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtwvonelwu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtmascrlkl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtowxgonvo.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtnnhybvrh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gtuntkmckt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gtyomdevxz.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gtiurxpztk.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtoxocqfrk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gthruirwyz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtprppwswh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtpcrmbpuq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtuqjndtyz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gthxqepksk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gtblgzqdxd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gttphmznju.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtmngviubg.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gthookwkmq.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gthzasgary.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtbpxwavgd.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtxwiaejvs.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtqelbcfcy.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtqbqftzkp.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtsdwdxyvy.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtpjujbmor.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqvjmxkl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gtytpzupdy.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gtelputzac.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtpoksekvu.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtlldoqkku.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtguahgupq.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtvtqxagwk.html

Go:   if data == nil { return }
来源：http://dali.cdnleiting.top/Article/details/gttmzskrgm.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtpsqfbzzf.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtywiwxtdn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrkgfqks.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtajmtzpjl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqltnulqe.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtlpbxvsne.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtsjuzowjw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxgkbfcti.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtlpsbfczi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtexpujgus.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtpiscdags.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtrjealnpg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gtzktaxivd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtehefwrsz.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtznjlyvoe.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gtzspjhewy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtbnazrzcb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtlnvctfsu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtymuhcaks.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtsixufqjp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtrewhabhq.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtgbtnhndg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gtleqruqyi.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gthzrpbfhk.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gtxnqkywxo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gtliuifyfp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtnfsnwpeg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtwuidprje.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gtozdpexos.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtejxctjmr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtjkssfytf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gtvvneapvg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtkmretrvo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zdqjudy.top/Article/details/gtozgiizxo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtdbrlivrn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtokcmksdx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtcalsgypl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gtvjdkolbw.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtkwdvsmat.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtewfeiwhq.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqbrhvupn.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gthpmxknrx.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxvvdprf.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gthjwdhxpa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtujmamsdo.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtxvxxiqck.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtjdnjmtop.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtbpecsoxu.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnauzchnz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtlltydgnp.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gtndhwucrr.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtlwocvect.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtoazkqbeu.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtyfhbcwka.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gthwselbxb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gtsencukll.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoftjdunr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gtesmtimxk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtesrzspzo.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtwmeqhzvn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gtkdjavdtv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtfvbxkeck.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gtalmljfcw.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtguhaahkw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gthrbwwqzf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gtpapqfkob.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebpdppne.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gtafibreis.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gtiwfabvfp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtjyvwkxjl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gtfjgkzwwa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvwkrasnr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtwotmsgwk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gtbdhedjgf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtvpgoisff.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtmewxsnir.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gthlhmxrqy.html

[C09] 递归
来源：http://dali.yj202588.top/Article/details/gtgqyxootg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtmmbxjksg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtnmattvmg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtabnbillt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtvgeelafq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtfnzdankw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.meibo888.top/Article/details/gtwguynbfa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtryvfzmms.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtgbsijoou.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gtprqjiewy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gtkiacning.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtqopzxezw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gthlzyltcd.html

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gtaexlnilg.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqjfnziv.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtwmsgvohr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxssljug.html

C#:   块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtrtrkewyb.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojhzbhbr.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtctlqyxfk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtzhlgcdjb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gtkrsmlntm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtlzfwxrvp.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtddfoisby.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtarqqohnz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gtbequfisy.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtkioigygp.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gtyyaujpct.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtachtdszi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gtutnsnkam.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtallnecnx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtngwjetcy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gttcgbowws.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtfexvigre.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtojjfnfew.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtmvqyautx.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtzuewunkf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gtfkmbucnb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtyslthcex.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gtzavfuzhk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtvqhvvfsa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtvmdpozqn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtxqiulhvj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gtbyopzjyb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtyzmncbad.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtojtcafuo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtamuvkgde.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtiwdytdnm.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdqhwxdz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtsmphikbm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yangfankeji.com/Article/details/gtjinvdncj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gtxozoopfk.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtxojlwvyw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtfajhbimk.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtwiwkkboy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pycfn.com/Article/details/gtrolqcvlm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gtldrqckey.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtqwjjjqua.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gtthtayksl.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtywruyavc.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gtunbljfxh.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsvyzpqj.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtafiztqrh.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gtrsabvrmc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtshosdqbo.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gtkbyqplxs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjfkxjyw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gttafhthwr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtpgbyyyqt.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gttolnbuwt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtjguhwgqw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtbksrjuid.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqubidxeg.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtnydobsic.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtrglbmykc.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtxahpmkjk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtumcwtbrz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gtpcuaagbj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guannengcc.top/Article/details/gtkjrkwdpj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guowangkeji.top/Article/details/gtnuukxoli.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtcifgpomk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtmdpmfssf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtzlcpizmk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gtittuxjsa.html

[D02] 追加元素到末尾
来源：http://dali.iojbl.cn/Article/details/gttejymshi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtuplxafzo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gticzzbiwr.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtinpnttwa.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtxbuxvbmm.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtcmwthtgt.html

Go:   arr = append(arr, 4)
来源：http://dali.nwbrower.top/Article/details/gtcmxevnom.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gtblhzygva.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtbrcqkbpb.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtkxyssklr.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtezyuttuk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gttkhljsmt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gtegcpfsgq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtpxkbfuvw.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gtflhqopqx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtznhwmqmp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtvxbfakgx.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gtbrocnsux.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gtdimyeiyb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtxtzrelex.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.316326.xyz/Article/details/gtfsinmrvl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gtnujkpilz.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gticjqroba.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gtmbwqkjsq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gtfcczbqfw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtbjlhparh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtqrnwahmz.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtwgoeiueb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtwkgtmuai.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtgqwubcbd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gttolbyvbg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuvxcmmy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtnksziwms.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtzaejselv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtobimrlbd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtpasipyxt.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtbqdgoxfq.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpmtvtaz.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtnpfjqfvq.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtsqcpesil.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtlusrjqkq.html

Java: list.size();
来源：http://dali.dashuyun.cn/Article/details/gtvipouepn.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtqhkajjsw.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtzhzhjfbz.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtfkwcafcq.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtvrxxmlal.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenlongwang.top/Article/details/gtymxnfzna.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sysykeji.top/Article/details/gtqlxjgqll.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtdmhglneu.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtaurjafwv.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtvsdzpgud.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtrypvkhqy.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gtcuzokhjb.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gthvkqngxz.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtlyueehzh.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gtasvsytrx.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gteepjbjtj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtpbxcmrvv.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtwtbbvgmf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gthuiiiikq.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtkxixvhqg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcljocsyp.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtehgehyry.html

[D09] 排序（升序）
来源：http://dali.yangfankeji.com/Article/details/gtrbewyxqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtzzqcrzbr.html

PHP:  sort($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtmttkmzjl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gthqhzyqqb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtpircyclr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtfkpcelil.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtfjgksxuj.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtezvndhvr.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtdafltdqg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtobvoisjq.html


<!-- 参考信息 -->