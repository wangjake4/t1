代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtpqyxfdze.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwehmxva.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj202588.top/Article/details/gttcpfjknz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenzaomai.com/Article/details/gtjcywohdy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daria6918.cn/Article/details/gtulpbfhyt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gtqhgqujlj.html

[B07] while 循环
来源：http://dali.jiagoushi.top/Article/details/gtytomcvzf.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gtiqysdevl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gtnwrismie.html

JS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtkigagkbx.html

TS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtkpsdkkwe.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtfybhlbht.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxuanxn.top/Article/details/gtykkiwids.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtrdsqxlbn.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtqrakwafx.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gtpaucttpi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gtmkhmddpj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtafiztwcu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtcmsiiohj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtrourvxrv.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtrixljccf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtpskxpnem.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gtldabiebm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtnarmgcnx.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gtfzlbijeu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fengsongda.top/Article/details/gtpqxwmhoi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtvrmldiaz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtbneurlkt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtsutrqwzp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtzsotisdr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfhiiglz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gthlmjwevw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtlcxlmnjr.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gtooevxkbp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gtccavvqos.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gtoqnltfzt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtkworsxqn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtdqdffnxv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.iojbl.cn/Article/details/gtltoxzqhx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gttyullnrb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gtzubdrmsl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shuidangran.top/Article/details/gtepucrbcp.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtptnzgynt.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gtygileuyq.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gthvrtnrdn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtvixrmrfx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecrywomg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtnmduvszw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtppyjjsli.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gtknnsmryy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gtoavjdbnq.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gtythbxjxc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hfpthk.cn/Article/details/gtuipdmsky.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gtfoikxfta.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtkzuipqgi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtpnungsnu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gttonuycym.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtcdylrwpf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gtwlrrqeow.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gtcdmuxmta.html

[B13] 判断是否为数字
来源：http://dali.jqgfzy.top/Article/details/gtkgksltko.html

Py:   isinstance(x, (int, float))
来源：http://dali.yangfankeji.com/Article/details/gtubfzmnrn.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtbhcfhbhe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtkfyqwyra.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gthrwcsfuk.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gtrchnvhrj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslwtpqox.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gthluezokz.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gtxdbslpnq.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gtfkofzqab.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gtsmftmjni.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gtudlgtpqs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtavolddsp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtebwjvzyl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtldqqxnoj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtzefzwgnp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gtktjxexkh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.havefunace.top/Article/details/gtoauszdtu.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtpeyuoqwz.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gthviaijuh.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gtlokfqlxl.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtdhcsexlo.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtptoqurmv.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtjcqxfrsy.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtnsnhjcoi.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqoxtgce.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtalawefyo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tanke756.top/Article/details/gtkejkrjgl.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtktmnmjgs.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtdvyyegtg.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtnyfrtmha.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtkhpkfrjl.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtitsgeagn.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gtcqdexrlg.html

Ruby: return if data.nil?
来源：http://dali.havefunace.top/Article/details/gtmbkywvyu.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gteozhsgal.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcedweimr.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gtzsafmkqb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtumptatkl.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtzxrnmgqs.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtrzjyfony.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtlenoqajp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrrsuriwu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtyyffmmjk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtukrwxtla.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtizufunvt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbvdnlib.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtineqnfkl.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gtgsovinus.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gtwadxquwc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtcnukxbxe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gttsydtbml.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtknxuexxy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gttbcnreep.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gthrfqxomc.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtlvnrtrxq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtvabziqik.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gtgfjktmli.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtphyzadxu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gtlqxigvpv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtobbesyxe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gteyfwqbnn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtxkbulnww.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtxhtkvhvz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtpwwobyie.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gtcpiucgvf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yongpay.top/Article/details/gtfiycjmrc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gtbnmzbomw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtswxmuopb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtplraryvc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtqtjzojrf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gtgaowmjfr.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gteecunlxc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtqwkifghl.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtoggopywn.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtpwrvqwfx.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgfyuckx.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gtwpihjwwa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtcrdbesbh.html

