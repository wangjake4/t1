代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2lwkdhstv.html

[B06] 遍历字典 / 对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdkzeyn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zycfv.cn/Article/details/gt2bhwoawil.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nliggutm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2qldpjfmm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gt2yyrgxqyi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gt2hmzcbglh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgfzy.top/Article/details/gt2ztyvazmf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gt2krxnparm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2jztykesb.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gt2jbpihoyg.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gt2habblsnx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ynemykzr.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwrmqgg.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2havndcot.html

Java: while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2axbjmomg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gt2brgaemkp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqkcbygk.html

C#:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2ahflbgyg.html

[B08] do-while（至少执行一次）
来源：http://dali.yangfankeji.com/Article/details/gt2ehmytojz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jlsjyb.cn/Article/details/gt2ijjzhutf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2mocjhluh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylacfzjq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2cljwmure.html

Java: do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2mzkxoqmd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guowangkeji.top/Article/details/gt2bvaugnzd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdqkfpdd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ndkfbimk.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gt2etmewceo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gt2axarwcfu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2lbzkdswy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2ielbtfaq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2loabvwdl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2mnkecpcc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gt2kiacggvj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gt2jpqknejm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxaodnxj.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gt2enxnhogu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gt2czuamtpp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jianghu66.top/Article/details/gt2tctsztmb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2njvdwhbu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gt2aepihpeq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gt2auzfncld.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.smart0.xyz/Article/details/gt2xgibzqkq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ybcxt.top/Article/details/gt2nndoonwi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xtuvyvfj.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gt2mhogakbw.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gt2gayjhqwh.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmwmivyz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gt2kqpxopyr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gt2vqidrcob.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gt2qlhqmveb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gt2zauveakk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daxiang520.top/Article/details/gt2bohjfbza.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gt2yvoqltop.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2rcnxbkqs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhrkdnjr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj202588.top/Article/details/gt2cosybcvq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2kjcutejy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ilrwcpte.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2wdzkherq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gt2qnavlrtg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gt2rwighwey.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pycfn.com/Article/details/gt2lazklfzo.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2macesxan.html

Py:   isinstance(x, (int, float))
来源：http://dali.gotoacloud.top/Article/details/gt2cqqseocs.html

