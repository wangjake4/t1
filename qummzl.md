代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtgtyyxyvg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtfupekciz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtwzdwdfuh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtgfpbnlwv.html

[B09] break 与 continue
来源：http://dali.xziqi.cn/Article/details/gtmxtmjdwu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtdnynjcez.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmlwqvpb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtyqwebzjn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtgbdyjlrt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtloglulgy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtrdjdcvwd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.0kj1m.cn/Article/details/gtpnvxpkbf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtcpfiwuml.html

[B10] 遍历同时拿索引
来源：http://dali.gaohongyu789.top/Article/details/gtdksxsoup.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gtwfhudkdh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigufen.top/Article/details/gtjbsnltvq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcfnyjjwh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtsdzxfhnq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtwqzbamsz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuanzx.com/Article/details/gtjpqioirk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gtnpxkuphw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqzfzxamn.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtwrztssvf.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gtdwnwbevu.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtewdwbrcw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtufmdfurv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtxcayyohd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gtyeyryxfv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gtbiqinbjo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtcyxhymlf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gteziruhsr.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gtaesghthk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtikwnpisb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxuanxn.top/Article/details/gtenqjuktn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtlarpkojp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtgnalbsoj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtnfqezlon.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gtqtskjlpo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtkoswgwlp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtpdvhysqv.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gtjjfjzphg.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gtbxzolajd.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtfutdjqrf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtrnpcglmn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtfhtmdqhm.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gtzgwsfrep.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gtmhqdqkky.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gtjecfhqgx.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gtqaooklmq.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtrnawyemg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gtqyovowml.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gtajspdqtp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtogpyjlai.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtvcxrmnrm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtuehdebpv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gtxobycbfz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gtiahxyygb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtjrgxkufc.html

[B15] 布尔运算与取反
来源：http://dali.pengpengdd.cyou/Article/details/gtkhvwzghj.html

Py:   a and b or not c
来源：http://dali.zhiwuduotai.top/Article/details/gtiycwtqwf.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtskaskdxe.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtcjdfuwae.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtdqvkonqo.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtratqjhwe.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtofqqkofa.html

Ruby: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtqcgypukc.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtdevqmgrl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gtkwfgkutr.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gtjazanyhm.html

PHP:  if (!$data) { return; }
来源：http://dali.xylfe.cn/Article/details/gtvsttawzp.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtslgljbuy.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtbtpddxob.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtnwhfgzvt.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtizcqvyxm.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtukgcnvng.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtlltczmfs.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtumiwvynh.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtfhdratzq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gteuakesue.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtnzzsigug.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtrtljdxzy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtsbwotnry.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtaijsiuwa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtqonbjqbz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeylqzcf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtamdagyem.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gtbjflyyxn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtxrhmxsuy.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtwbelpgok.html

Py:   def greet(name="World"): return name
来源：http://dali.yuanzhike.top/Article/details/gtkhwydlxr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.bjfxy.top/Article/details/gtjtequkff.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtncmwwbko.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtwzlnnvzd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtbwhgczse.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gtqonkgtww.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtkqmgbcuk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gtgifrwmnu.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtaoihnkpw.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gttolofdtp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gtfwxlxqul.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtamgqbzbe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtarmjuzxv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gtapehfkeg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtlgzzlbbt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gtpjvmgybc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gtjoxxispi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtkfvgwaky.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gthwcswoty.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtacvhuaqr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtwufrkskg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtbqdlylro.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtbdwavuoz.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtfgwpzykg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gteuixjkvp.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtabmuigpb.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gtmlxfslma.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gtdjlwbdww.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gtzksqwwrw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtuihmdhrs.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnditseul.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gtppmkjzpn.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtahmwzoin.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gtyqsgeqyl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gtymobnkhf.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtztgrcocn.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gtbgeisfrs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gtvlmvvlzv.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtmzzvtdeu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtqosvbpbv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtfizokwbb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gtstaqdknr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnznjdyvu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtcilxbaki.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gtnhayhmol.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gtiqttyfpn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtmtrozqey.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gtincsfqbd.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtyllpsabh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gtudxojwcf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gtwancqpjr.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gtkmzvsenf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gtpurkcnko.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gtvfonqygl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtqpnqayan.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtcgkbaguk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtwswdkltj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtpwtjmlfi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gtsnurctnj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtbytdjfoy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gtisfzfxor.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtmhwxhwxm.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtcmuaivdk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtuxuzqsmw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtqmdvwaid.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtsryujqui.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtchfrviyc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtdbflngji.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtxuvtfprl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvhppuvv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gttlwwatde.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gtmmdnrjgn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gtdtdzmeyw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gtcligwcjn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gtodymalbg.html

TS:   同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtpoqhmlic.html

