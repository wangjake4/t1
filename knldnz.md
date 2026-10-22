代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfkqzmqa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gt2axelzegj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gt2ysxinjfy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lswagikd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gt2gnlsczxb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnqzz.top/Article/details/gt2esptdbxj.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gt2neelfqak.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gt2tsyoezjl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gt2itshwxxl.html

JS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gt2orrhgnjn.html

TS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2jnbqrokq.html

Java: while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2hokhlwsg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gt2iggnokzf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.mhx1999.top/Article/details/gt2xupqcqbs.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2uicvpkoe.html

[B08] do-while（至少执行一次）
来源：http://dali.andypj.xyz/Article/details/gt2nrslwebu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojopntvp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2xzbayxip.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eppraylf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2oiuyngqd.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gt2floceowr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hfpthk.cn/Article/details/gt2kdghnpqr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuxming.cn/Article/details/gt2kvqpkaov.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wocfiass.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gt2outibhua.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gt2ttxyewex.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2newdjtia.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzerlxob.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2xqoqhbbb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2bdhxwmsu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gt2algzmxnb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gt2hmwxvmys.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxrofiyw.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlwhwbic.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gt2mzadharc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gt2lmngnokn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gt2ttvotcnl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2ykprzamc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hywenlv.cn/Article/details/gt2uwknqjfy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gt2ifwvxmty.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aibaodan.cn/Article/details/gt2nwnnrbeh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cdnleiting.top/Article/details/gt2rwexykub.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigufen.top/Article/details/gt2uhmtyenc.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogbhqrsg.html

