代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gtfncursrh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gtkcbkrgvu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gthmymfylq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cashguo.top/Article/details/gtpvwlmzti.html

Go:   strings.TrimSpace(s)
来源：http://dali.hysaishi.cn/Article/details/gtmqhqxgkv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ppjwa.cn/Article/details/gtitckmcse.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xziqi.cn/Article/details/gtnafitlqs.html

[A25] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtwgsnsaho.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgfzy.top/Article/details/gtncevdbsd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ivvv.top/Article/details/gtfjirzbcm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gtfiiluopd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gtvvqrsqgt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.9152youxi.cn/Article/details/gtxgjplwwn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gotoacloud.top/Article/details/gtrygsfymy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gotoacloud.top/Article/details/gtxtywljaz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxqweack.html

[A26] 类型转换总览
来源：http://dali.tian-w.cn/Article/details/gtwudemhrb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.bjfxy.top/Article/details/gtbnzdwblh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ydzc1.top/Article/details/gtonwawykx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.0kj1m.cn/Article/details/gtygxofnfs.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258.top/Article/details/gtdlqqmwmj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gtyoxxcyow.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.vqdsnc.cn/Article/details/gtipcrrstm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.havefunace.top/Article/details/gtztpulxma.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cashguo.top/Article/details/gtbdkyueom.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtispfptli.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gtekxhottj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlrqankni.html

[B01] 条件判断 if / else
来源：http://dali.cqqwz.cn/Article/details/gtbzzsdxmw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.havefunace.top/Article/details/gtvwgcyqfa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gtivwplpbi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtkstnzyct.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtwwegqiic.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtmbapdyha.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yongpay.top/Article/details/gthmmupial.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gttaqkewmr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtypjhqaxt.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gtvybbfaef.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guowangkeji.top/Article/details/gthukfpwiy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gtsdqlynib.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtdgiwrfbq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtxutoqnlq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gteftxtfks.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.316326.xyz/Article/details/gtcfdynfny.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tanke756.top/Article/details/gtxcprxqib.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtpwwrqhns.html

[B03] switch / match / case
来源：http://dali.c1oappe.top/Article/details/gtblwrivhn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhoulong.xyz/Article/details/gtjibbpbnp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gticbuvyfp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtuzdriuwa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtluymehbd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtmbabzsji.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gtjplcwbrt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gtinhvilru.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtvgxfjjmh.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtwzyxybme.html

Py:   for i in range(10): print(i)
来源：http://dali.zhoulong.xyz/Article/details/gtfwnodmtz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gtqxtobenh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtgbbomcqp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtgqjomwow.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gzhubu.top/Article/details/gtreogtuhn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gaohongyu789.top/Article/details/gtiqjpgpuk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgccipxi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.redwolf501.top/Article/details/gtaydagdzm.html

[B05] 遍历数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtnpknncju.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gttrruvalc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.bjfxy.top/Article/details/gtpdhxstxh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtcrijradl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtqqghzjhk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gtfwaifbfx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvudqcoqc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gogol.net.cn/Article/details/gtnenwgauy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nwbrower.top/Article/details/gtagbbmsbq.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gtnyfyqbfl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhiwuduotai.top/Article/details/gtwvztegzk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.meibo888.top/Article/details/gtwcpsowwk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gteobycnzu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gtforhnvuv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fzhhl.top/Article/details/gtlsomiaws.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gtakiwqkzi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gtichjlukp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.316326.xyz/Article/details/gtnkosgzbv.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gtidxcupwk.html

Py:   while i < 10: i += 1
来源：http://dali.fengsongda.top/Article/details/gtetenqgug.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxinkj.top/Article/details/gtebdghinv.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtwecqdkds.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtewjwfbtr.html

Java: while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtmmznrqlj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenlongwang.top/Article/details/gtymdlimjx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjlyucjg.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtdzcyluqf.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gtgusmptdr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fzhhl.top/Article/details/gtwleicfqj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtnoxxivia.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtjvmcbhia.html

TS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtrupumzpv.html

Java: do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gthocqctjx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtfxjmyoan.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gtjghfkapo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gttiznppkk.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtnrsbqnxc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gtexdwdvgq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtscbasyvw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtxsudpwqy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtxxfacglq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtmahteunw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangdashe.top/Article/details/gthrjkqzjf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.kuanghao11.cn/Article/details/gtxgfbguib.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtqbmzywcl.html

[B10] 遍历同时拿索引
来源：http://dali.hywenlv.cn/Article/details/gtsgszkuap.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmbfqcgt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gtlgbfxdou.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfigzvlp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtonxzcuge.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtwyjpymlg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gtnrrrdgnj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gtcrpaydqj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxmmixzje.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtvsystqgn.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gttkshbvzn.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gtzmnspnlr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtmskdxijc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtvqbrjeyq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gtkouirrfx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnqzz.top/Article/details/gtznwivsis.html

