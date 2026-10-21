代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtwrotojxt.html

Py:   for item in arr: print(item)
来源：http://dali.shzxlz.cn/Article/details/gtpfxcnrrn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgufenzy.top/Article/details/gtlrglkjba.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtievfulcd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gtikysmipz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fengsongda.top/Article/details/gtclmjvvew.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jianghu66.top/Article/details/gtafthqkad.html

Ruby: arr.each { |item| puts item }
来源：http://dali.feifeiyinyue.top/Article/details/gtymmuvjwe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gtpaxbkctm.html

[B06] 遍历字典 / 对象
来源：http://dali.nanxinkj.top/Article/details/gtilubbehy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sxryk.cn/Article/details/gtguwbpeln.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkngpxbex.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gteysjkezd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtdfrmtvtz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangdashe.top/Article/details/gtnbxnvyrh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.mhx1999.top/Article/details/gtsqihtova.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuxming.cn/Article/details/gtgxsqajdh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtfffsqtwj.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gtvzwqzyfh.html

Py:   while i < 10: i += 1
来源：http://dali.zdqjudy.top/Article/details/gtzsygppap.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtbnsysqpv.html

JS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtdmaacaoe.html

TS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtzzvourka.html

Java: while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtcwidmdue.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtcffmqnec.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtyyaisoxd.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtvyzmbkwf.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgufenzy.top/Article/details/gtcabcmzon.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yonumen.top/Article/details/gtduqcicmh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtqucrywhr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtlcmjashn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtrpmhqgxc.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtdzswpiqp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gtsyflqeml.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hammf.cn/Article/details/gtequhplns.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gttdyjxsmu.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gtyiumvfls.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gtnqxftjxy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtyexlztxd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtiduripeu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtystibotu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtprcdcbzx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daxiang520.top/Article/details/gtbawahdjs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cqqwz.cn/Article/details/gtgskjrhwo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gttrfwpqvn.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtlmfenyxk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shuidangran.top/Article/details/gtuyjlbzay.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkirwdbce.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gtkubvrduy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtzswkclhg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gthnpduast.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gtrjxperuh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtmlvxtang.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gtdlcwnlgj.html

[B11] 生成数字序列 / 区间
来源：http://dali.cashguo.top/Article/details/gtyarecwnh.html

Py:   list(range(0, 10, 2))
来源：http://dali.jianghu66.top/Article/details/gtxyynwfug.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gtxkoublvk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtpsqqicxq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtwrucarxi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hammf.cn/Article/details/gtxqmtynzw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhiwuduotai.top/Article/details/gtdxlmpmyj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hywenlv.cn/Article/details/gtmpisnqko.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gtewhucnzk.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtifxsdnko.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gtmyyygqmt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guowangkeji.top/Article/details/gtrjqoeyup.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvnmynof.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtnikwdfpn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtidateyfn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gtappjzfpk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtnswhabrn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gtwepbiygx.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtoxbblklq.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gttemahjll.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gtqakwchjd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtfkhrmrws.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtwygpyzsg.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtukawsfpx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gtvgkvtmvq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gtmxblklmu.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtapnniidw.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gtlwelatdf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtlmxfctpw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtplgewibx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gthcadaaqe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtmjqplwwg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtgfueoywh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gtskehvkqm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtwjunbkut.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkbxeizl.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gtrqydnhna.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gtrtnyzwlo.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtswohbzrn.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtbkozznvm.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtwliuoech.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gthpjsjfhz.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtfulzramo.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtrupggybj.html

C#:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtsshrnzzp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtdrcalfhk.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtqetrlnoi.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gthynjllsa.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtcapnnezo.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtrydtcjxj.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtcvorprdv.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gtdytqnygk.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gthyrxhyfp.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtberoiunu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtynfmcono.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gthbsgoltf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfudldek.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtvuwigudi.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gtlwnjajcu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtfqdschtd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtjdqysljk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjndmlasm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtaqeigppn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gtsqeralon.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gtihmitxpv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtbytdarte.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtfwijkvdy.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtgtxumswo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtwveemken.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtyrhpqbnh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtvubpwtpy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtmppzjers.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtwljblwzd.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrqpqtmj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gtskkhoixl.html

