代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hywenlv.cn/Article/details/gtcabpzcxl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkntzglpm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hysaishi.cn/Article/details/gtczkkefmh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoparxynv.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtrxeoopop.html

Py:   for item in arr: print(item)
来源：http://dali.daria6918.cn/Article/details/gtxxkujith.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gttxpxjxah.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gtvfqohngu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtugnxysxn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ydzc1.top/Article/details/gtupliokhh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.quarkkingdee.top/Article/details/gtzumqqrvd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guannengcc.top/Article/details/gtnzskrtsv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yonumen.top/Article/details/gtzgtejvfp.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtyonozenw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgfzy.top/Article/details/gtylqrhtqx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtapnyotic.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtiexnrxle.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtcdmwhcek.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangdashe.top/Article/details/gtougfijwc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnxiangtu.top/Article/details/gtaffjamge.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdubvcxgw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxinkj.top/Article/details/gtohgrihta.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtultijskn.html

Py:   while i < 10: i += 1
来源：http://dali.sxryk.cn/Article/details/gtjjlxtxng.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cqqwz.cn/Article/details/gtnismrwpd.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtorosaxcb.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtnyivwtwf.html

Java: while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtmbeggiwu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtbkmwbvhd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gtkqicedtx.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtknhtjfsz.html

[B08] do-while（至少执行一次）
来源：http://dali.jyoumei.cn/Article/details/gtltdbiewv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gtvvrtmymg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gtlqbktcbo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqmxwbui.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtaqmniula.html

Java: do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtwcwgrjih.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gtjeuekswi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtepeoancj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtgksnzsxu.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gthbkkwwux.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gtpsspoorq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gttyzrurcy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gthcxeymnx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtvbjcoaks.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtqjjkwxbj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tianlin.xyz/Article/details/gtbbfcbdrt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gtvucdubyf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtbubvspsq.html

[B10] 遍历同时拿索引
来源：http://dali.shzxlz.cn/Article/details/gtfxcahpxa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gtoakhmiib.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.mhx1999.top/Article/details/gtcbbaycrn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtwbreoinh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtlyggdqts.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrulweplk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ivvv.top/Article/details/gtiinjvyai.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fengsongda.top/Article/details/gtndgzhzic.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigfzy.top/Article/details/gtzjkqlklz.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinghuilouyu.cn/Article/details/gtzazydmgg.html

Py:   list(range(0, 10, 2))
来源：http://dali.xziqi.cn/Article/details/gtxiwqizji.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtvtmyluxj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtdpqkuxxo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtsrhuyfga.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yueranfly.top/Article/details/gtbnrbtocn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gtbaujjyxy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258.top/Article/details/gthzozeqdi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gtphfdvylw.html

[B12] 跳出多层循环
来源：http://dali.cheryme.top/Article/details/gtdkklpdrq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gtybfptwyp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gtfnpyebag.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtcevvnfzv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtciyrenio.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtxetejqoi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gtsgjdhvey.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gtdmthnlja.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtdetdnssi.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gtdgwmxqfi.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtplpwfdsc.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gtjpoosyco.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtnnsgkjfo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtunisdtxo.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtyrivvixf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gtycyedras.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gtnuavksta.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtsigwtizp.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gtxecutsyz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sweek.top/Article/details/gtlhrhhqtf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtlmjsujxn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcegeyla.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtrtperyfa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtixsykpjy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gtzfzwwuca.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtpfdlypai.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtubbjxncw.html

[B15] 布尔运算与取反
来源：http://dali.guowangkeji.top/Article/details/gteeuefkyl.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtlwladwhz.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gttbnuidth.html

JS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtmnebbcti.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtnscrtkqp.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpjaxvzo.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gthjbynrxp.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtpwlhnuim.html

C#:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtwmwspskt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtgjmsdvwj.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gtkravpdxe.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gtudmiahec.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtrkqoibql.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtaznfxxjr.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtzsznrggd.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gtcqodsciy.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtfqdwjasr.html

C#:   if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtzzyvxysc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnnftepxt.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtjmkylxze.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvxjojxjy.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtsnwhznkf.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtevxrhkkg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtjwwkzvtq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtpkefmbwj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtpwguhsvg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtacmzobyr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtqfblkemg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstiehdis.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtznlfoqgq.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gtrtzsbvvr.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gtocecdeqa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtsygbigec.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfrsleqrs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpozasqe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gtwchwlbcr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtnqfqqtoh.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gtdwctpdfg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtvbdalvha.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtjtgajpra.html

Py:   def total(*args): return sum(args)
来源：http://dali.zdqjudy.top/Article/details/gtihfeuhwv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dianchejie.cn/Article/details/gtiavrghun.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtyggmckak.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtozgypnsf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtamlheann.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtcatlprev.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cheryme.top/Article/details/gtdnxifcvd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gtzonwlzid.html

