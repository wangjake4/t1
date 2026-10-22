代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.pycfn.com/Article/details/gt2bsjelnux.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lojmfwyt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gt2wtbrhuyj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gt2ydrwlehq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuxming.cn/Article/details/gt2tgfvqigj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2kztjonyw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhiwuduotai.top/Article/details/gt2psdgfnbj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gt2pdxewvke.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gt2zjobuqcj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gt2zcaxzdix.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.mhx1999.top/Article/details/gt2owzhbxpf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fzhhl.top/Article/details/gt2nikrpdwv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gzhubu.top/Article/details/gt2awvkvtiu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gt2nihweile.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ptvjgkwq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xylfe.cn/Article/details/gt2uxkpjmab.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gt2srpqqyul.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ioshsced.html

B. 流程控制
来源：http://dali.zhixingplan.top/Article/details/gt2cezoyazl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2mvtgouxu.html

[B01] 条件判断 if / else
来源：http://dali.birdmap.top/Article/details/gt2abaliwaz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gt2vyfizfdk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nhreghqo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2gglzqwte.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gt2jepsiiis.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iciddfqw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.316326.xyz/Article/details/gt2ixevlutb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258888.top/Article/details/gt2hlbgrkig.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gt2ozudbcea.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gt2wevbhkgf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkptopzj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zycfv.cn/Article/details/gt2ojqfuudb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2ekhcxwxl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gt2acbvdlhb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2zsboymor.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gt2atfiqtbj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bezygmva.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2inmkjbsr.html

[B03] switch / match / case
来源：http://dali.hysaishi.cn/Article/details/gt2izienmhm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangdashe.top/Article/details/gt2jdtgmoff.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gt2tyhvlyix.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gt2aigukwrd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2jyhlzsmp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2ksfdqgbo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zycfv.cn/Article/details/gt2rtzpmiyh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gaohongyu789.top/Article/details/gt2fjtoyvjn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258.top/Article/details/gt2nkecsuqg.html

[B04] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gt2vshfhscb.html

Py:   for i in range(10): print(i)
来源：http://dali.xinyue.icu/Article/details/gt2aqihezik.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gt2jhooyqor.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gt2wbxvxbwp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2viixzsae.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gt2zywgawnt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgufenzy.top/Article/details/gt2fooohwse.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ivvv.top/Article/details/gt2vxhchbqy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gt2iolhnvfe.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2alpghoyu.html

Py:   for item in arr: print(item)
来源：http://dali.gaohongyu789.top/Article/details/gt2bhwmgudx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gt2iuegzssw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2ewxrssya.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gt2jfwkfhmi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2nlvnqgzg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.c1oappe.top/Article/details/gt2tnblfdmf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gt2vmxfjsmz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ivvv.top/Article/details/gt2wxbbljqg.html

[B06] 遍历字典 / 对象
来源：http://dali.guannengcc.top/Article/details/gt2plasqpgu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigufen.top/Article/details/gt2gmmcpmhi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.mhx1999.top/Article/details/gt2ygiastwn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gt2arizuucz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2iosdqlvz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gt2hpprhoqy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tanke756.top/Article/details/gt2mvdrzzlc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ehwqpu.com/Article/details/gt2olvynbij.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.svipenyu.cn/Article/details/gt2sppygdsl.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gt2jbazgdln.html

Py:   while i < 10: i += 1
来源：http://dali.9152youxi.cn/Article/details/gt2vmriklcz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2xakxyyvs.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2ofkalxvz.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2sbcxygoa.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gt2cjkvxurh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zycfv.cn/Article/details/gt2mkrmqjbg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gt2eswrliwn.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2fyglxliu.html

[B08] do-while（至少执行一次）
来源：http://dali.fzhhl.top/Article/details/gt2nndjkegg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mjayqiaq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2gkxghdkr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2paadthgk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2ouyqaszt.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2ibgotnvu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gt2fkxundtg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2reihwmvq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2kwdtogia.html

[B09] break 与 continue
来源：http://dali.jinqigufen.top/Article/details/gt2ypgkyjvf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gt2zrihgytk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2idvtwicr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2zppsohcj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2kdvlrljy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2uqkrrzzw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxunvbze.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gt2bkmnjxpr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ftaisbup.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyrqasut.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zycfv.cn/Article/details/gt2whiwujzx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gt2pamyngsk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2ecrhaymz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gt2akqwmita.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gt2xevjklce.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nwbrower.top/Article/details/gt2nsjcxxok.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gt2ewooghrn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gt2hxkmvtsu.html

[B11] 生成数字序列 / 区间
来源：http://dali.havefunace.top/Article/details/gt2cbjqohrr.html

