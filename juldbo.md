代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gturtfblzh.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gteebbvxee.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcdfgbimy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gtquswrweb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gtorbhxqni.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yvedp.cn/Article/details/gtsqwoytia.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gtmhgplvhf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aibaodan.cn/Article/details/gttnujzqiq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gogol.net.cn/Article/details/gtsdtqlnzj.html

[B06] 遍历字典 / 对象
来源：http://dali.daxiang520.top/Article/details/gtiapmrytc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gtutbmbtti.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gtxqnnhrur.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtxjwntrkd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtntnpfmji.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbkjulyeb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdnhifkf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtainejdth.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258.top/Article/details/gtgmhdihhz.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumcaroub.html

Py:   while i < 10: i += 1
来源：http://dali.gogol.net.cn/Article/details/gtgwywcpsy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlupkunwz.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtywwfaool.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvadboxtk.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtodhzibwu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gtbyvcqjee.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cqqwz.cn/Article/details/gtivknhnqc.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtvgrgjvnh.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gtxlkelfpg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gtbroebtvk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuanzx.com/Article/details/gtyygirbzf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtzydowlgs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtibjbikeq.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtyvjiyguj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtgoddiaaq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ybcxt.top/Article/details/gtzghnujpb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtcgombwmd.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gtjljqeemi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gtpwhlflfb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtvylajayo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtotuewvgu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtejigault.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtcdveblhj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtuquiaibj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.316326.xyz/Article/details/gtntqtamme.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtwzhwdmpi.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtspzybruq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovyfzema.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gtqhuidpsv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtgayhepsf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gtccjsowcl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gthnagoqgv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtsikxlwmb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtiuewwpmt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtruxgcprh.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gtaygvdjnd.html

Py:   list(range(0, 10, 2))
来源：http://dali.gzhubu.top/Article/details/gtwtqcyooi.html

PHP:  range(0, 10, 2);
来源：http://dali.ivvv.top/Article/details/gtxjrzdecs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtxailcrof.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtmaklrejq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtjnpagyeu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gtzpxxgrpz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtxlejrmdz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gtqxrwxhvw.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcvqmkcf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuxming.cn/Article/details/gtvcygnsms.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gtcfwfjqbk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtmcoomwak.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtwtxqhuuq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtcdvmbpnd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gtpblbejlk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gthcynncqk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gtqlkihmcu.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gthxzovgdz.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gtsblypuka.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gtpefauqxt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtpwrufqhf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtrghbfede.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtskbhlucx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gtaklgawhq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gtfdqcodjm.html

C#:   x is int or double or decimal
来源：http://dali.zhiwuduotai.top/Article/details/gtnlrgubsd.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtvzovialo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gtnfuyhvrg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwhvxhiv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtmfyfyshq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gteshsdzlm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gtcihsbmoe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gtweiwwulc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtedbfkkmn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtljhqjuoe.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gtfawobeym.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gthgbwxhtm.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtejtxok.html

JS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gthfrtfumk.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtgqcycjqt.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtpisiabph.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtasqcvyrb.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtkrkshddy.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtbbatyvyh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtfxkbkipu.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpjkfmor.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtfskolths.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxvbsmea.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtqsovxfrf.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtqlazceex.html

Go:   if data == nil { return }
来源：http://dali.zycfv.cn/Article/details/gttosvqpqx.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtfslwepaq.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtskqbcchj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtluguztnp.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtpecansut.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtudsnislm.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtyahmyfzs.html

