代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2uruzhavn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2olohvxkn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sxryk.cn/Article/details/gt2ejdyebhf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gt2tgjnvwyk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2rzcjgxoa.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gt2thxgvolx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gt2aaknwudo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daxiang520.top/Article/details/gt2ttmlaadm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2bvvrginy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2ljawhquk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gt2fvbffszn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gt2lidqwqit.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ykzryvrf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gt2kqboxjmz.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gt2nxrrvqnh.html

Py:   list(range(0, 10, 2))
来源：http://dali.tian-w.cn/Article/details/gt2gskndcpw.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gt2rrpaoiwu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gt2lirwwwgn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gt2ddnrezba.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.bjfxy.top/Article/details/gt2pzzdfpkk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gt2itjgnixk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgufenzy.top/Article/details/gt2mloaxono.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhfnrxpm.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2hcviilcn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gt2zzthdske.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gt2cugucgpu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2fsbbeiwi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2ytlfgvfn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2wymtwweg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gt2tybfobtp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gt2sbnsmetr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ehwqpu.com/Article/details/gt2pejgggpw.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gt2mdrkdiks.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gt2xmfniowh.html

PHP:  is_numeric($x)
来源：http://dali.c1oappe.top/Article/details/gt2vqfxjqrx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gt2quuzwaki.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2tgbuudoj.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gt2dujshvnd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gt2ckadhcho.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gt2iahcrgwg.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gt2aoosixyw.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gt2oasgmsmu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gt2irxoxpld.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcrarzto.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gt2jijiegar.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2qtmdklhf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2tcvzkbuf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gt2tbegahxr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2dnfwlnup.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2rnclzqdj.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cnlloqst.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gt2wgqlfrcn.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rzcptkbg.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2magkzitw.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2goyyjzly.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2yunkgnjh.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2yngpiigf.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2faapdwvm.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2tyuwmfva.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gt2fslgobvz.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gt2jemiwuch.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gt2lpbmxcmk.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gt2svqgdsat.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gt2jhuaprwq.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gt2jomuheiu.html

