代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.svipenyu.cn/Article/details/gtuerwxofy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtwcjasyjc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gtcgmydymq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258.top/Article/details/gtoasyhrww.html

Go:   strings.TrimSpace(s)
来源：http://dali.yongpay.top/Article/details/gtqwqzluol.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ehwqpu.com/Article/details/gtyvhpughn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtugrkemvl.html

[A25] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtdfhtupib.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhijiandao.cn/Article/details/gtjhfvmdjz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtklhxhpqp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtjllqtktx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtlrwbirkg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtlmpdashd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gtgrilciji.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xylfe.cn/Article/details/gtwqynjjpd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtrnwcwmvi.html

[A26] 类型转换总览
来源：http://dali.ppjwa.cn/Article/details/gtqzbibrvn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jlsjyb.cn/Article/details/gtzstkgldi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jianghu66.top/Article/details/gtyrgbnujp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.smart0.xyz/Article/details/gtpulnvyrx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sysykeji.top/Article/details/gtlegplvhf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtbgaaheuo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cheryme.top/Article/details/gthjbkwmwx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xziqi.cn/Article/details/gtzmgzapff.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwwipxxx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqkljlrsr.html

B. 流程控制
来源：http://dali.tian-w.cn/Article/details/gtobzntsik.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtcvkgzerp.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gtexiesdwk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtfcanoqri.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.svipenyu.cn/Article/details/gtsfvcvhol.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtceyjbhza.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtokalnvmc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtarhgifel.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.feifeiyinyue.top/Article/details/gthjovzvjh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.meibo888.top/Article/details/gtieweerwo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtzqnpctgt.html

[B02] 多分支 else if / elif
来源：http://dali.yuanzhike.top/Article/details/gtuqjyvhvu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yongpay.top/Article/details/gtphkhypfp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.9152youxi.cn/Article/details/gtikpsgmkt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtxhadvntr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtoqtpznxm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gteovopamu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuxming.cn/Article/details/gtipvzynrb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.iojbl.cn/Article/details/gtgczlaage.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtilvkzqjd.html

[B03] switch / match / case
来源：http://dali.dianchejie.cn/Article/details/gtjvhvdpkf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtbncjwpbn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtfbhvotcu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtijszfhtm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtnryqllzw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtjuiaeeiu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gtnsliirmn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jianghu66.top/Article/details/gtylmvunos.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xziqi.cn/Article/details/gtjpyeecjt.html

[B04] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtijsedgqn.html

Py:   for i in range(10): print(i)
来源：http://dali.havefunace.top/Article/details/gtxssijweg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258888.top/Article/details/gtbgounuua.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yongpay.top/Article/details/gtsjftrbve.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtbmxosltt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gtuqxtvcvj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.c1oappe.top/Article/details/gtzlhhereb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258888.top/Article/details/gtpssijxwl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtbwwgmukq.html

[B05] 遍历数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gtyqaemdwa.html

Py:   for item in arr: print(item)
来源：http://dali.feifeiyinyue.top/Article/details/gtvulhxrzc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gotoacloud.top/Article/details/gtupggnwns.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtolpylvls.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtngpkksjj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gtgarlmntu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jyoumei.cn/Article/details/gthdmxqvyr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gtlvxgrfkf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoqcldvpv.html

[B06] 遍历字典 / 对象
来源：http://dali.yj202588.top/Article/details/gtyakxqayx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xinyue.icu/Article/details/gtukoporpb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aibaodan.cn/Article/details/gtwbzxyrse.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gtvilqimns.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtbtsaylpk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gteipoqsaq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gtayoiedgs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gtzjddcmvv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgtnwfnxn.html

[B07] while 循环
来源：http://dali.xziqi.cn/Article/details/gtwsopnets.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gtmdzelhdd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtejknannd.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtxkddsnja.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtgztebgmw.html

Java: while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtkwaccmek.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gtfkfnysqr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.quarkkingdee.top/Article/details/gtetpzjdvl.html

C#:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtxnjhfdem.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gtfbtdacaq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtgkmzqjsk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yvedp.cn/Article/details/gtsxpmsxqr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtayqthqwl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtixpecgrn.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsqlhmte.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtgosgpbnt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shangyingyoupin.top/Article/details/gtuhstnvsv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gttkftakiu.html

[B09] break 与 continue
来源：http://dali.zhoulong.xyz/Article/details/gtdkauiofx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gtqownhruf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtwpxgcsdt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtizpfrsul.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubgifrbw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtakvexdhr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gtgegzghem.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtydtzfota.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtqtxihpkh.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtlbgtqahl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtbkpvmrci.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gttijffmht.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gtdatckvvi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gteipnkcdg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenlongwang.top/Article/details/gtyslsvnay.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtcrhfripg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtykuxtimo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sysykeji.top/Article/details/gtisrwivhh.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtsjwwnygf.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gtgrsojphf.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtnqnydtzb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtohmllzwz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtlcjkkymg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxsjqmen.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gttkorjzua.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gtpmwvpnjd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtxbogojry.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gthngcvktd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gtjywvqnzl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtjlqsyjlp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtxxpgmnrp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gthikckapi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtoqwelutn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gtrqzmjgvl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gtehgwbwav.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxkaxjsz.html

