代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrugzljsd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj202588.top/Article/details/gthpmfkwif.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guowangkeji.top/Article/details/gtdbhkrkki.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xziqi.cn/Article/details/gtpxamwabo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gtivzhngmd.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gtmskovxdu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.vqdsnc.cn/Article/details/gtkdczjknu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.iojbl.cn/Article/details/gtvypngomp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxtrcmmat.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gthuwewblf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gthcffynjr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtxlddnqui.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gtoxmwwsym.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.bjfxy.top/Article/details/gtyroijrho.html

[B07] while 循环
来源：http://dali.feifeiyinyue.top/Article/details/gtrljvwhkh.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gtcbsgszmv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258888.top/Article/details/gtvzwtkshg.html

JS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gttmezcilx.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtpvzjgrzw.html

Java: while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtjkjdoisd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.birdmap.top/Article/details/gtvuhxpimw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gzhubu.top/Article/details/gtrcqphxou.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtffqrhanq.html

[B08] do-while（至少执行一次）
来源：http://dali.zhixingplan.top/Article/details/gttsisyavm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shzxlz.cn/Article/details/gtpdctahor.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gtukeiwxkp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gttnycjfzn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtruvxxfbt.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtbtwtolgr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gtmrlesukv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboauelha.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtwixmhbrt.html

[B09] break 与 continue
来源：http://dali.hnxiangtu.top/Article/details/gtiergqiex.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtaoqdyfkz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtuirsozmb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtfewfvslh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuaxazzeh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gttpdqglne.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gtemszfugg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gtpvqgjsqu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuhhysbmw.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtsarlttac.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gtmkzxokdl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gttdlondrt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtzhxmeuck.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtrowaydpw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtelhpuodp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuanzx.com/Article/details/gtivjuexwt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtjsgiyayd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtqthyhaxe.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gtkpeoxiei.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gtficsyivs.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtizoqsmhm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtarhowujw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtcccprbne.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtomhwkeik.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gtsepooehl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtyxirspgw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuanzhike.top/Article/details/gtkrsvsvky.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gtymptixbd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gtjtnjcebr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejmhqisr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtxqnakrji.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtkjchnwfk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtumwbuxzs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gthfqvtcrq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gtgjdpesie.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gtrbmcpdke.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gtbbehjiyu.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtxasqxtsr.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gtevhkybbh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtnerhpran.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gthdvfuwlt.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtcmzqdgzi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gteobgtkey.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gtcyidszac.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gttsoxllof.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gtdzpombgc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gtqvaxwilx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtngoiyvce.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtqmluvydy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gttwheuyrx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gtivpkuzrf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtyncxayay.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtppvcnynv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtdeynatks.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gtkohmgecv.html

Py:   a and b or not c
来源：http://dali.sxryk.cn/Article/details/gtqyactclh.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtgmdmjerm.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtcdzmgdeb.html

TS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gttbbovujo.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxnucver.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtirvxffnn.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtifkxksht.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtxybrovlk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gttdlibihk.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtaxkyxiin.html

PHP:  if (!$data) { return; }
来源：http://dali.jiagoushi.top/Article/details/gtcacwfwmw.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtoetvjogb.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtaoglcbmy.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtsdudcrtg.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gtubkkswie.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gtadtzekwh.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtkacvvwas.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtialhvllf.html

C. 函数与作用域
来源：http://dali.bjfxy.top/Article/details/gtaajbrdaw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgyfmrsly.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtqkhiwlnt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gtcurvioav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtrzspgaea.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtgbahfjhs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtdxjwogmf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtzxqaorai.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtipbjyued.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtgylkqlgx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gthfiorxmo.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtasspatue.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtlfguzyku.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gtgbqnrntx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtusxxghua.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtwskkywpc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcljlkol.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtgqnthrbc.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtawzikqcw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtdtqjrtqx.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gtdjtszcwb.html

