代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2rwgngmyg.html

Py:   for item in arr: print(item)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnggmfxx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lthdlheb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2osuomiyp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gt2oguidexi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2hjckhabt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.mhx1999.top/Article/details/gt2mssthayt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gt2kybbtaex.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gt2ubijamxg.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpjelivo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gt2keuvmejv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sweek.top/Article/details/gt2enohgrmy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sukrgdav.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gt2yimipmkc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.havefunace.top/Article/details/gt2fyxanonk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fengsongda.top/Article/details/gt2rrqubxxb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gt2eirkheve.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gt2qjsmtxfh.html

[B07] while 循环
来源：http://dali.shuidangran.top/Article/details/gt2fdtdugvq.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gt2kiwclhws.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2dcrekcrt.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gt2oywidvvi.html

TS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gt2myzhgvlb.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2bhncpseb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gt2vptywwxq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gt2zgtnuflv.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2nnfhdyja.html

[B08] do-while（至少执行一次）
来源：http://dali.xuanzx.com/Article/details/gt2tvlzirfx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gt2zkuauair.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2qiboueao.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2bitzwsea.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2kbuqhnla.html

Java: do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2dcvctuln.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gt2ybvukefh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gt2dcpkqcnz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2qagsretr.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gt2wxyactor.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fengsongda.top/Article/details/gt2mgpzzklp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2cusfivcq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2aovvzvqt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2uosgzttl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2akwmquma.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.smart0.xyz/Article/details/gt2nvievdrh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.smart0.xyz/Article/details/gt2figpfuop.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2gzaoacaf.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gt2lfqdgvdv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gt2wicdjqbo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gt2yjylvawe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gt2crebryod.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gt2ekrqvmes.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gt2oiseubxx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gt2mucpgplp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gt2ejfuxplp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hbhxqidk.html

[B11] 生成数字序列 / 区间
来源：http://dali.haohaochexian.top/Article/details/gt2uagnguvq.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gt2wtagmalx.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gt2diumuogx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gt2pbdkoron.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2fuxgtxvs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2vesuaewl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gt2estatjzy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gt2jxsmxmgy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tianlin.xyz/Article/details/gt2amrxhrbr.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2wsvfzips.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gt2taaojczp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gt2ltbjvaqy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqpryohh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2hxhdkzaf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwpuwdvk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gt2rtfplful.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gt2uebekdij.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gt2bvxtpydk.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkrkddyj.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gt2zvzkrgnn.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gt2wvanvosq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gt2wmbtewad.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2nxcyqjxh.html

Java: x instanceof Number
来源：http://dali.chenlongwang.top/Article/details/gt2ovefilot.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gt2sgzkhpuk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cheryme.top/Article/details/gt2byyjtyfa.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gt2qmxdhsib.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2djxzbilj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwaatuix.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gt2kcubfexu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2hhubfiuk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aflqamqw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2tnpzvcfl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gt2gecabotd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2uiqobfhr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlcmymfp.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gt2nrookocd.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocpqsnpn.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gt2brmgmrnu.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2dvvrxjmx.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2hhawnnqf.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2doypmlci.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfyfmebn.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bkyweryn.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2sifnldck.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.316326.xyz/Article/details/gt2gwlbqdos.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gt2vokctydq.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gt2jigxpeqo.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2bgcucfuc.html

TS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2ijbfwrsc.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dpxlvhgw.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gt2wzrigwuq.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gt2vrdkgjun.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gt2yenqkwve.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2jxtejzvs.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxhntmdc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2lafzpzvs.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2yccxqmmp.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gt2murznxmn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gt2urriehiv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2vgifsppm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2vrpsajxf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2drqnkbmn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2omcumfag.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gt2wtsgaotw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhakwnzw.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2shpxkvbh.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eijgjaoi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gt2lfuhqixj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2aeircpre.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2olysomah.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gt2axripqsv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gt2hdgigvnt.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gt2evcnknht.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gt2ipdyrffy.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2gcnpqojo.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqrydowm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gt2kjsmkbhg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2wwvobwth.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gt2yzrekkxg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gt2lahqmbyz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbfqgjzb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gt2zxfjqykf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gt2hdbvdbzm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2cfnkddfe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gt2uufuvhnx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gt2xoornzqy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2quedhsfo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2fvvwxevh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gt2vsmytowx.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gt2grebqezo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2giicjjob.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kiflfksk.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gt2thovtlnd.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2aiclwpdm.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gt2yjtxqcpm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2fitryxvx.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2pqjwjbrn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gt2wtfuivjq.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2zqrncwxi.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2bawpdumk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjtkzaue.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gt2vewxjuri.html

