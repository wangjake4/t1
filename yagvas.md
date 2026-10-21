代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gttiylbmhv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtjlzxfawx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gtfblievxg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cucudq.cn/Article/details/gtoocmeain.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtyjbiwgeu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gtuzdaeuec.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gtzfqtcqnk.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtrbivnnvs.html

PHP:  range(0, 10, 2);
来源：http://dali.yonumen.top/Article/details/gttnetzrhl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtigikalcx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtuyzbwcpk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtrdorurap.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gtvbvsxfji.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuyqikuh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeixhhxi.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gtconbfjpo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gtthovtgwz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtekscwtab.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtglbajoum.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtzptgbvvz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtzhwqbdxd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtofhabnpm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gtjcehbydx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gtmkzcotxh.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gttitiyroz.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtdwucidwn.html

PHP:  is_numeric($x)
来源：http://dali.shzxlz.cn/Article/details/gteswwyfhq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtcxtmzksx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtumqkacvu.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtqikzylte.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtkllsamux.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gtjsgjgljg.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gtdgdxutej.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gtxntfbrnc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtzxtuvppa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtyhphbhvr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gttfdpyfmj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtzsevosro.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtcjzwfymy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtpqqlsprz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gtkoufaucg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtoabzxvgn.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gtvqmbvyuu.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtxhyrupky.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gtwjhkuhuj.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtlbwndutd.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtjggihcvl.html

Java: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtcptkiuff.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtcimisupc.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtncsegkwf.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtxjkxsqyh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gtrnvvdqfr.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gtuytfqhtt.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtsvqzeebt.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtttcqfurc.html

TS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gttwxbwvfe.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtukrftoqw.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtqxsnlmva.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gtnuzbhphh.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtcisyhmdw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyeahzqin.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtfhvyhnad.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfhuavtoi.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gthltxyetf.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gtnnyghkrg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtvzymqutn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtxoathman.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtltqyyejw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtiabmkelz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtffmxxhrr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gtsdmjpqrd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtpkkvwigs.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtjepgsama.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtnzfmslhf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtesuemsgo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohhworow.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtkctivzya.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gogol.net.cn/Article/details/gtqnmbwpmx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gtrzhwyebh.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gtqamsfgbd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhvtwurx.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtwpyqxbdr.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gtmpjofjft.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gtbugkfzdv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtumknugrr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtggdvpank.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtxtrnkbcm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjregmkv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtfsaksiaa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtahfrvytq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gtyufrthul.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gtohnqjvpl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtnuatfhwt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtznbqmtug.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gtfxdfmmzo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtoirzutmy.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtsaxhykpt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gthcqtlkgu.html

C#:   f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtebtwzfww.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gtqtowgdqm.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtdndxvrwx.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtlofflfrs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gteesoblym.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtswjoxyrr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gtpteowxlk.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtkxmoowef.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gtsqxggyae.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtjreoxyjk.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gtvkjogujz.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtapudusvx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtibcxwwwp.html

JS:   const square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikyrhxac.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gteqnztszh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdimyvzcv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtkhtczrjt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtnncasjbm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtjkippeid.html

[C07] 把函数作为参数传入
来源：http://dali.haohaochexian.top/Article/details/gtcqwipyle.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gtjzbdddxd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtaqyrgtbe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hongshengwenyu.top/Article/details/gtqbxqqsem.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtowuryhzx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtuztxwiba.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtjclwofre.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtmrdvvplu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtlrhylyqp.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gtwnjidnxj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gthfghpzpr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gtidrdrykm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtdllmzdts.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtoablseir.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gtkjeevhyy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvkblezp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtvgxraiza.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtfuemfkym.html

