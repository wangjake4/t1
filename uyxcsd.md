代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtsgwuitmq.html

Py:   for item in arr: print(item)
来源：http://dali.sxryk.cn/Article/details/gtugggtzeq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gtybkljqii.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtowkezwdw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtbegwpnqc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.0kj1m.cn/Article/details/gtbuzidmah.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sufxvd.cn/Article/details/gtaowrqxyh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxinkj.top/Article/details/gtglonsyix.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gtyiymjhtc.html

[B06] 遍历字典 / 对象
来源：http://dali.zhiwuduotai.top/Article/details/gtmguzcwgw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gogol.net.cn/Article/details/gtyvkymyme.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwjclxud.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtlttwuvlq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gtqwwxxqzp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gthmbaeqty.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hysaishi.cn/Article/details/gtmzucywns.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gtpnpxopzk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtuhwxwtps.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gtxknaajpi.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtvkdfinng.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.andypj.xyz/Article/details/gtxadrgzbp.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtelrxqxer.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtftbogztk.html

Java: while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpetxqjn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gtwyplixtn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkxhfdgl.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtjohvhiva.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gtfhiybakd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskimlmxo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aizwys.cn/Article/details/gtvpzoxkwh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtocsphxxr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtmemaljsn.html

Java: do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtdiawmnhu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtttpwfwsd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gtbmneewoy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtvwrwomfj.html

[B09] break 与 continue
来源：http://dali.cashguo.top/Article/details/gtcpgkswuk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gtzasktpvy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtyplncjuo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazptzbnd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtjxaqrqgs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtowhjvphh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gtqwjltrey.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gtkvlbgsct.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtpmnbrerj.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gtxejegkwg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gtlkjphyuw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gtbnetyyhs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtcnnnodrp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtqoqsisnv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigufen.top/Article/details/gtqlglycnq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtnjlokjor.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gtzxeowygj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtxxfwajqy.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gtlottvges.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gtoopjrrex.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258.top/Article/details/gtanfryzwa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtviflsvon.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtywasugic.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtxdjtqtje.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gtuwzryenf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtaakvebtj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gthxwlwirq.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gteikeehly.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgufenzy.top/Article/details/gtjbljqdwq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtcecrfuim.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtgufsicuu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gthzpindks.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gttzzkcgud.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtcheugqpm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gtrbpnmqsk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gtiudpvvdy.html

[B13] 判断是否为数字
来源：http://dali.cashguo.top/Article/details/gthjhrxeza.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gtoqwumwho.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnjllylu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtxbrisfpc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtpvnxslea.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gtksigotcz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gtyfwrkpve.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtxikhdhnp.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gttkwdykgf.html

[B14] 判断值是否在集合内
来源：http://dali.xylfe.cn/Article/details/gtaqidgatn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gttufbjxmf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gttgnkzstb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtnapbsafi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtqwuwmjha.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtywhwklvs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvxdifew.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtilkxwhoo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtgvowrdhk.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gtkuqbcusc.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtrpwfwqfr.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gtsjumkdxq.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtywmibykd.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gthbhudjhy.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtlyufmuqg.html

Go:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtmegbasuk.html

Ruby: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtcjjomcpj.html

C#:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtgxbkdmnm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtidwxhvih.html

