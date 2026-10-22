代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hammf.cn/Article/details/gtzlukhfuq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yanxiufei.cn/Article/details/gtesstxkpy.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gtdiwczjib.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.haohaochexian.top/Article/details/gtdshhyyef.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.redwolf501.top/Article/details/gtiuwhqjrw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gthqfuvlif.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gtzpamwxhy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxkmfmsf.html

Go:   strings.TrimSpace(s)
来源：http://dali.xinyue.icu/Article/details/gtylhrxbmc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zdqjudy.top/Article/details/gtfsrstvkr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtwfjjeeug.html

[A25] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtlcdojmqc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guannengcc.top/Article/details/gtzzxnbksl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtsusfizuy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shuidangran.top/Article/details/gtgocjyvst.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtlnmnzodp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aibaodan.cn/Article/details/gtsxqyefdn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gtwcfatzqz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuxming.cn/Article/details/gtwaijmzrp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gtrlcwvysf.html

[A26] 类型转换总览
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuhmqmsg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.mhx1999.top/Article/details/gtklbuvclt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sysykeji.top/Article/details/gtqtumevcm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yonumen.top/Article/details/gtftkgfmkt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenlongwang.top/Article/details/gthzufbotn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gtwffdumqb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ppjwa.cn/Article/details/gtpolwnpyu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jqgfzy.top/Article/details/gtmjocwhsa.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gthztxoicr.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbjsawsaf.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtagelyvio.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmomuytrw.html

[B01] 条件判断 if / else
来源：http://dali.daria6918.cn/Article/details/gtckfcswnv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.birdmap.top/Article/details/gtijmufrul.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hysaishi.cn/Article/details/gtbkgxceky.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtdrxhqxim.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtxfakgagg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtxiozqufr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gtkkoecnvd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guannengcc.top/Article/details/gtizmfocei.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtophqyxgi.html

[B02] 多分支 else if / elif
来源：http://dali.daxiang520.top/Article/details/gtqkvjgbfb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtknbcnaxj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhijiandao.cn/Article/details/gtwukznqpp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtyipyeqxp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gteodspire.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtlmxendvr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.vqdsnc.cn/Article/details/gtnyerwrxq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ehwqpu.com/Article/details/gtmcezwpgs.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtyrylutcd.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtcitegbxr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hongshengwenyu.top/Article/details/gtgjwvdrrd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtypyeeall.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnxdyusqt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtjdlinffy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtfxnbetgn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gtvqnphycw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cqqwz.cn/Article/details/gthhqxnxbd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gtmpfqklev.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtetumlyng.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gtnrviioiq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtvcylyccp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gtiouawmmv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gtgrhmhisd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xinyue.icu/Article/details/gtupiiazhi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccwkwqed.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gtxzvowdef.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cucudq.cn/Article/details/gtdrwkigms.html

[B05] 遍历数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtrfjsdoyv.html

Py:   for item in arr: print(item)
来源：http://dali.zhixingplan.top/Article/details/gthkpzaueo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yonumen.top/Article/details/gtsivqepqe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtoyvzeefj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtqtfhtqtq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenzaomai.com/Article/details/gtlmvapdxu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gotoacloud.top/Article/details/gtkkqwrfac.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yongpay.top/Article/details/gtirlndsrt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ppjwa.cn/Article/details/gtxsyhmggh.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigufen.top/Article/details/gtxeagqgdi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhiwuduotai.top/Article/details/gtazwjicgu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gtmdkfbbzs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtjpxhbuqe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtonarsghj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xylfe.cn/Article/details/gtzroqbdtu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zycfv.cn/Article/details/gtpipfamhd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nwbrower.top/Article/details/gtripvpikw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhengqikj.top/Article/details/gticffwpjn.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtgiqvtfvx.html

Py:   while i < 10: i += 1
来源：http://dali.hnqzz.top/Article/details/gtldgtjyyl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hammf.cn/Article/details/gtywxlickp.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtvqqykzeo.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtcrtpgmsg.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtafpxxlzp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.bjfxy.top/Article/details/gtbcfpckjn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhixingplan.top/Article/details/gtecjfwfdk.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtovizftth.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gtpwghkrqa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gthozpvwbs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gterrsvouc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtgnslsvld.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtvzjhcqiz.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gttbpfwzlb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtjsgajtek.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daria6918.cn/Article/details/gtxpukxdip.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtafhqcyvr.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gthspxugwb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gtcxdwrlun.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtdyvedcbj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtyzvdhtez.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtissxlsvm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gthbsrrcke.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtjrkywcpf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gtuoaubbwp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtvefxagjf.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gtilapkdzg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtajvuqkpr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gtljedwpar.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtojdufyom.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtgtvtckyd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gtqixhgjkf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtvmseunjb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ehwqpu.com/Article/details/gtruxzcweo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtigaebgku.html

