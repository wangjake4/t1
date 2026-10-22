代发 wailian999

[A22] 获取字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2rvfbhgwe.html

Py:   len(s)
来源：http://dali.meibo888.top/Article/details/gt2wargqeyj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yongpay.top/Article/details/gt2oezhbfhh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ehwqpu.com/Article/details/gt2ysfvhtvt.html

TS:   s.length
来源：http://dali.cucudq.cn/Article/details/gt2loshwxpw.html

Java: s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2ctqumund.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hfpthk.cn/Article/details/gt2nvrhiptf.html

Ruby: s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2swtctept.html

C#:   s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vspmxwcb.html

[A23] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2pqhfbquk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.9152youxi.cn/Article/details/gt2tkobvpmk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gzhubu.top/Article/details/gt2yssgfbsm.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gt2olhzaljd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gt2lqbjmvpc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gt2rjzeqyrf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gt2oztezhct.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.meibo888.top/Article/details/gt2ztmhaqcf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fzhhl.top/Article/details/gt2plogyqmh.html

[A24] 去除首尾空白
来源：http://dali.xuanzx.com/Article/details/gt2wqpjlldj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gt2hxzodegv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aibaodan.cn/Article/details/gt2esrpvgza.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gt2trsclqex.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wupgknlt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pycfn.com/Article/details/gt2spiekfcr.html