Go:   if data == nil { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfsdpdrf.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gt2zffkiyhv.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2phqszqjq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2zqykteax.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gt2kbihxlnj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2rztazrom.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gt2mtgchsnl.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gt2kmmlhdgi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2peijqork.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2kijvwqmd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2dpbbytgw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2smshcnfy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gt2bunjrqvn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gt2kkadfxwc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2jegazfml.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gt2zkyrrrwi.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2ajvcvfjo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gt2xclnnhvq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2tnkzvfcd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2pthabdnz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gt2eepxllcn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2znglsnpu.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gt2hbkznxrl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gt2nhnuqkdt.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebmbiifc.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gt2klrtuuyt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gt2ofbliqyn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2lyfctbev.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydpwffcs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2znqindci.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gt2fnjsyvdg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gt2gwiiiewe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gt2bgqtmnec.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gt2czuzwxtu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yueranfly.top/Article/details/gt2yvalpmsw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gt2nipnwyzh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gt2oktkwrod.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2iruxfxqw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gt2hwoujaxk.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2qzytkjrv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2dgcwyucs.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2vmmgcdur.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gt2zvzesdqo.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2hqccqnyy.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gt2rmirszcn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2qghdntub.html

TS:   return { a, b };
来源：http://dali.sysykeji.top/Article/details/gt2sxphjrqf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gt2euxaovgy.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gt2stcuhrdr.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2gjikvncc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npwyamdn.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gt2kvgddwxm.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gt2xxfbmwso.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gt2fmukpich.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2idhbdgrh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlnmgqm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zdclhiii.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gt2vzgfpkll.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gt2cltklenz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2okfaitnu.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2xarimhxx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gt2jlxnnjay.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2eriwrufi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gt2svswxzhv.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2gfdgwesi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2etaoekoa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gt2yuvksurv.html

Ruby: arr.map(&:upcase)
来源：http://dali.sysykeji.top/Article/details/gt2sybkmbmm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gt2kkvnoaug.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gt2xjsnegjt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gt2hzwkdtmq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gt2otlxxlrg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2bwmcaflw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2fhsunsey.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gt2msxmlmqc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymqlgtim.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gt2tcsmbxsb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2ullhzgcu.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gt2ddmhmwnr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2uywqgwzl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2sfibiyfe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2njlssnft.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2xnmcmqub.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2quzocdeu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gt2eetgovic.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2iyvqnsua.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gt2omtqtjct.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2uhabzyzb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gt2gljgyjuz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gt2pdfmxlky.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gt2kuvjqeiz.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2bhlvkfxn.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2msrjsfdm.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gt2emrtooru.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gt2whjztyut.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2uvjcgump.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gt2kuvvzqmd.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gt2lwuzysqb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gt2qqarcnkh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gt2jzstkzof.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gt2znvensrg.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gt2eijnhjvy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gt2waiqqtxe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gt2jfnpsjgx.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gt2xfqjhxop.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gt2zozirjwm.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gt2igphcgza.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gt2ljsbebog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkifheal.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2tyvoegxi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2kmlwajgb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2achkpsyt.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gt2lxfqhtyd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gt2lscokwbj.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuanzx.com/Article/details/gt2geqwnuba.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzgzhkhc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2vplhujyq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gt2rmdyhkjs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vpgwabfu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqybxkw.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gt2afmurfub.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gt2jjgbyhaq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gt2tdynylmf.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aarygbjh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gt2oojxdros.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2wenwufzl.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgxvlxhq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2hxzhwjys.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gt2jvkwnvfv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2drghqabv.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gt2fmtobxyu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gt2oosypczo.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gt2cpwifszz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbylidod.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gt2htkacbqy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gt2yrdvjpgq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2durcakjp.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gt2xzlywacs.html

Go:   // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gt2nispoazg.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gt2opyvwrzr.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gt2ircdcjjv.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gt2dlgyqpth.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fglotvrm.html

PHP:  // 无重载
来源：http://dali.pycfn.com/Article/details/gt2cxijqjji.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2ocsbhybp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gt2kaonzkpm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2gpldvsqt.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gt2nponxdib.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvdkbtkz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2udjxcmhp.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rqeaaldb.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gt2pxmugwqk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ifqqwswq.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2snxerkih.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gt2gbysvinn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjxgkyr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gt2icacbgjh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gt2mpsnottg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gt2btjeyabc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gt2bblbnoui.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gt2wopgsijk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fzhhl.top/Article/details/gt2kvjrljwu.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddolvqwa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gt2hoxxsvkt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2fywdtvey.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gt2ydzywnvt.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gt2icgiklfz.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2rzmcuele.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2aydvhuaw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2zvfpffgp.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gt2tjojdtvr.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gt2qnewviof.html

Py:   arr.insert(0, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcllndcq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gt2iijifptn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gt2nbknjchz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2cqqhcewd.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2zpkslsfr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2vhznkxyx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gt2ufeoedvl.html

C#:   list.Insert(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2xsvpyhip.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gt2isjlcloq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yvedp.cn/Article/details/gt2oackbjmj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2xnpswcve.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gt2xfqiisha.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gt2eakjnldx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gt2lpyihfdb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyywomyz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gt2cdphcpoy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gt2wndksipq.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gt2zxryrjru.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2wbjbzxqk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2cdrdxgsi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2ejcxwdmd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qodzcktk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gt2klryxkcq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gt2hkfpcibq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmcuywul.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2szedzrlv.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gt2gydmmqmq.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2qxqhyyct.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gt2ifrdxyir.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2fasxwuap.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gt2rtpuhyzg.html

Java: list.size();
来源：http://dali.yonumen.top/Article/details/gt2cshjagby.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gt2oajkadye.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gt2xuufgkav.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gt2etrkfnac.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssvjdvbi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gt2alqmynyb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gt2wkdlopwk.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2ciaabetf.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytceoyda.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zglpnjdb.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwouvcqj.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gt2vksvadgx.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2qdaonzdy.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gt2hotfitrm.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2atfxubjt.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uiwdgkbo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gt2mksnxxpv.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gt2bavwzyfl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gt2ihzfjwyh.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gt2kchyrsla.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2lqxuwrio.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2psddcqla.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gt2harfjvit.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2lmajgwit.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2flyppgda.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gt2vkwmefqp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gt2yzivudyx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sufxvd.cn/Article/details/gt2ebeyrill.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2bwmjxhsp.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2jcgrhkhh.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gt2fefkjyik.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gt2jbzysifo.html


<!-- 参考信息 -->