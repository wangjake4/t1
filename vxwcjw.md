代发 wailian999

[A22] 获取字符串长度
来源：http://dali.shzxlz.cn/Article/details/gttsyawglw.html

Py:   len(s)
来源：http://dali.dashuyun.cn/Article/details/gtqcakjyeu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xuetiantiany.cn/Article/details/gtizyjvaej.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yueranfly.top/Article/details/gtflisohuy.html

TS:   s.length
来源：http://dali.dianchejie.cn/Article/details/gtjykozewt.html

Java: s.length()
来源：http://dali.hammf.cn/Article/details/gtdtebiheb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj202588.top/Article/details/gtyagyrllb.html

Ruby: s.length
来源：http://dali.c1oappe.top/Article/details/gtifuyyhed.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcibntfu.html

[A23] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtmghwyfjq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.svipenyu.cn/Article/details/gttdqhgyqz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtihbjabta.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gtvknolxoy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtgawcsvgb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtlegmvvpb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gttvfqhdbx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtnjtnvkpb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhiwuduotai.top/Article/details/gtwzhoerar.html

[A24] 去除首尾空白
来源：http://dali.aizwys.cn/Article/details/gtlowbuywa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.feifeiyinyue.top/Article/details/gtdfsimtra.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guowangkeji.top/Article/details/gttrbhewky.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gtsaxmxvyk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aibaodan.cn/Article/details/gtbkmdfvte.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvvnxatn.html

Go:   strings.TrimSpace(s)
来源：http://dali.daxiang520.top/Article/details/gtctkoudry.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hywenlv.cn/Article/details/gtrvvupcbd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtobzjqmcq.html

[A25] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gthdeoactn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yanxiufei.cn/Article/details/gtzvuxyymy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gtkpbjlzsj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtqcznqlgt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dianchejie.cn/Article/details/gtxiisolel.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ybcxt.top/Article/details/gtqaombocg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gtctlzinxe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258.top/Article/details/gtjlzsfxjx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gtxdcczfdv.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gtieftgwrc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrbyflhf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gotoacloud.top/Article/details/gtrfaqavhz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pycfn.com/Article/details/gtanykbhqk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jqgfzy.top/Article/details/gtoqtvzmqs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gttxwqtcko.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.pengpengdd.cyou/Article/details/gtnmsneiol.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.c1oappe.top/Article/details/gtceoxwhue.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtovlmvdrw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtzceokqiy.html

B. 流程控制
来源：http://dali.jqgufenzy.top/Article/details/gtzalftebf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkcyldqvu.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gtehlpsocn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xylfe.cn/Article/details/gtieoaoned.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ivvv.top/Article/details/gtdpoutoou.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gthbcfwdbo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtstjhzdnw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtritfmely.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.snrcjt.cn/Article/details/gtnsdiqdxb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.0kj1m.cn/Article/details/gtkdsqizft.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtbnjxvhsy.html

[B02] 多分支 else if / elif
来源：http://dali.hywenlv.cn/Article/details/gtrobxjkyp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtbajqydkc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxmpjkbkj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtvvcpbwru.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtbwffhnwt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtuspxklna.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gtllyqcsvb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xylfe.cn/Article/details/gtgavhkqzm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtyfpvxnrf.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdynhqkxn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtyjwcpnvw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtbukvbasb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtlfkumcgt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtwwbyibrs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtejgvkvxx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtvkmhtrcg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aibaodan.cn/Article/details/gtjeujjlep.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gtbfvdkcry.html

[B04] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtrgvvbwcv.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreoinokx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gtmzttfciy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gtzwxnovmz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gtapbczvkf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.0kj1m.cn/Article/details/gtfygtvauk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yvedp.cn/Article/details/gteuhaeflu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ehwqpu.com/Article/details/gtnptukmou.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.dashuyun.cn/Article/details/gtmtjdcwpb.html

[B05] 遍历数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtzoleqnhp.html

Py:   for item in arr: print(item)
来源：http://dali.yonumen.top/Article/details/gtbjpgitrt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dashuyun.cn/Article/details/gttjdimtae.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gtkslvruke.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtoswykymd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.bjfxy.top/Article/details/gtyfzvbhao.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zycfv.cn/Article/details/gtqcztiwxt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangshuangyany.cn/Article/details/gtyxltbuxa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ivvv.top/Article/details/gtjbosiemi.html

[B06] 遍历字典 / 对象
来源：http://dali.zhiwuduotai.top/Article/details/gtvjyshgra.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zdqjudy.top/Article/details/gtmqvzttat.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.redwolf501.top/Article/details/gtctngplql.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gtqfqbusol.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gtmszescto.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxinkj.top/Article/details/gtukrlmyuy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tanke756.top/Article/details/gtsztbptwe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hysaishi.cn/Article/details/gtugtnpiuv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.mhx1999.top/Article/details/gtwikvwdim.html

[B07] while 循环
来源：http://dali.jiagoushi.top/Article/details/gthdfmjmoc.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gtsiflsmmo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gtstujtusl.html

JS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtcrlsmoee.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtjljmrpsq.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtclekiesf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gtrggbskgi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xziqi.cn/Article/details/gtunjkcicl.html