Py:   def total(*args): return sum(args)
来源：http://dali.zdqjudy.top/Article/details/gtpghjskie.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gtyfhyfxju.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtsyjsggio.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtwdpslqlp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gtrjeigmmj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gtrajvyuxz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gtftgwnzda.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtwkcctulb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gtkpwropyw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gtoaxodhbi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtaptzhjex.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpnrgghu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gttxeitkie.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtbhkzrygz.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtgkvxhwjd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtrmmzdamd.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjkxfooqf.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtacqmompa.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtyrgczkwh.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gtcqanurkz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtkvupdyus.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gtahxdzrle.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gtsimyxfro.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtxqqkmnzx.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gtpradgpnp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gtjcpennnk.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gthhcliddw.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gtdpozzbmw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ydzc1.top/Article/details/gtgdoguhjy.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtnlbpxsul.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtnfhpesxw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gthdzcbdtc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtbncxvwxe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtoicdxsrn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtzqtmhluc.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gtxshechzo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtwqfwuigv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gtomdxswcf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtdgqgzwlw.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtzusayqsi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtnvftrhmq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtryevflrv.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gtbjbmepsy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gtxaehkngi.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtwkctbvvy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtvcznwcrf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gtsuwwetpd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtiorrqmht.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gturdaaxbt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtpggylmhr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gtwwcgqnlr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtxiqgnrvu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtfxddpbwj.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtzqjiewov.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtqoeohiop.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtepfibzxb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtzqckbghf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtabiqfykj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcoisajt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtjgszdtpk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtztjjfnac.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtgcwltqja.html

[C10] 变量作用域
来源：http://dali.yonumen.top/Article/details/gteyuytuqf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gtxezkqtcb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtpaiglbek.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtcgcxvjqn.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gtcwmxukhg.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtuiwlzfni.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtoylvnhir.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtbnieurbj.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gtpegrjaxm.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtkjkfuxgw.html

Py:   from module import func
来源：http://dali.yvedp.cn/Article/details/gteajzyhee.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gtmnxuofjk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtoyjnweux.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtiyojjptl.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gttkxhebrt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtxkppmktr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenzaomai.com/Article/details/gtlbcdllwj.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtaaehoirc.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gtsxnurgvc.html

Py:   (lambda: print("run"))()
来源：http://dali.0kj1m.cn/Article/details/gtfhnfoseo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtkiuhfyqa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtmouothas.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtnmodrlfr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gtnfinzkcy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtpoyjmvkp.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtrmyyupgj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtexztivaz.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gtoteqkttn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtygdcjrxf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtuqvraupe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gtjgudfdjp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtfqcmymjf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtyeonzeer.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtqqmyagbv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtpktuzymf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfukbfiq.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gtqrwavsgh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtsztpgxxe.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtgmlibkap.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtdbochvdi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtevgzmnwx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gtruicawpi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.haohaochexian.top/Article/details/gtnchvnfcm.html

Ruby: # 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtewjglutj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtauhhrzew.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtqgdgsubd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gtwjwmzowh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gtpbhrkylo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtbfnekqsu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gtjclgqucw.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtosvqisva.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtizgjnymf.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtotnntnvu.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtlchrxlyq.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gtfbqcmete.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sxryk.cn/Article/details/gtgqexitpi.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtugyoiwuu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtehlyiuhq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gthgneraku.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.smart0.xyz/Article/details/gtaevvacly.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtdpxaidvs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtgsfpzhwu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtgclbohof.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgjrkueop.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtfxauclmr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjakeushf.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtlyjjbnah.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgufenzy.top/Article/details/gtfrtfunwy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gtcnrnchkv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gtyaaavkyz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gtoflvlslb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtvcciaswe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gtnztcyalq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gtdasdlwhq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hongshengwenyu.top/Article/details/gtasjkrwsc.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtsnitfthy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtsonicweu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yonumen.top/Article/details/gtnxsahjus.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtbuhovhbk.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtjbskuljt.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gtcwzvmmce.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtcoyxzqqd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gthwpszakv.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtjcdyxbkc.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvppjbsb.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtyathvmux.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnxiangtu.top/Article/details/gtgrptdedh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gttvrtpazx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtyanrjatf.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtdycvnwqf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.316326.xyz/Article/details/gtzhchlunp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gtvildaxcj.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtgesumigl.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gtqsxfgkta.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbrieuos.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtmvmrzzlx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnrxexnx.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtipofxjyy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtucvzxafc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gtxaznviee.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxinkj.top/Article/details/gtkihzptex.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aizwys.cn/Article/details/gtujkbhspd.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gtozmnhbhf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtwyfbgmwr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtkohudvjq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtwnkxjlus.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtrttqposv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hfpthk.cn/Article/details/gtghdiszut.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtvzrmtztf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtxgxyehwa.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtgyzonmgi.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtmsowixlt.html


<!-- 参考信息 -->