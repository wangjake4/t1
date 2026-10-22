代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gt2mkxhhtil.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258888.top/Article/details/gt2tlhixbvr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nwbrower.top/Article/details/gt2hvkoeeyh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuanzhike.top/Article/details/gt2tatfohpv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2klczikja.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2pcldrova.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gt2rfossfhh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gt2erhsgpiq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gt2fjemvbvb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gt2hvuommlz.html

[B03] switch / match / case
来源：http://dali.hywenlv.cn/Article/details/gt2jvdhigdb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nwbrower.top/Article/details/gt2fmncihfd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gt2sfgvuoiv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gt2ifwqrokk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2zuhhfius.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etnpafka.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2mvsegqxy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gt2tzvlpxww.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2ubxygeav.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2ylppbnvw.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gt2lmzupoxv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bouoxbwm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2slzuytqs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gt2wrzrnpvx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2sbaktdvg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rarpzkto.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cqqwz.cn/Article/details/gt2acqmrvbd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.c1oappe.top/Article/details/gt2ojyaeomu.html

[B05] 遍历数组 / 列表
来源：http://dali.sxryk.cn/Article/details/gt2vaywkoxh.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gt2zboqrjeb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.fzhhl.top/Article/details/gt2ezqvwohx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gt2gmqdhqjs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gt2jzoclwhw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2rnsifnzp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangdashe.top/Article/details/gt2ewiwfeph.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gt2uvkhfaoo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2mymhylkt.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gt2lscrjvit.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gt2gfxraczq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.svipenyu.cn/Article/details/gt2kxcftnsd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gt2trakwazj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gt2ulujnest.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yonumen.top/Article/details/gt2abipzjgi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigfzy.top/Article/details/gt2ikmlgnfh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.mhx1999.top/Article/details/gt2tdurjyan.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlqxawfq.html

[B07] while 循环
来源：http://dali.hysaishi.cn/Article/details/gt2kxhlzfcj.html

Py:   while i < 10: i += 1
来源：http://dali.wangdashe.top/Article/details/gt2ipkpvxzm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2krhxqinj.html

JS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gt2pqhgjnvw.html

TS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2vpdhylmy.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fygzhtst.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gt2krywzsks.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gt2lccenkok.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gt2kezszvmx.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gt2odlufydu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gt2prutmtad.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2diuzwzml.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2jiutbnzb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2otpetkgk.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lnszyciw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gt2spxgtrva.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ibhscuob.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2xpqkkgcm.html

[B09] break 与 continue
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzvpuzan.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gt2tmentmvz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmyxicrm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2tuwjgifb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iojcwrwc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2ezyfnleo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gt2amccksva.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gt2qggizmnz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ohntlocq.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gt2ykmzfvfq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rifjhowb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gt2uonlokds.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gt2deqtqcvn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2alviwzqb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gt2ptkmnsip.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gt2hyyorfff.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258.top/Article/details/gt2ggwywuxs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gt2vaupoope.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gt2cnvmsyxt.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gt2obluvkbs.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigufen.top/Article/details/gt2iovitvfa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2umttnwgp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gt2vjpylaik.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gt2eftvqrrk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gt2enytqass.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2xeeqjhwx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gt2ptnehkhh.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gt2xrmozpnq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gt2kaqpwdlw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258.top/Article/details/gt2ksaedisp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gt2rvyqekcr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzbwcsbv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2lvmxqpsd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2iojehbmw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gt2ytwisbwx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gt2nnlhjpdo.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gt2oincgins.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gt2bpnuqzlr.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gt2teappzlx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gt2embnnwdi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gt2nqwusmlh.html

Java: x instanceof Number
来源：http://dali.pengpengdd.cyou/Article/details/gt2bobdjpyq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gt2oivbbvna.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gt2zgvqycab.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gt2vztwumbi.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gt2heioobra.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gt2ahxnczsr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gt2xfforwxf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gt2xorzrujj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2zndtqfor.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2yotsugpo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gt2lxqmmcwh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gt2ltvhwwpo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2mbwqkluh.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gt2qlqnopmg.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gt2yrwijvfa.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gt2qpfhyodz.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2qpgzpqjb.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2kbefiqpj.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2lbtmamdf.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2fumjauya.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbbgezfb.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2ffbqfrpn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gt2hgsqrfba.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gt2yxtdgszr.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gt2dnjinzvy.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etmyukfd.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gt2yvyqevsw.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gt2zxopvzoo.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gt2nkshkskm.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gt2nftainri.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2tbjujfaw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2omknaukd.html

