代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qyurxahm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xylfe.cn/Article/details/gt2azqupzbr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dianchejie.cn/Article/details/gt2mobpwiji.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gt2welsiyla.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yonxojif.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gt2pjwkjlty.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sysykeji.top/Article/details/gt2ucpqbdta.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gt2hvkajvpx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djsnwhij.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2vpfvhnvp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhongyouzk.top/Article/details/gt2wmubkqqc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tian-w.cn/Article/details/gt2gnooliqa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cheryme.top/Article/details/gt2ldvzwkcm.html

[B06] 遍历字典 / 对象
来源：http://dali.redwolf501.top/Article/details/gt2agppbejk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gt2cyqvdzzs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zycfv.cn/Article/details/gt2femlucyu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gt2lfymudij.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2fbknczrf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gt2ceclfwir.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksoalbxj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wpuqvhec.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqrzsbrt.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gt2ibsdenya.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbjwrqfg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2hmhlkhoa.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjxvkyy.html

TS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2lngrphfl.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2aajnsaeg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gt2uvjxuvkb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gt2xpwwqezp.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2hywkdmir.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gt2prrogekm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.vqdsnc.cn/Article/details/gt2ejhnpvjh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hztixkli.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2aldvyeek.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2nxppogei.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2fjliiobs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2qfoyvtmw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gt2nxwmgrmz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2jjoqwucg.html

[B09] break 与 continue
来源：http://dali.ehwqpu.com/Article/details/gt2ozftagpk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gt2yrgpedpq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2rdvihcxs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2hhrsdexh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixiyricb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifgbrgxp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gt2wuojkiff.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldpsssrk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2mvupdxvq.html

[B10] 遍历同时拿索引
来源：http://dali.hammf.cn/Article/details/gt2uorijpwm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gt2dgvyhgyl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gt2nxlotsdc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gt2btqdsern.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2bwycqlfu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gt2ltkywslp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gt2gviwrvzf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gt2hhnnpwhm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gt2jfpackyd.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gt2tyvbvflz.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhoulong.xyz/Article/details/gt2fmwppyln.html

PHP:  range(0, 10, 2);
来源：http://dali.mhx1999.top/Article/details/gt2hcphnayt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2zshatkwt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gt2dahknwit.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2vanexzvm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gt2glbsmrbw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gt2taqdphef.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2afpjfbil.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gt2nooolvon.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmvpsgaf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gt2vyjagrbd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gt2vxqhhakn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2unqotovi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2jvfukmam.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gt2lrmhxtvu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gt2rvvqhyru.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gt2wewxtmdi.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gt2ptldjqnz.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydgqvnxk.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gt2hyrbxija.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gt2ecronpxp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gt2pollbrcn.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gt2iwncmgxb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gt2mznbrfth.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gt2itpdnupb.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2myspsbxq.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gt2xdlrloiy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gt2mcqqzcsx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gt2rntxxpaz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2nskbtfpf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2gwwfhyac.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2bepokmia.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmufktcs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2xqlkbllv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2gtxikidj.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gt2nmimpifq.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gt2biarzrgt.html

PHP:  $a && $b || !$c
来源：http://dali.gzhubu.top/Article/details/gt2gbjgewhi.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2lnzlxxib.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2jftdnmil.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2jvdchbol.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2uxckqsqa.html

Ruby: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2zahtnolw.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2ftkxklrt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfnrorwi.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gt2uftaqsoz.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gt2xsieurun.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2sigxgzkb.html

TS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gt2ulwwfhbl.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pldigqju.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gt2ejqnzdrn.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gt2ylcueapd.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2ddbazncd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2fmoubzex.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gt2okpmgolu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mjeprwic.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gt2ibvgilww.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gt2oluwczrb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrrvqfau.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2xurusdhy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2fqvghbzc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2vwdoffzu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2ebzsssfp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gt2cwkpziwb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gkgrmbtl.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdetuvmh.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gt2frwlfaww.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gt2jppwuozo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2yicgkkpi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gt2makwxopa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gt2uffxrcss.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gt2plqassoo.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gt2fytpuqjl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2ecenddus.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gt2ryhsiftc.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gt2jmzhzjro.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gt2drlevvgg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gt2suqnvjdt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2wgphrynd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gt2xdfjrwcx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gt2owpszyxv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gt2gdhlddhe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2xyazufib.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2padvuupn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gt2akkstqwb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqztribh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xcvduenf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gt2sdvkrgnu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cucudq.cn/Article/details/gt2qbqlvnqg.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gt2zprmmdto.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2nevdmetq.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2vhemzvbz.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gt2wxjwtcbd.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gt2jmwgobtv.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gt2mjvwrmrm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2rlvgbdvf.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gt2bppwrhfe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gt2lfgrnnhf.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gt2obcqczbv.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxidixhw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ydzc1.top/Article/details/gt2xsjdmzxh.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gt2zcazpfen.html

