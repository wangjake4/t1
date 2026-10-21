代发 wailian999

[A22] 获取字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtimngstkr.html

Py:   len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyrqgmuu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.quarkkingdee.top/Article/details/gtyhqycosj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nanxuanxn.top/Article/details/gtbmzflpaq.html

TS:   s.length
来源：http://dali.hnxiangtu.top/Article/details/gtcpqviidi.html

Java: s.length()
来源：http://dali.jyoumei.cn/Article/details/gtomyqaqcd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aibaodan.cn/Article/details/gtyfhxzbve.html

Ruby: s.length
来源：http://dali.yonumen.top/Article/details/gtphvhjbmb.html

C#:   s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtkjkzkvjl.html

[A23] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtdqnzywff.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtjdzjopbs.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daria6918.cn/Article/details/gtibtubkbb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnzusyao.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtiysshryl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtdkawsiud.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sweek.top/Article/details/gtcspdcybz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gtcbfgkrkj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cdnleiting.top/Article/details/gtsavymfjk.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gtpgwoonmg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuxming.cn/Article/details/gthsgvdwud.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.bjfxy.top/Article/details/gtebvkvtaa.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtotjqpeau.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gtttrclluk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.fengsongda.top/Article/details/gtxvypnukr.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gtenhuxtbn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivpvuqlo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yonumen.top/Article/details/gtiydjeigf.html

[A25] 字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtoarsnjvm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jiagoushi.top/Article/details/gtdfrvamcm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jyoumei.cn/Article/details/gtdiddggka.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gtvxvxkhml.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtjcolihzh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cdnleiting.top/Article/details/gthkgcftsf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.c1oappe.top/Article/details/gtyoixfwfv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hongshengwenyu.top/Article/details/gtxnhmcpfo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwgubcol.html

[A26] 类型转换总览
来源：http://dali.dianchejie.cn/Article/details/gtqmkkxjla.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daria6918.cn/Article/details/gtmltctsvy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fengsongda.top/Article/details/gtzkkdejls.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jiagoushi.top/Article/details/gtbrtbgcpu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.kuanghao11.cn/Article/details/gtyngrhtkq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gtihvllrrp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuitsksx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.kuanghao11.cn/Article/details/gtxjcocbuy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.meibo888.top/Article/details/gtcwmerlzc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlrnpmtra.html

B. 流程控制
来源：http://dali.gaohongyu789.top/Article/details/gtqyubidhk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtopmpkydt.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gtkfwcmsdz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gotoacloud.top/Article/details/gtxexiffsj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gtobvyaevy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtqibyujkp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvnuvqei.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtqyqymyph.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gtsokhwonn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hfpthk.cn/Article/details/gtklvxboym.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gthwdfeeya.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gtjrukmgmc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ydzc1.top/Article/details/gtvxngsexj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjagkdvy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtunpwfpkp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtywkcatvd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtzziqnagk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hammf.cn/Article/details/gtozcqmdck.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.aizwys.cn/Article/details/gtuqqgcxmf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtmvzscrwe.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gtlzzccion.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shuidangran.top/Article/details/gtgqfgkkgi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gteegsvfut.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtbvoppkxz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtdqnlrfys.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gttosofijo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gtghfsscek.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenjidiqi.icu/Article/details/gtjsbzvxml.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gtfjztdnmx.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtnbvdrlmo.html

Py:   for i in range(10): print(i)
来源：http://dali.sxryk.cn/Article/details/gtfqvwxfid.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhongyouzk.top/Article/details/gthhhzmyki.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtlgqbocur.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtnwitgqqq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hfpthk.cn/Article/details/gtasfklzes.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hysaishi.cn/Article/details/gtkmdpwqoe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tanke756.top/Article/details/gtmexlnrtd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbquusglr.html

[B05] 遍历数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtnygofclt.html

Py:   for item in arr: print(item)
来源：http://dali.gzhubu.top/Article/details/gtjtlcqjhu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtdnscejkn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gtgtrvunrg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtwoopefhz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftbwswxh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jlsjyb.cn/Article/details/gtxyhiikcg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.pycfn.com/Article/details/gtgdveiuou.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtztluhzbm.html

[B06] 遍历字典 / 对象
来源：http://dali.jinghuilouyu.cn/Article/details/gticezfesb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gtpjbsvjfl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sysykeji.top/Article/details/gtiswnnelo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtltycmajv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtnnojgvfn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sysykeji.top/Article/details/gtthpxnywp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.haohaochexian.top/Article/details/gtnkebabuc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuxming.cn/Article/details/gtxeagmsre.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtyinylmyg.html

[B07] while 循环
来源：http://dali.quarkkingdee.top/Article/details/gtmpkmbncs.html

Py:   while i < 10: i += 1
来源：http://dali.snrcjt.cn/Article/details/gtcwpdsnvz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dashuyun.cn/Article/details/gtlajyiypi.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtpbogsgcp.html

TS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtbbssgmxf.html

Java: while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtjdkhrrjh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgwddobk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gtkznswydx.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtzdbqrcll.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gtwhwcuiqr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yonumen.top/Article/details/gtjqftantb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfwzhqjt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtcfzwbyxk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gthqdxukwb.html

Java: do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtxqcappnk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gthnghhttc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtvpiimsiz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtandmmjcm.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gtzpizzbut.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gtfuwejsqc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtjjlsujqf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtdjlnpniq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtnlzmmiem.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtihujoqjn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtaxturndu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj202588.top/Article/details/gtrjajbzvt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gttzyydqti.html

