代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.iojbl.cn/Article/details/gtskpzbcia.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtggryjpff.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gtywzqoyto.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gttagfzzhe.html

Go:   strings.TrimSpace(s)
来源：http://dali.zdqjudy.top/Article/details/gtixikaxzf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.iojbl.cn/Article/details/gtlyuvktuz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtacjzfjmb.html

[A25] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtpxngxfpg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gzhubu.top/Article/details/gtwwzhzcbu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jianghu66.top/Article/details/gtmsphpsdh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gthqnbangd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtckepxzeo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gthzoqtmny.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gtqnuuwzcv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.smart0.xyz/Article/details/gtxjkabzgq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtnvicarpz.html

[A26] 类型转换总览
来源：http://dali.zhengqikj.top/Article/details/gtgbwbfxgz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgfzy.top/Article/details/gtrqmsbine.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrozhfue.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.birdmap.top/Article/details/gtbpuxrrvl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yangfankeji.com/Article/details/gtcbrqkufl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pycfn.com/Article/details/gtlboadfrb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuanzx.com/Article/details/gtthatznce.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gtiylgacmz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtwowcgfmh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtywaiqiln.html

B. 流程控制
来源：http://dali.shuidangran.top/Article/details/gtvmqnolkz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxcnwbaim.html

[B01] 条件判断 if / else
来源：http://dali.jiagoushi.top/Article/details/gtackbogpv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtmffsudaa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gtrqlcpvel.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtqellxqow.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gttkprnuok.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpboqekm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gtgyhgzpue.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fengsongda.top/Article/details/gtvikvhtnj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwfurcex.html

[B02] 多分支 else if / elif
来源：http://dali.hongshengwenyu.top/Article/details/gtoxpmrfkm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hfpthk.cn/Article/details/gtnrbromed.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gtjxhixrgz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtljeexblc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gttdcipcgs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtxoscdzmk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.316326.xyz/Article/details/gtykxpbxly.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.bjfxy.top/Article/details/gtaktofndg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtznykynii.html

[B03] switch / match / case
来源：http://dali.sufxvd.cn/Article/details/gtkvmwbbsn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gtrpbyxwhe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtiwqgyxxe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtxnxqcpwf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwatvkqrl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtdkjynltg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gtczbketfh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gttpdtoqde.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtglmvbwau.html

[B04] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtpttgziim.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gthepppnvj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gticdwsweu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtlojswuzt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtveovtocp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yueranfly.top/Article/details/gtyevyrrie.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xziqi.cn/Article/details/gtfbfeehwu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gtmwciuybl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtenstqira.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtpfyfkevz.html

