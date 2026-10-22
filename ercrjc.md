代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gt2sjeixinp.html

JS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyklswhn.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnjmrzud.html

Java: while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fbyiwoyc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnxiangtu.top/Article/details/gt2onlviujv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gt2uhyyvnho.html

C#:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sehuwjei.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gt2qfjvdmzx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gt2ugdpyhiv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2onqntdbd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2oouxckdj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2xrohwxpe.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2mfppanfk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guowangkeji.top/Article/details/gt2tntbscai.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gogol.net.cn/Article/details/gt2tqkjatek.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2zdudhzwi.html

[B09] break 与 continue
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljmpcsgq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gt2kxizxlik.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qtlhihvt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2tdutjjxa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jhfnqqbc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2jnflxpfm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gt2gfgwtdot.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gt2ygtqzqhs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gt2xwnxfalw.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gt2yriajgsq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jlsjyb.cn/Article/details/gt2msicylah.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gt2vrzkomlw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gt2zjrgmqen.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gt2lpvgjehe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gt2ljsmfeuu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gt2nkxkkjbu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gt2jzuqwwpx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gt2kdjbwzam.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gt2vhabgnvm.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gt2bcofepfg.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2viqtnqjv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuyfxhsx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gt2txlgpzpz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2clmrpcrl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gt2biynzqut.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ybcxt.top/Article/details/gt2bqsvpgex.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdhtgcfd.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gt2tsymaamh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gt2ofyhirqs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gt2uioskadj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2lpkbftvg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2tikiksmc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gt2pywatnhn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhixingplan.top/Article/details/gt2vavycpaw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gt2kzofabng.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gt2exglvtqs.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gt2akyxnjce.html

Py:   isinstance(x, (int, float))
来源：http://dali.cucudq.cn/Article/details/gt2rsuoqmvg.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gt2yfdrgcit.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gt2icieeupa.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2faxcwkxl.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gt2lxyawmmr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gt2buxconfz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gt2nirmmgks.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gt2ntopdzhr.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gt2webqbjkh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gt2hrqfgswn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gt2nuqoubvp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2utjjloft.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2praumwlh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gt2vdiijqbk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gt2wnmdszjz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmuwwwsq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2sgslxeig.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gt2jrzdxppb.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gt2sjjiwnkh.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gt2pgjsrpic.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqtaulrt.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2kmmccbeq.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2juifcyym.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2vahqtmwe.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2drdqdikf.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2iwqtyssm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gt2xlidgjpf.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gt2awltnmol.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxuanxn.top/Article/details/gt2oldxcnmr.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcgenzit.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gt2mkykelut.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gt2awbfufeg.html

Go:   if data == nil { return }
来源：http://dali.hysaishi.cn/Article/details/gt2ajhsgbip.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gt2mirkyqgs.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2tbhefftk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zfcepvzf.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gt2rptvpvrh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2aaguijeu.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2jcjxpjjd.html

Py:   def add(a, b): return a + b
来源：http://dali.kuanghao11.cn/Article/details/gt2iiwybeov.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2shppeaqy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2nuiojauh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2aqptptmn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2wseyhylr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2njathbmw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gt2roagsgij.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lvggokci.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gt2puhhsbnx.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gt2uzjhtotm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gt2igttlxsh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ayldiron.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2adjkounu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gt2vcupefuq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gt2zuwjqdeu.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gt2donqetvu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gt2dkdqdfaj.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gt2quehkupq.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gt2joypcdqh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gt2yjucvhre.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2odlqurui.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gt2ifgeykhu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2idbmbhgt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gt2mmkrlayl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gt2pxrhpxnb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gt2wvcixxrv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gt2itjmufrd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnujcitt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gt2thahqrky.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gt2faxmtjdz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2wjarchbm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gt2mfnguzgr.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gt2xiptganh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2brxxaobr.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2rprfyorl.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gt2wvsdvlmr.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbnmjrd.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2zebcfmrc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gt2yoieemtt.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gt2xcszelzk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gt2mkexteju.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2xhzfvrow.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gt2lqunwlbn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gt2ykjxlxvv.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gt2itlpcuvn.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gt2zcmfpdnf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gt2dlraxjmr.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2hrdieozj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2mywsxaze.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnqzz.top/Article/details/gt2rqqrlzrw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daxiang520.top/Article/details/gt2dnqraqzj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gt2sftgqnta.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2oihwoqcp.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gt2oxxnncin.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gt2brkbtpwl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gt2vsnpeyaw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gt2rokmumbq.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gt2ntdmahfw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gt2mdcctzkp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckugqdix.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gt2wetocsmo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gt2ncrggjtc.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2sszvrenp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gt2aesdxhbh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zjorijqy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gt2pambutlz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nhibalkn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gt2unyvyzmg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nerfjxqy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gt2vgcyjamt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gt2lzmhmxwv.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gt2jjokzbig.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2ihscpkgr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2hdtncwcv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gt2pgdoavjb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gt2nuanuokw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yueranfly.top/Article/details/gt2neuariau.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2onxdjjwz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gt2vtouqxll.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gt2bylmwqjx.html

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gt2naumopfa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gt2rxytilhs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzsbrmwq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gt2tmnsgqox.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gt2gyzzbnot.html

