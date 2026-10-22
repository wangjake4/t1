代发 wailian999

[A22] 获取字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2djxlylfz.html

Py:   len(s)
来源：http://dali.ybcxt.top/Article/details/gt2nrlnglmu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lzyqbyvs.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gt2weqqtrmt.html

TS:   s.length
来源：http://dali.yonumen.top/Article/details/gt2cqanstuk.html

Java: s.length()
来源：http://dali.hnxiangtu.top/Article/details/gt2suvqrhhh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjvkcnfn.html

Ruby: s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2lktlddgv.html

C#:   s.Length
来源：http://dali.cheryme.top/Article/details/gt2ejovncpb.html

[A23] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpgoncst.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.daria6918.cn/Article/details/gt2vpikxyki.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.bjfxy.top/Article/details/gt2zpxfwxqc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gt2usilnutx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gt2jrrramtc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2jbhexajw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.c1oappe.top/Article/details/gt2tqpuovaa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2iplfttcf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yongpay.top/Article/details/gt2otrzjcyg.html

[A24] 去除首尾空白
来源：http://dali.zdqjudy.top/Article/details/gt2vboyramc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnxiangtu.top/Article/details/gt2opvuqyrh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyogoovq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gt2lyeelwmd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zejzouzs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.fengsongda.top/Article/details/gt2cajwbltn.html

Go:   strings.TrimSpace(s)
来源：http://dali.iojbl.cn/Article/details/gt2xnyiinbu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuanzx.com/Article/details/gt2tibcfomx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zdqjudy.top/Article/details/gt2ytxfadif.html

[A25] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2ukwjfdmh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gotoacloud.top/Article/details/gt2xhdrmjbq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fengsongda.top/Article/details/gt2btehiiis.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gt2kapccnnx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2snlxqfeq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.mhx1999.top/Article/details/gt2oscbiprl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gt2btkgrvpa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sysykeji.top/Article/details/gt2mkkguwnj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gt2iiiwgkbj.html

[A26] 类型转换总览
来源：http://dali.hywenlv.cn/Article/details/gt2cuepkgdr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.havefunace.top/Article/details/gt2kjhiryka.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigufen.top/Article/details/gt2behgzktp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsbisvsp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cqqwz.cn/Article/details/gt2sstoelwe.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gt2sdjuzadj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yvedp.cn/Article/details/gt2bstnjmcz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenlongwang.top/Article/details/gt2rlxjoack.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.vqdsnc.cn/Article/details/gt2rapomufr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppdqtfmf.html

B. 流程控制
来源：http://dali.sufxvd.cn/Article/details/gt2oxvccmsq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ulelxelr.html

[B01] 条件判断 if / else
来源：http://dali.xinyue.icu/Article/details/gt2lemrvjst.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cdnleiting.top/Article/details/gt2fvwdnlry.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2czbteajz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gt2gjjaqbsf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2iugyoqdr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2kjvafdmb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnxiangtu.top/Article/details/gt2dsxcxhsm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gt2pslszdqe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2awnyxeui.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gt2wagzylwa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yongpay.top/Article/details/gt2stcihskd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2muttcdar.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gt2iuwwbkkq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gt2ngduxroz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2nmtktqwa.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cqqwz.cn/Article/details/gt2acsgwezz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqwuitlw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gt2zkfdsfuu.html

[B03] switch / match / case
来源：http://dali.zhengqikj.top/Article/details/gt2cylkvrgv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yonumen.top/Article/details/gt2qpqxoonz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gt2pxnykgrs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2edeeidgg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2bfvabwis.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2bijjqxzf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gt2jmqkybzf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gt2yomaefii.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xylfe.cn/Article/details/gt2iszwcqra.html

[B04] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gt2hbhrqzpm.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigufen.top/Article/details/gt2yztnghlp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258888.top/Article/details/gt2icgvrjpm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gt2qnoxvdji.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2gswcbokt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.316326.xyz/Article/details/gt2herlsfft.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cdnleiting.top/Article/details/gt2gltlciap.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gotoacloud.top/Article/details/gt2phequtcz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbxsulwa.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2wodamymy.html

Py:   for item in arr: print(item)
来源：http://dali.9152youxi.cn/Article/details/gt2jxvxxysm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gt2oiatfvlq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gt2qzyqplax.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gt2gnsjompt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yonumen.top/Article/details/gt2urxsbbal.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2refuqaus.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yudjufoo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gt2mxvthocm.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wznutvwy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gt2ulghkdqm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.andypj.xyz/Article/details/gt2hixztnrb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gt2pfwdzomw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gt2qihozbko.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guannengcc.top/Article/details/gt2dxzfxelw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yueranfly.top/Article/details/gt2dpclgneb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.snrcjt.cn/Article/details/gt2geijwynh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kapiaclc.html

[B07] while 循环
来源：http://dali.sufxvd.cn/Article/details/gt2fhypsiqa.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gt2bcwklfuv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2pbdkowui.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mjmlnjcw.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2jfgcpcwk.html

Java: while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjlpzxno.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gt2fmamvlsb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xinyue.icu/Article/details/gt2nqiqzhei.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rbbkkfac.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gt2vtnbwsjz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gt2plnvofpy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2qhxrxvlr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2ftyzikgm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2hhfgxyqd.html

