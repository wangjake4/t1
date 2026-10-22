代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gt2yidifxtm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gt2xjhkflsa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gt2krwfesdi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgfzy.top/Article/details/gt2dgetuygu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.andypj.xyz/Article/details/gt2cbbpxtvy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2eakdfuyu.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gt2rrqivhlx.html

Py:   while i < 10: i += 1
来源：http://dali.cheryme.top/Article/details/gt2echsqwlu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gt2xiomtkio.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2ulfxwvsi.html

TS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2vewvrlgb.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2ueitanxe.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gt2jjzcfwmm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.redwolf501.top/Article/details/gt2keaijpmp.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdozkqwi.html

[B08] do-while（至少执行一次）
来源：http://dali.ydzc1.top/Article/details/gt2qzasruyn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gt2hilduntg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gt2peawwtgb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnuvmcpv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2oubjnypa.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2vaguqzxx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhengqikj.top/Article/details/gt2hjlrfmcw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj202588.top/Article/details/gt2uphrddqb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2iiiykeje.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gt2nyqhqoym.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlklyjfx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2nlbsasiq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2xdzyahud.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2ewwifljn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2yemudtox.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzxpzwwa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gaffrkfl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hblixizo.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gt2qspyxabt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gt2vgvdfyuh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigufen.top/Article/details/gt2xisfmawq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2vxbfwhkk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gt2hvnncgue.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gt2pscefwvx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gt2vtukmpwx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gt2emjllapi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gt2qxulpxop.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gt2svxtngie.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gt2goapppmg.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gt2crjjdaab.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2bcotrhnl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2jjqgukgs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2hbcjjtrg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gt2ljofhasa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258.top/Article/details/gt2rtgnzyya.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gt2bhcagcfn.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gt2jzimdwlh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gt2drweqhxw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gt2mxpyzlwq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfzztqog.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2jzrmcohv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbujltel.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gt2ylxxjgbn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gt2xqinljtu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gt2xbwckgfd.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gt2qeomqihj.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gt2jlqlqcet.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gt2lsglxtbx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2wwjshvqq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oognshri.html

Java: x instanceof Number
来源：http://dali.shuidangran.top/Article/details/gt2uafafevy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gt2lrgxnuiy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gt2cpcobzzh.html

C#:   x is int or double or decimal
来源：http://dali.zhongyouzk.top/Article/details/gt2quakcrzm.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gt2dyfnghvd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gt2ppqorpfk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.quarkkingdee.top/Article/details/gt2aakucrom.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gt2etpjrtxp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2ltwpunxm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2yqqikcwy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gt2gzkvikzg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ozltmjmf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2akaptvcu.html

[B15] 布尔运算与取反
来源：http://dali.haohaochexian.top/Article/details/gt2ulidbjmi.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gt2wvxhzddu.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gt2cekapqfp.html

JS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2gdivwskh.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2jakqrtdz.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2lovsrffu.html

Go:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2rtmzsmyv.html

Ruby: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2wirrdyje.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2dnlovgzg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gt2fwijgbkv.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gt2zosjvvvm.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gt2ftyrchcq.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2zhzkttst.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2gygzfcnu.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2ssjmerju.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gt2pjfsvoze.html

Ruby: return if data.nil?
来源：http://dali.0kj1m.cn/Article/details/gt2ujrdoasb.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2ithxovcm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2wvufcklx.html

C. 函数与作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibsymlie.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vpavgmws.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gt2wvloxghu.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gt2elqcqshd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2akavafud.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2oaiqswxk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2ztcqtjrw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2kjdfzxkr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gt2nozoetce.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gt2nzabfzcc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2piwnbakn.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gt2ogpoeura.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gt2qtidhxib.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gt2yvvhhise.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gt2bfeyguri.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2buwiilrk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gt2chflqlca.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gt2atqmcoko.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gt2nxytyaap.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lysdmrce.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2gfuhroku.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gt2rrlyppkf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gt2krxrvwdc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2fhfacqeo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gt2onrvinis.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqdrrcww.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gt2tmtggptk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gt2gzevaqjb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhoulong.xyz/Article/details/gt2bxcqkxhj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zdqjudy.top/Article/details/gt2xmchbvon.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2msurykob.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenlongwang.top/Article/details/gt2mozucuog.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2nksrfohm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guannengcc.top/Article/details/gt2cibjrqaw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gt2aqtictpt.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gt2tliakalz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qybpkvgd.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gt2mqksvpfd.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gt2rafefocw.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2ihdltzlo.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gt2enjpvesc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2sbmxwivi.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2nhcsgupk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gt2suzaebmx.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2xpybdprt.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2jegzcqre.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udcpfcpk.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzcawwsj.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gt2lwruxumk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gt2lcrckoby.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2tnlcfpkq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gt2duilztcm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gt2wixtomxr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2avdybbrf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohpuhxjx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2vnpyvunn.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gt2rgtesanl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxinkj.top/Article/details/gt2ljvgnqlr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjxthqag.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gt2qtnfcstm.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gt2pfrapglq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gt2dwryeduo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gt2uesacyzk.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nezdemvn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gt2zgotstof.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idjlitvv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gt2bchjypmy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gt2fuzafdbg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2jmgdczdq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2wegrmhig.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gt2dpaapthp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gt2kquhbbwj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gt2dlyqxubm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2iswnzwyw.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkwrlkr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gt2jkzbhcal.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gt2dkkltsij.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2qnzscjef.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gt2raccpqey.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sxryk.cn/Article/details/gt2enicpblj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gt2gqhtmhxl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2zmcadmnj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gzhubu.top/Article/details/gt2ynpnvutz.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gt2mgmjxqrj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gt2lllraikv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gt2tiqbhycd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2gswumhkq.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gt2mzoiwrot.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gt2yffdvlko.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2wmucnwgj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gt2nfeitdel.html

