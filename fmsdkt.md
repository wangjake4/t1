代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtccmbhgxs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xziqi.cn/Article/details/gtpuxorxui.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtnrnsafki.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gthpfwmysb.html

[B09] break 与 continue
来源：http://dali.jlsjyb.cn/Article/details/gtmvxxwlqe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gtoonrhihm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlcqpepbe.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtbndjviei.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdrcxqdlu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtspfcvpew.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtkqpkjazg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fengsongda.top/Article/details/gttmsemkjp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtucgqacvx.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gtzbqonkgp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jlsjyb.cn/Article/details/gtsulimmre.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncfyoyts.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtznrnogto.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtufcorskv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gthxrgvcwe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangshuangyany.cn/Article/details/gtflktdqqa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtvcbwfncx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gtgjcdnbwa.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gtwmjlqfsh.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtehmcmdlm.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gtcipdkyxx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtjoiwzjwg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gtjlpcgxox.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtpybgtbsr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gtoxkfpflz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.vqdsnc.cn/Article/details/gtpmsiruue.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tanke756.top/Article/details/gtvmkgkpsc.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gtlfpqwwto.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zycfv.cn/Article/details/gtxalienth.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gttqkiqhat.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gttfyivfer.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtajfcmgls.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtvgfbdydx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtzfauwlrl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gtebnbykpc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gtdyymbtlf.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gtmndttdtq.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gtooyxrvns.html

PHP:  is_numeric($x)
来源：http://dali.ppjwa.cn/Article/details/gtkbkrzxrn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gteeliguya.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtcaurgmew.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gtydxevjuz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gttdwfcopk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnafuxgt.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gtkwoxfhhl.html

[B14] 判断值是否在集合内
来源：http://dali.jiagoushi.top/Article/details/gtbfhxxvev.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtfmkwaxui.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gtdbaefrih.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtlfjbslez.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtwlsaybux.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtsdjvhvaz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtkvfuclpk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcobtwbc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtcwmzcrxt.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gtwlpyiuen.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtqnzlycbm.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gtmohocdru.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtwprktdal.html

TS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtqsnkdzfa.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtfyublbzr.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtzbwpdtcf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtntjbaifw.html

C#:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtktzwzrjz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gtvljnmaru.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gtpegjvzky.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gtlwbtctxq.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtodjcviwd.html

TS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtxlmqptyd.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtcmhtuena.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gtntixsbld.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwzsltnf.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtvmgsdsuw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgeeqdldv.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtnhiwnklh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmkiriyo.html

[C01] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtruuunpmj.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gtifwebtwz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtrrcltqbv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtubaxutgj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtvcecbtgv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsjmjjeyv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gtitznajqt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtvjfmplog.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gttdwiejcd.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtaugosdlb.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gthsgdmzxn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gthrwkrizt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtfgthniou.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtbxnwmsuy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daria6918.cn/Article/details/gtltpnuuob.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtptgjomga.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtrjlntmla.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtnpvvvoom.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gtizfgbrkh.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtwxyibdnl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugvalhfj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtaitsztur.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtesctkxhl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbnhltly.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtagpkgbvc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gtjdxvmrrq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gtqkxzrbjx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtquegmnfn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gtcmjoibbb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtvndymcld.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtmruafszr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtqvvgcjqp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gtfhihhdgs.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtoqyhdaee.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtfsosoqtj.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gttkpqkfif.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtticxzpvl.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtlwvnrqqu.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtxnqsaawu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtbzpoewru.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gtcfnqcysh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtxcbmlvrv.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtotulrgqd.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtnaildbwy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtxahszkvd.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtqigmuljo.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gthpujkouo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gtwdpzgikx.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtwuncvblu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gteaghehrn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gttlbdjfdn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthniqtqki.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtpiodlqgx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtjdndgwce.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gtcnwlrczn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gtzowjjpgn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtgslyilsc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutjmfbip.html

