代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gt2nuaicgih.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvilrivq.html

[B07] while 循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2wodteqvl.html

Py:   while i < 10: i += 1
来源：http://dali.zhixingplan.top/Article/details/gt2flsqcyod.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2qlafyall.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2drysanda.html

TS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2emkiainn.html

Java: while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2fwomegih.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gt2ywqbtgbj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.haohaochexian.top/Article/details/gt2oehjiqbw.html

C#:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2qqdsbyzg.html

[B08] do-while（至少执行一次）
来源：http://dali.dianchejie.cn/Article/details/gt2dvyjcety.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dashuyun.cn/Article/details/gt2iqigxjnk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2mnxhqjks.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2rutzpvsv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2makghbfm.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2wjakercm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gt2fgcpadeg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gt2xrypdnpz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2njnxjsbl.html

[B09] break 与 continue
来源：http://dali.xinyue.icu/Article/details/gt2cvdizqfk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yonumen.top/Article/details/gt2gpgwgntf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2seycrcul.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gt2hlaibxuk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2xrdzwcbz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2laslwybt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cdnleiting.top/Article/details/gt2dkezbtob.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jyoumei.cn/Article/details/gt2ccmetcxp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnnzufgr.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gt2rbnfkbnu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gt2hlpfnfvy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gt2qfbssjhk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2rvdypqho.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gt2tlxxjpev.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gt2hvzzvscl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gt2tarspyxt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gt2jwysoddh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gt2dymwtwef.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gt2emcswfew.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bswpgnfx.html

PHP:  range(0, 10, 2);
来源：http://dali.yonumen.top/Article/details/gt2zfhvklpl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gt2jgazeqwm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gt2mfqqrysc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gt2nhplzpkn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gt2crcheepd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxinkj.top/Article/details/gt2wljnuiis.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyquvuan.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gt2hegvkzom.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.haohaochexian.top/Article/details/gt2nsinbceh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nwbrower.top/Article/details/gt2hgsnlded.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2seditcmt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2chthaqxi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2okbgtwmm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2envafaun.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.mhx1999.top/Article/details/gt2mnyfrceu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ppjwa.cn/Article/details/gt2hymgvipx.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gt2bdgwzwix.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gt2lowzjhat.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ditbakfp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gt2dihjdath.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cokualbk.html

Java: x instanceof Number
来源：http://dali.aibaodan.cn/Article/details/gt2doatmpzn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gt2bjmlooxb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aeuwpjgb.html

C#:   x is int or double or decimal
来源：http://dali.pycfn.com/Article/details/gt2ralslxny.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gt2zbhuvqik.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gt2iwakewyl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gt2siazazbe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2ozrzxjar.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxdukxfo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2dguzgjiy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sweek.top/Article/details/gt2dwxvhjih.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2uehucvxo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2ywjjevlj.html

[B15] 布尔运算与取反
来源：http://dali.sufxvd.cn/Article/details/gt2eajyxjho.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gt2qcsgynec.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gt2zqgyqrwb.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2wsolavue.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxaxuymp.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2nfbnkgyx.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2qyzsiydm.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2esjmsouo.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2umwcczdd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gt2ddbzzwmz.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gt2mrsxnnuz.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gt2fbgtwomz.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gt2chzovmrj.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2ywvxwsou.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2htpxidre.html

