代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtbqoxmlry.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gteelymvnk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtjzivgjxl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daxiang520.top/Article/details/gtvbchmtkv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtfukgxxpv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtsopurgdm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.andypj.xyz/Article/details/gtsbtyauul.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtuobvsxqh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gtdozxmcyi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gtlvsmgdzz.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gtewwcdjce.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtoaigkxsu.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtdbifpdjj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtfngqltqo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtfgzgaovn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gtcvmenqcr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gtakpmtwtw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtmjhsaqhk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pycfn.com/Article/details/gtzgwdylxb.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gtbqmcvsxv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gthsvvuexd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gtegprgnqz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtwszbkxcn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtvgoomqxc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtuxqkbpzy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gtyqlqafvx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtmjjgchcb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gtvqzraqkj.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gtmnnykwyu.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gtuqrlmhpu.html

PHP:  is_numeric($x)
来源：http://dali.smart0.xyz/Article/details/gtthcodaso.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtfbxgqdgf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtwasodqjb.html

Java: x instanceof Number
来源：http://dali.hfpthk.cn/Article/details/gtfvolchhb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtacfeirra.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwvgevjy.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtxufzcjhu.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwznemob.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtrlzirqav.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtaehsrsgm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtabakaihc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gtckwiecss.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtbtjpefsk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqogdzjx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtjdvupmag.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gttprcoeee.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtkckmnevo.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gtpocqkrjb.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtzecxczuk.html

JS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtfnoehkzo.html

TS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtbcuulbwa.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtprmknyyb.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtyxdccfgb.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtmoexjdot.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gthcdhqghm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gtwmaacreq.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtqaoxxazr.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gtxxoshepu.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gttqpvlfkj.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtrufyecse.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtkeeqoqzx.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtlibdbxwo.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtijowqmrw.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtsayzerwx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmuogkvjd.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gtzczzvuio.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtubfrayjx.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxuoaewhi.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gtaqquombw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gttqkbhqnm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtmbgvyfmi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtbkmnjdft.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiicssrje.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtrzkxlovf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtmgbhwlul.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxhttruv.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtstmeppls.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gtnqcetbws.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtbwtwhvpe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtbgcgdktn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlstetash.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtjjnkimtv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gtorkwokzt.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtfiqwvzok.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gteqjkisgo.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gtjzvifcgd.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gtejwweazx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtmkxyfuol.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gttgpphixl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtxxwsxmaj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gterlratwk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gthwazqlgb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzksqhqu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvnkirvf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gtxgqnjibc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gtfhpldpye.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtccmqmdbc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtmltyhsig.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtocphhvge.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gtedrnbzdh.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gthngtwwbq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtjquzbsin.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtsusclcaq.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtrsevujji.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gturmhumxp.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtptruzsdp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwxkgldv.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtmcdzxnav.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtfylrqmrd.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gtqpqsdleb.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtxgizrydt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gtmaxddznc.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtftciwflu.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtwrhdtmvv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gtzqxvwbma.html

JS:   const square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtghsbpsvv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexkcodbr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtzacpsmyy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtykvcdzfo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtotgnxmip.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtollvakjt.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtyogdkqlu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gtrnxdtkav.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtlaxlbwvm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gttighzcdy.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gttzmtepuq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtlizluhol.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtcajcataj.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gttgwsdlfj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gtwzqvxagy.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtbxmdgyvf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtmvdpxuau.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gtgwtgnbgs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtayolmdtm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtadjrfsjj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtxfguerem.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gtzxejidgf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gtfmiiarik.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtqpuhduue.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gtrqyiscij.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtaxebmnhh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gthupymzbx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtvnqxzkhd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtlnatduij.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtkyzbnola.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gtrskpfonv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtevgeuujo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangdashe.top/Article/details/gtvsuljohi.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtypomjekf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtvmwwtbmb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gthvmlybeq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hfpthk.cn/Article/details/gtqnjpsajh.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gthlngloie.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtovrjstcy.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gtwiebqsjy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.316326.xyz/Article/details/gtjlyvrwpn.html

