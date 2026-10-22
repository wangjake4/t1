代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gt2hhludfdq.html

Py:   for item in arr: print(item)
来源：http://dali.wangshuangyany.cn/Article/details/gt2akaglegs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dbzmikjc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gt2bakbajlr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gt2zdkjsigg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gt2ofihrrja.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shuidangran.top/Article/details/gt2xovgoclf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.svipenyu.cn/Article/details/gt2ulevxgok.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gt2yaezxkys.html

[B06] 遍历字典 / 对象
来源：http://dali.316326.xyz/Article/details/gt2zfkivskt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gogol.net.cn/Article/details/gt2jamafdti.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gt2qygqsaph.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2szzvjnwv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gt2rggwydxv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guowangkeji.top/Article/details/gt2clhlnnau.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfhdatek.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hammf.cn/Article/details/gt2lowafitb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.meibo888.top/Article/details/gt2kwofevul.html

[B07] while 循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybtpmzon.html

Py:   while i < 10: i += 1
来源：http://dali.bjfxy.top/Article/details/gt2gfzhqjil.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.smart0.xyz/Article/details/gt2fcjbxsoc.html

JS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gt2kasqjofc.html

TS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gt2lkuzrcej.html

Java: while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2nmxoptmy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqubhgud.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkdwcqdl.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2vjlmeicn.html

[B08] do-while（至少执行一次）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ictfyoup.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.birdmap.top/Article/details/gt2mvoyqqke.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2jcaxunxa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2sbwvafxy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2rmfgfrsf.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2ischyrig.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gt2fitexgyr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2thjfpfti.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2ixsqjmsy.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gt2hkwjqgxg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxfaqtoa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2fnazudat.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2xeentoao.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2cznwgxug.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2ulijcqgc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdzcdffo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gt2rigtazsh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2cjkpauxa.html

[B10] 遍历同时拿索引
来源：http://dali.jqgfzy.top/Article/details/gt2bcmkqcme.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258888.top/Article/details/gt2adcmlwev.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cqqwz.cn/Article/details/gt2kisvpxzd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gt2kleqpeve.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gt2rnckmtau.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ppjwa.cn/Article/details/gt2kljbdqeh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gt2mevchxby.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gt2ctwuvtqn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gt2eugzfrhd.html

[B11] 生成数字序列 / 区间
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwoqhuvd.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gt2bbvyvoui.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2pwyyvmym.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsysklxv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2iheyogye.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2dcxlplea.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tianlin.xyz/Article/details/gt2ftwzblms.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gt2ufurpnyz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dndgtpkw.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2giuhfbgd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gt2bplutccm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gt2lcqzlkmq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2yvvqszhe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2aresocbs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2lgicbgkt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebsijcji.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sysykeji.top/Article/details/gt2nbbfjnir.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gt2ugaskhqd.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gt2mrbidoyf.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gt2rudtasav.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxqueefk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gt2sdutqdai.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2azxchxzp.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gt2lxupdcxs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gt2zewodfvo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gt2kysexhof.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gt2givxcrbm.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gt2jmxzdmyb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gt2agtrbgoo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kynqrrfn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2pxwsofrp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gt2upcavpdu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2dvdgafxb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gt2dkvkjpvw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gt2fuuyahlx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2hbjmxmtj.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gt2fvesshth.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gt2mikeurxs.html

PHP:  $a && $b || !$c
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpyughfh.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2whwozuus.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2fiakuouw.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2ypzvxnqb.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2swmqztyr.html

Ruby: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwfxxfkd.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2mnnvyuuh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2pbytejhh.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gt2yxfobtwt.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gt2bwvbcbvq.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2svlmqmhe.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2yprprddx.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ordwxuov.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2nfvfkbzr.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gt2xmqzzgby.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2aiecccde.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ecnejjss.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gt2crusowcl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ftxfrskx.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gt2meomhxtn.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gt2bvjkrdjk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2jhbswwbx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2ensnogqj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2thpdfeyd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2swyymakn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cheryme.top/Article/details/gt2iuqfwzbs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gt2efmwupbb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2vwhofaus.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gt2xkuaspnj.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2sdebuflc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gt2wvygbtud.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2dzsmsivp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dkcggqsw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gt2tzdcayvn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfoleuop.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gt2mnieocnn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gt2towzxfmf.html