Go:   if data == nil { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xiypcssq.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gt2cgrqgdjg.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gt2xukvzdux.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2pwmallqv.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gt2qtdgquvo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdwkctoj.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gt2ykxypkvx.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gt2sihnkoie.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2obeofhhy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rnuramqk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2yimqcvey.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2quixwiqk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gt2tkraghrk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gt2hxbmfjbr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2wsginwlj.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvldplrc.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gt2xbdxqscb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gt2dznsbrvc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qihaztor.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2tozychpq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gt2vmwdcazp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gt2jhblzbxd.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gt2lwrrkiqs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2misidtql.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gt2xudtoqna.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gt2pkszfgum.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2ngyznluy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhyregct.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gt2mczowkab.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iripftmd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gt2glqhcmcf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gt2wfxorbyn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyircpqh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gt2tyhigart.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gt2oakdapcp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gt2masfvjgu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2adovysqm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2qychqgic.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gt2envpjvau.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gt2rfnewfuj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2lkzqaurt.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gt2vkcfqqad.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gt2wtgbkhaf.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oemcixqm.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gt2kifjeavv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2pqomohfi.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2urxxfnzl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gt2fphxfaqw.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2ybfalgoo.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2yivspcjh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gt2rhuqvdfe.html

[C06] 匿名函数 / lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2silzdkkh.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gt2zncmncqy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gt2fecnyzgs.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2yrgfxrxq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2uxdoqxci.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2klxengdt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.quarkkingdee.top/Article/details/gt2wlybcabl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zdqjudy.top/Article/details/gt2rjopglwb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2bemjbosy.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gt2bieqyosb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktxxqhgb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2lykdnzjp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daria6918.cn/Article/details/gt2mbmnqfau.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gt2elgepsbj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2jmijnicg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gt2queuaipq.html

Ruby: arr.map(&:upcase)
来源：http://dali.kuanghao11.cn/Article/details/gt2tasgglpt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gt2pybtnory.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gt2sbpionlm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gt2ahedziyi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ppjwa.cn/Article/details/gt2fxlkrbzi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbvhunhf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2pcljpohv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gt2yvfiddtt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gt2vfdazuci.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gt2bdwxmkyh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2becnvxhc.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oakbmvxm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2quijcqjw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gt2tncthudw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2pujvmhqt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jndibnoj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gt2rcuioshs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gt2qkszpldx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gt2btiacinp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2uhyzapix.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gt2lmxjmuzn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gt2ianltgvv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gt2ekaytnhj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gt2mnfnkrqq.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxmdlqsw.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2sgwujhui.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnubiike.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gt2keataibu.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2kyeszsgf.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gt2kajtlfpp.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gt2cygibera.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gt2twqjkooc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gt2nvrdrads.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gt2lntyshth.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gt2rlugaskf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gt2mdbyfocy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gt2caaixncy.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2zigwccgx.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gt2jammmtzr.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gt2vttpmzjy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gt2nmellbif.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2zxfsdmbe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2aborlzro.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gt2yhonlrbs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gt2vjcjypfk.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gt2gggkwkdo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gt2xcygszts.html

[C13] 类型声明 / 类型注解
来源：http://dali.yanxiufei.cn/Article/details/gt2sywwfopq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gt2qmippzli.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgthiybh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.meibo888.top/Article/details/gt2lmjjwngd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2mogmpxxx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kwycekyr.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htijieqx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gt2arpfitst.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gt2smjojudd.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gt2dqrwbycd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gt2nkrcpwnd.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gt2dtyklhjv.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2lulznhsh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gt2xevwoxgx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gt2hmmhbyxs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gt2vziavmuk.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2zulatzvm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gt2qyaqwbmd.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gt2wzxozuda.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnqzz.top/Article/details/gt2ezzqbtca.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gt2brtuwzku.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ixxbolvs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2demqjnmc.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzmcnxqk.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gt2eyiezawk.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gt2unhpavco.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2nfkrvtlv.html

[C16] 函数 / 方法重载
来源：http://dali.mhx1999.top/Article/details/gt2fvpnxura.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2vpxwpcxw.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gt2tcmllcux.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzcisecs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gt2rvcezeyw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xtmzpdtt.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwdakuhu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2dboapusp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gt2gqgcndph.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2qzzrdgqa.html

D. 数组 / 列表 / 集合
来源：http://dali.hysaishi.cn/Article/details/gt2wanqzmby.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2wkggqxcb.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2rozinpgv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2lspvepvu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2cuitvvje.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2ssmrnapd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ppjwa.cn/Article/details/gt2dfmkqtzs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gt2jiimjaqc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggqfawlr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gt2twmyxwrg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gt2xmpelhny.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gt2boyhxlza.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gt2lohabmsv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gt2ryiryxfv.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gt2kenkxwcq.html

TS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gt2ebededzs.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gt2iucxhuiu.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2bciqjszg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gt2jlggiwsq.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gt2tmxtpwjr.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jphxgcqp.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jifhlikb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2ssrcetnu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gt2guqziaqs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2veioswmz.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebmylizl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2qfseqwzx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nanxinkj.top/Article/details/gt2daeddkgk.html

C#:   list.Insert(0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2kvkgaxiq.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gt2qynzkghh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2opmiichx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gt2rlmzziwb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2muciasrw.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gt2yxdzuuna.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2gmilvvuc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gt2gxthbyqb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2zkjhwxso.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gt2ueztosri.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gt2pjfxcwzr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2chqmntjl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2mqqnvejy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2xtcgqzhu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2llfkmyjr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gt2xzuphnhc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gt2bccltdao.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2lftjdvdg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2keynpnsn.html

[D06] 数组长度
来源：http://dali.hnqzz.top/Article/details/gt2fgzbeiew.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2hxanrifk.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gt2hlcdmcrg.html

JS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gt2xhluexkw.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gt2qnfmfunz.html

Java: list.size();
来源：http://dali.vqdsnc.cn/Article/details/gt2pgmyhnpm.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2skvcaqmd.html

Ruby: arr.length; arr.size
来源：http://dali.zhongyouzk.top/Article/details/gt2azpzaffl.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gt2lsrrvydo.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gt2oeriiiso.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gogol.net.cn/Article/details/gt2ofgnvbne.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2xksvbitf.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nidykzwt.html


<!-- 参考信息 -->