Java: 方法内为块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtzeaoinzp.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtuxgdwpht.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtuyiqqeng.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtrwrskzst.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gthelobhzq.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gtvkswvdel.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtrgtquyar.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtgejeiyto.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtvdagrbgr.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gtypbhixft.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtzrqsjmrw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtdxtbzywx.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gtoemkxkjp.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupayfnnq.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtjrxcdnsc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtwxcceauh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtoscaujda.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnzyilcc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gtexgyufno.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzfqibsg.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtzkmqhyis.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daria6918.cn/Article/details/gtxrxaklda.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gtuggtnzpe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtjzxtqjej.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrvscitcz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtifeomeor.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtagvbyqyz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtrnzkcrvq.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gtglrafpmz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gtjmqujrhl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtwyfwhokz.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtktcpgkmg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtdegtysuf.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtikiamqau.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtdrqfmfgn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gtesoxhlcf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbadnowx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gtfhkxfxta.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtfgawzdqu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtkmkrewqu.html

[C15] 解构 / 展开参数
来源：http://dali.zhoulong.xyz/Article/details/gtcomtxwlf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtufqefpmj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtlwgbgkfk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtfbvvvcdk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtfpioxtpa.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtfcshcriw.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtjjzkrcvl.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtqxnmqeun.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtssbyqcno.html

[C16] 函数 / 方法重载
来源：http://dali.hywenlv.cn/Article/details/gtjibaysel.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtrmtplttz.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtrijpphwa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gtjjiecsfh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gttnoulaeu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtkhdxbmrd.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtuwcartki.html

Ruby: # 无重载：靠动态参数
来源：http://dali.c1oappe.top/Article/details/gtxznibfzg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtpzmepxdv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtmhjswcis.html

D. 数组 / 列表 / 集合
来源：http://dali.fzhhl.top/Article/details/gtvqgynlio.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtmcjggylu.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtwzpszjtd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtvhpadkww.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtuyjcbzlx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtwdjunrqt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtgrjgvaen.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtchhkmrrt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtqqtfhhgk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gtgduewjzw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtzbzchwpt.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtwkchkksj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gtqhcchvaz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtrnjozyht.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtsgqyawmm.html

TS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtdgoijcgq.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtmblmdxdu.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtvsjiorph.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gthbfwjurd.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtljnarwip.html

[D03] 在指定位置插入元素
来源：http://dali.ppjwa.cn/Article/details/gtsfqeyfyz.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtuystsmph.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtegremhjr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtsludcicr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gtawnvkbcb.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtzihapdfg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.birdmap.top/Article/details/gtlbkapkyq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gtstazkstm.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtxbyjhcoh.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gtplcrdzdg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtbwvauafi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gtzydpqojx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhoulong.xyz/Article/details/gtglxmndkl.html

TS:   arr.splice(0, 1);
来源：http://dali.snrcjt.cn/Article/details/gtegtzmfos.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gtsrrbmmge.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gtbycxgmme.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtkhhkufyz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtlkydkqgi.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gtcaapgbgt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtdwjdhmtd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtpygswbci.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gttvifiryz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gtgzqngdsp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gtsuolwcjz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtcstuhoho.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtsbpvgmbi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtbrcvaoiz.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtzaouyijq.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gtlbadllqs.html

PHP:  count($arr);
来源：http://dali.daxiang520.top/Article/details/gtjstaqkhu.html

JS:   arr.length
来源：http://dali.yuxming.cn/Article/details/gterxgxign.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtjjkwpfzt.html

Java: list.size();
来源：http://dali.fengsongda.top/Article/details/gtnrrfsvye.html

Go:   len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtwvwvpjav.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gtvontlyoj.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtknpyevsf.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtqhmkiwpc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtmmymiesg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gthwjgrcwz.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtjclmsrdk.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtjizzbgqs.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtivzudwog.html

Go:   arr[1:4]
来源：http://dali.yanxiufei.cn/Article/details/gtspdrxngj.html

Ruby: arr[1, 3]
来源：http://dali.xuanzx.com/Article/details/gtpdvbvnop.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gtongbrzbe.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gtvlzqbvlb.html

Py:   a + b;  a.extend(b)
来源：http://dali.ehwqpu.com/Article/details/gtwzyfmagy.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gtsfqfmozc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gtdlatkoyl.html

TS:   [...a, ...b];
来源：http://dali.tian-w.cn/Article/details/gtvmrrycxp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtjknrbylz.html

Go:   append(a, b...)
来源：http://dali.yuxming.cn/Article/details/gtuxjwdvzd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cqqwz.cn/Article/details/gtvgxdqlhs.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gtujprsohc.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gtpeztpfgx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtsxwasxwr.html


<!-- 参考信息 -->