Py:   for item in arr: print(item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteepmnibj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbcmcrzjj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtpumodvdi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtdocdejlj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shuidangran.top/Article/details/gtogjybvly.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.svipenyu.cn/Article/details/gtblhrnqnf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangdashe.top/Article/details/gtnmfjntib.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.havefunace.top/Article/details/gtlljdisoo.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gtejinshkz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gtjgnrqwgy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtppheldqz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtshiegeet.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gttmoafefp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.birdmap.top/Article/details/gtipehjbab.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jiagoushi.top/Article/details/gtznvgndtz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gtxoujxtfk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jianghu66.top/Article/details/gtkhyufdtr.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gtybdftdsd.html

Py:   while i < 10: i += 1
来源：http://dali.dashuyun.cn/Article/details/gtirrgkfuo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gtckmhhlab.html

JS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtczwkoyja.html

TS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtugjdgkbb.html

Java: while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtgzpcuruz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gtsjxxhrlj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sufxvd.cn/Article/details/gtntubayao.html

C#:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtulqqqcfu.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gtrqitwoon.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guannengcc.top/Article/details/gtdkvjzbnw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtzpzrmlql.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtareremlc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtzegaaiel.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtjpysoqzx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gttgqiilez.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258888.top/Article/details/gtizjwwkwi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtnahtamds.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gtgtjmkzks.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtijoegpix.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gteoivrfvx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtuyjrhmeq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtqpcgusne.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtalslfzbc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtqrerquhn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtqckveexs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtmoswpgur.html

[B10] 遍历同时拿索引
来源：http://dali.kuanghao11.cn/Article/details/gtcpguwwwe.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gtkivujozx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gtoclvzaqb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtdgchccla.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtatwjfrpm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gtvmzybxxs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangshuangyany.cn/Article/details/gtqmvmperi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gthsorrhdz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnagwxpk.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhnziqor.html

Py:   list(range(0, 10, 2))
来源：http://dali.jiagoushi.top/Article/details/gtculvssel.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtiiyajdjr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gturckawvt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtowkpypua.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtxuqzsfan.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmnzwjrc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtgbmuwhud.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gtkkgeercn.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtoovycxwf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.birdmap.top/Article/details/gthyjjzxxb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.haohaochexian.top/Article/details/gtfdsarnpn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtevotohvn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyffjdtms.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtpsjwpaqu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtusxichuk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gtxjxthapr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxriywfb.html

[B13] 判断是否为数字
来源：http://dali.shzxlz.cn/Article/details/gtcvgehpgv.html

Py:   isinstance(x, (int, float))
来源：http://dali.redwolf501.top/Article/details/gtjurbxdcn.html

PHP:  is_numeric($x)
来源：http://dali.daria6918.cn/Article/details/gtjqfiwelj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtwkxsueat.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtshkvvhwt.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gtfqwqrgwq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gtbruqiewl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtmvnakvci.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gtwyddosgh.html

[B14] 判断值是否在集合内
来源：http://dali.hfpthk.cn/Article/details/gtuxvscddl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gtpqlpjyjh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gtrozrlhli.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtkgsnzffy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzpishjzk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtlfpjeuss.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gtiyfdoynh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtbtwzjsex.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtssghxiig.html

[B15] 布尔运算与取反
来源：http://dali.vqdsnc.cn/Article/details/gtptwggxgd.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gtwwpmxozj.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqwkxqyf.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtobybzrqd.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtdsjsxqlh.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtuafguqyt.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtlwodowam.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtetdhrcap.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtxruerdzv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtppnzmcxr.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gteqzfzpzt.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gtycrvfqxj.html

JS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtmcveyoux.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtyxgewyff.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtjcauebem.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtoxkzdglm.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtnbljwppr.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtrwfimeuv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthehkxurd.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtlhjewpfm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtubndtvqy.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtbnycibrd.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtdnakqpmb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtiulgyleg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtdzisnbru.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtzfiigkjq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtidicprkk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtweqidrir.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtbmjazuac.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtscaqtptp.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gtsdkyyatm.html

Py:   def greet(name="World"): return name
来源：http://dali.feifeiyinyue.top/Article/details/gtjvhydtuo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtoxdfkgvl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtaqsqxzey.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtcsluvdzs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtdfxkbpkp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtuvktusig.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gtwvurohbb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtwyjvaxxt.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtflctbkag.html

Py:   def total(*args): return sum(args)
来源：http://dali.sweek.top/Article/details/gtrryumhrv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtsgrurgqx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdgzabohf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtzlruslbd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtzurzfptr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcomxhffe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtwrczxnkc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gtnkcdvlhn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtpvcgyijk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cashguo.top/Article/details/gtgddesqsm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gteueotvbw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtymppqgdn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtuhzzttvj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigfzy.top/Article/details/gtdwlrohvy.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gtxgqyhptw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtouauotgh.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtaawlcyky.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtrutacrbd.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtdxnspdhk.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqztejyd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gtlaxxfrnf.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyeniaqt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gtcocwsefo.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtfhczglpn.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtlblgbckt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtvbgjzypn.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gtpsrkldox.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmeddeluf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtuuxrmdeh.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtnkgtmzyq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtyjuntlxa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gthqgzsaml.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtxpjsknwn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gttfusvvfx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gthwfdrosy.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtldpgvjtk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtzfpdhoaw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtkaeeuraa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtojhezpig.html

TS:   arr.map(String)
来源：http://dali.ybcxt.top/Article/details/gtltdzzrbr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdhihhuz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtzzodvsri.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gtagkdvrof.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gtloistoef.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gtwbgrxyln.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtinpbsqay.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gtgpthucmd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbtrcyhux.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtszdkqvcl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gtmlfxotnh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gtboycnhcf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gtwrphzxfv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfwsktqez.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gtshvwnmjc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtiskavoye.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtrbdyqgbw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtptgrddcy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtqrdbfvsj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hammf.cn/Article/details/gtlyiuwaoe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtzcihwlte.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtrdvirvwp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gteonnxodt.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtxjbptwyc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnrawfsx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gtkzfrtqdh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqkpljnj.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtwwasjmwb.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtdwbaigup.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtymrlklki.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gtassgawmc.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtmyomnbfe.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gtsmxycrdm.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtumnoacmw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gttkubteja.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtlsqzwcyf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gthbkeuyjs.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtfwqxfxce.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdjdwgvy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gtvrtjzgty.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gtavwpjyrp.html

[C12] 立即执行函数 IIFE
来源：http://dali.hfpthk.cn/Article/details/gtspiyicbr.html

Py:   (lambda: print("run"))()
来源：http://dali.vqdsnc.cn/Article/details/gttakxazdi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gtamjtzqnm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtfadhysgq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtreqtcxdx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtecctkgeq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtuvdpogxd.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiscwotq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbqmcjiy.html

[C13] 类型声明 / 类型注解
来源：http://dali.aizwys.cn/Article/details/gtzdtgrafx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtprjgjfjb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtwltelsgc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtpfuinmnd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtabmusord.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtetusgxqj.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gtenikhlnj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gtlklzhtan.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.quarkkingdee.top/Article/details/gthlsszbej.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gtuilexzih.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gteaeetllb.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtntowtmiq.html

JS:   // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtqnpoubln.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtusrjddlu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gtflbilbne.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gtugbtiltx.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtohdiqfrr.html


<!-- 参考信息 -->