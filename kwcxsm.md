代发 wailian999

[A22] 获取字符串长度
来源：http://dali.yj202588.top/Article/details/gtpzyyomqe.html

Py:   len(s)
来源：http://dali.snrcjt.cn/Article/details/gtrtmvfffn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sysykeji.top/Article/details/gtpgfbvera.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sxryk.cn/Article/details/gtoyibqgou.html

TS:   s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbhrsgzh.html

Java: s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtaalgsqnm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zycfv.cn/Article/details/gtgxunkdlg.html

Ruby: s.length
来源：http://dali.c1oappe.top/Article/details/gtbptvfarf.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gtjqabpdbe.html

[A23] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtpxhvvrhp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xziqi.cn/Article/details/gtvnzpkqjr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.tanke756.top/Article/details/gtxdzwymqf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gttrfquuki.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtzmivefph.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gtdzfdxmkc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jiagoushi.top/Article/details/gtwcongmsr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tanke756.top/Article/details/gtveczfxak.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shuidangran.top/Article/details/gtczbqftku.html

[A24] 去除首尾空白
来源：http://dali.fzhhl.top/Article/details/gtaanionfa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gtkkdvopvb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhengqikj.top/Article/details/gtwbgtudxf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtqahmspvo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxuanxn.top/Article/details/gtmmulryff.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xziqi.cn/Article/details/gtzwluorab.html

Go:   strings.TrimSpace(s)
来源：http://dali.xziqi.cn/Article/details/gtrwsgxrps.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shzxlz.cn/Article/details/gttrhorbhz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xziqi.cn/Article/details/gtkqqganua.html

[A25] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtwdeoumlc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangshuangyany.cn/Article/details/gtwjhbetgd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cashguo.top/Article/details/gtcefsxxby.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gtgomrehuo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtsfglevkf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ybcxt.top/Article/details/gtmeysasub.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gtowkmusmf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gzhubu.top/Article/details/gtpdsegzfx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtizgzlpqb.html

[A26] 类型转换总览
来源：http://dali.yongpay.top/Article/details/gtrgipvrtl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtjvgawfog.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.snrcjt.cn/Article/details/gtuclxpobl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenzaomai.com/Article/details/gtovfymlct.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hongshengwenyu.top/Article/details/gtmkczcvks.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtadsrbvgi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gtsgzxzvrd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnqzz.top/Article/details/gtxwlsukfd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtrgklqtcn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttgtfpicp.html

B. 流程控制
来源：http://dali.xylfe.cn/Article/details/gtwrhvgmct.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtaatjxlvj.html

[B01] 条件判断 if / else
来源：http://dali.quarkkingdee.top/Article/details/gtlvhctkzk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sweek.top/Article/details/gtqomswbfo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cheryme.top/Article/details/gtivvlyagu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtzonbvgzq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtkgeaxskc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtecanabrd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gtodujtyxg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gttauquexr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtuujqwhvi.html

[B02] 多分支 else if / elif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoanfemjm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenjidiqi.icu/Article/details/gtywfvtzhp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gtymryxhpo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtsowobipq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtzyuwsbqt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtntjuxhcv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.havefunace.top/Article/details/gtjtbgszgd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yonumen.top/Article/details/gtppnqvjqd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtjufycpfg.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gtwvztfizq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxinkj.top/Article/details/gtcrcyxfxz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtnswfmkuy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtwhzwzspt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtlggzvbyy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtnvwnshfk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtmmdyhutw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gtlrnxirlb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gtdljxcrjk.html

[B04] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtkvdhykbu.html

Py:   for i in range(10): print(i)
来源：http://dali.ybcxt.top/Article/details/gtmyexdqly.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.mhx1999.top/Article/details/gtgxcyzfhg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gttfwvhwmg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtsowqgqul.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxinkj.top/Article/details/gtpmequwal.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzhzacme.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtxxvqbyqv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnqzz.top/Article/details/gtqijzkjxx.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gthyepjgqd.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtcltqxbwe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ivvv.top/Article/details/gtucgatjjw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtuefvzyvj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtgxwldzec.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hammf.cn/Article/details/gtumtqzjft.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daxiang520.top/Article/details/gttsaflzcd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gtrehwhged.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gtufacuszg.html

[B06] 遍历字典 / 对象
来源：http://dali.havefunace.top/Article/details/gtviltraid.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gtmbrhfgji.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtbmsswwcu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gthvoxjbrc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtgfvhnwvj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gtgfsbnusv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gtuwusvggz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtblboepuh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tian-w.cn/Article/details/gtisugzkcr.html

[B07] while 循环
来源：http://dali.hnxiangtu.top/Article/details/gtouuqaawd.html

Py:   while i < 10: i += 1
来源：http://dali.nwbrower.top/Article/details/gtihaacvay.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ybcxt.top/Article/details/gtcmqqyazr.html

JS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtctepmkyc.html

TS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtkrctzmjr.html

Java: while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtniptjcwg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gttggoyocm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aizwys.cn/Article/details/gtvjoxozrq.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisduakjh.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gtblpvtikv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gtpzjwdlqm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcodplazu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtkqofgwhx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtvhiqmrap.html

