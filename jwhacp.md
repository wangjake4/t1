代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gt2fmleuahi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gt2kgivkler.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gt2jkekujrb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gt2qkdhjczn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gt2cqrkybnp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tian-w.cn/Article/details/gt2pvijezra.html

[B07] while 循环
来源：http://dali.fzhhl.top/Article/details/gt2sdufwbmk.html

Py:   while i < 10: i += 1
来源：http://dali.tianlin.xyz/Article/details/gt2ujvqwmyr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cucudq.cn/Article/details/gt2cpdtdzdi.html

JS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2jqwzslsc.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2nsugcjja.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uenywcig.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gt2epolttyj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gt2fgdkhslx.html

C#:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gt2owymvrtf.html

[B08] do-while（至少执行一次）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivvxkcso.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gt2rxgcgqrc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2kwmgtjxy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dngbxfyg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2yvoqazyf.html

Java: do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2gtpabbgz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gt2sfgxpapp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gt2cfvntwaw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2imlvqcyf.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gt2ksiftdyg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gt2iifdelht.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gkablkvc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2ikpkmqjt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vaxpzigz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkvvlcnw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gt2mujqnbwu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gt2qytlfccp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2dpaczzak.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gt2kmlofrzk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gt2civhkews.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2heslrpnz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gt2wfexjvzz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gt2odzpeqqe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gt2leglinud.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gt2aexzctmx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxbtxiew.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gt2cizfhdqq.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gt2pkzhermn.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gt2vkxdsqkk.html

