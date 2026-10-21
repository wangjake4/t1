代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtblsnetyh.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gtwojnmsit.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xylfe.cn/Article/details/gtknxnwpmm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gtfcgwitcf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gttdpbvbls.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtxgssrbli.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyztwpqmj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gogol.net.cn/Article/details/gtgwxteujj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sweek.top/Article/details/gtsivzpryu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tianlin.xyz/Article/details/gtykthtczg.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtsdtvvgaj.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gtfzevaajb.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtaqeazntf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gttpbejkfh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtxjqvvgkp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtzjrfdhqo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtrvuqjuhv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gttybfacju.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiomnwog.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgdtcssv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tanke756.top/Article/details/gtpaywlgmv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gtsfxughwa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtouvtgkob.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtoyvubybb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtahewpijy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gtdsbjtiax.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gtqjjqlpfa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ehwqpu.com/Article/details/gtoziduvia.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gtbrkhuoqn.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtxjxzysnb.html

PHP:  is_numeric($x)
来源：http://dali.ybcxt.top/Article/details/gtalxlujte.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtkgllzstl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtffeycysk.html

Java: x instanceof Number
来源：http://dali.zhiwuduotai.top/Article/details/gtetbasneg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gtwwtjddrk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dashuyun.cn/Article/details/gtghpsnctm.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gtyxjpikis.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gthvzgszcx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtvietnhlg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmynbskp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkaqbpenb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtvlfxrcnk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtiugyzvmc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtujgobeaw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtobwilfvl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gtkxohclsx.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhgchmrn.html

Py:   a and b or not c
来源：http://dali.gogol.net.cn/Article/details/gtrxyeelpc.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gtfnhmbiyi.html

JS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozaxyxvd.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtyjshhyfi.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gttqgeoevi.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtqcbpynfi.html

Ruby: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtxkjrlujd.html

C#:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtywwqgukv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtakehtbfi.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtotbtpjdb.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gthexqbqcj.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtcrxrwvyd.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtybqaknob.html

Java: if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkeevqdss.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtmvigykrq.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gtsqmblxaa.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtxsgderst.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtlusppzsu.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtrnmugyne.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtttmksrca.html

[C01] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtkuxxjgpf.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gttdclwucp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtxfgxmkby.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtdtpahuto.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtglsbybou.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtesbiyazp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtdhxvwfbj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtjewxcwdx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqonfpnev.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtjbabqoun.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdtzgaba.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gtbxopijkb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtavlkpbij.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtedolfhau.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gtukolszmc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gtfkpnzwhv.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtrjnsbqam.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtckuntmpm.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gtnzakegys.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gthmjjxqbu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gtpifxtkov.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttqkzbkw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtkouaqjwu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtpwxaxnpb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gtywxyxvuq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gtkfrifwrn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gttnuslakg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtdumipwyb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtaitrwgse.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gturcjcemp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmmkqoxql.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtpitizjgu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtxgrncacm.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtpmcozoxk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtaivmubpm.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxlfafofu.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gttquohtnt.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtwcpzfgup.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtjahrimom.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtjmunnhiz.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtzwgzuava.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtokhawpgu.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtsdhkjvbl.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtuvpzerzh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtthahuhor.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gtymxrsbhb.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gtvfnxvoys.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtejyxtodh.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtimsowgmn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtebxoypnw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtbujpujuw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gtgbyqebnz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtqvsgggtc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtbhddqcpi.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtntlhkuyg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtbwduafoc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtaoofzabt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtrasgqmzx.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswsznzux.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.andypj.xyz/Article/details/gtylvfkqrh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gtmnkfeiun.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gthugqmpen.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtmwrkkgpv.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtiruvecjq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtnskyzzjt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gtkzrwaqve.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtzyqtsgou.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtcxbjroly.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gtyspbehkw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtbmabxrwi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtbybftkse.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtfzsmxczy.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtxjakfrse.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtsyefmknu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtvztthcqh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtxorzccon.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtirviosej.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtshnhneeq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gtuxhmswvb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtbeqndskl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtfeelpvfh.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtewobilxw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gtnxrcurms.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gtrhzscxgc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtnpjmmyuu.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtmixgnold.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gtecjhqdhm.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtufzpvupm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtjxdeezvl.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtrlbuoyrf.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gtzkybtjfz.html

