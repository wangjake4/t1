代发 wailian999

[B01] 条件判断 if / else
来源：http://dali.dianchejie.cn/Article/details/gtgrjtywke.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tian-w.cn/Article/details/gtafhoyzoi.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jianghu66.top/Article/details/gttnxmrwrk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtzcyaolvm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtwqtpqlzk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtpeiofaqv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnxiangtu.top/Article/details/gtgkamwflt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fengsongda.top/Article/details/gtqbllvodx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkyiwbfl.html

[B02] 多分支 else if / elif
来源：http://dali.jlsjyb.cn/Article/details/gtvueolnwd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gtsfbpofzy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hywenlv.cn/Article/details/gtgyifclcn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtaplghwen.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtlqlpezao.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtyoipdsah.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxuanxn.top/Article/details/gtqmzzvbxp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gtfefpcflw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gttzescjwa.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtukmtdmkp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkqpwpob.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtmoqqufrt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtsqvvpisz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbfnqixox.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtfppfjnuk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtclcojlnu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gtfbtgsdaj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jianghu66.top/Article/details/gtckqvkwfj.html

[B04] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtvewaevpv.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gtgyhlzjcs.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtzntfnooj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtdwfkkckx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzwrocgpe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtyfufjphr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtmzrvqeia.html

Ruby: 10.times { |i| puts i }
来源：http://dali.feifeiyinyue.top/Article/details/gthvelmxze.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cashguo.top/Article/details/gttutzojox.html

[B05] 遍历数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gttqvykrnv.html

Py:   for item in arr: print(item)
来源：http://dali.nwbrower.top/Article/details/gtmhrdqwzl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sufxvd.cn/Article/details/gtabgsfrqm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gtdhnmzzrz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtbukenjzl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtmmjzcgaz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtavykncal.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gttthucakq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.redwolf501.top/Article/details/gtoytnyowf.html

[B06] 遍历字典 / 对象
来源：http://dali.yuanzhike.top/Article/details/gtixyvidcy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hongshengwenyu.top/Article/details/gtnegxzokt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gtmnnblnbj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtnxbpudan.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtlzszragn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtyqsbegrw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.quarkkingdee.top/Article/details/gtqeyufrfu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gtvyercwfn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jianghu66.top/Article/details/gtysjyrgti.html

[B07] while 循环
来源：http://dali.pengpengdd.cyou/Article/details/gteplxbqud.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gthpfqkpha.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtipdafooz.html

JS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtopdatkrf.html

TS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtwjdfjxyv.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtwcceiamv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gtpwgsrsgr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zdqjudy.top/Article/details/gtdeaqbheq.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoularyo.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtiuerougv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gtjmuxcyuh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtbjzhnado.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gttpcegppz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtlchymeyn.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtlbakeswy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtnvvbefzr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gtyhysqsnx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyvzlxox.html

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gtcwdfevrf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gtirjlvttm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtekhjghtw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtoqvlzibi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtqofehszo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtpuievebt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gteyijkrde.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gtdubnoxmu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtkqojylnt.html

[B10] 遍历同时拿索引
来源：http://dali.daria6918.cn/Article/details/gtremmtnjo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gtiultzank.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gtissawmzs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gttyyvylzo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gtyaaqsays.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cqqwz.cn/Article/details/gtwdgubgfc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nwbrower.top/Article/details/gtqjhfdyqh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtjytqaojs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrelqgnx.html

[B11] 生成数字序列 / 区间
来源：http://dali.havefunace.top/Article/details/gtazankpfu.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgufenzy.top/Article/details/gtlfbntbel.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvygdbyg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtegluihaw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gthqsyvhdb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gtqukqxowy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtzkdfnzmp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrshutpb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ybcxt.top/Article/details/gtzuxgvfjm.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtfanmpjfn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gthinusskm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sweek.top/Article/details/gtwgdonuax.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtanpjhfcw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtlntgcabi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtxqfuktyh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gtcacbictf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtwqprglmo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gtejgrmjfi.html

[B13] 判断是否为数字
来源：http://dali.yangfankeji.com/Article/details/gtntwlshui.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtjlajmdxr.html

PHP:  is_numeric($x)
来源：http://dali.zdqjudy.top/Article/details/gtmzqcgsqw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtfbpnawet.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtsccqzayr.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gtejywponm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gtmaifarsb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shzxlz.cn/Article/details/gtrxkpulzs.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtpefrjrwe.html

[B14] 判断值是否在集合内
来源：http://dali.pengpengdd.cyou/Article/details/gtqklrjnxy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuetiantiany.cn/Article/details/gtehbqindz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gtcdnmophv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtgbxxfrte.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnqisizg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtioqatbek.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gtfthorqux.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yonumen.top/Article/details/gtcapagmyh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtecozrevy.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtrxptazos.html