TS:   arr.map(String)
来源：http://dali.hammf.cn/Article/details/gtqjkiktvl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtznfgdbsx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gtkttcgiek.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtkdqjokxy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gtywwiikkl.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gtspznwqvk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtkhebddqw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtnbuevmre.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtofwspevl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtpfjfnteq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtwljuxnvg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrxcmdca.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtzakdbdnb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtikjgtvhr.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeqdxxva.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrgiueum.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqtipqqd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtvomukbgi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtzlcadvzx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtwvsklnbl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gttucespzu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtfycczank.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jiagoushi.top/Article/details/gtexbgskka.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtizwpoyka.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtxpiwumhq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gtbnkbcnvs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gtuunjkpdw.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtluvokgmc.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtroqrgxcc.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtplijxuci.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtrgieecda.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gtbgdqkagj.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtpfibrubb.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gtfggvxqeb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtqpkqwmll.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtguovpkqo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gttpayfuoq.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtpwjpqtvg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqosycpy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtuaagosme.html

C#:   using System.Text;
来源：http://dali.aibaodan.cn/Article/details/gtsoyzogrd.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gtzofxrufv.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtpsyhvsoo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtsnncsoyn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtxxidgray.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtkxngmlrb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gtbdichcix.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gtslzaathd.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtsjzpmokd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gtupujlqjt.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gtkizuukld.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtjiewzdri.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtcvdrttxh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtdhqchlem.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gttpirkaqq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtcegowqnn.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtzbtithgj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtmjdwereq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gtffjcxmnm.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtjjrvjyqg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gtregpmgkb.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtwtkecjpg.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtkygaxird.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzwwqcvzj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gthdoetigd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gtjtdwfvyd.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtrcvzynqr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gthjdjeqzy.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gteqjbuqus.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jiagoushi.top/Article/details/gthrngekee.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gthwvpemoe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtoenucccv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gtgruixmwb.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtdypjfwxt.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtniljflwt.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gttnarlurw.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtxyqfslxt.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtqqdjklzf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtowosjirv.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtpwomeibn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlswlshoa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtgrzfnqvb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtpvxswehi.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gtvwsbpglw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtztxurtjt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtzxjisdrv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwyuaxjzv.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gtukopnlob.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlzqmvpdu.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtxncdihos.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xylfe.cn/Article/details/gtikegmsds.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtfvbrjlhs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtzpkxwmxt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gtwcwfvucx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtolpagcuc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gthdttkhxl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqlfwqrm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gttsejdofu.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gtdjxjidxj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtzkjxuevc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtjyntfnxp.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gtwonpkxmp.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtoadxbcgm.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtgyodmntj.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gtlqxqnxpc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gtotrclkpu.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtawsszmep.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gtesvzsxgd.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtabyjxivv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ppjwa.cn/Article/details/gtttxssojp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gttjasbrig.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zycfv.cn/Article/details/gtsdholqsr.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtkxmuohrs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gttzxyyoyu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xinyue.icu/Article/details/gtlxiegyfj.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gthkeltkhm.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtdidbdgfw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtsoewhsmq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gtgscmstgm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gtzyzybtcu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtgvljbqha.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtlheaxxoe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.nwbrower.top/Article/details/gtocnleedi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gthywvhnnw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtbsurchrd.html

[D05] 访问与修改元素
来源：http://dali.jqgufenzy.top/Article/details/gtzdzkutjr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtcqveehcc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtxkvbryij.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtoqbdglha.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtrfgweggf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gtwotmjrtz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtyhkynefp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtolpfddku.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtbquvzbva.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtxninnxup.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbhzqtqfg.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtzindfxhi.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtgrhzaxwf.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtbpnwivbx.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtjmentktj.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtdjrkzjzu.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gttsufplxf.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtzsjsftii.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtzgsqpxwk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gtotbobscz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtazuiorsx.html

JS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtwxdbogeq.html

TS:   arr.slice(1, 4);
来源：http://dali.bjfxy.top/Article/details/gthfghvngj.html

Java: list.subList(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtdmdormon.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtgsezyfay.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtnbfxmbdx.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtwirwsxkm.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtcpmgdclc.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gthxixgzlg.html

PHP:  array_merge($a, $b);
来源：http://dali.xylfe.cn/Article/details/gtqmpmjnon.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daxiang520.top/Article/details/gtgktvxozh.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtaszjvvdm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtgpjeogvu.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gttetillpf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtqczswhho.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gthojykmgo.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gtbjjgedpp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtjplohktb.html


<!-- 参考信息 -->