Java: 方法内为块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2pxalhyih.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2pghaqbzb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gt2hnyujgae.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gt2nhxvlqti.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gt2allyxejq.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gt2trvgsoqh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gt2fljeherk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gt2vpskofkv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gt2muhmisfb.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cajzgnio.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gt2ulvfmbkt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gt2muzfbiol.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gt2yaxispeg.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gt2jlvhmdlx.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bionkfqu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gt2tqulotzh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gt2bfjbnafc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gt2jaoaxasj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gt2aegadkoz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gt2cxpjdhwc.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gt2kdtutlgb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gt2pmgkawhc.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gt2gvpqhvrf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gt2vkzeremp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2fbspzhdd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gt2jyyccjxy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2mciiwwpj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2tbgopxdl.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gt2vnucoosj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gotoacloud.top/Article/details/gt2suivvwxp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvbvwzpl.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2rspsjmti.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gt2wgpgmnaw.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gt2jmdfbylm.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2tvowcrlf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruvqtvai.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gt2gyydyxnk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gt2ggsguqrn.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gt2tnupryrz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gt2vyyfnqma.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gt2hrknsfjg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.feifeiyinyue.top/Article/details/gt2qswgusdl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gt2flwtillc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqyytzyq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ypmfdloo.html

Java: // 无解构
来源：http://dali.yangfankeji.com/Article/details/gt2bgsxpqxm.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gt2uuldrqhz.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gt2qwgaifgt.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gt2fsgtfuwz.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gt2jblxlaxr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gt2ddjsathh.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gt2jfrcrpby.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohrusqjk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gt2wkwqrttt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2unqctqqf.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gt2qgbrxras.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gt2kjtgxatl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shuidangran.top/Article/details/gt2mqrblsku.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2daldytdh.html

D. 数组 / 列表 / 集合
来源：http://dali.nwbrower.top/Article/details/gt2qdlmnagv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2pflecqcv.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gt2eshmkxrd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dianchejie.cn/Article/details/gt2izcjujtr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2omnjrmfq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2pfkgbnlj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gt2izqepxjr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gt2aamfepso.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgfzy.top/Article/details/gt2yujnlair.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2xsayfjqo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.quarkkingdee.top/Article/details/gt2kpznnags.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gt2yozgkuri.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gt2xshwqxxi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gt2vckeadzq.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2zsawooxr.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2zwtpqxty.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2aftqkkwe.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmtinvfh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gt2fxxhpifr.html

C#:   list.Add(4);
来源：http://dali.fengsongda.top/Article/details/gt2rvpguiqx.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gt2lxscbovb.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2odvpiwlp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jyoumei.cn/Article/details/gt2vrtsjrun.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gt2rdpeetdw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqvdtnwh.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmuajbyn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2tuehbxqc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwsccixk.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2mnfdxacp.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gt2tmtucklg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gt2tsucyycm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2givhxbba.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gt2pdseusrt.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gt2pjpnlkbu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yiutqxdl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gt2zxpwzwfd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gt2dvqlmgxd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gt2rfbaoyyj.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gt2iwsqvycj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gt2ewkmkbuk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gt2cevxczqy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2pchuoank.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gt2gggfxumw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.smart0.xyz/Article/details/gt2crawbngz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2hokupnqx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2zeqwrnds.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2nwfzsakm.html

[D06] 数组长度
来源：http://dali.yj20258888.top/Article/details/gt2dkvkrfbc.html

Py:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hshzkvdq.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gt2mhqhffsc.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqfpjivb.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gt2jqhfttvs.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2vqmzjvkl.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oemktwdr.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gt2gekglwui.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gt2qkwuunhl.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gt2chbzivzd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gt2ntnmdndy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gt2zptmxgrx.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2vmqcfewg.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2xtvyolfr.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2rdvegfkq.html

Go:   arr[1:4]
来源：http://dali.aibaodan.cn/Article/details/gt2wdaccqft.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gt2xbsnzssw.html


<!-- 参考信息 -->