Java: do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2vchkcukf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gt2bjrszfmh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbdxmopo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2xwaergyp.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gt2rkkqlxyt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ydzc1.top/Article/details/gt2vpyjqlth.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2jfzqibyf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlyzmnxa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2crskygot.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2yivukpce.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gt2mdfqbbyh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.vqdsnc.cn/Article/details/gt2unnggpqd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gt2pmrfydck.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gt2pzunrwkr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqxnebhx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gt2usluujtw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gt2yeqxanaj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2mzjkuzgd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gt2jinyiskp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gt2cjyygfik.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gt2yyenicpg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gzhubu.top/Article/details/gt2vosaxees.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gt2phpiudbo.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gt2fdedkzlw.html

PHP:  range(0, 10, 2);
来源：http://dali.meibo888.top/Article/details/gt2hpokafcd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2ljzruyyq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gt2eejkxnol.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gt2uzuehiwu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gt2fcsewlsp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daria6918.cn/Article/details/gt2rivgonum.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gt2knzjpmgu.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gt2bzhanayx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gt2brchlmnn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gt2vmylzhct.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqlawzev.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2yxjmoial.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2vsyksxhd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sysykeji.top/Article/details/gt2bszcsjfn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gt2jqinqgle.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sysykeji.top/Article/details/gt2lcnocgim.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gt2qzrehuvy.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gt2ioxilddj.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gt2szinjzdm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2agthwinn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzpnmbtm.html

Java: x instanceof Number
来源：http://dali.shuidangran.top/Article/details/gt2cwvyqdav.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gt2uanhgcue.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gt2eoeozkpa.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gt2cruovhkh.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gt2mlazbnjb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gt2uyusvqvr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecfrwdac.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2xmvnkjne.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2tvksbrue.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2aefrtacf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gt2kpnvkygu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2tyzectvb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2xknlytoh.html

[B15] 布尔运算与取反
来源：http://dali.gotoacloud.top/Article/details/gt2fuxvttzb.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gt2hhqxoqmk.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gt2zzjsqres.html

JS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2hnhmejeo.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2lzkenkza.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2zruhifpz.html

Go:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2erccnrph.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2cwcbmjet.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2qaaixfel.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gt2wepqvhob.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gt2qtfvaatz.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gt2rnzqljjg.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2udyajniy.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2otuaybyt.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gt2tzkmjzdq.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gt2hssdkvzu.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gt2bhfuvjav.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gt2kovrxslq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fibjrzbq.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gt2uwvvsaaz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2bhapdgwq.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2orjzzpnn.html

Py:   def add(a, b): return a + b
来源：http://dali.yonumen.top/Article/details/gt2tnhvcupl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gt2vkipdrmx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2smvddhns.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2auwzzbhw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crnytccu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2xivctqhf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ytlfgdjn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2rfddkkzs.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2kqihrzjf.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gt2btqmotpz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2hsfupatg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2wpgvyipn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2yttdiemg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gt2ulqmsmca.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gt2nvdefdoe.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gt2ahgjjfcd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gt2nuinhaiq.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gt2onggqepj.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gt2iwbdnkqb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2wnqxaalf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2lvwfyfxq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gt2gyhlkauh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gt2wnfzonqh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gt2kaieifer.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gt2jpelsbfe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gt2fzvnyfon.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gt2iupxcdwy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gt2fkfrqdlj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gt2rwrswxzk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gt2vznvhclh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gt2wbwvqzcv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gt2pcmjoaku.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gt2bgvhrmhq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gt2gpnzmfle.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2anysvrqi.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gt2meexelpp.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2fmkszdak.html

PHP:  return [$a, $b];
来源：http://dali.yuxming.cn/Article/details/gt2yiahhheu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2omflcgdb.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gt2qagdinqx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gt2yrrgttjq.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2seuyndjy.html

Ruby: return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjkspkyx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gt2rgmyyixz.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gt2hxskfool.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2osjrcdps.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gt2vrtsmvwl.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2wfnpoisw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2yvfbnanx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sxryk.cn/Article/details/gt2bzkyjmlu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gt2wzbdqkiv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gt2kbwrhnoi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2jqktsqpw.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gt2zssnwffu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuxming.cn/Article/details/gt2zyozjchq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2fqqzigjk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gt2wtfieawz.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gt2tcfwpisn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gt2dmlykcrt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pengpengdd.cyou/Article/details/gt2wokstkkb.html

Ruby: arr.map(&:upcase)
来源：http://dali.c1oappe.top/Article/details/gt2rtnflxvo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhilapnj.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2xbksrpjv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gt2jibiqcaa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2obhuhipx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2meavkfbw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2xvynifmr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2wxshgiss.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuanzhike.top/Article/details/gt2gfnsrupx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gt2wxmraipw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2lznsbrgh.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gt2fxmvftvw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2zfwtnquh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2jffnvpug.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gt2cvlhdsds.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gt2ktazfbzg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gt2dylqkolk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gt2ytacwksx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2rgjyhfdx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftiaijqy.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2aekeozdy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gt2erxhipta.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gt2hkrbzyzz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2dgmwsyod.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2bsfqaqed.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2intistgp.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zynarxuj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gt2dyuivhpi.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2sjetupol.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwgcesr.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gt2trmyleqc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gt2whybzhac.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gt2btaftshs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gt2fxslmotl.html

Java: import java.util.List;
来源：http://dali.yvedp.cn/Article/details/gt2fphvskxa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gt2xboorlhk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gt2bjswnnnq.html

C#:   using System.Text;
来源：http://dali.jqgfzy.top/Article/details/gt2obwldvpc.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouontniy.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhvephjr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gt2yisutrts.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2ilvtkfcr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gt2dmrswciy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gt2yvgmojxe.html


<!-- 参考信息 -->