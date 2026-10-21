代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daria6918.cn/Article/details/gtroweptqj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtnnlqljbg.html

[B03] switch / match / case
来源：http://dali.cashguo.top/Article/details/gtrkjlwfqh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinghuilouyu.cn/Article/details/gtanpfcsct.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gttttiplku.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtlqagqeab.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gttqeucyvy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gthbkzbdws.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cashguo.top/Article/details/gtkvxrxjnl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gthyhiwanf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gtbmbmrxbq.html

[B04] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gtekexbuik.html

Py:   for i in range(10): print(i)
来源：http://dali.chenzaomai.com/Article/details/gtwsymjyuc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangdashe.top/Article/details/gtwsvjiaif.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvtjkhoa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtavuohkov.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjexvotur.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gogol.net.cn/Article/details/gtlumakwaj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtjshokopl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtmolkdynw.html

[B05] 遍历数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtkanjrheb.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gtyxuqkkzr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.birdmap.top/Article/details/gtbatyvcsw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gtwwnmrwkb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtjwmyivat.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtckexsdeh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxinkj.top/Article/details/gtrehnvzff.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenlongwang.top/Article/details/gtzjqrsfhs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gtahgbmtbk.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gttptfvwsb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.birdmap.top/Article/details/gtraaegeta.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtgphxgwhn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtjgucxlmy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gtdihudfcz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jiagoushi.top/Article/details/gtmdnsiioj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.birdmap.top/Article/details/gtspqeraxr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gtktyljjcq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daria6918.cn/Article/details/gtwyadshcm.html

[B07] while 循环
来源：http://dali.yuanzhike.top/Article/details/gtfiwkaphr.html

Py:   while i < 10: i += 1
来源：http://dali.tian-w.cn/Article/details/gtaaydymmj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.snrcjt.cn/Article/details/gtzkydapqq.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gthlcugxsc.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbviytift.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtijvnmkom.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gttuzdhuyj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqqsmyre.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbvansvfx.html

[B08] do-while（至少执行一次）
来源：http://dali.redwolf501.top/Article/details/gteiuydzxv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shzxlz.cn/Article/details/gtmlxgbiil.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtgdgkboei.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtsdisqnkd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtncfyjnpk.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtgaxydjme.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtnmeztbgf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gtipivenvw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtmsfoulij.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gtifnfihbq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtzdonsnra.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtjsnhcugf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpnysurk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtzxrhzudk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gticbdaosk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtvnzktxvk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.havefunace.top/Article/details/gtzbextxec.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gthltelpwk.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gtzspxvryx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gtrqgmrgaz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.bjfxy.top/Article/details/gthdltfvkr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtwqkokhou.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtthtzmplm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gtdwhjidjm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gtskqfkwhj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gtpjjsmubb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gtasgmkxqi.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinghuilouyu.cn/Article/details/gtwesirlvo.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gtzjtuljxd.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtygbxldsg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtxnfuivbt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtttethrpp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gtzgdwnbpy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtwguopzjf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gtgcrrvnrm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gaohongyu789.top/Article/details/gtvdjobqul.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtelrwwlwl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtsdsuenoi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258888.top/Article/details/gtqzegxepm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtnrwsowtn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtztxttghz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtraapkvkv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gtqthzexhd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtzpoxwipf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtrfmvxvkj.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gtlbpjsqas.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtpfanxxko.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gtbjevlogh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtievxmlll.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtvqheznxi.html

Java: x instanceof Number
来源：http://dali.tian-w.cn/Article/details/gtgbbwvmdi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gtpvkrwfkt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gtmijmyjrc.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtlomaripr.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gtzaxircmq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtrnggoldy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtibxeibdi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtyvvckxjp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtevedllqa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtwdtcrcpc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gtanypmgiv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtfuvgewcu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtyvicgjed.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gttivoisay.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gtlhdxjzio.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gtdcywomfz.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtjtmyyncs.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtqubuvugj.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtaukzkbsp.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gthkuzonxo.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtnbueljpa.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtdtfrgtel.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gtehevjaqs.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtvchrnxas.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaackjeb.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtnikvsafm.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtimgcahjp.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtcaadaadv.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gtfwwjsovn.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtjdhhkulk.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtriznzhsu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlvyzweob.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gtxqywqcby.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthfkndikf.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gtwjfkqjep.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gtudulwdiz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtijxkhjuq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtcblcqyen.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtwwxmzkke.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtcztanewl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258888.top/Article/details/gtoemkkupx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258.top/Article/details/gtfubflias.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gteuwfipux.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtxshvvebs.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtfbcebngg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gturbgijky.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtdisrxkvh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtopsypbzz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtjdqygzwh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gtsxlrgeqh.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gtfiegsqaq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gteckurvfk.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtkajaymsk.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtgturnyfg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gtbrogsdzu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzvniaacb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtfdrsnkrm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gtlralwvhs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gtsdcfeyce.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtrzaebqlo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtftwubrxp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtycawwnov.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gtkktntwmu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gtcbulagwq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtxeimumwb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtqrhspisx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gtmgioyulb.html

