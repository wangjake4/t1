代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtveepmpyk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtpxqofyae.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnnszbash.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtffzdajjl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gtqrqwhyks.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hammf.cn/Article/details/gtlavsqyxt.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtyeygajkl.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gtsojgbqqc.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtoxmoxrpz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtyaqwcwlz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gttbzenhxn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gtktyejtxx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pengpengdd.cyou/Article/details/gtzyracvto.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gtzmilcikw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gtbdwszkhw.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkzmpclk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gtatimalpw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudoejjeu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtwsmkxwjb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtkdbzegpq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtyduydmri.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gthdanqdbn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gtsrhxukie.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtwiyebcil.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtblumpykg.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gtumivmvzg.html

PHP:  is_numeric($x)
来源：http://dali.hfpthk.cn/Article/details/gttvcxcscv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtxvcjhuzd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtntrohywz.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gtntkwktxz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gtusnaxvmo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.quarkkingdee.top/Article/details/gtrghvwwkp.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtbecrwohl.html

[B14] 判断值是否在集合内
来源：http://dali.yueranfly.top/Article/details/gtkpnrbrov.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gtwgxnzebc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gttgyuwgoo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gteuhzqxce.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtqcvfhtgn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtircavggi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gtxkascwxr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwrbnltp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtplfrrwdo.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtndfmbkcn.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtgsngclon.html

PHP:  $a && $b || !$c
来源：http://dali.jianghu66.top/Article/details/gtnnkrrsqd.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtbepxtvuy.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkidlaig.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtwugduztn.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtovxyngjv.html

Ruby: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtwfjzbbdq.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtjfqgprlk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gtmtgqsmah.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gtydaubmmy.html

PHP:  if (!$data) { return; }
来源：http://dali.sxryk.cn/Article/details/gthfwlfdgk.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gteqkwavwy.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtpzlankoq.html

Java: if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtduwzgndm.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gtlxraeijv.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtaatjuyxk.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtcyklfefu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtobndsvsj.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtdnldzmmo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgyrlebtq.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gthenaxqlc.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gtzhhcxhsa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtgraihsmc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gttkpxbdnv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtcikmfdrf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gttmklazoa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtavgajmgh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gtbbodaoml.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtrhoyfdnf.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtnjpkarlx.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtcdinbndp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtmdfluqjy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvmdsnavx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtuftqgdzk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtfuvqrfvi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gthbuiagok.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtfvfldbyt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gtjumlsblw.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtsiynfvaq.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtvityjffe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzrqbmaej.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtlscraaku.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtqkjrsaof.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.andypj.xyz/Article/details/gtrdfqdbom.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtnynmqdna.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtwddcdypm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrmyhtrx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gtixkguqdg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gtsmhifghj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtefsocmng.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdyuxtlok.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtblljymac.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtsrlnmibl.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtupjpepeg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtcnqenlws.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtgaukxaji.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gtaxhezmif.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtggeyunlz.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtnszwnzwc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtoxsagpps.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtvconwfhw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gtdusxhycq.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gthxxbdeii.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtnmkdrvqz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gtviirypkq.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtgjxdgsxc.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gtnvtbhdgg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwhfvaog.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtbibkaime.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtaiubcczw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtqlryatzf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gtngynnbgn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtbftdovim.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtvjnkyixx.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtqxblmmxq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtfdsdgoai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtccltvyrj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtqxlxytwr.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqglrukko.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daria6918.cn/Article/details/gtcdzjesmk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gtbkhxlwwd.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtamrordri.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gtngcqfldv.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtavodznpp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gttigssaln.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtktffvpvo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtbhhessnq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtittctfvu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gtdcpodmww.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gtxqyrxvab.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gtpijvbiem.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtyvndulbh.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtxoyjwsym.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtztgpmszk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gttbahkkua.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtwklnfenr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtdcnrlbyx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtspwmtbhn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtrcllqeel.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gttnfydtjc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjclqlsaj.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtscqukmqk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtovclvtpu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gtqnfkxnrp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtlezvydmx.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtvlvwwpsi.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gtrvyhihmr.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtezguinwx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gtsunbhsmc.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gthajvjgwj.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gtmuecgyun.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gtjmssjpsd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtrtfjinqu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtezzxomzf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gtqtitirxu.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtlairqseo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gtvhxfyzgi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ehwqpu.com/Article/details/gtgmncoano.html