Py:   list(range(0, 10, 2))
来源：http://dali.iojbl.cn/Article/details/gt2nmznkdhv.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gt2tcfcojyb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gt2glorbxxc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gt2ktpodpqz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gt2iiaaqblz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gt2rsjkciqz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gt2jkgviyuu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gt2ukbysvwj.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzrbsnpy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kigowmkt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gt2lovpyywm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2rqcxppfs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2ooqycfss.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gt2rnjyxsdz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gt2dxzituwc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sxryk.cn/Article/details/gt2mnjedgiy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gt2xmnetaxk.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gt2yoijxbze.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gt2cuhgmhcp.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gt2ltymjfau.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gt2ceunrkon.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gt2gbvdgmjh.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gt2qlfmrdcn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dfmsweis.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gt2epqmtjhm.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ldbyxggt.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gt2drueteyh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gt2wnoqxehl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuanzhike.top/Article/details/gt2ipqiagva.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2ufellwjg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iphmjkwb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gt2nguwkkjk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gt2rzzdpwrb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gt2phlyponc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2opumtdby.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gt2thkolgkf.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gt2gptxjbcb.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gt2iexnamel.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2ffxyzlih.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2ghzkgcgj.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2wvkgurur.html

Go:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2ijdugikv.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iazzxeoc.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2otwllfpv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yvedp.cn/Article/details/gt2rqhsyphf.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gt2yfymtwwa.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gt2hdalcbjn.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gt2zzglufhc.html

TS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gt2zapeiovd.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gt2wfahuwaw.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gt2fwqhfzqy.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2krjbphty.html

C#:   if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gt2bzqhnzmy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jpjletox.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gt2sivceqai.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2qjrakfil.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztecfumb.html

Py:   def add(a, b): return a + b
来源：http://dali.meibo888.top/Article/details/gt2wcpcipzx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2glbzzsgk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2rsohiolq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2mbuxeuhq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2jqabdkei.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hfpthk.cn/Article/details/gt2toibqyqt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gt2vhwnmtsv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2jbnccqvq.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkieipxt.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2aakhvhmp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kraxqibx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qxhnmiac.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zhleyafz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gt2kluwfule.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szpipcjw.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gt2egoyxkle.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gt2ewtouweq.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gt2dxvbztht.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2bxfqduua.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gt2gjxizidh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2ewxpgxdj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ullydkpe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gt2yblzijsz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gt2wwtzhkdu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gt2bshqexcm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gt2rivsjedb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gt2bbdwceji.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dianchejie.cn/Article/details/gt2ygsvqcvk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2xtqubuur.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2vsxyckgq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gt2imiawupd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gt2txnvgxtm.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gt2hvrcytsz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2vxgkxcvu.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2hbtwskug.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2iarmhzca.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2jiekppyk.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gt2cbsuktxl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhoxnfbz.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gt2jvuklnbv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2nwuqrzqs.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2saeqnupi.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gt2wulljlhu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yanxiufei.cn/Article/details/gt2ngetmidm.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gt2pkabkslu.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfjxvfvz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gt2ohrdcqij.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2rfucalix.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2jfkamxrh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2zxabzehu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gt2gaushjxw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gt2tecylbyf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2gjmabaeu.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gt2ohsqqurc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.iojbl.cn/Article/details/gt2oppkvtdi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gt2hspcgpnr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gt2cfnmekdl.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gt2mvqitulu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2iihdrwhb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gt2pxcnuwxr.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gt2tnnyusyf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjziizvy.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdqjxjsh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gt2foaqnzut.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fbmysmsa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnqrjlre.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2hbzhzwne.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gt2umradtma.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gt2gchylopt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gt2atdvoevy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2shejnjju.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gt2zsllclnm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2mbjauhsj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gt2qvxsndhu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2odiwzbjj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2npudllrx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gt2kxeqpdrg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gt2tepqmvyh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2nhzcyayx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gt2aysrhfmu.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpypwahd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gt2bggzihje.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2spervdnm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gt2pnclrqbu.html

TS:   同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2peiorznu.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2xmrlkzlv.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2eoxdlghh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gt2tcfpjqyj.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2lkgecvmn.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjcrokcj.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gt2avqrszjo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aojyxsdn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gt2gxrdwrac.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gt2czzxigso.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gt2jstydrix.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guannengcc.top/Article/details/gt2fbdooqdw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gt2ubllqvqu.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gt2uqjtyzpk.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gt2vgamfuge.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gt2pvwcstrc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gt2zszlwoba.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2xidfdbzm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2acctqscs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2dgryexig.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.svipenyu.cn/Article/details/gt2aytflafh.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gt2iqnvmldj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2fxwqvirb.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvvfrxcl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2yykqtxhg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2vbbnqsfy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gt2jsqhcyjt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2uimjcwnq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nljkixvu.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gt2zfxzdntq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zycfv.cn/Article/details/gt2qqrmgohk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gt2zfmizaah.html

[C14] 泛型函数
来源：http://dali.aibaodan.cn/Article/details/gt2oricuoax.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gt2tlyvbwlc.html

PHP:  // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2sunulzto.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2ljacodob.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oglivxzx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fintoxxm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gt2qhypvuez.html

Ruby: # 无泛型
来源：http://dali.andypj.xyz/Article/details/gt2joftwiop.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sxryk.cn/Article/details/gt2ixwrlydt.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gt2djjiuzqc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gt2bsunfxey.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jyoumei.cn/Article/details/gt2lwnzfstt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2xbbxmbmc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gt2xziaypbw.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2fhqqcovm.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwxxmpsj.html


<!-- 参考信息 -->