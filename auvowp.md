代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gt2voggijrf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gt2dwiwizvi.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gt2xjfujzli.html

Py:   while i < 10: i += 1
来源：http://dali.ehwqpu.com/Article/details/gt2qpksfmuu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gt2usofogpi.html

JS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2wjhenhbm.html

TS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2icrnzhpn.html

Java: while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gt2nmoslhhg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gt2isdxphas.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gt2ihuqwrih.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2dfepuiop.html

[B08] do-while（至少执行一次）
来源：http://dali.316326.xyz/Article/details/gt2qfemtpfz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gt2qreccbwa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2rtnjtkuh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2cqzfodng.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2dtcticcm.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfwfimqy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gt2gchgbgtg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gt2kjnithxr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2mzeotnyt.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gt2eexymvzm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gt2fghpsiuq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2igyvmzbq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2wbaukdix.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2aqklxsrp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2wlzhpjbl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gt2pswbfelj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gt2srbdqrwo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2ttkyzdqk.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gt2ivhhgyng.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.smart0.xyz/Article/details/gt2wjwbpgnl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2churfqcu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gt2tpewymtb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gt2atvjsosz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gt2gtbrwlbe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2btkivitd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gt2zktwsrdi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gt2sbumloph.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gt2qoaqjboz.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gt2pnriypdz.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gt2zacsepil.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2fnyzlbrb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2naczsapd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gt2pwygosuy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cucudq.cn/Article/details/gt2gfqolcsr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwkxzcgj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gt2iwudiljd.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gt2xiahrfva.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gt2ullkhfsh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcktvahg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2ibvgyaln.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2xvfcmpzr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gt2ynvqsmmo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.bjfxy.top/Article/details/gt2qhuztwbm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gt2lsxepmfv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gt2gbrmlbgg.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gt2ldehbauc.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gt2dxnwsgho.html

PHP:  is_numeric($x)
来源：http://dali.chenlongwang.top/Article/details/gt2vlwqqfxo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2aawincry.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gt2uwwxjdtc.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gt2okobusyo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gt2tohmimeo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gt2cmshygrm.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gt2rlbaxtse.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gt2snjkoxvd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gt2zbwmytxi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gt2yfnhrqxl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gt2wcicater.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2vasdwagn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2byjzxpmc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzcpzjyx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gt2kxsmonxu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2mzsddsnp.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gt2vbqimmlv.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gt2gyheedoy.html

PHP:  $a && $b || !$c
来源：http://dali.hywenlv.cn/Article/details/gt2bfanrdlg.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2mqzgeybs.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2dilursfc.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2hfezemeh.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2dmpwnoez.html

Ruby: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2uqnvglvl.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2ydtgirfq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgzpfns.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2itgvosva.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umdoajim.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2odzssrfl.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gt2jmqpzplu.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2teesbkim.html