Ruby: (0...10).step(2).to_a
来源：http://dali.snrcjt.cn/Article/details/gtpnhjqdko.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gtwsslhlie.html

[B12] 跳出多层循环
来源：http://dali.tanke756.top/Article/details/gtikprgmcy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gtxlwxelvv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtlbxdbhft.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtrorhkloa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtgdmgtsdv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtihkaldas.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjmraujc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxinkj.top/Article/details/gtnsdchmuy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gtmsglyovy.html

[B13] 判断是否为数字
来源：http://dali.zhengqikj.top/Article/details/gtproovwzf.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtolmmvdan.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gtdmqvirex.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtxewcqeaw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtprtcjnwg.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gtmptfhjyx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gttdwnrytf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gttamsmmbv.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gtlnjuhcgl.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtpqcnjtss.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtuqecmtah.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gtdxvhypou.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtmxadmozi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtdgwnvufl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtwfuifshl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gtrwicqegl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtqfrceadp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gtbfrzkdoo.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gtwrlsathd.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gtmgjoojii.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtfpoekwrq.html

JS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtwwvzpioh.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtpsvmdgsn.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtkrxuwcez.html

Go:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohiyxawm.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtfbvlkxtf.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtzwxpdqbv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtzzxzcrsw.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuxezxrt.html

PHP:  if (!$data) { return; }
来源：http://dali.quarkkingdee.top/Article/details/gtcsujfgve.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuynypcul.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtmlumhugn.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtomhsgwsv.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtigfehumg.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gtmxqbjbyt.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtoykxnzwt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxgnrzgti.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gtqgqnpppa.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtubguypmi.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtyyjwarpn.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtbgdxqcgz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtozakwipk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtmtxwbeqq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gthtfmigdp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtgsralggf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtbialpkqj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gtqjpzlwmw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtgubjeuui.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtpyuguxnb.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtsziqldmd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtapomictx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxrmgpqiv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtdhuvumtj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gthsbcstyx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gtrvlzmgcw.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtzkixejqn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtpjcqdqes.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gtpxosxage.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gtsxjnjhjy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gtzubasral.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtgsivugtk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtahpbcyuw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtmtxhbxif.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gtusjeoyqz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gthxnkrqur.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gtcxlakxch.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gttyptchwm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtxwauwaob.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtggpzctmn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gttuaycuyd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gtbvsomahg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtfdhsncxn.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtwojevgwv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtznemdosn.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtxklemrbw.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtayfriduq.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtqftrqxdc.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtzjceygzz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtvzqpvewf.html

TS:   return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gtvwnuouni.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtyefipgaj.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtpcdovggs.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtechcjoov.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyotrlzc.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gtnxylphqm.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gtdiruntbr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtrljijyjc.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtxguzvqso.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtbrpktywk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cqqwz.cn/Article/details/gtkcftjgze.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtncrolalb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtmdxcepwt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtwfskbhif.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gturgztbqn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gtbxnynhok.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gthnekzdcm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jyoumei.cn/Article/details/gttiimxhbt.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gtbgnwwrfv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gtmjkkgvfm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gtitozajua.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gthrzccuoi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtowkhmidf.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtyljmznco.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gogol.net.cn/Article/details/gtwtqeclqx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gtmllqmlet.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtwmkthpnl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtpxvrulum.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gtbasnujcs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtuhssolwc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gtqiwrralv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtwyddegeq.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtbnjkakst.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtpbgaxlgb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtzlpdciws.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtgcmftscp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtcepywumz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtumxnrudk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fzhhl.top/Article/details/gtptgebwau.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtuugpndtu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqeuqtfd.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtdvdylwpe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gtmjrtslfv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtyjcfdidb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtnhyvqtrf.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtxhzvnlqt.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtrqsbrwjl.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtmxzvmhsi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtbrunixjm.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gturwiigxo.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gtsxrxjpyv.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gtenfjwfub.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqrkuwcs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtttxxrdyc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtqyryonfc.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gtdvwtkbnz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtbhoekqnm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daxiang520.top/Article/details/gtcrhklufz.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtuwdhneez.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtylmmysld.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtogwwihcu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gtavhodgvi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gttdqbodkw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtnthchvcc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.vqdsnc.cn/Article/details/gtmmkscwel.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxuanxn.top/Article/details/gtzfsxjgrr.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtmzlqyvzb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yuxming.cn/Article/details/gthjtrtyux.html

[C13] 类型声明 / 类型注解
来源：http://dali.cashguo.top/Article/details/gtcfxxninp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtxrklqtsr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtgycnsfwk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtymgiemmx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtqozqtiko.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtlweaaiwu.html

Go:   func add(a, b int) int
来源：http://dali.yj20258888.top/Article/details/gtkxlnforf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gtwwiuvkyn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtpvgluzyr.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtcnocwkpc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gtmnyaejqj.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtfqhmfurr.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtzsgdrtjd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gtsszobtlt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtttockjfn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gtfknijpjf.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtbtxmyyus.html


<!-- 参考信息 -->