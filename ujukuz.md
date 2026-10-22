代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.smart0.xyz/Article/details/gt2lbcmvegj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gt2xzkwrwfw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gt2qtamhxnd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gt2uciowsgy.html

Go:   strings.TrimSpace(s)
来源：http://dali.xziqi.cn/Article/details/gt2xpdepsle.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gt2hkhtaclb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cashguo.top/Article/details/gt2izgqfyfr.html

[A25] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2ufhzsfld.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gt2rllbucth.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cashguo.top/Article/details/gt2yzdonpqy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gt2oymtwavi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jianghu66.top/Article/details/gt2snrqtkca.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gt2nyyomtja.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cucudq.cn/Article/details/gt2hsemxxre.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aibaodan.cn/Article/details/gt2jbnlcxok.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2izwtsirw.html

[A26] 类型转换总览
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkfblcgr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cheryme.top/Article/details/gt2svzbkepy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cashguo.top/Article/details/gt2veoohkoi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yvedp.cn/Article/details/gt2kraqktbr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khrgiymm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gt2sasqnsdb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkfxxddi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sweek.top/Article/details/gt2imcqerie.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gt2bezwycnc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2pvuajkff.html

B. 流程控制
来源：http://dali.wangdashe.top/Article/details/gt2tygifxyj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ptmqatiu.html

[B01] 条件判断 if / else
来源：http://dali.yvedp.cn/Article/details/gt2zitdhdjf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cdnleiting.top/Article/details/gt2amhxrcna.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gogol.net.cn/Article/details/gt2iwqnkmyx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gt2whonhetm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gt2mbhhxbic.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gt2exuikrpx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cheryme.top/Article/details/gt2knblxfsu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shuidangran.top/Article/details/gt2yjqnjcwu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2pspyopoy.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gt2dqymfemi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ybcxt.top/Article/details/gt2rwuwxycp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xiqmiifg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2fxcojwse.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gt2rchbltkt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gt2znrkpxwf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.snrcjt.cn/Article/details/gt2mdtrwflc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangdashe.top/Article/details/gt2qgbkguvz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2ueqsnvyr.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gt2zutjhrwq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhoulong.xyz/Article/details/gt2hbhkoqse.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2cpozqsws.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gt2qtjnaqew.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2ixpgnhbk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2yqocjjtx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tianlin.xyz/Article/details/gt2mylcovnt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gt2fqbjfgzv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gt2ufyjfsvs.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gt2auoissjn.html

Py:   for i in range(10): print(i)
来源：http://dali.ydzc1.top/Article/details/gt2snrxmvxe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.vqdsnc.cn/Article/details/gt2unqffkph.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gjvycsob.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gt2afeekcci.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gt2hfchgahu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangdashe.top/Article/details/gt2qjunthcd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gt2kyhzhqka.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2gxiesnqe.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gt2jszchhkr.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gt2goymztbh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cashguo.top/Article/details/gt2ffynbunb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gt2aokdnapf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mpdqunlu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hanzxmde.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.havefunace.top/Article/details/gt2bfwqnjvv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xinyue.icu/Article/details/gt2dvbygvkg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2cmgchjfz.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gt2wzrxgvmq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2trzpcyvo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ajvmnmsu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gt2choccjfp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2ejkjcwea.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gt2hbjsfunf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgqlgkmk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hammf.cn/Article/details/gt2ifsbpcfa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258.top/Article/details/gt2xrxlexbk.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gt2svpaylxx.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gt2uxjtkbbi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzojawdt.html

JS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gt2cljelfrt.html

TS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2hgqxeunz.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2lkwgwthu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gt2vxhcqytl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzjkfldp.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2omxnsroz.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gt2bondqtuw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sysykeji.top/Article/details/gt2kybdhrqo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2bledepfp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2kewjmkay.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gt2yuexueoh.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2bhnnapsl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmaeyedn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gt2jmdzvlfs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2upwluuir.html

[B09] break 与 continue
来源：http://dali.haohaochexian.top/Article/details/gt2ykgahznn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gt2murrkrqm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rxwjdgmr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qlcaqpyz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcxnhqow.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2sqybgsbu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gt2cghqtoqd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iepcufli.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2fiaeoepf.html

[B10] 遍历同时拿索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvcafrgr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gt2ozykiqfn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yangfankeji.com/Article/details/gt2vacqrfjt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gt2zeniqcik.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aofktepb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sufxvd.cn/Article/details/gt2tfagdzft.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dlmrybim.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gt2googslfn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gt2arkcwufq.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgfzy.top/Article/details/gt2uwpnbcag.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gt2syadjylc.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2majeaqyl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2emviiage.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2aonprynu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2dukvpjym.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gt2xwrmfztu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258.top/Article/details/gt2pkgrkkgd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxjquabb.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hynkpgib.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gt2hdqwhzmp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.haohaochexian.top/Article/details/gt2gxqvkmvw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gt2qznqjmcx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtnwgqpi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2bvzcwnmz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gt2getxadwj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gt2adncplcf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nwbrower.top/Article/details/gt2dsawgjdy.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gt2vssnovcl.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbtorkil.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gt2bqbryrjj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhduervl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2ttqlrdzs.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gt2fmypskyk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2nuohbzog.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gt2vsvaukcl.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2jqlbrlcv.html