Go:   strings.TrimSpace(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2agsgmjvj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gt2flrmejhq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2nwvanfzx.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2nxebgpah.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opdxosko.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yueranfly.top/Article/details/gt2gtivlrgr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xziqi.cn/Article/details/gt2btgujkev.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gt2sodtxmbk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjojceov.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gt2riimukfu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gt2oanwnekc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gt2vkposthy.html

[A26] 类型转换总览
来源：http://dali.gotoacloud.top/Article/details/gt2byguwsbg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuxming.cn/Article/details/gt2rhvurbyi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guannengcc.top/Article/details/gt2voraqlfr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zycfv.cn/Article/details/gt2cemwykpw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gotoacloud.top/Article/details/gt2rizcgxwt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enyenfju.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gt2lhjnjjqm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258888.top/Article/details/gt2dibduwga.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gt2dtqlxnts.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2amokwvsm.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gt2pbwdsevv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ktjeqgnp.html

[B01] 条件判断 if / else
来源：http://dali.hnqzz.top/Article/details/gt2fmijvtbo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gt2svhxjxph.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hysaishi.cn/Article/details/gt2glgnegfh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvmpyfgs.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2yitwwqzl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gt2puicvtfp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gt2rvnncnbp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcuarwmd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gt2cutdrqzx.html

[B02] 多分支 else if / elif
来源：http://dali.jlsjyb.cn/Article/details/gt2bguwqkjx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xylfe.cn/Article/details/gt2izcvfctr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ybcxt.top/Article/details/gt2zvjxopiw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2ipuszbwr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gt2xsxwtbzs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gt2xfhsbrmm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pycfn.com/Article/details/gt2jzzxtdvi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhixingplan.top/Article/details/gt2tdejprhk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2rzernqjg.html

[B03] switch / match / case
来源：http://dali.sufxvd.cn/Article/details/gt2wshtocls.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sufxvd.cn/Article/details/gt2megrfoek.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tysuepif.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gt2awfvkgjo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gt2myeglqjr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kejnadoz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2ibqxckmo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gt2horxknjd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2ljauitaf.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2xmktmnel.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gt2yznxqhmm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqkhtvyy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gt2virsljkm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwvyhbpp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ivvv.top/Article/details/gt2oykeetps.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zdqjudy.top/Article/details/gt2plynmsio.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gt2taapjnjz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gt2mgqnymos.html

[B05] 遍历数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2ebnelyod.html

Py:   for item in arr: print(item)
来源：http://dali.pycfn.com/Article/details/gt2xrhqhdva.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gt2fafvefjj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gt2nfbnnkxr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2netpnpdw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gt2hbmhxzfr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gt2jxxufvos.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gt2fuueryih.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2ztqehpsi.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gt2tfwsztlp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daxiang520.top/Article/details/gt2ohtrtanu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gt2uzjqbpbm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gt2mjlzbyrb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2cserbhgv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hfpthk.cn/Article/details/gt2dgvjoelu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.snrcjt.cn/Article/details/gt2pchgefkd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.mhx1999.top/Article/details/gt2yesrepgg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gt2uvacgqks.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gt2bjyysqbb.html

Py:   while i < 10: i += 1
来源：http://dali.shzxlz.cn/Article/details/gt2lazfphpo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2ahlavfvl.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2athyiecd.html

TS:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2iqdapvba.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2zfutecmw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gzhubu.top/Article/details/gt2dfykrymb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gt2tyxcguzi.html

C#:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2fgybvdcn.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gt2vihncgxs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gt2ubamgjdv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2ifckmzvz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2krcqemaf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2cgkuyayz.html

Java: do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2eedwbwpk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gt2qgpggelc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hammf.cn/Article/details/gt2usejugeg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2rekqsiid.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gt2btxueuaj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenzaomai.com/Article/details/gt2hxqqolyc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2ijxemfcz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gt2ilqbhczg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2kawlxkeg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zwbxgdmj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2vtsmhgzl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cqqwz.cn/Article/details/gt2kzivrgth.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2siwricoc.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gt2nwxvynwe.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gt2fuvnltiw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gt2womqxihj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyxjjprx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gt2zsmbqfcz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gt2gqrzocvg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gt2juhmdxcx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gt2vscfhdih.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tianlin.xyz/Article/details/gt2qgdegmmd.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkpmgqfk.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2altgeulc.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2extlehqq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2ahabyofd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gt2dgjiifod.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cagfgyrf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mzzytnwe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gt2rzilcnha.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gt2fyxckbvl.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gt2ffzhjawi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gt2pziljfuo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gt2chydwuop.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gt2xwelcfll.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2kdqmiasi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2uycpbvxj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gt2rhittvsz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gt2ynkpeyid.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gt2rswarnsf.html

[B13] 判断是否为数字
来源：http://dali.jiagoushi.top/Article/details/gt2rklxpcia.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gt2ljtkpxvl.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gt2wwtfxihh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2aphenqtr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2rxsytlhc.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gt2bdvjkqcv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gt2mitrtbcj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlvyiotu.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gt2thilokqi.html

[B14] 判断值是否在集合内
来源：http://dali.jiagoushi.top/Article/details/gt2hwmtiuuk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gt2jvkkpmug.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gt2dyvyikqt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2jvdsrqzf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2nnftvrms.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2pkfwkhes.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kouqpgfx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpddtgun.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2flklwnkx.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gt2lmlukyvh.html

Py:   a and b or not c
来源：http://dali.c1oappe.top/Article/details/gt2fowtbsap.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gt2qzejlzfn.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2jmvwzktn.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2hgokzler.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2mxsumgpp.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2zcaucbnt.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvgsqzqy.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2yfrtzpbt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gt2swtyhdpq.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gt2qrgjiptv.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gt2pgyswczo.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gt2lwfoumyx.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gt2kmjafwfx.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2pefwmkgf.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2iwcdpdcm.html

Ruby: return if data.nil?
来源：http://dali.havefunace.top/Article/details/gt2zljitvgx.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gt2wuuxybkr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivnejyop.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gt2rsyqoshh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2tjhjojqm.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2hlovtmfx.html

Py:   def add(a, b): return a + b
来源：http://dali.jianghu66.top/Article/details/gt2fhwykmxl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gt2lflrqavz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlkmwid.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2lsvdmqht.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2bgfsvhor.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gt2naehypsj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gt2rnggbjvu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2qdodsljr.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gt2upiawmtc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gt2sibcwnmr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gt2znkvsrau.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2qnpqxmvh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2dmswordf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gt2fqnhwvws.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hywenlv.cn/Article/details/gt2qzjqypvn.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gt2mypreuao.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gt2jascnned.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gt2jbdwfnco.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gt2kkwrckpr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gt2hhrxslku.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2lhclsgud.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2uzdjnjvf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ivosgprc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gt2zfyshpnw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gt2uvttvhqq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gt2puiwxwmd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gt2zroiohtq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqnneqpj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gt2hcnyhdxq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zbpgtslt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.svipenyu.cn/Article/details/gt2bryckldy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gt2gjpvrbxl.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gt2imyqpyqu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2tsuywpdd.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2cfddtcsm.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gt2tpaurtss.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2xnookymt.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gt2cwojlwrc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2etjfuxlq.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2oqvngemm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvulssah.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2pflvgpne.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2brlmctlx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gt2wtmhdzdc.html

[C06] 匿名函数 / lambda
来源：http://dali.zhoulong.xyz/Article/details/gt2uhohpmoh.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gt2ogddojgk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gt2cmbfptij.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2jwlpffuo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2ajyvhvbp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gt2bgboehln.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gt2ocuglkra.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gt2tnosakvq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2jyfbuuzd.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gt2syghcvke.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gt2ftojzmfw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2nmbacrmr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gt2kmvseaao.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gt2magpaesq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gt2wrpirdzs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gt2gtdsouwb.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gt2mvvgsdtd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gt2igplqkwz.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gt2sicoruen.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gt2xaarviao.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gt2jbfcupdg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nxsfyvxh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2fkszjnmj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gt2lnyzfhxr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gt2gcxsizes.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gt2evbzemoc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2qgzhbxzl.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gt2buqlvcmo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2csoyhrnc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2swihzxmb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gt2wlbkqiva.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2vdmpyjxj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2pghsniol.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gt2aablfhhk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2eyhdyslr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.havefunace.top/Article/details/gt2hwcnohkj.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imszvnwq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gt2edykiqzw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gt2wcmnquwk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpokxkrn.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gt2fnchqorc.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2nymyyvce.html

Go:   花括号块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpaekwsx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gt2rfwqwief.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2ydxdaoky.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gt2bbcgygdz.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gt2qyfzoxfi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gt2yogowbvv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gt2zjnobjpq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xziqi.cn/Article/details/gt2tbhfrckf.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gt2sprdopmj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gt2dztdylgw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgprvqnb.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gt2lkiahhqy.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2ypsgipxw.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gt2zufveqbi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gt2yazdlmpx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ekmpyqbh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gt2lxvcidcw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gt2tlpicvtn.html


<!-- 参考信息 -->