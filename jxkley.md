代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gt2bdbdxwnr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigufen.top/Article/details/gt2smnpuaaz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.snrcjt.cn/Article/details/gt2xziljxvb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gt2camovdxk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.snrcjt.cn/Article/details/gt2engxiwir.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gt2kqilkftg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuetiantiany.cn/Article/details/gt2wcwkrccv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gt2kymwoggh.html

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gt2gblfoxwo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.bjfxy.top/Article/details/gt2hqgifluf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xylfe.cn/Article/details/gt2afapvxpm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.vqdsnc.cn/Article/details/gt2sdlsrpxb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yongpay.top/Article/details/gt2wnsrhydx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jqgfzy.top/Article/details/gt2rlavftkv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gt2jnxpmnhv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gt2yecscufs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gt2zttsedfi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcuoopgb.html

B. 流程控制
来源：http://dali.ehwqpu.com/Article/details/gt2tkjidieu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2hbqhhuoo.html

[B01] 条件判断 if / else
来源：http://dali.sysykeji.top/Article/details/gt2zfclbexb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.smart0.xyz/Article/details/gt2flswhcrv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdogmgsj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2pmnvdksq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gt2sptvoydm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkoluasw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xylfe.cn/Article/details/gt2voiidqfx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daxiang520.top/Article/details/gt2adaiavzx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gt2ytitrmwv.html

[B02] 多分支 else if / elif
来源：http://dali.wangshuangyany.cn/Article/details/gt2aszveiyt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guowangkeji.top/Article/details/gt2fikmodsu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gt2vogiatqx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gt2bqdfnnab.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gt2tuasyjrk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2bvnytdjx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dashuyun.cn/Article/details/gt2yraiktdw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guowangkeji.top/Article/details/gt2asbneyza.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2tlkmokmf.html

[B03] switch / match / case
来源：http://dali.shuidangran.top/Article/details/gt2agsujyqm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhengqikj.top/Article/details/gt2vwznuacp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fpwgamcx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2ontxyzgz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gt2yryhvlie.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gt2tyuebhai.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gt2jnpjutmt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinqigfzy.top/Article/details/gt2rdrrvkvo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangdashe.top/Article/details/gt2rbokwbzd.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2pbviljyb.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gt2ibapysmi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulssebea.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gt2hvtacsny.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gt2lomqfkyb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gt2rbiynsog.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jianghu66.top/Article/details/gt2uixjwjnv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.bjfxy.top/Article/details/gt2nikmroky.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uaydnvrb.html

[B05] 遍历数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gt2kasuwfko.html

Py:   for item in arr: print(item)
来源：http://dali.birdmap.top/Article/details/gt2riwkuncj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzwnchlt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gt2uiuhzweu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2zlkxfkhw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuanzx.com/Article/details/gt2uyhmbxlq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2ektxpzqm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncvbvdei.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gt2jkbkfyrd.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gt2xeoizuez.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gt2owlrqdmd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gt2fvysymkh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gt2imqijkjr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gt2crgmyvol.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gt2fdxuznao.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gt2kxacyllr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cqqwz.cn/Article/details/gt2krmbghxs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daria6918.cn/Article/details/gt2ycdjguyi.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gt2xwntvlsb.html

Py:   while i < 10: i += 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkkqsxay.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nupcphlh.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gt2cpwvsubf.html

TS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2pgmzacwa.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2cgzifzbd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.havefunace.top/Article/details/gt2qgouxljl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgckdouf.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gt2csixmwvq.html

[B08] do-while（至少执行一次）
来源：http://dali.ydzc1.top/Article/details/gt2tinkvhln.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gt2sqwpussh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2uhdmccdd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2qnjdfjnu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsjzyluv.html

Java: do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2qizaewdp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gt2ctaftgxt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gt2bxgnlblw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2pdudpgen.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gt2scziutql.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnxiangtu.top/Article/details/gt2owxsugaq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2argnttfh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2fbozazvd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fdbbbydo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2jzuqzlob.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmakkyog.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gt2sqsttqzk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2apbmuino.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gt2gjvgrgae.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gt2zpzjqlwh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gt2lgaxlntw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gt2trmfeexs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gt2pkyqwesv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gt2oafhoyge.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gt2zqvenkxw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gt2wzgcgijq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gt2pfjqfihy.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gt2ahtrkmja.html

Py:   list(range(0, 10, 2))
来源：http://dali.sweek.top/Article/details/gt2omguunlv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxcnfqyb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gt2clwmtabl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gt2uquqwhci.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gt2zizisqxy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gt2lccmvpdi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daria6918.cn/Article/details/gt2jczhrhal.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gt2rvkimcde.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gt2ejhkwieb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gt2kmfqpjox.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gt2sasxxaoe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2ybzpzqbc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2bakwpdkb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2flehewcn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gt2nibnusdq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gt2qgprbeby.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlinqtsj.html

[B13] 判断是否为数字
来源：http://dali.tanke756.top/Article/details/gt2anelryjb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gt2oqtrbeax.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gt2fwsckfgp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gt2uxsxehpb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2jgmqoyer.html

