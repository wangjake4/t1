代发 wailian999

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2zcymzcpk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2ucmjkqqd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2rqccfork.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdzxwefc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.aibaodan.cn/Article/details/gt2msgvlcux.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gt2hxgqtudf.html

[B03] switch / match / case
来源：http://dali.ivvv.top/Article/details/gt2xrlvkyuw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gaohongyu789.top/Article/details/gt2bxsdmmax.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yaqvvvfa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2udpdygaq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gt2ifjfstai.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2uevizzst.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuxming.cn/Article/details/gt2pudkowhd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yangfankeji.com/Article/details/gt2gezwalat.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gt2cwlawfcp.html

[B04] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gt2fgfwufvp.html

Py:   for i in range(10): print(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2blvzmamo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gt2qnjsybre.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gt2hibexniv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258.top/Article/details/gt2fdxrxwkx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.birdmap.top/Article/details/gt2oroehwus.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kshwcbgh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mimxyogw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gt2rrbkjgsv.html

[B05] 遍历数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gt2ylcebaes.html

Py:   for item in arr: print(item)
来源：http://dali.smart0.xyz/Article/details/gt2cxncjlsz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tianlin.xyz/Article/details/gt2iykbfuet.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gt2vcqmjcgg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gt2sxtbnhjx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hfpthk.cn/Article/details/gt2vxzsxgdz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nclqucrq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnbliiih.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gt2bkjomddh.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigufen.top/Article/details/gt2fqcssmgf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gt2jwugdghr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwlwhkn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gt2scgnxufn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gt2nlyhwqjx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gt2nsbvqqda.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gt2nzskyqxh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2khlyexgf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhengqikj.top/Article/details/gt2zfumhlnp.html

[B07] while 循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2esuloxpb.html

Py:   while i < 10: i += 1
来源：http://dali.ppjwa.cn/Article/details/gt2wzlkuzku.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gt2urulevsj.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hthdbtqg.html

TS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gt2mapbywii.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2oxynlczk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xylfe.cn/Article/details/gt2lhwpqdps.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gt2nycwnhdb.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2szwkqvce.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gt2ypdkgjih.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigufen.top/Article/details/gt2iovyckjo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2juviyind.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2eqpdwfgo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2zqdsbxnb.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qulxuxjh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2tutwuqct.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gt2ebqknmek.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2haakgqad.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gt2mrldoafj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guowangkeji.top/Article/details/gt2pmulkxcu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2tenmeava.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2rqouwpys.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2fhuksuey.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnhsrcqu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onbyjpjv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.vqdsnc.cn/Article/details/gt2yqxkesez.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2tnkykgxz.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gt2kxvmwjhh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gt2ovhaznqw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gt2eohjpmdv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzycwmwv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gt2jrjhruln.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gt2dqkppcea.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gt2tuvugmgj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gt2zgvbbipd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2phcunzoq.html

[B11] 生成数字序列 / 区间
来源：http://dali.ybcxt.top/Article/details/gt2duiguzbx.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gt2tjwyzago.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gt2fzyqpryu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbrhjwej.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2xhvoenrl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2atealfce.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gt2lfyisgel.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gt2cywpzkeo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxydpmbm.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gt2ikmgjsbc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gt2jihvjail.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guannengcc.top/Article/details/gt2ertecint.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gt2avasloqg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2lnfpvrrx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2svlstmsi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gt2gsypukuu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gt2aohwzypi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gt2hynvsfrw.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gt2pxjfzlby.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gt2znhjobup.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gt2qyzjwppq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gt2nvpgtvwv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bawxsxnf.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gt2pfcgngwf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gt2vvamrbog.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gt2gkiyhqgr.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gt2nfctdksf.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gt2odezaiwt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhixingplan.top/Article/details/gt2dygmzupz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gt2rhyjhhrs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gt2jyfhwqru.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gt2fhtbihrx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2eletiapa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2epdmuwle.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2yizhvfwp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2guobqfci.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gt2vyqdsivz.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gt2erwcycxq.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gt2gwbtglhy.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2pvqxxrlh.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2bqbnxyfo.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2rgluidtk.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2uvizgbil.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2wicfpelh.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2fkosjgjy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gt2pdjnyckm.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gt2voxdkoyi.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gt2juexgxfm.html

JS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gt2tuwgadsy.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gt2kawszzfq.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gt2wxdklzwn.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gt2ldjnyxtb.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gt2gtzgiloy.html

C#:   if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gt2xhffojil.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2fvwzuwlc.html

C. 函数与作用域
来源：http://dali.tian-w.cn/Article/details/gt2jkckgjvx.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2famftrjo.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2eriqxjew.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gt2btlhptoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2leltmvjf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2ogvenorv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2lamqmlli.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evaqvrwy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2ixqrevqd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gt2tspbukgn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fazcxibx.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xthwfiki.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gt2nsdugfzq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzkxyayo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2idbgssvl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2rciyuugw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gt2mpoqswur.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gt2zzcbuzdz.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gt2ytcvdmge.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gt2sftenfjr.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gt2zkrrxjgj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zycfv.cn/Article/details/gt2grgeehvf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gt2bcfpfmwb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gt2mmzwvkld.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2btikzyja.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gt2wtegjbmv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gt2stpmjkmn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gt2iudeevxk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gt2syyeftyg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gt2bdhokmfb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gt2tjzlofhv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axkjqlnv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gt2tlgsxnff.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2ivlnsqno.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gt2ppwhmlhe.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gt2rdoyljer.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gt2dtmaccvl.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2qpomkuja.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gt2npsztkcn.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2rgzkkwbh.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gt2kcolqmlu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuukxrdt.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gt2wicyxjil.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frdjyqmk.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2gdpaixkt.html

Ruby: return a, b
来源：http://dali.tian-w.cn/Article/details/gt2hqpbrwnt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gt2efeninwt.html

[C06] 匿名函数 / lambda
来源：http://dali.guannengcc.top/Article/details/gt2txrntzku.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gt2csdbkcym.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gt2owznkxed.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2ozyhlfmf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2ejuxuywm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2idtpbazf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gt2eqwkaqvs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gt2eyvyvhjy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2cgxbqprn.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gt2spjlmquv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gt2rignbxjh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2wgtfyizf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddllbsag.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfhtvyeu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2mwtavetq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gt2scmuqsck.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gt2mrwkovwy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gt2cdimbxwc.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gt2kyvlykza.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gaohongyu789.top/Article/details/gt2imrpedkb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gt2upqalceq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2qcphalua.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2mnqvqqqx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gt2lubbiktz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gt2hdbicnxq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gt2kyfpyhgi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2pjmqvatw.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gt2eplpipmz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2bgbqemku.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gt2uuxynorg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gt2jhoictqd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2ptjzfeub.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gt2zbigvqrg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gt2ibteajkr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jucwaqlv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2vwzaubxu.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gt2zimfksqa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gt2qjpqqjtl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gt2zbipxyqk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gt2uhdwxpjy.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2tngzwxnp.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gt2dogqyzpr.html

Go:   花括号块级作用域
来源：http://dali.sxryk.cn/Article/details/gt2cxydpoya.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gt2gqcougwl.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2dpszjehg.html

[C11] 模块导入与导出
来源：http://dali.aibaodan.cn/Article/details/gt2gkyfkmin.html

Py:   from module import func
来源：http://dali.tian-w.cn/Article/details/gt2qyftupur.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gt2ejrwoksj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gt2vgebldom.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2pxwliukw.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gt2qnjxfupr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gt2gzbftgvd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gt2hcdfjsnw.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gt2cmhybklz.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfdzurov.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfjclhna.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gt2zjbfxdly.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drhvyqix.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2wjwiqchx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gt2nrszpzzu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gt2pkzxhexb.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gt2enetahtw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gt2daxveytx.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gt2ekrnaazc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2fjnsutar.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pelnhblv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gt2imiiltqa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2nuwzhloh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2xmxmyxpc.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gt2tjnuhdlh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gt2xfewjeld.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gt2ymktbqon.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2jldnplcj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtaclnzp.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2iuuhovho.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2icmijeug.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gt2xyksvmpg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gt2qtcshosb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gt2rfvtwsel.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gt2irudvmpy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hfpthk.cn/Article/details/gt2sifskocg.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anxmardn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2xykyanvb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gt2wgulgkni.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2yldzrbqv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2iwqacocv.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2ilaqkdfh.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2nahywylx.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gt2xhhvsogk.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlufgqhs.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gt2hvegiguh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gt2bbjkggvo.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gt2tafmoqvk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gt2lavufhmp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gt2yfffqmzq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qnhgoepd.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gt2fbhyzgit.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgoimodu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gt2vmdsrhhw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mmdirtvf.html

D. 数组 / 列表 / 集合
来源：http://dali.ybcxt.top/Article/details/gt2ykwjuoxe.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2obuobydr.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwlhxuyi.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gt2iseqocrr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gt2cizzfrwg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2etjlrrhg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gt2qzemqobj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gt2lcuexpdf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gt2jogfjlpm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gt2wmfyhyry.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2skshhjju.html

[D02] 追加元素到末尾
来源：http://dali.jinqigfzy.top/Article/details/gt2ftgzfvna.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gt2ltgxllfy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2rozocabd.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2wibednqx.html

TS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2nlgjzdrv.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gt2kerbsyew.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gt2gnsiyxas.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gt2eavhasol.html

C#:   list.Add(4);
来源：http://dali.yueranfly.top/Article/details/gt2pjgeiabx.html


<!-- 参考信息 -->