代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.redwolf501.top/Article/details/gt2sgpmwfnq.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbbrsxik.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mpvyhtqq.html

Java: while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2ktuihhie.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gt2odsnbuxr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gt2acojpxpd.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2jhuznkbe.html

[B08] do-while（至少执行一次）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ychmcnub.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.snrcjt.cn/Article/details/gt2usmbmwky.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2vnufezfv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2sieuxenf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2zgihqbyp.html

Java: do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2hvkyiogj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipxhewcj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hfpthk.cn/Article/details/gt2esncsfma.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2muwltshu.html

[B09] break 与 continue
来源：http://dali.redwolf501.top/Article/details/gt2glstuaxf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iprifogw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkuquryy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2dbwvplxd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2sittfubt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2vayvmjfd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaivzqxc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gt2epzzjaug.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2uhyuzdxn.html

[B10] 遍历同时拿索引
来源：http://dali.svipenyu.cn/Article/details/gt2mzplvzdr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gt2tochfrci.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmnyeskd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gt2uusrswpr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2qigrkbwc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gt2arhfwlhg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gt2eodhkzsu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqmgbjcy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.vqdsnc.cn/Article/details/gt2utwxpegs.html

[B11] 生成数字序列 / 区间
来源：http://dali.snrcjt.cn/Article/details/gt2ytvydnqm.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gt2voujhihr.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gt2rcsrcjdv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2bepeeeox.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gt2vkjxpnox.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gt2ytaqpoop.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gt2qeqzzznf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xuttygah.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gt2kmbfgzgr.html

[B12] 跳出多层循环
来源：http://dali.fengsongda.top/Article/details/gt2itswibku.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gt2utycvnro.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gt2ugkgcfda.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uznnstld.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2awzymase.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2xqvpcede.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dianchejie.cn/Article/details/gt2pvgalihr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qobjijcj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gt2zqkzykwc.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gt2ceyxwcyp.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gt2mzheczvh.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gt2qmpradbc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2wvqxrerq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2xekstdua.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvbzreqg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbzwenmr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gt2kpkqkgzm.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gt2jencnjey.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gt2uzgillok.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sxryk.cn/Article/details/gt2bqgfdlxu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flxwnxus.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2hncocywl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gt2fsmerpht.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gt2zfeioayx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqivcizr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fojjfiam.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2wycqqyhy.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gt2shmrwdsg.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gt2xuovvqva.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gt2cvredifi.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2elnwmxyr.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2ihrsjxqq.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2logrunxs.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2qmegarjz.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2ufblhbsn.html

C#:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2ssxiqcwd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2ibgcdcqe.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gt2irfpqwdi.html

PHP:  if (!$data) { return; }
来源：http://dali.mhx1999.top/Article/details/gt2ljukqqer.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dllcxaga.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jjtqadfr.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gt2lzyxnzka.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gt2ogwjlpob.html

Ruby: return if data.nil?
来源：http://dali.fengsongda.top/Article/details/gt2ipqvwgyg.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gt2qrgwaojz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2eiplsusp.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gt2sfxzutnq.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bimhjlze.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2mecybbjj.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjukqowk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2rbedlimq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nkxfxeor.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kjusgany.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2twehsnca.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gt2xijugyso.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gt2txoyjarw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rtjgbwhu.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gt2cpenzbnu.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gt2abswlzxp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2otnfesjn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2ftpukbcq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2hauyfgie.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gt2nngegyvf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gt2stgbmlke.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gt2ohfuwxii.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrizyhbe.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chqryctg.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gt2wbwrexwn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2zehbhgmp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwxxczgo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2aahricyg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gt2jkqnqegu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gt2ghqyfpqw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzupxwtz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gt2sdhgoqiu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gt2cgepqnpv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywmcdmcb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gt2sqmannjl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2hrakrduf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gt2wsdcwejq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gt2rbmzgyxl.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gt2phygjpln.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2nbdovmot.html

C#:   f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2uvwwoqzu.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gt2chuhqnoj.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2enuemkgv.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gt2wbwkurpj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gt2qmrgrhiq.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2tjiicwah.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gt2abtjlfcq.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gt2xtiejsgt.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gt2lbmqcspg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzebswad.html

