代发 wailian999

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gt2xtzveczi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gt2zwdmyews.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2mszwkyra.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2cyvzktxt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2adaohoab.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2qvgpjqks.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gt2evhlsfgv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyfcssrv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2cnoxcacc.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gt2eybgexwl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gt2hybomtxf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gt2oscxsmnj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gt2ubqommar.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzwuqied.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shzxlz.cn/Article/details/gt2yosnjmih.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.mhx1999.top/Article/details/gt2jieuaedl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2hoocpzvu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gt2xklccdrl.html

[B11] 生成数字序列 / 区间
来源：http://dali.daria6918.cn/Article/details/gt2bhrzgotg.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258888.top/Article/details/gt2rbbarihw.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2uqwdgdtv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gt2oircxofq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gt2qnkjfzzl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gt2ghbkrlsk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqfaecoj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.birdmap.top/Article/details/gt2uudogvyl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gt2zbkbiygp.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gt2klcjaotc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gt2jwmkthgq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gt2hajwyzsa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2lckcxmqw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2ohaktasb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvpefiwt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gt2cgwhkahx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gt2loxoxasr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gt2shssrgml.html

[B13] 判断是否为数字
来源：http://dali.yuanzhike.top/Article/details/gt2ehetktya.html

Py:   isinstance(x, (int, float))
来源：http://dali.yanxiufei.cn/Article/details/gt2kgwuvwhx.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2adnuqgce.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gt2mmavxygo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqqimdmp.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gt2lyulxnyl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gt2vxktgsio.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhmqnaon.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjcxbmda.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gt2jwtxfeub.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gt2oigpkrve.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gt2jmlsddtx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gt2bbfsmasj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uaaquokc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2qdpwaiio.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gt2vvixblgg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgubidgw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwtjynro.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gt2czyuegwp.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gt2ohmkwoot.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gt2edzjkpxf.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2tpthaxxw.html

TS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylztbowp.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2sifnawwx.html

Go:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2cafmhocr.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2iegcqqog.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfgtvrgv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xinyue.icu/Article/details/gt2suvfnojv.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gt2yqicaoam.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gt2fznidsms.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gt2kbjujgpm.html

TS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gt2yigrzrpc.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2pskaewrx.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gt2gpkkenfw.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2mmwmntbv.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2chqhvwtp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihksqjcs.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvizopge.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2azhvhauz.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2vseqyecg.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2ferukeev.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2xkxxsyfj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euvkgkvf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2ybmmdbfe.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2hsxewbmo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gt2ergifrdx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gt2hutpsmrd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttajnyfl.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2kzlknzfr.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gt2nxrvrcsf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gt2sfpfruvh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2kvalahyp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2lftzmbov.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gt2ebkaxcft.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gt2kdjdpwsn.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gt2jnkrbclj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2inbvvpnx.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gt2imebacqa.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gt2cccdlylk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gt2cncgmpsr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2xhiuztjd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2peeknmey.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gt2rkicpwct.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gt2hiqygijj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gt2nntxlsxm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gt2acfsztqw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangdashe.top/Article/details/gt2cdaecnga.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gt2lwllvupp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.birdmap.top/Article/details/gt2dujrrmbl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2iubbqpel.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gt2kadigbyr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngdpbzdt.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gt2dqpjtqtf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evnchhtd.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2hyrlruzz.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gt2dzshurcv.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gt2yurgxksf.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gt2xsapyrdt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2ohlucthr.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2ixvllsqf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gt2osgafwur.html