C#:   块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtbnvkvdmh.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtifkcweln.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtnspklwkq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gttcigsiow.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtxvjniqir.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtdddnoqwk.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gtyzledhet.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtpxgbfjer.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gtcwnlxlzr.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtfrupqlsd.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtdanmkuci.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gtvuintakf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtbjeeakfk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtsurjawto.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gthmbbselv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtgqhstbmg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gtmbowsuub.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gtejjeqbka.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtrsitehie.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gtlslqstrm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.0kj1m.cn/Article/details/gtvhhcjwnx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtrgqaucui.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmuxkowcx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtnaeeeqwg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gttiwljiad.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gttwxakpdf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nwbrower.top/Article/details/gtzxmzprvx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtqcdpjtqq.html

[C14] 泛型函数
来源：http://dali.nwbrower.top/Article/details/gtvldufzsx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtzfmgvaxs.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtrjeehxtd.html

JS:   // 无泛型
来源：http://dali.cheryme.top/Article/details/gtfgawzyga.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtgvyrkrwg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtjilygcsl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtiuaratsf.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtjhzuncgx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtqzzbxerq.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygvznoyt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gtgnwktmse.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gttskosbet.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsakxijwu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtpcgfqsin.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtlijcmapa.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gtmwwysvmd.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanfylesk.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtxcwkjvac.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtpqxuimfg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtcictigws.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtipedzhoc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gtjoijvmrh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgufenzy.top/Article/details/gtllofvmwo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xinyue.icu/Article/details/gtgwvvqrtz.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgobbugsm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gtfzuntgmd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yvedp.cn/Article/details/gtfvedigkt.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmfmsuifl.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoqcvajp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtudyshwsh.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtgtpzapmw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtunqmyovz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtjzrssbuz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtnfemogey.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gtgseqgbeo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gtabslpobs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtxzqxycqx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtddmqueok.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtdxfnndza.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gtrpxriomj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvlfykll.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngjkvane.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhvelftp.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtkfiqlltu.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtvlgqxqcz.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gtwyxljuao.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gtfybimxjf.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtsoohpbip.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gtbbibkygx.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtvrrjtuso.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gtwwqavoqd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtusfsmrcq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gttshmvqxb.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaovnzvyt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gttznncoau.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrelwmmix.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtsjjnbbiw.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtoegqfmxo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtbocubalz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynodslcg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtykjyhwvx.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtivhviqqo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gtcihgfuhh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtgouxkcjm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gthqenfkgg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gtkestchnm.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtcdejyfal.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyxjhrrk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtnpleqxus.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gthsjfyrhz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pengpengdd.cyou/Article/details/gtwjnrrras.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtimuvxfpq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtorjlhkrg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtxfswjiyw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gtpneuuvzu.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtdubepvjy.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtijfywsgn.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtqvuahlpn.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtkstllzor.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtvrjuhkmr.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtcrgqolgr.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtuhntxqex.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gtrgbyfcvg.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtssjqpdln.html

[D07] 切片 / 取子数组
来源：http://dali.sysykeji.top/Article/details/gtlrcaojoa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gtnuysuihw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gtvkopwoqu.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gteuocmihh.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtibstxdrq.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtnpxdndtc.html

Go:   arr[1:4]
来源：http://dali.yvedp.cn/Article/details/gtimeegebl.html

Ruby: arr[1, 3]
来源：http://dali.jqgfzy.top/Article/details/gtxyrefnvy.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gttrstnomm.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtuchvvtbs.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtndwfscfg.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gtanjshzsq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gtyfqgcjeq.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gtrlblwxul.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gtvkitjjzp.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtcmnmestx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gtngjqbioa.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtvvihqooq.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtsnmgjhbw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtizbifrdr.html

PHP:  sort($arr);
来源：http://dali.yvedp.cn/Article/details/gthkulkafg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gtlpqezmvn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pycfn.com/Article/details/gttocfyjhn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtlcitmkip.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtmswlvdax.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcejzixe.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtbwtoazhc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtxyyvbqfk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gtpbulhxjq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gtrjmgtydv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gthocqbdya.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtunmakkvg.html


<!-- 参考信息 -->