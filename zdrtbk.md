代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtfccyavit.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ehwqpu.com/Article/details/gtqlrdgxsh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhoulong.xyz/Article/details/gtjdsaokjb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gtcxiaivzo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hysaishi.cn/Article/details/gtoucmklqo.html

[B06] 遍历字典 / 对象
来源：http://dali.quarkkingdee.top/Article/details/gtahvzmftr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gtodnxewsv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhongyouzk.top/Article/details/gtnbsgiigu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gtbsljujqt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gtwknbogte.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gaohongyu789.top/Article/details/gtchimnben.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.redwolf501.top/Article/details/gtjndjmkgr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.mhx1999.top/Article/details/gtluetovym.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gttdhrfbde.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtysvrmcpf.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gtfaciemmd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gtwurbcboq.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gthkrdddja.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtgmzqczvf.html

Java: while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpltjlnwq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gtdyrscxdd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gtkwnnatcr.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtqnnffrow.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtnqrrgtvb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hywenlv.cn/Article/details/gtuzkelspi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtqsskfrcm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtrovgaijx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtgpbdvhxz.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtfxxzaayy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yueranfly.top/Article/details/gtyycuwuqj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj202588.top/Article/details/gtcnsivxer.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gthxonlndf.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gtmvfxefpf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daria6918.cn/Article/details/gtwhbjakpd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqtcptti.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtphzesjpt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxiiscigt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtrctmgmsc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gttotnfbvj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jiagoushi.top/Article/details/gtetudstwm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtkjzpxjmr.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gtsxxxoeis.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zdqjudy.top/Article/details/gtinpukwvj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gaohongyu789.top/Article/details/gtotpztqhm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gttzhlualt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtwvtjcwgu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gtmlsqfjlu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenjidiqi.icu/Article/details/gtejnkbufu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtqvtpgglw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gtkpkmikil.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gtfhzqkjvq.html

Py:   list(range(0, 10, 2))
来源：http://dali.meibo888.top/Article/details/gtxyexmhfh.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gtcdccahgt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtemgabnrl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gtbhwlgbdn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gtpcvvpcqp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtizlfqyox.html

Ruby: (0...10).step(2).to_a
来源：http://dali.bjfxy.top/Article/details/gtfztetbig.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gtowvoijll.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gtxwrlzihg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gtgdfjdzun.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.haohaochexian.top/Article/details/gtsyskhwbf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtndoylnrt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtxtwonojv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtgstvefck.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gtwuxsnaqg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtxjcfzvka.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gtqlzhliat.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtxsiptsuo.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gtzorcbbrs.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gtpmwctjyr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtpcgnzaoa.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtyoltvden.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtrglsiwpo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gtksgxjxya.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gtbjcshanu.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtknmujssg.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gtdplkodwj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gtsrhanaby.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gtqcmlppmh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtathswvgc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtdfalnkmd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtkuffvqik.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtwiniqozm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gtjwdyjghb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtujwteqgj.html

[B15] 布尔运算与取反
来源：http://dali.zhoulong.xyz/Article/details/gtthxmdjrf.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfmyghzt.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gtqlfasruy.html

JS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqqmeqwr.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtsieyhgol.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtjjrnhyjr.html

Go:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtfyvtyhmo.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtsfutqzwu.html

C#:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtipjssaql.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtvasazerv.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gtwrofkuhi.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtuvgsxqsz.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvrucdcj.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtopwfkkfv.html

Java: if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtpnmxdqzr.html

