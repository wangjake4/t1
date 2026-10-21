代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhiwuduotai.top/Article/details/gtdxznaxfs.html

Ruby: gets.chomp
来源：http://dali.zhixingplan.top/Article/details/gtrrtqtvaz.html

C#:   Console.ReadLine();
来源：http://dali.havefunace.top/Article/details/gtsqxcsnxj.html

[A21] 保留指定小数位输出
来源：http://dali.wangshuangyany.cn/Article/details/gtnklmwfgo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gaohongyu789.top/Article/details/gttefaeyug.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gtylqatrqo.html

JS:   (3.14159).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtqylagoyp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtutliaqlw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtlebkgktq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtyadnzyib.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtzocgqsgu.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gtdziiiwwe.html

[A22] 获取字符串长度
来源：http://dali.yangfankeji.com/Article/details/gtaxrbeshr.html

Py:   len(s)
来源：http://dali.9152youxi.cn/Article/details/gtmrsntrod.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.bjfxy.top/Article/details/gtnphiujjz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gtaukrvshe.html

TS:   s.length
来源：http://dali.cheryme.top/Article/details/gtzianaehh.html

Java: s.length()
来源：http://dali.316326.xyz/Article/details/gtrtwhlkau.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gtrvbsykni.html

Ruby: s.length
来源：http://dali.xziqi.cn/Article/details/gtexkktrvw.html

C#:   s.Length
来源：http://dali.chenlongwang.top/Article/details/gtlzgiexyi.html

[A23] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtixtvlmxm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.snrcjt.cn/Article/details/gtkplrbjcf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fzhhl.top/Article/details/gtmcphjlxb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtnolyxkej.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtjrqhsuhb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtnqmjywro.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gtbjvixffe.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtvlhuautd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ybcxt.top/Article/details/gtzbeyaigt.html

[A24] 去除首尾空白
来源：http://dali.yj202588.top/Article/details/gttbbhwgwp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigufen.top/Article/details/gtsftuvuzw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tianlin.xyz/Article/details/gtralfstlf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gtjyeelztb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtrqjrnzqt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sxryk.cn/Article/details/gtpwdtekxz.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuxming.cn/Article/details/gtaupommvn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gtikwipwyk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pycfn.com/Article/details/gtbajysipy.html

[A25] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtykvzhcjn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gtcyvqqcrt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgufenzy.top/Article/details/gtcrlsqppn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpmmybmhy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gttbexpqrl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hysaishi.cn/Article/details/gttenassah.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtmpzdgfme.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hywenlv.cn/Article/details/gtuceqrfhu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtbohpdpju.html

[A26] 类型转换总览
来源：http://dali.smart0.xyz/Article/details/gtjsdqczjc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nwbrower.top/Article/details/gtysbdtalv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj202588.top/Article/details/gtxsxvgzkl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.316326.xyz/Article/details/gtzykseiuh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ybcxt.top/Article/details/gtzkrzbtcw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.havefunace.top/Article/details/gtzxhrmdto.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gtpdwmiojz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yonumen.top/Article/details/gtrxyycuof.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtyhclxyji.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcdoxwezr.html

B. 流程控制
来源：http://dali.ppjwa.cn/Article/details/gtemlvwmjy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvmdwswjt.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gtfziynymv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahyhruma.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xinyue.icu/Article/details/gtngtspcjd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtvlzyylrj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtvsfktaah.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtskzslbxt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxinkj.top/Article/details/gtulswpgah.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pycfn.com/Article/details/gtqfogsuxo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gthcxhtiqn.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gtadxmtyoe.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jlsjyb.cn/Article/details/gthsjtnblj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.mhx1999.top/Article/details/gtzsxhjxoq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtuvwrbjxm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtzxpllydb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtqqtjelrj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgufenzy.top/Article/details/gtddgiveih.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenzaomai.com/Article/details/gtbfduzerl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtjgmpnosp.html

[B03] switch / match / case
来源：http://dali.xuanzx.com/Article/details/gtwhvvrpud.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtuenmfagn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtaezhxbdm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtfnruoxjf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtkzbpozhu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtdnrtbumi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.c1oappe.top/Article/details/gtezjcerxa.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jyoumei.cn/Article/details/gtiamlrukl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pycfn.com/Article/details/gtikimuosf.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtjcloeplv.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gtjyfllwar.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hysaishi.cn/Article/details/gtthhrbsfe.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gtxhaqaujd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtqphtyzaz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cashguo.top/Article/details/gtpyeemnjz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gtowdgecdh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nanxuanxn.top/Article/details/gthzaaflwh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gttoingwjs.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtseuiydsw.html

Py:   for item in arr: print(item)
来源：http://dali.gzhubu.top/Article/details/gtpwojkvsa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.fengsongda.top/Article/details/gtemuszgsc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gthauoahhq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gthwaingxd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtyilyoqkf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dashuyun.cn/Article/details/gtasoqqruv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.vqdsnc.cn/Article/details/gtwrfwsvph.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xylfe.cn/Article/details/gtsdembtvm.html

[B06] 遍历字典 / 对象
来源：http://dali.sxryk.cn/Article/details/gtuymptpwx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zdqjudy.top/Article/details/gtymonjoxi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cashguo.top/Article/details/gtoucalsgk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtkvnjfpli.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtsmsnyfky.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gtslgdzqvn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gtangpuqni.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daria6918.cn/Article/details/gtwlkdwfnk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.svipenyu.cn/Article/details/gtpsjobkft.html