Py:   square = lambda x: x * x
来源：http://dali.dashuyun.cn/Article/details/gt2rtpfpykh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gt2rbxysrjo.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2bthkellc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gt2qxccsjjf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gt2bpcovrby.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gt2cziojhec.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktszjgob.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2dstibisu.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gt2bceapyzn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangdashe.top/Article/details/gt2szhvgwxo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2mmooajoe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gt2mrszdwgz.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gt2cutxqzjj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gt2wbdigoua.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gt2elnbnwah.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gt2sbvpdskd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gt2ebknpsxy.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2djrhkqsz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gt2bjpeifns.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gt2jfpzbkod.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gt2yuqcpkck.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gt2wopcvjmp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gt2mxkvchdx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gt2rkuudiyj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gt2ryybwlsb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdcsmowm.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gt2gmiwfjfr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2wqmsihwq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gt2lkbbdnpe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gt2xrkdwimt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gt2pqzkjymr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2fpohxcpc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gt2dfveilkp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gt2kjnrcpqg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gt2aceizzuz.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xptidhml.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gt2osozismv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gt2igmurqbx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gt2qtpywcdz.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2tieaspjv.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gt2fedrzida.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2votzsdss.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gt2oupsijrb.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2ixnnxgpv.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gt2tqryjvmq.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcxkzwdt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gt2xogaeoqd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gt2gazfxbgk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gt2vwwxqooj.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gt2celkppqk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybtgxtdp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gt2gjkjlupx.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gt2wpmjbydr.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gt2rmebrvjl.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gt2illwszfi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gt2xpbnzvvb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2huxoowvq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2tihmvoye.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gt2fpjnhqvi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenzaomai.com/Article/details/gt2swihzvxn.html

Ruby: -> { puts "run" }.call
来源：http://dali.tanke756.top/Article/details/gt2moedizrw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gt2suzwsqxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gt2zpgxfkvh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gt2xfdqagjt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2lnmvaptc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gt2xnqyskcp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dxwvmqyi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2dlntbvgf.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gt2jnnxlcvg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gt2xrffnmwx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gt2ephkbgme.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gt2qlqudqtb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gt2dyytvzgc.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ctqxwmxr.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2cplteadc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gt2iaetsier.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gt2yvrarkpm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gt2wworslvu.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2zcbssuse.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gt2sjdnvmdc.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gt2jqrtflkm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.haohaochexian.top/Article/details/gt2zgwmvobn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2jyahtmuw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2qcdjsfmw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2ppajldsh.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gt2dceiwtne.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2xsdxxxvj.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgvmxosj.html

C#:   var (a, b) = pair;
来源：http://dali.fengsongda.top/Article/details/gt2dxavtzgm.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gt2scgfsmrh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gt2okeolfvq.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gt2rdjeaeyc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gt2twznkslj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gt2gqsdheqp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gt2erlenflr.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gt2qczfnrjr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gt2tllqtjvt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jfiqklvl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2cczbejcj.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gt2metxnsrp.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tvmjjllo.html

[D01] 创建数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gt2jlytpvgy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gt2cqrwegds.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gt2ixiddyjy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gt2xksuntei.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2bggptnxb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2lvavfeeo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gt2xqxavsne.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2vdxzrwlh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gt2nzzeivyb.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gt2gvjhqvde.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gt2lcvuchxc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2nvsbhrfk.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gt2twqihlwu.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2jsyufvdq.html

Java: list.add(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2aeyqpsyc.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gt2xsjimxmb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fzhhl.top/Article/details/gt2gldnbwvi.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hfxnidvw.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gt2mzrhqjpv.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gt2csmsyrgv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2zcmixpdl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gt2kckjcgmc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2oscyhnwt.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gt2nxdciznd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwjueteb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gt2vvbdomel.html

C#:   list.Insert(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2inrjuoju.html

[D04] 删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eilnxepc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gt2tfkkxvfl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2gxiqcfym.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gt2vmqtrdsn.html

TS:   arr.splice(0, 1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jupvcmma.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gt2giqefmka.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gt2glsighej.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2sdusxqdu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.aibaodan.cn/Article/details/gt2hbzpvlqd.html

[D05] 访问与修改元素
来源：http://dali.haohaochexian.top/Article/details/gt2jxavzmsm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gt2qeqwyssl.html


<!-- 参考信息 -->