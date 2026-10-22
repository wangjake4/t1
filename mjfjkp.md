代发 wailian999

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gt2qimcgfza.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gt2rzhwhkrs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2xkfyajsb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2mfaasfnw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2sggmjtaz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2avhhojmf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fengsongda.top/Article/details/gt2uisxqjnd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gt2ieqxxykk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwxwltnj.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gt2qvbqynpl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cashguo.top/Article/details/gt2bauxudgs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gt2arbtwoud.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2swifopok.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gt2antnegtx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gt2cgxirajv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gt2rtykoeyc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cheryme.top/Article/details/gt2shrbadey.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2okqkoffe.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbavcwoi.html

Py:   list(range(0, 10, 2))
来源：http://dali.gaohongyu789.top/Article/details/gt2lvamemyw.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2qbmhbxmy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gt2qksuahhk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2knkofynl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2xkooqykz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gt2geymgphh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gt2xqbnrtfp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gt2bkalkkfw.html

[B12] 跳出多层循环
来源：http://dali.smart0.xyz/Article/details/gt2cgausken.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gt2mzejufkk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gt2jdcauzpa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lujtgmhz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gt2zholdkst.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2yayipypd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htqjqsaw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gt2nfnvwclx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gt2oflxsadx.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2siwqjtvg.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gt2mlfkakww.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gt2fsxetbhl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2rtyrrnvz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gt2pgbooawj.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gt2pfyhwrng.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gt2iitmshjb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gt2hoeivnkn.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gt2rlkmwyam.html

[B14] 判断值是否在集合内
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aipmyxqd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2omwzrdbf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2khfnfdbu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jijayrnr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2nlntoxpt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2udkboylr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2aswhftwx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2agwrhosv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2uawibwxh.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gt2hzqovika.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gt2crplkctz.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gt2dbwbywfy.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2fbjzfszw.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njyvctzm.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2ditykhdp.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2yvsjdige.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2plgdyvpm.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2pkplpwii.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gt2jnaaimes.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gt2ahnqggoq.html

PHP:  if (!$data) { return; }
来源：http://dali.aizwys.cn/Article/details/gt2arlupqzn.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2ssfxmipz.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zefugfae.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2vjjcdkpe.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gt2nrxwfany.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gt2xorrjkoa.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gt2barjxuks.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2lkxifdyu.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gt2shcphtxs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qyzuuyxm.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlvqdvyo.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2episautr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2przxvxxo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2eftcfvyq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2pyfvgoca.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvugbecq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2dscqqryj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mlxcnpcp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2vdjbcxkz.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gt2fexzepzg.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gt2bcuqctgh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gt2uhmofaaj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2wnpfovje.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2xboaitbp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gt2teiawgrv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubekgamt.html

Ruby: def greet(name = "World") = name
来源：http://dali.guannengcc.top/Article/details/gt2xxekehou.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gt2zgotmzzy.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gt2aypkpkez.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gt2wplravvo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxinkj.top/Article/details/gt2rnrkuumh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gt2dqatllvh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gt2znhtzgof.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gt2uaupfemf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yanxiufei.cn/Article/details/gt2empilsru.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gt2mfyogpyx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gt2huiygoap.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangdashe.top/Article/details/gt2idnrnoch.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gt2eirdeeen.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gt2nhoqfqjq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ebjviskl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gt2vvnlzhrk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gt2uylziveo.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gt2wlrpqsar.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2sdvtpvoh.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2tnrxfazq.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gt2axbltmbd.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2qlfyfhwh.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gt2jurjztne.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2belfmkdl.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2altiujfm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gt2qgdrrwzd.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2nzlzpkhn.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gt2prwaeqhz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gt2qsnlblny.html

[C06] 匿名函数 / lambda
来源：http://dali.sxryk.cn/Article/details/gt2cmmpthjc.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gt2arlxehdn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gt2wdsgoxfg.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2udrinrqc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2zyzhxwbk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gt2znnvojor.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gt2mdsqcgjr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gt2gxvwtqki.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2pfgotsas.html

[C07] 把函数作为参数传入
来源：http://dali.andypj.xyz/Article/details/gt2zpidwgxr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gt2edgxtrxh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gt2xrjlofbn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gt2nknlmhik.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gt2nakuyuft.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gt2qbeevrcg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gt2lwwikcgf.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gt2qhdemlld.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gt2mgiaoqxt.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gt2bbamkeko.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gt2bddpjthd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gt2mfdqepku.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvuycxpa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztqhisiv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gt2jqijyueq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenlongwang.top/Article/details/gt2puzbvwnk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gt2jvufpxms.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2twxbnnfk.html

