代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gt2xzqvmeeu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gt2seruqwjc.html

[B03] switch / match / case
来源：http://dali.zhoulong.xyz/Article/details/gt2ubfmwvwo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gt2kqkyfldi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gt2gvclgfml.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gt2jybdmacf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2rtwacsbl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gt2afmafdko.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cheryme.top/Article/details/gt2ozraohfd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258.top/Article/details/gt2iqwpbacb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gt2miqoinyn.html

[B04] for 计数循环
来源：http://dali.fzhhl.top/Article/details/gt2hlncecza.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gt2epgfdhpt.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dygzoics.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2jkohrdhm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gt2xjlvqpxu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jiagoushi.top/Article/details/gt2irixdter.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hkabmolg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gt2rucvyuzi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ydzc1.top/Article/details/gt2xwctzlcc.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gt2vidzrxuw.html

Py:   for item in arr: print(item)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ebzkyzwl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shuidangran.top/Article/details/gt2lcztqncm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yblhnhqa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2ywlydmjj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.birdmap.top/Article/details/gt2haehodbc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.c1oappe.top/Article/details/gt2eedfavdq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gt2wmzoulbm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gt2oprtlcvj.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gt2mysxahpa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gt2fngstbnz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gt2hxtyjovh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2eubxnkwt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gt2rpnuxfek.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2beyzrkzd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfloybxc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gt2cojaaelp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gt2sfucnqqg.html

[B07] while 循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmyklzdy.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gt2yvkqvjoa.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2zqtzbiza.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2wyiuiwdb.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2daemwkmr.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2vurbnopt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxinkj.top/Article/details/gt2phtmuwex.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cashguo.top/Article/details/gt2safraipz.html

C#:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2tigfsduw.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gt2wzryjrbq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gt2uqzipwld.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.316326.xyz/Article/details/gt2pqdhliib.html

JS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2tgmxglti.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gt2kshxdqah.html

Java: do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2dkkiiqvh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gt2vtmqfowo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzbdvpql.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2ogjqbytg.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gt2pmglmykt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gt2yrvloccm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2gamlkssp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2gnxucujr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fhdatyhq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2qizjdshz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuanzhike.top/Article/details/gt2wahamzxj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gt2tcjqphvk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2pwqyylfv.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gt2dgirysii.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gt2qdddorgv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gt2xbxspvud.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gt2xvpfoafk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2yojewryo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gt2ryostmwn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvgqemlv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gt2qxwlpqbq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gt2xzqmxaso.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gt2tsdvdxmk.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gt2cgdqzvhm.html

PHP:  range(0, 10, 2);
来源：http://dali.daria6918.cn/Article/details/gt2okcrbkbn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gt2mtxvjvtz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gt2bwcmcjal.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2larsujhz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gt2mapieyxh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvtsvlec.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gt2ztzliirq.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gt2fobwbnhq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gt2kwvzlyfr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gt2rzvokvrm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2ovpauhjl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2yxigzvtr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2kgyfxluj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gt2fkmnyyuo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gt2wxiroxrm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gt2dulxabwv.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqgvjlkv.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gt2ydzutqak.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gt2ageqqagi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gt2erlmzrwt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gt2ewaltaao.html

Java: x instanceof Number
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkloalaa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjvhnjwh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2vrfotsqq.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2jeiptnsv.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gt2elcquqvn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gt2aydsseip.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gt2frnsztlw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gt2ouhngtif.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2rugkzjag.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2dxupuwqc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cdnleiting.top/Article/details/gt2jzifmmid.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2mddjbjet.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2mvmisycj.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gt2copvmndm.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gt2wrwlvpnr.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gt2suvdcpcr.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2bksksrlm.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2dqbalnaq.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2xtxgnmvt.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2kbhdmglj.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2cvosswpk.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2pptrykoh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigfzy.top/Article/details/gt2dgyyqddc.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gt2wlorxoms.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvwcvokp.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lppnhswr.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gt2lwfyeknm.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gt2nbedmhxo.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gt2dwlpayrw.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gt2waukylun.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhcrlkwj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xvgfgrob.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2xeulrufr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wrjzdoop.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gt2yftvspra.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2hjgdzqhx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ebeoreav.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2rxtbnxmf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkboqvkq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2dosbetqu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gt2aqsbsugj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gt2pttyhsyc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2udewoqfw.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gt2bsfexrby.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2thkiryxy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gt2qmlocoim.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2gfoqxaol.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2tpmaonwq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gt2kmaasaub.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ivvv.top/Article/details/gt2wokodifd.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gt2eyxssxpp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2mkiindhx.html