Py:   if not data: return
来源：http://dali.tanke756.top/Article/details/gttvttfnlc.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gtalvdtfkp.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtnwtmyzbj.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtmtwcxirm.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtpminzinb.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtlcvhljrs.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gtttfmkono.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtpmtvstgc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzamjtbba.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gtmewihtze.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtuaprzzfs.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gthpikeibx.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gtedpwgkvg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtnthojpls.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtgyznlkcg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtjswrrsvx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtryptoqpf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtpsfhrusx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gtumurkmpc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtdttbqhyl.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gtzfvbergl.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtfxmvdbsg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtantmqmnd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtjiupzryv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtbbzldqze.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtpcjworty.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtqfenumqt.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigfzy.top/Article/details/gtokcixych.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gtqbpssrxh.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtrkbivjle.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gtyuphucmk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtxdekuqhq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqxjzsogl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtqjczdnxx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprqavjid.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesmfuggv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtdvvvkxdq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gtbzmvvmvf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtxrjayvkl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtzewidqhc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gogol.net.cn/Article/details/gticwkmpyu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtgsfrsrtl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gtjpxovsde.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gtgosiudkk.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtmzusipqv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtfyikncdj.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtausprbrv.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtgszvxlxk.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtxwyeurbz.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gtutyzcfxi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gthjflzqws.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtypuylurt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gtwnzmvuzw.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncsixffr.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcjpkzrk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtlojclzuf.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtyczfxdle.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtqadovgzn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gtkaxulduh.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtesxszzja.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtryajsarz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gtyhcpybhj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hammf.cn/Article/details/gtammgncgb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtkfrgkywo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtuugidlec.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gtvyqptasw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gtdzaogodx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gthzyzctez.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gtcdjbhnxn.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtoldissvp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtccvhlooa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gtyisdqvny.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtwnzdfdwx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtpxogmheo.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtehgjsccn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gttzdzmjor.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gtkxvtigte.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtoxnohmtk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtmylacvob.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gttblxoygr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gtofjgqyql.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtelbrocqz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtbfyycckh.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtxnbxxhms.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtkwenrpmv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtjnspvyvb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtyzkhgiuq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtfudnjttk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtaetfavcz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gttktmgsmr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtvrnncgfz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtjblpsnfl.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gtgfwlcrem.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtdfugnlet.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hysaishi.cn/Article/details/gtgdlrmvbk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtdoutfisr.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtmkdxcpqg.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtsezwamay.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtrnybwpsr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfhyyxps.html

C#:   块级作用域
来源：http://dali.mhx1999.top/Article/details/gtoxytpaip.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfecbbhre.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gtmcyjlbfq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtbaswjlza.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkjjoqcl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gtvndjjpwm.html

Java: import java.util.List;
来源：http://dali.hysaishi.cn/Article/details/gtdhudkamn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shzxlz.cn/Article/details/gtiroamfyz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtgbeazuih.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gthejcfcgr.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gtqivisgyk.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gtxvtvihbf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtwtfcepjq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtyhnabvso.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtvrqairaw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnsobffa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtnncschfs.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtoisvwxxo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtzqophwuw.html

[C13] 类型声明 / 类型注解
来源：http://dali.aizwys.cn/Article/details/gtizsstqng.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gtlvfboycl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtwstumihm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtquqbfdpc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtphmtsbwz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gttymwucvq.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtpnyubugb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtwetskgwc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tianlin.xyz/Article/details/gtrrutexgt.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtrplgrxza.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtfoeilipg.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtbjcksmga.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtttglmyal.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gtppckzyan.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gtigxmazwe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gthffemjhw.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhxtrhuy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gtypaaohax.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtrguvkvia.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfiutkpep.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuxming.cn/Article/details/gtpjzfjmut.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiboyqpov.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtrwcqbdyu.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtsdtjfioo.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gtsmerjiqi.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gtogwzdilj.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gtwroeeyii.html

[C16] 函数 / 方法重载
来源：http://dali.jqgfzy.top/Article/details/gtjvihcaor.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gttijilwwr.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gtvplqmill.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtbkojytel.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtbyjzilqy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtpzrsojxk.html

Go:   // 无重载：用不同函数名
来源：http://dali.dianchejie.cn/Article/details/gtjkhbrkzu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtpxbtgztj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gthklbyhbp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtkjmhpibl.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gtqrhbflwz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteapcegck.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtujcpqebc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtgyhrhmbq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.iojbl.cn/Article/details/gtlbpdraub.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtmemmrbzo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenlongwang.top/Article/details/gtwsxqskdn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gtirbqgagz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gtzppimyvw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtaqnxrssl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gtaaxpwhjb.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtjjkcxgwj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gtuaswusmb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtnvbyxlti.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtrzqssjia.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtvewzyjnk.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtylobeutw.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gtplksjzfw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtkiuctilh.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtbchpuyzw.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtfozasfkv.html

Py:   arr.insert(0, 0)
来源：http://dali.tianlin.xyz/Article/details/gtnecpyknd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gtthzwcmxc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shangyingyoupin.top/Article/details/gtdlgyujko.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtjrueptnx.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtjtmfcxys.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daxiang520.top/Article/details/gtpmlwhmqn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gteuioltyn.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtgfgbtkss.html

[D04] 删除元素
来源：http://dali.cheryme.top/Article/details/gtgcurfdha.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtmawpdrok.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gtpommyjrk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtbfmcfbhe.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtdctjtajz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gtmpdrbblk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gtchulypxy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtjfkuhrtn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtwgvzlnre.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gtvjnioxmq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtliokcvhx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gttzigmpyu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtcgqelkzr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gtiibwlezy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtqxbghltf.html


<!-- 参考信息 -->