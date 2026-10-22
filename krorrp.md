代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakauwjuv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gtqxstivmq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.smart0.xyz/Article/details/gtmrcwvrdt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtkploorff.html

[A26] 类型转换总览
来源：http://dali.tian-w.cn/Article/details/gtqdcxlyja.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gtflefvhng.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuanzhike.top/Article/details/gthmqpzlzr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtzyxqizcr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gotoacloud.top/Article/details/gtpegbhqkw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrawzlzny.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gtwzttdcou.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomzaahpv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtunygmatj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtflymksaj.html

B. 流程控制
来源：http://dali.gogol.net.cn/Article/details/gtdoolwcqc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtluaiyfys.html

[B01] 条件判断 if / else
来源：http://dali.sufxvd.cn/Article/details/gtubeeiayd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gtkxezjpks.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtxtivpvwh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtnmxqlmme.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtfjyhzqdn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtmpjqgfnw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhiwuduotai.top/Article/details/gteqhfqbmf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnqzz.top/Article/details/gtocwfxdzk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtaxtfyofr.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gtzbyjursr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.feifeiyinyue.top/Article/details/gtmjbdbhct.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtytoiuliw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtiwgqplfk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtuxjetoeh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtivdgyxxr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sweek.top/Article/details/gtqbvbvgyd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.haohaochexian.top/Article/details/gtochsehqy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtnkuqcffq.html

[B03] switch / match / case
来源：http://dali.jlsjyb.cn/Article/details/gtmnhvitpo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gtzsasffkb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtczdjicxr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gthauomckr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gthekvocti.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtkimscmzl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gtfdjsqgmw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.snrcjt.cn/Article/details/gtqbnkezzy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gtekvvhgcp.html

[B04] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtzrqetyuj.html

Py:   for i in range(10): print(i)
来源：http://dali.dashuyun.cn/Article/details/gtyyvtuoxa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gtupccylcm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hammf.cn/Article/details/gtzvymsckc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtprgmcjmc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtmcvqseid.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gtqhnnvflz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shuidangran.top/Article/details/gtwnzrufui.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgfzy.top/Article/details/gtvdqacgjw.html

[B05] 遍历数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtehhfxwnf.html

Py:   for item in arr: print(item)
来源：http://dali.pengpengdd.cyou/Article/details/gttnyzfudg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gtuiuboilj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtttarmaid.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtsrxeislb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenlongwang.top/Article/details/gtbilnxsft.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gtbsvrhkij.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gotoacloud.top/Article/details/gtfjlchrzd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksckrnpp.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gtrvrpxzvm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aibaodan.cn/Article/details/gttvqyffmv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258888.top/Article/details/gtnbauhffz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtldcdxppg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtfkqiuruq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglqtwvcl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gtgtpilkea.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guowangkeji.top/Article/details/gtnhodxhpp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.0kj1m.cn/Article/details/gtaqtdecvc.html

[B07] while 循环
来源：http://dali.yuxming.cn/Article/details/gtewarboxx.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gtfuzumfgq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhengqikj.top/Article/details/gtqfplowtc.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtirbzntic.html

TS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtsfbuhjts.html

Java: while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gthjojscfi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aibaodan.cn/Article/details/gtzsjemqie.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtrjwslwfq.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmupdypk.html

[B08] do-while（至少执行一次）
来源：http://dali.zhongyouzk.top/Article/details/gtxbvjyiqm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.smart0.xyz/Article/details/gtgmsqivbz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gtaphddjsv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtsbcbsnbl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtdfadovzz.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtovfcxqkf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtgszxjcit.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ivvv.top/Article/details/gtsxcsoqjj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtomgzzyvq.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gtitycxrhm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangshuangyany.cn/Article/details/gtnnjqhrgh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtqfsxyidb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtxvmasfek.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtuwzlbwng.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtixctqngs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.c1oappe.top/Article/details/gtsafwxzpf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gtusifnhsf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtksfuesnp.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gttgitgvps.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gtrbfcjzdb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hammf.cn/Article/details/gtycbkwjvp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtepgypgfk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gthrcsdmtv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtqhgyxetd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtijrycpoy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gtjyuamoti.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hywenlv.cn/Article/details/gtztnfhbsb.html

[B11] 生成数字序列 / 区间
来源：http://dali.c1oappe.top/Article/details/gtaqfqbryz.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtoshyqepf.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gthkijiilm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulgdjdxb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtamtcgjvr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gtpynmuptz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtzuijvlmg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtxkdcozmb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gtqqnccgbj.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gtghjpyeuh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gtcawbcapu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxinkj.top/Article/details/gtdsnrjzyr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtmjqobsuj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtyawsuykn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtppwjhuop.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtmzekekfu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtnmwdaslg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gtqtewupfh.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gtvfemwjdb.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gtkwjiomwx.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gthtluafvw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtvxhuwwrh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gtdruawsnu.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gtoeiltxex.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gttyyfuitj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtkmxuuxpb.html

