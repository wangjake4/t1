代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gt2lqzqsfeq.html

JS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2iotxpwhh.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2rqgfrgud.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gt2tlkrchvf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gt2kwescscd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gt2pwzjjxlp.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2bwrcummi.html

[B08] do-while（至少执行一次）
来源：http://dali.gzhubu.top/Article/details/gt2wlmojgvw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gt2zzpystrt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2nfzguliq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2jtbpisuv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2xrhlpmsa.html

Java: do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2edkgnjtr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gt2nvqqlxus.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hysaishi.cn/Article/details/gt2llmgcvly.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2syuoohnf.html

[B09] break 与 continue
来源：http://dali.zhengqikj.top/Article/details/gt2yrnxrqdd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gt2znlucrwq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2oaohoqys.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2motanghu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2sklzfjwy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pkavdbue.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gt2drluwhix.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gt2vyrdtbxe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2tktikmrn.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gt2wmhhiqpn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shzxlz.cn/Article/details/gt2ieouugxe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vpjdvkyw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gt2snapezli.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2nxlzompi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangdashe.top/Article/details/gt2njskojnj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gt2arjkvshz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gt2esbdnsmq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gt2fzjvyfri.html

[B11] 生成数字序列 / 区间
来源：http://dali.cashguo.top/Article/details/gt2enyqelbq.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gt2adcoocze.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uevtwhll.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rihogxtt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gt2mzaznpdx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gt2rnhzymwj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yanxiufei.cn/Article/details/gt2akxggcov.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gt2chqgoftj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gt2rlkfhtah.html

[B12] 跳出多层循环
来源：http://dali.316326.xyz/Article/details/gt2fzapihjd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gt2jtvcjqvh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gt2buisjpey.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2ydmkoweg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnwjnrlq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2dedrnalg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gt2wkeezrme.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gt2gyykntjc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gt2hlvhotjv.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcogjre.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytjthxlu.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gt2fjsnyrdv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mclxvvzl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gt2vksstbmk.html

Java: x instanceof Number
来源：http://dali.chenzaomai.com/Article/details/gt2rgnyvwmi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gt2ksmunxgc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gt2bvfxvkxi.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2iqqlhqta.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gt2kxxvwmma.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gt2ukmyqroa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gt2sufarixc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2rtyyfgmr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2raxsjsau.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2lxvfykkp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2bhgknrqf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2idzgntsf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2dcinlidx.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gt2mjrtmzrb.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gt2zdkwszid.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gt2bnhtmgfu.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2gdgkduyi.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2rhuubnoo.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2cjojdbhm.html

Go:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2dvdxoyqz.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2zrpgaoer.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2vwhxkbig.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gt2ntztagaa.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gt2wmagqazl.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gt2xqmcjpjc.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gt2ilouzizp.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2umxbtmaj.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2vvyyjdbr.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gt2nznwrgnn.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gt2ksewxpku.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2yobvvxxs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wqfmpmjj.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2gaozxucf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2lpnlakgu.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2mrgqmqil.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2ygnhxdsg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gt2rnpdscgt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2frigiwye.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gabsfeyu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2snegxjqw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gt2nvvrxvxh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gt2smdrhaje.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fcbdkejt.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gt2qlyybjsd.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2tnilrnke.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gt2rqgdftwk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sykonbgt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdbxltqa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gt2gmsiwzph.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gt2mjluiltb.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gt2kcrbjjwy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gt2lmynbhnv.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gt2engbdief.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gt2wgabimwl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gt2yosqauda.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fczwhzwd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2iuelhnfi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gt2atlzwfos.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gt2juflhsqd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gt2ppgrjxvk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gt2ebfoljmj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ybwebqjv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gt2eevhdcmv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sysykeji.top/Article/details/gt2ynwvxslo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2ztptdtsw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2vyrzpqmw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gt2tvenjkgx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gt2kjnnkaib.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nbjuxvay.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2orvoigrg.html

[C05] 返回多个值
来源：http://dali.hywenlv.cn/Article/details/gt2hlsfqdtw.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gt2ifmocdds.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gt2kguvzhlt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2mljvudqn.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2pjzxskbt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gt2vdlbszxu.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2zzxpaikv.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gt2zgevsuex.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gt2dnflpevy.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gt2bjpxaysa.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gt2spretzla.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gt2snnqfuct.html

