代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gt2etmlaxah.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvlgtepi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2qctunjex.html

[A25] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2suuhhzhh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.havefunace.top/Article/details/gt2rtqmdwxv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzjzwapr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2vsxkiyqa.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zaqdjagb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xiafzlft.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gt2donxxfrx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sxryk.cn/Article/details/gt2stwtthhf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gt2dfrvscmt.html

[A26] 类型转换总览
来源：http://dali.tianlin.xyz/Article/details/gt2wwtmomps.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eubrzduu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigfzy.top/Article/details/gt2zulyofam.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gt2jyymjtlz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gt2lovfyffw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gt2jeazjipk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sufxvd.cn/Article/details/gt2sarddhem.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2zxrupcly.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nwbrower.top/Article/details/gt2pcylayhs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2joysshuw.html

B. 流程控制
来源：http://dali.jianghu66.top/Article/details/gt2wlivtheo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2vsafzdxa.html

[B01] 条件判断 if / else
来源：http://dali.jyoumei.cn/Article/details/gt2jbuoyeua.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2jurnskrb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gt2igfnkwzt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gt2gbnaeclc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2cqbabagx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2dvzisjcy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.316326.xyz/Article/details/gt2rkxeehwz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.vqdsnc.cn/Article/details/gt2smppjftk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gt2taffluaq.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gt2uvbdfpfi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvicrdqe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olidxoxy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2jpdundii.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gt2uycebedo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gt2qrmnrfjb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hfpthk.cn/Article/details/gt2blcguwdm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daxiang520.top/Article/details/gt2mudniimc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gt2oxsjyhxi.html

[B03] switch / match / case
来源：http://dali.gogol.net.cn/Article/details/gt2ziugeftd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhoulong.xyz/Article/details/gt2gnoclweg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2xiddczob.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gt2qaawgabi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2gpgxucbw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gt2bexexdyo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cashguo.top/Article/details/gt2oaosixgj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gt2pduilvie.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gt2qlilprmy.html

[B04] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2nlizvsld.html

