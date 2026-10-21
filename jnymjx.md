代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmygtzhgd.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gtpegvupmm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gtenrrkfnn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gtivhbrzne.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtqfspwjbb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtpcszovzg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgcrcbqv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtrlqetkem.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwcwejzw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gtrqphyyeb.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gtmyhbzwas.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gtkrakbjwz.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gtazvslpfm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtkfcdqvda.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtlullpzrb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtdyeqhjtq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ppjwa.cn/Article/details/gtuuqwvaqj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtugloowti.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtkhieidjz.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gtfpfohkpw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtmjqeoyls.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guannengcc.top/Article/details/gtgmtxrliu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyxlxoxa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtvyhuisco.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtjmvbtnvi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gtheuysljq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gtmiwcwevg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gtritvdwrb.html

[B13] 判断是否为数字
来源：http://dali.yj202588.top/Article/details/gtkelzthdu.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gtazrguhxj.html

PHP:  is_numeric($x)
来源：http://dali.jqgfzy.top/Article/details/gtkrgpkdyj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtmzpxqmsy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtzgodvykg.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gtkfandxcw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gtrtaicmui.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ppjwa.cn/Article/details/gtmfutfpiz.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtnjqrerdb.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtnkvwhouo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtohxwhobk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtsirrzyfy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtkpxdkhji.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtjrnxnfvh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtqjowxowa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gtktgmkiom.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtdeysnihx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtyqzajmcz.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtigqdluot.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gtlwrnfkeg.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtcfgyopqt.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtfinjvmji.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtjoejddzk.html

Java: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtcrlabnhh.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtzxqvnmzv.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtuffnosqj.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtczzgmuhl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gtawbxhjhw.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtqrcybhuj.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gtbfhplupr.html

JS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtduyrekpd.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtdtmtpxvv.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gthufzuvtr.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtluzrvnjn.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtnynhkvlm.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtasihizik.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtcwhwpyur.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gtulhuwvlw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqvktrwsj.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtrbexyhbn.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtjaziqtew.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtnbiuzvdu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtbgiktbic.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuwhhkjoh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqynxjnm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gtqjusvmya.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gthjjjmmdv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtygtvinvo.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gtnwwjwtsk.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gtpxrbyysi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gtdxvybarp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtsjtvokcu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtrpjjrfgq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtcgokzuvm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtwmoakyoh.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gtsqezvhdt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gtpnsidzlq.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gtnkdbdlcc.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtiefosghi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkgugzvyu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtskxcblhg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gthdierlyo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tian-w.cn/Article/details/gtfzgunemx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtoqqkrdst.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtknablqyt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtekpelmub.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yongpay.top/Article/details/gtbrzjllvh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtwzqcxczk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.birdmap.top/Article/details/gtykobkgma.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtzelugitq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtabbzezsa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtfjklhwgh.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtvpxxaqvg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtwllgbhrt.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtmgdoblzk.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gtkwjvewov.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtzbpncbdo.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gtbidcmvtd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtulfayjdo.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoecajvyf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtzcutxowf.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtvhtezsyx.html

Ruby: return a, b
来源：http://dali.xylfe.cn/Article/details/gthnrulelw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gtlxmqnfcq.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbatqequd.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gtqjunesaa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenlongwang.top/Article/details/gtpcobadbi.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtdknzdipr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gthoxbnrsx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gtivnzjcwb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtrasfzorp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtypvnacpi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtxoyyguya.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gtwakeermm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtrrfrrndg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtalpyvnwn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gthfyyfuzr.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtjhwjdusz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gtzfrjijrs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gthucxmhac.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtaryrtxnu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gttpjhzknl.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtwbwatsnu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gttogsksrd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtnsrxwspt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtmzgkqzok.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtlbvglbjf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gtudqcubep.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuanzx.com/Article/details/gtftutmxld.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cheryme.top/Article/details/gtbvuhxlfz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtcgcehhbi.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gtabzbueyw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtofaupeym.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtslrwglnv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtpyugavzb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtlnhpyqcz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtnaypwhca.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gthpghvvut.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtopbuzibv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gtnuyntkti.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gtdjanurwt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gtdoilnmmy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gtneyyapiq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuanzx.com/Article/details/gtonztenov.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gtsswsrdoj.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gtlvmflnex.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtgteqfazu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gtyzjbuigp.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtdthrlmgo.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtechrjfdx.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtjlkuizko.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gtmajbcldz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtvauqgacw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtpgunzokb.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtbumlthwj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtqaxgdokl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gtmmbcrfvp.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gtnvzozmyq.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtylotxqwi.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gtdptzubkx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtwkeoyoyy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtziyqvmmf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtlxvycjhv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gtrrnvoicy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gtjmzkchfy.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gtcmxrufcr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtrlxuojqx.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtdxrdtrnl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gtzpbsbykc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtbkqjcwhk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gttrlarlnp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gttbsgvrlk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrmzjvzmh.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtwfomwwhe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtjpajbxui.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gtsqwjneam.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtbnibbqra.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtwalqvzce.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtnsinowlx.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtwmappasm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtvarvhgio.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shzxlz.cn/Article/details/gtyzahbpul.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtzfrusxqq.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtbfhprdru.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cheryme.top/Article/details/gtgbmntsuh.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufxmwggt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtjrxxzlgn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gtsabbypoe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmrifexqq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gtawdxodch.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gteejdbqak.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gtdchexhpf.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtsqmmavvr.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtuqboyviu.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtxuqnufsn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.snrcjt.cn/Article/details/gtrnrunuuz.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gtvkrdjthf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtcorhpmuf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtyiwueewe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqazrbgmq.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gthzcxjymh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gtcdzdsdtm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gttqrdgwas.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrrovxjkd.html

