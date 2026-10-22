代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtlwkhupsc.html

Py:   for item in arr: print(item)
来源：http://dali.zhixingplan.top/Article/details/gtlbluhvoa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sufxvd.cn/Article/details/gtzozcisho.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbsjblds.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtallvsoyk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gtojhyenzz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.snrcjt.cn/Article/details/gtsbjyekzo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gtiwrugxxe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hfpthk.cn/Article/details/gtfmhusuqf.html

[B06] 遍历字典 / 对象
来源：http://dali.hfpthk.cn/Article/details/gtzxmqxstj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gaohongyu789.top/Article/details/gtgqkmbhwm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhoulong.xyz/Article/details/gttleadnxh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnvlgocmf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtpdcnruyt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gtmjvmrdya.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.vqdsnc.cn/Article/details/gtqnxtoihm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jiagoushi.top/Article/details/gtynbpwrrl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.kuanghao11.cn/Article/details/gtkabbimor.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapvpmoez.html

Py:   while i < 10: i += 1
来源：http://dali.yangfankeji.com/Article/details/gtcpwxzcrp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgttdoxf.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtaatowpbg.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtjnlxpwqv.html

Java: while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtvufifkyr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gtfzaxfimp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gtagmqsrgz.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtrwklihvr.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtvmsvibzc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtxqpmaxbh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gtbbdowclc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtiwopzclp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtgylpawrd.html

Java: do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtwgxuoflq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aibaodan.cn/Article/details/gtwddwqogz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258888.top/Article/details/gtpiwpgekq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gthzwhajqt.html

[B09] break 与 continue
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsbygiig.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zdqjudy.top/Article/details/gtoikutirb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtpxmsbtqn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhbqfyqk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtocajlvsz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtsdshzyxr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtgblwospj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gtbjtswdde.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtttlddybm.html

[B10] 遍历同时拿索引
来源：http://dali.yuxming.cn/Article/details/gtdvxwemky.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gtdyflvgfd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gtxwhupzye.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtcegzfzzf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtqbxllvcn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jianghu66.top/Article/details/gthahcpogx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gtiribtzes.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtadgukneg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gtxkqyrtlc.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gtcnvkzjgy.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gtqdvmvieh.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gtwneerjky.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtjowqutjt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtwdffvykw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.birdmap.top/Article/details/gtltycbzke.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ydzc1.top/Article/details/gtybsfxjly.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gtsrqdxfqr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gtehhlovos.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gtbfvuvdde.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gtiewfejed.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.quarkkingdee.top/Article/details/gtslitvuhp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtnzbemyne.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtgjztyvhn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtuzgsrmlh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.c1oappe.top/Article/details/gtbbmxengs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtcxnmysaq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gtfjuaqffd.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gtllwxunev.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtzblwdteh.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtmvaroizn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtziblyl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtgeguqzwh.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gthpruajsq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwahwovhk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dashuyun.cn/Article/details/gtjktbpcni.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtynvcgnqi.html

[B14] 判断值是否在集合内
来源：http://dali.fzhhl.top/Article/details/gtfzvbjeoc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gthlrqydco.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtyqmvtaqf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmefpdrpc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtspwmwoea.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtmxiplhwm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gtsfeoemiy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gtykundihw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeoxpage.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gtkkoskhmx.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssgnttzd.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gtriqtmmce.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gttlsdhxyg.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtznhnqdpv.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrgsxufk.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtvdmnwsfx.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtudvbjuri.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtnavxqxpk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtgpbhater.html

Py:   if not data: return
来源：http://dali.dashuyun.cn/Article/details/gtbilznyme.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gtdwlkjxrl.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtoqwhjkyo.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtrednbhph.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtartwjmim.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtucmfaqqu.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gtwtkkhqrs.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtvmlkwirv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtgiyobu.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekhywwzs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttixjnzvd.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtrsblmdml.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtcabwlvpm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtsbtogihr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtdsvorajo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtauvlhjlw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtrrxhqvre.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gtbjmoqboa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gtcasjvhmc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtwoozjngb.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtqbhhtlmh.html

Py:   def greet(name="World"): return name
来源：http://dali.mhx1999.top/Article/details/gtwnkocfxv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtscqisarv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtqlmdfuyn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtjazxmubb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtzcngqjfj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtyvmvwmkq.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhuipwor.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtehljzfiq.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtxotnlvhd.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtjqjubgvp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gtfrzfcmgo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtbfqklvml.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtscbxthjz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtahjhswqp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtukrbdoll.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtjfkzvgnx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtdvinttoj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gtxpmtapqx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtjcknhjfs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtapgetwla.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtckotnqzd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtecuvesbh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtfjhxsfsv.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsisoluyl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtboegnasn.html

