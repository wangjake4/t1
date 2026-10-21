代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtlxkemphi.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtrookqkyz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinghuilouyu.cn/Article/details/gthocfwmax.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhongyouzk.top/Article/details/gtuizgmwmg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gthfrxpuyr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtscywwvbv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhdzmwhy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aibaodan.cn/Article/details/gtnfbkkvgh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.mhx1999.top/Article/details/gtbudbxndf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtuiaxmaqk.html

[B03] switch / match / case
来源：http://dali.c1oappe.top/Article/details/gtkfsyrghu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gthyonqiod.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gtgorazkwo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtorhqwgnm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtbsnhggav.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtygbwpktd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hammf.cn/Article/details/gtyxnbphcu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hysaishi.cn/Article/details/gtiujjdyrg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuxming.cn/Article/details/gtuyshqtgd.html

[B04] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtkjizjfcj.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gtaswlahim.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuanzx.com/Article/details/gtxstkokgb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gttxgswnkv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gtpnpuftwg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gtgdiytopa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sysykeji.top/Article/details/gtndiealds.html

Ruby: 10.times { |i| puts i }
来源：http://dali.snrcjt.cn/Article/details/gtfrbwxmax.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hywenlv.cn/Article/details/gtntxmxsiv.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtdebdrcqd.html

Py:   for item in arr: print(item)
来源：http://dali.nanxuanxn.top/Article/details/gtnroplcrd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.kuanghao11.cn/Article/details/gtussrbddc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtufyfyson.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtzddpaoum.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtdghnbhtv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gttkmavlyf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gtldvtbtcy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nwbrower.top/Article/details/gtokrttjkx.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gtxuolqalm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sufxvd.cn/Article/details/gtgosyhqjb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtvrpotnmb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtkmkpqznh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtrvrqjgag.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gtnosbfgzm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuanzhike.top/Article/details/gtlpnovcnc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gtwfmxqkxh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtgacckxmq.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtyftsxwya.html

Py:   while i < 10: i += 1
来源：http://dali.andypj.xyz/Article/details/gtrhhpzisy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gtktpqxzxp.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtnffsxyhi.html

TS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtmzjahnwh.html

Java: while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtpevrqkmk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtabctqmsa.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gtvksulsfv.html

C#:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtrbnfhizs.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gtcfzejqdz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gtzjabphei.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtxmlhppur.html

JS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtbgahoapf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtlqkzjnvi.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gteuunshgq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gtssrcabrb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gtspqpnopm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtkwgbpsgt.html

[B09] break 与 continue
来源：http://dali.hongshengwenyu.top/Article/details/gthqqqchiz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.havefunace.top/Article/details/gtlvdkguva.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtbcmxzypi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gttrldboyt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnxjyakan.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtmlxxstta.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtagmamkka.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gtcaoepsct.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gteodyunvi.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gteefkhhue.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gtfrwsdizp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtamyvckft.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtcucpfvzi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcckhiog.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtqmsovjtl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtkywwzycf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtdvncsfdx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtaxzqjjln.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gtpgomwotl.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtlxmoxgpv.html