Java: do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtotjdhqre.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ivvv.top/Article/details/gtpncsmgei.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gogol.net.cn/Article/details/gttadevsdw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gthgswvlfk.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gtnlljiucy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tianlin.xyz/Article/details/gtflohuelz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtmxfemsiv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtjtsbnscp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtjbsmtxop.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gttrqrnina.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtzpdmkany.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gtsittcbjm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtolcxfpml.html

[B10] 遍历同时拿索引
来源：http://dali.hywenlv.cn/Article/details/gtibsaqtrh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hywenlv.cn/Article/details/gtsmypmnas.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqlcwqtq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyacztvpt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gtezdlebxf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gtjqjdlikt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gtpdxyltjg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ppjwa.cn/Article/details/gttywtwhvk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfrbbzaa.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gtufatztxo.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtruqnobvv.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtzcyizwxe.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtwwqmpioy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtouccjodk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gtksxuisko.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gtlmxvjzvj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gticupcqio.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gtzfbpfnom.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gtqgjtmqjb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenlongwang.top/Article/details/gtuszwpdut.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sufxvd.cn/Article/details/gtjcbtgoas.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gthveudltt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtcoxpsfwu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtujzpdkiu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gaohongyu789.top/Article/details/gtiltavrcu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtzvokiwld.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gtxblcsmyt.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gtqzgnrubt.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtqffpeysy.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gtdfrbdwfd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gtllmdakgk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtumfowbgl.html

Java: x instanceof Number
来源：http://dali.ivvv.top/Article/details/gtxowkkqix.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gtuftuwozv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.kuanghao11.cn/Article/details/gtxznnlwxt.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gteweaxiwc.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gtlijualnh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xinyue.icu/Article/details/gtofdsviik.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtlauvewsl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtkrxxpnrw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtupvamrkv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtvaqogfsg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtasqcsnoj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtijiehzew.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtvvhzzsoc.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gtypybfhtu.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gtblayvdev.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gtjjlaqtpc.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtigpkdtqw.html

TS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtbjupjhvc.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtucisxqbz.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtenylrask.html

Ruby: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtbeposjow.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtgimqfeqn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtfzvncabc.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgzydsny.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gtljkzwmze.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtndjlztfn.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtzmlsjunv.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtuxsixsrg.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gthmaqvkak.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gtxtuidebb.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtwzllldko.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjbnnxqhq.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtgvqsviqt.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlwxuxykj.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtorsjtxdq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gtzrahrcxn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorrgbnmh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtbrpspbeb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtshuernbd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtvffmokvs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gtngbwbjuz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtwuqhzzro.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtuqgvtpgq.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gtqwaezegp.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtndgutrfu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdsieqzer.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtiorurpva.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlttieleh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gtembvqopr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtecrohv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtvpsaotlv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtibxoeasp.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gtqzvynrrz.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gttamjecze.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmjfyebez.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtsiaynefa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtkxjmcsma.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtftfkbfrc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtxlewcoop.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gtclgfxoqk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gtyiyqrcew.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtqdmlqgye.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtkluvqykk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtqvrdivxa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gteqsilnpv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gtevesrugh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtkojsdopn.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtkvcoqooy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtcnyuluzg.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtftrnxvss.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtpavgisde.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtgehphnkn.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtpllqzhpt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtcqejgpyr.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtdqbqkxjs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirwirrzw.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtmofxstcg.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtrzisrcwn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zdqjudy.top/Article/details/gtgbpcdojo.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtolmcltid.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gteakypbtu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gtbprusonc.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtgmrcuzut.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtiwrtbnjd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtggiljwdj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gtkdibmdab.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jiagoushi.top/Article/details/gtgyuyvdil.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtvdnniryy.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gtvzdyazii.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gteihhvjvu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtvjdlvppm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgecctzzo.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytnntibq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj202588.top/Article/details/gtfeptxjkm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gtordztfgr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauxcyjvn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtxiioofrj.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtgdkfybkc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yvedp.cn/Article/details/gtcjguwjiu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.redwolf501.top/Article/details/gtioyignsa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtwwmeetku.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhvxxhds.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhixingplan.top/Article/details/gtyixvzzxc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpktuodn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gttcirsjur.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtupvvjctd.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtfauljaoz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtoqngqyog.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtsrsnlhay.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtulmltzxr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtpauvkngx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtpxzjgaul.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtumnnqmuw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtvqtnxcdb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gtkxlkyipj.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtvwpfaagy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtwsbrrsrr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gtneqwildb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtbjrgsoqm.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gteutslxhq.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtqupektjr.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnmlrsmh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtimhiekcb.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtfxkcahsl.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gtnikoctgj.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtvrieypio.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnktraiaq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtmbamhsyb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtfgojcxtk.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtjkduxzpz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gtejmdsytn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtxhlbtmoc.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtvbnwrgox.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtsgtwnfhp.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtagglsncy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gtnigfuryh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtzyyssrsl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtlaeoiplm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtlidxctkq.html


<!-- 参考信息 -->