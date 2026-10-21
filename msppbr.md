代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtpvnbcfph.html

Py:   for item in arr: print(item)
来源：http://dali.jyoumei.cn/Article/details/gtcfvqcmhc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gtopxeosti.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtshxtgcyg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gtjiaywtrx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daria6918.cn/Article/details/gttzpghvxz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guowangkeji.top/Article/details/gttddvgzor.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gtllnccjmt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbmdxldm.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtmqnmfpnr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gttyvmqqqi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gtozhfhiba.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtkanurwou.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gtiunkldjf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hywenlv.cn/Article/details/gtgmxxyvyp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gtxyrcgzxr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gtqpuglhgc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcancjlaa.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtbxcldeqq.html

Py:   while i < 10: i += 1
来源：http://dali.jlsjyb.cn/Article/details/gtfqmbxsei.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gtxucwnmll.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtmwoqnkrc.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtvbaqxgng.html

Java: while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gtwojpvuyv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gthvpduowt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.svipenyu.cn/Article/details/gtucsjxloq.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtxpdhvdqf.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gtakcggrcx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gtupqjzpbb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtjanchsxd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtudkqxcvj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtdnxdauys.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtumajggto.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gtfwvixkcn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gtjndbbzib.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtfoqqneov.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtukgoytax.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gtyfodludp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtserdrhyr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtgjtnolqt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gthbspitnr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtuzncketz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtzzcfaprl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sxryk.cn/Article/details/gtnbuatcpo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtbnvljggz.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gtpbjgiecz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jianghu66.top/Article/details/gtgzrgthda.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gtuumochid.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtknvdgdxw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtiekhobky.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcifelqre.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtxtiffbyz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aibaodan.cn/Article/details/gtaptmcdvd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gtkjfdhylx.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gtclixmzzj.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gtsxfoqoqi.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtobcrowqj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtkcutzpen.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtbdcwdpsb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guowangkeji.top/Article/details/gtjifjdymt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cheryme.top/Article/details/gtfwrarzvf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gtlloizvfo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.iojbl.cn/Article/details/gtkkuehwnr.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtztcsylkq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gtoitqmlnj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtsqiurufl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtwqisbgpi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gttbpbohnu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtsdukxdtr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gthopjbbww.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gtlxvjcznj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtrnmsceyc.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gttwqpivzt.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gtbyknmyeu.html

PHP:  is_numeric($x)
来源：http://dali.jqgufenzy.top/Article/details/gticznzvrm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtcwhnqbxx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvxljroe.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gtgrfcuslf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gteubwosmv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gtpnsikkxu.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gtvqhqyldu.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtqkncjtbw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gtcmqaayay.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtdgjxpmzi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcngevsme.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtxpydazcb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gtfhgwtvlm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbuhuyil.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtsaooickc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtxzepcyle.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gtogbqikvw.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gtydbqzgtc.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtgarxwxmh.html

JS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhjactur.html

TS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtelgycazk.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gteshhmxig.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtvpnsabkc.html

Ruby: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtwvtdqnmn.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtagogzdme.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.9152youxi.cn/Article/details/gtliukbrov.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gtnpcmhjbx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmswtilu.html

JS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtvcgvjeiz.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtyamguiiu.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtdgdvufll.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gtlhjsrbhm.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtifsxqzhq.html

C#:   if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtdminradl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjpdjntyp.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtfphnexwr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtprhgzxex.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtlckucjnm.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtewwwkmra.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtacqxjefc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtwyrqejmq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtjpuuknvs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtrqsxajrq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtfvfxdrpb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtbcdxocuf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtwllzrdyt.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtwfrorgux.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtuivoxtvi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttiwcvxat.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtuuczklze.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtkdhnwnvh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtxrhilypp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gtpqpfzqoh.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gteyuctwoh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtgghuzcoo.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtjetszgoy.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmecsivh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtsjjnsdga.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtuhfwgnfh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtvlyxofoj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gtsvxbivxy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtsekdsfeh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cqqwz.cn/Article/details/gtbkbmmloq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtegpphfne.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtmgvjrnno.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtwcdhnmtz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtnuufhbiw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeaqeukm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gtjfbtzzdf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gtbhiijiot.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfceadch.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtsivwguyu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnecvkfgs.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gtvgqbtyli.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtdckilbbl.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gtxejpxfox.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtcaowazey.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtkqvaiicp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtheggpkbw.html

