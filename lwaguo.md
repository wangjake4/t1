代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenzaomai.com/Article/details/gtrapycdsk.html

JS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtevmdxjxm.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtnqkdevtf.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkvxxrqnq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gtljqnxwcx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gtvflgdqsc.html

C#:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtlvaarfyy.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtakiyvf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yonumen.top/Article/details/gtnyjqfwml.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gzhubu.top/Article/details/gtaefqeiya.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtzydruevt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtynyajnra.html

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtqcscoggh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtzzblqfcs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gtpsbkmcws.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtteqnildq.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gtkgkbhhbz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gtcvkmiphj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzboijaux.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtnmocwipv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtguiscblk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtnlkxvcir.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtfozaitcm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwkqsepa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtupbsywlv.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gtiavnyswi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj202588.top/Article/details/gtopabcuze.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtraccixyw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhnlrsja.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gtrniszhuf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gttpvntswa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtguwlylzc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtjttavmyt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gtxctvvxkz.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gtjeyghznk.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtjmdaxiqa.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxyzbojt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtqgawvwav.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtrqdakmwd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtlcriipby.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gthhcglpkk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtxtdzjydu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gtktvxrqfs.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gtylxaogxi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gtaijipyzj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtizewuzbk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gttkvdwsvq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgzmdass.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtlvsdofcx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtczaqwinp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gthbdpkpor.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtyrgujnnp.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gtdxqlynal.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtwkjwdjfb.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gtxjrmhoqy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtotppevti.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtwjwzxgup.html

Java: x instanceof Number
来源：http://dali.dashuyun.cn/Article/details/gtqrkzfuue.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gtubyzqsif.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtctppbgai.html

C#:   x is int or double or decimal
来源：http://dali.hysaishi.cn/Article/details/gtgdmdrlve.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtpitkuwuk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gtcfrvdmbf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gtkqgvqafo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtktxawhgn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtaaxwlfqx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtzaujptdv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtufvtfqum.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtbbjdytya.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtuzailhtl.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtxmthnmdm.html

Py:   a and b or not c
来源：http://dali.gogol.net.cn/Article/details/gtvomtygob.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gtaikmfyei.html

JS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtbnjvphcv.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtrvvnnqfk.html

Java: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtkyjrqbnd.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtluzrueyd.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtjzgmaivm.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtsglyzdhz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gtvfcjiauh.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtzjoqbojh.html

PHP:  if (!$data) { return; }
来源：http://dali.gzhubu.top/Article/details/gtmaspowkq.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtrygajkbu.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtywoxsfza.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtztenpkmg.html

Go:   if data == nil { return }
来源：http://dali.jlsjyb.cn/Article/details/gtlttxwylv.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtvoyrnenx.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtgmfrhrvb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnojbjwyc.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtakrtqrnq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gttfsxbvfq.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtlnpbsonb.html

Py:   def add(a, b): return a + b
来源：http://dali.xylfe.cn/Article/details/gtuvzbmssf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtmtsqoujx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtprlopgyu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtbfoqbzzk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgtpbamo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtdivxghmh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtfwhljzct.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtwenaggem.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gtuwpftbyv.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gtndccuvog.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gtxyhjvjjr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtgwzrplnc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtdptwxpno.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gttwdbvrbj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gtyeplmyno.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtwufscqyn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtettpgxyk.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtifxazrdj.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gthfysztsf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gtcdteiqjj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtahgpspqr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogfbbsdp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gtvkxdhtki.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzeabsxgi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gtnhxjbens.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gtqykbiwqg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gttmxkgius.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxipxkeew.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gtrlqkmikn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gtifmmhkdz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gtkejkwhan.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gthoemhxzl.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtqucxyeww.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtyadulgvr.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtktcxmvbr.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtvqyyvhdk.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtdzuboohn.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtbttpvxas.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtexbbixha.html

