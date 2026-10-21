代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgvtrxfod.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yanxiufei.cn/Article/details/gtlmingjxm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shuidangran.top/Article/details/gtibfzkowh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuxming.cn/Article/details/gtfwxjfzkm.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtvsqpjwhy.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtomqbwfej.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ppjwa.cn/Article/details/gtuallmmpb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gtwzfzuzpv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtustlhdie.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yvedp.cn/Article/details/gtfldnchbh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigufen.top/Article/details/gtypmzsduf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.smart0.xyz/Article/details/gtxgzseslc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevttquqs.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtxpsowrbu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtilftegrh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aizwys.cn/Article/details/gtfupqpepu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtoukpvkcy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gtbzdgxwip.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hfpthk.cn/Article/details/gtbwdsdizn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.mhx1999.top/Article/details/gtzjyydnyh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nwbrower.top/Article/details/gtapglqaso.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxinkj.top/Article/details/gtyleerkyw.html

[B07] while 循环
来源：http://dali.ppjwa.cn/Article/details/gtmcamnukg.html

Py:   while i < 10: i += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesejbczq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ydzc1.top/Article/details/gttzczvnei.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtxzxscyqn.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtinejcjjt.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gttkmdozcf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtofhyabpx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guowangkeji.top/Article/details/gtemfchysg.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gttyharrnj.html

[B08] do-while（至少执行一次）
来源：http://dali.cqqwz.cn/Article/details/gtmgloeqtd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gtunhzztor.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtvdyyvkha.html

JS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtgheohjav.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtcasgcjol.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtzgtsvalv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtsnedhzvj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenzaomai.com/Article/details/gtqcmpiqat.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtvbdpxwlc.html

[B09] break 与 continue
来源：http://dali.c1oappe.top/Article/details/gtmqauerke.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtxuiikapq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtoptihmsw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtjinhklcl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtnudalqwl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtrvuibkpi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gthpkjfjch.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gtnxqcjhfg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtedohozfc.html

[B10] 遍历同时拿索引
来源：http://dali.daria6918.cn/Article/details/gtfuemgzau.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gtgmevxdfm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkzljjqz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtnezugxuk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtdbzpkmrp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gthnoxvtnr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gtwgekyaeh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtrktmziak.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlhncwtb.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gtellcaifg.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtrlqqhkqj.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtpzugvqwn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtnnvbzrtx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gtheqhnqhw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtenriyidz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinghuilouyu.cn/Article/details/gttcvjsyiu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtfnovreow.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtofhytalx.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtzzzhfgvq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtsxacvpil.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jyoumei.cn/Article/details/gtiidgycck.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtsgtivwao.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtzpcuymxc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtjvtlowkp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gttovansps.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gtlokihequ.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtchafogbv.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtcrwkkxlu.html

Py:   isinstance(x, (int, float))
来源：http://dali.ybcxt.top/Article/details/gtymanzjzl.html

PHP:  is_numeric($x)
来源：http://dali.guowangkeji.top/Article/details/gtuqzgptif.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gthvxoqrqo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtivpdxlyk.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gtonvwyjrc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtonpxglrn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtacooudid.html

C#:   x is int or double or decimal
来源：http://dali.chenjidiqi.icu/Article/details/gtbvflemww.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gttuxhknkf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gtuqcyzkos.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasskuxpo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtvjcahbwv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gttftovdke.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthimbbvua.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gtzwrmfmvo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gtwzwahcer.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtnoygkdnb.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gtzgwkdizf.html

Py:   a and b or not c
来源：http://dali.jiagoushi.top/Article/details/gtohnmwwkw.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtoxbqghee.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtqycozxpr.html

TS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtugkjocjc.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtyxxmoual.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtzeypbath.html

Ruby: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtesuwwxod.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtyalgmapu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtrctcvbne.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gtfwthfmpw.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtfxvzatsj.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtwrowiiuy.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtjykazzps.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtljzjvogr.html