C. 函数与作用域
来源：http://dali.zdqjudy.top/Article/details/gt2lyfjaknc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2fwjqnivq.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2losssknc.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2vboeryod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gt2hjihlchm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2tsjasxiu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2lqilzcrl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xthditbj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gt2obtmggbs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxinkj.top/Article/details/gt2tcakixqd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2vzcwkhph.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gt2uuvnnrii.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gt2dpjskqph.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gt2kwxbgeny.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smiddgyq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2bggyxkcq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gt2gcdfoukd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gt2dzjinqll.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gt2ndzhiwrl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gt2qdvloryo.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gt2luifxyjv.html

Py:   def total(*args): return sum(args)
来源：http://dali.aizwys.cn/Article/details/gt2pwudclqc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gt2kozlfnmg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2myxkbobv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2ltpdicls.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2rgnjlbxg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.quarkkingdee.top/Article/details/gt2ufsjwgsv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2equduisx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gt2odmukuju.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gt2qgkuaakx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gt2yqxeqcxd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gt2vkthfdmj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gt2osxpdrrr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gt2joknuoxq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gt2lkfbxyit.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gt2usatznzs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2knidlndy.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mppfjtvr.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gt2pozpqnnj.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnooscxc.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gt2nqgtxaiv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gt2plwgkkvj.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gt2kcixrzma.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gt2lrjcunto.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umfpubkz.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2uynonfwf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gt2ugxfczha.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2jzxpjgqp.html

Py:   square = lambda x: x * x
来源：http://dali.wangdashe.top/Article/details/gt2izemdsjx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fumzpmjq.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2kepwjvjt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2yljrdzcw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2hziosvbr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gt2nmenjlpy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2tvmmzvrs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2gzcwepgp.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gt2shvyislw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gt2yugymlwy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2navaawoz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gt2sshwcwgk.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gt2slarghxt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gt2rvlotyto.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gt2ragtlvrz.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gt2ugpojyyu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gt2jbeaplfc.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gt2lrztgbyq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2qynydogp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gt2vzrlidkb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pwqnhgsc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gt2faubsstc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2jmbducum.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gt2slbxdvnf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gt2zulwyrll.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gt2oelwdwii.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvdjeurl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvrkygzp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2rqdvzlwa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2ltidhlhl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzeclelp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gt2owqiwles.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.quarkkingdee.top/Article/details/gt2jrjukjqs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gquiqqlh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqzcgspv.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2sblfeuei.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sysykeji.top/Article/details/gt2wkfrdbug.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsgqfxtl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gt2zxsxfgrz.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2cljqfopu.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2exmeyduv.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2khukffov.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gt2jcqzmchj.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2tchvpego.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gt2jrwmmgwa.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gt2gfjmisoz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gt2wewqyugn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tanke756.top/Article/details/gt2fgxvxghi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gt2xqbashqd.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gt2otxisnav.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gt2ovpucxka.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gt2plcpazpr.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2wqalesmo.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gt2dyxtkcym.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2mibqcdcs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gt2qffiigfp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gt2oywfbvjp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gt2mvcqsupf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gt2awlpygrp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gt2rjwmglcm.html

Ruby: -> { puts "run" }.call
来源：http://dali.guannengcc.top/Article/details/gt2ocfndmsi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gt2yarajkas.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gt2wdsithbz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2tfvfomym.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2uujdnrfl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gt2rwmtcapu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2vxaokhao.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fllrfjwq.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gt2cnbatguh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gt2keuqirfx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gt2qqnrdadg.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gt2dyyusovz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gt2xkdslevx.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2idfmukdh.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2qhychtec.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gt2ajshbvsy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.316326.xyz/Article/details/gt2pocacors.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2rbcyrqib.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtkiglcv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gt2lkhfjqte.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxbbesuy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2buwfybzd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gt2nwyxgegx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2uwqmawth.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2omwlyquz.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gt2wutbifgn.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdweuxhd.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqinunqo.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gt2tvvlfblw.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gt2uxftxtgh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gt2fatfmaur.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gt2dtkqlpcy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gt2yujmjulk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wetcnsjq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ytsyzdmy.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2cablbivh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gt2mnlwouhh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zdqjudy.top/Article/details/gt2huzgmxqe.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hebdbjzj.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gt2zlqljudd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2aaociacu.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gt2ajafrhgb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jqgfzy.top/Article/details/gt2vfspyjay.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gt2zqiditir.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtdnuaqv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gt2wwznzcdy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gt2fzvlvrvv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghncfjpl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gt2ovrcbaey.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gt2udgqrncc.html

[D02] 追加元素到末尾
来源：http://dali.fengsongda.top/Article/details/gt2gsddlvzp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gt2jtmhcrrf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2jlumzqly.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gt2wtkmijpu.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2furadmeg.html


<!-- 参考信息 -->