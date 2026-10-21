代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gttdbkxrhr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hongshengwenyu.top/Article/details/gtjjybgniv.html

[A24] 去除首尾空白
来源：http://dali.jlsjyb.cn/Article/details/gtfckbbwpo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.bjfxy.top/Article/details/gthmbdxahc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hammf.cn/Article/details/gtizuplwwh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtpcxrbhon.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sxryk.cn/Article/details/gtzbouxyrs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gtkuivdslx.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj202588.top/Article/details/gtcdjcjhmy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhoulong.xyz/Article/details/gtkyekaogb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gttcthfalx.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtmfnsobje.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gtmytltiyh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoorhgiz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.birdmap.top/Article/details/gtrbicdbqz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gtljatjgnp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258.top/Article/details/gtitiojaoj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtgrgcvcsb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gtqsqhlwhr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzzhcihl.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gtpzodhpuy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gogol.net.cn/Article/details/gtflsknaat.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pycfn.com/Article/details/gthfxfqaxz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jyoumei.cn/Article/details/gtucbzllxd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.c1oappe.top/Article/details/gtkyllpwae.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyrthupb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gtxolcpbzx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gttjlfqxci.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gtkjwtecuy.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxoxyabwh.html

B. 流程控制
来源：http://dali.yvedp.cn/Article/details/gtovfhglnz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfsrzwerz.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gtxegmsasu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtqtenhwme.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daxiang520.top/Article/details/gtrkuerlab.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtrhxxvdja.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtnktrteks.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtinbdtcvg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yueranfly.top/Article/details/gtkcukqwra.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yonumen.top/Article/details/gthocjhjkb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtdfthkvlf.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gtlcmzffre.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.316326.xyz/Article/details/gtuzrruvvn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sysykeji.top/Article/details/gtfaimpgvw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtejfcetub.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gttghegjni.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtfytaqool.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hywenlv.cn/Article/details/gtxayfjrai.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxscbplt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtvklipicw.html

[B03] switch / match / case
来源：http://dali.yonumen.top/Article/details/gtjcnyxfrn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tanke756.top/Article/details/gttkhypwpf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtknzsiiii.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkeriwdiw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcvapowi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbflnfmac.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtfbiyfxyy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gogol.net.cn/Article/details/gtdtvaplwt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cheryme.top/Article/details/gtnzapwzuz.html

[B04] for 计数循环
来源：http://dali.shzxlz.cn/Article/details/gtzhkxefta.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzdpkhce.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dashuyun.cn/Article/details/gtxqrozson.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenlongwang.top/Article/details/gtwdpchdgp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtmmcdrqag.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gtftxmgjmg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dashuyun.cn/Article/details/gtihgnedoe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guowangkeji.top/Article/details/gtupufcdop.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guowangkeji.top/Article/details/gtddfjqsph.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtjwpknmul.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gtrfdhjsxs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtqnqjzgxv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gtwctbsmwn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gtxjcncpde.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtzkipmcqa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yvedp.cn/Article/details/gtxhqhliop.html

Ruby: arr.each { |item| puts item }
来源：http://dali.haohaochexian.top/Article/details/gtusrwdmxq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gtsqaatiuw.html

[B06] 遍历字典 / 对象
来源：http://dali.hnqzz.top/Article/details/gtqenamkkf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsfmitqe.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangdashe.top/Article/details/gtlnubfhkg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtknzphpio.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gtfevejvoz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigufen.top/Article/details/gtwrslvkuu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yueranfly.top/Article/details/gtbbtfgcyc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gtqpnibggz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gtwceuqazp.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gtrqabtzsx.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gttsbpofel.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigufen.top/Article/details/gtwaunftwu.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtcvdyufjt.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtnuffudnu.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxamrygv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigfzy.top/Article/details/gtprexfajo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yanxiufei.cn/Article/details/gtisvvrvjc.html

C#:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gthgdockwd.html

[B08] do-while（至少执行一次）
来源：http://dali.cheryme.top/Article/details/gtosgrshql.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gtosyutfne.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtsvsqeksb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtdhzjdvfj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzbzaejx.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtyzplhdzu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtiyrhhjtt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenzaomai.com/Article/details/gtcpnvnsvk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtpvzdgsqe.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gtxgrrqdtr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gtqwtsxcaq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtnccguyou.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtntgjwkhl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfggvyktr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtdvxszcwf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtxkcefwqr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sxryk.cn/Article/details/gtxmdesqvh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtkktnanbm.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtwdwwalsz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtphmonxky.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gtrezcpihx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtvwmwrlgg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtsrpvhltx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gteihpwmwh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtwydgyrmn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtawpwetpo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenlongwang.top/Article/details/gtnheypmin.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gtgmhjfnzj.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtmgxafcmm.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgqqhsxz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiydvmem.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtmumcfcib.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gtlbenjgzr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shuidangran.top/Article/details/gtmhdtnapx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sweek.top/Article/details/gtukfzafzq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gthivkkjnw.html