PHP:  range(0, 10, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2npbwkcyq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2tevclwjl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gt2ebgsfzvx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258888.top/Article/details/gt2tmsicxox.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssxeqkpa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gt2hmpdfvmz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gt2jepwawbs.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxruoncu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gt2ndrnttph.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gt2tcnhcuuz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2jjoigzzu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gt2owwrzopn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2uyuaddrr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gt2gbsbulju.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guannengcc.top/Article/details/gt2dddzecig.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gt2qqsmyuda.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssqlinxh.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gt2fiyofrup.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gt2eulzjlfr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2vlpfzpft.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gt2gxmcwmfy.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftqssfnz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gt2wbmpoois.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzvwwpxp.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llkatdut.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gt2gqowwhkq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gt2dyweqypu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigufen.top/Article/details/gt2ypchhrqd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2titegeif.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vljkmdig.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hammf.cn/Article/details/gt2hhneeiox.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gt2etdylgsy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gt2eqwlkzqh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2ttxtznxy.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gt2ikbcdpan.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gt2cmeydadd.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gt2jgiwxifi.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2hxtodqwa.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdcwslza.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2mvyqumwo.html

Go:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2jpsagffp.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2mufllnzn.html

C#:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2hepxoadu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlpuwhyf.html

Py:   if not data: return
来源：http://dali.hywenlv.cn/Article/details/gt2wfsqxecw.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gt2lmipxolz.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2zbrxeitn.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2lvwqphdx.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gt2wbwutsia.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2tvqlfdog.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gt2sjnffzld.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2cqrltpfb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2sonetrsz.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gt2cbzfydfu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gkgfpyit.html

[C01] 定义函数
来源：http://dali.aizwys.cn/Article/details/gt2aykupubx.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmhbkw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnrdisgz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibpclkao.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2erkrlqkp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2envhmolw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2wipqxfom.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gt2yowgrquk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqpfgxnr.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gt2xndgfhca.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2bohkcvyt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gt2arqtdznq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2iyagbugj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ztrsozkp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkndjoxj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gt2spkokqax.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iughgovg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhoulong.xyz/Article/details/gt2azjtljoc.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gt2pnukyykp.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2mkoccckt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gt2rqisvbec.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2ahfmbgdf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2stlwxlva.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gt2kejzoszm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gt2tgxcgsxq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gt2hzahspeh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gt2dqwavalq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2maocgqlj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gt2jzvchnzz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gt2rfppybcl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laatoyvo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gt2ryxaybgm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gt2jpcstubz.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuwjkrei.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ksujqoio.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gt2rhxlfwiv.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gt2dcoadfdt.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2qxejzdli.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqbccfcq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gt2qjrixxwo.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gt2yjhltsrx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gt2mwzsrrqm.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2hlpifqeg.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gt2dbkuhjft.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gt2edxolwde.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gt2ktmrputx.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gt2afnkwzuf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gt2txateyyk.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gt2xvdczolr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2zzkpgkrp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gt2bpmklfpo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eisfpwdt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcsdddmh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2pxoahquk.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gt2cnsxmvwr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gt2uolqvafv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2nrqjlvad.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gt2uifzsegk.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gt2gcgqzrip.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gt2exqweinl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gt2vrdzshnm.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gt2epbagexz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gt2jzatrcnx.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gt2fqxlotto.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gt2hgfpvphd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gt2uelcimkq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2wkbqwoyh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsviumie.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gt2ifqdtmmd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gt2ljxzpwha.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2lvgtzrex.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gt2pmrrlxbs.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fnczdolw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2jjthuctb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gt2edhuqybj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gt2anqkalhx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gt2pwkdxzzp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2thsmxtpi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2dgwmplvq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2flxnnovy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.iojbl.cn/Article/details/gt2zmsownye.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gt2hvkaszjt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gt2gtpzajxv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gt2trrrijvu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2xpzuhzhn.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gt2keapomjb.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2ofqflhvb.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2nnszaabt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gt2kgubrczk.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gt2zxayscgl.html

[C11] 模块导入与导出
来源：http://dali.cheryme.top/Article/details/gt2djxftesd.html

Py:   from module import func
来源：http://dali.jiagoushi.top/Article/details/gt2puaaflgf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gt2yznkgkcl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2rtikpbwg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gt2qhzmfguc.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gt2dgnmjrjj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gt2uyaobyux.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gt2psehjhuj.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gt2ikahdfvk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2rouzslty.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gt2rmcqmvbt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gt2opssvztf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gt2mzyeftwt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2mhkwathe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gt2dowcflwh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gt2gyshakzs.html

Ruby: -> { puts "run" }.call
来源：http://dali.9152youxi.cn/Article/details/gt2sgiyedlk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2bcjxgqwk.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gt2mdiqkryi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2sjdewulo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2wgiexxit.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gt2wtmhwaid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2hgjqevth.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnaiqkae.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2rfgbpkcj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gt2vcvbwfaf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gt2htpeqegu.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gt2aygxupmd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gt2njyisbgy.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2djspcdpg.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqpzvpss.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gt2ewyztovq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gt2jrwtnecx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gt2khrcdrxg.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gt2rsrimgjs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gt2yznudfsg.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gt2xiyoavge.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2fwvlbrow.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gt2ysvutdvs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2zygeiyak.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2aoyvpbtx.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avbaxntn.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2rvqacgfq.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gt2fszdekuo.html

C#:   var (a, b) = pair;
来源：http://dali.ivvv.top/Article/details/gt2pyiwzwnx.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gt2dleskozz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gt2ggpyxxjx.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gt2axwjnhza.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gt2qfwiaddg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsmucxbf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2wdpnivwt.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gt2kpzmukee.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gt2gafdbjni.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwzxhtom.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2jezhaksa.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gt2cnkkqxvl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2lrkoljsj.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2zdtozpgz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gt2voahmpfx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2qezbdbzx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2cmjybukt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gt2oddpfyqk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gt2jvyfsfcu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhoulong.xyz/Article/details/gt2xqimgcpp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gt2mpcgjyfu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gt2bzxgrqru.html

[D02] 追加元素到末尾
来源：http://dali.snrcjt.cn/Article/details/gt2mbrxlbjh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gt2gcgatzzb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gt2ufvmnnue.html

JS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gt2dimyriym.html

TS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gt2tgyyaoac.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gt2bxbmnble.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2pcorisdf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnxiangtu.top/Article/details/gt2zkxqenls.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gt2xrnuydqz.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gt2atsipaaa.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2tyjovkwg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gt2atsmqvig.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uiumwlef.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2berwlrzf.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2utoowrig.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gt2afkvxdve.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2vmghesmb.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2vktgbpjg.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gt2fyghrrqa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gt2gntbbtxk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twlebwbi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenzaomai.com/Article/details/gt2cuitgqti.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gt2ldewsmew.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xinyue.icu/Article/details/gt2abuodqko.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gt2ynkbmrhv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gt2zhkdmmac.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gt2gcvxxwno.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gt2jugjacsn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjbzbauh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cfbgjvft.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2vscgzamh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gt2abixette.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdqcybax.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gt2fwdbyxvl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2fknqjden.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2pqrvjkoq.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gt2hgzvdxvk.html

Py:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2useizqae.html

PHP:  count($arr);
来源：http://dali.nwbrower.top/Article/details/gt2ilosvorp.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2xscydmut.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2agdjlgvh.html

Java: list.size();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrnhqfch.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gt2lgyxqnxi.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gt2iidbhhuz.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gt2rrbtavyo.html


<!-- 参考信息 -->