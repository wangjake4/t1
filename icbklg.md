代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtiiovktla.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgfzy.top/Article/details/gtiridjote.html

[A24] 去除首尾空白
来源：http://dali.zhoulong.xyz/Article/details/gtttorsplf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gtbzhqvvou.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guowangkeji.top/Article/details/gtbsauuxci.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtyjtdlbqg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtlkhssqcc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.svipenyu.cn/Article/details/gtbiqytkis.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangdashe.top/Article/details/gtzsuuksyb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.feifeiyinyue.top/Article/details/gtcdvaiblg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtmppdfnrh.html

[A25] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtttxncmce.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gtdnngcznh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gtkoktgslt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.bjfxy.top/Article/details/gtqjifhild.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtyuyvafiy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtfqokqglv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtjtlhnxwz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cheryme.top/Article/details/gthddbkeoo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpajupygz.html

[A26] 类型转换总览
来源：http://dali.chenzaomai.com/Article/details/gthodoenru.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gtufcywypp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fzhhl.top/Article/details/gtrbcvpnuj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtoxqgpgyh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.smart0.xyz/Article/details/gtivtrozmn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtwupxcnvr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhoulong.xyz/Article/details/gtqdlyergi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinqigfzy.top/Article/details/gtokpdeywu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sweek.top/Article/details/gtcjampgct.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthtidrkph.html

B. 流程控制
来源：http://dali.sysykeji.top/Article/details/gtvfgfohim.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtamkxvsgs.html

[B01] 条件判断 if / else
来源：http://dali.iojbl.cn/Article/details/gtjgcalxhh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtdhjkprqx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gtxfbxtzuc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtsyouyfbv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtadgqdgas.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxrpkaqp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cashguo.top/Article/details/gtzdqgjgiq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xziqi.cn/Article/details/gtnkvjcbrb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtazmvzbdi.html

[B02] 多分支 else if / elif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvsrnhjl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxinkj.top/Article/details/gtygmitbqc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gtkkmiaryl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtrkmzgdfw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtlqggkrgw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoitcykfk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gotoacloud.top/Article/details/gtqpejmecp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvruyfco.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtfcnszbsp.html

[B03] switch / match / case
来源：http://dali.birdmap.top/Article/details/gtftfilseh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhongyouzk.top/Article/details/gtlebqnuqt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtrduihnkw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtdsgwwfws.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtdyymmprz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtqxzuosiu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gtflmwobfz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gaohongyu789.top/Article/details/gtrzrftcpw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yonumen.top/Article/details/gtwhkmtajm.html

[B04] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtfzhmqprd.html

Py:   for i in range(10): print(i)
来源：http://dali.smart0.xyz/Article/details/gtjkauzobn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmmmfulpq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtkfxfyzrv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gttdjkvqbm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtkmdpveya.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zycfv.cn/Article/details/gtbkmmxzyf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hywenlv.cn/Article/details/gtkqpepkzl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtyejasijs.html

[B05] 遍历数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gttcghelhs.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gtuylefesp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ppjwa.cn/Article/details/gtenrjdgho.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtjjwpbpml.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtwalnlgqh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gtbuoirmbz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gogol.net.cn/Article/details/gtryzbhdge.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtnyctaumo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gotoacloud.top/Article/details/gtzbqlejgr.html

[B06] 遍历字典 / 对象
来源：http://dali.tian-w.cn/Article/details/gtckfmnwpu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhxdoxoq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sufxvd.cn/Article/details/gtyuammsju.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtknkcigse.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtbagaxdom.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cheryme.top/Article/details/gtshgrttcj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteilauzdf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yongpay.top/Article/details/gtkkjowflu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gtgrgzzakr.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gtnpxebvgh.html

Py:   while i < 10: i += 1
来源：http://dali.fengsongda.top/Article/details/gtawudweph.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtmxxpasdw.html

JS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtcbhriydm.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtebirusxq.html

Java: while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtoshoscdd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtudpiyair.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gzhubu.top/Article/details/gtrjbjglbe.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtkljkvsrx.html

[B08] do-while（至少执行一次）
来源：http://dali.cqqwz.cn/Article/details/gtqfocdkps.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fengsongda.top/Article/details/gtmeqoknaj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gtlwsysmgi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtvkzkqnne.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtlindplau.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtsdwrrszd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gtnafecbrw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhbhpqeh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gteaqpeego.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtgjwvaybr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gtmsgcrrxc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtexidwgka.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtfaxsnmcv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtynhnsyiu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtcpccowkh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtpysnzgfs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.vqdsnc.cn/Article/details/gtfomqkiak.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtmkzaerym.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gtcxkjyqoi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtxjdwgymm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gtrslbmedp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtwgnkwdqy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtganregwx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtigtirwoz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gtoehqkfxr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtjeotemlh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gtbevabaht.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gtjubjljai.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtmzooubqw.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258.top/Article/details/gtuutfcyty.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtovonoqpa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtegjpsoxi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtbbmefxlw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gaohongyu789.top/Article/details/gtcagysoag.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gtvoprntrg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtadtshknx.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiarpuoho.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gtmatvsbjk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtmqslkqfg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtfpkvintp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtjxufkwvz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gthnfebtwn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gtwwpmcthr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gtsfgnmflp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gtpnkcgkrc.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gtbopbwjza.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gtxsexfope.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gtmqjsqvcs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtiprpdlbi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtooodffit.html

