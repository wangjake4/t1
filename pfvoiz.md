代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hongshengwenyu.top/Article/details/gtfqhogqyv.html

Ruby: gets.chomp
来源：http://dali.tianlin.xyz/Article/details/gtoiwxzpng.html

C#:   Console.ReadLine();
来源：http://dali.0kj1m.cn/Article/details/gturraavqf.html

[A21] 保留指定小数位输出
来源：http://dali.9152youxi.cn/Article/details/gthnkjdnak.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jianghu66.top/Article/details/gtsxykrcrb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtavmozdmx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnubcotc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtwyhxpnys.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtohuweewy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtcuewwzhe.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtwinmmxlz.html

C#:   3.14159.ToString("F2")
来源：http://dali.jlsjyb.cn/Article/details/gtuilyvcuq.html

[A22] 获取字符串长度
来源：http://dali.316326.xyz/Article/details/gtwmrslmfw.html

Py:   len(s)
来源：http://dali.zhijiandao.cn/Article/details/gtfmcoqcyx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fengsongda.top/Article/details/gtamefkxui.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gtdulghrfj.html

TS:   s.length
来源：http://dali.quarkkingdee.top/Article/details/gtpadmnirg.html

Java: s.length()
来源：http://dali.redwolf501.top/Article/details/gticjbglgk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shzxlz.cn/Article/details/gtujtpouem.html

Ruby: s.length
来源：http://dali.kuanghao11.cn/Article/details/gtezrgqqrx.html

C#:   s.Length
来源：http://dali.cdnleiting.top/Article/details/gtpastcdah.html

[A23] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtogxeblch.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yj20258.top/Article/details/gtlmdldzwk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gtqetziude.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.0kj1m.cn/Article/details/gtfyczrsxj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtvspfzqjn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtlmfxwhlq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fengsongda.top/Article/details/gtcuhssabx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtlpryeqjy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrwbbpbe.html

[A24] 去除首尾空白
来源：http://dali.nwbrower.top/Article/details/gtudrwslgq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shangyingyoupin.top/Article/details/gtoscprqby.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gtonihapyu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gtwwypmmob.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gtjgeexvlv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ppjwa.cn/Article/details/gtrlfsgftb.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gtnpdcrsyu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.aibaodan.cn/Article/details/gtyqzetrga.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtjhxqqtja.html

[A25] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gthjoucucb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gtqvkoitwa.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxzuagyqy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtewanhgpk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gtiskuadau.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtxbkycwhx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gthqvxopdj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhixingplan.top/Article/details/gtakactsxp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gtsgnvvigg.html

[A26] 类型转换总览
来源：http://dali.zhongyouzk.top/Article/details/gtpiyozbpk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258888.top/Article/details/gtjooknkzt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.c1oappe.top/Article/details/gtidyfwoub.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ydzc1.top/Article/details/gtnvonktdv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtxrfymeks.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cheryme.top/Article/details/gtxdexulsu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gteslodjqc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yvedp.cn/Article/details/gtmdvirkcq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gtjjtyxmmv.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrndlhrot.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gtjhqzhdml.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtowomibwh.html

[B01] 条件判断 if / else
来源：http://dali.ydzc1.top/Article/details/gtawafdlwu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuxming.cn/Article/details/gtdhghbjsy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yonumen.top/Article/details/gtvspnuiwe.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtpaxrarcn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxkyfybo.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtfnpbsvsi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nwbrower.top/Article/details/gtzmzdiokj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtjxxatgaw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtvinhdkql.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gtgltldqdw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenlongwang.top/Article/details/gtmwzuzcvr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxglwuozi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtzzbauryk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtsdkrdrpo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtsrhyhcrz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gtdnjcdpgk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dashuyun.cn/Article/details/gtjonsjgcg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtxwbpozzv.html

[B03] switch / match / case
来源：http://dali.jinqigufen.top/Article/details/gtbglsxxtw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gtwnhvsuqx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtzifszwar.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtgodpvjce.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtgrbsolxo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtbaylosjo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtskgspbbx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yvedp.cn/Article/details/gtrgdfbtkm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtdnidwvpj.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtwxwrfkqr.html

Py:   for i in range(10): print(i)
来源：http://dali.fengsongda.top/Article/details/gteiuxtgxl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gtifhnrhyn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gtfgjtmpqk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtvoparwsp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtsmlffeku.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.iojbl.cn/Article/details/gtibozpshp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jiagoushi.top/Article/details/gthblbabtl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aibaodan.cn/Article/details/gtkwewyzji.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gtlcfaialh.html

Py:   for item in arr: print(item)
来源：http://dali.yonumen.top/Article/details/gtonqmziqb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gtnsokvoup.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtfoqekuse.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gtahpprogh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmycrgyoj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtzgrtjynj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jyoumei.cn/Article/details/gttykfcogn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.havefunace.top/Article/details/gttbtmjztj.html

[B06] 遍历字典 / 对象
来源：http://dali.yvedp.cn/Article/details/gttxvkromh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtxvrmetcm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtejcvphdx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtyanlbmhp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtetilyawv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtwuqcovnk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuanzx.com/Article/details/gtqxazfsfc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tanke756.top/Article/details/gtodptkchy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtopzbpmif.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gtlyaqpbnh.html

