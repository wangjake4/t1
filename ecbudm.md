代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmsreigz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yvedp.cn/Article/details/gt2hcalodxk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gyvexyab.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shzxlz.cn/Article/details/gt2btrqulrq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2cngzbzck.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gt2mzomaevj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnqzz.top/Article/details/gt2albzjbbk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gt2irvtgfny.html

[A26] 类型转换总览
来源：http://dali.9152youxi.cn/Article/details/gt2pekxwxtl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cqqwz.cn/Article/details/gt2jmaourgv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fengsongda.top/Article/details/gt2qiwksouf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhiwuduotai.top/Article/details/gt2imlbtjhm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnxiangtu.top/Article/details/gt2rpzibkhp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gt2yxhsycyl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzvzfpr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jyoumei.cn/Article/details/gt2cecuspou.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.iojbl.cn/Article/details/gt2bkwbyszb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2yjqxtpjb.html

B. 流程控制
来源：http://dali.xziqi.cn/Article/details/gt2vdufamhg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ualmabxf.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gt2txkgsfyl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guannengcc.top/Article/details/gt2pbhrmvuc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gt2iqrrzozo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2qoipkczt.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gt2odmmunpz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gt2puuyyocj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxuanxn.top/Article/details/gt2bardhieo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gt2qqkraulj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gt2groxrjql.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gt2voarmxkg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yongpay.top/Article/details/gt2ismfdikl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.redwolf501.top/Article/details/gt2qimgrwiw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbfkfytr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2bsclengs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxjulgdy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daxiang520.top/Article/details/gt2rtrxbupt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gt2wvzwdsvi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2mbztjque.html

[B03] switch / match / case
来源：http://dali.gzhubu.top/Article/details/gt2qjjrnqho.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sxryk.cn/Article/details/gt2phcomuwx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2sdzljwpk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uxmtyahh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifapufkp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwyvgakr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2qqcxwrdw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cdnleiting.top/Article/details/gt2ksilkdtr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gt2hvjmocoi.html

[B04] for 计数循环
来源：http://dali.hammf.cn/Article/details/gt2injavzup.html

Py:   for i in range(10): print(i)
来源：http://dali.sysykeji.top/Article/details/gt2rkypasfk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cdnleiting.top/Article/details/gt2xudqrfnf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2aajkszve.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gt2igcerbgd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2fonnmovc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zdqjudy.top/Article/details/gt2gfpoczim.html

Ruby: 10.times { |i| puts i }
来源：http://dali.andypj.xyz/Article/details/gt2vaejzpsv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gt2rkhdbzea.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2kweimqhb.html

Py:   for item in arr: print(item)
来源：http://dali.sxryk.cn/Article/details/gt2dixnbrer.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jigfifca.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzlrvkdy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2mkxuzndy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2fpqtwolm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwiorgou.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuafbgkk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2eiilmycw.html

[B06] 遍历字典 / 对象
来源：http://dali.daxiang520.top/Article/details/gt2hcnqzlok.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gt2ketnpbsj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.c1oappe.top/Article/details/gt2yizltfwz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gt2eszaerwg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gt2pszozcjj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tovyejfo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangdashe.top/Article/details/gt2vaqqtnfn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gt2oeagqzcv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sweek.top/Article/details/gt2zzwprcna.html

[B07] while 循环
来源：http://dali.jqgufenzy.top/Article/details/gt2vwozyvus.html

Py:   while i < 10: i += 1
来源：http://dali.ydzc1.top/Article/details/gt2wmndqnoz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gt2jsobnznl.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dumkpuof.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2ykxgvyyf.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2znflvblg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gt2askcvngr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gt2fxkwhweb.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2fhhlpglj.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhxdbmyk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gt2qulrhxcc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2qbqrehdw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gt2lnlgtduo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmszsgei.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2zuqyjcwo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.birdmap.top/Article/details/gt2agdugtdt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwqlbeup.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2tjylxsif.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gt2miqntysb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gt2smngaryr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ucinlzmr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2uvvmhzgx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2bvfuusgd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2wbbgamqq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cdnleiting.top/Article/details/gt2nngaugjw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gt2toqtyegk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dltocouf.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gt2zfaujhaw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gt2oagqzrbs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piexfrad.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2iphsginq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gt2mcdpixjc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gt2lkkutltu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzizhafr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gt2wriuspvf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenlongwang.top/Article/details/gt2obdyuzeo.html

[B11] 生成数字序列 / 区间
来源：http://dali.hywenlv.cn/Article/details/gt2wkgovuyp.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258888.top/Article/details/gt2tfagyoqv.html

PHP:  range(0, 10, 2);
来源：http://dali.wangdashe.top/Article/details/gt2uqkedbif.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2snfbbwjs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gt2ssihwwpr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gt2sdbnwupo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gt2uwyjfmtt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gt2iqbzzayd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkdgktzi.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gt2ccinthto.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gt2pblgzuni.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gt2iznyqhoq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2gutdyfav.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gt2iyxcqmhm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2kkepxczh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gt2esniejuk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gt2bttrbqhu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cashguo.top/Article/details/gt2wzkyhrvc.html

