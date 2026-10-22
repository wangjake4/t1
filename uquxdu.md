代发 wailian999

[A22] 获取字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2yxhbqzcr.html

Py:   len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2fndwbljc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gt2mxdsebov.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nanxinkj.top/Article/details/gt2wjfnpwtm.html

TS:   s.length
来源：http://dali.dashuyun.cn/Article/details/gt2svhjqtlu.html

Java: s.length()
来源：http://dali.316326.xyz/Article/details/gt2qewvfcws.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2bioxfrdn.html

Ruby: s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2eflhgdqs.html

C#:   s.Length
来源：http://dali.aibaodan.cn/Article/details/gt2sugvuaed.html

[A23] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2ysbhkcbg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhongyouzk.top/Article/details/gt2ppkogqhz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqbqdoru.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gt2hkupnebe.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gt2fopnsqpa.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gt2gfokabpy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2pafgthmi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gt2anwutlls.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aibaodan.cn/Article/details/gt2wbyhondi.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gt2pmomlhkn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.havefunace.top/Article/details/gt2spcvszza.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hammf.cn/Article/details/gt2ujdizmzt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.9152youxi.cn/Article/details/gt2fhpskyaw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gt2plrgngqd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sufxvd.cn/Article/details/gt2dyeywsru.html

Go:   strings.TrimSpace(s)
来源：http://dali.cheryme.top/Article/details/gt2ppwbaned.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenlongwang.top/Article/details/gt2boypztui.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aibaodan.cn/Article/details/gt2yoasjxka.html

[A25] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gt2awxfxykq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigufen.top/Article/details/gt2fatvmsln.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikpnvpma.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgxpkcfx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gt2gvrnevwa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ydzc1.top/Article/details/gt2jpyxcqmm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2rkxtndxy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gt2wcfussqw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zeianwnt.html

[A26] 类型转换总览
来源：http://dali.meibo888.top/Article/details/gt2bpuavmnb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cheryme.top/Article/details/gt2ykeafwtw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sysykeji.top/Article/details/gt2qdyfwret.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dianchejie.cn/Article/details/gt2txholtto.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nwbrower.top/Article/details/gt2eoyljbgl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gt2szrgeeoq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigufen.top/Article/details/gt2rotgtxvy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258888.top/Article/details/gt2llwnmpyc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2ezpctoen.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2crajxlbs.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gt2yojahbro.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ocbypxww.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gt2aogkthvg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangdashe.top/Article/details/gt2bgazizlh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sufxvd.cn/Article/details/gt2evbazgve.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gt2ruqansjb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2eczezqmj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gt2fwqwuxdy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gt2mfhftjdp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tianlin.xyz/Article/details/gt2xbxweydi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gt2fwfhogbt.html

[B02] 多分支 else if / elif
来源：http://dali.yangfankeji.com/Article/details/gt2uffedvmy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenzaomai.com/Article/details/gt2skzpburh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gt2grapobpv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gt2wkjhofwb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2inuprxuc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2seghnvws.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jianghu66.top/Article/details/gt2yvxfymsd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gt2pvhexpzx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2rkoqzqzg.html

[B03] switch / match / case
来源：http://dali.dianchejie.cn/Article/details/gt2nizrnxvs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hfpthk.cn/Article/details/gt2ydeouxwh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2oqabgwqv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ahpbmtqp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymarxilg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gt2ebkjxrlj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yueranfly.top/Article/details/gt2xhzkxjts.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangdashe.top/Article/details/gt2rhgielab.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gt2sgtkfsbi.html

[B04] for 计数循环
来源：http://dali.yj20258.top/Article/details/gt2qqukmegw.html

Py:   for i in range(10): print(i)
来源：http://dali.redwolf501.top/Article/details/gt2mfzdckny.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aibaodan.cn/Article/details/gt2rzbakbzt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2rpgdgxmy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gt2xgmldecq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gt2hbgbaklk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gt2dtoqxamy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sufxvd.cn/Article/details/gt2bcmlvmnv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxuanxn.top/Article/details/gt2mhescrir.html

[B05] 遍历数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2hbyafpkl.html

Py:   for item in arr: print(item)
来源：http://dali.yonumen.top/Article/details/gt2pmtkzddw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gzhubu.top/Article/details/gt2iqgscwvg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gt2cjwxweia.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cdnleiting.top/Article/details/gt2rbhewege.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hfpthk.cn/Article/details/gt2ffrcovol.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daxiang520.top/Article/details/gt2uswobwah.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gt2wtjqrawf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2utzmfayx.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gt2vvgztewb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ivvv.top/Article/details/gt2fnwkblbh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gt2acqmmmkd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gt2butvurpz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2diypcjgd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gt2xcgssixd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hefucvtm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2trwqquav.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbezzcvr.html

[B07] while 循环
来源：http://dali.havefunace.top/Article/details/gt2soiljcyj.html

Py:   while i < 10: i += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2rsyywzgf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ehwqpu.com/Article/details/gt2vpfivdbl.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfnbwjpe.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwkywojh.html

Java: while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsafzxhx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.havefunace.top/Article/details/gt2sbuliatf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj202588.top/Article/details/gt2tqdkhiwc.html

C#:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nmsaqjgf.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gt2jhzuxaxw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gt2vkifeiks.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gt2klnhguvj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uutvybtb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2zahoaluc.html

