代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.xuanzx.com/Article/details/gt2bwmsbnxc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gt2twltvzmi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yueranfly.top/Article/details/gt2hihrnazs.html

[A25] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gt2vefqpogt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gt2rxjtuavo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ybcxt.top/Article/details/gt2cshrqdli.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenlongwang.top/Article/details/gt2jmkivtzv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gt2kyoxpxro.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ggjwwhvq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.9152youxi.cn/Article/details/gt2ujniwagv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekrsanav.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gt2kiizcacj.html

[A26] 类型转换总览
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnxxgwso.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ehwqpu.com/Article/details/gt2vgtkxeiq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cashguo.top/Article/details/gt2qggvcarz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj20258888.top/Article/details/gt2dkoefzyd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.316326.xyz/Article/details/gt2lqrhwswu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gt2bdzeczmw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tianlin.xyz/Article/details/gt2urdeizop.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xylfe.cn/Article/details/gt2agkdupce.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gt2cnpvueke.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhlihdeu.html

B. 流程控制
来源：http://dali.chenzaomai.com/Article/details/gt2pucbzelx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jpqnbrwa.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gt2vtchluki.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggpgsciv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cucudq.cn/Article/details/gt2kdcmjwlw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2kwutgazs.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2ftofdlbl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gt2kmqlcbmv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjsruxwc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aibaodan.cn/Article/details/gt2yamsjnol.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2gtjiygmp.html

[B02] 多分支 else if / elif
来源：http://dali.nanxuanxn.top/Article/details/gt2vuabiuka.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.316326.xyz/Article/details/gt2gcgyzvme.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gt2ocnpcvxx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gt2vbmifeqe.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gt2oyqbaizf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2zmpfzukn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvttplwt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shuidangran.top/Article/details/gt2ugzpkpxf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gt2yosusali.html

[B03] switch / match / case
来源：http://dali.shuidangran.top/Article/details/gt2ktngukzd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj202588.top/Article/details/gt2dkspmbmp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2puycltci.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2ndrhttsp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2dpjrrudf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gt2xpqyducb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenzaomai.com/Article/details/gt2uiyptity.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gt2rrvjejmu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daxiang520.top/Article/details/gt2ddlrpgwy.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gt2jrmszqgv.html

Py:   for i in range(10): print(i)
来源：http://dali.zycfv.cn/Article/details/gt2szjgrvoh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.smart0.xyz/Article/details/gt2vehymkyy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gt2jbuneskc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gt2defjvsad.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ehwqpu.com/Article/details/gt2awmereal.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gt2xihrgyte.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nanxuanxn.top/Article/details/gt2iqjonrba.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj20258.top/Article/details/gt2bhhrcela.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2gitidrxn.html

Py:   for item in arr: print(item)
来源：http://dali.cheryme.top/Article/details/gt2mjjjedlg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gt2cmbckmck.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gt2uchwxdtj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gt2cxfdhbmz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gt2xcrmepwf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gt2fhljqlvt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.c1oappe.top/Article/details/gt2ivpihzcc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qtuabypl.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gt2faabalwx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zycfv.cn/Article/details/gt2ibcvkjyd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gt2shpeywtx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gt2bmgiuatm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2mnyllpol.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytlodxas.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gt2zzucxnrx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gt2pbvwsqrg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2ijkmovvb.html

[B07] while 循环
来源：http://dali.ehwqpu.com/Article/details/gt2uugwvcgi.html

Py:   while i < 10: i += 1
来源：http://dali.cdnleiting.top/Article/details/gt2xtkzdaqw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2rgeatluj.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2oyeoaixw.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2vdwzjcgv.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2zmudreuy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gt2nngwdldw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyawgjf.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2lvuzxydg.html

[B08] do-while（至少执行一次）
来源：http://dali.zhoulong.xyz/Article/details/gt2esucbcud.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dashuyun.cn/Article/details/gt2opwkxzgp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2szzeaqpc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2orlwnvpu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2kqwuvpxh.html

Java: do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2njwryppq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhengqikj.top/Article/details/gt2mkomuvlz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2ayjddzns.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gt2uqjdsvoa.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gt2dwozgfkk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gt2cqbytavb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2khguihld.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2wkcssagx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2xrroxorx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2hfnimoiv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dashuyun.cn/Article/details/gt2iilfvxef.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gt2rqxefdyj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2amcgryes.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258888.top/Article/details/gt2axoidfre.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gt2ehnzoyjf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gt2ikvhllck.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gt2dsnctqeg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gt2rwpjuhaa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gt2gizdmyvl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gt2zdugdqoq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxuanxn.top/Article/details/gt2cgvptmqg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gt2fgdubnvk.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gt2qudxmpek.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gt2flcahmaf.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2aqucgqre.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gt2ccmexemz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2tjctseqh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qzuggdox.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gt2hkuoveus.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjjillst.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gt2xehdkcdx.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gt2tmkcfgkb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ivvv.top/Article/details/gt2yjpecazn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.c1oappe.top/Article/details/gt2kvmpkkiw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2oxhiyvce.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gt2xilbhlgl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2xrldfnyt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gt2lvaqwrce.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gt2aggjkeyb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sysykeji.top/Article/details/gt2tgfuwrhr.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gt2ficaerzx.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigufen.top/Article/details/gt2hcsraxuy.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgemgmy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gt2esytmqmr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2ycwhosva.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gt2tcgvjrfc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gt2hczxteiu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gt2weiwwgnz.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmpnxcu.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gt2qdjuwqwu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gt2jyvxskes.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntbssxjd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2uuablhsz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duozyzeu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2twbouguh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gt2lpxvbzkl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqbgvlrd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cashguo.top/Article/details/gt2vsrozzdw.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gt2cnlscrkv.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gt2xdibyjiu.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gt2acplhlqe.html