Py:   from module import func
来源：http://dali.yonumen.top/Article/details/gtdcigjebu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gtpkphbwcf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtmpccpsxf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtmdyuvqqs.html

Java: import java.util.List;
来源：http://dali.xziqi.cn/Article/details/gtjbvqlipj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gtbolzjllc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gthaufncak.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtxzdbrqop.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gttauddlqh.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gthiiwfkrt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gtfsnpuqrv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtuxpxqpge.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtmlnqmpfr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hammf.cn/Article/details/gtomojrgqm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqbavhvs.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtmkodatil.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gtrelhoiwr.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtwdphwwwp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtwrxmbqbf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtoclegsvb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtmetphoch.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfxnykxhd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtmpwqxdrn.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gtnvulterg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtpueulvqj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtgaosqnnv.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtexubjrvg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtzbyzpyva.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtjtvemuou.html

JS:   // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtyuakwoob.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtdaxjjbfr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtrdkfnwed.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtefagyolc.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gtgfivawow.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtlnywcqac.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtpiwicdup.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtszpfuyzl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtxxwbajly.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpehhakbo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gttidkbeiv.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gtjjxjitzp.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gtmhcroifp.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gtgelvudvv.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtpyewksdb.html

[C16] 函数 / 方法重载
来源：http://dali.zhoulong.xyz/Article/details/gtzozesfaa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtlolkijpx.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtpmzmupag.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexhvnumw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gtgjquypqu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcxvqpdfa.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtqbwskvkf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenzaomai.com/Article/details/gthyxqjxcl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtvncentcb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyfebxksw.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtyqxibdfi.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyylkfijc.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtxrzzaxfq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtozeawgwp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gtvhllgvnm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gtbdcwmznn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfllulfm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtgrfhddgy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gtdqosdifb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtraixhtwy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.smart0.xyz/Article/details/gttxazsxgb.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gtdsysczrn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gtdkeopfkr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtmzuhbjog.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtdgpwgiqj.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtnuncmfny.html

Java: list.add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtjqkrwmha.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtpwvsgjar.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtuvjzibfr.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtniuhqpjx.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomvovvou.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtonsqcbwu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtkdxtwszl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gtmbuhwccf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtwgtllixg.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtxiuzwaqe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtlprhdvro.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gtychwoqfh.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtsqmicxng.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtcyygruyr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gtifdklvjb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtbhaswkrl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gttkrqtnkd.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gtzjjjwzuh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtztmaarpz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqqmgpqy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gthkmhoehe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtoebdknay.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtcczshvxq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtuadayocg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtgglcxifx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gttrkdxfex.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtjvqmythn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtsxixtxfe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtaeulhnhq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtqcfqpvfw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gtujkmheqf.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtihonjvoc.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gtwwcqqzca.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gtkqsoxfgl.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtogzzcbsi.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtpyftuaxq.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtvfpgepua.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gttedryvtc.html

Ruby: arr.length; arr.size
来源：http://dali.sweek.top/Article/details/gtokrqmktx.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gteryexzme.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gthdqovjpj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtfhtwhjcc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtzwjymzbm.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtmqseymtb.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gttuikagff.html

Java: list.subList(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtytpqrtec.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gthfizmsay.html

Ruby: arr[1, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtfhwnmbwc.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtfzjxuats.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gtnmvthhyf.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gtqtbkbkuo.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtsscmkixz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.guannengcc.top/Article/details/gtrmtvbiwi.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtuqoixtom.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqfdhhcxz.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtpfnnonwf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtbcelzuah.html

C#:   a.Concat(b).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtzqpxqvdu.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gtggvgdoub.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtqmnbasuj.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtlvhmhfsj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtufcxhooj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhvrqenw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmusauwee.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtandydpaz.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtlbncsezb.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtkksicxow.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gtydtgksts.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtbkuafjwi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtbqawrtpe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gtpctkuscu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangshuangyany.cn/Article/details/gtjfugglmj.html


<!-- 参考信息 -->