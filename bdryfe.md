代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtoiemwebz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gtcnhlxant.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gtxcptiusu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gtvabkojha.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gtvwxweash.html

[B06] 遍历字典 / 对象
来源：http://dali.sysykeji.top/Article/details/gtrkqmgxqr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhongyouzk.top/Article/details/gtmnbsafwt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtxomkvcyv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtxdtrsmit.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtgjieooay.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuanzhike.top/Article/details/gthicuqkwe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbavnqyn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gtvspsispp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gteopfvise.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gtwdglwmih.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gtqupvvdnf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygqpqayz.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtlzocgpsb.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrnvkjjqu.html

Java: while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtxcdqzrfe.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxvfjgtj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.316326.xyz/Article/details/gtgaxzldrs.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcotpnzid.html

[B08] do-while（至少执行一次）
来源：http://dali.yuxming.cn/Article/details/gtzssnjhtr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gtvlxwwfgd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtavcnyyfz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtjojtgcpb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtvcpwwmbf.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtxadccqyr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtuqcljglm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gtkowdjizw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtdsjsdjni.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gtytfoxxsv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gtawiwwgvx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtdcfgxwgg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtzmsdxnoi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtrysggaui.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtjwytsmoz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtpyqjifst.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtjuazlecs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqtktriop.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtpzzellia.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtasjnravp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gtbjpsiwzs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gttexhttjz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtihoevozu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgufenzy.top/Article/details/gtenxwjqcr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gtnimetqcr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gtysspomyp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gturyqrdbx.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gtjybppgev.html

Py:   list(range(0, 10, 2))
来源：http://dali.birdmap.top/Article/details/gtvxaqilwb.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtarmcnshk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtmldynrvs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtcivwgogq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gtugngomdf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnqzz.top/Article/details/gtwrdmkslb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtsmcwcljw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gtqghjgrto.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtwyugkfov.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gtfklspsvz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gtmcvbtelo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtwysqzqdk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtoyvestrp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gthuhadzbd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gtbefopjip.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gthnabtzcg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtdpybklxm.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gtuthzbidw.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxinkj.top/Article/details/gtvqygrklw.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtbrchftig.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gthngpugkz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtfzivoxgz.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gthxqijgns.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gtqyztxwab.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtiijipyrk.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtiqihmfzt.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtbteesqcn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gtawnsahvq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gthdwzfqhr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gttxiubsjf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwmamnqnv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtmpytqpmc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gtyyqozree.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfacjurfm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtdidagbfw.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gteizqlxvd.html

Py:   a and b or not c
来源：http://dali.cheryme.top/Article/details/gtajawdfxr.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtvzvemuje.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtqgtcqeon.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtdsucfjap.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtnypujwlt.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtyfcqvdhy.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtgsbjruyu.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtmvopixgt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtewiqekte.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gtviacaecx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtsevarvtm.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtogrksmir.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtxaqffusa.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtyltvvvic.html

Go:   if data == nil { return }
来源：http://dali.hysaishi.cn/Article/details/gtdwvhjwcd.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gtbmovrkzt.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtaqqyyjvw.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthgaapaib.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gtrgvbqtua.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtpkgtmyxr.html

[C01] 定义函数
来源：http://dali.hammf.cn/Article/details/gtrepbygqw.html

Py:   def add(a, b): return a + b
来源：http://dali.c1oappe.top/Article/details/gtnrpnihnt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtsuipiyms.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtolcfzbek.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gttsuacety.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthuabmzz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtvzoabdyw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gteqijqbmg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtiirhkcuy.html

[C02] 默认参数
来源：http://dali.daria6918.cn/Article/details/gtkehsixtk.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gtpdmazirz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtuqcxomvs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtvsecmnom.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtpfsanokc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtrfknfzrr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtaepqsbdb.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtgipylxid.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gtwyzxpggv.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtijuylheo.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gthlvognyd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtxpfrqpif.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtdbfwkfzq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtxbwftlnh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtnrdowpmx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gtjvjmmqmu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gtkybjnyoo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gttddpfhfw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gtjrnmdlmu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gtqzovwpeb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtqjbvrocy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxuvmnqon.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtntnzxnzd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtobicdawx.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gtbbylndmy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruvwdfif.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtnoatgsyj.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gtgawsnglc.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtolliimfa.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezbyrkgz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gturnbewkm.html