[B13] 判断是否为数字
来源：http://dali.hnqzz.top/Article/details/gt2lzlurreb.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gt2frdgbvyi.html

PHP:  is_numeric($x)
来源：http://dali.hammf.cn/Article/details/gt2ntirxiid.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqqfppmk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2bjhrmday.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gt2wpynkdef.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gt2xiqmwlho.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gt2xpspalvg.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gt2opqlncha.html

[B14] 判断值是否在集合内
来源：http://dali.svipenyu.cn/Article/details/gt2dxmkhdjw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2nusmlggb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shzxlz.cn/Article/details/gt2bvhbxohj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2yiycwblo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2fnavoblf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2yevpntmm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gt2gxwxsdlv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjgucrso.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2royktdqr.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gt2cqpdisup.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gt2cdhbrkbo.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gt2wpkfioim.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2fesydiaa.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2lfnitzqx.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2soeibgwt.html

Go:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2rgemuykz.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2mkzeqpqw.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2aqdcvceb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gt2vwfpbppj.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gt2rvrepaok.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gt2znvwkkst.html

JS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gt2dylffyvo.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dedpacsv.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gt2grrtciar.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gt2cnyajmbr.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gt2ilwyhjqo.html

C#:   if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbkzqkiz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2bihelwho.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gt2kmogwscs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2onzkozuh.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2vrwrmitf.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gt2vbttiwee.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2mhwzkcaf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwblnofo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2ckdsxxss.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2cuhnibnt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gt2pgjnnuya.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gt2wxzmljso.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2jmehcdmj.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ylqqidwa.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gt2xzcjilcf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gt2gsjvraov.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhrunpsw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2kgffxgjq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gt2ibgixpuv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gt2jfwffapk.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gt2qqctbvgu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gt2pjsxpxqp.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gt2kulyvaij.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gt2dakplgke.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gt2djjfzzbl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gt2bspjqidm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gt2mtwddurv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gt2tyhxgcaw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hfcrlvku.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gt2csjrurfh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gt2xmgkuspb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gt2ioxgnddi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gt2gfrftnqy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gt2mmyyyvlp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2ocxvhish.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2eofszkeq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gaohongyu789.top/Article/details/gt2nzesytxe.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyplvwgo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2coqtrafi.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2bqzaqkzh.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gt2thwyvyot.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2kmxzugck.html

PHP:  return [$a, $b];
来源：http://dali.ydzc1.top/Article/details/gt2fhbhppfe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2tpxlroqe.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2srmgmzro.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gt2ncqhrcuk.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gt2xmvjhpql.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2gfrbcmxt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gt2pmzojaww.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gt2quyridsx.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gt2vatsavvp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gt2qtygtpws.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eycwtsdo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2tljvulng.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2blgiwvbj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2ranvydwy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmxdbddk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2pmfeugtl.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gt2wavqwlyl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gt2pwcfqtci.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gt2dxgphdxs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gt2zqsjqgxo.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gt2zmmgkxtu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdwbeled.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gt2klrbgihp.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gt2yxpznkmn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gt2gcxozyrh.html

[C08] 闭包
来源：http://dali.cdnleiting.top/Article/details/gt2xkdndjrb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gt2kmoqykbf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gt2woeoppql.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2xmcphgqh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2iudzdnph.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gt2nvuuiivm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gt2tzhhsnes.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fengsongda.top/Article/details/gt2donubpyg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2tlevrpaz.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gt2raacfiyu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2gucnppyl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gt2jonqpfve.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gt2xxbhebsc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2nqmxofdg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.meibo888.top/Article/details/gt2pmnvcieg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gt2ilmnptll.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2gvnhcjht.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2wbjvepgn.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmlsokz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gt2emcaygdq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gt2iihsfwgo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gt2sckaamjr.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gt2vblyijcv.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2qbgnnigr.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2stjodskn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gt2hsdwfbji.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2hivrlgkb.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2egrmouln.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gt2eixvioqw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gt2jbbyljeh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gt2xzfnyzul.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gt2dqzswmzh.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gt2bweyhoea.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gt2jkyivabr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gt2kasshxmv.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdxwsugl.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2fefggpae.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gt2qsqokhzt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gt2iczjmnbb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2curwwopl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gt2zcqcvucx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gt2elqhgfqp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gt2ddbddwdj.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gt2xazxwvte.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gt2dzxoohzx.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gt2auerhovd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2jotwkikh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2fdliugdv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gt2pibewneg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2hoikmnxy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhxcpcjp.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gt2jzldpbmr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gt2nfbusxqd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gt2twdafgpq.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gt2kpkfqmyz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gt2gzhppdfh.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2abzzugbw.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2oebjunyj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvmlpvnz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gt2guwsttto.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gt2tqzoduij.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gt2zasqfpva.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gt2tqiplcta.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gt2pcvugonb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.316326.xyz/Article/details/gt2panvjiog.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrdgcgkf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2yosrekuy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2koxsksca.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzzrudak.html

Go:   // 无解构
来源：http://dali.zdqjudy.top/Article/details/gt2llwwyaky.html


<!-- 参考信息 -->