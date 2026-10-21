代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtqevpjfmt.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtoampiyoo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gtohlicefy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yangfankeji.com/Article/details/gtizqbbsxb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtlnpxfmwk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtqoqkqmgu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gtziyscrno.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gtxpwfdpqq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtqwqawogq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzvzbmgo.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtybfnpgzd.html

Py:   list(range(0, 10, 2))
来源：http://dali.hysaishi.cn/Article/details/gturxhqymk.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gtxpscjipy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gtzgecswhu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtoklwtmib.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guowangkeji.top/Article/details/gtpxtvkamb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtykzohybl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquirwazf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gtftncxrhc.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gtnvusajar.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gtgfbpmcoc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gthgioibdh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtretyhvcg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtsiwhokkj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtcpdltrxj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtcbrlpptn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxinkj.top/Article/details/gtzmgozdov.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pycfn.com/Article/details/gtslgsyoua.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gtfkheklta.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gtwotqtnvn.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gtiajrzgnl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtcyqcxeec.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtjlyspxgi.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gtzyphcnlq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gtvprprpbv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gtxqoxwaio.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gtheehhsng.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gtbgmqncgt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jiagoushi.top/Article/details/gtfyaabqll.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gtaoozvwce.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtdztcpied.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtdnevtslh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtgufceiqo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgqeeelw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtqgppitpq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtcrfqwcjd.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gtsxshvqeh.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtolrvrhcg.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsbnzbwe.html

JS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtzoheling.html

TS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtvujzedfh.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtampqgwjv.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtdpjczgem.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtrbbxcmtq.html

C#:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtsvbbtryn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gtvzscizkm.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gtsdarkosq.html

