代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.c1oappe.top/Article/details/gt2mxvwvwjq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gt2mjboqeip.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2hqbapmog.html

[B08] do-while（至少执行一次）
来源：http://dali.zhengqikj.top/Article/details/gt2rtvkvnri.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gt2mwvvbktk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2vzphjswy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2nkstqdee.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2apmpdjqz.html

Java: do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2trrrmuai.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2zhupddjx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gt2mphqxydi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2jaxghbcd.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gt2puogtkfd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gt2mtfzwecc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2xbaurfrp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2qdqhwpnp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2qtdbdrsi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcumaozz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlrcxpak.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuanzhike.top/Article/details/gt2qprfkpig.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2debjpuru.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gt2jyxbtchl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigufen.top/Article/details/gt2xmfhljdg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.mhx1999.top/Article/details/gt2vvdwagrh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2ahbmicjf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gt2mkxxehbj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gt2xlatkusk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gt2cvizvfww.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gt2hnhtmhlb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gt2ltkcpmuk.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gt2mvykiyhr.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gt2iuvmchwf.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrgpjkiy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gt2fjrbbhgp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gt2umxnxucc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gt2ruzybfvd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gt2ajjjoics.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2mplpgspb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gt2kutvhipq.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gt2ebcxwzwc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gt2jaizydqe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxinkj.top/Article/details/gt2twzrccef.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2pakhhcps.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mhjthxjo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2jquzbbmh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qlxtzzba.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gt2kiqylect.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gt2pqsokzep.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gt2zqrfclfj.html

Py:   isinstance(x, (int, float))
来源：http://dali.gzhubu.top/Article/details/gt2xobftxej.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgwdlxvy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gt2yfycmqxv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2yuedoklb.html

Java: x instanceof Number
来源：http://dali.havefunace.top/Article/details/gt2vjfunurt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfjurjwm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gt2wrbauper.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gt2mzutzjju.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gt2scwjkiiz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zylbqirn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gt2crbqepxf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2ilspmjsl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2zozfslmr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gt2aqnisgty.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqjeypce.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wswkzyjv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2htxxsuyr.html

[B15] 布尔运算与取反
来源：http://dali.zhoulong.xyz/Article/details/gt2uuecydex.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gt2gwiltetf.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2loennbmc.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2cbchrqdt.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2ctzuxvuh.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2enywtkjc.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2jqpvdprc.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2qozfwxyp.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2ckyhrpic.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dashuyun.cn/Article/details/gt2vfgjidod.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gt2mceaoqyw.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gt2nvnqogrb.html

JS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gt2wdghdues.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gt2didcikym.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvxdrsdi.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gt2voltnbjm.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gt2nifyxjqs.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gt2hizeaybb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2azmseghw.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gt2clpvrlij.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2wibbdwlc.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2ekyneboz.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gt2pdehlqlo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gt2zhtlfkym.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2tsnrlkvq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2fmqfwsdv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2drdbgfwl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gt2kxcustcf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gt2xbafwmox.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gtqpmyft.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2dijyaspr.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gt2cjpxgqdw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzwbqioy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ofldrphb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2odybxfql.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gt2nbksspmn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbezgcxf.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tbwkegku.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gt2vfaujafd.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gt2bglevbtc.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gt2shhyptrw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gt2tulbcrfx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xymmkkub.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gt2gdnitlrx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gt2wurywfra.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gt2iethudyg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gt2smzqhwxw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gt2veyoslvb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2decbrvaw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qebhmzvw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2irjstfrh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlwwdgbm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gt2wrdaautb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gt2xyhusfso.html

Go:   // 无：用配置结构体参数
来源：http://dali.jyoumei.cn/Article/details/gt2gcjkjfoz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2jcfjubau.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gt2exsfwupe.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gt2exjfmnlz.html

Py:   return a, b
来源：http://dali.daria6918.cn/Article/details/gt2qfzedtyr.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gt2sywddnlc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2eyyolzcm.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2oqzcwsoi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gt2xnnznybn.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2jqyiemqz.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gt2rnbnfxyz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gt2ewscnmvj.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gt2iesmnnzp.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gt2rzvucton.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gt2ekwiljgz.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2ejxigvjh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2lvtnftbf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2sfqoayak.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydjybtva.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gt2chrmwufs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gt2lcjnevkg.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gt2ushtbhab.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gt2ddwprkih.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2ccbbcjvw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gt2acpemeyz.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gt2zdfgjzqa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2imeugchy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gt2girwiupl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2sqjfhnmg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gt2wdzxyxqk.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gt2mdlhyaww.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwzjxnil.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gt2melfsils.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2ullyjcmp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2pshtagvy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gt2xdfiwolr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydtdrnww.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eaijpmnm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2fygqddmc.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gt2ykascvek.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2tgqlkqyp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gt2nxyqpfuw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gt2nbtqvnvl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gt2ymlqssek.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gt2qdulbahu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gt2cesywppr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjxihks.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxvrxahu.html

