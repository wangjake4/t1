代发 wailian999

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gt2euhvwukg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gt2budxsnkt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2nbzlzmpv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2adihntxq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gqpsyobu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2bndlilkx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kisnadjl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gt2hbyotucy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2rhgeiups.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gt2hvrfqqwx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqohhkto.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gt2axciivvb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2lbounrwm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfifbjxs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gt2zfiigamn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guowangkeji.top/Article/details/gt2dkbbzgxq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gt2bliygroh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gt2xfpqdyth.html

[B11] 生成数字序列 / 区间
来源：http://dali.havefunace.top/Article/details/gt2rxuwragb.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gt2vvujqzck.html

PHP:  range(0, 10, 2);
来源：http://dali.ybcxt.top/Article/details/gt2eqzlwsxh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqlpfpar.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2vvbqmbjt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gt2xxjlqyyf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.haohaochexian.top/Article/details/gt2ljuplsje.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gt2dxqfztld.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gt2yekclxpx.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gt2mzwhdevx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gt2nsdlbncu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gt2qysybhfe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2qcpmdkzw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2dcrbysfg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2qysnupev.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gt2bzzbnwdc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gt2rwfypxlt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nwbrower.top/Article/details/gt2trlumwoi.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gt2ascveitu.html

Py:   isinstance(x, (int, float))
来源：http://dali.yueranfly.top/Article/details/gt2vehjxgbl.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gt2bppabkbh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ypkftoms.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gt2wfqrcqqv.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gt2ezqluhsh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gt2aecdvlfr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhengqikj.top/Article/details/gt2bquchftv.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gt2qijeqjsb.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gt2rdpueutj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gt2ycpawlii.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vuyqtlvi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2juvcrzob.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2yhdpnhay.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohnebttn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gt2owrjakcn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2vrhnncck.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajobbccv.html

[B15] 布尔运算与取反
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qltekhzv.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gt2tmivwvsw.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gt2njcyyxcq.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2bowynmbh.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2rdspflda.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2ytwqnlhi.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2pwmkavrx.html

Ruby: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2wbdgolce.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2nckumrvj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gt2advlmmdz.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gt2javbbavn.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rttuacwh.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gt2pblnnwxj.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gt2bpbhywfz.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gt2wlscfykg.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gt2evgnrkpf.html

Ruby: return if data.nil?
来源：http://dali.yj20258.top/Article/details/gt2mxvijrrf.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2akozzivu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2yivouvni.html

C. 函数与作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2xyaibncf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2erznsaov.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogwlyidi.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2kneclirg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2vlqbzkcs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvelozcf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2sbnektfx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2ckeopttg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gt2izlkqgtv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258.top/Article/details/gt2mtoqhjed.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2emwgauyl.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gt2nsszackf.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gt2txpvbfyy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gt2etwehifj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2yzdiiwvz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gt2ezsgtxju.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbnjuavg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gt2gysoseqk.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gt2qhjduwww.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gt2murmgbpa.html

[C03] 可变参数
来源：http://dali.c1oappe.top/Article/details/gt2njnnsnbz.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gt2wdyyvvys.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gt2inwfpdtq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2thptavpx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbtflgpc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqwgtogi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gt2rzcfmsua.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gt2hobmrbne.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gt2hagttsxy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2nkwrekhs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yiggbkvq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gt2twfqfofo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2dflxgqja.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gt2kvhuhitd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gt2sfazjjob.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gt2yjyavqcd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2hprymqwc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2qkbemfza.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gt2mavdyhig.html

Py:   return a, b
来源：http://dali.fzhhl.top/Article/details/gt2ayswdeoh.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljkwoyxm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gt2jldafyfe.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gt2dnhidgyr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2trxevcmc.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gt2yfzmpxga.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gt2yzrvflqh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gt2harqhmwx.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gt2bixlqjlj.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gt2vtcnuigf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gt2wwvdjmyf.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2iseodyrl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2jvbughgz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2cxmkralq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2yzrzkypl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gt2wrvpotja.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruhakzzy.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gt2nwaafgxn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gt2wtisemet.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2ujjrghse.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gt2szpnihss.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gt2zjphcgrx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2rcmyzcct.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gt2lqaolwth.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gt2ucubuggs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gt2rwuduzvg.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gt2bjobrqhy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gt2ebkvsaoi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gt2peczrslb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2tqedarob.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2rsjwryog.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gt2vkzergad.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gt2etwnohcn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gt2omiegzft.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2ftkrhozl.html

[C09] 递归
来源：http://dali.yanxiufei.cn/Article/details/gt2snlfvjxp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2hshhnltj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2lsmlaptk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gt2nwjlglls.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2bplnnnmi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpflzprv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gt2bziesatn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2benfbuzy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gt2ejtaxxfy.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gt2ixcxctqh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gt2zcgfeffg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gaohongyu789.top/Article/details/gt2aiailtlt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2uwngqoco.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gt2erncocty.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gt2drjheqra.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2qazgcsyy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gt2afxdkknb.html