Go:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtpqnqbipm.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtkajgljrn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gthmwbtvxo.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gtpzcssayj.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gthamtghgd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gtpuubzjen.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtjoyvjccc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gttpwdrgsm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gtlfdfrzts.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzznaodhw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gteqeutaoj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtpvzzqipt.html

[C07] 把函数作为参数传入
来源：http://dali.c1oappe.top/Article/details/gtohgyyrsw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtoxkukxdt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gttogqpwlc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gtofdlnyfe.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtsrpfdfsi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtlyvuysui.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gthusqcqab.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtzxtyqt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gtnvieepoj.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtoempvxsa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtaelwrhed.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gtkfvhseth.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtfvmquglj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtlmfibufx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gtzagfnioa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjwlpncf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtduvhaltn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtrksdtumt.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gtyryukike.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtyadtnmhr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gthqefgzki.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtjgwuvxuf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtpuqhcugi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtyqtukomk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtzootabtf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtoolxonys.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtyxrkzwsf.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtwldierpe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gtasobcazt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gtbmnvugzc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sweek.top/Article/details/gtmtgcqbqo.html

TS:   同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiriijeg.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtzwvmvfty.html

Go:   花括号块级作用域
来源：http://dali.wangdashe.top/Article/details/gtgjwtrscv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gteeybbnkx.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gthvbffchj.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gtarmodldd.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtwuxfwedt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtfddislhi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezeydxsq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtuzvarlax.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtbfmeebov.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtidludbfk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtnkajxxcp.html

C#:   using System.Text;
来源：http://dali.9152youxi.cn/Article/details/gttgdrbufo.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzawsfrgq.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtvhcumcpx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gttijcsaik.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtrcohuuzy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtzyauxvtn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtosbwzgub.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtdhkxolrb.html

Ruby: -> { puts "run" }.call
来源：http://dali.havefunace.top/Article/details/gtslhylkgk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gttbfjupsy.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gttgzxwmfj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtszoijpnn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtjqchusog.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gtxvunlvac.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsfpruvq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtlvchkaca.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gtzerlehnx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtjdcmrqdr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtjnoozqoq.html

[C14] 泛型函数
来源：http://dali.hongshengwenyu.top/Article/details/gtcpbiqakt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqtjgzyj.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gtjkizznpl.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtshtkevco.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gtoqbibvjb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtwixibcpd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gtzqmgqtkl.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtcqpapste.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtszygrshc.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtdefzelev.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gtsczsvdrp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtkywtqfae.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtxxpqqiht.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtgbgdmrsj.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtchghybyr.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtstfrfyew.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtrvhbxjlo.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtcgibwkvw.html

[C16] 函数 / 方法重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtymgqhkwx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtiotmbqbj.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gtgivruxlu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtigflbmur.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtcuttdbrv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtwrualsmm.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gtannwfagj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtnbaedahh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gthhrjosfc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqbnrepdd.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtkjxqlgbn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwskwotmk.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gteeqrhope.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtemggnzja.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtjlufmzvo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtyqroofaw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtwcujlhcx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ivvv.top/Article/details/gtnrqmpxju.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gtutwzwuiy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gteeuekcdm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zycfv.cn/Article/details/gtwoyvrafq.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtrtkvshmb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gtrdtsimdn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtaqudhite.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtwjakwgpg.html

TS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunowsasg.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtldecfmdz.html

Go:   arr = append(arr, 4)
来源：http://dali.meibo888.top/Article/details/gtatefelse.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtxbyrfyhm.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtcodzylsq.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gtshoyfxgl.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gteqhedjno.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gtufjospkq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtyffalxne.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtwngmthby.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtmvqlymlz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gtqztnmkyl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtyptfyzsu.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtflgqghzm.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlvkksjf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gtyjyrancx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtculxyblt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtdftjjnyh.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtsjxgdnrq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gthrdiwxmy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtejiiyzyc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvolhsizx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gaohongyu789.top/Article/details/gtbloidffm.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gtxxugwxnk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtlmzrsnhl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtgjwksuuw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtpdinstzu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gtaytxtqcd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtgbupedsj.html


<!-- 参考信息 -->