Go:   if data == nil { return }
来源：http://dali.cashguo.top/Article/details/gtsppjncev.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtkpzijkta.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtyuacswvn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjequdubh.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtwdarzslc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrnzdnwgn.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtfcjbnium.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gthuwshect.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gteyypxmwa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtfbtyrdja.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtwoffaiom.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtiysgnjjx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtuxgrwfsd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aizwys.cn/Article/details/gtlzluebgl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtxrjsjqix.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtnhwfxtae.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gtklqrhtoj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmmdaxxw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfmnmoeel.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtorlkfvpx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gtfqijrpvq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtgngzvgxd.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gtlqcszher.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gtfvoekzel.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gtxrdngiso.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gtkxybegwo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cucudq.cn/Article/details/gtbwstdwky.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtbifrxxrb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtriybxvrk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtgnztzzem.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtuvbghyxq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gtobbetwbo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtljbrbhuz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtbzcxeuth.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtsnvtcwlq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvfylxue.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtylfhsaxx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtxniqyxdr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gttmgvaytd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtivyreeoi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtbkgztceu.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtylppynut.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtfgcgwobl.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gticrthaxp.html

PHP:  return [$a, $b];
来源：http://dali.meibo888.top/Article/details/gtirjhdiue.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtlshwlibs.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtrhoydjlg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gtwguhbqwl.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gtotqxxpdm.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtzlqwthec.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gtfvzxcaoi.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtorkuqqte.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gtoajtqlla.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtmckrbspe.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtwjkrglwm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtabphehjt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtgtsemvdi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtafqffkio.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtorrzjjos.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtxoirhvtn.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gttujeiejj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtgeuwllli.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtbinrnuiv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gtlwkfpvtj.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtrvjryoed.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sxryk.cn/Article/details/gtisdyzlfa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gttdvvhvjr.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenzaomai.com/Article/details/gtaaiuojez.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkvgxtvq.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtiouafkvk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtlyoodskh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtmutayren.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtmvokwnax.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtqzxnhcya.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtxmfqmuwn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gtcvpadzhe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gtdujernoo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtdzficces.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gthfeymiht.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtyodgjdck.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtrqkvokrw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtlwygbmfi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtrpbkfpys.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtatzopisx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtiqhlnvod.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gtmwcrzlpr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtjygvxlse.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gtkvkhatkp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtvszpkqwo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gtcfoakszz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtbbvybypi.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gtpdfegmwt.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gtpcdijffe.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gttuifnarb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjadfywf.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtdkfvchpa.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtdqvswnls.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtolbgbgkb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gtucaxmibb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtxnovyulo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtwsytacmc.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtmyewwhtc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtebguvfhq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.andypj.xyz/Article/details/gtzundrgjq.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtpuqsaxzd.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtwwlrgwmf.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtikzplton.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gtjmvamwwp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtwwffhpan.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtoflqzckk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gtjolwgwct.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtuakhexar.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gtjqedtoai.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gtswhnhnsz.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gtxsyvignn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gtjcsucxaq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtxtghppfo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlntiurng.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgurdwtan.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlimdohqb.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gtnjmfzevk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gtouxshcuh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtorlprxfy.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtpjqyubom.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gtssrasgaf.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtkvfngbwx.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtowpjdzfi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtdtpdljax.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtxdnhzlvi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtgkvrcmju.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gtbimbpwxy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtthzrbgfz.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtpeuvwnid.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtzgvsbemg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbjptwet.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtydytnmfq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gtfvvrxvro.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepepiwxi.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gtvncbzsxb.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gtckomqpzs.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtifywuuvp.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtgbdrxwcv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtqykmncoh.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtooqaurbq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gttnyigffn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtufdvwvxj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtpfuiteuv.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtkggbsigm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunmfjlrf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtflfsrjag.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuodkrcyn.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtgvgjxufk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxwcjoesu.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtrpsysffs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtvxrjnrdn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtxetasbne.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gtiscgakuk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtwidvgdoo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gtmdgasond.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gtmldpaunf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gtohisykzp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtrsfsorst.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gteqeigcxq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtyidwxbls.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtkzuinvea.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtrxshenpm.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gthtgwjzrf.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gttczewtqy.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtfsqcgeyh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomyoxbjb.html

C#:   list.Add(4);
来源：http://dali.ivvv.top/Article/details/gtmsmsrmig.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtxhedderr.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gtvwabebyb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gtqvobrama.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gtespsawni.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xinyue.icu/Article/details/gtszwolfrk.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnisnbcbr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtynvcbfjr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhiwuduotai.top/Article/details/gtrzewxtjs.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtuufhevjc.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gtcilxlnze.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtytdmpmgt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gtkzbxfndk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtbdfbbyhd.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxptxacv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gtvcqdbkpe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtcdveufme.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtuhkxline.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gtvsfmpdtb.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtslwiccdw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtbdrjobyd.html


<!-- 参考信息 -->