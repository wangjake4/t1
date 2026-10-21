代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwuoqibq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtswlhyhzi.html

[B07] while 循环
来源：http://dali.fzhhl.top/Article/details/gtcswceniv.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gtqktnmxno.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenlongwang.top/Article/details/gtghkpsqdg.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtrimakzzb.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtpxhgszlw.html

Java: while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtxbzgdsnp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gtemfbpnmu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gtbuwujbxq.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtjsprsuiu.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtqkxqptik.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yueranfly.top/Article/details/gtldrnxsli.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.birdmap.top/Article/details/gtszeqchid.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtetuhgkhb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtsrrhqmng.html

Java: do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtaortpilb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gtktostzqy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaommrgb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtvhsedogg.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gtqdjuxgcd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gtddvhbkbr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtgyfssheb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtajndwfba.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtxijwovgy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtrsflofft.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gthnwltxbq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtjtxtmeng.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtvbzmrxcm.html

[B10] 遍历同时拿索引
来源：http://dali.zhoulong.xyz/Article/details/gtjnunmoup.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtgrmnomqu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttmvbfjbn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtsnhrzxzu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtgqhvyscw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtyquatzcd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtisjidzjf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtoqtnlcfx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhongyouzk.top/Article/details/gtzekajqga.html

[B11] 生成数字序列 / 区间
来源：http://dali.snrcjt.cn/Article/details/gtirrtqeib.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gttdcbdgap.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtspnhroyl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gtjyvzjnta.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gtimjcixmp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gthesgfyzx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gthddbtmvw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gtudtfyput.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gtfhwofcio.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtxstwraeb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbowlxbtv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtwrprvrfz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtwwbcjnog.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtcfkquxmo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtomloijto.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gtdqrxdzuv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gtvbbxmscl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtelymnssj.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gtbijhbmeo.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtfclzytcx.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gtqlgaazev.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtwqykmgfe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtuwmqxcdm.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtutpyiwec.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gtjndgnzdv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtpfwowvvf.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtnvcztvnf.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gtddlunrud.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dashuyun.cn/Article/details/gtxyzjaptk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cheryme.top/Article/details/gtigsxcrln.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtfgmxjypt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtigbcbfox.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gtottkhgtu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtnbrvlbeq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gtfgxoweus.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtrfpxnxfk.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gtmlviqgce.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtnvpdrsmp.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gtnextsret.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtpnbmdwol.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtkrklpiol.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtgxcbhspz.html

Go:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtyzglppir.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtdvzzrixy.html

C#:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtijuagirw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gtnmfcwvdk.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gtyfubkdhl.html

PHP:  if (!$data) { return; }
来源：http://dali.ppjwa.cn/Article/details/gtnkrqaacw.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtqdrjflug.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtrgzgvvng.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtuhmcnbjv.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtdoybsxst.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gtlegpglhr.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtpeyfyose.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgagminkv.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtnatojtaf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzkabsmyg.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtqfwzmgjo.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtcenhvoro.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gthasxpikk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gttyqabncy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtbckpnqpl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtfjwwbhmm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqletelx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cqqwz.cn/Article/details/gtqoovxlur.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtnwvnykpp.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gtarnleuho.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gtopyxlmlx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gtwrqpvaje.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfxhneow.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtrinlwbnk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtxommgmtu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gtwyhuirkg.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtmkmwcjcr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gtvhetmncl.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gtuscwnabh.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtywenckxo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksmziniy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtwaisovwa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtloxcxwpp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gtuabbcrvi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtllxletzs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gtkteeocgs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gtsvkkrrhd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gtjlqwbcqv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gttaljhxst.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydlrlxzl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gttbljfimo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtarpnmuxk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtyiqyjmpi.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuanzhike.top/Article/details/gtbnvgvgaq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtpgjzfzkk.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtavkgqdui.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtuzqnvudn.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gtueujtvxd.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtpqynsmym.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtbovqydml.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtckbtbpqb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gtkekzrbdj.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtyamajbic.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gtncqyyeak.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtnyfdqocc.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gtynuayvcd.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gtktlvpuvs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gtvfzulnmg.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtmagejqiq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtsovlctif.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtjntlfldj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtnpotrize.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gtisclodyo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtlrojitfu.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gtgxokphhw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtqysioovu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gtictcbedz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtfypbyhvn.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyizshrqj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gttjiynbxe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gtyupuqddr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gtycmkyoqf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtaoefzxnx.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtoojfrfnf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gtaipdsqoa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvgncuukn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtkqrcfmoi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtkueolaew.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jianghu66.top/Article/details/gtsrjcbrww.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gteoirvjzy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gtkmeexory.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtddbeihvs.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gtbtuxtsde.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtgnchvywi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gtevbfjxof.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtrtbwnedk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtmxjndhoi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtbxvainbv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gtckwuqseh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtktisejej.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtowjagjuz.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtnppekeom.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gtpyeoafdb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtmtkmqpyj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtlzztdndc.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gteylkkext.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtxcxdpshw.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gtlyjvaagt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtndjslbes.html