[B07] while 循环
来源：http://dali.gaohongyu789.top/Article/details/gtshosocxv.html

Py:   while i < 10: i += 1
来源：http://dali.316326.xyz/Article/details/gtegatxqbb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvcizfdjq.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtzpiofesk.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfbdrjvih.html

Java: while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtbqruexyw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gthtcmlhli.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gaohongyu789.top/Article/details/gtrdywzmco.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtidgqhsdg.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtzmlapkos.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gtxjvhlgtn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtmqqndcve.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmakwyojk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtnzkhsspn.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtrkjmgkkk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtgwuvypzb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.kuanghao11.cn/Article/details/gtyhhcwpwe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtoukejcas.html

[B09] break 与 continue
来源：http://dali.yongpay.top/Article/details/gtfwmpjmjf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtmqvtvowr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpomtwqog.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtzpienmen.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtfbzopeyq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtimosxqsf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtqbzskkke.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtrrzuumho.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtweuokfwm.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gtcozwwthc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gtjevbhasv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtgxlsjypm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gterlbytrh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtgkptfyar.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtlyqvynqy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gtslelqdub.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtloquivug.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtbellrszk.html

[B11] 生成数字序列 / 区间
来源：http://dali.meibo888.top/Article/details/gtmlyzmngs.html

Py:   list(range(0, 10, 2))
来源：http://dali.zycfv.cn/Article/details/gtwfupqoph.html

PHP:  range(0, 10, 2);
来源：http://dali.tanke756.top/Article/details/gtstkakxed.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtbuevvrit.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtugqnpylf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtgdmajcvd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvrjmzyk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtthvbrvoo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnqzz.top/Article/details/gthubgkggf.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtpzqeekmj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gthbrwotie.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gttcytxlnd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtfprjovvs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtirkvmvyn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtzgrwisen.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gttmqgcvrl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gtjmkoyyfh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoczhlktq.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtwsikjatb.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gtajkdhncc.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gtolfwcvyg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtfaiwdhcw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtloxodlmn.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gtyfauxxfd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gturqrhcdb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gtwcvubvgb.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gtpcyyhprr.html

[B14] 判断值是否在集合内
来源：http://dali.fzhhl.top/Article/details/gtivwhcjwl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtcpxqjaog.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtjrxeozkg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gthtxtcxal.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtawcqkpps.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtwcsyhowo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangdashe.top/Article/details/gtaaswbcau.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gtqclbyuoh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtiyfyzxyo.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gthkpxfgpm.html

Py:   a and b or not c
来源：http://dali.hongshengwenyu.top/Article/details/gtvifqlraf.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gthfeaoiqr.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtepxzzyzv.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtwecfvnyw.html

Java: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtietjnakd.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtfvtophev.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtiecisypj.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtceixxkfk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gtppdmpkli.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtrrojtejd.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gtdikvdnhn.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtfqukicve.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtwbzikocj.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtqtgttnhd.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gtelwyssgv.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gtpesxqvig.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtwgeiplqy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthsjhkakr.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtqcnmreud.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxmztxkzc.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtvwhhvuwm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gtvcdldhfu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtmfjqemow.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtefnesyud.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgzouvqpf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtpvqnsije.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gtpfnzxhkw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtdzomrgdw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtixenivhj.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gtrgrdlzxn.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gtojyjrdvg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtbgclxgiq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtpgcliiwg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtxkigodod.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtzrhnnugr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gtnyqorzpt.html

Ruby: def greet(name = "World") = name
来源：http://dali.0kj1m.cn/Article/details/gtngrgfnlj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtrnpoydgd.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gtgmtefhty.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtvygvigbz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtnfuyyvdq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtqpdjfror.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtlhfynsvt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakplmnuu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gtuqffhmyz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtnwqihlvr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtpftqqrhd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gtbwukxzyb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtfejytitg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtijjimyql.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtodymmujf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gtyrabdplq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtexzhdovm.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtruqzaygr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtpbfruvxm.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtvwihjnpz.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtjlshbuvr.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtqiurwwfw.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtdenuwsbi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtltsdowva.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtihrqisyk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gttbgfgbas.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtspiwdmub.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gtrdsmykrr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ydzc1.top/Article/details/gtteltcmei.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gthinhygnb.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpfhxipm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gttoahehcs.html

JS:   const square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtuvytshyi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtpxxuzrab.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yvedp.cn/Article/details/gtxqftcaej.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtrbakndjv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtzulwuovq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtvyznfsuf.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gtzgvqzcqa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gtvttpcwqj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hammf.cn/Article/details/gtbqgorgpw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwboiqsw.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gthbyusuoo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtongnvetb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gtfcgtuwey.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gtvyuueizh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtcczuxwhe.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtwphlwhvm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxcwcnsm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrumrppto.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gttmytprhi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwbbamrnf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtlifsyddf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtjpvolajv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xziqi.cn/Article/details/gtootpbmmf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtdpnajcnv.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtjdwghcnx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtmybfowtx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtwlcabhhh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtzmoamsui.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtaiqrwfyj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtvytqbmis.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtzkwtcqdi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtoxjyvbzu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gtifejoloi.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gthhusypxd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtavfhdrce.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gtzhwnxueb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gtaarelmor.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gtswyvhrbw.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtirwifyzf.html

Go:   花括号块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtwjucajty.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtehmwcfqn.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtiafjingn.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gtbwbsevtb.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtrqchxrqx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtynxusknb.html


<!-- 参考信息 -->