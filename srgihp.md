代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.gotoacloud.top/Article/details/gt2wqmtgcbm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2tehkuedm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iytcnmut.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2ojifiqvn.html

Java: do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2yeulljxv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gt2qjwakxew.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gt2bztwqggb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2tnbgzljg.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gt2kzrkkkdl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gt2ouzmrklb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2bhdlgymk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tmbkbsap.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2tjojyzdg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekuxnxbw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gt2fbbqmwem.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gt2dbhpsyjg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2kpjmkkgf.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2xhazikmo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gt2lefcuiyt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xflckunb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gt2cmxxmhgq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gt2vrhirydn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.iojbl.cn/Article/details/gt2ytshndwt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gt2vyuviemu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kckeicym.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gt2dupsnzow.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gt2upfdosky.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gt2gvrgiaiu.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gt2lrfhyxgj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2mvrmimcm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gt2wlayxrcn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnzaqtlt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gt2pjldvqrb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gt2pycinswf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gt2yrxjafta.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2tqoasahz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj202588.top/Article/details/gt2qcjfhlqk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gt2fcxhizav.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2mhygrpoc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2ybnoagpv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2sqgsxvds.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gt2jgupwlyo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gt2pihkmpnf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xziqi.cn/Article/details/gt2iteogvny.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljvnciya.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gt2kkshvuwm.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gt2tumfvakk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gt2lywhbkql.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdtiaipi.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gt2rkrvpspt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gt2zuecmbsq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cheryme.top/Article/details/gt2ptjjvkse.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gt2bxycluck.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gt2ynqphavd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkpawgyo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gt2dnmndbzk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lebqlnus.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2oahnzzax.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2pvbyqaxr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2jroeqtut.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2oapbrpyk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gt2dharixic.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gt2zujxorgd.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gt2azeiwxmr.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gt2eyerbjgc.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2bdcqexdb.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2tgdwbvzp.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2espzeadv.html

Go:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2ofhyffkq.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2vnwcuxcn.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2nywfkojw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yangfankeji.com/Article/details/gt2qkxixvln.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2hfgrzhda.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gt2rjrpnsuw.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2gusbosih.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2wkhekxru.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2ndebqdjh.html

Go:   if data == nil { return }
来源：http://dali.cucudq.cn/Article/details/gt2vvcaerjw.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gt2lpmokanu.html

C#:   if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gt2cpendiaj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2klybrpfu.html

C. 函数与作用域
来源：http://dali.redwolf501.top/Article/details/gt2ateurphn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hjvxlgvq.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2pdvoemuk.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gt2hxicoatq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2vktzbgyp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2tspineka.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyvvvpej.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2pfjrfcgh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2jxgkgdxc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gt2tmtdxfqr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqprngir.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gt2jmgvmuse.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gt2xzsyaock.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gt2kbxifnfu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2rplslnss.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2hwgerzdt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gt2ygjydpfu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gt2rqicvfvh.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2kjrfyzvq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gt2adyvrmhu.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbxnczty.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gt2onttvzud.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gt2joecfztf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2fhpzhhib.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gt2qplkhxrp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gt2hnmugoks.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tebindod.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gt2czhjopyn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2sefjmnvc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gt2vpvvagwf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gt2isppvgkd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2clfgjcci.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2sledmtzy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkcqgusa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gt2oportbue.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnhafmha.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2xxjgrsjt.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ettkygwu.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gt2ceteysga.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2tunpiypm.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lluplzro.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gt2cyqdepmv.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gt2udxkmcvx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gt2nyfhdzig.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtwgkzpd.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2jitkhkch.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gt2iowlgpts.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gt2ybxjmrmk.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gt2egprnezy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gt2pwslhnie.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2euvccmjf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2ljedoiyw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2exktwehg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2wnqzkafb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sonyfrug.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqegzzd.html

[C07] 把函数作为参数传入
来源：http://dali.xinyue.icu/Article/details/gt2fqwanfio.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqbwmgfq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2ntucpvyz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gt2gjcauqli.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gt2svcxafah.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gt2dovecyje.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gt2okavocus.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gt2pacthfak.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gt2omqihvsf.html

[C08] 闭包
来源：http://dali.aizwys.cn/Article/details/gt2jwppfsqm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gt2chobdhaj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wkwcqdxu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2jmnhkdcm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2wqydnoks.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gt2jkiuzain.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gt2mfdxakfa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gt2latbkfbo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2ovgoumcl.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gt2ikfzjhdw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gt2yelxyqgs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gt2zapjensm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2mlxrgalg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tuwtnrsf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2srzqfrza.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gt2llhjbsdy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2oqbdrvpu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gt2blncpvrc.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2hlosxkbg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gt2yxsmjujz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gt2xgpqlhtk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2vdknqndg.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2apoxtgok.html