C#:   块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtnszcybfm.html

[C11] 模块导入与导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxckzwfyt.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtpfxlnqzc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtbiylpwbf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtoiazadza.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhengqikj.top/Article/details/gtlwqsotno.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtbsaobsfk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gtsirgdxtr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gtjgktncna.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gtyqqesmgr.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtsbmmyfaq.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gtwtscifzj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yanxiufei.cn/Article/details/gtgdebqkek.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gthelvpicg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtuzvgiqjw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hammf.cn/Article/details/gtllligvme.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtxyecqlvb.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gtospqhjqz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gtqsoghctm.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtllnqbgrn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtoulhshrf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtkbnmtgkz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gtalgtxlqi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtctqgzzqi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrmykatuz.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtrgtvcvwe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gtezkgwrsi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gtfvhnbkew.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtwhsfqmve.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtbxixwyws.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtsqjksivt.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvvmhxsu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlqzezaa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gtfewtjzeq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gtiaddnjnf.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtpmxiubhn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtrbqojhqw.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtvybqhvue.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtshihzppg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtiqeqzbpo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtinvcczlz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtguhoqdfr.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtgmfghqlp.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxfhmgqs.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtmefvlcha.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gtwwiiwril.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gtutezbeks.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtdblqdwkn.html

PHP:  // 无重载
来源：http://dali.xylfe.cn/Article/details/gtgqkpivmx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gtfixiotub.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gttpksxnrl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwxxqswmc.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gttejcnkkg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtwprvpsxi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtmfcoardy.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrzdpkiew.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gthlzmbauf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnmsjmsem.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtqnsulhbb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gtdvvlmyvc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gtlwrjjljd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gtsddofmgk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlfqgtdt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtlxahcrih.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtpesdzcbc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtejofdozz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtjstmikmp.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtngagigxg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tianlin.xyz/Article/details/gtzndqhxni.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gzhubu.top/Article/details/gtjhlkamqf.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtltfazdks.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtsbfgvbgj.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtcnclbujl.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtbjkoykcd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gtbaxvyunz.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gtffrsptqa.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqcwezts.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwoworbj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtxmjkhbcd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gtcuzjnnbc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtzuspwsls.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtyrsvdlie.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gtomonfdkj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlrlikdw.html

C#:   list.Insert(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtbovndrag.html

[D04] 删除元素
来源：http://dali.cashguo.top/Article/details/gtuvfeupxk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gtaddtnnlf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gtkryegpsg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aibaodan.cn/Article/details/gtwpnlszqg.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrqjcemk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtqnisiref.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gtjodnvxnt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtwdznxstd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtnakzdvyr.html

[D05] 访问与修改元素
来源：http://dali.kuanghao11.cn/Article/details/gtodghskyl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gtmkijvfqf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtqawmeqgr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtuciunahd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtenlkvfrl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gttrnwxpsg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtebeajrws.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtvydafjna.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiqkwexs.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gthyvzxmgu.html

Py:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtvsfiuarx.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gttnccnzxy.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gtzvcyrvie.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtpkqtjfxh.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtvplwqine.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtovcwwlri.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gtsmbyshog.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtwhuoqzpa.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtwmqglnuw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.svipenyu.cn/Article/details/gtwdqwpyav.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ivvv.top/Article/details/gtalhorxqw.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gtljcdfsii.html


<!-- 参考信息 -->