Py:   def add(a, b): return a + b
来源：http://dali.yvedp.cn/Article/details/gtkjiqqfno.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtjyrmpvho.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtccwmzlhm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtggdprzyx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtbxmnooxl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangdashe.top/Article/details/gthhssmdob.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gtisjpcezz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gteubdenvx.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gthswavqkd.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gtddmggvsz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtwetuglwq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtgtwhgpmn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtiowegosv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnouaxti.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gtthgambzl.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gtqcmcweur.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gtjlrarkqn.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gtleasffrl.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gtjfpnhyxj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gthjwandim.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtpldequfh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtvkwfvnbd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtkfnhkqyh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gttegelcgf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhdhumcb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtcadnhvzh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtoiqpnnlb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtimqesats.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbhosljg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtefttxsde.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtzamscrjk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtishtzkvq.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gthkixngkv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtxkfxcuut.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtjooygdyr.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtnspvgrop.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtcoochkjm.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawhfraxe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtilnvgufd.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtednkfbvc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gttomlauyv.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtixwhrwrf.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtragnfscc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtbyrpcvvq.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtrkxkdblj.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtblvgthip.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtktmnfcqo.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtkhxysaob.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtwlyhgjhd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gtbkinzccm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gtvviidtcq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gtmmoaauia.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtyehyxkqk.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gtbjlrtzbl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwsytlta.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gtmffeoxfc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtcvqvlpci.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtchfjrljs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gtxszwtfcu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtxfzsyuzs.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtefrrdupa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gtkkccnuxl.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtinxnzkus.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtxdqiiveo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthutppymh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gtdtpetgei.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtlpouihlp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtcxbcxzsw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gtlugiqsbl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.vqdsnc.cn/Article/details/gtbbabnjby.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtxaabsywz.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtetgejfcj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtgullbbkj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtkgbejugw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtaqckbpcp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtgpdvgagt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtefcdeipo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jiagoushi.top/Article/details/gtiveyzhak.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtumtczith.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtxjwepkwe.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtrpidggnv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtooqvmjgj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gtpbdwfhed.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtjxtuazgd.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtzacystfb.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtrggvpsoc.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtjrutqzpi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.smart0.xyz/Article/details/gtxwnxsngm.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtnwcrgmnc.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtcykaabsn.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gthyzuguwf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gtfmnonnpc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtoeodongd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gtvysmzlwf.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtvkviyacj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gtqeqbtsuh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guowangkeji.top/Article/details/gtdwubmhwj.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gtyxsnahkl.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzimnmazk.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtgrnnhihl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gtcugpktvr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtbjzhkagq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtzncprzxw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gtfpzvmduz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtkqaiejrd.html

Ruby: -> { puts "run" }.call
来源：http://dali.gotoacloud.top/Article/details/gtyugfkgge.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gttyupzjjj.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtaznvgmaj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gtgnqgalaa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtnhjqfhxl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gtigsojkvb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtkmrehblw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpogsbhf.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtbdlopest.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gtmauqbzjh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gtlpixzpxw.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtlzxnnmef.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gttrkoshdm.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtcsnmbqas.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtlnwbzaae.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gtwikkavah.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtzhfdvggg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtsoxwuuqn.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtnyaykwtu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtectldlqc.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gthsmvnmgq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtxnewatgm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtfycvwxji.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtfjjsmxhm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwjhlumlh.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gthflosvgl.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtfhxpmwne.html

Ruby: a, b = pair
来源：http://dali.dashuyun.cn/Article/details/gtzrbfqgmm.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtglcjopwj.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtyimoxxxk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtxaohfwiu.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gtegxrbifz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pengpengdd.cyou/Article/details/gtwhqspzld.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtaurdwmbi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gtbuatoqec.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gtnyqlvxol.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gtwruvgprg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtajpdvtdi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtrjhuvvyu.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbvailbj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmswwldvs.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gttukcjsmp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtukdnhxgf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtccflzsre.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtamwtjfmr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtcayljarq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gtghfndfyb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtztoqtbrt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtwetsrham.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtlsncwrrm.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gtbdqcavlk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gtmdwarxtg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.wangdashe.top/Article/details/gtibhlzxvj.html

JS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxmbzfjri.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtpxuauqug.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtasmjgeop.html

Go:   arr = append(arr, 4)
来源：http://dali.hnqzz.top/Article/details/gtlulcmlnz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gtlyxzngmw.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtnfntovph.html

[D03] 在指定位置插入元素
来源：http://dali.vqdsnc.cn/Article/details/gtoowanjct.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtajpwseve.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtjlschaqr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtofritkvx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtffxfladw.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtoqvitbrn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtzxsaftpc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gtxhcququt.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtmshztdgn.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtsctllyxi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gtsyekpgys.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezbfbuqv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gthhyzvdpg.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtpjuyliwq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtxsjacnzp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258.top/Article/details/gtyieqfvrj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtehsvqcfh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtjssqvdpr.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gtnrowvmfp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtpbgrxjbn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gtvcvofmkz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gtqpqglven.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gtnphroswl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtcfkwqogg.html


<!-- 参考信息 -->