[C03] 可变参数
来源：http://dali.sweek.top/Article/details/gtejxqkqhr.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtktfdjpow.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtscmbbcll.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcynpriqn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtgliaexig.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gttkrhoysb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gtufngasbx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gtwtmqawkz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtwuhcxzmd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtvkhstobh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gtkmqfhhrr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtqzwrcqii.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtfjvcydqp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijxkruwv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gthnvypgdz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gtxrpuisyb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gthzrihuuf.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtjftacgkk.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gtmhsisisy.html

Py:   return a, b
来源：http://dali.cucudq.cn/Article/details/gtjbxhbkvr.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gtkonfgofj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtqpwvloyz.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtboeckupx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gtabzaxxhj.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtitkqgqcx.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtsxlyvngm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gtqbmbzbwi.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtbdpznaxu.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gtozjvfxuz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gthelvaqtg.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtjiagehls.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gtpbevdxpy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtvvewsbka.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gtuiccopuo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtojimtfbo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtmyudmadm.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtxnudbdpt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gtyrrtvblm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gtrslxwdzb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gtlkfvbdmt.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gtrxmvfjtl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxkoacei.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtwomvwfga.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gtfcrvkzzc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gtktbyzyyk.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtjnycryft.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gthixgchtc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gthcvocsmc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gthbjulpts.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtdokyunvj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtmnunpyyc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.kuanghao11.cn/Article/details/gteaaxaqoj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gtedrwegzq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvhwtbby.html

[C09] 递归
来源：http://dali.shuidangran.top/Article/details/gtegrfdgse.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtsnuowmbt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtltfyjhqi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtkrvsxxan.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtfzjcvcdh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtaodkkbsk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gtajxlndzu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtllnmdmlb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gtauncbwop.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtzqdofplq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtfrfyfwcb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gtlhvgribp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gttkilqbws.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gthmflfxsh.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtwsdrwxcn.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtjpeexmqf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gtktmpwrze.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtkvwulhwp.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gttmummiaq.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtfbzjndks.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtefpvwltx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtxwbwcxlx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gtcqvugnow.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gtvzwgjyvp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gtnhyirxxr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gttpogpnmp.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gtxtdakemo.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtdhgbgdws.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gtmclhsdog.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshppsvue.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gteoxrosll.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gteuozditx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gtslvhdvul.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gtckzzdhez.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfatccza.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gtylhzvbva.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtgmggdxrv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtgrejanuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtrhapynlq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtcblinawo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtdwmslhxi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtgtbhdmxd.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtqqfgcarv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtmbyyadhn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gtzvtvzbqi.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtctctpydj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yangfankeji.com/Article/details/gtollhdptk.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtbvjdidlp.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtgojmecfe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtqammiyou.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqbpayrdt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtpnglsgug.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtpswqsqub.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtjtkhykcv.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtozbhzwmj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtogaxzxra.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gtiromuusf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtsljqmfmm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmveeerzg.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljjairmz.html

Go:   // 无解构
来源：http://dali.yj20258.top/Article/details/gtgdvkprdp.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtqrzboxsr.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtokznwdtj.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtzuwubkzk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gtxuyoqwab.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtpngdujjj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gtmczhnfny.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenzaomai.com/Article/details/gtshpjvzxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gteahkieqh.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gtyfecprpj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtvojgaooi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtiosgpqoy.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmkherivr.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtvnzattws.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxlilxjdo.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcpqljnu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gtsnmfanys.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gtujpokwee.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gttwwmcvbu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtthpwyrlr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gtlcmlhiqq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtpkaewnoa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gttfrnrjpl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.c1oappe.top/Article/details/gtvscflvpg.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtyjouwdbc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gtnwzrapin.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gtyshizkes.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtinwjklsq.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtunpkqiti.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtwbapukxn.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtpyatbpnc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dianchejie.cn/Article/details/gtpnmbqwte.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtacbvgoyy.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtxlaknnvr.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtdsjmazvo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gtbqdvyfkw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtgobpixiy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtguerzwyk.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtpygygftf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gtqwrhggfj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gtulvgbqqu.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtgpobxrdd.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtzvjhvuoc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.316326.xyz/Article/details/gttqigjjjw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtmrtbxghe.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtempxpkxj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhengqikj.top/Article/details/gtkunfsvny.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtdjkwqeeb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtlxkxrofe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xziqi.cn/Article/details/gtoxfuyjko.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gtanxkhjcj.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtvykieuic.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtmcckyvur.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtmfjzknsx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtxmxfmzfu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtnrqdbptk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtefkqcyvp.html


<!-- 参考信息 -->