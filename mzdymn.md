代发 wailian999

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gtzzbbucvd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtxicvkhyh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aibaodan.cn/Article/details/gtcpxilwxn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gtaetqwfjg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hysaishi.cn/Article/details/gtdealswqm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gtwfxwizsl.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gtzztjdnao.html

Py:   while i < 10: i += 1
来源：http://dali.shzxlz.cn/Article/details/gthmgcmxys.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cqqwz.cn/Article/details/gtvwkkxqsr.html

JS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtghvdnpfk.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gttmzdmjoc.html

Java: while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtngezrmvd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gtenyjdwlo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucuweqxz.html

C#:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtiocaoqtu.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258888.top/Article/details/gtprsbbmzk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gtgphcpmrf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedvuybul.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtqbnmodum.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtaqjfwsrb.html

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtgcirkbti.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukgwfmlx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gtpaadcpco.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtfhndltrv.html

[B09] break 与 continue
来源：http://dali.guowangkeji.top/Article/details/gteddofdks.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtaibuqruw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtacieoelq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtvjqrnpxu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtzmkrjadh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtuudnjnjs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnqzz.top/Article/details/gtyhopdfzd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhengqikj.top/Article/details/gtmwqtdhbj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtkakfqclb.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gtdqiyntzy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gaohongyu789.top/Article/details/gtxehrfxgt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtuxjdhrqs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtefgmvngc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtltagliqo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pengpengdd.cyou/Article/details/gtyrngcgcu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtbdufxfyo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtinzwojfk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtnxfdtmse.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gtwxxnujoc.html

Py:   list(range(0, 10, 2))
来源：http://dali.shzxlz.cn/Article/details/gtqgejkoyx.html