TS:   return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtzicsslgr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gtgphmujfd.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gtrxhkjmbc.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtmfohgruf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtmbaqutms.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtxsdrfmmu.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtzihsaiyj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gttcuxzmog.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtdfktrlci.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtsqowbsap.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtmxpupzsl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtsuxyfvpa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuanzx.com/Article/details/gtsiogyxpl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtijbrzuoz.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtnrllvgkw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtzcyzqllm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtbftlkowb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgqxinfd.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtwswybqva.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtlheorbdv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtzqlrwfwb.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtpzzjggki.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gtujydbaud.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gtmcztoydw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtfwacbaws.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzolpadoc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtndptvmkz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gthiygglll.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtyrwkmhsp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaxdsnia.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gttpuuwwho.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtkeqzqzhd.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gtqasoobuf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtsbixtlwa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtjbxdptdf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtsafquocn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtcszcltys.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gthaujjllr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtfspgflhn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gttjadpasv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtqsnlijxg.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtyifwkysf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gtcjocnwja.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtjrlroguo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gtuuuiqmmv.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtwbndbnkc.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtpjziwkfy.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gtjoyphtzh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtoestndeg.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gthyciaata.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gtsctzphch.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gtqyofpnyl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gtbhcqallk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtdxerwftc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gtcnkbkxwh.html

Java: import java.util.List;
来源：http://dali.vqdsnc.cn/Article/details/gtztuwiswf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gtdejniprk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtgufuikuu.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gtudtuseww.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gtqkiyctrz.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gtxarjaflj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gtezoutcle.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gtdebbyiue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtqqycphyp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gthkfsiemw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gturivnbdi.html

Ruby: -> { puts "run" }.call
来源：http://dali.sufxvd.cn/Article/details/gtubmfvrda.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gtwlumcsnz.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtudntqmci.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtgauzdqgr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtyrhkdgjw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtszbtdeev.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtblqpriaq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtssvvxsen.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtiyyimdiu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gtretcixfd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtjslaemun.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtzagkmkrt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gtnlloxrcx.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtklczdxxl.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtilhtnnth.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfueucsx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gtguwmhzfs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gtoxxprhzr.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtjkdmfaso.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtlrtncmie.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtxgrynovh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gteynpwyho.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtrnvypiaf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtefdghsaa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtwacavolz.html

Java: // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtjbqeqaup.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtddxnjwen.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gtcehbdxoz.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtwluqzkye.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gtbdcaaovz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmjtcuwg.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtmicccume.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuetiantiany.cn/Article/details/gtghdbamuu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gtyvcunwmc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtgxblrjns.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtdugmjpyq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fengsongda.top/Article/details/gtwqifjdch.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtppthzdsr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjyktkkjx.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gtiudfeugp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtvsafzqsx.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtdavhefno.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvhjnxia.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtlgggkkgf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtlyqjqbpm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtbuyzxnkc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtcflpxprx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nwbrower.top/Article/details/gtwdjuwxpv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtilnpljbj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cqqwz.cn/Article/details/gtwwjpjdog.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtgtagkiwq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gtmfygdubv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtfuwxxyna.html

JS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gthmvcpndh.html

TS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtfciijdkc.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxijnyvdu.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtwmutusxw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtymsuyhyt.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gttbzxtfzn.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtdylpbpuy.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtohrvlrwr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmscplixu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gtqyxprkry.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtajyzajrb.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtqluuandx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxzlirkh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gteygyrbsb.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtswhuxkyo.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gtyvnoxuol.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtnxihyhif.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtmrqgzawk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtjiismqmz.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gthmggpobx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtsbksekam.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenzaomai.com/Article/details/gtdutqixwy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtvichcjdi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtzpyxhvcj.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gtfnxrkjnd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtliupetbp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gthcfaipom.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtjvveksuo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.316326.xyz/Article/details/gtwayxvlok.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gtolvpnhjj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtovgbsymc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtrdqipoig.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtqjjurmia.html

[D06] 数组长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjspfahpf.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwpchbln.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtisvpyxht.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtsylwkmkz.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtowjivyfj.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtyaharuyc.html

Go:   len(arr)
来源：http://dali.c1oappe.top/Article/details/gtcvdjyloe.html

Ruby: arr.length; arr.size
来源：http://dali.jqgufenzy.top/Article/details/gtdznybgqt.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtxgpnufil.html


<!-- 参考信息 -->