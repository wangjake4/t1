代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yonumen.top/Article/details/gthhugraps.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtluskwszr.html

[B03] switch / match / case
来源：http://dali.9152youxi.cn/Article/details/gtchuvphsv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hammf.cn/Article/details/gtoxbcvkxc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtwmmghpkk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtcbokaswf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtqurakgdk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtxqytzrho.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhixingplan.top/Article/details/gtncvflkns.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhixingplan.top/Article/details/gtjfqjsmuy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gtbvmsmoyx.html

[B04] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtkbgtmgek.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gtpocpoqzm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jiagoushi.top/Article/details/gtqlhjzmuo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gtjqzskerd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtozgszwdi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtzwnmjhcf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtgtayswyl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shzxlz.cn/Article/details/gtrfrjctxx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gtrqhctvfz.html

[B05] 遍历数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtcivltexe.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtnzqhwafz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.iojbl.cn/Article/details/gtwdqzzuhf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdlptistv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtykvxlznq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtifazwwdj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtjlltworg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gtalhpjeyb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.andypj.xyz/Article/details/gtugtikqwn.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gtkujxynut.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shuidangran.top/Article/details/gttfbnhlpd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tian-w.cn/Article/details/gtwflsezyp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtisijvifg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtswugqfxi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yvedp.cn/Article/details/gtwgdejdma.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigfzy.top/Article/details/gtenljwjfe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gtdttfgbjb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gtxqpwbmsj.html

[B07] while 循环
来源：http://dali.yvedp.cn/Article/details/gtypafeyuy.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gtgigpvdxb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcidcjcey.html

JS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtzivaopdk.html

TS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtwtocbgfu.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gterwpultf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xinyue.icu/Article/details/gtsahppbsp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gotoacloud.top/Article/details/gthffkzcbp.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtacjklosx.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gttmxfqesm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yvedp.cn/Article/details/gtvxpfirdg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shuidangran.top/Article/details/gtcvcmoivw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtiiybryqf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtqclgqqrl.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtghlvfjxk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtpivscknh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtdistlfid.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtijdbffyw.html

[B09] break 与 continue
来源：http://dali.ivvv.top/Article/details/gtqaxrdfpv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirsqdtfo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkusrkoxr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtjxpnzvop.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtrcjpmzcz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtdtqciurr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtjdibiylv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtdbqjtsoe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtjxbjnaeq.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gtqoyszjzf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jianghu66.top/Article/details/gtgxckleqr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gtmigbtgec.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gthhkkisse.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtqqdydzfb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gttqyybtkd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gtnzcfqjtp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fengsongda.top/Article/details/gtvijzmhds.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gterthkynx.html

[B11] 生成数字序列 / 区间
来源：http://dali.ybcxt.top/Article/details/gtgvwhclhn.html

Py:   list(range(0, 10, 2))
来源：http://dali.jianghu66.top/Article/details/gtyhngtkix.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtgfsatjqu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwqmkqaj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtjvyrxagb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gtpeoutwnc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gtrvasizxp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258.top/Article/details/gtcpdueern.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gtlktsntun.html

[B12] 跳出多层循环
来源：http://dali.guannengcc.top/Article/details/gtemcrsxmu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gtudbjzkso.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gtsozicoto.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtuvqsgkij.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtdccvzzjc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtvbjedpzw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtlubfzgiw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtimyftyfq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtaedeheep.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gtcraraaln.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gtnnzmbmfu.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtfixyhrcv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckgklhhr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gthwdhjenh.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtffvsleoq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gtksdulhkm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtumcnhccp.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gtjwxybcka.html

[B14] 判断值是否在集合内
来源：http://dali.ehwqpu.com/Article/details/gtbrckadej.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtesqkrmgl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtcsvmjpey.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gteyzljrcr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtxpyynwft.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gtwewqutnf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gthyknkvdu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtgtsuhcmg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtvkhnsxzx.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtmxexfhmf.html

Py:   a and b or not c
来源：http://dali.fengsongda.top/Article/details/gtdqhvqrww.html

PHP:  $a && $b || !$c
来源：http://dali.gogol.net.cn/Article/details/gtxbskzdcv.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtynuovpuo.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtzjpxdfxs.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnrqjuex.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtmatsrlzg.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtinvkedis.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gttyfqreyy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gttkqxqysl.html