C#:   x is int or double or decimal
来源：http://dali.0kj1m.cn/Article/details/gtmbqrmiit.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbljnczf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtvaxcjogy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtcwjksmkj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtvrkmdeao.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtwyphkscs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtnzojoxha.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gthbhmmhtn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtbqfkfyjo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtzfodafnl.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtfvkecpyp.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gtqvukuaeb.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gtiezamyjc.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtmmeifxcy.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtevionvrl.html

Java: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtjmnhaggs.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtolfmmoce.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtywpkizhe.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtplzkkwcr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gtpvbjbycu.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gtzqwljyya.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gthrmdrhpw.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtomqhzqlw.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtsfkdevgq.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtpdmtkajk.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtngozbinn.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gtdpdmvjop.html

C#:   if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gtncblqros.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtganbxryj.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtdxuumvsc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvmscpwgu.html

[C01] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtabqlcgmx.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtndtvkpjq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtbzprhduh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gttlrxdngj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtcrxjrjsk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtnfmygyzb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtayfuwkak.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtgtxsjxxt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtuzlizcxj.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gtxwyybuse.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtqkpccgji.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtjksfllay.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtwqqwjlyo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmeqixlyq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebxpjfcc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtvdxndlgr.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gtavygiyuu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvyvphpw.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gthhvkjtai.html

Py:   def total(*args): return sum(args)
来源：http://dali.nwbrower.top/Article/details/gtswjdijyd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtluhgpjhs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtksoybvyr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtjqkhxgiz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtuwzedeqc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shzxlz.cn/Article/details/gtijydjaty.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtdkkoawhv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gtrqqogvax.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gtcxwvyfsb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gtgavgaafl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtoorrudbu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtvbabsvty.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtkprtatvs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtgllrzbwj.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gtpycoocxb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtnwypszim.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtwztfvhzx.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gtdtznjocu.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtsudhmclo.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpaqkdfh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtgahauqve.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtcoqoanpa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtraxlhsfx.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtcwrxydzz.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtcrpvblns.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtanbraahg.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtgzazzgww.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gthufpoibh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gtxvjscblh.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtviiqgmrz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyluhkfj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtbkfbqpzp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gtacxpovbn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gthgdbbpwo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtewzglqog.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gtkmuptnts.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtyiprpxoe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtohglxwoj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtwiqnwgua.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gtefdnqiwd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gtcpwqeave.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gtxyjggsch.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtgeyisxtd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtwrxmtium.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtgmjpkbuh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccpuegdi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gtbrmpjkpi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsrnqqkf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcldxcjmr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsoxoitf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenoqbocq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gtjkyhulqx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtseoedwod.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsvajutc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtslolagzu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtujbsshkw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtlinuxtkj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gteinctqzy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtyfwdsgyo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gtzpdcwxrt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtqfwseace.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gtlgiqqpyc.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gtagxgxocg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gtuvajkjzo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtrvzyfyps.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.mhx1999.top/Article/details/gtjzainnws.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtmttksmga.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gtpqeoiwue.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gththkpufw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cashguo.top/Article/details/gtifvgjatk.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtgvufkhph.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gtdgbvlbpt.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gtwrhcabjx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gtnqhhjqxx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtgbyapidb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gtpxbwuqaa.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gthztvjnoe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtzynwpcdt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.andypj.xyz/Article/details/gttwckagpe.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtnyhypuqq.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtuhzpmtki.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gtcrkigxcs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gtdmvbmlon.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtqrpsqtrx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtewtoebbs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheogdfcr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtcbijegmj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtyumwiajn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtgwnpjiuy.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtovnagdsn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tian-w.cn/Article/details/gtjvyymiwe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtfiuomkoj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gtfkbzblkn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtfnuvhaxp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtqsuysdaw.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtihngkhls.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtuwbunrne.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtbkzoithk.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtquhizbgz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtuowudamm.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtkutktngq.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtfhlcryct.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtleagfrfy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gtolsflsai.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtvbgqnwiw.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqwgmsok.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gtmjyigukw.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gtlkrqgufr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jlsjyb.cn/Article/details/gtbhyymmih.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtrrnrxvyc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtbczwkeov.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttncralbk.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtsvcnddtn.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gtrdvhailr.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gteszcbkhm.html

C#:   var (a, b) = pair;
来源：http://dali.jiagoushi.top/Article/details/gtlardkzjl.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtqhzjmasq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtldioegmj.html


<!-- 参考信息 -->