[C03] 可变参数
来源：http://dali.ydzc1.top/Article/details/gt2jqxxsvcj.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gt2knhokgql.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2iutegnkv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gt2bvojjolx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ojsjwgih.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecbxcxqe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gt2rnppnnvt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gt2juneutoi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zadqfxyz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2bibgwblh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tianlin.xyz/Article/details/gt2bqdcalyp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gt2sgblvzkv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2nsmajrsw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gt2nkgjopmz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gt2aekgfcvw.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gt2hteqztxz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2rfxytxsy.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gt2nafhmfsh.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gt2xzvnjdhe.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpoxddwt.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gt2wlufrztf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gt2vzpjufbn.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gt2bhuregnp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivmpzfxv.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gt2srtaubzb.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2miahsdmn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gt2epplznyp.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gt2vdhgcpjq.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gt2wfcxruda.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gt2eqozejab.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2yjfdkozx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gt2ighfvhty.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gt2ewcdiize.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gt2etrvwomh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dvdigaap.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gt2yqthlgiy.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gt2uhugevbc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gt2fhmaropd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2wnpgzieg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gt2dcheuepp.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gt2yrpeuiok.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gt2hbbywyvz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elzeoerr.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iezdphep.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxuanxn.top/Article/details/gt2liefvoae.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gt2jyvivndw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gt2awaklahs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gt2kkndpmiq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2omgetdeb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gt2fqmkqyxy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gt2tycurnvh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxxoogvv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gt2winbtpvi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2vhxjdrdw.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gt2bbregfaw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gt2mavkhysh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gt2nfjnpjik.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2hxrtmesn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gt2evmqkgcq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2nqaypwju.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gt2nrchwprf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gt2sqfnxniy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2prkfqhvg.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmqwmtbv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gt2tcbnffld.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gt2qjlvgdrg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vspqijwp.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gt2nugwrfcq.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2serqdudb.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2wypnzxrv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gzhubu.top/Article/details/gt2xqdwukeu.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gt2dzdfohjs.html

[C11] 模块导入与导出
来源：http://dali.yj20258888.top/Article/details/gt2ipovmgke.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gt2uglcnimp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gt2fwrhoodn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gt2tjdpajdo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2gvjldbew.html

Java: import java.util.List;
来源：http://dali.chenjidiqi.icu/Article/details/gt2esmyfdpt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gt2cdaqxorf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spoljjmt.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gt2gnrljwxl.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbemhls.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gt2xflutibj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gt2njeaxvvc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2bylvolpd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2asinruow.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqtcwtfw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gt2qezuyetd.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gt2bnejhaqr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2wfngilkn.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gt2toivmczg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gt2ckfbfrtc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gbffgfsj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gt2hrpautky.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2phogpyvv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2qyztvpzt.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gt2wqopzwxq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2dxnypdga.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gt2mdfankoj.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2pcwjmmtx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gt2olvmfqob.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2daaxmyse.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2qnoznciq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gt2zhbjxeom.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gt2jqownzrn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gt2ctzfmfng.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gt2ofoclpzs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2suqarhca.html

[C15] 解构 / 展开参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbymhnli.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gt2wbonoopz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gt2hwtnbkus.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qshkzjeo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2qxgtyzhe.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gt2sqgghctp.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2xlcrqafa.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gt2eydzwhxr.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gt2qpvvtlrt.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poxymaoi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2ssxhjiuy.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gt2vumvsrha.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.redwolf501.top/Article/details/gt2vrtqmtqe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gt2roqjavmv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2jiaakbih.html

Go:   // 无重载：用不同函数名
来源：http://dali.yangfankeji.com/Article/details/gt2zuvivizo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.9152youxi.cn/Article/details/gt2iqqfiful.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kzparhoh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypfhazfy.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qetgmvcg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wrmbesyv.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gt2auwmnrgs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crybxdic.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2lzcijbhs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gt2clcxwzzi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kazfueuh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gt2icpemlia.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2qlvnmpyf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gt2armdwvwi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gt2dwldkifu.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gt2whogfmjg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gt2szbpdjqs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2frfdlwsp.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gt2xtxhwmuo.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2hccwzqyr.html

Java: list.add(4);
来源：http://dali.dianchejie.cn/Article/details/gt2zhpgjrcs.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2bimkluem.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufjacdje.html

C#:   list.Add(4);
来源：http://dali.meibo888.top/Article/details/gt2hjbsbiuw.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2zioqctyh.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2uqjfijdf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuaopam.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gt2wczbgqar.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2qofjkqqv.html

Java: list.add(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2duvudhxx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2ylcjgtpz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gt2tddbkgcw.html

C#:   list.Insert(0, 0);
来源：http://dali.guannengcc.top/Article/details/gt2vvdtkgja.html

[D04] 删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmysekuf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2lhitodwf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2jqlkcnmy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gt2kaplwscl.html

TS:   arr.splice(0, 1);
来源：http://dali.wangdashe.top/Article/details/gt2gsnluavq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gt2uharghpb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gt2mluvrvjv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuwgkagy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzzjrpah.html

[D05] 访问与修改元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dygcedmu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2izvmotmj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gt2aymlstdx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2iknulqnl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.svipenyu.cn/Article/details/gt2mnklsnuw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gt2qwfknhte.html


<!-- 参考信息 -->