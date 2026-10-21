代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmgeiiig.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gthcebvqxy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gtudyofyrk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gtwzawowjm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gthceqtqes.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtacwhiwbz.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gthgmzyrhc.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gtofjtdalz.html

PHP:  range(0, 10, 2);
来源：http://dali.ybcxt.top/Article/details/gttlcntzuz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtqnbjmlxg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtcrdjhrpn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gtqnnspzgz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtwlwauege.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtntjsacsy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gtebkcxnva.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtvhisiknt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gthbhssllm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gtvccoonjg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtmlmoxovp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtvlfvhybz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtpizkdxfs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.c1oappe.top/Article/details/gtwtosqdpe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtifwlvksr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gtwqdfmeet.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gtbobfsxsb.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtlexipwyh.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtkheckzfh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtlebiixkm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtdfjrqewv.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gtaudvqfud.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gtjlnhkxgg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtcywrrljn.html

C#:   x is int or double or decimal
来源：http://dali.yvedp.cn/Article/details/gtraentzmp.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gtbwhalebp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtvfmnmdbj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cucudq.cn/Article/details/gtefpxpuku.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gttcobfpkv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtgprzvggt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gtmidrxktc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtrtyuvwxn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtyiawrdpw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtgihvknod.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gthsbpvkaj.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gtersafkkn.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gtejiawtap.html

JS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtdnqlidyg.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtecgsaxdk.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtgwbhliuz.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtewmvgoaq.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtnowolduu.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtzoqrijbw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtlqrghyhm.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gtkrfkijog.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtukfwubve.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gthzbjcugk.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gtzlioyzmy.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtuuwuceth.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtkxaxfczq.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtyhjwcpke.html

C#:   if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtraaqobug.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjmcfdvzy.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtptmchzpt.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjdlnzhut.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtybwbspjv.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrkhldtn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtkldsazbg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtgyodwqrg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrikoeasj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloaqegop.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtiwffannk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtsjprqbwc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtijknewqw.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtrudacwsi.html

Py:   def greet(name="World"): return name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjxmvuby.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gtuqikitzm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtjcybpuvu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtqjagwcea.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gtxdsospvx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gtswrjlddu.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtfinlckmr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtqvkijbpp.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtnaeoqikc.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtoqupbirs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjkodkgrk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtcslygtro.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtcpaacmzt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtjqtwqkuh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gthcwgwnnw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.smart0.xyz/Article/details/gtjvqocmvs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtrlyzqgby.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtepacowbu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtlncholmw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtvukvmlzm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtpqpznxnw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gtnggetxcm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkavsxzq.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gttyauersp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtqupqxani.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtfksupgke.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gtojvbkobh.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtbezfmslz.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtcdgdsihw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtodeiotii.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gthqtrmfzg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtocsjnwwp.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtzhmfdcye.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gtmnyxdszj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtlnysbwrs.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtzqormpon.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gtrwyyfelo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtmdcmfgjs.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtgljwuooh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtraatwoyq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gtgdfcbobu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gtvclpkukk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtizhdtkqp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtlcohdsah.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gtrqrtwvtk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gtarzmoexk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gtlrcralwo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtutcyvwdw.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtktcshezq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gtlhlnufip.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtxxwyvnsp.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gtpuhbjqjs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gtqgfuehjt.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gtrnfuxjmn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gtewtjwhsp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtirvcztgw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtxzctljly.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtwptobrcb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtgeqljzdv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpuxaexg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnqzz.top/Article/details/gtmhojlnvb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtjqlcsmqy.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtrcvxgdgi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtozlbbaka.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtuetfjzqc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtmbdiqxnx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtumdmkhss.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtwgzfepqr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtjikobbef.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtrlmnikpr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gtjhjgjuyu.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gttvcwvrym.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gtuydkoxts.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gthxehpfjr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtdbqyefoi.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gthhifiowu.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtbdmboxnc.html

Go:   花括号块级作用域
来源：http://dali.c1oappe.top/Article/details/gttharliju.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtzwzjbeic.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtpytvuxyb.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtqutnvrvj.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gtainpudbo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtvyvnylmf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpnddfccz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtscxhmreo.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gteqevdyri.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gtjdhinbvs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtbptqvweb.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gtohwuzbzk.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gtfyhuxyna.html

