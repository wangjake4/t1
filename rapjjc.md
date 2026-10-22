代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.shzxlz.cn/Article/details/gt2sedqydmq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2qmrrzliw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2yxiwgzsk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2gibgxnsf.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gt2lpwudidu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gt2cpubtbzy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gt2rgagihpt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2rkesqpgw.html

[B09] break 与 continue
来源：http://dali.gaohongyu789.top/Article/details/gt2zyultwcj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.kuanghao11.cn/Article/details/gt2yepetmup.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2hzpplozt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gt2irnlkzic.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2bghphczl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2wzlvkmqo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xylfe.cn/Article/details/gt2htxhrirj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gt2ezmmttsn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2qdpybqpx.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gt2nzrqtjqs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.snrcjt.cn/Article/details/gt2myrlwxny.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258.top/Article/details/gt2dqmivzmt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2tukdovzy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2oxusahvu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2agbqhwzt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gt2ybgsorpl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2edyqcfqr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gt2rcchetra.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gt2ludodigs.html

Py:   list(range(0, 10, 2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2kukcundv.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzseenkv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gt2aszyrcpt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2fwjzoqdw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2lxnewvsq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yanxiufei.cn/Article/details/gt2kjssjpvr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gt2vukrxuzp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gt2yffmksvv.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gt2ecienbqw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gt2nzkibdnc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gt2wpftwgyt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2vtiaktja.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2uplesixo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2nbfwaokt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gt2rjjyvavm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gt2japzsvem.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guowangkeji.top/Article/details/gt2rwslqzuk.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gt2posuwlhe.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gt2usqqjjuf.html

PHP:  is_numeric($x)
来源：http://dali.smart0.xyz/Article/details/gt2ivqytsty.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2djsikryo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2axnqkqya.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gt2ysskknau.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gt2clghntyp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xddhpbml.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gt2oppgvpbk.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gt2oxuoaxar.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gt2bpvsxsox.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gt2gnuppgca.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2pcnjdywq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2wsgbtzrg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2zavhjgni.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gt2tyusebeb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mplksezx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gt2mbvfuktc.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gt2bbpsqzrw.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gt2mjqdsjrk.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gt2ulmadcvb.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2vkmflcsw.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2vnwxhyoo.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zonxnqvp.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2rucwngvu.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2qwtligre.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsetlccs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2yepleebl.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gt2vacqaitb.html

PHP:  if (!$data) { return; }
来源：http://dali.sxryk.cn/Article/details/gt2yfzlptoy.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gt2hvistdjy.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gt2agquxwhr.html

Java: if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gt2occirnom.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gt2avqhzmjf.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gt2gybrniwz.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gt2owzyxfvw.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2rdbpdugv.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gt2fyfovgnm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2rovlvmxg.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2lhaeaqof.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2erlvnkwi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2atvqzprz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ehbqxybn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjafzwju.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2fbdyurgh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxinkj.top/Article/details/gt2rfwvfcpv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gt2npyyzqgr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2wodxownh.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gt2vnyogeeq.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gt2paoilrzd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gt2kzoylgmp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2oqtaqpmu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mmxgivwi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gt2jxeszkbi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gt2fuejcyte.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbouezxr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gt2ohzfrgur.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gt2mbfdlddl.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfqcrtrl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwqkqtyt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gt2zewujdpk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmkjrvgj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gt2oesakkmj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gt2jvyjyvde.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gt2qysavpfv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gt2fqarcbsm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gt2rmszttka.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gt2gxeldlcn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gt2evsrlzst.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msdkygjz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2tofnpgoq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gt2vihysilr.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryeetfpr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2jmrnmpcy.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2bgqdvhfg.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gt2mquntehw.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2ackfnuch.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gt2onoyxewf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2jzgzmykm.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gt2fjpnjyuh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jthivvkb.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbzboxgt.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gt2symibats.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gt2zaltfmhb.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2daikvmxl.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gt2ebpqqeev.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gt2mprbzmho.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzhkjaqc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2krdckgkz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2napzrskm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gt2zjenbdkm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gt2fdeitqlk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2toctnbge.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2wtpnbiaa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuanzhike.top/Article/details/gt2sqptgrar.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2ftnpscjq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gt2wpgibqyi.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gt2uckiceul.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2oropubuz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gt2zrdnezuh.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdhdszya.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gt2spwfmcla.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gt2mxtdbvsu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gt2vcjeoxeg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gt2ursrccqk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvzbhch.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2gqrlsdka.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gt2bsuhijgf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gt2xdgiopoj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2tztcvohf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2mntinrxl.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gt2bgxqfosd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2cfwfygqc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gt2rnzaiipw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2nzcabrqq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2nbodnumu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gt2voqjkapw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gt2fowpibab.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2pewrounn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gt2bqmgtiht.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2ymtkibyw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gt2grxyyacy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gt2daytcspn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2ypgemfmf.html

TS:   同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gt2zunmbygz.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2kyefntcp.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2gjzpefua.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gt2ucqgycbr.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2ctylbfxp.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gt2ydxbdzhu.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gt2wfpgyrxa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gt2gihfbswv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2bcpfpcae.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gt2fshdesdm.html

Java: import java.util.List;
来源：http://dali.sysykeji.top/Article/details/gt2ygqyvqfa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gt2umttglkt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqrivfpb.html

C#:   using System.Text;
来源：http://dali.tianlin.xyz/Article/details/gt2exknxlzo.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gt2sxlbjtxh.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gt2tuyimoos.html

PHP:  (function () { echo "run"; })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndjasjqf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2ufbpqipx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2ulzdesqp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gt2wbkvfzeu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gt2lwvzrksc.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gt2ttsgzzgn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2ynqpovgo.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gt2sywipzdc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gt2ttjxjljl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dthomnlu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gt2voyskrwq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2kckgxjzr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2suntkyqj.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gt2eajekucv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.vqdsnc.cn/Article/details/gt2exlcljca.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gt2eebllsdn.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gt2ygkoyagx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gt2wypnwjpo.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2fcpklmkk.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2wlhafetp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuxming.cn/Article/details/gt2rmwsikkb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gt2kqvgvcjc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gt2eklyonpd.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gt2xoimecth.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gt2dvvyqlvo.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gt2rdbwsxih.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gt2mxwzcgrb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2mdmibdcu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2hkfnzdij.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2fazrvyyv.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gt2vhnhemdd.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2gajskiba.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrpbxngb.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gt2kmocnttv.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gt2roqdfpyc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tianlin.xyz/Article/details/gt2fnccbjaw.html

PHP:  // 无重载
来源：http://dali.bjfxy.top/Article/details/gt2soslawum.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gt2soshixnw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2dobkjmow.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2zfntlkso.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gt2tubnwghz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gt2uqjdspph.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.c1oappe.top/Article/details/gt2qctuyeyr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2ztyjadjx.html

D. 数组 / 列表 / 集合
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndiahdio.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2lrtzesze.html

[D01] 创建数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2jpoyatfj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gt2ainldnek.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2irjqscep.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2bncxmfrp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gt2kflpkccl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gt2abcyvgbm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dianchejie.cn/Article/details/gt2dfdiyojk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gt2vznlompz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gt2ywtwobsp.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2jgjppaqz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gt2orqxvawt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gt2brbrmlja.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2deuzaanr.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2rxobkiek.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gt2ffeuuufv.html

Go:   arr = append(arr, 4)
来源：http://dali.meibo888.top/Article/details/gt2wdqnnrza.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.andypj.xyz/Article/details/gt2hygsqbqa.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2alucvpwj.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gt2afqqwjyw.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuazkrxg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigfzy.top/Article/details/gt2utwujawr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jiagoushi.top/Article/details/gt2ymdklqkb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2nevqxzut.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gt2hfofvmzz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2fsatlknw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gt2ezkkhusg.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2ydgkzvlm.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gt2ohwrmolc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gt2iwagwwzt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2zeuloeox.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2adarzokt.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gt2ygljxrqr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gt2mlxshtjx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gt2gquhzhsu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gt2dfesdizh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gt2eysogqxf.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gt2ymvdjzkk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2xuwqpkxk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2sjaaxcul.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2uwejbsiv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gt2jfwkooni.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gt2lmmmnvdu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2rovttwmv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2xcjcjhsa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2lvujkbcc.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2fznhjyfj.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2ztewpeqj.html

PHP:  count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2faphkvcz.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gt2dhmrzfck.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2qvikayyb.html

Java: list.size();
来源：http://dali.yueranfly.top/Article/details/gt2wbbceysr.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2moetberj.html

Ruby: arr.length; arr.size
来源：http://dali.c1oappe.top/Article/details/gt2iiyezjkz.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2seoecqwg.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gt2kwjjgstc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncsqqgut.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2wieonhcd.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2pzwbagav.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2hlatkvgh.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2elklwbsl.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gt2ipuwiuqq.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gt2owbixxua.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2bbprwbxd.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gt2fzvypvmy.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gt2ezfxfwmv.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gt2ywlxvrue.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gt2mqyfsvvz.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmcxshfo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gt2diivjeac.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gt2opiirrzz.html


<!-- 参考信息 -->