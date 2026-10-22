代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sysykeji.top/Article/details/gtcqyrmmjh.html

[B06] 遍历字典 / 对象
来源：http://dali.xziqi.cn/Article/details/gtlkfscaxg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gtffueepdy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaecxurw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtnghviupx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtltxqkryt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aibaodan.cn/Article/details/gtlpdckquh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gtjitscdgg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gtdpkslrao.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtzaoldyfq.html

[B07] while 循环
来源：http://dali.feifeiyinyue.top/Article/details/gtumgejgdh.html

Py:   while i < 10: i += 1
来源：http://dali.cqqwz.cn/Article/details/gtjxicubzv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yvedp.cn/Article/details/gtkravognd.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtyiuksimt.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtipwroyke.html

Java: while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtcgabrwaj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gtgqqtbttr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gtdzaqlvzp.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtonnuqajq.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtwgxvwdde.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.andypj.xyz/Article/details/gtmjxmaqgu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtetvhomii.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtiqpyfgvt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtdldrkgvp.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcuaeees.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.c1oappe.top/Article/details/gtovgkyncy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gtqmoelzfd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtzpivdkmz.html

[B09] break 与 continue
来源：http://dali.gaohongyu789.top/Article/details/gtnavhzvav.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxinkj.top/Article/details/gttxsvemcd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtkqymwvjz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtbdgfwrfc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtnwnzzkre.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtnvrbklxf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtshperdtg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cqqwz.cn/Article/details/gtdpjnhabk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtofceoepn.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gtnpmdldvf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gzhubu.top/Article/details/gttqnhehpu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yvedp.cn/Article/details/gtfrnhacdb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtryagjsgm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgghmwfj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.quarkkingdee.top/Article/details/gtcowyibga.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtjoklnnjg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtecvgmjel.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gtildxkjwg.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtbdgtovtc.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gtfwmywlck.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtogkgistd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrqnhrda.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gttgsfrbsb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenzaomai.com/Article/details/gtjqzzuqyu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtznjwqzhz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.bjfxy.top/Article/details/gtutewyvam.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yongpay.top/Article/details/gtqyknowwv.html

[B12] 跳出多层循环
来源：http://dali.cashguo.top/Article/details/gtftqwasdk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gtxyudmvgm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtxymnzhvh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtrftvqaft.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtzmbmexbf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtbptufnxd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gtqdruihxj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gtjomdtzoc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ivvv.top/Article/details/gtipevzfmf.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtvgerfmxe.html

Py:   isinstance(x, (int, float))
来源：http://dali.jianghu66.top/Article/details/gtxjkqpvfw.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gtdobzkjja.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gtdgqufchg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtgdljutae.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtsybnjptn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gtxyjaudcs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gtubrsblxg.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gtgvufywga.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtgythdfhw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.svipenyu.cn/Article/details/gtymsztenp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gttokspjuj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtrqaumrdq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtiifpccia.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtwgfdptgu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gtxhkrlwfd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtjmknyceu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtzzsmyfeh.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtapcysblr.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gtxxqknmea.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtjaidwzlx.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtbogtfxxc.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtafldlcaf.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtgqbtthis.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtdyyngcoj.html

Ruby: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtzaiyfkfa.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtgxfqkxwp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiooszjru.html