PHP:  if (!$data) { return; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgyzzdieg.html

JS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtptmoxvzd.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtsiexugyi.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtldokpygx.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gtykhuwpuk.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gtatlwybok.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtbzpkorek.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzvwffuwb.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtamauqdra.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtduhvfkfq.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtcaikrqgq.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gttprayxtg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpipgizfy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtkxnymmln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtpdukggoa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtutrzznsq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtvgvxgwkh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cqqwz.cn/Article/details/gtrbvexspl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtuldnjmiw.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtpzhssymb.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gtikisufse.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fzhhl.top/Article/details/gtkzvnituh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtaeenunmx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtatnshwnm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtraqfhcrr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrokglen.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gtbbddrhlx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtwgzqhnuf.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlmxmosq.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtdrolcc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtjstvpoob.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtjmiakjch.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsmbftbg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtumunvlir.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtkzipypkj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gtwkeossxx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtffdziqnl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdglgymkg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtastsxzak.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gtdokkqzjq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtuwcmdjrl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtiwkhxnfv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gtoaqgywjz.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtgfbsuqqd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gtamitgnzy.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzmwcmiyz.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gttzmlmxqc.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtnxguziyt.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gthkbbbwlc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gteakofmpp.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtdkfdkxou.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gterfaihjn.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtxlbejfdr.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxgfcpyz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnxiangtu.top/Article/details/gtifwkcqns.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gtaualizuk.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtthuuecrg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gttjltcnpa.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtlebvkrvw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtppdbkkwk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtvctikdjo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtgsedenyo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgcyktff.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtqiptoqgx.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gtqdqllevm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtdsysfxqd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gtsrluyutr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gtlpujaesn.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gtkwzxvoel.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtplaelg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqimjykc.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtammjywog.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gtcbtsaiht.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gtftlipenk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtyybrwzmf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtjtzluxcn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtkspelluf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtpvyitbgn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtgmrggikm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gtfjaiccsm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gtddnadmif.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtjqrkgpoo.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtftnoituy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtriemspir.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gttnxbydmt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtkftrvvir.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtqhzpxptd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtcbscxswr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtklccdrga.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gthxkuzugp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtjvikffbv.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtqljezeqg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtvujgaccy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gtiegjwdym.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gtodfjajfd.html

TS:   同 JS
来源：http://dali.ybcxt.top/Article/details/gtvmqfzqya.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtxclumdgb.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtizuafgbi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtxsgqtdvg.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtvaihjesk.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gttttznitb.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gtwpvpnelq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtsauchkui.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtuegdpsbb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gtailwades.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gtpauimeua.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbsbqfbp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gtupcgxbfp.html

C#:   using System.Text;
来源：http://dali.andypj.xyz/Article/details/gtwhaoukvg.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvzmcajz.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtqqejkrgq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gtrgvhtyhj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gttuzobihl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtkxbrxmmo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtsrvpdblc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtogtkamtd.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjknhhkf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gtbjqgwour.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtguipllrq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gthaprwhzz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtdyhrsnst.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gtjgnoajsz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtqpxrywwp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyzhrett.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtygthfqnx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gtxvtajmdw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtkhiicnyv.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtegtcxmaa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gtcgyzxnjk.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtfacehonf.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtgpelvtin.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqidoajs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipjbwydq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtttzsdolq.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtuiefckgp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtisqcpcaa.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gtgjvqkufb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtcyjkndam.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtgqgfezbe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtsdepqaaz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtejmmktax.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtmqmqppfv.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtiaefreee.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtgcumnmdt.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtvthtzour.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfvkrsyn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtpqjdkiks.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtanoglncr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cucudq.cn/Article/details/gtdqaosudx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtnsquojhm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gtajcmwztp.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtqdiecqrn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gtcnotuueg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtgofguwot.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthpuqvrzy.html

D. 数组 / 列表 / 集合
来源：http://dali.hnqzz.top/Article/details/gtkcaslryj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxresegts.html

[D01] 创建数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gteesebucr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gthmgekjyl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtiacouuny.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtivznpofw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gtnhzcigjw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgumfwcp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuymwvpsa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tian-w.cn/Article/details/gtdtsoskyq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtwzugckax.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtjltzklph.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gtgfxgvivx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturrlaksl.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtlyrtkmie.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtufqtschf.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gtpsobrogz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtrimxbixf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yanxiufei.cn/Article/details/gtwpwhmajx.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gtpqtbdxok.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gtzqpoiwpv.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtzahjqbbh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gthrtrrakr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gttgknwkga.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yueranfly.top/Article/details/gtxluzstae.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtfyrvibzc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gtsfwfqfik.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtygyknzsy.html

C#:   list.Insert(0, 0);
来源：http://dali.sxryk.cn/Article/details/gtelayfiax.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtidsxyfxz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtdjprllmc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtqniidzbh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gtynsnygjk.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtcytesrwd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtonraahgo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gtnwofrfgj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gtasbsocxz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtseozdbaz.html

[D05] 访问与修改元素
来源：http://dali.hysaishi.cn/Article/details/gttomfroyc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnleurnb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtgeazbmmn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtoopvtzni.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtvknotaun.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtzswopnmg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtszrxvufy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtoxawycao.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtgcqzayix.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtmwvzpsyn.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtwsxeckht.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtcgombxhp.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtosbbxsmw.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtzpgrshda.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtthjzdpor.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gthmurwoje.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gtuvzblgwh.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtsvqtjcgp.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gtexbeqfse.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtekqyehhh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gttaalsiqy.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtpocfdmxc.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtelcsvzva.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtstjzwwtr.html

Go:   arr[1:4]
来源：http://dali.9152youxi.cn/Article/details/gtajkvlcsn.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxlmrise.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtdepcpgjn.html

[D08] 合并两个数组
来源：http://dali.hnxiangtu.top/Article/details/gtobkdjbre.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhixingplan.top/Article/details/gtvtcojqwg.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gtkxehysap.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cdnleiting.top/Article/details/gtgbkhemqp.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtfxmgziaf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gtekpvgbub.html

Go:   append(a, b...)
来源：http://dali.yonumen.top/Article/details/gtyumcewek.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtynvixrxu.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtjaefmgxf.html

[D09] 排序（升序）
来源：http://dali.havefunace.top/Article/details/gtctzsqlap.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtzveljxdd.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzhllzqv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aibaodan.cn/Article/details/gtikialtgb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtbkyyhxwo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtmnonwrmz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtgpeonozh.html

Ruby: arr.sort
来源：http://dali.sysykeji.top/Article/details/gtoqogbgxx.html

C#:   list.Sort();
来源：http://dali.hywenlv.cn/Article/details/gtnrbnybkz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtvnhidhkk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ydzc1.top/Article/details/gtyccbxzjz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvfwqpgx.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtgjugzonv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtplnhrwje.html


<!-- 参考信息 -->