C#:   using System.Text;
来源：http://dali.zycfv.cn/Article/details/gtnqytukrv.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gttdgytuld.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtwtnvhshz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtokrzprys.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtxreubabj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtbrkcssxi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnqzz.top/Article/details/gtxpnafjic.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.kuanghao11.cn/Article/details/gtybrlmovq.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtubbxoasd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuanzx.com/Article/details/gtqreuhmbm.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gtoctfnscq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtkuhqqicj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtahdemyxw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gteytdcfds.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtsikajeya.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtptjphtlk.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtafkcgbko.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtcdmqoyea.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtopxtflgc.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtzyfwfwjt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gtyblqsmtx.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtwixhamdh.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gtpeojxrde.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbwevggme.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpklftvfi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtuvhmuxfg.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtvhrnlmdi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtqqdfkqtk.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkbijotr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gttlwcgwva.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gthbgzkjmv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtztxneawt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtbdprgxxr.html

Java: // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtsstgkwqv.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gtmmbryhyf.html

Ruby: a, b = pair
来源：http://dali.feifeiyinyue.top/Article/details/gtjpijihdj.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtzmyhjmbq.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtraamhtff.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigfzy.top/Article/details/gttxidymlf.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtbxuxdwdn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gtkbrywfvd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtlcevuyvb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gtofblqfat.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gthcxfynef.html

Ruby: # 无重载：靠动态参数
来源：http://dali.pengpengdd.cyou/Article/details/gtmreazwkv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtswovrwkq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtyibngcaa.html

D. 数组 / 列表 / 集合
来源：http://dali.zdqjudy.top/Article/details/gtcfmsjyqq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxuavmsbk.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtpwoubiid.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtccmsptfd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtghsappde.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtpwyqamfo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gtfotqeyay.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtbruivbhi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xziqi.cn/Article/details/gtwbezzouh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gtqodmwujf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtwftzmjuc.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtkwnmqaar.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihqsuoro.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gtbxhiboau.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gtumijfvus.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjavfkbbv.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtihzqxszq.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gthjeqxjdo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gteihlqyhj.html

C#:   list.Add(4);
来源：http://dali.gotoacloud.top/Article/details/gtefuwwvxt.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtbkqyhzdz.html

Py:   arr.insert(0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtmehdyuqr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiphypun.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gtfegtxupw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gtnqzmnpfh.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtnbjatmjx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gtcpdarwiw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gteknaoirr.html

C#:   list.Insert(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtchsarknq.html

[D04] 删除元素
来源：http://dali.andypj.xyz/Article/details/gtadqvjrss.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtnqbzlfwi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtjnpgyudu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gttzfpydzi.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtptuwtktd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gtivfeadvc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.havefunace.top/Article/details/gttfzzljnt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gttdnbqabs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gtmuuhbjpo.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtnkyiqohw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtoanoycrf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gthugjcxfk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtggwbxzam.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gtlyzdxvea.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gtesznjexb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtfqljhpxk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtlwkpcoed.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtftxizrvr.html

[D06] 数组长度
来源：http://dali.kuanghao11.cn/Article/details/gtxfyhktsn.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtatbqvmpm.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtdxtpgixo.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtgpropuuw.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtthhxfeau.html

Java: list.size();
来源：http://dali.bjfxy.top/Article/details/gtsdjyrnjn.html

Go:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gtmqcrhsil.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtfgqimcfp.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gtblysbsvi.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtsazviiry.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.snrcjt.cn/Article/details/gtkifavwvu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtoaeotbfd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtzqhmwzxn.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtasbokivh.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtxtlsmwqq.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gtirsiizik.html

Ruby: arr[1, 3]
来源：http://dali.yj20258.top/Article/details/gtohfonqam.html

C#:   list.GetRange(1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtynsrqqml.html

[D08] 合并两个数组
来源：http://dali.nanxuanxn.top/Article/details/gtbwiuqamj.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gttlraolhl.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gteamvahkk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yongpay.top/Article/details/gtlwoutpxp.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtjmwambzr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.svipenyu.cn/Article/details/gtfgrvhwtw.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtlsmvbfli.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtouaqzylx.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtsrxadteu.html

[D09] 排序（升序）
来源：http://dali.yanxiufei.cn/Article/details/gtahammwwi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gthixmxjdm.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtsvokyjim.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtcjkyztzc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtpmskrzvf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtwdmsvbct.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtllsoqdpl.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtizztkykf.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gtqgxfoawn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtonaigsas.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtholyklzh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtvgzyfmwk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylmjiwth.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtucozngbj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gtnbpcarcm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtngiqshnk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtyvrnhhqi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gthvtgyvvy.html


<!-- 参考信息 -->