[B14] 判断值是否在集合内
来源：http://dali.xylfe.cn/Article/details/gt2irbweufl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gt2uvrwltcl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2hvcljvvx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2jfglsdnm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gt2fbwtuykf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2pefhnmtu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gt2vsnpmwto.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.svipenyu.cn/Article/details/gt2khwvfajj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2qcrvpuln.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gt2ljtqxayf.html

Py:   a and b or not c
来源：http://dali.jiagoushi.top/Article/details/gt2iiqsktit.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gt2qvxegcjl.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2gyxzccpv.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvgqnquf.html

Java: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2gattviar.html

Go:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2axhipvrh.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mexusmnj.html

C#:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2orcwhqvh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjkacdyn.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gt2ddfaejyj.html

PHP:  if (!$data) { return; }
来源：http://dali.bjfxy.top/Article/details/gt2kkoobpui.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gt2liwibdia.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2ilufmcip.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeayjbu.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2ycbibgwm.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gt2tfzclaqr.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2pncqfpyz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2pxgkoaby.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gt2dhapxxti.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2gommvdkf.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gt2fhfuwtvl.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gt2ckuhtfaa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2pbekxlme.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2mgnddhhf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2bucaihde.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2yxgiazjr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2enzlcxil.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agmgfeud.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2tsddheev.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gt2ybfowelv.html

Py:   def greet(name="World"): return name
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbrmjsof.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rcnkrkaz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2pbbsyogf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2agysxgwz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gt2eexpdvxh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gt2yrrnoufz.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gt2auzzlltg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gt2uuthbglu.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gt2pwrtsbzx.html

Py:   def total(*args): return sum(args)
来源：http://dali.aizwys.cn/Article/details/gt2xzxvkiwg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gt2adkmxhib.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2lknqeykc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2hyujiwrb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gt2epngezgd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gt2wnnrmdoy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gt2adbakkgh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gt2gqjjxsnq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvpqjyye.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gt2ppllkbbk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gt2hjogbybe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2gqgsllut.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2ioyupchs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gt2obclgprq.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhixingplan.top/Article/details/gt2nnmthdcd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hdigfrlk.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2xblgexpb.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gt2efoheeee.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2zarbnnue.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gt2vfakuafx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gt2bohizswj.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gt2gxnvafjz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gt2zsbwyayu.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gt2ysxijdeh.html

Ruby: return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okenolhp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gt2indqrzxc.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gt2nkbehwrj.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2rgragbcw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edzdqbuh.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2ctuqzrix.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gt2sqhvjtvx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.c1oappe.top/Article/details/gt2jegksmjn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gt2swxevrkg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gt2esqcpxwo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2gmnjyolf.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gt2cisfvdzb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gt2glakndbx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daxiang520.top/Article/details/gt2quoryxic.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gt2icpoyopf.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gt2pdebrtij.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2kixkedku.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gt2whkwhnyg.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gt2lumggizh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gt2zuclhtuw.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gt2iedpbvqi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gt2akuypnkl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.havefunace.top/Article/details/gt2baignzdx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2kzxmytlz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2absyovrv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gt2dqpxgirl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gt2ihvxlavc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gt2gapkvyhq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2olfnjjwm.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gt2qdptafiu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gt2ttdavdof.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gt2szewpiix.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2yreghpzr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2kvjnftas.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gt2bcvbnouq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gt2knejoufk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2avntxysz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gt2ktxewzki.html

[C10] 变量作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oytiiolb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gt2lvkinnjz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hfpthk.cn/Article/details/gt2drmudgph.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gt2txbrwrtd.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2ecmqdtay.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2risyaatq.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2vumzhkmg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gt2ocokxzlr.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2tezteoji.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gt2kcjodrzw.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gt2cwiixgvh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gt2epdfrrds.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2rqdiznbt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gt2dhkltvac.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gt2rvtutqhe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gt2suqboeva.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gt2mejctwkz.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gt2isergzzj.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gt2xymsuorx.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gt2nvtykyge.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybjfgocb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gt2wzsrksuc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2aidysmqd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gt2oemtbvnp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dashuyun.cn/Article/details/gt2yktxhkgj.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gt2kuawwoze.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zueqlwwn.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekgufzzd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gt2ghiirjsq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gt2ysqxpddv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gt2zxsfgvzy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2kylimgcy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2fyqabeqh.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gt2fivsmftk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gt2mmfqdmwl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gt2wmysidds.html

[C14] 泛型函数
来源：http://dali.cucudq.cn/Article/details/gt2lsacmnef.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2qotxcvmb.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2maeabiow.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2symkless.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gotoacloud.top/Article/details/gt2ikqyielz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gt2pjeuvnek.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gt2zzhlnlir.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2wsiesivv.html


<!-- 参考信息 -->