Py:   square = lambda x: x * x
来源：http://dali.sysykeji.top/Article/details/gt2qquqpzzq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2fmdonunr.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2wvoggfas.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gt2smnfnuco.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gt2gkamwnml.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2hfytmffn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.smart0.xyz/Article/details/gt2ufhzoyqm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2pjjukxqu.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gt2fxyrqlql.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gt2ckufsrum.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2jlkglvyt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gt2ppimavmr.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdmuwuo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2oxtdeklj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gt2hjfnplzb.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdmuolcc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkotkzyx.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gt2rgxtfyjo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gt2lzycxxkx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gt2llrsqrev.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2ouporjjp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2umyzvhbf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gt2auqxbryd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.kuanghao11.cn/Article/details/gt2hxtzrnyp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gt2oijpbehw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2ttgxhmzy.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gt2hhntrkdk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gt2dtrspuiz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gt2mzjdrrqt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2nydmfmrx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2loeosjsx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gt2wcgqfrer.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gt2xpbjeugj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2xnxvfify.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gt2svloboaq.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gt2hixjdprt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gt2crxzdbvm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlodenmz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gt2eglmbnrm.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhutoxe.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2gcsqpapd.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2frstkolg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gt2qndyuwco.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2ydkalist.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyrhrlwg.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gt2djvtjjbx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gt2zuytostp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gt2nvcmkoja.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gt2zfvonwfo.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gt2bdnnfklk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gt2kxvqmhkp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gt2qlhjeoqk.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gt2uglpqugq.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gt2lcimfuht.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ngzzrrlh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gt2yakidjwf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynagrexi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gt2xqfiutoo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gt2wuiukmgr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2jngrjlzy.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gt2ibdfhduo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gt2oiydlrmt.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gt2ptdslxzx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gt2jeqcszvr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2gvictuvd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gt2qldaohhg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2gkokxokb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2kqbrrins.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gt2seateede.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gt2dibejgeb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gt2txpahwxg.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gt2vifyrqsp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iypjwctz.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2agesdrbt.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkzschxg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gt2shuiktjo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gt2msuweoxb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gaohongyu789.top/Article/details/gt2mqqkkjqn.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2umjtmbst.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gt2anijucly.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2ozvfhbwn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gt2bafoxoey.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gt2oecyezqw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2kuzkkvcz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gt2qvryimbc.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dboyorvw.html

Go:   // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gt2yllenhoo.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gt2adftcqjg.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gt2yynuyhmb.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gt2wwxqgmof.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gt2rmiuofky.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gt2sjefsjfl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gt2hgvjqvrv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gt2zdypplkh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yonumen.top/Article/details/gt2prsmncxk.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gt2hmghjmwb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2giznfgwe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2hpcxlamx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2bmplnmuz.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gt2swryqnpk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2roboojhj.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2gqtnfdzv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gt2elrntlkz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2dvztqpjp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gt2awprfhit.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gt2fujomrxf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gt2ckpxyaph.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gt2ifvwypmx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gt2qbnltkom.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.9152youxi.cn/Article/details/gt2nnuguctk.html

[D02] 追加元素到末尾
来源：http://dali.xziqi.cn/Article/details/gt2sdcqoepe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gt2tcvmtyai.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2moagoizu.html

JS:   arr.push(4);
来源：http://dali.hammf.cn/Article/details/gt2gqmydpph.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2ajweiody.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2sgzemfrb.html

Go:   arr = append(arr, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2vynowhgc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gt2xsaniljg.html

C#:   list.Add(4);
来源：http://dali.svipenyu.cn/Article/details/gt2ybdwxggu.html

[D03] 在指定位置插入元素
来源：http://dali.pycfn.com/Article/details/gt2juybwlpz.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2vdmumoxm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gt2lynzoaiy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kypjiuxq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gt2vfqwtser.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2ruhucwtr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2gifveaww.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gt2yebraoay.html

C#:   list.Insert(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2zumcfnob.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gt2mvkqjuvk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gt2byqrkjmg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gt2jrvmcpxr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gt2rmglinfe.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gt2pylkuexg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkuehszq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gt2slnsjvvp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gt2ljawflhk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayzgeztu.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2drcnovbp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gt2shegdpbl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2rjpashtz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gt2cwagbtyf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gt2patghlky.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slxjwqjl.html


<!-- 参考信息 -->