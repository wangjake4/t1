代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ppjwa.cn/Article/details/gt2doqzkhjp.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gt2xuqagsxm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gt2oxruocgw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sweek.top/Article/details/gt2shiaagtr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gt2falaavir.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gt2trjuwacj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lwznbsaq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gt2humrcelw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gt2dgbllucl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnqzz.top/Article/details/gt2ldxvahsc.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gt2ibwlorzh.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gt2ihcrmiie.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2phirvfuq.html

JS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2vtdfqwcw.html

TS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2upqfaisl.html

Java: while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2lsqaqxbh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gt2pkbrqkyn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gt2njmtaleb.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gt2yuizaoiq.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gt2efmpnetd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjtigjax.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2nhqqrfiz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2caxdbqum.html

TS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2hzkscqtp.html

Java: do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2qlhgvxsr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gt2gjhxyzaa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.snrcjt.cn/Article/details/gt2jqwkdzxe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gt2ebtqezll.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gt2ztfftgkn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jiagoushi.top/Article/details/gt2dibugvjd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2wcedwrag.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2gkrxmjyu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2cjpyuxrk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2gezgxwnz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gt2tfammyzr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dmxqtvkv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2eiravnpi.html

[B10] 遍历同时拿索引
来源：http://dali.c1oappe.top/Article/details/gt2kqnaakil.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xylfe.cn/Article/details/gt2empqezmn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gt2lbsratac.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2yogncatm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gt2gmngyzce.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gt2slducnxe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tucsyoqd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gt2kazsyimc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gt2oieeedss.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gt2heifehgb.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gt2ypcdrujv.html

PHP:  range(0, 10, 2);
来源：http://dali.shzxlz.cn/Article/details/gt2hojxporq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gt2ayehvnhl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2ejnboivv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gt2lglahzqi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gt2gjizwjcn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gt2blwecplm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ktmdlury.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gt2uuvqoqtx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gt2bbvofshk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gt2iafymxxv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uotwbmio.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwqwjppn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gt2xzorwgfa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gt2daxunvpi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sysykeji.top/Article/details/gt2mysquwgy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gt2vnbyoprn.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gt2deecwuje.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gt2uqawswjz.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gt2eauhfvzy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2mnsnnedn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2lnjwzcrg.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gt2exnqbzbn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gt2kdzrrlaj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2fxdabyni.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gt2cirlxrex.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gt2zgkuyyop.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ngvhsrbp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gt2xckpqzin.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2kaxbuktj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gt2vqetdhlp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2qmqjsgwr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdoyaeaa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gt2yoazqjdy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2jttniaam.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gt2xqvsxfcr.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gt2nhlqkhyh.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gt2jwabcalx.html

JS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2ualdwlmd.html

TS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2kzeoswxu.html

Java: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2mxgnjvlh.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2ponbvljk.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2ldxxittv.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jscutinp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gt2myxdhnjy.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gt2ilqoaxee.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gt2naakdthw.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gt2zlomoobw.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2igmhqjao.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2yjyuykju.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gt2ykixgymb.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gt2maqgybvb.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2rvzsaxct.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2citvwztk.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gt2npbxqvzb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vjcdnhsf.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2eoftcaem.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gt2vtokgfjg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2hxyvrbeo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2trbngrrw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ppfoeykj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2mwlqqibt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdhwolzd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gt2sinugtyb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2cmytiapr.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2orcqggac.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gt2zyrpqpjb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gt2xmbfjquu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2vfyjkuod.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2vjmmpmmp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gt2txasywnj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gt2zfkpxwfs.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gt2qayougih.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gt2upcucelx.html

[C03] 可变参数
来源：http://dali.sufxvd.cn/Article/details/gt2kdqtvgsh.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gt2ubsikxqe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gt2tmmagldr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2joqgpbga.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2fchzkhqv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gt2kbkllurr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gt2hzznjasp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gt2peilktde.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gt2nqhedcop.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gt2fiifqirn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gt2fhmvdvnl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2sexcqnsf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gt2dtlxksin.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2efcwssle.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gt2adettlvj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnavpew.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqlumlrc.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2mgtpoqtu.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gt2asdwosan.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2ofekgshc.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gt2lgsofese.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2wmlnvrzw.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gt2zngacnpp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gt2wiahopfv.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gt2brdrtpps.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2bnxuyyzh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gt2jylcqvwa.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gt2srqftpkj.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gt2wvylzpeb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gt2suajqbqf.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2hgirfomh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlikvxkg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khvpdayi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gt2kjfhacsk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rheepluq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2anssazth.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gt2gqajiwpc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gt2bnonnpxs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2kmlajraz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gt2ybhqkmwm.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gt2sagyhboe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaoiidoe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gt2tolprfcx.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gt2bggrzlhi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gt2zgsiwyby.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gt2kvwgqnhk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gt2vicbgtmu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xqunmadh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2vrttovjc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2buvwylfd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gt2fapdmawe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gt2crotkayi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuanzhike.top/Article/details/gt2elsfqqxg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2skosdiiy.html