C#:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtvnxezqaz.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gtvzqtbvle.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gttcqiwusk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtwbhwpuvt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtacbxvskw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gteeqkhsid.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtsexublpi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gtqtagdkhc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gtakbtjypq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gteviotyim.html

[B09] break 与 continue
来源：http://dali.ivvv.top/Article/details/gtyqgneihe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuanzhike.top/Article/details/gtonoejbve.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtijtbsbhf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgskdorea.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtavzsiyjq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gteaotzqjz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtukxnyqxq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gtcccbhkpb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtinnqyluw.html

[B10] 遍历同时拿索引
来源：http://dali.dianchejie.cn/Article/details/gtblmbpocd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gtkoqbbief.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtojppidkr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtktcvdedi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtgfamaczw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtuuqfnasb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.haohaochexian.top/Article/details/gtivojmppe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtpbqzczlx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gthavbudqd.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gtjutlbtqz.html

Py:   list(range(0, 10, 2))
来源：http://dali.dianchejie.cn/Article/details/gticwmtbki.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtlhmvvayr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtazygwmpm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtaepdlrgz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gtyvppyplb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gtrzibrapm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sweek.top/Article/details/gtizmmugvh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gtobxaylio.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gtuoymkopi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtaxafcqps.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtxlowpokp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtighyvsnh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gthwmjidca.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gthvfkorwf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gtydxteejz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gtkectldzw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtuwvxmobh.html

[B13] 判断是否为数字
来源：http://dali.snrcjt.cn/Article/details/gthxlskyzo.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gtiprxmbox.html

PHP:  is_numeric($x)
来源：http://dali.ppjwa.cn/Article/details/gtfjwpnpjo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtwwgsrroe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtgnirttlp.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtkfcpussg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gtxoyyufyo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtnysoibhc.html

C#:   x is int or double or decimal
来源：http://dali.chenjidiqi.icu/Article/details/gtczqjpinw.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtkqmgyybj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtnfkhohfp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtmsjrcdcv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtbrzyutsr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtatohzv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gtkvoxxwuw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gtlckfelvw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gtknygiwry.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gteqorsgsi.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gtzeguvbtx.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gtgjgszlgh.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gtdzdfbjze.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtnnxkdzyk.html

TS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtzhltniye.html

Java: a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtuevodyag.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtkbxxvjnu.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtermckrgu.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtpuomolcp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtrvctznoz.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtzzktvfxi.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gtpwgyrfyk.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtmtgkywqc.html

TS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtizmfxmez.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtlrwsuxoq.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtwrvrwzkx.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtdaaltyut.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtrnbcnfen.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxpwchngr.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtltenmlbe.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtuqmcfodm.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtlaggmcan.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtkcwubkfi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtclgspeis.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtyjgvszgk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrahzbwni.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtrqqzrqmd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtticxfizh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gtzoukfkfc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcylnavj.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtgkpjdrck.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtetdqlbgm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gtpulyptfr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtxrsjcdnz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdezfmwza.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtninjaryr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gtvddkguol.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtxjjlneih.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gtofcoohca.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtwzqasknm.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtuwfsqrqj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvbyrzneu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtkfoqpvov.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtfjvfufco.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtribwmzux.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtcuydiycv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangdashe.top/Article/details/gtmcyozwjv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtxdhfcaex.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtfhjuonvx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtpjfbhrii.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtmpwpeduk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gttnflduym.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gtaohuwruw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtjbqqgafm.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gtfovrlvzc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gthasogqvl.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtklcnjigo.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtpsgimqtz.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtgymfpdlt.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtnprorjja.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gthwfskhgi.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtmbisfqfx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtwpgckfns.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtfbqvpbcc.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtnapgfecw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gtoahzmdsj.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gtddesynrq.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gtwcsswyzz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtrwfbaqdt.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtbgglburc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtrzpkqeeo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtsyghpikm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtzcefzsyh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtodxsxtfa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtbdnasfzg.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gthfsyoutz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtwrcigfwo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtpwtuzumx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gtlxrlrkvo.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtxnpipqsn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.svipenyu.cn/Article/details/gtnlzkxyxs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtgnlkzbts.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gttjeflrfd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gtdkdtoedp.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtowzcjtep.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gtlikwfnul.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gtoembrlls.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtjgdledzl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtinrjskty.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtovhzzguo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtvqvpapva.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtoqtprzlm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtmgnmpthr.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtqycqwbri.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtoldrvywr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtarhrhjca.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtxqhleghn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtwhasbimz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtmntmgwox.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gtgsegluip.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtwhlgskjt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggvyvuou.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtprabvrrn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.smart0.xyz/Article/details/gtpkygzzqm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtvapranvk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtdybgtobt.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtwsjcemup.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtouxnrysy.html

Go:   花括号块级作用域
来源：http://dali.yvedp.cn/Article/details/gtyasxlxqm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gtrcccynlk.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gtwfofjpte.html

[C11] 模块导入与导出
来源：http://dali.dashuyun.cn/Article/details/gtuwkolujo.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gteiwibvjs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtrbeumdye.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtkerisird.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvonqzimh.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gthqiwdwnj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gttxdacoun.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gtoajpegwp.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gtyelezudn.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtawthzitl.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtjokgzkth.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtgqtzytfm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtvkllsalw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhixingplan.top/Article/details/gtvmeginjg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtedttvhlk.html


<!-- 参考信息 -->