D. 数组 / 列表 / 集合
来源：http://dali.shzxlz.cn/Article/details/gthltfraio.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteeqrnfpp.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowclbgfk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtmmpdhbpu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtobiagbqq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gtdlvzjxbj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtaeotqznl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtolpgtdar.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gtnifsfuhc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gtmqaqzzgy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtnhukoeim.html

[D02] 追加元素到末尾
来源：http://dali.dianchejie.cn/Article/details/gtdscaaehc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtcogiftmv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgttabvsu.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtjkkcgxmf.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtuvpwzakv.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtwwwybxeg.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkwlhgmt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldbmrwsi.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupvoputy.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gtqonbqpxa.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtichhkmxd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gtljibkcjh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtexuaaykp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtzadfqxkm.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtzviksqft.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqxwclkw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gtbkdmjlbo.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gttzmxvdkm.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtpzelwutb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.redwolf501.top/Article/details/gtwqouzpor.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gtrilpmcoc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinyuanbaomall.cn/Article/details/gteipwqvzf.html

TS:   arr.splice(0, 1);
来源：http://dali.aibaodan.cn/Article/details/gtciljwqgg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtyzlubhnf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gtayaqodus.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gtpddpogzw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yangfankeji.com/Article/details/gtvjuqqkdq.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtetpcugti.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtkymswkwc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtiqawplve.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtafnafcpd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtuoteobbr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gttzjlejrv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtdnticxoj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtcrzzrgwn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtmwjrlgdk.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtgomgmrur.html

Py:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtnwnhkqys.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtaipqauwd.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtsimmoahu.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtpzvneheu.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtsixdbgtk.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtfrnmaonb.html

Ruby: arr.length; arr.size
来源：http://dali.cheryme.top/Article/details/gtwrwwyzjt.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gtnfyqmxnv.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtzmvqrwpd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gttlefexiq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmqoiieh.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtshzeuzvf.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtlrinkwhp.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxohtenk.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gtynggvjgb.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtaaadfeke.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj20258888.top/Article/details/gthgovzbai.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gtcdkgleql.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtstaqdpww.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gttrrbdfmn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ppjwa.cn/Article/details/gtmuwgabwe.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuxqwvov.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtsvdlfhfc.html

Go:   append(a, b...)
来源：http://dali.ppjwa.cn/Article/details/gtfuhfacrn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtultsjxmv.html

C#:   a.Concat(b).ToList()
来源：http://dali.ybcxt.top/Article/details/gtkzmvaene.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtwktdyyhf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jlsjyb.cn/Article/details/gtzmasqrec.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtudvrczjx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hywenlv.cn/Article/details/gtzcpdguln.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gtyzsjuebw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gthfwtqkvi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gtyiwxnnyf.html

Ruby: arr.sort
来源：http://dali.dianchejie.cn/Article/details/gtfklwupad.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtzwrrlhyw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj202588.top/Article/details/gtaucyytwr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cheryme.top/Article/details/gtbssfqbwg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gthgguhusx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdzhmljl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtrfxgnycg.html


<!-- 参考信息 -->