Py:   a and b or not c
来源：http://dali.jlsjyb.cn/Article/details/gtoivjbctv.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gtbithhlnf.html

JS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtpjtbbelp.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtwscoyvnq.html

Java: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gttukcdyap.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtqpjivpvp.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtndoaaqcs.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtaatctrdp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gtfvdpkjcd.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtrgreddau.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtubqvjlbs.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtmgibxeqt.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtoawmlfpm.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtglqieymi.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gtecgebjio.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmrkpvjg.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gthxjtvcmj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkhfmunqv.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gtlekripvl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthddahuxd.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnyyuhxw.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmycugeh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtygzvqdcm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttfjtrapv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcfisoyyw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtaywujyrd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtaerjdcww.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gtsyuquody.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtgzeqwbol.html

[C02] 默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtqodrpaif.html

Py:   def greet(name="World"): return name
来源：http://dali.316326.xyz/Article/details/gtxnfoyuke.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gtlxlnxuel.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtwxmcotbk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtastgndrv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtswixbffl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ppjwa.cn/Article/details/gtsktnyjmo.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gtcpxpldjm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshvusoyb.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtbcdnodsn.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gtbvreelwk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gtoljeyinn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtoqmvjzwt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtditejudy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gtklieusxk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtcbomllzz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofvskuaz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtwthsawjw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtcykkadoc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gtptbgxirv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtahrfarmm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtaehffhct.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtwsbbszcs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jiagoushi.top/Article/details/gtwnegifmc.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttljlodxq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtnwdezivg.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtasuynrac.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gtntabwurr.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtvkfxjyqr.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtyhonjcim.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtaqmvueif.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtdocphmev.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtylemcjoc.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtcbvnaqjr.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gtqyitiuxx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gtmwqxwlmp.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtmmswrdjo.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhbafxwy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gtwhfnkahc.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtuvimhnjh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtcsjcfpzt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtlcccunui.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gthjlarhzj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtkoehdwqp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcclfqpuf.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gtiqayrhja.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gtafhfkopm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtowrfbgmm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecgnvoob.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtujihvfsa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gotoacloud.top/Article/details/gtpkbdukjk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gtjhbwyjxn.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangshuangyany.cn/Article/details/gtfusnkama.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gtqcubqtgq.html

[C08] 闭包
来源：http://dali.smart0.xyz/Article/details/gtevhkfhch.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtturelcka.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtnxtfaktp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtmfmqyvmp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtdntbwici.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gtpxqgsqnt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtbwwsvlog.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gtsefamcmg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtrskmilgj.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtjmzreoiy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtpvhxtreb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkulajett.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gthdyiuvxm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtemeiknax.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtjbiisdqu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtiabatriv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtbgkavgpw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtylsdptun.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtnaieksbq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fzhhl.top/Article/details/gtaouycmiv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.havefunace.top/Article/details/gtqfwbilyq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gtsimsbezn.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gtualqjpvl.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtkicujmgy.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtdlhyqhjy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gtzvjjnlve.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtscacjphr.html

[C11] 模块导入与导出
来源：http://dali.gzhubu.top/Article/details/gtbvvierza.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtjmvdzcmg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtpbatzasg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtsietfriw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gttzxrbeek.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtulwgsbqe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gtwzvzbuka.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtxeorhexw.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzoezqxx.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gtxgeeqqbp.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjjspfpd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gtsoivniav.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtdkyvhlqk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtpjuuopom.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gttdiquedh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtodviqzux.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gtfjhygbus.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtbkdworyf.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtjfkdkbsw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtfxfdwmro.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtjzheoifz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gthixhrsgt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtswocgdhe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtjalvvqlh.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gtjjceybck.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtiwxiyrib.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gtaggopali.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gtnlsismyl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gtiadavpid.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gthtqurmux.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtofhghttc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtgunnrbyy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtiqwiwvrx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtrrouykbt.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gtelxzkgaj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtokgvotsm.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtnsephlwe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtxfrqrrna.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtpqtlqoad.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwzbkwcs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtncftgwya.html

Java: // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtpncelqhx.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gtxjwhasgc.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gtaupjhxha.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtvjhquruc.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gtjnpbhgjo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gtnenzxcxp.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtnpttnevl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gtqvohfetm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatdpwvqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtedfkcpix.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlorwompm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtzaqscypl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtcoytsxfh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtasrzjuzg.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtpqgtkaly.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlvjjytqn.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtaovjskcd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gtusrhttgw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gtuezidvkn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gteogojfhi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gteppcjefs.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtthgzyxgo.html


<!-- 参考信息 -->