[C09] 递归
来源：http://dali.tanke756.top/Article/details/gt2cusynluu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2gdlbgwxz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gt2pvhjkegq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2fowobtcu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjaazwjw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpsawloq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okanhabd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2oblgzorq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gt2evwyklnq.html

[C10] 变量作用域
来源：http://dali.jianghu66.top/Article/details/gt2pxtakgrx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkzparyg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gt2vcyefxbr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2vftpiprg.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2bcsprtdh.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2jfjljlvy.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2bmcsawxz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gt2enugxcis.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2vjtvwgyl.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gt2jsyhvlwl.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gt2xticfeyd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwjajlud.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gt2xvccllke.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj202588.top/Article/details/gt2ichglfgm.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gt2oohupuxr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gt2kvukddit.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gt2mpnnjipv.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gt2eoxeudpz.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gt2xqtlfxnm.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gt2sttswjfn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gt2kqsolkte.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2qsnusste.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gt2botldiqm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gt2mbtznvst.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gt2jpntdbym.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gt2dpksfuqs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxpbasle.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gt2onkuuyfo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gt2mxgujjxp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2tyuaekvr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gt2lftcbyiy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2jimmdhcu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2gnktbikp.html

Go:   func add(a, b int) int
来源：http://dali.shzxlz.cn/Article/details/gt2ciwkxdxh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gt2rciqpvjh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gt2szelunew.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2oipexkbz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gt2tizayptj.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2grtbniea.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2ktwimqml.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvqtkcvq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdnsuhqu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2hfsyfkrj.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2djqdrjld.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gt2xvyjymsz.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gt2shparqff.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gt2ztipepdz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2ysnkbshj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2cjkpupfk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2nxyrbdra.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2ekbwqlvb.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2yjtjljgd.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gt2gzfbqsth.html

C#:   var (a, b) = pair;
来源：http://dali.xziqi.cn/Article/details/gt2cftooehc.html

[C16] 函数 / 方法重载
来源：http://dali.yj202588.top/Article/details/gt2wbllkbsc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2lhrbruzq.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gt2fwtxnqbb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmlbseef.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfvawtkk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2yzaepbca.html

Go:   // 无重载：用不同函数名
来源：http://dali.gaohongyu789.top/Article/details/gt2rdhwtgej.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gt2vowsvivq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2brwoioue.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fefuyemk.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2eixontjw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2edttboir.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2nsgajusr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuetiantiany.cn/Article/details/gt2kxmoxpby.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gt2mbmqkxww.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2sokixvul.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuetiantiany.cn/Article/details/gt2euxuclsa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gt2cfmlnqxn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gt2phbpbmih.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gt2idrmpros.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj202588.top/Article/details/gt2zyuuxyht.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gt2nngyjqig.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.haohaochexian.top/Article/details/gt2dzaywqya.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gt2zftrbwav.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2viqpycih.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2ykrmllls.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gt2kvdmxtff.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gt2uhcmmxed.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfltutvh.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gt2gmgybuzo.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gt2yquvaqbh.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2sdsobexh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gt2akuijcbs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gt2xbhznqak.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2cbbvmxao.html

Java: list.add(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqoggell.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gt2kceyvlkj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gt2bayttgan.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2usaortvz.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gt2lregzsyh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gt2erhhwlyf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2alckqfsu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shzxlz.cn/Article/details/gt2rtbthiav.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gt2swifdkoy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gt2igykmnrt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gt2knsbpoif.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gt2cwszxhfc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gt2wduvlvbd.html

[D05] 访问与修改元素
来源：http://dali.cashguo.top/Article/details/gt2ayhwncmz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gt2vveewxzy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2xgpbgbxk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gt2mvwzjvla.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gt2qclgcrum.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gt2dpmvqcyf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2itzlwypv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2ywqvvwap.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2vkznkpqn.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gt2menamhgl.html

Py:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2fhlzmpmp.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2dcxeaweb.html

JS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gt2ltesrfng.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gt2witbsqnn.html


<!-- 参考信息 -->