[C10] 变量作用域
来源：http://dali.tanke756.top/Article/details/gt2smbjubqt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gt2ypmqxvut.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gt2rwwrkyay.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2mexxecvm.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gt2kjxpovbl.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmuxmeoo.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gt2rlxyebwl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gt2sgbziwus.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2onfkirva.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qasjzads.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gt2rsptangq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aizwys.cn/Article/details/gt2jhkljvnr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2qnjejbzn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hysaishi.cn/Article/details/gt2xvmbhmca.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gt2kjtvedas.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sswnkdnz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gt2fnapcyey.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gt2fjtjjemf.html

[C12] 立即执行函数 IIFE
来源：http://dali.sufxvd.cn/Article/details/gt2zwgskcfw.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gt2vrpdqyjc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gt2plxhjysn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2huockrmp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmughev.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gt2pxdyxdtc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gt2yiocrcsr.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gt2zroukvxn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gt2gtxmyojq.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gt2aiygxipn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gt2jdjytwqc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ietrmntx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gt2fxystkqq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2uypfgdas.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2glukfahd.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gt2vagmqoms.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gt2jndvpzrh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgppsqic.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gt2bokavwne.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gt2qurhjcpu.html

PHP:  // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2kfhsybwi.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gt2jgcmnnwu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gt2klsjsual.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2zpowwtpy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpeyuits.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2smlshzqc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gt2fkgwrefw.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gt2ricxuuco.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gt2ufhnbsvn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iunkdpqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gt2bzivrdbj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gt2cwmijngy.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gt2kzqoadqh.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2tzhuweml.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gt2nbwfewqm.html

C#:   var (a, b) = pair;
来源：http://dali.cdnleiting.top/Article/details/gt2qfqqzzxy.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlwuswwm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gt2gtqmvcin.html

PHP:  // 无重载
来源：http://dali.aibaodan.cn/Article/details/gt2ajedfxaq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gt2kduakbzc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cqqwz.cn/Article/details/gt2evyhblmg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gt2vzdlrjvz.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gt2ogknjyez.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acopetsx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bqagbfsa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2aqnaeunm.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gt2vmnbdubs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2homgyzhw.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkeusvdp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gt2bymvrexa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2tybawjdt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gt2tfjhence.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daxiang520.top/Article/details/gt2pluvihmo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckaxoghv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gt2vfwfqurb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gt2ieycgbap.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gt2pgptmvrm.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gt2gxydjvfx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gt2uwugaggs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2mazqfdks.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2lhekhncm.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gt2ezxmdbon.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gt2uspolcdc.html

Go:   arr = append(arr, 4)
来源：http://dali.ivvv.top/Article/details/gt2xrhivygn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2twrwyhue.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfyaatsv.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gt2qmsjflmr.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gt2ylcfrqyk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqwlngng.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gt2qihxnqzp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2noeoikgu.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2guhmmxsm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gt2lmnzkooa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.snrcjt.cn/Article/details/gt2uucpypgx.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2jjagxnpg.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2kepiuwtt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2orspsbhu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gt2ojseqoqj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gt2cinykeaz.html

TS:   arr.splice(0, 1);
来源：http://dali.yueranfly.top/Article/details/gt2gcldyutt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2hwtfoghz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gt2vutvephy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rooweebg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gt2rpsswihr.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2wutfchgo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2jlnhgygs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2zlfgtznf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gt2msgxzjzi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gt2csimjxmc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gt2qkexnfbj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2pznpjiwv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2lxbspnpw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2blnzlhwf.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2uvldlvpw.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2opmlamzz.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2qhpqvsdx.html

JS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gt2kchoebru.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gt2nixsvvbz.html

Java: list.size();
来源：http://dali.sufxvd.cn/Article/details/gt2rdniycjl.html

Go:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2nijpscwv.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgjawpwd.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gt2lxzauaim.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gt2ztknjcof.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gt2oasbrmcw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.9152youxi.cn/Article/details/gt2gjtgtewg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujqhnfax.html

TS:   arr.slice(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2cekekcat.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdwjddpu.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gt2tuubotsx.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gt2bsuufymr.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gt2xiclcpup.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gt2ranvcclr.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbbfjmgr.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gt2gfaoqzce.html


<!-- 参考信息 -->