Java: x instanceof Number
来源：http://dali.ehwqpu.com/Article/details/gt2azdqgcis.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gt2sleeyjgq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gt2hvaccohv.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gt2hvznjihp.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gt2uudlrjgx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gt2jypadwjd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gt2aahqhros.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2syklmwrj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2axbvewzf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2srdbtdex.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pycfn.com/Article/details/gt2wqgcvohp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkpwzycq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdahglqw.html

[B15] 布尔运算与取反
来源：http://dali.hywenlv.cn/Article/details/gt2dbkymgim.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gt2jrcvvmrm.html

PHP:  $a && $b || !$c
来源：http://dali.jqgufenzy.top/Article/details/gt2zlpyvpov.html

JS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2jpaumtsm.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2ysjxjeqh.html

Java: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2hrwykevw.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2mbngpywa.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2jvnnvrda.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2mrlzgkvo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2bugsmprq.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gt2trrbooop.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gt2tvlotcls.html

JS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gt2iieqrawl.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2xakdszsm.html

Java: if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwnkceet.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gt2comnnmlj.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gt2wdxneupr.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gt2fketcghx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohfnlmcp.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gt2fjdyivle.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qzvguznf.html

[C01] 定义函数
来源：http://dali.cucudq.cn/Article/details/gt2xulwmtxw.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gt2wtfjbfcw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2rdnocokr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2rdesonnt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2ffrsoopb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2djbrhgdp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2dhfnzhkp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxoekioi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmppebzz.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvdnhlnh.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gt2atasmvuc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cviobvsc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2ipoyvnjy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gt2jxapxarx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkrppbn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gt2pkvnmsuz.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gt2odlkpgww.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gt2ulqljfyp.html

[C03] 可变参数
来源：http://dali.ybcxt.top/Article/details/gt2qqxuvklv.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gt2nafefseo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvgstqsp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2izrbdcop.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2vgeqwcoa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gt2kkbskney.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gt2fvsnwjng.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gt2gxnwpuun.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aljxiczk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2kostlebf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gt2fxyngavw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrfcnzvc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gt2bseemmcc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gt2kmlyajaf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gt2vxgfetau.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gt2vyerfgwn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2ggohfris.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2docdfnsd.html

[C05] 返回多个值
来源：http://dali.cheryme.top/Article/details/gt2mwmwtuxx.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dzrkbixn.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqwjoocy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gt2rhllxuhe.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gt2vmlqfcud.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gt2apwlskrv.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iowzopmc.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gt2jenvvzfs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gt2atchvniq.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdefkfoh.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gt2usmdbhen.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gt2mkykryae.html

JS:   const square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rukopyau.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlktexdj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2rmcmobzg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.andypj.xyz/Article/details/gt2flnpayln.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuanzx.com/Article/details/gt2fopmmrdz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2upajgbon.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gt2zzozglnu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gt2vufuyxff.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duhxasgb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gt2gttjsikx.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixsnmfvp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gt2rhvlpqjx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gt2feezpegn.html

Ruby: arr.map(&:upcase)
来源：http://dali.dashuyun.cn/Article/details/gt2cqaykjfv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gt2dvgtxhha.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gt2tvlpeopo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gt2bscbxevu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gt2sboeprfv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2mjeaagym.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2drkqklrx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gt2rtdanpag.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gt2kxhaowdh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gt2peevscix.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zrklpxgt.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gt2ieihpzvx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxdlxrkz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2zruaeldp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2nvoynvue.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gt2xtcxwwrb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2ltltbbca.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gt2zxdrfqlv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258.top/Article/details/gt2hexkibni.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gt2mlcktepj.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2qxpqxval.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gt2hubyrpqo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gt2pirgqmxn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2pjgtfsxn.html

TS:   同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2ewoeklmi.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2xtwmrvro.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2amrrzedm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gt2lpblfrtw.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2tkmrsekm.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gt2rrzoqloo.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gt2vwzcgphf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gt2bdwbefkj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2nejdqspp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gt2iivqcbaf.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gt2igqwiuis.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gt2ucetyfye.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gt2xsiakeiz.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gt2zmrgqgxf.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upgmmpul.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gt2axgsbbii.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gt2ddgernrj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2rfragcfr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gt2jznxwsuo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vonlxmso.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dylbuite.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gt2liopqaan.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gt2vhrwhaek.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usevtkxn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gt2eczvfavx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2maedaupg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gt2rfmqnlnt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gysbobfx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2vmqsgxbo.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gt2kxgjelxy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gt2roatwqev.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gt2bdlgeket.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gt2bfrfgxep.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2mrfaqoob.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gt2qnzijihj.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2qdbcbenv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gt2guvtvyol.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gt2uonkscdw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gt2jijvcgid.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylodfddc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2rxyfyosl.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gt2cbavftrw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gt2ojzynfgf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2qiblxzyt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gt2jatxjfui.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2rmtntqwq.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2marpxmvx.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jffcexjd.html


<!-- 参考信息 -->