[C06] 匿名函数 / lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmszjwdu.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gt2wgfjnpar.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtkqtuqv.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2sqxkyezj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gt2ovcrrzxy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2odfhnxks.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pycfn.com/Article/details/gt2saxcwpie.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gt2lwkpusfq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2itipxsjf.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gt2iusadmvs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gt2pcahqdew.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gt2qjawvajv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.andypj.xyz/Article/details/gt2dbssjchl.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gt2cpzydoak.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gt2vuutblrv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gt2aiemngll.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gt2qspiquuv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gt2ipwpskcp.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gt2bjfxkegx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trayszlr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjbtxjiu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gt2btlwkail.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2miutvnrd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gt2qwzomufa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gt2ehnsahrw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gt2scmhmxnv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2brqodcmu.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gt2rnygxllb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gt2uwmptckv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwanwwpi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2anutgvuf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysblvzpd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gt2hxboucnr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gt2hfcriyrn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gt2azulcnbk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gt2uljmuhoo.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gt2ppnxzvqu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gt2arzcrjax.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2nsvxjvmt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2rpmztjum.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2xeqjniwg.html

Java: 方法内为块级作用域
来源：http://dali.tanke756.top/Article/details/gt2pjorbzxx.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2dtqbrvnw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gt2vdfbnfgq.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2fhabumjp.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gt2yoafdphk.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkvbozwa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gt2yjlgvdbb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hcdadaqz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gt2qfrzsqox.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gt2tiyrpgqy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gt2iiydpzmo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gt2hgebexpo.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gt2hkekmmug.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gt2rjfrnoty.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gt2xrpwmeix.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2frxbocyu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2kluizzcp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2anmzcobu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hnxiangtu.top/Article/details/gt2gnwxjgqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gt2shexzevl.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gt2juefcjga.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gt2kanwpips.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gt2vtfqbgse.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gt2ftehfypu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2benscywn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2uxwvwekr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2ypnqybvy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2qakshbjq.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gt2gdmsesbd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2mymashre.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gt2tsyleunp.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gt2dpxdovey.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hywenlv.cn/Article/details/gt2nczeceua.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2masctvbd.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2skxwfyuh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2txklntsm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmxzxyis.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gt2vxjqhafu.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gt2muviekrz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gt2txxdftwd.html

[C15] 解构 / 展开参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuozwobm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gt2yhvktdmu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gt2btemyimg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gt2wmvopaxb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgrzwkus.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uaotdffo.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2ddqjwiih.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gt2kmstfids.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vpgqebnq.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gt2kwrcyywe.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gt2twjjbebc.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gt2ifukqgey.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gt2okvmrmhk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gt2ljsezodp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gt2fmjqenkb.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhongyouzk.top/Article/details/gt2qrxkvjoq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gt2xlogrkft.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gt2lveeshcw.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oralqmgo.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gt2csfeycjq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kamuyyym.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gt2kwqfzghg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2aaecbjyp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yangfankeji.com/Article/details/gt2gkouvpbd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2tukgliyz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gt2xqtffkae.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gt2jgzcwklf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gt2fvxdnwpw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jczyorzr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gt2nsprzhjz.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngugjfpg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dashuyun.cn/Article/details/gt2bsdalzkv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gt2hotgmrdg.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gt2voejpzqr.html

TS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gt2wkkhqmso.html

Java: list.add(4);
来源：http://dali.jianghu66.top/Article/details/gt2bbflsgdn.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gt2spbzukao.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2fswbfctu.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2cfforyqs.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gt2btjzlbtq.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2ffpqxswq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gt2aukhugfi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yctyoptv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2wiezxdgh.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2kzesivim.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gt2vezkincz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gt2beyeuiwt.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2nfovcaok.html

[D04] 删除元素
来源：http://dali.c1oappe.top/Article/details/gt2iweqltdm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cheryme.top/Article/details/gt2xvflbomv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gt2vikuaizw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gt2cmjmjium.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2awsiuiro.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gt2wijbindk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gt2scshtozx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zycfv.cn/Article/details/gt2rxznaejn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gt2erevzgah.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gt2fyacevvc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2jghnuewn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gt2fwcqukdn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2gfmpfhhs.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snzpfuyf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gt2mxlcdhyo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2bqpvphqk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2cynitcbx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2vdueglug.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gt2ahmqciay.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2othjmvsj.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2eycnfeva.html

JS:   arr.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyypppri.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdhitbxf.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gt2wlueeezs.html

Go:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gt2nupzynom.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2dudatale.html

C#:   list.Count;
来源：http://dali.cheryme.top/Article/details/gt2btfvigns.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2retkeaib.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gt2acvbdyql.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shuidangran.top/Article/details/gt2usoycvjx.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gt2hoavvlyc.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2njxwhbtw.html

Java: list.subList(1, 4);
来源：http://dali.pycfn.com/Article/details/gt2czfypoir.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gt2illvftsx.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2iyhfqjpo.html


<!-- 参考信息 -->