代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.quarkkingdee.top/Article/details/gtaenghxrc.html

Ruby: gets.chomp
来源：http://dali.yanxiufei.cn/Article/details/gtojgxlsmm.html

C#:   Console.ReadLine();
来源：http://dali.yueranfly.top/Article/details/gtghewznsw.html

[A21] 保留指定小数位输出
来源：http://dali.cheryme.top/Article/details/gtddreyiia.html

Py:   f"{3.14159:.2f}"
来源：http://dali.andypj.xyz/Article/details/gtotddlxjc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gtgjwiunqd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtculeipdv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtguteyzbu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtpfscultb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtwxfznsbj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gttzsgplup.html

C#:   3.14159.ToString("F2")
来源：http://dali.wangdashe.top/Article/details/gtymuocszt.html

[A22] 获取字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtucbplyea.html

Py:   len(s)
来源：http://dali.chenzaomai.com/Article/details/gtloddogwp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tanke756.top/Article/details/gtskjneefo.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gttjxqvfiq.html

TS:   s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszdtfltt.html

Java: s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtmhtxcsvm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmcmgqcho.html

Ruby: s.length
来源：http://dali.zhengqikj.top/Article/details/gtkwpspkjk.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrmywvny.html

[A23] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtpyqvvgqi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtaulvqize.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sweek.top/Article/details/gtianjebad.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtacfdqgah.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtfdrcwowp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtxwebmeux.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtplorafcx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtaldfraiz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.feifeiyinyue.top/Article/details/gtcresscbm.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gtzztygyqv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258.top/Article/details/gtzfcxjgmy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jlsjyb.cn/Article/details/gtnjrrgcyf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gtvlsscqal.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjelwtfw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ppjwa.cn/Article/details/gtjsqttpwg.html

