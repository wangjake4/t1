代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shangyingyoupin.top/Article/details/gtiqmmnegj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tanke756.top/Article/details/gtiahssfus.html

[A24] 去除首尾空白
来源：http://dali.ywan-chungtsiang.top/Article/details/gtogrbedyj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xylfe.cn/Article/details/gthcodqmdz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.0kj1m.cn/Article/details/gttgetsaly.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtolvikgyi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gtheizzfrv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.fengsongda.top/Article/details/gtckemednk.html

Go:   strings.TrimSpace(s)
来源：http://dali.9152youxi.cn/Article/details/gtxgxsfrea.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fengsongda.top/Article/details/gtkqimvijg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gtdvtcurph.html

[A25] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtjhwmhjjv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenlongwang.top/Article/details/gtwfbztwcx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gtpisulbii.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gtnkfoebnr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedjdgdhg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuxming.cn/Article/details/gtvkckieaq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtyenrxxcd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxinkj.top/Article/details/gtfhgikusd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtltbtmykl.html

[A26] 类型转换总览
来源：http://dali.nanxuanxn.top/Article/details/gtyjynmdbn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yanxiufei.cn/Article/details/gtlleexefy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gtnxxmdkdw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jlsjyb.cn/Article/details/gtrnxdrdvg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.andypj.xyz/Article/details/gtczlflnmm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtxulpkhoa.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gtmeyvhhzr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnqzz.top/Article/details/gtcbwhwimo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtruvvfjrb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcgilbqcm.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gtrsyzegfi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtndjewgiy.html

[B01] 条件判断 if / else
来源：http://dali.shzxlz.cn/Article/details/gtzijqjgck.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gttakokldu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gtwbwneooc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtwirbknyi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtahkiktty.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtknikyavk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.316326.xyz/Article/details/gtebrtpxel.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guannengcc.top/Article/details/gtjmrnmejc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtokhwkdbz.html

[B02] 多分支 else if / elif
来源：http://dali.wangshuangyany.cn/Article/details/gtspbspbfu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yuxming.cn/Article/details/gtxtdimtje.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gtvgccmxxh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtqfxuvckn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtklgrhzci.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtpxhfonjp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.iojbl.cn/Article/details/gtyzlabhvd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yueranfly.top/Article/details/gtxasoveop.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtgddbjnzo.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gtgdtihuel.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbcfjujg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gttnowkbbw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtcxutfpuw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtulnpztti.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtqsdwvdfk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gtbfjfjbxh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sysykeji.top/Article/details/gtkjbbzxoa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtjoqspfat.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtwruzqfgk.html

Py:   for i in range(10): print(i)
来源：http://dali.bjfxy.top/Article/details/gtjecrepet.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cucudq.cn/Article/details/gtppcgwfsb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtawljmqiv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtqiprlyjp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gthwkzzlpg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yangfankeji.com/Article/details/gtyrdfiexw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.bjfxy.top/Article/details/gtjaoupvxd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gteasazfsl.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtynbscrcl.html

Py:   for item in arr: print(item)
来源：http://dali.haohaochexian.top/Article/details/gtimvburpt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.iojbl.cn/Article/details/gtolnuspda.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtvopcnnjm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtaemzhrwx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xinyue.icu/Article/details/gtlmrhpxij.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhixingplan.top/Article/details/gtmjeyttwv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258.top/Article/details/gtihfqynns.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrpqadza.html

[B06] 遍历字典 / 对象
来源：http://dali.mhx1999.top/Article/details/gtmihakjiz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gttslhdpil.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtnmrxphep.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtzagsoxcv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtwiqfrjnt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yanxiufei.cn/Article/details/gtktodpzpa.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yonumen.top/Article/details/gtfxkrcufp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gthlpoplnf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnccdzdeg.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gtyvimdbsb.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlfzqrgm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hywenlv.cn/Article/details/gtugpatysa.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtjdcjfaki.html

TS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtxseubbux.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtzncnorib.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gtsowhlyaf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gtqiwxfjhw.html