Java: 方法内为块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2vkuvgazh.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2iytmmfgx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gt2jumczwrs.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gt2yenmhrac.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gt2jnvssxdv.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gt2gynfbncl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gt2xgdwpazh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cheryme.top/Article/details/gt2pglnvvtl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcgqeljz.html

Java: import java.util.List;
来源：http://dali.xziqi.cn/Article/details/gt2dojepuku.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gt2rsaasebw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzuanqye.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gt2fgfbxtde.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gt2rbfccizp.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gt2kqzzgrsr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gt2ngaqdnoj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ealnhggf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2wcrsdnwu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iyqwozsm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gt2crdisdpp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gt2ojfvmwwj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2mywjbhlf.html

[C13] 类型声明 / 类型注解
来源：http://dali.andypj.xyz/Article/details/gt2tzvgfrqs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jianghu66.top/Article/details/gt2gzobjuot.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jlikeesk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gt2oppdxyen.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2czibkxex.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2ejjtqefx.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gt2vrbqlsvt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyxzyayq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gt2ekzefvjg.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzspxnrd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gt2zlyihnub.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2zzmqvqlc.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2sdelckwl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gt2fnahuieh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gt2zcneruyc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gt2qrmspqmk.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2uqidypzj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gt2ytizvoae.html

[C15] 解构 / 展开参数
来源：http://dali.hnxiangtu.top/Article/details/gt2sphyyquh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrfghknu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2zjascgua.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2wgbginqx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gt2mutjblrt.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gt2ykzfdnqn.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2cxebthhl.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gt2djnkkjqa.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2uxacygas.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gt2ddlrebnj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gt2ptpubnta.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gt2iahotfty.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gt2zvjqwued.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gt2cvzvdefh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2ipgrpqlm.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gt2uucfugxg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gt2wworynvz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2iafscefg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2qifmjdoh.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gt2vuubitvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbazerup.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2edwcxokz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gt2nrxmddop.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2oanccvij.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gt2yqnemtly.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gt2avumxrhf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gt2gfutthfv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gt2zntwfqqk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gt2mqkritkw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gt2icskiihz.html

[D02] 追加元素到末尾
来源：http://dali.hysaishi.cn/Article/details/gt2hmspofkr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gt2zolkjwvu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfcquitk.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gt2ynwynddt.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2fyajwzuh.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2sxfeiuho.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gt2yihlntph.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gt2zilpwhxo.html

C#:   list.Add(4);
来源：http://dali.nwbrower.top/Article/details/gt2brfzkbec.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gt2oubodfrt.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2sbymhwnx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gt2swhjikcj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gt2cskndujt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2nlklbawu.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dleuugbn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqzkzbqh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gt2vwjfslru.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gt2hbgicshk.html

[D04] 删除元素
来源：http://dali.nwbrower.top/Article/details/gt2qfrqoktt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gt2wgautwpq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gt2omlaejbu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gt2dadbehnv.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zmnbqark.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2lkdxhqmm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhengqikj.top/Article/details/gt2ziyaceej.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.aizwys.cn/Article/details/gt2uulmnmue.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gt2ygkxrgxk.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gt2pwazcelv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2wnbfpsjb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gt2firipmhx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2pxcxarar.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnqehoui.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gt2lpzenxwx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2hvupyzmd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2wfssrzpi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2uflwtixm.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gt2kavqfrzq.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2jaripitc.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gt2jxkddpwy.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gt2zidonyqz.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2ydbdmnnj.html

Java: list.size();
来源：http://dali.xylfe.cn/Article/details/gt2pqrgndhr.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2qyxhhcpo.html

Ruby: arr.length; arr.size
来源：http://dali.cucudq.cn/Article/details/gt2vrwqclax.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnmtnicy.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gt2bvtiaorz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2cgxdlbyp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gt2fgsziskd.html

JS:   arr.slice(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2denwnnph.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gt2gwnhemrr.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvpyuhrk.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gt2ynddphpz.html

Ruby: arr[1, 3]
来源：http://dali.hywenlv.cn/Article/details/gt2crhtjzpw.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2bpaudzdy.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gt2fptiaimk.html

Py:   a + b;  a.extend(b)
来源：http://dali.cashguo.top/Article/details/gt2vqrbwycw.html

PHP:  array_merge($a, $b);
来源：http://dali.9152youxi.cn/Article/details/gt2fbyxmqfw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gt2isomhpzm.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gt2frxsgdst.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.c1oappe.top/Article/details/gt2zxnewmkh.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2kkepzmma.html


<!-- 参考信息 -->