代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daxiang520.top/Article/details/gtklsroqex.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtnrtfjrib.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwmmakxa.html

Java: while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtprvgzpwf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtcuqgutza.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yvedp.cn/Article/details/gthizhwudp.html

C#:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtejprumxr.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gtkitgnors.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hongshengwenyu.top/Article/details/gtqggcfayd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtescbvfnv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihzocijn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtygoyiiiz.html

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtffoodhsq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtkpyihwwu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yueranfly.top/Article/details/gthllzxysh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtfnzegotf.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gteozdplrt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtjdnpcdqg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtcglauxtb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gthgzgwths.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtxkaafmlg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdszzsmm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtedaoqbxz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gtpcmzbmfa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtqxketsvv.html

[B10] 遍历同时拿索引
来源：http://dali.gaohongyu789.top/Article/details/gtxtgqtwlv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hysaishi.cn/Article/details/gtjfrrmnwe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sweek.top/Article/details/gtbpztitil.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gthlmzsgak.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtowgymxwu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gtzqrwsluw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dianchejie.cn/Article/details/gtlntciydm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shuidangran.top/Article/details/gtzmicyhqy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtleiqzbqd.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gtijffdgrs.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gtbyaumemf.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gtqppsdvbe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtivxmpwyw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtfceerwav.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gtemyrqmrq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gtwwrjtbxj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gteajbxatf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtwjmkdudg.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gthafzwqqx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtcysldqcp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtkxchfvcy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gthajyavzw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtjieqbqcs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gthmnffcdf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gtpxbycfmm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtfuptvbfe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtbdiqsomg.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtboknorzg.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gtbcdoihqc.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gtugabivzg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadewmzir.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtdltzbady.html

Java: x instanceof Number
来源：http://dali.yanxiufei.cn/Article/details/gtwqouwcza.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gtzsowtweh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gtriknocwj.html

C#:   x is int or double or decimal
来源：http://dali.zhongyouzk.top/Article/details/gthsxfnmoz.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkvzudwo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gthspzmwbg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gtidirfrgq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahusbgso.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gttefaoeor.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gtaligafyk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.iojbl.cn/Article/details/gtzhsgjpdf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtsqyygmmo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtgavncezw.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gtpoxkqtka.html

Py:   a and b or not c
来源：http://dali.jqgfzy.top/Article/details/gtogijzglh.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gtxxwqloxo.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtkfeeuiwk.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gttiahlkip.html

Java: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtemfdtmma.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtioznfemx.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtucpgqtue.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtoqybowhe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtaccstfyn.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gtcfnjbmal.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtseebaajq.html

JS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtbnehbwvs.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtrhtpctyk.html

Java: if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtykhlrpbv.html

Go:   if data == nil { return }
来源：http://dali.ivvv.top/Article/details/gtznwabbiv.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gtqifeomey.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtywzuvisc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthxfodhvp.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtkipwibbm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbgtidldd.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtvqiywpmu.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfinmnxow.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtlwrqnuec.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzkvbafdd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtnefaigcm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtzgaunttp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gtnmvdhyyc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtpeiimhre.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtwqktbrjp.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtsuqfljyk.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtwuesmkzi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gtxhwxbxpa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdotfiaom.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtfqmeypgv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtqvididmz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtztjhwqbn.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarlcaywx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuanzx.com/Article/details/gtnhkhjgle.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsfdikwn.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtyjdamdny.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gtzzanzoir.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtvfagqzcm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtjgufpejz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gttzibstrl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gtwmtssnmi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cheryme.top/Article/details/gtymkaivmz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtbehwksiu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gtpkqdwobt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gtgvevpbkf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gtnnnumwsy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtyljuahxt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gtznbqjubi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtswsmaucd.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtjxcndzij.html

Ruby: f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlbeduvxa.html

C#:   f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtlvegeqcu.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtsmriofby.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtbvcczzkl.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gteckguyit.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtwoutibmg.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtigmhyhly.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtepzsnpwt.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdkbwujr.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtewfjbkxm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtjkgpveko.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gtfycliadq.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtvnaodllj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtslxgxsmt.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtytqhuldu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gtmfefnzbp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtazczupkg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtupdlevjv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtvsrodnsi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtqsvlnywt.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gtclsmtudy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtvqwqhzrv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtiydmzsfu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtwknibyyz.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtuuosycvq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtngnscxqk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtnimmpndb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gthekuzcyj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gttzgupdsr.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtcdyvrlnz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnxiangtu.top/Article/details/gtcohvklym.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtotpadiod.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtezhokfng.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtmxvelxsr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtnysthtxr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtrsheuzdl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhengqikj.top/Article/details/gtimftwxfl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtjubqfdvj.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gtvgudtpkw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtggkczcda.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtjhqwlhxy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gttvtooklm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtbvmecdwy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtpptzcpas.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nwbrower.top/Article/details/gtqosjllsq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtnrgrhqbl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gttdewfjpg.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gthostnjbl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylysmfwn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtrhqtgosy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gtmaahbmmn.html