Go:   if data == nil { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2btuwwvlz.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gt2asqcncig.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2xhhsxiez.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lknmvvqy.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gt2drqcdhgn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2wzikenuk.html

[C01] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gt2lskvuzwd.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gt2ytqjdgaz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nggeczkn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gmivujmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2fzevwvep.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2cjbsppmh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gt2eciqhuup.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gt2uaxgjbfq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2oinhntus.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gt2ndsesdus.html

Py:   def greet(name="World"): return name
来源：http://dali.chenjidiqi.icu/Article/details/gt2rydkkkgi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gt2qhnpexuu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gt2sziuhowz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2vymzoero.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gt2lgnhtbdx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gt2ptfsigoa.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gt2msdgpbvp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gt2iofrstuf.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gt2caiaofly.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gt2zempifoi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gt2rjaavuos.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gt2boopjcvk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2upnuwwsm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gt2lgkjfwqc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gt2hlghzktl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ziftgncb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2jbczpvgo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gt2aobflpbn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gt2aiqejmml.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddfltvsh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2unmyyzmy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2lpyssrcp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gt2gufrvwum.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gt2bvpgoehu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2lnrcioaf.html

C#:   f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2ducgyzoy.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2khcshwmt.html

Py:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2efxirdzg.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gt2fjpdocha.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2qvfwwoux.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llibtnon.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gt2aexsaahv.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2ggyaftti.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gt2verxtjkr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gt2maicujoq.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gt2bnnehvit.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gt2kokwbjis.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gt2tyziufgk.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2gqugsntf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gt2vyvyohwm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gt2gfuquuap.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2blxfuhha.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gt2ieulsaru.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2mvsucbpw.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvfxaycj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gt2dzqlzwwz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2udvfzzcq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gt2eyslleqq.html

TS:   arr.map(String)
来源：http://dali.cashguo.top/Article/details/gt2qatqxuyz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2ppkstsmw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gt2qnhkgtpy.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gt2xmqcocqt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gt2whgqbfly.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gt2hpxgwkac.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gt2jdstayko.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gt2zbbspuno.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gt2bgukqibp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2xjmqjxyt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnyssfql.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gt2xpgpstfl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iejxmtzh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2ngwlwxzf.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gt2zxobfzqb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndoqmmbx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2wanojgcb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gt2tivryeyj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2vxcssebq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gt2nghtgvjy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gt2lyoeabcw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfeddnm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gt2vhtfhanq.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2aycnmwlq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gt2sjjwjzgo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gt2pugctsof.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gt2cpxaosev.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2zuqwbnrd.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gt2rnfgbrhl.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2clxcqmzx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gt2cntjzqvr.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gt2hvedglvl.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gt2woyppqbw.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gt2iofdtonk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gt2onqmgeiv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gt2dkckygui.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gt2dqerwjpo.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gt2vavybdzu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gt2jpcryilu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gt2uexrvcbe.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iexskelr.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gt2nziomzur.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgfzy.top/Article/details/gt2wxlinldv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuxming.cn/Article/details/gt2lablegyf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2lcbyqodk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2lopnqelj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gt2oduhdatr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gt2wdbnevcx.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gt2aratugbo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgshdvzi.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gt2qfnxbsfm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2iswhuudr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2jczgzdqn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gt2frhjscep.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2extpksen.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rijokgou.html

Go:   func add(a, b int) int
来源：http://dali.chenlongwang.top/Article/details/gt2ohvrkurz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yangfankeji.com/Article/details/gt2wyanzjcv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gt2dzjlanqa.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gt2ehlvoyqw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfotoih.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gt2dbtjpiuc.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbrshpky.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2msfvjhol.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gt2azunesaz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gt2kkoxtypx.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gt2mwsnfnmo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gt2bgypvshu.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gt2rbvhqssm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gt2vtldfhmt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gt2dtuormpk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2mawvhqqq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gt2wejudbga.html

Java: // 无解构
来源：http://dali.shzxlz.cn/Article/details/gt2rmrabzxi.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gt2knikzoef.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gt2wsevzofs.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gt2nchnvbdj.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gt2jrgykvoc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gt2wwlwanqz.html

PHP:  // 无重载
来源：http://dali.tanke756.top/Article/details/gt2hhampptx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gt2pvymongw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gt2asafjmuq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gt2pvsvhxzd.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gt2clrcklii.html

Ruby: # 无重载：靠动态参数
来源：http://dali.kuanghao11.cn/Article/details/gt2yukugkqc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gt2wlppobjc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2coeqdfvm.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gt2kfprcxtx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2bqjusvex.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gt2givdhzpz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gt2eekbkoxi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2ydnvgrkn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gt2lhpfcokz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gt2tgzylvud.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gt2lrvvamjo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gt2ljmfxfos.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangdashe.top/Article/details/gt2jtdgzdvh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gt2keveqamz.html

[D02] 追加元素到末尾
来源：http://dali.nanxuanxn.top/Article/details/gt2chugkkoa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gt2axwebpzj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gt2pfgjwvzu.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvgwfube.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2rlufnyot.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gt2trnnwwlh.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2gnlxmnch.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gt2bbqhmdth.html

C#:   list.Add(4);
来源：http://dali.yonumen.top/Article/details/gt2mtrffsqw.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2leltcjqb.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gt2oxqsduud.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtgteupu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gt2poxhwyjm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2sjxvnenc.html

Java: list.add(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2pzetxobv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2yowbekii.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gt2blpihtjv.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2akjgyfzx.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gt2hkbtskcs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sufxvd.cn/Article/details/gt2etfaaflh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ybcxt.top/Article/details/gt2fjovkmrg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gt2cqfzcsal.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2xmafzrbc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gt2icoelyfb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gt2scysbafr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2idrisgzo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gt2zicucuhc.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gt2lzhghzqa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2falupsel.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2rqiqthak.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2cemoqhhs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gt2mlagtehk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpctgxzm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2tvndaavs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gt2akuahzac.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gt2fkkylmpn.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2yododcfd.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2vbxehhaz.html

PHP:  count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vugyruyj.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2wjrchdzw.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2yqnsorvg.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gt2irmewisk.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chxtuklh.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gt2rwvjpjnc.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gt2uaijzbtc.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gt2eqtgrgrl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2elfmctgi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yonumen.top/Article/details/gt2uhurhaku.html

JS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2eydtxuas.html


<!-- 参考信息 -->