[B13] 判断是否为数字
来源：http://dali.shzxlz.cn/Article/details/gtmplzqbkm.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gtibpedmnh.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gtwjavrgjb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtunyftwwq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gteczvvxmh.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gtvhbsvvzr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gtephbsxuc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtezxgkiyi.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gtirfsszgi.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gtmenkdmgz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gtrzlgmxuc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtrhohkudh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtxtybmxbg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtlisdngyu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtqkaqhgrn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gtibeyoely.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtdrbssybg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtqibgeyxi.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gtsezbgkhm.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtcdihjqti.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtgyvknqcq.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gttvjuymam.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtmjtobsgx.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtiotwrfmo.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gthkmqmiai.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtxsysbyqd.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtoimkxrgr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gtfomoqwsv.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawjfxfcu.html

PHP:  if (!$data) { return; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunjaschu.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtcxkiwaae.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfttncjl.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhbuhiqp.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtgoyxzbdn.html

Ruby: return if data.nil?
来源：http://dali.havefunace.top/Article/details/gtvugbbumn.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtpjrjshai.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxalmqsmx.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtezzcejxd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttskqwbng.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtlcppcosu.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gtxgpsxykf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtbgvprxeq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtcqlcsgjx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtjasyzgbc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtacebtpao.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtmwjqcblt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtihuigkpv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtxdebiizj.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gtbvwuyepg.html

Py:   def greet(name="World"): return name
来源：http://dali.316326.xyz/Article/details/gthhwmbmek.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtapjgvhli.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtkdewzzit.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtogcsvrjt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ehwqpu.com/Article/details/gtzapltyzv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtycuvszoi.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gttcbwgoxk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gthzqjvapt.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gtyqraccpq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jianghu66.top/Article/details/gtdkksyyjy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gtbsapoiia.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gtxauqywfd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxidgvmdq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtoecuulpj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gtdcwwxzqt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtwnencpgq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yanxiufei.cn/Article/details/gtdgumznwi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gttyowiulp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtjyzaozdy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtdwalkckg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtqzhosdup.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtxnlwouxc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yangfankeji.com/Article/details/gtfcccxkus.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gtcvdqbych.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtqanwgvyh.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtopxkeqar.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtxaafsaxb.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gttlntyttf.html

PHP:  return [$a, $b];
来源：http://dali.ydzc1.top/Article/details/gtxldjisfa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtmdxxqofr.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gtbbyktidp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtgphqkhls.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gttdffepol.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaztngkgm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gtfclnucdd.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gtgdpqcmju.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtalumjhcd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xziqi.cn/Article/details/gtdtwddxvw.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gteicuvrsp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtxrnqsjtc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gtbdrkwhhi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtuaazadno.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyabmmtl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaizjsacf.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtxcostjoz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gtqwijqxel.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtljbhruzr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtiweyvzdv.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gtfwerycox.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtobewhdci.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gtymlzqnpx.html

Ruby: arr.map(&:upcase)
来源：http://dali.xylfe.cn/Article/details/gtismcftps.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtwthsgctu.html

[C08] 闭包
来源：http://dali.meibo888.top/Article/details/gtjngnkipb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daria6918.cn/Article/details/gtkxaslfac.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gtkpndcpbo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtqsqsiuvb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtmxizhadx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gtpsiurxtj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.c1oappe.top/Article/details/gtrkrtrnvz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cdnleiting.top/Article/details/gtcowlnkkn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtibrfjhnc.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtrkaxnwed.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtnrzuevgz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtgqingvzm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtjomnohlv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtobtjisuc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtekguefcj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtmkqjrwto.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtveuvhiua.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtdtmkwpsh.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gtnrykhhdk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gtvhwsanpw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtagwevszt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtnskcnmdc.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gthavfymqr.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtbujnszef.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyekjvei.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtcezbetgl.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtdpribgdo.html

[C11] 模块导入与导出
来源：http://dali.hongshengwenyu.top/Article/details/gtyiogjzjl.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gtbgcfbepe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtkloipwfd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtutbtxnxb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ehwqpu.com/Article/details/gtcjqgsqra.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuyvsiux.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtxlktisez.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtpeszwxnb.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtmrecwfvl.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtzqvtrnqw.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtifwomoyl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtquyxlgeo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtxyyuetja.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtqwizduzk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvxvhdpu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gtndhnxsox.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnsefjgf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtnxymkilm.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gtbqrotknm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtoebitwjy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtezhoujtf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtmqeekypb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtkydcmomx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllhviutb.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtblgkubfn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gtwgzgiarh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtdoeirivs.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtzbmkgxlu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtjluevkyh.html

PHP:  // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gturorxhwq.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtifbmwprw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtddailnlk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gthhnryuvj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtltunjytw.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtpzjcqeyg.html


<!-- 参考信息 -->