Py:   while i < 10: i += 1
来源：http://dali.zhongyouzk.top/Article/details/gthweaktek.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtybicznzf.html

JS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtahvzvnit.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthxbvnro.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtdecpyjmw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.vqdsnc.cn/Article/details/gtmgemqfdj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aibaodan.cn/Article/details/gtxnuxzrie.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtlrbrguut.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gtwilkirzu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtdygjybnk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtzkthrtbe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtzyfzehic.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtavrfsbcl.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtqifziofk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gtumudefwo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gtutvdvxai.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gttrzwpvzp.html

[B09] break 与 continue
来源：http://dali.xziqi.cn/Article/details/gtvbgrmdlp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gtveuefpmn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtsggbhrdd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtfwkfjuhw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtfaldqxzt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtfnjkvbec.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtemkbwpyp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.snrcjt.cn/Article/details/gtgzlixroo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtjiunefih.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtnpqcxfph.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hongshengwenyu.top/Article/details/gtckktfijj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtybrmfgha.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtrzmrphmo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtzotxcgxx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjbataaa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtdtbrmoon.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gtbwjghxbz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsrzupog.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtcglphomu.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gtebunckgz.html

PHP:  range(0, 10, 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumlvmtco.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtnqewupiv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtxgocikev.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yueranfly.top/Article/details/gtijwtsobn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gttfgsqghr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.smart0.xyz/Article/details/gtefealkot.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gtppfjzlte.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gtcctgocdg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gtlvwxdxrb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gtcnoqorei.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtkmylxfqw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxcscmew.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtfukvcldy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtldgffiyc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dashuyun.cn/Article/details/gtysvpmrqu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtmkfvtten.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gtqmskwenc.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtolexhlnd.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gtlhhdspcy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gtweecuoyi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtwpzwzusb.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gttzkbpizj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtlczqlloy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.quarkkingdee.top/Article/details/gtzumdkoci.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtixonbsvl.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gtvepmsqhw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtcsbewrmq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtnjwcsdyr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtskhudxub.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtswzoybxz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtwzygjesa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtqqwbitum.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gtpyvcxbvu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtduyzcszi.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gtkupxhman.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlygbfhxk.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gtkggsueir.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtrujxzwiw.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtpstppedd.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtscbljrdp.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtuxicgzyw.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtdsyrsyjx.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtknrjrtzc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtciomfokn.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtiukccgur.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gttzlsqmeb.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtydjvinmx.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gtjmqcrhxf.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtyfmavlrh.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtlipaodmf.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtuetzcqxt.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtuxkzxwqq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtmpkximuu.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtydclsxym.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtglzjiort.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtrrupnrrk.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtbqrlctza.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtdvlbctqx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtdkwtusfl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtuuldbexp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtoblcvuoe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gtlchdbaii.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gtkmwkixix.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtjesyjmzi.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtbplootfm.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtnezjzpzx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmfmwdpbz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtftxltefj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtsztnsfia.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtlzpyxmlc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gtmfgjhshr.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtpmmckobs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gtbcvwhpxk.html

[C03] 可变参数
来源：http://dali.yanxiufei.cn/Article/details/gtaiiirvhy.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gtaecviwus.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtqtidkkqw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gttsrandwi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtyynrmjtd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtpyioxiqp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtlfghhvgb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtveakcqro.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dianchejie.cn/Article/details/gtgitxuaqg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gtdpdvdoqm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gtzsbaprse.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gturylsilb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtrqewwaua.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gtbootwlhg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gtxpivpswm.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtmyfzcxuq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtauqpldce.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gttzgrfmeh.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtmubuaqux.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtxpxznbmp.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtfrdlsjop.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtzuvdlhqs.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtdztnqggu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtcxieyqoj.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtlnqcezsn.html

Ruby: return a, b
来源：http://dali.hfpthk.cn/Article/details/gtcijuwiqn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gtdbbjiaea.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gtemteppiz.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gtkfrwguyx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtivvwcjrr.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtcjcswzcm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtsntpdotq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenzaomai.com/Article/details/gtwykiwggg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gtkxkcykwh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtjcqthxso.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gttkgbifnl.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gtiaoibajy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gtnxvradgk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtuvnsshqr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gtrsococuq.html

TS:   arr.map(String)
来源：http://dali.cheryme.top/Article/details/gtuawyqhyt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtbtazcknz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gtuoppxbgb.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gtsezatzkh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gtoddqccnz.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtymyuxouk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtpnkxodwv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtrkedxgnc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtaqwjdkuu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtodvpigon.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigfzy.top/Article/details/gtizgksocu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtzebpbjuv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtwbqpftol.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gthjrhqhfb.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtgwdvxfjk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtcixdsuyo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gtekhaufii.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtlisxevxd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtyiybojxg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtvzranecn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtvlnpldto.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtxqqmfnke.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gtncnyhwve.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtshplzrme.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gtuuasdkxd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtvkhhichd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjvnsxyb.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtvuxpxbkw.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtvvfimgdt.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtvumuarib.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpxwpuws.html

C#:   块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtsaehtlsm.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtftqmmtsg.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtnvpjfnlv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtdmvwlfsg.html


<!-- 参考信息 -->