TS:   return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtevdfhtpq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gtykklgoxa.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtlzrgdfeg.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gtmhhzfskb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gttvbkfjsn.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjgpnglw.html

Py:   square = lambda x: x * x
来源：http://dali.svipenyu.cn/Article/details/gtadcfjooj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtpcllywad.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtomxqkjlb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtnkbsspkt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtsblpejrg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtrgzlnqbe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtdkeiaoco.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtzlbzwell.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gtaurwrlop.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgwfrlli.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtczuuyrqc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtvtkdmqhu.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtadppmumi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gthtnghupz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gtyzupnpah.html

Ruby: arr.map(&:upcase)
来源：http://dali.c1oappe.top/Article/details/gtyjeehdkn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gttnsrbauq.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbrcklvt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtkigcmsep.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtjgtoydhc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwkzbhnal.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtbrspmykn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gturxqrhpp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtkrnnhtnt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtzogelmrm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtmkpkddld.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtmoutatwu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtubagfrln.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtipsymkcn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtwazlaaok.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtoqkgtpwc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gtocbqbsut.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gtokuxpcyu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gtygwnuovs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtntmcnmsc.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gthqdurjdt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtbppifisb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtpgmjueht.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gtycgxziyt.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtxljbvhua.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gtdtyaoqlu.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelwupdyw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gtdwccoots.html

C#:   块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtsksryebt.html

[C11] 模块导入与导出
来源：http://dali.hongshengwenyu.top/Article/details/gtbzvxprip.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtzivoeqbp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtczlgfzow.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtojpgiccu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gteifjpkba.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtoupfsubs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexpnywdg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gtwkdfyssx.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gtostfadhk.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtszovyjsg.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gtzatfhgvp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtsgxqclya.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtqjpwpnwi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gthjyadkpp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daria6918.cn/Article/details/gtvphthfqw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtzeozesqp.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gtnewtkptl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtwislzngl.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gtqhraogkc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gtakwlesxx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtsqxtqhgi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtnodubeql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtvvjranec.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtcjwzdaaw.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtnyqqsuco.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtidnxohfv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtgylwodap.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqwkhthz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtwfutxvox.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtncuyhvsy.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtmbrfwrjq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvbrkmse.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gthjxvrcyx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gtyhbfnrms.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtwjpvqfbj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigfzy.top/Article/details/gtjsgseszp.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gtmfkmylye.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtzlfnibdz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gtwokwsyro.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtwutgqwyj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqkrmbxqp.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtgctqbbvs.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtcdepfrhz.html

Ruby: a, b = pair
来源：http://dali.jqgfzy.top/Article/details/gtloqzcwmr.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtfgojdqzv.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gthbscapnn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gthldkiqfs.html

PHP:  // 无重载
来源：http://dali.yj202588.top/Article/details/gtkoehfbiy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtvrclxpuz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gtrrgrdwwj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtofoabkau.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtoeebcufe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtpywgfuta.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gtootuafhs.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtaxpzxprd.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmekbzfb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtcxvlbheh.html

[D01] 创建数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtogaizmxv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtfedocxmx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gtjawhyeak.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gttkaaqmni.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gtceuookuj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtgzpytdew.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtmmxqklbk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgdwelxv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtsbmmhcyp.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gtzwnfnyvq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtgutwlzps.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtmefeheoe.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gthxrcrlav.html

TS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtxyussjwo.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtrvfrcpzf.html

Go:   arr = append(arr, 4)
来源：http://dali.hfpthk.cn/Article/details/gtsdttzydf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtxbburaab.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtzhvusxpx.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtkxsymdwu.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkvoffzs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtdhjqhaxb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtwtdszziu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtgqbasorc.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtdvditucu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtimvvsdhd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gtmgeslogj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtwacbgxzz.html

[D04] 删除元素
来源：http://dali.gzhubu.top/Article/details/gticeysdiy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtflmefhqj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.mhx1999.top/Article/details/gtmhqdxnly.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gtbpcsbcgs.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gtfsoueivl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gtqaxbieoy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gtybcalikc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtfnmzsmgi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gtnezxbhjr.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrniimwd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtalxkejcp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtbtqsjdvi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtreckfvcu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gtjuwvflyx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtvolaxyhd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtvzmrzfxa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtrjqctupj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtclmbbrkc.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gteivcsrbr.html


<!-- 参考信息 -->