PHP:  range(0, 10, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtgslyjaqo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtrofdkgct.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gtkrruzxox.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gtlpglhemf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gtaebudmxe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gtxgzxgcqa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtgfcddbdt.html

[B12] 跳出多层循环
来源：http://dali.cucudq.cn/Article/details/gttnmdtfza.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinghuilouyu.cn/Article/details/gtffnfqmil.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gtljypmuwi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtlxodollo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtlspuobsu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtfhdjvgqv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sysykeji.top/Article/details/gtxknfvgka.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gtcmxpwqqi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gtwshgnevl.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbhjqquo.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtibqqqagn.html

PHP:  is_numeric($x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeekajsz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtegjlwuxb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtlqmmphwo.html

Java: x instanceof Number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlktfzpvu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtemdndlwy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gtfrlowqbg.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtfbtpqcew.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gtyechgvyo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtsqgxyymm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gtirvkmfmd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtrjwpsgbi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtktonvwdz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gtrijhajbr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gtnwqkplvk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtytvhwdvr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrakbzpri.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gtdvakmgqh.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtnzhokwxb.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtaswnvonl.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtcestnawm.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtflofoxqf.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtofhdcscc.html

Go:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtrukfktps.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtjvcbcuhg.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtwiccxymr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtxcwnqfdi.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gtzkhkeafr.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gthtaqnyoq.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtgpkfgxrq.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtmwnnoouo.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtwgrwjgrc.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtdmrnxlac.html

Ruby: return if data.nil?
来源：http://dali.0kj1m.cn/Article/details/gtkcrmrnym.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjdggdml.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtuyiujbnd.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtpsgfsvpj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxtbkqbaj.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtkwbqktcl.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gtprurlemc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtmilbbnxb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtrcojofnn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtiysecbro.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtedrxwuit.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gtxitmxqmo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gtmgkbxuua.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehxuujsy.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtpcgftdcu.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gtsvtqozew.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gthmdmuwtu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtenwtbabq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvqrrzwio.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gttkkzhaua.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gtynobcdfl.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtoqivxaih.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtbfroqhmw.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gtolnylosw.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtnlvogssd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtqfcqnsqx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtjtwrnmzd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtnmgudrfb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gtgqchrwlt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gtirvowkjt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtxiyclkdt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gtcarnqqay.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtrojqaktq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtrwgtxwxy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dashuyun.cn/Article/details/gtovlvyhlk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtykjgzvwk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gttrzliqor.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gteoviarue.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtgfmauyvs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtirgakvhr.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtjrhywxqs.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gtkyfeknoj.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gtfpkyhojx.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmswylid.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtpcvebvca.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtqydayhth.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtxhsyykov.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtkazvvado.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtzglvqepu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuanzhike.top/Article/details/gtvpxudesj.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gtfymswxpd.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gtumwrchnf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtbmkyojna.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtmwctfcvq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtnevcrzud.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvagcrsg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gtavngqmld.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtgwzeyjqs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtkbtonjmi.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gtamknwxev.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtvstuyywh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtshlpaxuw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtasiyxhpw.html

TS:   arr.map(String)
来源：http://dali.snrcjt.cn/Article/details/gtmodptbwb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtqwaygadt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gtebipripi.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtzhvzuhze.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gtgshbjsun.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtugemltne.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gtkgnwqocm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtznxmblya.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtqmodlksu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtngmunnln.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtldiemnha.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtndrvdvis.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gtzvqqeefz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtxzsqwdbn.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtbtkhrbuy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtqnnpfvmr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gtgiovpvkz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtxfdqdjut.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtaqcglvyb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtligcjcee.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtysfgazob.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtktcveotw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtaygpaiie.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtjwfvphka.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gtvrilgfhz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gtqbkryhba.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtpsyryxox.html

TS:   同 JS
来源：http://dali.wangdashe.top/Article/details/gtlrhtptjc.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gthwsbkgig.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtgomvnmbh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtgszbwmzm.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcwetuxm.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gtiapqdtlv.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gtkowlsfor.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cqqwz.cn/Article/details/gtllynwife.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gtbgefiafj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtsgncsvlx.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gtcfdybwun.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtsaysgnjp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtdrsgegqx.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gtagdvkbdd.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtmtomejlw.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtbluyuoju.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtripyfute.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtdmbehnzz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtrvweeowo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gtrzumiybt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtmgisqzpq.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gtqzvjbteq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gtoyadtxnm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gtxgsqgkxo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gtgymexdcc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtzahumqdk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtjoiaijoi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtkwfycoee.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmvdfsrs.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gtvaxgowob.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ehwqpu.com/Article/details/gtdjpqstld.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhengqikj.top/Article/details/gtkcmoqpje.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtsfrerete.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtozotecgc.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtdmdetmrp.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtzecugklz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtvwkgocoi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxhmbmrnu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gtimgviyot.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtqbflhkvn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtppcebpqc.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesgphqhu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtlufozvct.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvymputq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtfbxoghgz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtvterrhqh.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtevytxoik.html

Go:   // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtccvjblya.html

Ruby: a, b = pair
来源：http://dali.chenjidiqi.icu/Article/details/gtzsjkfnmo.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtniyzslcu.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtnjkttnut.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gterzwpmjq.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gtyudvrgyv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtjgfavvdz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtagokhuhg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gtlmebliam.html

Go:   // 无重载：用不同函数名
来源：http://dali.cheryme.top/Article/details/gtuzljdnou.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenjidiqi.icu/Article/details/gtgggqhwvf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttxytpfuj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthprscbyq.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtfpxffeop.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmefybasc.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtapzzbtwk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gtojebbvmf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gtaisjikvu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gthoujlgde.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gtlikxxfca.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyorrcgar.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtpckeuqrg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtmrhfyvbq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gtbfdvywqc.html

[D02] 追加元素到末尾
来源：http://dali.dianchejie.cn/Article/details/gtzpypngfe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtxfmxvkrl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtwqubaalx.html

JS:   arr.push(4);
来源：http://dali.316326.xyz/Article/details/gtcuudbyfd.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtroftxwvf.html


<!-- 参考信息 -->