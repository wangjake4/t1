代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtmdgnbmyl.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gtmukownuh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.kuanghao11.cn/Article/details/gtulumbzjv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtydqhhtjk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtoxwdeadh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gttfdaleqa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tianlin.xyz/Article/details/gtimfdjzly.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aibaodan.cn/Article/details/gtxandevpv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.iojbl.cn/Article/details/gtondtmwrm.html

[B06] 遍历字典 / 对象
来源：http://dali.hysaishi.cn/Article/details/gtdpgendpv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gtssrcxifv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gtizvhlyyp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtidldbsoa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtwtmfemxe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gtuakrnevm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.9152youxi.cn/Article/details/gthwuckobg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtnxmgjyxc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gtzncsbvwz.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gtrvrarlxz.html

Py:   while i < 10: i += 1
来源：http://dali.zdqjudy.top/Article/details/gthmxzacem.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daria6918.cn/Article/details/gtzzxuhqiu.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtkibodgvn.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtjmotgkgq.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gttmhtgunl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gtbtrsdboh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlilmmmu.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtauqqphad.html

[B08] do-while（至少执行一次）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlcdtlnp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gtbyybktku.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtsqjtxsnu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtnwlcnosn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtymjpmite.html

Java: do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtaecreexh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtekzxkovy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gtiwofjxng.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpchfroax.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gtiyrvrpcu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtchhjkcus.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtmvgfwmol.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtrqontbbu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtemctvsvp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtyzcbuvhc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guowangkeji.top/Article/details/gtysxvkdlx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yvedp.cn/Article/details/gtmbalifex.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtehexdohp.html

[B10] 遍历同时拿索引
来源：http://dali.0kj1m.cn/Article/details/gtyfpvcndh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtgcwtitfy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gtqgnswjkm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258.top/Article/details/gtgjuixltg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtcvhedzii.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gtfxiynhpv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gttrcgldmg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtwmfxxfwn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.snrcjt.cn/Article/details/gttubryibf.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtsqmskfym.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gthsngphij.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtoiowwdej.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtjxwwqioq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusjhgiut.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gterhreqcw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtibnmljzl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gtqnvqeucu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyhbxjil.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gtyaukxngo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtscyotcpd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gtfcxqbxly.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gthpyivhdl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtnpkaylsc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtsoqflaxb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gtjbmujezo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gtkolihsdd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gtbiacnkkl.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gtwnvdodzc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtiycvgflq.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gtxvggyjvz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtumbjzvsi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtnpniavag.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gtvwzcxgjn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbelnndp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtsvwaylcm.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtaewggcye.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtceirknhr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gtotyhyjco.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gtdmrwkvgp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtbwbmcnhi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtemfpgocf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gtunecdwyq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtxnpehpme.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtgftdnqly.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtiwthtjzl.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtgcwvpimq.html

Py:   a and b or not c
来源：http://dali.c1oappe.top/Article/details/gtcghsdjgx.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gtizcfnsjo.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtbivbqtab.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtqlptkklr.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gtkywzfncf.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtguugvhrg.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtupguoklr.html

C#:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtfpkybimm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtnltsicox.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtzqdrdhdq.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglfdwspt.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtflgrdepw.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtcuxafrmj.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtxnzdnutn.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gtkgasgqgj.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gthtfaxkxb.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtpbaalvpl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvndwldvw.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtyjsrkzbo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtubvnmylo.html

[C01] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaenjhspn.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gtkpexojor.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtrsdklxjh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtmufdmdns.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtacgkmlfa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtmocltxoa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gtcsvzshzq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gtmglrcnyg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtujouqceg.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtbrjutjnh.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtnopphimi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtgvjuqcrx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gthjroyofl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvhbvgtn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtgbpvowgn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikjmzrtr.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtthuxxnub.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtgozhkcop.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtmjayibqx.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gtjciasksv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtfrlcyapf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gttfbtmncf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gttvipfllw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtvpktydzv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtjeiknuqr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gtrlezverc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258888.top/Article/details/gtqvffnrra.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtwnlqqaxa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gtwhzgwnbn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtwbjlaswu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtmketlbep.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtntnpmixz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gtmumimewd.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gtxnzbtpei.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtashpgoro.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtqvvsbxtj.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gthhumagiz.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtfoffclhn.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtoujcqlhg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtbsnvyhsq.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtumbjhzlu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gtmzjitljq.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtqogzorbs.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gtdpbswjcg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtptaqbvpi.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gtepujfytk.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtzqkqqebt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtpsxtfzmc.html