JS:   const square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2dexhrrbo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2zrvwfjec.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2selzyqck.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gt2aktbrrdw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkkskjv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2thoxrnnb.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gt2czzkpjwc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gt2gwifhlhw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gt2cbppvyej.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gt2bgfcigpb.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gt2irwcimaw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gt2hxzulohc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gt2whvtmgik.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mefxzzkl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gt2lsjeuhoe.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gt2wuldzavc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gt2gvddzzul.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gt2lqfftmrb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2djxqmmjs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2bnqlicwy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jiagoushi.top/Article/details/gt2vnnkdhxc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntmdmxap.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gt2ntdsfdqy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2qkkqovmp.html

[C09] 递归
来源：http://dali.sysykeji.top/Article/details/gt2yjjrivli.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gt2juvklvmz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2pcnpkcvx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gt2eclkqwag.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gt2defapoii.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gt2vfvdlhgw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gt2qirvslqi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dknupqaj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gt2hpbbhlhn.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gt2gffkcxvx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gt2jzxfrfjm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gt2ngnypsoq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2ozzovctl.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2trlaimrs.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2uqjfiopa.html

Go:   花括号块级作用域
来源：http://dali.0kj1m.cn/Article/details/gt2wmbpgiml.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gt2xmeryyke.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gt2bgkfurqo.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gt2xcgampcz.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gt2tebsqpbc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gt2asrkkotv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gt2bnndvjcj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gt2yrafngvx.html

Java: import java.util.List;
来源：http://dali.xuanzx.com/Article/details/gt2xikyksvw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gt2mwaonrhn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hongshengwenyu.top/Article/details/gt2hntbycmo.html

C#:   using System.Text;
来源：http://dali.snrcjt.cn/Article/details/gt2zsqylxjy.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gt2sfseowly.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xidgjerf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gt2waoxsjyw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gt2snjzvcwn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2aqpydytp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gt2ejsqdwjv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gt2kodwqetk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gt2fvnhctfu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2qhjfpqvo.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gt2wmurzycs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2basjrlwe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2lnclqvzt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gt2yrejgyxk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2jgydngcw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2cjovnymk.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gt2ohusugdw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gt2jogizxno.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guowangkeji.top/Article/details/gt2fuvesekd.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gt2feoiovgp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gt2eytrdryo.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2mzhdhjya.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2dfznlheh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdigelnz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gt2fjdzajot.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gt2izrxzmzx.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpqbnlgf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfcfbgka.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gt2ntumffau.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjmszkou.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gt2mfntvjqb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2jvtrpzpc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gt2spkqxqrp.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2obshnsjo.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2wbtvwlxw.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izpixtxd.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gt2xjudbvos.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gt2xnzhlpya.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gt2dwhtpabu.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gt2riftkekp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfmfhrn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gt2towtdfwv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2kykkrsoq.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gt2dyuitjhe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gt2osavoleo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2vmwqkxte.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ufphdtvz.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gt2nwyuectm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2npvebuab.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2ufozyuiq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gt2bykmgweq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gt2axnykhkk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2ifpvwvgv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gt2vwndumnp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2xheozpcp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gt2tfraykeb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gt2oavwbfyz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gt2cbasfsoi.html

[D02] 追加元素到末尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahpazdjm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2syfzjaki.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gt2xesjrrfg.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2ntyccwmg.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2ryqavcyx.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gt2vtkscdns.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbqouqrb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gt2bdirotud.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gt2ckocrcnl.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gt2jctuxajl.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gt2swlxgmyj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gt2bopesjvf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gt2jofpkfbq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2eoyixngp.html

Java: list.add(0, 0);
来源：http://dali.sysykeji.top/Article/details/gt2uehnhlyb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umsewefy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gt2iryvlhzt.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2jeqhvhyb.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfxkhzbb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ongkvvwg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fogjwbvv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jlsjyb.cn/Article/details/gt2cyuenbob.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gt2hwlsarsy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2hnakucul.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gt2gsgiuzde.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.smart0.xyz/Article/details/gt2iyjixfvs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gt2gvlgkjks.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gt2uxhnetel.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plxmyzpd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2gulltibx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2anydfwqf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gt2omvafwly.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltbpklet.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2xcwecqrq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlacrwig.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrieroiy.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2ubproopa.html

Py:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktvtzcqn.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gt2pkxaukzd.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gt2gvncalat.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2vwnjzolf.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gt2sknmllts.html

Go:   len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2fpmzmkal.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gt2ssabxjps.html

C#:   list.Count;
来源：http://dali.feifeiyinyue.top/Article/details/gt2upzcawlb.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gt2vgodlurg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.vqdsnc.cn/Article/details/gt2gehialtr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2azfzfjlx.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2wipnlazl.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2bhteubkk.html

Java: list.subList(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gt2nlzyawwc.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gt2xdbtcezn.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2odaakhwl.html


<!-- 参考信息 -->