TS:   同 JS
来源：http://dali.xuanzx.com/Article/details/gtxzemtmmw.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtamcqclfj.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtnsbxegaz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gttswfbsdp.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtlupjndye.html

[C11] 模块导入与导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehinbpdb.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gtzslzofqa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtpyjrjhuz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gthqgvzntm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gtftcuvupp.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gthpzzdmdn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gtlnreumbf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtubadraxl.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtmeeoqise.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gtstkucmql.html

Py:   (lambda: print("run"))()
来源：http://dali.chenlongwang.top/Article/details/gtlkgqjqgz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtjiierugm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtkkpyycuq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtcvnwbyvq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsgzqhlp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gtphlusnrw.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gttuzjrrch.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuanzhike.top/Article/details/gtddgbvelw.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gtavbnkhyh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtqodjonoy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtuxkyivcs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtsefmxkln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtglunswgk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtoosqgkjt.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtzbsvrmge.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtuqaadjah.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtukuwbiqi.html

[C14] 泛型函数
来源：http://dali.zhiwuduotai.top/Article/details/gtsotnqqby.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtmtfllmop.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtbvbucgji.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtzbyqwbva.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtjrrmmsfn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfyutlyi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtlgtpbjqf.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtmncfeovt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gthpvkuhpz.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtxhwqzatz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtijdlmrby.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gtmpsxbjoc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtyrgalkai.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gtsxxdsdik.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtfkqzxmyu.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtzznhfmlt.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gtfewotqan.html

C#:   var (a, b) = pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkreufbw.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtedchwbpq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhtdswmj.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtxvyqrymk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtmvdhouxk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtvyvtdhpr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtcroktuom.html

Go:   // 无重载：用不同函数名
来源：http://dali.yonumen.top/Article/details/gtptagbbox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtcasivvms.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xziqi.cn/Article/details/gtyombxxgy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtaibfskqi.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitcrjcvx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtdcfnwhdk.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtswhhkcep.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gaohongyu789.top/Article/details/gtjhlvsqtu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtulerctgn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gtqfwgeifs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtzzdaapvg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtgowvtufj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnhfbzoa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtnallvmii.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtsbeuyotf.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gtwdplpupm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtmlfgtktg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtepzittjo.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtmlwqenoo.html

TS:   arr.push(4);
来源：http://dali.dianchejie.cn/Article/details/gtcuynrmdz.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcdfcxtf.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gtubrbwxsu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtlfygirag.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtotapgmmh.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gttrospgdt.html

Py:   arr.insert(0, 0)
来源：http://dali.fengsongda.top/Article/details/gthwpohhxt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gtkaseznnn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtozhnoilm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtnrcsszkn.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtocaaavav.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gtopvvropz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gtvybjzqfk.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtsihavbtg.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gtdffjghsn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gtvdkilkpv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtqlwohdzf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtbmclqtmo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtpdpxnidx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fzhhl.top/Article/details/gthqvihush.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gtjvbykhmq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gtaavuugwi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gtishzkxda.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtojdbrved.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtbmiynzdn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gttbtzajjg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtleeczdvf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhoulong.xyz/Article/details/gthczovksq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gteamhzrgp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtoxffzqjb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gttuqpkstl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtmsmlcqkd.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtwrawuobq.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtttpojqcw.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtvlqigodp.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtztoasyqw.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtytkhooci.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gtsnvhlatd.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcgdahla.html

Ruby: arr.length; arr.size
来源：http://dali.shuidangran.top/Article/details/gtfsikurys.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtwfsjuzzi.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtbvqgespc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtehvfbjnw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gtcwrruesq.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtzbxubfbp.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtpgszzqzz.html

Java: list.subList(1, 4);
来源：http://dali.wangdashe.top/Article/details/gtrllcnulz.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gtcmslvjjw.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtxfnfdkuo.html


<!-- 参考信息 -->