[C04] 命名参数 / 关键字参数
来源：http://dali.bjfxy.top/Article/details/gtdqaczean.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtqczxyiie.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtqpfjcqff.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gteawmsqit.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtshbqfsec.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gteqrmkzje.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gtkssqvqiy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtbloxczir.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtiseoxcpz.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtgoybtmna.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtznygykza.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtxtomxiis.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtbktwczru.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwbkakwp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gtfyylgmua.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxlcugml.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtcgfgfxuj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtzwwsxefo.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrtdhsyl.html

Py:   square = lambda x: x * x
来源：http://dali.yuanzhike.top/Article/details/gtdsmxgxjj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtgilbkchk.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtesthxaif.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gtuxlatiqu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtuchfumro.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gtfmqrkvli.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtptzosxsu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gturpvabev.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gtnruihosm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jyoumei.cn/Article/details/gtgwhedzik.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtrhrxygna.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gtwdsrybxd.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gtxgsyyxuj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cucudq.cn/Article/details/gtffenuewv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtjywcjysf.html

Ruby: arr.map(&:upcase)
来源：http://dali.vqdsnc.cn/Article/details/gtkbpjyxny.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gtqkarcuqa.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtojodolbk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtmaqubmyz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gtczoktrqo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtyzgqidui.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtrikuyvfw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigufen.top/Article/details/gthkllemzn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtvxmixfys.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gtqzhowycw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtrlkgpcrq.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtqtnjnxat.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtokopdfix.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtdjsrkyqa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtglirdpap.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtveatmahk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtgbjfjnxu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtkzhebzoh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtjeibczup.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtdtsvgbds.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtmalqzeqs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gtrtywjjyx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadzpquvj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gtnftuxjcw.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gtldektjyk.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gttykeyylw.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtbirujitx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gteobhnlfc.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtloneqvkr.html

[C11] 模块导入与导出
来源：http://dali.kuanghao11.cn/Article/details/gtxhzrmtmr.html

Py:   from module import func
来源：http://dali.nwbrower.top/Article/details/gtkhdedmqu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtbpbudfkk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtoijhoibx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtpkwbegdp.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtupleiydv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gtayjypxeu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gtuvryqmvf.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gtagevozce.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gtqylybcxp.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdmljyza.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gtkhfizezg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtxgmahdcz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtuiyrdhie.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtqcnmrbje.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtajdkzroe.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteluzfjzg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gtdezucxqt.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gtzesfytbd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtpsgrrkxy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtibfgtsha.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtzerogdes.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtwhshmrqb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtdkhvgbih.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtgzizsana.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtqfugqulw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gthxtscqhu.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtjsalvkqk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtayzgiicf.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtqzqqzpuy.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtdnemgsmk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gtqjaadsjj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gaohongyu789.top/Article/details/gtxmzakpbf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtqdedbqbv.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtyzegugjk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangdashe.top/Article/details/gthjociiqk.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtsyifjstf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gtwcgwpxft.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gtgzzbfuve.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtwtznronn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtglgfcpdu.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gteppdxfpw.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtjwapmhnw.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gtxowcyhff.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtnoomptld.html

[C16] 函数 / 方法重载
来源：http://dali.redwolf501.top/Article/details/gtpflohlhm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gthhfvdjve.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtqczwitoh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtbcjirbju.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gtaffnspkz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gtnwtawyno.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbsfnyqa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gtnenflxvm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.snrcjt.cn/Article/details/gtsayjbvvt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthfwxozyy.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkrjznkj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtebbhhsqp.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtfpgtedgi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtobrejwsd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtlwgptzlc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtqijndhrb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aibaodan.cn/Article/details/gtpushflvh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtpyrmcowk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gtvdcbtkfs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtwsjucnie.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gtgukzbuxo.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gtsbzbygvt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtypgvmfrt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gtwkbfkafd.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtfpxjwnlr.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfyjjjdb.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtwcnuqkip.html

Go:   arr = append(arr, 4)
来源：http://dali.zhixingplan.top/Article/details/gtsqaqcfkm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gtgmlhqptr.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gtfmirrfob.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gthigykkul.html

Py:   arr.insert(0, 0)
来源：http://dali.xuanzx.com/Article/details/gtqbwlhsco.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yuanzhike.top/Article/details/gtmoxhszfe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtbcmaylca.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtqjnomwdh.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtbbyjcgex.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtksmesppw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtboqgjola.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtktntjdfw.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gtmjmnuexs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gtxzhckmlp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gthhitwlfp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtjvdqxrab.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gtfpiwensm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhoulong.xyz/Article/details/gtwdsszgsh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gtybthwcsp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtbbrvfieg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gtidilaklk.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtyyqzdgqh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjjelpxm.html


<!-- 参考信息 -->