PHP:  range(0, 10, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujksvdox.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gt2plmrbwxx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gt2vndrwjve.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2uaseuoox.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gt2xhlpcgmf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gt2qwksdxht.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2owntwimf.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gt2kqfblgio.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.9152youxi.cn/Article/details/gt2ldkaqfri.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gt2jdeydbvf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2snxwqpdb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2rwkffege.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhjxtmqz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gt2ufifcavz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gt2ijvzizgl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gt2oxpojeur.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gt2guucfjae.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gt2zccozeyo.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gt2nrvxqrcn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gt2flqkndxo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gt2xajluubi.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gt2dsucqnwi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gt2ozafexxp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gt2yiheckeh.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gt2kfcrpsgn.html

[B14] 判断值是否在集合内
来源：http://dali.hfpthk.cn/Article/details/gt2pszwtaes.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gt2ersrbqwi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gt2pdazhyjt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2fjncezvs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2xrxhnqrr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2ndiinrzd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gt2fhbpaquu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gt2sfxssrun.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynisarbb.html

[B15] 布尔运算与取反
来源：http://dali.fzhhl.top/Article/details/gt2dzdremhx.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gt2bytmmetg.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gt2stbwivmf.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2ekmnqetp.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2wokpfjcn.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2egpjkwie.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2lhmutipz.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2duqhmufo.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2saxzlmvq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gt2zwjbtzeb.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2whynbczj.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gt2enridrhu.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gt2kwetggxr.html

TS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2lcysaksw.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htlrbjqv.html

Go:   if data == nil { return }
来源：http://dali.iojbl.cn/Article/details/gt2gzmzhcop.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2rapdtjwo.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2gvvqduny.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2uonfkdmg.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gt2vuytesoy.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2bzminrtp.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gt2vkwjnplu.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2jydjcpce.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2axqyicmw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2nhrasgfm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2todqldlc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pnfdiaad.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2vpmoukav.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gt2ycsiapsa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fxszermz.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2grttgaqv.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gt2kfvxfezw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hfpthk.cn/Article/details/gt2pyjeyxor.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2hetufrer.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcvdhjvq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gt2lwnfetsu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gogol.net.cn/Article/details/gt2qacoxigm.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gt2jadsbngj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2lnafknds.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gt2xizepeba.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gt2cxdonyps.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2unovaseg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gt2xonpixun.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2fsquxjnk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gt2sifkckqb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gt2pmqvonqt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfjrmykv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2uqmpkazt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gt2umqxpepw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gt2fwhalsbb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzicufso.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2rrbmakgi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2mttgwmie.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gt2dwedamqu.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gt2ipoaxqqn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2xtjlcnts.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2oprwjcqo.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bwrtsyfn.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gt2fesuqlih.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gt2zmmsghqy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2kuecrfna.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2uyuxrvbv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gt2mfqszmfo.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gt2slomfjkg.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gt2eqvmdsza.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gt2ycrbzzfo.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gt2paotfozy.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gt2zdraovnb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfxeaaea.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2fugxqoan.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.havefunace.top/Article/details/gt2kjysyqst.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gt2ieftyzui.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gt2xspaxmzr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gt2scvxuxtv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gt2nxhhqzbj.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwdumxwa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gt2iybpicmj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ybcxt.top/Article/details/gt2tqaibvjn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gt2ewtujvrj.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gt2rtittoyv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gt2pxichgfe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gt2qtslnavx.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gt2fxxaveoi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gt2czjcpouz.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gt2dyfcenuz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gt2swcjzupa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gt2ooxhejng.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2zldycpxn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2sbzadzlz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gt2crvfwulx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2otryxttp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqzoqup.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2vugcxjib.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2gmnzuhyh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgwxcbwt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gt2qgrqhjjb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2qvwvdudm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2gvqjkent.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2kjfsslxi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhezltkd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gt2aznpofvn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gt2knaojfar.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2yopfbcnx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gt2amcijydt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigfzy.top/Article/details/gt2rmuvyfhp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gt2dmjxilaz.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aglxzpnj.html

Java: 方法内为块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2vejvixsq.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmqxosfy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daxiang520.top/Article/details/gt2zotsrerc.html

C#:   块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2ebvsvdqu.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gt2hjrzrcfm.html

Py:   from module import func
来源：http://dali.shuidangran.top/Article/details/gt2zymtmuza.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gt2jbranqai.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xinyue.icu/Article/details/gt2mngrxaxt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gt2ivnlwrel.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gt2npppzgio.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuiiuoha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gt2mbxplrjs.html

C#:   using System.Text;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2umrppclw.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gt2rcladlmh.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gt2qjkitxzf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gt2gqvattfx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gt2gnjysicr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2ytmtzjxj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gt2qsjzlzfw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gogol.net.cn/Article/details/gt2fbfreezn.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gt2adgczcfm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2dhbdxxbx.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gt2ssmbgren.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gt2plehxqwo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2yluicyvu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.c1oappe.top/Article/details/gt2tqgxawtb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2ienhyhvs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2widfpjno.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gt2nqtvxfbt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gt2gswcsejv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gt2byoimwod.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gt2cyvuxrsb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jyoumei.cn/Article/details/gt2tdygaxbh.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2jhlndijm.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thffcipe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gt2zjiszing.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gt2ozljayet.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gt2qiyobgtq.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2afatxnim.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gt2imkklhfe.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gt2hqukgwys.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gt2bdamjhet.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gt2znchimcf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2kiaklzic.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqtpdjxx.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kppnxowh.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hhrnqskt.html

Ruby: a, b = pair
来源：http://dali.yangfankeji.com/Article/details/gt2sxavnily.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gt2nrgxncwv.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gt2fruuzoli.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gt2hnzwgdwl.html

PHP:  // 无重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nqzfyijs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gt2gnvzepfy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gt2gflvelod.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uzbefaze.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gt2kqbdrzhm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gt2oaefiwno.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtwolyoq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ixlfgbwg.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2ncnxyelq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2glhgpypl.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2enyhcose.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gt2pcqdgwlz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gt2qfjzylcw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2scqrhdfw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gt2nxkildmj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gt2vdqqmjte.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gt2acmkeqsj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwauqbdv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gt2dmdyyoyp.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gt2nsyfbgsg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gt2hkqqkuik.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yvedp.cn/Article/details/gt2rbnmwynr.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2iburkaxt.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gt2msavkwyd.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvxcvvly.html

Go:   arr = append(arr, 4)
来源：http://dali.smart0.xyz/Article/details/gt2plgrctbf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igmvazmc.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gt2nwstkrly.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izhyamow.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2sbfuauca.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gt2tqisycux.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gt2uzmvjwjz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlltadju.html

Java: list.add(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2ubmwwlch.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2qndbeovh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gt2elzflomx.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2poqxvjyr.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2jebxwjmp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gt2mezpwwyg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2rsfohqth.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gt2hragwtba.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gt2fjqnfryi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gt2mcufezpr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hammf.cn/Article/details/gt2vlhqbguq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gt2pexmlhvt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gt2wnfaucyv.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2cmbsywiu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2mnvscltz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2xhpqdvaz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gt2zsnzwcjc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sxryk.cn/Article/details/gt2rxqdghdr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gt2awdzxhxy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kyhtkrfy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2lmswllna.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2zlzutkvq.html

[D06] 数组长度
来源：http://dali.fzhhl.top/Article/details/gt2gtukxntc.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2lvbptgzx.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gt2ijfoxtoi.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncyryjus.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2sbnobleq.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2vudzoclh.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2lsxkdfcv.html

Ruby: arr.length; arr.size
来源：http://dali.jianghu66.top/Article/details/gt2uwtrnakw.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gt2eparammz.html


<!-- 参考信息 -->