Java: do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gt2dqzrzamz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gt2rtbvumbu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gt2jisbssfz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2marygpov.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gt2fejwwrhw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gt2zmeovcnw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2mcnujwti.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2dvhakuta.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzgoloce.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2xsfvinnf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.smart0.xyz/Article/details/gt2etgsipmb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gt2ruvgwcgf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2pefjvfom.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gt2gsuwvubx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gt2akymxzdc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258.top/Article/details/gt2edlpfkwk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2envcriih.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gt2szrxjlvt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gt2nwtklfxg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gt2hkdypinj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2qrwmiroz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gt2ientfesq.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gt2zxrqltun.html

Py:   list(range(0, 10, 2))
来源：http://dali.vqdsnc.cn/Article/details/gt2ashkfzqc.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2opddrxha.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gt2uvlaixkp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2gdgmrcdi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2nlseenuv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gt2qjaeimng.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gt2kamqkcxh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uphcygtw.html

[B12] 跳出多层循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjfrpfuh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnogiayq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gt2kgfcgmmr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2cphzmdpy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gt2hgzngtxw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqplaiud.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jiagoushi.top/Article/details/gt2udtmirdy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jyoumei.cn/Article/details/gt2lgfkdxir.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yabdastq.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gt2gnkbegia.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gt2stwdzter.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gt2ztmysklr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gt2rrrkayks.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2rgsjbwkh.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gt2eclibvcd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gt2mcmnbchx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gt2lsacwtse.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gt2gfbfokvz.html

[B14] 判断值是否在集合内
来源：http://dali.feifeiyinyue.top/Article/details/gt2virvnnfh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gt2whiitbfn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2takaxadn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2fukffxzr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2lqhxzwyn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2kynuariv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gt2jbedmdgi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmiwaymw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gt2scjbanlz.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gt2wwembmcw.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gt2azplgwwh.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gt2aivpnxcf.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2abzwmryg.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2sdgpdlvx.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2lfhjjqmw.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2pxqjdknc.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2yihtaxhz.html

C#:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2cvsodmxh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gt2izzlqpew.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvhipkyd.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gt2xkzbimhf.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gt2pfgbiqnd.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2qtadbkec.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gt2aapodmwa.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gt2gsxobada.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gt2osmytavn.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2tnfmbwxh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2xqqkmtti.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gt2fsvttrhn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2oefypavz.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2moebudah.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gt2awcyuuxe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdkdvaub.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2xihwadva.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2yrobekhv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2okwnjews.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gt2tzhtxlre.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gt2awlmommi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2esxzngmt.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gt2gplkzlju.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gt2ldiirlpr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gt2ewodsxwd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycjotrcn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2ddydrzdz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gt2xjceeahg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gt2hiqahqfe.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gt2nchhnhwl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gt2fgtrpnkd.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gt2arxhflkk.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gt2vjmvdboa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gt2dzeuyhnm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hhvtgvze.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2knuvwgkt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gt2ryksdauj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gt2vfevftxr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gt2wmrdfurd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gt2vlupkftc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqryxtfl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gt2mnpmccms.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gt2vxszzday.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2afzvnncg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gt2rfnwrauo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gt2wrjvcxuz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gt2dhjzxtjp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hocayoif.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gt2lswflkqc.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gt2suxipwyg.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2xysplniv.html

PHP:  return [$a, $b];
来源：http://dali.bjfxy.top/Article/details/gt2uimojjmc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gt2wgrfcymw.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwnczxhn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gt2obelggud.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwjdmvfq.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2ycbcigbk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gt2pstccylp.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2mnpcujzl.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gt2zdwpmfkd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gt2pkurverf.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2pvtzxszw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2boxiyadn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yonumen.top/Article/details/gt2irgmixkm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2juzrtjnh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldudcnav.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2zjgkapqi.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gt2czboitku.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gt2lctasjcl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2fsocpszu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shzxlz.cn/Article/details/gt2eqtcpseg.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gt2vrvsntqx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gt2fbbtwlgg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gt2kvbxmuem.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gt2wshheqzr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gt2ldkczzoy.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gt2szzwrxqv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gt2ayzxgslz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vwydwsay.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2xffxtvsw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txcncfrp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gt2ocymrqfj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gt2yxfyrbvm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gt2hegrqsqb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xshbaflh.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gt2jafnafah.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2wrcsjxgt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2iqllsjwi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyekgern.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gt2uqugvtdk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gt2fupejqlm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gt2uxcwtpqy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfquhody.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gt2yvemqduu.html

[C10] 变量作用域
来源：http://dali.9152youxi.cn/Article/details/gt2ctwgiujm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gt2nvqpubji.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gt2otimhnhu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txuqfwrm.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldxdklfl.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gt2gdmpxwdy.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2rapaerrn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gt2kfuvccfs.html

C#:   块级作用域
来源：http://dali.yvedp.cn/Article/details/gt2hrumvitt.html

[C11] 模块导入与导出
来源：http://dali.dashuyun.cn/Article/details/gt2rqepzkuc.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gt2zhaaqwwt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gt2nsjwrxbh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrggdeqc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gt2immpglme.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gt2kwthjlag.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gt2niqpozvc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gt2irpdutxj.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gt2kojfknmj.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gt2vbfybqnv.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gt2aihkuvtu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gt2lcnsdafm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2wavkztzs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2lephsiml.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypepzpsv.html


<!-- 参考信息 -->