Go:   // 无：用配置结构体参数
来源：http://dali.cdnleiting.top/Article/details/gthqvsgmri.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtththkqrx.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtxgjymgww.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtjntrszqw.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtitlhgwib.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtxmstgyvk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtxbomajqs.html

TS:   return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtiwdmphgn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtsbnloenk.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtgeyquorr.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfzudovm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrnfbeqs.html

[C06] 匿名函数 / lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtlixipwqn.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gtsrcuhhhs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtqukaohkc.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtrrleyrzg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gtydcexpsi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gtxeitncvm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gtpbxxmccf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jyoumei.cn/Article/details/gtibjctdwl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtifzpcpfr.html

[C07] 把函数作为参数传入
来源：http://dali.cqqwz.cn/Article/details/gtrupuupgb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.haohaochexian.top/Article/details/gtfwxiynao.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtyvmvgcjl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gtihpijlgf.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtcruwykmq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtivcfrzkm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gtqypvmtsm.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzgwvdtp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtkcorqxxr.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gttztnrrzu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gteqlinrbr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gtsnrqcily.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtrnfpysga.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtinpslzgq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtrjhzalnk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtqvxyvlph.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gtzkrrckdg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtpfufmnjd.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gtqzvmndod.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtwafluxwv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtcqteucrh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtxwzzhfym.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtyzjuwpzg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtfprlkzlt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.meibo888.top/Article/details/gtlcrzifme.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtgcwzwpqm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gtiyabxile.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtvmaodcne.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gtmtxnnage.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gttctmyugd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtutgzwibu.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtimmauywq.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtbyhtzkmz.html

Go:   花括号块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtldtfvbrn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzhpssti.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gtzddxhprr.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtibrnpjxz.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtmrxyusyl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gthduadyrf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtbzzzqltl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhixingplan.top/Article/details/gtvnujawig.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtbrbnanxd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtrrchqbcd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gtvtrgbvlj.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtryhgzhtb.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtgjdatszz.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gthvrkvvdk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtgwqawokk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gthqukqodf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtxicsqrtk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gtcvmoizpf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hysaishi.cn/Article/details/gtqksbleom.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtpqotzsoy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtbhbnxjws.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gtilgyggov.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.svipenyu.cn/Article/details/gtqfamtyhr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtdviyizsv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtntffshqd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gthbarfrly.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtvoehbkcw.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gtjpckxlaq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtvdeolkxx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtzleivqme.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gtokrcahtm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gthahhzsit.html

PHP:  // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtgigcfoha.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtrrdgchqy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtxcrcrzsc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaktgdlu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtgsdtenqr.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtajueubcn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyielhyij.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtvykcyjpu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtsjevfhyn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtkdlfmgsu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtqnrloyqe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcuenpwmy.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gthhezejmi.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtxkwbfilc.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gttvkldxpv.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtezdnaqrs.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gtxxdoktsq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtzzwvcmvc.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtghkknhgg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gtofktimmo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.vqdsnc.cn/Article/details/gtpkhmvhhf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtpfidxtnk.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtuwyjxuqi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gtucuxmhss.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjgadiaqg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtoggeolsa.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtwyiqwpbp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdimvronf.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtjriabxla.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gtujyatceh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtqhajgahg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtgdvbjvfw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtyuuctqut.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtbzjjafqx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gtmzxhjbdf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtmjeptyqt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtrihzniht.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gtdzpwrnkj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.vqdsnc.cn/Article/details/gtiblgqmgh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtsrgmuarv.html

JS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtkogaplsf.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphniaflg.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtaouxxvmp.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtanzshumv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtzujxisjz.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gttqjzdvbv.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhfjrxzr.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtklprdjkh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gtlultpboy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtbqcoizrz.html


<!-- 参考信息 -->