Java: x instanceof Number
来源：http://dali.shuidangran.top/Article/details/gtisnismfq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gtufeteggr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gthofyynap.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gtmwtycmln.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtnfnozvla.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gtxgfvdxfi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtnfwcezon.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwqqjdqu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gttgnvlmjp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gthrohixbd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmkipwnlz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtbjwjpicn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtougpelfe.html

[B15] 布尔运算与取反
来源：http://dali.guowangkeji.top/Article/details/gtpvjsbgho.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtihfwczvo.html

PHP:  $a && $b || !$c
来源：http://dali.316326.xyz/Article/details/gtvyeavedz.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtlykthfgl.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtapvgbyub.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtvevepjbv.html

Go:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtvkznbbqn.html

Ruby: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtpzfpyhiy.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtjdensvfg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtprjwshof.html

Py:   if not data: return
来源：http://dali.gaohongyu789.top/Article/details/gtywhpxadb.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gtbxibpefd.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtliuvgqqk.html

TS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gtordpeybf.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtvybzbvas.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtpovwcapr.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gtxwhflueb.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtbhujmpon.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlizoonyb.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtoteqromr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcsklsgpm.html

[C01] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtyexsfbdb.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gttskgnpwv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtdbcpfokx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtlkslcivm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtjajdhrlw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtyzghtmwx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcsdosgb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gtrnomepjf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtimkgfwps.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtfvrbojgz.html

Py:   def greet(name="World"): return name
来源：http://dali.sweek.top/Article/details/gtnpkteasn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtusqifobw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtfxwxlhpj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtxluhdzko.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gtblxtgpkh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gtajfpderb.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gtksmpahwm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtydlzzozo.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gtenguazkz.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtrwixmhtx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxuanxn.top/Article/details/gtiutatghk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtxcxeyuoj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtpepydbfg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gtpoykgpvn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtvbndfvdx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtlzbfmpob.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtmjyqenrs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtwofwocbs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfknjkcnz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtckndprrq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtjzccrbgz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hammf.cn/Article/details/gthmwmaamp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gtfoccskqs.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtwhqrtqbh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtkcxuopxk.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtpcevnzzt.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gtlwrzhmdl.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtwoodxyvb.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtoyzyselj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtsofzaqpj.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtqmztcdlp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gtgfwdqphk.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtdfivxycu.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtivdvfmfc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtgcqnyhkc.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gtxytlpztr.html

Py:   square = lambda x: x * x
来源：http://dali.wangdashe.top/Article/details/gtparagrix.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gtleikyjtd.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtvlfjemqk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtfwkuzaol.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtkxfucdie.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gttytneyrt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gthuyviwah.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtcawfdyqy.html

[C07] 把函数作为参数传入
来源：http://dali.zhongyouzk.top/Article/details/gtgmxjhgkb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gogol.net.cn/Article/details/gtnbhtfzni.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtvdufesns.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtdhlmhksn.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gtrfxgufpt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtgqonpeas.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtfrufiokm.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtmuwnryqw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gtjuerfvzg.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gtpynsfhbl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtmzguexwu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtonjprkmu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtknlijshp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtizgfizbl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtusgntsze.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtnqirekyg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gtddgvforl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtgoorqvca.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtnukdgqja.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtgzemqcex.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtiswdyrpg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtzbcjjaet.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtlrumyppb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtxubkwqdq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gtrpcgdatd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtjatrjtil.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigfzy.top/Article/details/gtxmpabqen.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnqyrbsv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gtryuwpcbs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gtywpgqppe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtxlgztlrh.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtcaezfzhk.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gtvlebgagx.html

Go:   花括号块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtyoyocasa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xziqi.cn/Article/details/gtzqefrnov.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggxtyhpu.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtvxogbblg.html

Py:   from module import func
来源：http://dali.yj20258.top/Article/details/gtznolebwh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtunwcjmue.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtjlfbcscj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtxypnnqfb.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtxqaxetbo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtpykrufzo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gtldxtpibl.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtjjeeehux.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkxhphon.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtpjkqzbym.html

PHP:  (function () { echo "run"; })();
来源：http://dali.quarkkingdee.top/Article/details/gthxngpzht.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtgvtztfqv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtcvqjrsmv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.birdmap.top/Article/details/gtunbjvpom.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gtfhjgzzbr.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gtzmmegefd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtnjuvkwsd.html

[C13] 类型声明 / 类型注解
来源：http://dali.yongpay.top/Article/details/gtbuhhrlhu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtmkzzosvx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtkljlsbfh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnxiangtu.top/Article/details/gtzaugmbot.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gthgexiqem.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtyveuuthl.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtvrlvgwzo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gtkzztubwn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gtukfpvqbg.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtzkieesvr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gtfxdkasqo.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtwfpwodeb.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtokrsppsi.html


<!-- 参考信息 -->