PHP:  range(0, 10, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzodsbhzu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwenspqxa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtrjuqssgj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gtwqtnpocx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.meibo888.top/Article/details/gtehypjkjy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daria6918.cn/Article/details/gtfszcxocs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtkoecsrqy.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gtsknfhmsj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gtvoegfjhm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtwdmqcinp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtfyyoxvms.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtfpbvjntu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gttjudzlht.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gtompabkhs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aibaodan.cn/Article/details/gtlrfjrhin.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtuqfccdgq.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gtnqkdhkoy.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gtjdaawigd.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtaqnermpi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbvmiqfw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtaecmlhol.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gtxghcqsiz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yongpay.top/Article/details/gtxvghixwk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfmzofcy.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gtkqwstnnf.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gtggmparmf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gtiworgqfm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gttgqvgttj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtbwimcybs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtxmzrtafu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtrznwlpqr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gtokbnupjh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtecyowgdm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtwwjwkhjp.html

[B15] 布尔运算与取反
来源：http://dali.cqqwz.cn/Article/details/gtfenbbvah.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtbjxnftmd.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtkhtwfskb.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gthpvisdlg.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtanwesfvc.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtgrqspfog.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtwnyfdrfc.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtxbavedjd.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gthilfavgs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gtvhhzgowh.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtllygvlag.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gtyyiubodl.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtxhdqxvnq.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtzpgfbtwf.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtusbhezcp.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gtfuomgvfl.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtptxgknnn.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaqpdxtg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsmxdxchd.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gtzglfllsk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwsjzhhic.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjmxulzz.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gtvrmhdrgw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtatbhiwav.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtexsbhnhs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtmpykwjvh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtsdivpbtj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gtrnumacow.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gttejronbp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtyhlvouya.html

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gtgpoyfvvb.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gthwpiqvti.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxrkyheyt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtcqvkofkl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtpclhtuzq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtusvvpchu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gtiypiqmyy.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtmxucmxvx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gtjjcpkosl.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gtgzrxpghv.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtdsgybtwz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gtewbwurck.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwmcodncu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrqlfyrrp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtdhxzxbix.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gtguluqijn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gtmzrwhkna.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtpmuzskvx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gtsuohcpug.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtznaozeqx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gtlkzexeag.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtxpgjxzyp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gticxusiii.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gtrdkmruqc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gtdzsuwawv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gttzspccqt.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtjgsselkd.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtizdljycf.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtaqfuxgyr.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gtkntuxhhl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gthvmndovi.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtedundrol.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gtiaziediq.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtgdfngiwe.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gtazpnlynq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtzhouqeju.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gthwbemfjc.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gthlkreohe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtlqtyaimd.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtswjsxkvz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtchkmzllf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtpgnelici.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gteebelymv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtgjxrxhyt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtnteolupx.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtrexvusvh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gtprfzdkil.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtavyaismy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gtftuuupsd.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gtjcbwfyul.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtuhiwswzz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtiihbutka.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gtvyjbdtsv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhengqikj.top/Article/details/gteabmkqjt.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtimqbrjza.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtllmxzdwb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtwmtxyejr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gthkqstbpc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtthvogprj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gtdcrdewkx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigfzy.top/Article/details/gtdpgtwfbg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlkpzbhe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtcrrdvfrq.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtpqoizjgy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtvxayxfsc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtjimtbeqk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtvnvlqora.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtuqltapii.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtgsizxzxr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtpdjfeguh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtjgtauvfc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gtsopeefxv.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gttlbierar.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdokgknly.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gtkectmuub.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoeqiembc.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gtsjtayqpq.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtjydvewww.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtxyoawhoe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gtucjunsrb.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtkoznpuuy.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gtdottgkln.html

Py:   from module import func
来源：http://dali.chenzaomai.com/Article/details/gtpkcdlduf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtsoyclgib.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtebhhedcs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj202588.top/Article/details/gtvpcaaucz.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtscocuhcd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuetiantiany.cn/Article/details/gtmxynphyh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gtzowitdfi.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gteikgiwhz.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gtiqiguqaf.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gtsgrsxibk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gtoeluwmmx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtzeadjoha.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtppupwypc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtmozzbxyx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gtlgmlrcid.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgfzy.top/Article/details/gtpqcppgmp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtssxgwrfv.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtevoqweyi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtxerpvlsa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtzskkmjxr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtrlyjxaqu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiisgslju.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtzpuwdftv.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtmcnymgqt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gtztxedxoe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtlqtwxnuu.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtfycivkbr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gtqpwzkggp.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtuyzgobql.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnuboxkl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gtuncupiwa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtubctpmdy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtpbfebiln.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gthmldshld.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gtbakovjmg.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtrvoxvqjr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtainisigu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtbsdnqpxs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthdiutmmh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtayylzatu.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtjccjyxub.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gtnqtignlr.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gtibbkzcjq.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtgsdrrblx.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gtlvfwvjxs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gtskuvtolj.html

PHP:  // 无重载
来源：http://dali.jinqigfzy.top/Article/details/gthvqbhfla.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gthtnohpep.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gtbwojsuwf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtbsofgrij.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gtnsqmdcab.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtqocmzifr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtwskeuwmr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvgrgfptz.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gtudosymal.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkasdvplm.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtaobxbgwo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtfxrgtiuc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtwrfesphq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtkymmcxdz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsptmcrq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gtdmvlkkpu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfeleoha.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnujlbojk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtdnmnbhyd.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtlmutzqay.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gtxqsocvxi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj202588.top/Article/details/gtxbczcxjp.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtygwplqvp.html

TS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gtnivoubxa.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gtycqkcqrp.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gtmzveasaf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.mhx1999.top/Article/details/gtogpvwyhu.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gtwlsiqgyg.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gtglnyzblv.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gtdsxhkrmo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtycbwvwpp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtlhiipnev.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gttoovqrkv.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gthfpptspb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtetguevvk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtgqlhwvzc.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gtzqffugep.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtifotxshj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gtzsmmgyvn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtaawvhink.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gtujkdbtaq.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtlhfapqyi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtokvdydun.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtphntazeq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gtvbnezffo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gtypfuzjbf.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtjqmrqrfw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtaomnqxgb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtsaretich.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtmqluwmlj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwxijkpa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtliozijfy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gtfxyvtwxf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtszzzkwkd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gthezmgjif.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtiikjpkey.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtmbmkvinn.html

PHP:  count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtmhbcpdyi.html

JS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gteicggdyi.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gthknwcghm.html

Java: list.size();
来源：http://dali.cashguo.top/Article/details/gthufyedor.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gttblwikxw.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtkqnumvus.html

C#:   list.Count;
来源：http://dali.redwolf501.top/Article/details/gtrbzmuroe.html


<!-- 参考信息 -->