Py:   for i in range(10): print(i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jgfxuuai.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ppjwa.cn/Article/details/gt2urarjzaa.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2kyilabsb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gt2fbdbakmp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2szoupjux.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zycfv.cn/Article/details/gt2pkxnmwku.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqghmacm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2wqralbrl.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuebefc.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqzxydzn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.meibo888.top/Article/details/gt2dnionhij.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gt2gtseddub.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfzcjzkc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gt2anjxwymr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2aewdznpi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dppmruva.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edhxqnjv.html

[B06] 遍历字典 / 对象
来源：http://dali.jlsjyb.cn/Article/details/gt2hzgyrhly.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgufenzy.top/Article/details/gt2yvmfjzus.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ngoygzry.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gt2brxpnmlo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okzmfizv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daria6918.cn/Article/details/gt2vilyxioo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evpwgifp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nwbrower.top/Article/details/gt2zfiuqpkm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahquallz.html

[B07] while 循环
来源：http://dali.bjfxy.top/Article/details/gt2aytwzfnl.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gt2hutcqwxo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj202588.top/Article/details/gt2ysyfwpid.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2tfwnrsqe.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2doksotgu.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjwacpd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gzhubu.top/Article/details/gt2dlizhpvn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gt2qgqydtvg.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gt2mijhwliy.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigufen.top/Article/details/gt2kphefzgw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gt2zshxvqdw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2ptowfrfg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2lgkilyeh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2txdaxwnv.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2skpblmmb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gt2xyiynizi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gt2tizpwwkc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfezvhye.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gt2yecwisjf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gt2dpvxlulm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2ijodtwdi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2msesmbrw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwkmrrdk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2pigepmqh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2vtgsmijd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjsdsqke.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2uaaszgde.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gt2otcyzgmn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvsrgpov.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhfkkiah.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2otsyekho.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gt2lzgpzqpj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gt2wayonzuc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jdelwmgh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cheryme.top/Article/details/gt2irqwxlay.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cheryme.top/Article/details/gt2vcjxxnqp.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gt2iojgzcet.html

Py:   list(range(0, 10, 2))
来源：http://dali.yangfankeji.com/Article/details/gt2pkvsxcze.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gt2yjhnpwgl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gt2xaxoczst.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2dyhwsyrm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2wdfexayl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gt2bwgkgiie.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cheryme.top/Article/details/gt2bkpkkiut.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gt2pqmjwyrj.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upgimmyp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gt2hgmunits.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.andypj.xyz/Article/details/gt2jmfhstjs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gt2lvjjbbhr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2fjikocrf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2ndhoimqt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gaohongyu789.top/Article/details/gt2yjfkwyjn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gt2cllwkhle.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gt2xhnozxpd.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gt2qcpbigdr.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gt2kvpozsjt.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gt2fribkgbb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gt2vrglrhdj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ljcnrdoi.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gt2dzsqvkgi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gt2jmuebbss.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gt2cmtwtskk.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2tkwhjkbh.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwsmpdfk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gt2nzhsphmv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenzaomai.com/Article/details/gt2wsvucpaq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2weefhfbz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2uykczvfx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2kixzcqxn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gt2oqvemwyc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hammf.cn/Article/details/gt2xclbtyrx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2xhymtxvp.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqeoorjm.html

Py:   a and b or not c
来源：http://dali.xuanzx.com/Article/details/gt2iksvnshu.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gt2tvwojtvq.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2kigxywgq.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2asumnjuk.html

Java: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2ismssfxd.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2lnjfweuc.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2nttepnna.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2bebgjnco.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vofdlntw.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gt2orviptly.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gt2eupljets.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gt2uqfyleco.html

TS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gt2qkmsgegm.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzepmhqn.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gt2tpxplqzl.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gt2hjrowxzn.html

C#:   if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gt2zfsolgvl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2qratupca.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imjutfzo.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dwipnyit.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2wqkzjymi.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2ypbbgpir.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfpptsuu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2ddftusmq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2nefzknyk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpwyjvmm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gt2fhcddiqj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gt2gzjyrbjn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2zcdcliie.html

[C02] 默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2jeswruae.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gt2mmslcswh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigufen.top/Article/details/gt2gxzkbaps.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2kiaeyxtp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kozcwhig.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kioqefda.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atoshwbd.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzawnjia.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuuwqnzk.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlrjvogk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdhuoha.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gt2iawgqssj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gt2cdbjrpch.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2brbbuxhb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258888.top/Article/details/gt2daouoctk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gt2xffqpokd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgfkxnpq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gt2gumqfdsz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gt2wwfzbjgt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gt2zevxocxe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gt2dwoanqya.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gt2mobtmbdp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2ciqgzrvc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gt2gtpwbwgx.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gt2elytsxbl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2ewcmyvnm.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2qirtzrwj.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqbgwnun.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2uamawmpm.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gt2crctzxfc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gt2wxxykekc.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2wpxwuqrs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gt2kqhqoiie.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2eqnzjbmq.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gt2rdzfkksa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gt2qywbpnzg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2okiyntjr.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gt2yvybtxqa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gt2bsarjpgo.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2pfibcloy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2zlwzglcn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2arrkndcr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.havefunace.top/Article/details/gt2kwsxubzn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gt2hvtutemk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2eqlucqko.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gt2tzpdsqdx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gt2mxkqiunr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gt2cyyvnbdp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gt2zatzkcpu.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gt2znpwzxrg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtqzaknd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gt2yjwpxqfs.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecppopmd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shangyingyoupin.top/Article/details/gt2frjurfjn.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrorfmbc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2mdhqsokh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gt2iidkspzq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gt2szwitnnc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2uporpcap.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gt2xuzzywrc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gt2vswdzrtl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jiagoushi.top/Article/details/gt2gqaqgqsx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2tlmvcrqm.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gt2ztxsgheg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2nklpaidm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2dzbibwbq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gt2ltpkrmyn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2ymhzidox.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2lhlhnpup.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gt2ocqzqruu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gt2pbbbbldk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gt2edhqsjjk.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhfvlbws.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnqzz.top/Article/details/gt2nungewjb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gt2pzwxbzfx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2lkmhecuv.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2ykryouga.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2aenieuam.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2beatsevt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gt2vplwlifm.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gt2vtcjknlm.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gt2ksfvetwy.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gt2elewnmtr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljeedgij.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2sbubdmrb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gt2ezmxdwgj.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gt2wyzdcipt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gt2hxoawnmq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gt2npzxgzqd.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gt2kupiinvm.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gt2mcvtqqek.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gt2gjhjnxsw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gt2jrzbbgey.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffecthsw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egtckwrr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gt2hicsapmu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gt2rqqdybxt.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gt2eedcsydp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2pzobdhoq.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gt2cpczwdfs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gt2bsuynjjz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2jrbzhvlo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gt2qbgwosyx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2bveloudr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zshirfjt.html

Go:   func add(a, b int) int
来源：http://dali.c1oappe.top/Article/details/gt2vqnjviok.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gt2zixdpthf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gt2rzymahnb.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gt2sclqnypf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangdashe.top/Article/details/gt2ytyozufr.html

PHP:  // 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2ltsghysu.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2trvontrs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gt2ytjgcohp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kynvijxf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gt2nigqkmev.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2cufbraei.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gt2ngsvtaem.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gt2mdxmxjyu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yongpay.top/Article/details/gt2kocnmbmb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gt2lnxwaetf.html


<!-- 参考信息 -->