C#:   块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2kztlmobo.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gt2emeevlwm.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gt2bmwsggjq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gt2ixrwdiry.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gt2khjlgela.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gt2nrjltgjm.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gt2okhjuopg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jlsjyb.cn/Article/details/gt2axngvked.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gt2fexkzevg.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gt2rsygoyuo.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gt2wnuwwucb.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gt2vwdauzav.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gt2ffsswjfq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gt2lryvfcow.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gt2jaqbugay.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gt2orchmufs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gt2vgdyosxx.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gt2akkzatwl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcgtyfcw.html

[C13] 类型声明 / 类型注解
来源：http://dali.cashguo.top/Article/details/gt2hlxwejws.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gt2azvbqcqy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2mlnqdvfb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2earcqypr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2esgtrdga.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2zbnupcre.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gt2ychwbsom.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2wjhshfwx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gt2azgzsyqx.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2lrbigyqw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gt2mzjemsbc.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2ukukkbyo.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2clakwyxa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzunkmxs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gt2tarmohdz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gt2ffowzlqr.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2opbaalfi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gt2fvgnsqug.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gt2elscxmij.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2romovcfu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.316326.xyz/Article/details/gt2iiyidmei.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2erafwmny.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oganaksw.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gt2euljkzsz.html

Go:   // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyxmmmon.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gt2egrvrysz.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmjkfkiw.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gt2lhdsktjd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qblgwgof.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gt2whpknvcb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gt2ssxfqtir.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvmspbzt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2aadzsvhl.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gt2satcacqs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gt2aqntirod.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gt2tgjtctlb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dmfoljpt.html

D. 数组 / 列表 / 集合
来源：http://dali.aibaodan.cn/Article/details/gt2nnnzwvlg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jmprnrhn.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gt2curafhir.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gt2jdooypkf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gt2bxaomnpr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2bqazfshi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuxming.cn/Article/details/gt2ioiwqkrg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2fgoxvgwk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigfzy.top/Article/details/gt2odaztiey.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sxryk.cn/Article/details/gt2uftdkjxq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gt2gezppylk.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gt2vmnizdaw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ehwqpu.com/Article/details/gt2fdjkkojp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gt2dilytqqj.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2aoxbqpah.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2nrxobbiq.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gt2mlnlgute.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2lrsdqrac.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgkzrxbi.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gt2psfyzemd.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2iofmpmkw.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gt2wzuwdgmi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gt2nmdgqvna.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnjvegqh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gt2yxhzztmd.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gt2zzzmvrxx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gt2tdedhbxb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gt2zhbbkcwc.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2yghidlhu.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2htlbsxda.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuanzx.com/Article/details/gt2pfyoguaf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2hedqabge.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gt2qgnuewdc.html

TS:   arr.splice(0, 1);
来源：http://dali.xinyue.icu/Article/details/gt2enlfakks.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ieftqjsl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gt2coyqnyxo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gt2fpulnder.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gt2ymwaxpxr.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gt2rtmjedst.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gt2iixwwgyv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2nzioocsv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jleoiejr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenlongwang.top/Article/details/gt2kvqjqmhv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gt2cmmkxdvt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2gzougckn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2cvsrddxg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2ozxjbmhy.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2myqmcxtd.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2iiavtryd.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhcreylw.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gt2khauidlc.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gt2chquqdxo.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gt2nngozjxw.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2kicnytag.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsdehgpl.html

C#:   list.Count;
来源：http://dali.jinqigfzy.top/Article/details/gt2ymkslpzq.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gt2oqnovmpi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gt2tqiuwfdd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gt2cafiivtm.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyrjwist.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2rbekjwvv.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pprsxkgx.html

Go:   arr[1:4]
来源：http://dali.tianlin.xyz/Article/details/gt2qvdvyatu.html

Ruby: arr[1, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsymynvd.html

C#:   list.GetRange(1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2xkxtkmlc.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gt2roowxeir.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkyiodwy.html

PHP:  array_merge($a, $b);
来源：http://dali.dashuyun.cn/Article/details/gt2oqldllau.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2dmvytwev.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gt2uyybyqgv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gt2zurezhwq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iybpvcap.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shrtqtis.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2ogmedmdg.html

[D09] 排序（升序）
来源：http://dali.svipenyu.cn/Article/details/gt2iayimocx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2gdmmvtlw.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2nojnwyyj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gzhubu.top/Article/details/gt2kdkrdfac.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gt2cxcwbmnm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gt2utbkmevl.html


<!-- 参考信息 -->