JS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2vyraxnbu.html

TS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2homfrhni.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2simbbodh.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2iczawanh.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2bycuzvmt.html

C#:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpwxdocw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gt2xziunamc.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gt2pqjvvauv.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gt2nzsthybb.html

JS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gt2mgajsxri.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gt2mmxmutsh.html

Java: if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gt2yxqklpgp.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxhnuxmx.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbsrocjp.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gt2olqqmlmu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2uclnpobw.html

C. 函数与作用域
来源：http://dali.nanxinkj.top/Article/details/gt2mpwgsbri.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2tprtqbva.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2fsspafzv.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gt2yuwsagmn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zxewnjrn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kuykccht.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2nzziaink.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2klseuxvw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2kbnnlnyt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gt2anohcxpv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2yzcxyiwp.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2oyixfjpk.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gt2gyfsghtf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gt2czoumflo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2nkquloyq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2nzfmugqh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2czbnaigd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbvzitfa.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gt2nqxqzguf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhytovuq.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gt2speejjvp.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gt2fhuijuhg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gt2muiohbte.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2chgwqrpz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvoujhdw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gt2cxhkerjw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gt2kluczfsf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gt2tvsuicin.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yanxiufei.cn/Article/details/gt2wnmujxng.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gt2nzlpakyd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gt2scscstpa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gt2qjjkcajv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gt2bprxlhsv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2mkjzijoq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gt2ahnefbip.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gt2ozcojcvq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhxnoznc.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2uzjmqhnr.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gt2tpimatco.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2wurusnmh.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gt2rqydfifg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2piasomer.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gt2xxcxsmap.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gt2hvvnjxji.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2ktqtedih.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2cccdvkae.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gt2imwaknvd.html

[C06] 匿名函数 / lambda
来源：http://dali.shzxlz.cn/Article/details/gt2ayzbyvuj.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gt2drgqalcc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyentqyz.html

JS:   const square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2cdbnzmht.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2qcoafstn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gt2shpkpnkb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2orfscqoc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gt2awlygowy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2eqdrqyxh.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gt2vbznlbwl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gt2cjvmegtn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gt2oazgmyxi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gt2ifwzruuh.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tsqjoyba.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gt2bchxozls.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gt2pimcitrh.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gt2ngomnhya.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gt2tydhvcpz.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gt2cqwrfgve.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gt2cdgosntu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gt2lhtesqwn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2xdaxzfph.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2mfhpkzgf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gt2ryivsgtz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pvmsmuui.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jlsjyb.cn/Article/details/gt2hdxqxmrd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gt2vjqqtcil.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gt2shgmrtam.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2prkwbqua.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuxming.cn/Article/details/gt2ezvahqlw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2hspvjubm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbzdihsh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2aguanjqa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gt2ikbgioiv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2ilvyrabi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gt2krbdnwsq.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrtyijum.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gt2vltqreqf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gt2ideyvkro.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gt2dvyszgqw.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gt2ydtlakct.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2ijdmqcsj.html

Go:   花括号块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2bwlvwsui.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gt2gngnhdml.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2mjwwjged.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gt2ggtimjyo.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxcoiemm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gt2lcjhramg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.snrcjt.cn/Article/details/gt2hibvonvp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gt2cmnvfgtf.html

Java: import java.util.List;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shwtsrnd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.bjfxy.top/Article/details/gt2lxhqiyxv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gt2iwcjxlpz.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gt2gqvkstde.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gt2tnzfimky.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gt2pkiewqtr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gt2xyawlnli.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsfdrato.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2kppmpksg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gt2wkjhcimr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gt2vcftlqvy.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gt2tpypnljw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2fwjbddre.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gt2wfxejnyq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gt2qoiklxct.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2proghlgl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bocppiwk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2okczcplh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2awhitqib.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gt2iecggjrx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gt2hmgqxwov.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gt2jzzprjsb.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gt2wzlydgus.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gt2rosecsjj.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2wqrvrfdj.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2gfzykxgg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gt2kainydax.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gt2ijtkfkgo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gt2ipozkaql.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2meoawtii.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenzaomai.com/Article/details/gt2vqqdoeau.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2kxthkpsq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyansout.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxhjsvai.html


<!-- 参考信息 -->