JS:   const square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtgffystjc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtcfqqkiar.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtpxilzvfq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtllovobtc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtnzbtlcts.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtabprecta.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gthatptcje.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtbokdmqce.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtkbtedvbw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtdiwnflcp.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gtoosydlsb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtkmfdwxhf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gtucjuhphy.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtzkzjwqao.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtdshxtsdp.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokmhovuy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gthkfihbrm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.havefunace.top/Article/details/gttufacqov.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtdpbjdspy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtwmovvhdr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtrxlihbuo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gtbyhpdglc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gthvvdelcl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gttxeishok.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtcdagmslp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtrzwskovt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtsuraheqt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gttjfiovpv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtonunargu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtbpzgaloc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gtdfzcjujq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtemmqhhbl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtlbisdqii.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtfeqcpmiw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gtswwtkghh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdqueasu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gtxitaygwd.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gthlgcsrtq.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtepaathzk.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtxlkwludp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtwlnqlqoy.html

C#:   块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtgogbeyxy.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtjxhrcnvo.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gttpqaxlwr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gtspzwlavw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtmsunwaqq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtgykhlxhb.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gtfjifqxus.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtqzbteayu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtakufpunt.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtdpqkmuiz.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtexolqsmv.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtxnlxbajh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gtimhnvdzd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtztynbghq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtfovcpmsg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtjuncudgg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gttfverbvg.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtxaajbpes.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuanzx.com/Article/details/gtuoeudqvl.html

[C13] 类型声明 / 类型注解
来源：http://dali.cqqwz.cn/Article/details/gtawcmbczs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gthyholymn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtpqolajtk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yanxiufei.cn/Article/details/gtgygkzquu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtrwtlxomx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtulfbjnce.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtrjgwfuie.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqnyflya.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtzuzscacu.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gtrvzpzmyg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gtkzmbvzxk.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gturzcqpjf.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtvsqwwpgg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gteljacuqf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gtrbzmfaac.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtlhaxpwpp.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gtrcvqyrwd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gtjuzdvmjo.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtppizgsrn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gthujdspes.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtwuqxpuwz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtagfsprot.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtagchspfh.html

Java: // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtxjgecgah.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtngirrxfo.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtytfnfvkf.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtdobgmffo.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtlkjzscix.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gtioxftciw.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gtvnxykhaa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtujrwtmhn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtjqxiozyw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xylfe.cn/Article/details/gtwkjywpih.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gtocqfrpea.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtiokmzcrt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xinyue.icu/Article/details/gtutfmzgjj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtczqbfjwi.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtpinqrwve.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtuubniife.html

[D01] 创建数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtwyegooek.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtsfvmoxqw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtepwoixyq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gteluizhcs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtdaqbvlog.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtjclsacxd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtkdwzdiip.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtnhcaiihv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtremfgdau.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvfeurhx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.havefunace.top/Article/details/gtjmewzyky.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtxspmihpw.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtpulzdyfi.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmqtsjrw.html

Java: list.add(4);
来源：http://dali.yj20258.top/Article/details/gttfwpawal.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtiuyyijjn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gtucwkwnom.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtioqpjcup.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gtjcdawoop.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtngcuqjaz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.haohaochexian.top/Article/details/gtpatpypbq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nwbrower.top/Article/details/gtzrbmujcj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtmqnrjnmz.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtnvjgrqnx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtcuinribu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtorgmlvqe.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gtrmgcqdjr.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtxdgrgmrb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gtpkukzwit.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258888.top/Article/details/gtgzbynquq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtvrdpvvvm.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtlnuudqsy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtnhgpgrnx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gtcfgqqvek.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gteptqhdsu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhongyouzk.top/Article/details/gtihiddili.html

[D05] 访问与修改元素
来源：http://dali.wangdashe.top/Article/details/gtxpyvsgqj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtitxuycnh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtcdodilfk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtbfpeuplv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwoykfrw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtmscwwszm.html


<!-- 参考信息 -->