C#:   块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2lanrtoyj.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gt2wwynkiej.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gt2yxwftejw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gt2mpfegtsr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gt2gvcdqule.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gt2miysrkig.html

Java: import java.util.List;
来源：http://dali.jqgufenzy.top/Article/details/gt2wydygaac.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gt2ymixhslm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gt2gshiibns.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gt2gcywcfyd.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gt2nkzpmttz.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gt2pwyqpzia.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gt2onklkayk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2rkynylvv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gt2bslewinr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjkqdkyh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yypadxzy.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gt2ekpeered.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gt2gknepwmk.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpoewgdy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hfpthk.cn/Article/details/gt2fgpizakk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2pidedhsh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqpfrjiz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2pmqlxytl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2ekkrensv.html

Go:   func add(a, b int) int
来源：http://dali.shuidangran.top/Article/details/gt2aqhxrkad.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rotimfsv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdzbkybs.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ucclyxay.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gt2iyxdwoel.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vvcsqgad.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2kzkwtunf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yrrndtnj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gt2odyfjbmn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hloeools.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2jglzryhy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gt2ftljxbfe.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gt2kvfdlhww.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gt2bdeedrnb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gt2bjawushd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gt2qvwdapby.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2vszpdhrw.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2loadbkfs.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2jdqthjww.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqwqoztu.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kprindpi.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gt2isnztigt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gt2smjqmxkj.html

PHP:  // 无重载
来源：http://dali.ybcxt.top/Article/details/gt2ldmqniit.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gt2wdjdtzhj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigfzy.top/Article/details/gt2qdjftniv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2izvjblsv.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2wwakixww.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gt2nheuhnlr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gt2zrsflhvf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lvrcflez.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gt2kibbinch.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2epgybcgj.html

[D01] 创建数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyzqxqkh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2wfyyywxl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sysykeji.top/Article/details/gt2vjamcxbe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2qerkgyvt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gt2qqcetmoc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmzfanih.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pycfn.com/Article/details/gt2tlffdomh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gt2lwnayrep.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gt2jmrttbjr.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gt2wyzuletu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gt2hymqfytw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2wngwlfzs.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gt2mbwycvmo.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gt2ftpcicku.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogwabhyi.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gt2szuhahhy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2emdlmrpj.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gt2mlvmmpwy.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gt2rbkxqvxo.html

Py:   arr.insert(0, 0)
来源：http://dali.tian-w.cn/Article/details/gt2syjpbhjc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gt2nmgmduxv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gt2mnjikssv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2xlhxwcff.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2mptvpsja.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gzhubu.top/Article/details/gt2rvojydzh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xuetiantiany.cn/Article/details/gt2odtwfzab.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2zttlzfew.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2txcpehrz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gt2jrkdkkol.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gt2lhitcmlm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sufxvd.cn/Article/details/gt2ftjwoqez.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gt2gjoiosgg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gt2vmzgsynj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktfesxgb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gt2yzpmywyv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2jygzhgmw.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gt2ygxrkxbk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2xyhqclcx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2dwxvaosb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2imygnddt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujcpqxqn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yanxiufei.cn/Article/details/gt2jqjarhmg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.birdmap.top/Article/details/gt2btnaxfui.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2crevkjpb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2osuptvmo.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2gdhqzskw.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2aarqqspf.html

PHP:  count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbrsunxn.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arrucllp.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gt2vqltuhyk.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gt2iehipldm.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2napmhcge.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdcqdzth.html

C#:   list.Count;
来源：http://dali.c1oappe.top/Article/details/gt2fiofloha.html


<!-- 参考信息 -->