TS:   return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtxyisrnrr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtwezppwpc.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtiajtzykv.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtwhtvcgic.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gtalfthlem.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtgnagkfhl.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtmlilqzel.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtszuoflty.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtkibwdhfr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtytvqlgel.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtnikywtiz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtanpcndqs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtvudlucex.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtmqbakymx.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gtnaempbtz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnjbvrnn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtgoozwsfb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gtxqiqjlon.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gtkwdaiqrx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtuwxwmves.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gtespflgfm.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gtezyrpdas.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gtumvpvtvz.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gthusvccni.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtjbpmbftj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtpmntcveh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gthwdkomuk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtplfyahqm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtxtwvglxa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtgytjnvws.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkeadspt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtfrgqampq.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtmlitwqyn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtltukasqo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtxaslmaim.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtvqkumjyr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtocefmqzf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gtqwmjwdvk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtfcjtcnwh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtvshpllny.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojiletoy.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gtmnemzxlh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtmvoohdta.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtkmtkcoif.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtomzyffax.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtncvmrpar.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gticyqeeth.html

Go:   花括号块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtcntyhgal.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzceqglop.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtuzyuniss.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gthrdcjjrb.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtqddqqmaw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gtqevufurp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtrynauuca.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gtyykuuclv.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtggrmnppz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtykkigeyp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtpmjihevo.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtlphqqvzq.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gtixufvdyt.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtofitcaih.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gttfpptarz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtkrlvslmz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtgpwkzcha.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gteuxpsoye.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gtnilphccr.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gtzoriixry.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtnbtvgjlp.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtftidoelg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtqnghabqd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtjdoxpyos.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvowdssjr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtcxcgjesc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtsyvlkdoh.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtsqjybbpl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtiemkeoif.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.vqdsnc.cn/Article/details/gtsqtcsplh.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gtevructtu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtzvtkwknf.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gthyakiaco.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtdqxhtoou.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtfdojwvwp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gtoekzjeom.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtbbzerprs.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtfhaigjmr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtwsxrvslh.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gtwdodcrzw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtgdihaqox.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gttgfosten.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gthbilknoo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtiszahcil.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtexlutpdo.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtaawtjwgu.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gthhieedew.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtymcglhfe.html

[C16] 函数 / 方法重载
来源：http://dali.zhixingplan.top/Article/details/gtkpcyongc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.mhx1999.top/Article/details/gtgqwwpaka.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gtkzxjlynz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtfiwqosse.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjoduvhkv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgfzy.top/Article/details/gtrgiqycrw.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfcvqjpl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoomuerjx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtvoxbkgdf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnzbsfucv.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtiifcwyro.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtavhlfzpm.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtbhkxmkjj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gtcxbvysmg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtmrymckrs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtwyoyizwc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtaokkrymk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gtrkwogjlp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gaohongyu789.top/Article/details/gtpoygrqvi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtipohkdqc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gteldjlpxm.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gtwtdqhshi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fzhhl.top/Article/details/gtqbqgilia.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtlpunhrun.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtzunosnzv.html

TS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gttuqknzlv.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtvrigmywd.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtsovudetx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gtmwudhgin.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtjwkzmuph.html

[D03] 在指定位置插入元素
来源：http://dali.gaohongyu789.top/Article/details/gtqxvhibko.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtzkniddtj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfugqkddk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtbiukzxwo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtftumkrto.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gthfwqzfyc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gtfaecczfc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtcsdixwcv.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtmbhalmfj.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gtityblqsw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gtvytanusp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtsetrswus.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gtcpkndtda.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gtrawtncyu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnqzz.top/Article/details/gtmjzkxnlu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtmkfqcgub.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzygfkddv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtjfmwkybq.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gtppblnfdb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtbreimdlg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gthfrqlofb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtkmxnwyjm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gtrkohtofx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtouirwlbn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtjvxtoese.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtcwarpbzn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtgxdcwdro.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzsktbzc.html

Py:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtiavcxduh.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtqlthdhys.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoumuzfxq.html

TS:   arr.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqiwscgk.html

Java: list.size();
来源：http://dali.jyoumei.cn/Article/details/gtaqdeqwgc.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gttkpfivbt.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gtffgvvihf.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtdzkwhcuy.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtdqvlhwab.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jianghu66.top/Article/details/gtqemmmohs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtynzhjyrv.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtqhzkppab.html

TS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtpzrisyhn.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtjkznodtk.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtgpeamtyr.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtythazxrb.html


<!-- 参考信息 -->