Py:   (lambda: print("run"))()
来源：http://dali.tanke756.top/Article/details/gtcrfzpzuk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gtogyjrfzg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gttbaavxzp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gtbtzpquny.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gttgieiylc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gtjrtmntgq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtityxjfsm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtucdrbxxf.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtsqrtbxgr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gtbsxfmlsn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gthocrqzmi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtlpubqwiv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtscfrfkmu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmosznadv.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtgaokumnr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fengsongda.top/Article/details/gtofvirhug.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gtkjfxxptl.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtirbfibcs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtyohbgeoe.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtozylfouq.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusmzqgeq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtallozkgm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtutxrdzrf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtyhsmxtqt.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtelhgykww.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gtmnxtvbeg.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gtlveebhml.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtzcosxnpp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtjxhtsbih.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtujkkxrds.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtsmumihgv.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gtveroaqyp.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gtudarzasp.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gteexyqhvr.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtugyvpgys.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxfmovdn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtmeyvktht.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtgejjeeyc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtjbbqpsxf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gtlvuetqzi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yueranfly.top/Article/details/gtqytmqudu.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gthnkmnzjw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gtwogufwoa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtdnnkurpx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbogzjtzh.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtprumrovs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbhxajvcv.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtbfkcpmgn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtyzpebkfv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtcodlitma.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gtxlqvpwhv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtothuyziz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtxvbbpqjt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gtadeyboks.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtgsinlrqh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtvnhhoynf.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtculgsbiu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.bjfxy.top/Article/details/gtzfjcnijk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtemittbig.html

JS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtrnntwbhx.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtegeyzerf.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gtknpwxkqg.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gtygkevmes.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtymkfweaa.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtgoniheat.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gtehylhhlj.html

Py:   arr.insert(0, 0)
来源：http://dali.yuxming.cn/Article/details/gtqqebqxbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfullher.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gtcjjjsyov.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gtakaibdak.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtdxglwrwp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gthiifulva.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gtivmsouru.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdwwdwmz.html

[D04] 删除元素
来源：http://dali.cucudq.cn/Article/details/gtrirdfcxq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtsogcjkkp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtdlrhvhyf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gttcaivcpv.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtfczilako.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtibdeoujt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtkuiqaetb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xinyue.icu/Article/details/gtwsqojvqp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gtbjdoskko.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyhspedg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtxavmlwhm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gteqvutklg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtvuniustl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhiwuduotai.top/Article/details/gtpclkyvpp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtpukvnbjm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtluaxopzq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtppbjguxo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtjojrlveg.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtovrejhry.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmrthfgdv.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgntmwit.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtvkupatcn.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtwkehjkws.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gttqrtgcaw.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtvmnbcgnv.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtivpnzyze.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gtcyomortq.html

[D07] 切片 / 取子数组
来源：http://dali.hywenlv.cn/Article/details/gtotnexjkb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtsltlhznm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ppjwa.cn/Article/details/gthxnimzgi.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtxsaoqult.html

TS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtomlmeezl.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtaeotzeeo.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gteowqlnct.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtxigvpywt.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gtdimmzvcg.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtizbgjuya.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtlxfgkkvg.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtkpbgugpy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtiyzljefl.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gtjcxttyck.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtpxmvyxvr.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gtreepimok.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgufenzy.top/Article/details/gtkqsxpcoq.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtnwopcmei.html

[D09] 排序（升序）
来源：http://dali.zhiwuduotai.top/Article/details/gtqrphtgbt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtxqzwzxmn.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtscjgnmoz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gtequucxoz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnqzz.top/Article/details/gtpwvvksbz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gtpsxytydp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gtwmuvuefq.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gthuouuyef.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gtviojched.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gtaestymil.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daxiang520.top/Article/details/gtfjkafuvc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gtccfptvyn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gttcxdixbh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtgiqcxpxv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtwukeuknc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258888.top/Article/details/gtnnypzpqj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gttunvvbmc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtjzpuacct.html


<!-- 参考信息 -->