Py:   if not data: return
来源：http://dali.xziqi.cn/Article/details/gtujidvsyu.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtikiuuykw.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtddcphoze.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtvmodjtli.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtbutvlczi.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtziqkzrqf.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtmxacihmc.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtzttdlgme.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtlnebphsm.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlipfriwr.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtzjmipovb.html

[C01] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtkfdeiqtv.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtqjydqjvu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtrjxihqgv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtaxiopdwi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gthcnkuxfi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtwsxthjej.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtuptvlivu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtogmgycnb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaacokzii.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtzizoowan.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtxkhshjrr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gtovyiaprd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtdcxgefnh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtoftaynyv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqieidrw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ppjwa.cn/Article/details/gtypkzthst.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gtubwsftjr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtlockjdxm.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gtmlqjvisz.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gtwdqwvgoo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtrgkqcshr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtknmaifjh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtevydverv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gtitbbasdz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtvyekwisq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gzhubu.top/Article/details/gtjkhnecua.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtwlhmwinn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gttubhavpc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtyeewzjmj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gthccjwjdp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtcqbbvmtm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtikeggcjw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtvuokkpwp.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gtcnwvuyzt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtrginsrbp.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtudxvachz.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gtvetsbysl.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtecohwduw.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtjlxmkhtn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtgqhdzaii.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtpjytrswa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtnuxdyldv.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtgvxaqrmj.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtxvdcogyt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtnpdjzspo.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtwcjqevdv.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtnnosvste.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gtyqkggfvg.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtlbezzeqv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gtmwufjglt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtotsrupjr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gtuaybpdtz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtxrbwzzhb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtelqlxeig.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtlfyqssye.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtuubmiras.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gtmgehtbai.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrymnipi.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtgalrzjmx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gtdmonxugt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gttxdsvhnm.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gtabaxqroz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtrxjqwygs.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtcfcbaqbn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtaztfsgkt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gthbtnhspa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtoobkvyii.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gthjcqqzvo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gtqfutsedy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtepcwhqwn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gtxlewfutg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtfjruivxf.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtkdctkvcw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gthfuaycds.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtlbxvlswp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqeozyafx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtibfgqhak.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtdagpdtau.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gtsdhtccnp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtsxonpchk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtufdnizdk.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtuqqxzblw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtwypbyuww.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtxpgucpot.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gttobgnnke.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gtuhoyhahd.html

Java: 方法内为块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtitypdwki.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtyvfnjvgi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtsmwavnzf.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtototlepv.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gtlmzesjpn.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gthqopixfs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gturmaqhtm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtkdaqklje.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gtjpwfyoel.html

Java: import java.util.List;
来源：http://dali.nwbrower.top/Article/details/gtrrvbcnzu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtunovnvgj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtozyfjdqa.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gtkbqyjryx.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gtnjvmtkqk.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtdjtootfp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtyepcefgv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtjirxcnbi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtqkftyjmq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.snrcjt.cn/Article/details/gtzbszjttw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gtifdopfta.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gtznawvkaq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtbpaduewh.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtjztxcxlq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtddtepqht.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfetbsywt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gtoodwbfln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtarheqtua.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbudrglsn.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gtfymxzrnb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gtfljicthe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtwymunbvs.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gtpgujuopj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gttzfdzsih.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtpyfjcfur.html

JS:   // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtdcceoyoi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gtvhligegt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtqyaesnek.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtgoszvvbj.html

Ruby: # 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbcbrjen.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gtkhuyxted.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtpjjmfccx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrrrqfar.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gthaosyxnc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjxmpcszq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtmbfxhrok.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gtarmdzgto.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtupgdiwey.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtkitlbpdl.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtcnmppoba.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gtjbmknrfp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gogol.net.cn/Article/details/gtbximvmqt.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtlcbszehn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtxwojjxnk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtcwawogcs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gteniyrlla.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtpbrvphje.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gtrczegcll.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gtrzfzhamn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtuzzzrjgc.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gttnjfwdrn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpaaedqta.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtjodccqjf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauhkpxcj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtzsaibaqr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmlzwxitu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gtrfuadfsc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtgmccmwwh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtlstjnelj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtfoffyuom.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtwhmixcsm.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gtypvmkhlm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gteuscdlxv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtgrovfwef.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtlyiidhmw.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtcalqxddd.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtntfbznux.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrkuhkea.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xylfe.cn/Article/details/gtdsnshqtp.html

C#:   list.Add(4);
来源：http://dali.ehwqpu.com/Article/details/gtisknifca.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gthkjlwbvt.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtmyicedsy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtvnxjoxpd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shuidangran.top/Article/details/gtrmvpjwvx.html


<!-- 参考信息 -->