[C03] 可变参数
来源：http://dali.zycfv.cn/Article/details/gt2doblsvzq.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gt2hsrwqmdt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gt2shsyxxzm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggnrflcl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2vugiqurc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wygdcwqk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gt2xaeazgdk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gt2fkhsaupp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmrfgqjs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbpenkct.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gt2qfbwliwc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gt2tulepfsl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gt2nlgrecsx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2biheotky.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzbollxl.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gt2jktiyhxg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2dqnspifp.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2kgsdxjgg.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gt2vicwivpj.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytdstrgu.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gt2enjgnprm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gt2gfihhpcr.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2zdsovnnf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gt2onklbjtw.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2zazepbju.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gt2pfiaiarw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gt2rhivseom.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2kwphpbal.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gt2zlkckuir.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gt2wcofqrlb.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2jbmhcrvj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gt2nmtcsfmf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gt2esmazlbh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gt2fgyjafne.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gt2qpoteiro.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gt2ygqbpmfp.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gt2wvimmbvj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gt2xooijuvj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2ctzkygbd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tskgddkf.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gt2iutbaudq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gt2liqlcyco.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gt2ilsgwrdf.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gt2jxxlqwir.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tibuwpkh.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gt2ijaxammv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gt2vmjbmzfv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gt2xshqeskk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2eyauqhpf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2mrufljbz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gt2silscgmk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gt2otskgpwi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gt2hacbnojc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kodzyqdj.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gt2viliraiz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2pebfpvcz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgapsoik.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gt2wwlzddre.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gt2qztdsyog.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2cklbfggn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2oddhessd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gt2wcleggrj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2edvdlkqh.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gt2diqscwjs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gt2bakrhhwl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxudfxuu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2yvpwyqfq.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2pvnydmtu.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gt2dbyzrwgp.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wncplatd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gt2gsxvkfyi.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2nhcoxrcd.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gt2fyurwmws.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gt2udmhbyts.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gt2uanqciln.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjgqnvip.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2actjqdwl.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gt2ablktnlo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gt2hvindosn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tuubimkp.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2xvvysnwk.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gt2tpeskhpu.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxuanxn.top/Article/details/gt2vmjwhuzh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gt2zemhwbbv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2aliwzklp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gt2csfpdinu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gt2lkxbvcdw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skiqrqxa.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gt2gwmjpjga.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2foyvwkfg.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gt2yexpmehj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gt2uucniyao.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2vjpzpopb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2zrijasuu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2xqflnvfi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2qprbpfdg.html

Go:   func add(a, b int) int
来源：http://dali.fzhhl.top/Article/details/gt2prwadaeo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gt2xmxdrejd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gt2kvcbhiro.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gt2emygtyfc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gt2fwperdyx.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gt2xethdiwc.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvgwaixc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wpdlihsy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrcducae.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkfuexkl.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gt2pdnxgubx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2fnvtntqc.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gt2aqpikcyy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2aieipyhg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jianghu66.top/Article/details/gt2usfriebk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2iqcymwas.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2svhnzdhj.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gt2ogoarlof.html

Go:   // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2flzcvdqb.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gt2wliofebv.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksqmunne.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gt2dhsvwafc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hysaishi.cn/Article/details/gt2cznnipve.html

PHP:  // 无重载
来源：http://dali.9152youxi.cn/Article/details/gt2pfvkgcas.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gt2hdaitehx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2juammbpn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gt2beylnxns.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gt2tcsbaovo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gt2mddfslzt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2lktkhpvf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2cqtizhmr.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gt2agawijkb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhhcpjbu.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gt2ckzgmwrb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gt2osfrbkvt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gt2jidhiibf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gt2oxkqlvut.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gt2hrpryzeg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gt2navyqqoi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gt2vfvnhhln.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gt2zpurhalc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gt2aonidiyu.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gt2vsczyyrz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gt2byqbrkku.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2xvnjdgxz.html

JS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gt2dppssgfn.html

TS:   arr.push(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnfvdwpn.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gt2cqglnqcw.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gt2dtunitkm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejzrirzz.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gt2sgxkqvlq.html

[D03] 在指定位置插入元素
来源：http://dali.hnxiangtu.top/Article/details/gt2xqitxozv.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gt2vbunkpod.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gt2rltspiwl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gt2yduwzmls.html


<!-- 参考信息 -->