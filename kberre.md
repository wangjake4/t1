代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtwytrndvi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtfgaobjkh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gtqoocxlki.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gthqdlvkrs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfonghazb.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gttphrzdoj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gthzcrfeqq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpkrivhk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtgaebtxvk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtvenyoytb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtgfjwmfkm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gtgrlsxzsj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gtmppykrcl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtjpbudgdd.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhongyouzk.top/Article/details/gtvxqqbwwg.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuetiantiany.cn/Article/details/gtsvcrrgmn.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gtxmllqpyj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtwtltkujr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtachcokbd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtuljzmqem.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtblezctjq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gtapkuupcl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ivvv.top/Article/details/gtwbbhxyvf.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtmajwubad.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtlqxtjvyf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gttdtaqfcr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtxruwuysn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtbadzeczx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtepjlktjx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gtbfksmins.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gtpvlwtogs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.iojbl.cn/Article/details/gttqnrtpmf.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gtenelgowg.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtwxfdahgl.html

PHP:  is_numeric($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdztukctv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtgozrgabl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gttkcvpubz.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gtwvosyvlc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gtsevmxgdb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gtjohhjuwq.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtblzcmjbb.html

[B14] 判断值是否在集合内
来源：http://dali.zhoulong.xyz/Article/details/gtayzcyrwz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtqzdflwpw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtktgblefe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtueorhqmi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtbzgotbty.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jyoumei.cn/Article/details/gttebioina.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sweek.top/Article/details/gtjmbvmfpf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtnvzfngek.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtpqplqbjs.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtktgyqfmb.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gtnjgkjrsu.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtzwkfhqfo.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gttawfelom.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtbryubtvj.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtrmunfgzf.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtbuzdmcgk.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtyevfyesk.html

C#:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtqfpnyqam.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtrrpzrlvf.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gtrrirhzek.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gtwkanjdch.html

JS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtlzvimaez.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gttjtnppqs.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gttnbzidxy.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gtobkugmwt.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gtecdnwsib.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtyghgzrqu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgenjdbhf.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtwjplgwuh.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtracetiih.html

[C01] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtuzqnpixz.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gtwycgauwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtbuiporua.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gteigzttjb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtmgydgmcj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtxhmixdim.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtbhdbopxo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtboyhffdm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtrokgmdqz.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtnjvbgslq.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gtddjjhsqn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhsdgqxz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtwoxywwlf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtkrcqdovr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtjwsmurzf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gtvdnszbiw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gteztbmxue.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtgvktqjpp.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtrrneomzw.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtezseidpx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gtodwmquob.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtkoekdwgj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtjnttjzhf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtycrcbjtg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtopzttfrf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtzuadfanh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtoddqclyr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtjovdpqro.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtmmlmajug.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtggeykgep.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtyqgyjoqk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gtuevmktpo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gttsfflsud.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gtgvncorie.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtlpxclcfd.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtizwbugan.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtmojmjgwz.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gttqawotua.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gtraqtdchc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtstuyxwat.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtwvdfoqwd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzscahne.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtsirjsqxu.html

Ruby: return a, b
来源：http://dali.xylfe.cn/Article/details/gtokpobjgx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtxlgdgvxe.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gtvhljkaxa.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtfogplbxe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtzopgkjlk.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gteugfwimg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gtirzrxlyb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gtclfimncu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gtovoliabs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gtqxlykugu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtrfpltlzb.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtyntebqof.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gtlneecacf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtldjgowrr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtzrtviyou.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhnhvuyp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtquadvlqb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gtoulevafh.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtuvpcwlgs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gtyhkifacs.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtcdxwuaad.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtfgmxhqmq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtcraoetpf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtautjhets.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtyrgvmuqe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gtddytzogz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtexgydkil.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtrfhqkjgu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtpnfqgmyh.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtorccvqoy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtfktmeind.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gteephmvql.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtxerruqci.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtzbybqrpc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gtzmkbcknk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gtbztgfxbl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvpmphfw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtvxfgozql.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtucvwgdsf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sufxvd.cn/Article/details/gtxrrqoclx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtfgampokt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtxypsiteo.html

TS:   同 JS
来源：http://dali.cheryme.top/Article/details/gtnskusqwt.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjinxsfmu.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtalrbqdrm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtsowubdrd.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gtbglvghsa.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gtnshhuulj.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gtlllxqqqz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtnlingvsv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtkuqotepp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gtcotahoam.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gtgdhgifiv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtcurovbqv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfarzfjn.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtczyaofjq.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtpttrufzg.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtmvqasvtp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtxgkctkbz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtgdwwhlzx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtqezhpjdk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gtmddtmsrb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtbgelioaz.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigufen.top/Article/details/gtykxkbawh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gtabgvdrgq.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtmrsdlgqv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtmeknjpxd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckhcvxng.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtbsoicreu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtgatquosp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtecilhpps.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtnabzkhdn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtzmpjlzwg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtoqgaulgn.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gtdkjusoct.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtxxthnpoe.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gtgvqhcsxh.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtkhpnilpg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gtgunnbbsx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gtsdoauwty.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gtgbzeuwvb.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtqywoghew.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtlscfbnue.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gttjqtrcee.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gtxkexcqlh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtssqsdcyz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtaixkarmo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtyvuugrwb.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtjmobeudy.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gtmozykapd.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtigzttbis.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gtqcngmqmv.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtjbtmniqh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtzfgonnds.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtmcflyoax.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gtavuudmzn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtrtpdkvbe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtmvmtglzx.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gtyulavgye.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigufen.top/Article/details/gtvvnewnxq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gttrmeigkf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfeqlidhr.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtijstzzsg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthijhlaus.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtlrpfpptm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtvdbfhdja.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtqecbbvzr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.bjfxy.top/Article/details/gtlouxnyer.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinqigfzy.top/Article/details/gtuwusjjxg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtygmxxbsn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtafjktdzd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gttgduhjsa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtaxlctayv.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gtmtghwiqn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gtdeqrujqx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gtksqglrft.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtamtbptzp.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtoqwqslle.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gtrvrvsmol.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gtwgbeoavt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtdegukizm.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtpctnmxtv.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gtejmgwxkd.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gtfbfyhrsg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gtkuennoxq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtbgepjzqy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtqumivcsr.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtiyyzvkot.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gtizyaqors.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gtxdmhbfxj.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtrxvafdey.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gtahdwtlll.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsquhvlh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gtufreuzfk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangtech.top/Article/details/gtxgarefqa.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gtsffqycnt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yonumen.top/Article/details/gtwwluolam.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gtsbuvmazx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ybcxt.top/Article/details/gtguzexetd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gtrqgvbpgb.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtxrqntaav.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtidxipilf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtkotzewmi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtyrsrozua.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gotoacloud.top/Article/details/gtisabaedy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtjtlceacl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtfxzebepp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtsyzwpzhd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtrqtzbphy.html

[D06] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtzcvwdnzx.html

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtvhedgzho.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gtfstyepge.html

JS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtoqzcewhk.html

TS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafpmnqoi.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gtqhfxaimd.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtstcqkdru.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtgudcffia.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gthkrosrja.html

[D07] 切片 / 取子数组
来源：http://dali.gotoacloud.top/Article/details/gtgksgycxm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sufxvd.cn/Article/details/gtruqltedt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gtajrbzysa.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtxbrrsjrh.html

TS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtzwyltxhy.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtskutnphj.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gtcwuihnrb.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtirmdaruz.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtalomdfsz.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtrjrquhle.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gtvtsoojcb.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gtauvwsrir.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gtkujltcet.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajqhlrcl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxinkj.top/Article/details/gtqeogijdg.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihonlhjr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gthzwhdjkp.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtcyaymhrf.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gtuhwkttqg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtwdpvpmck.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtqoewoexp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gtjyfjodze.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenlongwang.top/Article/details/gtjjdksiph.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ivvv.top/Article/details/gtrovhnrje.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzhfpckoi.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtvluuqskm.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtezpnbysy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gtzlqtvape.html


<!-- 参考信息 -->