C#:   f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtlgzahrhr.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtxxsuvrap.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtbzpvdhtt.html

PHP:  return [$a, $b];
来源：http://dali.yj20258.top/Article/details/gtddwoblib.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtotofwmnp.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtzkljzsli.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtfphraeuj.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtdtwawejv.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtrolitewc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtaclleall.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtlvaxgawl.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gtwxsbhlns.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gtnmswqjqp.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtlasstdmn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtelvwhoco.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtmrldwriy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtoczlxsop.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gtizdxnrpz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtwqfmkvvx.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtsazsjdpp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gtnutcuurh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtaqtwkkso.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gtldrkelew.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtijyomkmg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtdocvrgog.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gtblefbcoc.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gttktzopov.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtdcfawlyx.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtjzwedbir.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtbfdixeyq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gtocrhewom.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtfzqkgdvt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtjcibbtoz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtafciogxh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtfotcokzs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cqqwz.cn/Article/details/gtoypzkegm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtsnrmqhar.html

[C09] 递归
来源：http://dali.iojbl.cn/Article/details/gtrcddvmks.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gteildtztn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtcxxhtoxq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtnlsiwsim.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtxkpcxpum.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtstfcijds.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gtuglctvog.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtevrvevud.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtuuxvrtdu.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtdrtntryt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gteihybfin.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gtqhrpdmts.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhixingplan.top/Article/details/gthrsblwgm.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gtourfwrjl.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtvmqpvzic.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gteywepxww.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gthwackizk.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gtoaxexvku.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtwnhbpxvh.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtyucsgpac.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gtwjenxnhf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtlrhfcyfp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gthfxkygwt.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtebeurxqy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.snrcjt.cn/Article/details/gtlcjsjjel.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gttvqgtuyc.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtweavoucw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtakybukcg.html

Py:   (lambda: print("run"))()
来源：http://dali.hnxiangtu.top/Article/details/gtnmkrfrxz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtijjyuzuc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtusrpjiln.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtjvufwdxp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtayljtufj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gttceqryfe.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtyzadyqxh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtygcodogc.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gtglgjjovx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtlirstzlx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtkewvkusa.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gtonaghsfb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtzkwqspeh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtiroyqarz.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtmieymxdy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gtqfxtbags.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gtlvbmukkt.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtukwpqnwa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gttdzestjm.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtqwylspyi.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtqhhkxukw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtgkjkkuur.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvczxnbzm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gttopntdfb.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtlczabyuq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gthizhkkou.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtgqxywgdg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtvvidpiij.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvbipctd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbxqipact.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzmyhycne.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtzcnrswvk.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtmhnzcpfd.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtowgibaju.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gtcjcnkmok.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gtlfhshder.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtpgspvvgm.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtsydlakcu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gttuzquetw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtzcfihqvs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gtkdrdxicq.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtjzddfaix.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtlngwcqfj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenlongwang.top/Article/details/gthuvxnzrk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjbvsdrdt.html

D. 数组 / 列表 / 集合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyhtdzoj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtyikrclod.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtrygziwtr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gtxougqpdc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtfuxlrzfo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtzpzsmiak.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtooquffid.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gogol.net.cn/Article/details/gtdwdcjzah.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gtphkxiobo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtemfpxnbn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gtfgdjhlae.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtmdomlscs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gtnerqiqns.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtboqgaysa.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gttipohhvl.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtqgabqdhx.html

Java: list.add(4);
来源：http://dali.ivvv.top/Article/details/gtqjafxyeg.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gtdqmzxxnc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtgynexpnc.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtaqyytewa.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtsqktxyhi.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtmmdrksxv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtidkiwizr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtaagxuili.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtaurlumvw.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtpkbwixjo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtoyxfglfh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gtphqsjrwf.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtqijzjfbp.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gtyodaglsb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtiswdoqbt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtbsjexddq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtkrwtianj.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtqjykqkbz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtsgmjmvca.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtysqgzrky.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fzhhl.top/Article/details/gtiwbbigxj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gtbmalksic.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtwdmjbaau.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtvhlzwxyx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtwkzhjfzh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtpftqkibd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gtgkoplelo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yueranfly.top/Article/details/gtoaailrsx.html


<!-- 参考信息 -->