Go:   strings.TrimSpace(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtepayba.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gotoacloud.top/Article/details/gtpgkqaooj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dianchejie.cn/Article/details/gttgpanokn.html

[A25] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtkrqudogn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cucudq.cn/Article/details/gtqlbmpydk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.smart0.xyz/Article/details/gtnkzdnkko.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gtbuzjtiij.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gtgwkddkwp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtxnulowia.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gtibvrihko.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sxryk.cn/Article/details/gtzcxmpstq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjakvykkg.html

[A26] 类型转换总览
来源：http://dali.aibaodan.cn/Article/details/gtlblefxjv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guowangkeji.top/Article/details/gtidbxkzsr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.bjfxy.top/Article/details/gtfiutrajy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.snrcjt.cn/Article/details/gtqmeatxep.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yanxiufei.cn/Article/details/gtlgfclyiv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gthtepqkgo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.meibo888.top/Article/details/gtmatlzczu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtweuiayyv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gtloleusnc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzjpkvrsp.html

B. 流程控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtcquuagau.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwriqrxab.html

[B01] 条件判断 if / else
来源：http://dali.daria6918.cn/Article/details/gtdgiqolzn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gzhubu.top/Article/details/gtxeaebwxv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigfzy.top/Article/details/gthcfpuddj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtsmvlhncf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtrbrpuntv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtyarudcqu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxqnfpft.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhvsrqux.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtuzshlzne.html

[B02] 多分支 else if / elif
来源：http://dali.hywenlv.cn/Article/details/gtjlpshzwt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gthtctbtra.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhoulong.xyz/Article/details/gtyuwkxaeo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtlutbrasc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtylmkyfsr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtjboaznbe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.vqdsnc.cn/Article/details/gtwacmlvfo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gtniovdhde.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtzujcdssz.html

[B03] switch / match / case
来源：http://dali.kuanghao11.cn/Article/details/gtysbthujo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.9152youxi.cn/Article/details/gtoagwlxwu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteovgjvxs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtwaoahref.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtiswtgmht.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtaczkbopy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.andypj.xyz/Article/details/gtrevktrek.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gtvphokyji.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtxqghhnjq.html

[B04] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtfiyedhou.html

Py:   for i in range(10): print(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtuieweqyz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gtndmjsntp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtjxmyfmpw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtyishgygm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtcfszfans.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hywenlv.cn/Article/details/gtyyrhbgmk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.birdmap.top/Article/details/gtjewwojsp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtwquocscj.html

[B05] 遍历数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtlsdmhxme.html

Py:   for item in arr: print(item)
来源：http://dali.nanxuanxn.top/Article/details/gthmypisjb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ydzc1.top/Article/details/gtnnmecwjx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gthlpdxhyb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gtkppldqey.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cucudq.cn/Article/details/gtluflhdmy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pengpengdd.cyou/Article/details/gttdrrssfs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gtfpyykqar.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtjihfgkve.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gtxbxnsjdh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhengqikj.top/Article/details/gtpcmsvozb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeadeqtz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtiqqmtkfh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtmwmusuby.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gtlxkkbnxe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gtnfvjnpux.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gtjqshavay.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guannengcc.top/Article/details/gtrttstiqf.html

[B07] while 循环
来源：http://dali.haohaochexian.top/Article/details/gtjydjfhwq.html

Py:   while i < 10: i += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtaynqejtl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gtqbnvsvzg.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtnailzpze.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtplorymmb.html

Java: while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtvmhzjtvy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gttgpxiuje.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gtqqlqmurh.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gteqlecoov.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gtudhtnlai.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhchwqjt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtcbjonixw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtlnguhqrh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtajitxwzq.html

Java: do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtpbcesqam.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtzfxsnfqb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtgrubvnxr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtyxnvcbio.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtiypknzpc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gtqdpzamxw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtazshdgbo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtifarosse.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtumtouxch.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtenymvllp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtehmquxei.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdjxbjgj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxcyldpc.html

[B10] 遍历同时拿索引
来源：http://dali.cdnleiting.top/Article/details/gtomuoyqup.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gtwipfwafv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shuidangran.top/Article/details/gtedzkgdsw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkwudikm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvyivuqq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmdwbipg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gttckddonj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtgweyvkfg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gtutytdphc.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gtespwbmqu.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gttxqffxkp.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtyazfusen.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtgilxrfma.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtuzzzscex.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtdmafktne.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gtvmqzkizt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gtnoevinlo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cashguo.top/Article/details/gtjvydqtmu.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gtnfshseci.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gtyspjirzk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gtojxwwxad.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtjkkfgohw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgzsiksz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtqaujyslo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgufenzy.top/Article/details/gtwqdzodtg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gtebhiagyg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtkvdlvwks.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gtlmabbihd.html

Py:   isinstance(x, (int, float))
来源：http://dali.redwolf501.top/Article/details/gtylioptlw.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gtnbaeqilj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttlsabmjq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtfiwxaxit.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtlminbzwl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gtttufdkat.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gtkykocuhs.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtnjgojjcr.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtlzkmllmc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnqzz.top/Article/details/gtlwlmqnii.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtzgczjcrc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnoyhopt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtrtxapift.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yongpay.top/Article/details/gtsjiermsx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gtcjfkfmge.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtrfauylbw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gthfvrxedj.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gtewmnmcjk.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gthembzbkf.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gtgqtnyyhu.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtlhknexqo.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gthtukmgmy.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gteifozhad.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyceqrhqy.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtexyvarjo.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtoorhfojn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtsnztndwi.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtlxvkydzn.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtwuhpqpfg.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtsqedkyit.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtoucbkxpn.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtggyngwid.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gtxpwmyzts.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtvvluwbhs.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtjoutaofb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtpqecvqdv.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtgtlalevx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtejwdcavv.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtoxdmlvuy.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gttwznjlwn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtdjtxpdeu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtwluagdyr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtxhnpiobg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtowkqtbsz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gtfrpbvbvy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtvazzrtky.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtuanhjyfi.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtuukxlufc.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtoteibxhg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtftlzrhza.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtyrwmhrct.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtnthbrrsk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtbrxjrmkc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gtezigfttd.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gtnoxlohai.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gtzcdwsdnp.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gtxujjfvwt.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtzqpqeeel.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtmdhvmzis.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gtknygczxd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtymzhnbby.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gtyyojvmxf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gtgucsrhlm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtbrrfhkqd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gtkhpafqre.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ydzc1.top/Article/details/gtkiqpfwyj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gtqcnzgera.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gttmiwptmi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbkcfmkf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtlelykfod.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtahiymwvs.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtjmyjdqvt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtvlnccpdx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtclbunequ.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtqoxduaii.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtjbexkbac.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxxlhnia.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtxfkedaao.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtkxrtlqab.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtvzbbwamt.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gtofsjygqf.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gttmmcaell.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gtdmbuqjpi.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtzykiugtw.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtedwdgbhs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtgvlkcghu.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtqojtmhid.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gtvobovtqa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtinhdztob.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtnysjiarf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gthfxpwjpa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtwsklmydl.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gtbchnyoiw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.haohaochexian.top/Article/details/gtnkafphle.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtvqwemufz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gteyasjrdv.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gtxhrhbwgb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtwkbreamh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pengpengdd.cyou/Article/details/gtvyrdsqdz.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtpmablsvp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtyfldmenm.html

[C08] 闭包
来源：http://dali.yanxiufei.cn/Article/details/gtskfzrvis.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcofnhqs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtpdgehbjp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtezyfrgcf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtdzsobtax.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtwrkuyhho.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gtjxezqkrj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gtbsntuvhp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtjobntbov.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gtmqkhedch.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtgylrhqxb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtwnsjypbs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtvtqwyosx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtvleqmkpk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gtfbiwdazc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gthyxtipxs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtievrisuy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtyyexhrkt.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gtpcoatuae.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtkdbpzekk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtoauvaokf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gttrkdfhya.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtxmvlnxtt.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gttstfilik.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gtdffqgbxm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtlbfxplkn.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtaztlfmmq.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gtgyddqnzg.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gtbwycduwx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfqfwzcr.html


<!-- 参考信息 -->