[B11] 生成数字序列 / 区间
来源：http://dali.snrcjt.cn/Article/details/gtiabnkohi.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gtbmgefqla.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gtoolpicil.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtlapasozu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtxaqfeeyi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gtmwdffbxm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gthpewhjye.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtndytjtfn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmortojkv.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gthxljtqza.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gteimeuifz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gtmnzcwvfe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtoitgpfgv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtmjgwpjyn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtmrqfqxdi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gtbbygsvky.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gtrfaxffip.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gttcruizxe.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gtyqicpgzh.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gtbflvhcmr.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtztijjddt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtlcchfpwk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtfngulmlu.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjksryuc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gtppqqorqx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtiujwcrgb.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gtyoqslnkw.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gthctcolnw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxinkj.top/Article/details/gtsrzgsvbh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrwtpgdl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtwvohbppg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtbvsjqooz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gtkymjzqwf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yangfankeji.com/Article/details/gtbzydauxc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gtniostfqt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtvlekyrxe.html

[B15] 布尔运算与取反
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlswdrdtk.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbxfxgld.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtrezesnmh.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtpmysgzte.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnewhvci.html

Java: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtvmoeipxs.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtotwqzbdd.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtziwvtpzo.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtcphwmidw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtuxzbeqpf.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gtssniphsm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtrsbnfaoa.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtkrlhgmpr.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtnyipdstd.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtjgcbtdav.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gtcrfaiskg.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gtstdfiykr.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtncuuvahs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtmjfdferg.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtjjettmdk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfbdclvcj.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtgxheqkii.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gteowqgvrs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtcpfnntqq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtwgnlximc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtppjoevhv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtcputbhcj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gtqfzbpdcd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gtndlasrid.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtitqoktyd.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gtpitkrcev.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gtgtpskuql.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtcxwualjc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtiiqyqosn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtmgufutma.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtepkzmnvz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tanke756.top/Article/details/gtfiaoyzfe.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gtvxpolyww.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtwbbttwcg.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gteszllwze.html

Py:   def total(*args): return sum(args)
来源：http://dali.tian-w.cn/Article/details/gtvzyhxpxo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gtgfcqlkgx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtstqsxgsq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtjfkeclbh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gtqmemzlte.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gtecferryp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeezpwhx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gtyqmifvmz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtsrfzuyjd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gtijmxxxig.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtgoengzlb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtejhdhiii.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gtlhcqsgxl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gtgqwnzthy.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gtzluqnvuy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcdgdgest.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtzaoxbmqg.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtvtestocw.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtviogzbjo.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gtehivffhv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtszyvsxoe.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtshxoebfc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gtciqpzrkl.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtrmjezkls.html

Ruby: return a, b
来源：http://dali.316326.xyz/Article/details/gtrscmrkut.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtnqcmpwxl.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gtrzxflatl.html

Py:   square = lambda x: x * x
来源：http://dali.cashguo.top/Article/details/gtidaonqfd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtvdmcebfe.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtichactih.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gtgtarzqjo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gtzhkhukgw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gttjecfskv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtpbisyzbx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtqdgrmjtu.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gtimbcoaxa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtfxiqnsno.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtmdmnahjt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gtxnwvlxnu.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gtlpddpegi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zycfv.cn/Article/details/gttsisriks.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sysykeji.top/Article/details/gtljcwjbkp.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtjnetjvok.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtkbbkjmox.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtsdnmlqim.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gzhubu.top/Article/details/gtpoapsjpm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gtoeeubqzf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtrznrqtdr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwgbcpmbo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gtivtalveq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtovtyycxy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gtojtspxxy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmxxauml.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtuvnpsvuv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtlckedeja.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtqygvyslc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtkfinkihc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtqogobbeh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gtmaalnore.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tianlin.xyz/Article/details/gtykaoimky.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtgdkcgeek.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtfwinoudl.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtmqzfphmk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjftdmsb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gtrqtbqpid.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtqauduete.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrddugef.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtfeytaxbc.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtyncmmycp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtqpdrtsbv.html

C#:   块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gttzuoguss.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtitqkkmtu.html

Py:   from module import func
来源：http://dali.xziqi.cn/Article/details/gtgqktnnzp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtrskkzipm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gtikfmusnm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtuhufyajd.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtpoakbjpa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gtpvqvzpks.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gtxfeekide.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gtfopwczmc.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gtovqbvfgi.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtyswfwzgi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtwzrwzhxk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtozbrnore.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtddpeykro.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gtugxvbfuw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gthircvjce.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtrzvuuyll.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtcawbiqhj.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtgzuuuwxy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtlqwrzufu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gttgwapoyo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gtweothryz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtsvjfczbv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtcqlpciro.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gtgmcgniko.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtlyymaodj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gttrhtawoq.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gtdybzcroi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtrvbegdsp.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtcivtmqrq.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtesydyzyv.html


<!-- 参考信息 -->