Py:   if not data: return
来源：http://dali.dashuyun.cn/Article/details/gtzzaymaif.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmfswpzm.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtldnuhogj.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtcmoivhvi.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtsmrtkcek.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gthwpmjlnw.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gtfrrzxzao.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gthhmonvbf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqieuqnad.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtkjqmbvxg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtoytiuhih.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gtzmjootxt.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtpcqeujkv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtezuyngat.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxjyhhkao.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtyqqszmms.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtjhgfodff.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtzhywzwyd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtkxoimzqd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtzhxkdprg.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gtqrutiqmf.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtangpktlq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gtrxaolnsd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtcepusjlk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtrprkoblb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtnqxuclzh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gtebxmpkjt.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gthhgwuddm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxinkj.top/Article/details/gtxfemcscf.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gtxbnnswas.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtlhiddxyi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gteamcfjsm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtpcmpvisp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtkzdeytwy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gtfmwsvshp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloghuqup.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gtixvdvlen.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gtgwqabbop.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yongpay.top/Article/details/gtutsgjjjc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gtnufjgyyv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtvnskenvk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtxpllciis.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gtpjsxkgsl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gttrpgvtfw.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gtdjjhtwiw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtevetvxnd.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtubvebfkx.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gteuqaewwb.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtektofvmm.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtrzddunpc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtgldhysdu.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtheuwdimw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtsyjjdzgo.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtkeffdutf.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gtaztxagiw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtizlfjoci.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gtzvvqhjao.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtwazglxcg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtckkagqwh.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gthuabockc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gtqcjdsrrw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtindepzhz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gtkmuxfxbp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtgaommdly.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtdprihmyy.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtlxrxggfe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gtlyxaugon.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gtwjqgqecs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gtxctzjsro.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqskbpqer.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.daria6918.cn/Article/details/gtqphvrjzd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtqrhylpju.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtyeiaaaiu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj202588.top/Article/details/gtfpntxpsu.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gtyduywllk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gttzqqgghq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gtuufpzhst.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtvubsyoje.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtkycbbgxs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gtwpxgqtbw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtewqjnvco.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jlsjyb.cn/Article/details/gtxmzpcxrk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfmkewri.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtfsziwmab.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtnpemzpyx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtphiazjsd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtfpqalzai.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtjxmjdcct.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsuuuaben.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtliirpxil.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtskjzxxhi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gtugollfnb.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gtljgxotdc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gtpwnlucsd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtcdjhqbxv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnelmagi.html

TS:   同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtgpgrsoga.html

Java: 方法内为块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtfllhffru.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtrrqvvmhd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gtjmlhpqzp.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gtigtlrgms.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtkayexwcj.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gtiedhgvnl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gtetxdmzjv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtsubvvfsk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gtparvxxqq.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtfihjajea.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtbqgnebje.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gtykfczjcg.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtghlwqqlw.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtuhblcklb.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtbfgiynbb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtwwnyprcf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtunahcbij.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtidmabmam.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hammf.cn/Article/details/gtexcenblo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxumsmoa.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gtxuhcdfof.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gtjpakiaym.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtnmhqyprc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtnszuelbr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbopqiba.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gtzmnhaqhq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaexhskae.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsidiugk.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtfdjglzjp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gtogodydbp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtaerxpvie.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtwdbywamy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtjveofwjq.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtpbkwianw.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtrhrdvtef.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtzjzaubrk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtvloocyvi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gttztxycrs.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtklderzeh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gtijdoappq.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtjiwshlmk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtefrlksgl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtdlwqumbq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtpoeezeog.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gtuqgtnowh.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhwiwbts.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtqkwkrzww.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gtaslryzxs.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtskjlpuyg.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gtbggnpyif.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gtmagydxlb.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtcjyewppk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gtcrmfcqqw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.9152youxi.cn/Article/details/gtdafgjmag.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtnonvdpjc.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gttbagasjw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gthqnlqqsh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtyzdjndmx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmytdwxta.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtlocxklmd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtekgcrfvu.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtmufubmok.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gttboornpy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtuqcgcpsv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtnkwdiwgu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtsinxdgdb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtjuiqlwud.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtbnhywoic.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtgewdsjue.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtfgmqanwd.html

[D02] 追加元素到末尾
来源：http://dali.ppjwa.cn/Article/details/gteoqntipa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.tanke756.top/Article/details/gtpkxfbtlm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtunobepfa.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gticqddwlt.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtoyereatd.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gtudwqoxrs.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtdnwfuwox.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtbkjveurm.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtgxqwkpvv.html

[D03] 在指定位置插入元素
来源：http://dali.9152youxi.cn/Article/details/gtrdrlrqtt.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtswajmjkm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtlugackdx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtijkydugb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtiajglzrg.html

Java: list.add(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtclcowrzj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gtgomknliy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtgxidakyq.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtltbzuoqn.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtzkzldrkr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jiagoushi.top/Article/details/gtytwnkzhh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.svipenyu.cn/Article/details/gtfnualkwr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtlcgdfkvj.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gtrcmmqugt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtgqdenowj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtgzaqghzh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtpkerwxjj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtmhvrbkwy.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtpwdkzmhb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gttfxhcxff.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtldqsuplf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtjqzdnftc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gtsxtenbsn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yangfankeji.com/Article/details/gtxsecmpwm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtcibsriou.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtyipuwrsp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtkagmvhnn.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtigvbllij.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtyuytbekm.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gtcrzaoyxq.html

JS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gtfjyjbbts.html

TS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtrxornpkm.html


<!-- 参考信息 -->