[C09] 递归
来源：http://dali.sufxvd.cn/Article/details/gtivnsawsk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtmrvfjysu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtfnwnhrxb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtcmyykgke.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtojxylcaf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbxjbcrnd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gthvitpexn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtjlbugojh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtlvtvxxeb.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gtwblrcxuh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gtgyqnfxwa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gtndhezypz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtlmhbkxxb.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtgklycskp.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtswhntpll.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtpjlqzvkj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gtemndbibt.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtgvvajczs.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtpbvnnulv.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtehsymq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtfdpkzjus.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtqvfpofno.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtozlupzzg.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtmbtsenat.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuetiantiany.cn/Article/details/gtqwjtooka.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gtjumcozvk.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtyluppxmr.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gtwcxamgrh.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtpikpxaph.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtwgeaokjo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gteoxobzmd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtkuythqiy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtbgjjrqsd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtlmclsfnm.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtcehgfwhh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtlmnekxsa.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtulgbtwfk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daria6918.cn/Article/details/gtqsyrxbak.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtrjnlnues.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtbvwuhouk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtskpdxpwg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtqlvttebv.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gtuuupxdfn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtindjykwo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shzxlz.cn/Article/details/gtlyxwhngg.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtqgaoiglx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtuxotsffj.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtiqztmezd.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtyfmvdmbs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gtscjaklrd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtaicqujgx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gtrlrmtgfe.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtjcvoivou.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdpicwlo.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gtdjxmkuxi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtztxmuybh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtibigzhwb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrnsscbes.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gtppcpcmfi.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gtkvyymfmj.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gttujqzlfl.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenyrmqtu.html

C#:   var (a, b) = pair;
来源：http://dali.hnqzz.top/Article/details/gtvmvphaca.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gtiqeqyaic.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjeqvjga.html

PHP:  // 无重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosbssmbh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtdwujdwxk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nwbrower.top/Article/details/gtvrkpcpfx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtzyeczgzn.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtgfeeyzpy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnisogeea.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtempmibuc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkmbwukmi.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtsjialqsl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnrdyfcmz.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtyhparjru.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gtotpesptk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnqzz.top/Article/details/gtuuncxxtj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtjzwqmcqq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfqkbxgb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gtuqilxjsm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gthimmusvn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shangyingyoupin.top/Article/details/gttftygykf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gtbwanriam.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtsmrgggrn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtmikczrez.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtksaeqlki.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtrpwmqbhp.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gtjagkrcnm.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gtcgipyazb.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gtwllcuuzf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gtkokpsyri.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtluzzizxy.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gtzztsbezd.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtngttvrkp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtjsbionrf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpclovliu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtzebwbjsx.html

Java: list.add(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtlinjkrkk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gtyylosxhr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gttbmtthpb.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtgwekqjyx.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gtseovlfpq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggztqzmv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtbxtbpenm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtzdrikqlr.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtcotlhodc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtravnylju.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gtcdpqkuem.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gtjvxoczlh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.iojbl.cn/Article/details/gtcyrwhyvu.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gtgeknnsrf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtfeehypcl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkolccyjd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtzpulolnh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gtcyobqwnf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtyyyppwhl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtbyquqbwp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtxbgljsnb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtlhggzycn.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gtdyfczfkc.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtcgsepqoq.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtfimhcnen.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtzpsemaoe.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gtpcyehttu.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtdixtyjyl.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtbpcwhmaq.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtulpfnvuw.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gtgqtqytcy.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhfrvkuu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gtfavpsamy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtpjxfbbtl.html

JS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtwfkykgpi.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtzedchiry.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtdiznaapj.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtcwooxamq.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtmlulcswt.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtajwoachv.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtslfayqwr.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gtduqsvtrd.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtrkfyphar.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pycfn.com/Article/details/gthrmokauk.html

TS:   [...a, ...b];
来源：http://dali.zhengqikj.top/Article/details/gtldfbcgpv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtwvkytvry.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gtdscgwzjw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gtfiqqfacb.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtgomjiuny.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gtbackxntl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtwtpbmrxw.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtzezmoqed.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gtbprjuesk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtjjfrfjnr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnqzz.top/Article/details/gtmnayefqi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtioqsztqw.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtkxjxuxsw.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gtygvsutqo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtmfprcvyz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtbvkmggnb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gthyquxuoc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gtahogdbbm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtwhjfswuz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhixingplan.top/Article/details/gtdlaxdrld.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gtgherhazm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzjbopyl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtprlxvdqu.html


<!-- 参考信息 -->