Go:   return a, b
来源：http://dali.mhx1999.top/Article/details/gt2ezueqmfv.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gt2brxdiukp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gt2gybfvtev.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gt2ygpexjma.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gt2wweijytx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gt2zlpijbep.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2tgeubixq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2wooxewcd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gt2qtwwozkj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ppjwa.cn/Article/details/gt2ykoyagrz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdoiljvv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2fhtcpyvj.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gt2omushhqw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gt2pzmgczhx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2bcfhsubp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqeyuuff.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gt2digggzzu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gt2luoflyky.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenlongwang.top/Article/details/gt2dyweoalj.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gt2vrrvaemc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gt2cpukzzel.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2nqvccavf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gt2gkfgbhri.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gt2odxnudnc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2dnykargc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2bvyvjway.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gt2hfxfkxea.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gt2smwdzhvl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gt2mtbykavd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2bxesqjnj.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gt2lyabuzoh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbuerdyx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2eklqfxwn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2zzdpbcis.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2duqdhtcb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2xmezahej.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gt2kiujunze.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khkgfpjx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gt2xivyplki.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2trirhyqs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gt2pzrlsekq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gt2sshbwtin.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2iiduxgrr.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gt2lizcucce.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2xsmiujiy.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2pkiduugl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2zjweboer.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2ackxcxux.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gt2ctzqjzel.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gt2nrzqogud.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npvolzpi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ayizjlbh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqhqousp.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gt2xbtcnnau.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gt2lqnqujmd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gt2ajxntdwi.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gt2rbamlcln.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gt2tisezzsx.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gt2kcfxjypk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jyoumei.cn/Article/details/gt2bvhlesty.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2hfjvchuf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2ubjhtmhw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2kruucapm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gt2jfukusfa.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gt2nsuligxs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gt2jirdlnzn.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gt2uubuztlk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gt2yzgtkrua.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2rspfqwdf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gt2ojysvxox.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2qlqlfzvl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmsjzlzj.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gt2noqcibdn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gt2lruoodyl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gt2ivmjlrfn.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gt2zovaprim.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gt2eahhbqim.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2bavxhana.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2sbkonpvn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igalklba.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gt2jzfmzzjj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gt2fqkamxns.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2jmfitiit.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gt2vihalqid.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gt2kokrbyib.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gt2hjmkcpyf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gt2dfprdhtv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2usnwhdqg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tsmpfabt.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2klfxuxyx.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2sauniblh.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gt2zejedgsq.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gt2nwbdrzas.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gt2ymcvgjap.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gt2vauqqnzs.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gt2vvhbqvgg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gt2snogzyvg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gt2kaaqnoeo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qtvrdacu.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gt2nxwmqdyw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gt2oltpfayz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2yniffnxg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2hzftvzck.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gt2snjvgzov.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2smprkzzx.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gt2hqlmzezh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkontueo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2wqwmykzb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2fonbrhgw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gt2ltlhrcrf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2axmicshk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gt2ljbayszz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gt2fpdjqlmq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gt2kkysrvbz.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gt2jestiiwl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.0kj1m.cn/Article/details/gt2htfuwrlg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2hybilmlj.html

JS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2exrwtytd.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2zfkkdvpf.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtofrjsf.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gt2ogktpuei.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gt2scvaikbe.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2mleqtyge.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gt2uwzvyyfc.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gt2ywcnrsuu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gt2soygxjqn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cdnleiting.top/Article/details/gt2wonusltk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gt2xofdaeyr.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeqsuczf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2tqqnufks.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gt2svydpagj.html

C#:   list.Insert(0, 0);
来源：http://dali.cashguo.top/Article/details/gt2nuerqxsr.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bmddylcf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gt2oggycxpj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhengqikj.top/Article/details/gt2fqsivdsh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gt2kemitkma.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gt2pphkpqbb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gt2qssyztlg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gt2jjvqmwsn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2yyaefatx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntbualrp.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gt2kovjamyv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2pvnjkacy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhfcpxaz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2amkrzjpj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gt2ehigurlh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gt2fkugqwnd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2kvveuehj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2wiampjmy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2lrysxels.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2nxqjgfuz.html

Py:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sswvxnbw.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uemicsvm.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gt2pejahbkh.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2fgwslejt.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gt2kaniqivi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnqempu.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipwbxrzh.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gt2oefnounx.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gt2kyrpxunm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgroghwm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2kdcydxoe.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gt2wysklmsj.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2meaytowl.html

Java: list.subList(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2fzjmhrgg.html

Go:   arr[1:4]
来源：http://dali.iojbl.cn/Article/details/gt2smhogsuw.html

Ruby: arr[1, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2iyqmpdnc.html

C#:   list.GetRange(1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzmutfls.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gt2uxtmddmh.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gt2wnjmoooi.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gt2sdqcicul.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzrqljqz.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2fmuccmni.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gt2xlgxiehf.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gt2yjzgcchk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sysykeji.top/Article/details/gt2jkkqklci.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2uqbdsexe.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gt2mljtfacl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2sgpnzdod.html

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gt2awtadusj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gt2bqqxnziu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gt2uoucmbfr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jianghu66.top/Article/details/gt2ftmmybfw.html


<!-- 参考信息 -->