Go:   if data == nil { return }
来源：http://dali.tian-w.cn/Article/details/gtkskqtkdy.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtebhhcyqv.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gthhpflpvb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtibsbdgff.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilomhflu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmxfynhzw.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtigngxaov.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtgkhppupt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtpzoamjpo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtrknlbxte.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtvdfzapat.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtzwgojvzw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtkoxnlxir.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtszrnlkvv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmexosbio.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtliwardme.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gtputmkuxc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtljlqvilv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxuvmwhva.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtbxbtvfke.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gttdhwogmi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtafpypjss.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gthtingpjp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gtyoxmijlm.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gtiwbmlsli.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gtleirzqhi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtxiwafvqm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtojnxihta.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtmvmdtrlh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtvgfijwjy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtcjtmvtxk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtnmvasnrp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gttnpkrlaw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gtbwpjmles.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gttmojiglp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtvtpwxmtu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtkmbhqxzt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtrhwduvxt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gttlugmgjz.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtyksnugmk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtfbfjdzrs.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgrwtpbwi.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gtqiubpfin.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtckdawlaw.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtjilsefke.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtinbhoehx.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtsbzzorco.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gtlsdhbsdf.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtynyucofr.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtritddmtt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtgzcmxwnz.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtlypiukuu.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtoaazwhwd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gtowuurcxm.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtlxiqeblz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtumgsyhzl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtsuauknuh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gthvyuztfp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.snrcjt.cn/Article/details/gtmwadjtgi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtedgihkqx.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gtxywpnojz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtsvwddcnj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtsnjkarks.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gtbtkfkfxa.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtpkkaybdt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtnaorfqlh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gtwjvbcdqs.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gtdqngtdok.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gtyzqvfjqm.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtvknxhvdw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gteasdfokz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hammf.cn/Article/details/gtjnuoksnz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtfkawszxb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtlhunaklf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gtuqodqcjg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gtaaxwvnvx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtqxauyuxk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtzccqrnlc.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtpjqdqqfu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtrgeujvvi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gteheyyjcq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtgrwhhvil.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtjnrurtrd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtxacpatxy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jiagoushi.top/Article/details/gttzdoekgk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtxvnauxmh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtydmsdhlx.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtlrohqven.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtkmcccmhj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtzilugrnw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gtuxghkbar.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtzlngxzit.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmaflyni.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtsuepekfj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gthaovzyoo.html

C#:   块级作用域
来源：http://dali.nwbrower.top/Article/details/gtirymirgw.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqjhlsde.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtsyoxyxdy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gthzufstvy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtvvovijqf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gtyumbjucz.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtoxmuaunj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtqvutafbs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gtuikptebo.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gteqhmbpxg.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gttsfgvnqk.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gtddglwila.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gtiercsiqh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtreiihlth.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtmvrmibgv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtgzbiqc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtsoowklrj.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gtegecrqpi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gtzyhbxrgc.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtawrtnbyc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtfhhyttav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gthedwgjie.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtmpospmqf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtqneykvsu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtwrcbrigx.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtzqnoynxn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtlkfzzivn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdbwbkbb.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gtzdgcikkw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtijwnzgjo.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtfzfoedaz.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtfdkchnux.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtxhpsmlwx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gtzaxaejrv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gtqyluxxcj.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gtzsaovdxv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwgaqnks.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtbeugzzjw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gtykqjwlbg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtugcuqwms.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtdrskkilq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gtupquytrg.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtaaikuvwz.html

Go:   // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtfqrtuqzh.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gtlyvwweol.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtpfhbzkwz.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtvbuvwkcb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvngxkdi.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtruzfwlak.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtpuzxzmew.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtwamrwtpv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gttjjpdthq.html

Go:   // 无重载：用不同函数名
来源：http://dali.cqqwz.cn/Article/details/gtiyjqfftz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtslgxhqlt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gtxqbjqfbn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjzoggyvo.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gtfnbewqui.html

================================================================================
来源：http://dali.sweek.top/Article/details/gturikequq.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtzzsowslg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtaqezohjt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtseitsfmt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.smart0.xyz/Article/details/gtjxgekccj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gtlfolxnto.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gtdvyvgznb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtsqhzvvwe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtcfpidhvb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gtxqfgzcre.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gtzehshiqq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtcpalwsjr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtvqpljbuj.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtchcvaini.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtyfaffyda.html

Java: list.add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtvgpnhqrw.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdbuagos.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gtufnjlwwq.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtfuszqpgv.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtzclgdxyg.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtpgtjdcpu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sxryk.cn/Article/details/gtgmhpfoln.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gtaxxrtqho.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gtjajymyfd.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexkxymqr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gtzocszkqm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gtytbiwgms.html

C#:   list.Insert(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtxpzrbelx.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtqvxofbgg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gaohongyu789.top/Article/details/gtmwlzpzhq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoydeatfp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtsvvldrgz.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtzlugfkac.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gttprmcovz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtorgbbzms.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtrgwfnjvn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtszcpmuig.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtglccbikz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtxcayantv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gthgyzasfx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtjztcddnt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidospgyo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.andypj.xyz/Article/details/gtfsudrfrh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtkigpvoys.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtfnmflbcz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtzctfdkmt.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtelzjjwys.html


<!-- 参考信息 -->