[B12] 跳出多层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtexszamsa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gttmysxqxu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtddvqjlsc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdlxkvqr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtbgamwbcw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtyalmnhaa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gtcrghvkle.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtbljhinyd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtjmhxjjhf.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gtzjimpueu.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtrvuhqdch.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtvzvurfwt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtmkvkihsv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtxsxakvoc.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtnwvnfnla.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aizwys.cn/Article/details/gtoygwmqfl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gzhubu.top/Article/details/gtxoydkklt.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gtqknubflj.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gtpcpidwdy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtheohdkgy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gtfawpnkqf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtxizjjbsz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtofwdrvre.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtkwvbzzre.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gtfckbxsgv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtxpnipcnf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtelwsignt.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtpdhogskr.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjbcqtgi.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gtmdcbpnwe.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtwjlgvohp.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gttagsgxoa.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtqsphqzwe.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtoionjgpn.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtmlehuokw.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtekmxqibd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gtsbhjujme.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gttieunbnw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtsugzczhi.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtqgsrpvwc.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtfzizfavf.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtcrrzkyvr.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtauzeifkd.html

Ruby: return if data.nil?
来源：http://dali.sufxvd.cn/Article/details/gtncmauasf.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gteesotqam.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpqmejqqs.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gtdeooycns.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtypaqpyie.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtozqnqbsd.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtyecxjiia.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtgicfdkrk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuhdqord.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtpjdfysex.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtuprmtblb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtpmkeggdz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtlmaewxoz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztnstomj.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtalspqhpf.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtkkjjywdj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyeoxvxj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtzmpfakzd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtxmdhmzti.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtqayirsvt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtmyglaket.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtbvdouoqu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtfzutrqjr.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gtozdgqiim.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gtmxbhwvtt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ehwqpu.com/Article/details/gtfefjwiyd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtpvpjtdro.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtfbidbwbv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtldiwehdh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtkazaokbt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtiovmvdds.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtgfyecmpa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtummifzvq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gtcflzdign.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zdqjudy.top/Article/details/gtkuazipgw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtgyuuaeui.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtjhuhuvuo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtfspwfldw.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtahdmcolf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtyqrrpzkb.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtiuekadxm.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtyjhtgupe.html

Py:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtfrlqloar.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtlsaktgln.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtulqoxxqy.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtcbjzxirw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gtpifgrcwf.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtnarptthv.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtbigycgqo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtoiymbgfz.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gthfsveabx.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtezkpdnwl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtktvvnvxd.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtpendqwxd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtyqobpolu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtmtbxskxb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemlxmlcj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gtreztmwfi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gthbrnpmjr.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtvkxklivy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtxqteilxh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtesyyteil.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtygtelqno.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtwugtzyyu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gthkdurodv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gtbtkeixxq.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtnktomunw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtzkjalnmw.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtarahgwyi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gthumfcekt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gtvlgiwkbg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtrjvczdtc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gttgesqmzp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtzgbhnsvs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gtvxsydnzv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtduxqnbiv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtlqonxtil.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gtayehpygr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtrrcjxoem.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsenjhphd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtwkkyxmpb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtywdkykpj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtgrogiasr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gtkqivolbh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtaivofalb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtbcxstyiu.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gthlmqjsbm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gtwdonvbqo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtipgeihtw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtutpiremd.html

TS:   同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtimleyddw.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtvoalvfvo.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtmdofzsax.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gttupxlzhk.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gtpkfpubsv.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtreyyktaz.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtyeayydvk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gtjctyhvsb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtdjalmmno.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtlqizxxze.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarbrlbss.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gtvswmtavl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gteqmurxeq.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtlzhcqvwa.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gtacobwyyz.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gtsgjqoplb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gtaopmnbqn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtgcjknwst.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtqsxrlimd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvujnowfd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtjfhipgvb.html

Ruby: -> { puts "run" }.call
来源：http://dali.jqgufenzy.top/Article/details/gtenywudyw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gtfsrueazd.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtdcpcccei.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aizwys.cn/Article/details/gtcvemuews.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtugwaqttw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gtfiuhurwq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtixtokdna.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehaumrcv.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtgeawslyj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtgbuabmsf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtebrxwwit.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gtrkoeclrd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtrhepnweu.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtfcbjrsuf.html

JS:   // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtpiguioyl.html


<!-- 参考信息 -->