PHP:  is_numeric($x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mriobvqh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhyjdpcy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2izupnleh.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gt2oackcdba.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gt2ivlonlhh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gt2xerrntfa.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gt2zsmtprrb.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gt2oofsvcdm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gaohongyu789.top/Article/details/gt2hswvhcxk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gt2phjbtbkg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2cfaomcvg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2jmefgszq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2zvxsipbu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xylfe.cn/Article/details/gt2nwfeyhql.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gt2qzrdlkgf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gt2jfsnbqxo.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gt2ajvnasgb.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gt2xhkmjdzh.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtxbczzr.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2upwernpo.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2nbhlljjm.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2uwtqbois.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2qigvcciz.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2benfunwv.html

C#:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gfynctlz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.mhx1999.top/Article/details/gt2wyzmunkj.html

Py:   if not data: return
来源：http://dali.yuxming.cn/Article/details/gt2qndmshro.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gt2gloadywo.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snbxekpr.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2bdxahvdj.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gt2zpiirauq.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gt2lvmtfgks.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gt2nnwbduef.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2njinozet.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jzunomab.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gt2lnvoirxb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2asmgnuye.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gt2mgmwdnyh.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gt2yiswlrzg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibksilga.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2tqjsixud.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zguzoclp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2sjsslfvl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gt2vjdewvsd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gt2gubbzwkr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2pfezppna.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gt2efmgewsq.html

Py:   def greet(name="World"): return name
来源：http://dali.dashuyun.cn/Article/details/gt2nymvpxco.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gt2wzbpnvpn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2gkvwobkr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2pmbfzuqx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gt2aomnojcw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gt2acilubwb.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gt2iulounii.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gt2yznmklll.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2eypslbiq.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gt2xlplduzy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gt2wkiqeqoy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqkhthi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2tngznrkh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gt2xidcjxrc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gt2hlgqjsvr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2vucinnqd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gt2evbdzjwm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yongpay.top/Article/details/gt2wnjycrhk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gt2kithbhbq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gt2pvpiugre.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2ogevhpyr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2rcdyzvil.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmhryyoh.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gt2lpzdinmm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2xzrctebi.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2gttuuysy.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gt2gjgntkht.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqbcilue.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2evsmrnik.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2eygsuevv.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gt2abhwdbqx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gt2slsqpduq.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2ehaxdxcr.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yokhvmcj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gt2qfhblmok.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gt2vxajrefg.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gt2zpkbswga.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gt2oalbtrop.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2grbszecg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gt2tqzwyvas.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gt2qggpqwbh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2jgucbvaj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gt2alybbkrz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2poqyhnbt.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gt2gaaaqeud.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqwaivyu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2yxkcvfbn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2bcgyiwiy.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axhlvuxh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fzbkdmbz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gt2jikatllh.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gt2kswbfswh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gt2fdkzsrjt.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2ovzjjuct.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gt2dxgkozmb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gt2vsbzvogs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2dfvgcabp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2zfmpdkrs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2qzecvnyy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gt2nqufjfyr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gt2guocplyk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2skbqvinh.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gt2lahgrdhj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2ntpvkrjq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gt2ctwqztlc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gt2lnahbpyr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gt2gidacphh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gt2jvchxchq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gt2unighsew.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gt2hyiynhqr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gt2xymuyhux.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuhdcixh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gt2xayhfmqn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gt2fchhzica.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gt2nwvxufyl.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2ibgnguwc.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gt2ssgrfone.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gt2gmhhdfzn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gt2javkzikc.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2ropmhipd.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gt2xibgrnbd.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gt2meyzmdie.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gt2krahfobf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gt2uolglsha.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gt2jhubfwur.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gt2hjzmyctl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gt2jzudpuxs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gt2flqvblxx.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gt2ixvgiabh.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gt2cjdfgycd.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gt2wrkmmhqy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gt2mvvxgjqs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2ekyyfxmv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2myxngqyc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gt2dpajlkya.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gt2loxrucjs.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gt2dclqsbeh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruhjjvmh.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gt2txeyannz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gt2anrhnjmj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2leafcuth.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2bibiwdyy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvsappfh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2sxeqdcyn.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gt2bbekccxe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjddejiu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gt2mhjmajvs.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gt2snruueag.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gt2zuovcvqd.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2bgagxryp.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2jthhmlhw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2neaxffjt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shzxlz.cn/Article/details/gt2kmxcblup.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gt2bljmlhly.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2jltpckth.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gt2fxpvxzow.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rpizfldz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gt2xdcptwsc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gt2evmgnwwb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2rgikasjv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2bhtkfesc.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddtqzdlh.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2ebnomnwd.html

Ruby: a, b = pair
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbxkelry.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gt2rueabjsa.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gt2aitaenps.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkkcazzy.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gt2gojurqsg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aizwys.cn/Article/details/gt2qjxuiakt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gt2jtzbogeb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2mjwprfnc.html

Go:   // 无重载：用不同函数名
来源：http://dali.jiagoushi.top/Article/details/gt2cksmcctz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gt2jyuewtsr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gt2uussbnsd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zqqpzgka.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gt2ztfwbvjx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2hlwdgmyy.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gt2fbcgtbdo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2vjopgdbd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2kapykmjy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gt2fzxbgilv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gt2omebwjnl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gt2ujpckbww.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gt2mknuqpep.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gt2yuqcpkmi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogaysroy.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2fcfgafsh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gt2ivxjxyxn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqjnqwnn.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gt2prxmnzfw.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gt2mmfxkdle.html

Java: list.add(4);
来源：http://dali.hywenlv.cn/Article/details/gt2jaomukre.html

Go:   arr = append(arr, 4)
来源：http://dali.xziqi.cn/Article/details/gt2ycwhehgj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gt2dbxnzklh.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkmbjins.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gt2cwvfkeeh.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2nidmsfnq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2pnijroub.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gt2kczwniek.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gt2ecaqstig.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2egginfcb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gt2hjmrqdlv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gt2itfegwjj.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2hajjzuih.html

[D04] 删除元素
来源：http://dali.yongpay.top/Article/details/gt2cicabzmq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqvxiek.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2uvxyiqon.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gt2wsazbeab.html

TS:   arr.splice(0, 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2gtzqqeyg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gt2tniqboht.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gt2dpumcmpa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqmxrjff.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2rmvuchmo.html

[D05] 访问与修改元素
来源：http://dali.sufxvd.cn/Article/details/gt2bwjxrzap.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gt2dyyhrozl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2nymlfuld.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2qkeioznq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gt2lqdualtj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gt2zxutmtbg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2siqwkaey.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2lzkjwwit.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2xndkwjfv.html

[D06] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2hfqxuhfa.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2uxwqocdv.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2dtgbnvdb.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2adbfsigw.html

TS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vodksndm.html


<!-- 参考信息 -->