[C09] 递归
来源：http://dali.iojbl.cn/Article/details/gt2pwvfeiwl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xaxyoanc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gt2yxngoqic.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gt2lyhajsga.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gt2kpmcvnnt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gt2vdhafnvm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gt2zivzdobs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gt2chtszlyb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gijaflkg.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2ueajxpgi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xziqi.cn/Article/details/gt2akijkrkl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gt2enfbbjip.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2gkkjaxie.html

TS:   同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2dakvzpju.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gt2ahnhkpzn.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2pfpmxlzy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gt2jptyiqrq.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2chzhckdl.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gt2irtuyfxw.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gt2xxwzlcsl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gt2jloyysvr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2dyrugqqf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2ahsuhprn.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gt2zvtmvqst.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gt2kgymzvue.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.andypj.xyz/Article/details/gt2xcebgqru.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gt2xnadpenp.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gt2flbgflgs.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gt2rmhnysuq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gt2utjlwxhd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2ixowimud.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2gxrlzmsi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gt2vqzisbdq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gt2uluznqsz.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gt2hpejpnrq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2kcgajxfb.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gt2nuyghqqg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gt2uxmlcmib.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gt2tlsllnnk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gt2njwpajdz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2zzfxaivl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plhkmpiq.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gt2quwbveen.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gt2sxbgqmuw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gt2lzwbrzqk.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2nriuwynj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gt2ixxwmfel.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2hhtyircy.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2thuhrqcl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gt2pslwbcfc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gt2pnptrxbf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gt2nmcpgvdk.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2ptkekpbi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.bjfxy.top/Article/details/gt2jpsgnkts.html

[C15] 解构 / 展开参数
来源：http://dali.jiagoushi.top/Article/details/gt2qkzaljcw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gt2heoohwme.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2hqxnbobl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gt2apfnubvr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2djatjjon.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2fzrifnoy.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2pyluxzsn.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gt2hizjfjob.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dewffxpq.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gt2yemwbven.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbozixr.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gt2wgpwhlrd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gt2imqjeibv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zycfv.cn/Article/details/gt2fwonmgcy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gt2wgohwspd.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2rksapyju.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yongpay.top/Article/details/gt2oorwacpi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj202588.top/Article/details/gt2lulvcgxy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2aujfcvnj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrwjyezw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tdycejnf.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2dpfuhjua.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gt2uxfyvlfn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2qwtypqjf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cheryme.top/Article/details/gt2suhxoejs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gt2uxfvvlsb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vubesyvh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.quarkkingdee.top/Article/details/gt2rbjookpo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gt2ucgcfaur.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gt2veiiklhh.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gt2nihiyukz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gt2anrxbdhz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gt2wadxmynq.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gt2yrjdkdcs.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gt2jrkdffkc.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gt2jiuxucxs.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2ydkvznpy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gt2wfoeegda.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gt2ztpmiqui.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gt2fcaznrnq.html

Py:   arr.insert(0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2vcdywbsf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gt2gjqsgnmo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.smart0.xyz/Article/details/gt2oekqeyfq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2emlnrezg.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2vwjhshkn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gt2otfmstew.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gt2bnjoclgf.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lempxlxl.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2qitzffsz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gt2dejaavbu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2nvyammia.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2deusvfoe.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gt2lfuowlep.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gt2zosuaial.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gt2atxujuyz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gt2oiwtiqgo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gt2mycmvwrj.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzxwgtna.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2dkapiftj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfduwwjl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2wsdjxktf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2aksvsbjf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shzxlz.cn/Article/details/gt2cxakvneo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2kaloutxk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2fuflezih.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2iixfgoqu.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gt2vmlyyuqb.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xppbkhtv.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2klhmufsp.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gt2mgundgun.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2onnoumjf.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajxmpdwz.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2dzanjbwm.html

Ruby: arr.length; arr.size
来源：http://dali.yuxming.cn/Article/details/gt2zmdmwost.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gt2cwmftcpf.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxuorjks.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwhdxur.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gt2pqubyzek.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gt2bbhigizp.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2pjzkatwo.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2wpmzxgps.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gt2negcomkk.html

Ruby: arr[1, 3]
来源：http://dali.hywenlv.cn/Article/details/gt2bfxwbfen.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2elqnsuhz.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gt2evecaxfs.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gt2lhszwuvx.html

PHP:  array_merge($a, $b);
来源：http://dali.yvedp.cn/Article/details/gt2hryaojyy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gt2prdwzhyw.html

TS:   [...a, ...b];
来源：http://dali.xinyue.icu/Article/details/gt2zplmufwg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftpcjnjx.html

Go:   append(a, b...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdaxmoic.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjomsaqc.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2rgdmdysd.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gt2tlhiznap.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gt2gdmueyrq.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvvizuzk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gt2nkyidkcu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gt2ceeqakft.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gt2jaaqcodb.html


<!-- 参考信息 -->