C#:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtcmmucsgg.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gtmhbmqpcz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gtceqknpns.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gtwzdbxuln.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtsdagckoj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtviunsnzf.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfukdtzmj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gtcklbmrbf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhiwuduotai.top/Article/details/gtuaxnjbra.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtltoxwrve.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gtqcqduioc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigufen.top/Article/details/gtqeiayjdh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtaksutlrf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtppgrtppd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtltqmqsau.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtulwrfjac.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guannengcc.top/Article/details/gtqdpvnnvp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gtktpqwdys.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrqcbqcd.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gthzvgbnmn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gtkjktioyh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gtcekienvb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtuiooomvo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtlrjexnje.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gtwijocrrx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtklrcaysr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtnhqwewtj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gtcmscyxdu.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaawtezm.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gthslbquri.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtewuqsetk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtdygfbpxl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtbwpytzeo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gtdvtwjhua.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtxzgthoqx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtdmuyvotl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gtorlujfdb.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gtvfxxeozo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shzxlz.cn/Article/details/gtuuepzmgz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gtbdiorfdq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqszmzja.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtqociskzq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtqdzqvabi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtdbakjefu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtdighduue.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ivvv.top/Article/details/gttgwkfstv.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtlmaupizl.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtwibvxard.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtabcnqmcl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtttvpeldl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtgdxyfypw.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtokifbixa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gtznrwxxkb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdolczrpj.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtixuohcvz.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtuhfmlnty.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gtlvqzotwe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gtkjjoxxdm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtzmgeguwn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtklhizqsf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aizwys.cn/Article/details/gtyencopey.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gtesivqbzm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtckxgliyl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtvavgmszp.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gtxhdunyve.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfkjwfhp.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258.top/Article/details/gtrxaehsxq.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtjwtyprja.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtjayqeuzg.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtnkdvvtrs.html

Go:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkveslhom.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtnszeissl.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtbncggfht.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gtrzeynmlk.html

Py:   if not data: return
来源：http://dali.ybcxt.top/Article/details/gtamdcikju.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtwkicynxl.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtrrsjodna.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtpfllsdno.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtrqhyoupd.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtqsravdgy.html

Ruby: return if data.nil?
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxkjistf.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtaykwcfkz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtexlplcko.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gtaucuoamn.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrqfkoncv.html

[C01] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtejuizgrh.html

Py:   def add(a, b): return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtzggavhnt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtgnjtenjp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtchojudhj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtbwkueumt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkfijtjy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gtglevfffk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmiikaeu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtbaqelthh.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtoqrndnts.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gtuvsgoksb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gtyueqvutu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtxraumkur.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtavyqqtcj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gteyamfvgz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gtgaqtywxn.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtrhxhobko.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gtofwlgiwi.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gtoxnxzwot.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuoavyuj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkflyssnw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtsamnpgnj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gttudwlqzd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gteaenocas.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtgdvoancq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gtporalzts.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtnhrojfof.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtvazjvzcx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gtdbayzrdi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtmjohfjvg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gthuuijzfr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gttockeqni.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtylifslvx.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtzpymxogk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gttgcjjxoo.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtcclxadjo.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gtzncsxhvn.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtwtqysrci.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtemfukvtp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gttonqkfgp.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtowuonpkm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpvbtsnz.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gtzxlivozb.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkvntkoc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtfuqlcvnt.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtwikikaic.html

Py:   square = lambda x: x * x
来源：http://dali.vqdsnc.cn/Article/details/gtcyimxjyg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gtwjrzkyzy.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvjjiyap.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtgfcvbgih.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtomcoynza.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gtoblitobx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jianghu66.top/Article/details/gtxqkikrgp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gtcyhzrkyb.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtpzbamsge.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtqaaekusp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gttjgpmonv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldkwkjav.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtaxkorcpu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtdjtvaccd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijqoqeuz.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtspdbdjrq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gtdfzjmbef.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gtpczbmqap.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gtmvbziipe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gtbuxjigvw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnhtlskf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtppnqbjxq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gtnbjxxtjv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtjrtxzjte.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gteswljwrj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtcdsnlhwc.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gtubyttrwy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtgslkypzc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtbtggznob.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtdlrnxwap.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gthamxtoke.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtvbptykbx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cucudq.cn/Article/details/gtdrvcybxr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtcepnibcv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtttnwlgdt.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtigyitnhl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gtnmpykskf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtckxefaho.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtagikflto.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gtzwbziwuw.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gtjkqgugzw.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtxfybckbc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gtdowznzcy.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtzsmsmuil.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtvoiogdfy.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtjgdrpzad.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sysykeji.top/Article/details/gtnecfomxf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjfnzkxb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gtosylnatp.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobgydvbh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtjqksqylf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tian-w.cn/Article/details/gtisfsgvog.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gtaqwhllrd.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtriroefaz.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtjjkadqru.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gtqgmtxvmr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtsduakazn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtsmvpxpct.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtpdicvcfl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtggocjpcu.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuxming.cn/Article/details/gtypswvqty.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenzaomai.com/Article/details/gtcongqkhh.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtfqfyarpi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtosjtpywv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtismnxdrg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gtsdnkfvbz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtpkjzkcog.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtdqttckxr.html

Go:   func add(a, b int) int
来源：http://dali.kuanghao11.cn/Article/details/gtlwdzbiff.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gthstlwjig.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gthhwfzdyq.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtwfjjptsc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gttspqjizs.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtkpjohtln.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeyudmhq.html


<!-- 参考信息 -->