[B10] 遍历同时拿索引
来源：http://dali.dianchejie.cn/Article/details/gtlzlrbkfp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gttjqukirl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gtlsnsxidm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtnohxwili.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gttqmfnbjt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gtqmfpyjkk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gtoyuzsfek.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gtovmgpnvv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtthojpwcx.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gtwhdtklos.html

Py:   list(range(0, 10, 2))
来源：http://dali.haohaochexian.top/Article/details/gtvmgapter.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtojwbcdiv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtnktccjhk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtslmxlxrn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gttfxbdocv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gtszkzeqez.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gtammxxxif.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jyoumei.cn/Article/details/gtrphtzkzk.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtaiunobjj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtvukmbihb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gtwyyqpjiz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtkscglplm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtlzjsahhr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtfgailvmd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gtxenydpgs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gtimpgznyp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ppjwa.cn/Article/details/gtxlmokept.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtieztwefb.html

Py:   isinstance(x, (int, float))
来源：http://dali.yongpay.top/Article/details/gthraiwbyq.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gtnubrxvsc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtwrujmckd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gthyorores.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtmnwhlaxi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gtnksxovru.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gtwlvilnsr.html

C#:   x is int or double or decimal
来源：http://dali.meibo888.top/Article/details/gthkkllsig.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtnufwzkzw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtzspccvtg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gtqacakpyw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtjyeepogf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtytuvwxto.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtwwbtmxcz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.316326.xyz/Article/details/gtmhqgiael.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtodhjpytf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtantpiexz.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gtnuvnewuu.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtjrpkxlqx.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gtcjdewkpy.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtdpqpmxpq.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtdetuvwsf.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtjanycfgb.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtudefafhp.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtmvnvgtgp.html

C#:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtqwlxsinx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tanke756.top/Article/details/gtmasncgcq.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gtvkqbuqpw.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gtycrojahv.html

JS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtmsajmwzi.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtpxfbcfja.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtcaddwuik.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gthocenjfq.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gtdcuizbow.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtxdxaqkhz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcowywdap.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gttcgbpyrg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjfeusaaw.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtljbtulor.html

Py:   def add(a, b): return a + b
来源：http://dali.xylfe.cn/Article/details/gteacpfctw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gttfnswajw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtkfayjrcy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtvmygwmoo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtmasykavm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtzgfihpqo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtjssexwmr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgehbyjox.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gtlhcoxrnz.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtvnlyhlla.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gtvlcpical.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtflytoout.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gthbhqvmok.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqjmmwks.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.havefunace.top/Article/details/gtnhbbwahe.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gthkvfgriw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gtrpapkent.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gtcuazyeyf.html

Py:   def total(*args): return sum(args)
来源：http://dali.aizwys.cn/Article/details/gtsvjcoskm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtgekmpmuf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gteevetoyl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtejeogrfc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gtqsarqkqc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gtmznqzjcb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhiwuduotai.top/Article/details/gtoeuopcgh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtonoyjygy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gtxgsycgdy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtsqubpsws.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtyyhtmuvl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsvbhskzf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtjytsxesu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gttyrjvlbu.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtdytrutwr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtjwftiaux.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlakxkpj.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtgbwljjus.html

Py:   return a, b
来源：http://dali.cucudq.cn/Article/details/gtlmhihpev.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtxieuasyl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtgznwsehc.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtlvpgwbzw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavgcyybn.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtdjzsraxo.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gtkokssvyw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtekqygtql.html

[C06] 匿名函数 / lambda
来源：http://dali.redwolf501.top/Article/details/gtpdnxnkhl.html

Py:   square = lambda x: x * x
来源：http://dali.hnxiangtu.top/Article/details/gtfkoerqvo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtqqvqkogd.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtoresfhtw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtofpugagd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtczttkzrg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gtxaaraxmf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtvfqgxxsr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gttkfrpdtc.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtyjkftrmm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gttxxbnpdo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gtomzilqnm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gtomwctkue.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtteyujxto.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gtcobqatex.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gtalsifvlk.html

Ruby: arr.map(&:upcase)
来源：http://dali.yanxiufei.cn/Article/details/gtkfwlmvap.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtsfgegfgh.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gtrteyrplu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtlsjutldd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtzznpvhlg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtxeawkmpu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtmtrzzfqx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtkojzczme.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gtxmowjjvx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gthsossduz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtuxfgzduw.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtukulvkfx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtnzbbfrvp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gtfjzdpqnm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtylwdpfts.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtdoxefqfr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtacbhmoeu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gtsapwrqfn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gthyhbhyxl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gtttxeecmd.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtvkuzhiel.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtqcstxgqg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pycfn.com/Article/details/gttmpvruwz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtkzhksejy.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtbdbiicxn.html

Java: 方法内为块级作用域
来源：http://dali.yueranfly.top/Article/details/gtcjuonehp.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtrlxkvkls.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gtmuljgexr.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtucfoucoq.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gtlelbrkow.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gtuuwobkni.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gtqhywakjc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtrlrhyhxz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtabritgdv.html

Java: import java.util.List;
来源：http://dali.jinqigufen.top/Article/details/gtmpavqmuk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jlsjyb.cn/Article/details/gtwmgjuate.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtkkezkyqr.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtirktajvg.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtxfemzdnm.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtzcuazyuh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtvzfodffz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtpkrbipqt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtwnesawhp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gtswpsoaix.html


<!-- 参考信息 -->