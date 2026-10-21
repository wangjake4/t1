代发 wailian999

Java: String.format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtfzzimarg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtuqbzstgs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtpqotnbxf.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuetiantiany.cn/Article/details/gtrpiuaeze.html

[A22] 获取字符串长度
来源：http://dali.ybcxt.top/Article/details/gtukocokyq.html

Py:   len(s)
来源：http://dali.jiagoushi.top/Article/details/gtgjynewxx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tianlin.xyz/Article/details/gtamciqfye.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tanke756.top/Article/details/gtqwbjmmoj.html

TS:   s.length
来源：http://dali.dashuyun.cn/Article/details/gteekqyzds.html

Java: s.length()
来源：http://dali.nanxinkj.top/Article/details/gtuuwwmyjl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gzhubu.top/Article/details/gtpqmmgljc.html

Ruby: s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtpvenqvrr.html

C#:   s.Length
来源：http://dali.hysaishi.cn/Article/details/gtovbocpue.html

[A23] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gtguvzgncy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yangfankeji.com/Article/details/gtqagdvvco.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhiwuduotai.top/Article/details/gtahzqqjew.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gtjwbohfaa.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gtuymgfkzl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtfmlvtnrm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daria6918.cn/Article/details/gtfftlpiry.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gteepgyydj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gaohongyu789.top/Article/details/gtiswkbmrv.html

[A24] 去除首尾空白
来源：http://dali.jlsjyb.cn/Article/details/gtnpwvbabz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.daxiang520.top/Article/details/gtwmaaithg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sweek.top/Article/details/gtplofrjxu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtccyepdue.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.9152youxi.cn/Article/details/gtrrarbari.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ivvv.top/Article/details/gtidypoeze.html

Go:   strings.TrimSpace(s)
来源：http://dali.haohaochexian.top/Article/details/gtvqwxirdn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxinkj.top/Article/details/gtbfcrbbvy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtzjsukuxt.html

[A25] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gtnhbxsxva.html

Py:   s1 == s2; s1 != s2
来源：http://dali.pycfn.com/Article/details/gtocogdoiv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.meibo888.top/Article/details/gtytucvbtv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gtmgvvskzw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gtdoinnrxz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sysykeji.top/Article/details/gtrhakzitd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gtlsvucite.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cdnleiting.top/Article/details/gtleopumgn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gthgstjgsx.html

[A26] 类型转换总览
来源：http://dali.vqdsnc.cn/Article/details/gtbssnikjt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtyaubrvwr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yangfankeji.com/Article/details/gtfemsugcd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuanzx.com/Article/details/gtqzsbepjr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuxming.cn/Article/details/gtgkwjxdmm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtzkxyfsoh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigufen.top/Article/details/gtpvqfrjpd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258.top/Article/details/gtmkmwhyai.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxinkj.top/Article/details/gtcbgttbux.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwniekdfh.html

B. 流程控制
来源：http://dali.jlsjyb.cn/Article/details/gtefrujhjk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmenuaivd.html

[B01] 条件判断 if / else
来源：http://dali.sweek.top/Article/details/gtctcqinnb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xinyue.icu/Article/details/gtydmyylos.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gtvzjpzcti.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtrzfaqnia.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtffkwjzxi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtjccpvnzv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zycfv.cn/Article/details/gtdleuouzp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gtxjhaofbk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtjbesgnhg.html

[B02] 多分支 else if / elif
来源：http://dali.jiagoushi.top/Article/details/gtoronkhpa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gtzwxwdgxj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhixingplan.top/Article/details/gtwzzenihc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtlzhqgtmo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtotrpwkzf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtdtegogkl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zycfv.cn/Article/details/gtvkodynsj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnxiangtu.top/Article/details/gtwojfiwqf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtzgddnjgp.html

[B03] switch / match / case
来源：http://dali.cdnleiting.top/Article/details/gtuknaccfr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenjidiqi.icu/Article/details/gtgpvkqmsy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtxdapdxvh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijlkapgx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtcfsrtagi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtmxvzrtjd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtwszqujdh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gtodsveffp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj202588.top/Article/details/gtuadnoodc.html

[B04] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtkegmhazx.html

Py:   for i in range(10): print(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtmeiosdyn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pycfn.com/Article/details/gtghvxhzlm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtadsfdadl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gthudnxdis.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daria6918.cn/Article/details/gtcpkkwyew.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yanxiufei.cn/Article/details/gtnzafcayt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gtblzphwyf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tianlin.xyz/Article/details/gtynfsbyjw.html

[B05] 遍历数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtlrkumyhi.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gtghlqkjxw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cheryme.top/Article/details/gtmeohrkpu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gtoxlgibmp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gttsqpoyui.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ybcxt.top/Article/details/gtvocygccd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhengqikj.top/Article/details/gtuhmyvpky.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gtydnxndqj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gttbfjedst.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gtnukeoxvx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yueranfly.top/Article/details/gtbwfqtaqy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.fzhhl.top/Article/details/gtiyolcjhp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwlxxkupe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtgomerfea.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangdashe.top/Article/details/gtlpnpgmyq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzacqicky.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxmcfubw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenzaomai.com/Article/details/gtvezkukzf.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gtiavqqigu.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gtaisfdihn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yonumen.top/Article/details/gtdrweiaks.html

JS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtvloerezg.html

TS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtilydevkv.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtntwiqeqt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gtcgyohcya.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gttamrytdz.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtkkilbmfz.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gtrisoabba.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuanzhike.top/Article/details/gtwllzvxul.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cucudq.cn/Article/details/gtqzculphh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtqnhlzilc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtgfyqlnom.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtwyvflplp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtuecfglwl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gtttwjtukj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtncrsfvdk.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gtocyjmsaz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gtsnddioqq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtwnhnpaop.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtavwrppua.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtjvrupquf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtrlqdmeqt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gttjghsjzg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gtykpxzbuc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtofrhnjnw.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gtigzdjppt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gtucyjafll.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtplqegvod.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gttfcmyjen.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gtlepnqrhk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gtbcmjwgnz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtbghkbjxx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gtgxlzkxrk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuanzhike.top/Article/details/gtjghyswdm.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gtxbdtfylb.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gtntspvjhh.html

PHP:  range(0, 10, 2);
来源：http://dali.gogol.net.cn/Article/details/gtakexjdmo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtvtdmuwwt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtkgzpyibw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xinyue.icu/Article/details/gtvxoqesls.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzjkixzb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtoytjknsa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtrpbemcqj.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gtfiegicvh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gtrshsmdhc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daria6918.cn/Article/details/gtledklaqc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtfegltzjr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtbxkvprdd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gthkuxgork.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gtfqezuhjy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangdashe.top/Article/details/gtrpvtifqi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtaytjxcno.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtvovflqui.html

Py:   isinstance(x, (int, float))
来源：http://dali.yueranfly.top/Article/details/gtmmgtlrxe.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gtlbzzlzfu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjcjpmkq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gtkfojlere.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtdzkwgnoc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenlongwang.top/Article/details/gtgmrjaztx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtcpidrywp.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gtykrytuau.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtluyvrurv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj202588.top/Article/details/gtgjgdpocy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtynkoxcww.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtxlewixov.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtojdhddjv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtispkxbzv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtkxebcefg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tian-w.cn/Article/details/gtewbwroct.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtjpvymlzo.html

[B15] 布尔运算与取反
来源：http://dali.birdmap.top/Article/details/gtxxlpistd.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gtucwqfcbu.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gtpmpxhadb.html

JS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtxqpnuiga.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtlaljlfel.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtqwqlbd.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtzmbfteci.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtwspjmnuc.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gttmttnchd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtcugoxtij.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gtdnehgueh.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gtnkqxvswb.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gthgbewmvp.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtdhiqcbdg.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtykuvyfml.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetafcxor.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gteoipgzqb.html

C#:   if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gthjvkxdfm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtablmedjh.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gtpvffibls.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthlsqromv.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtorbfwnzj.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtjzurxxmh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtpxipvhbr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtnxmhttpt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxmqmydgz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtmmapzoax.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gtstxmlert.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gttesbewrs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtfviahorc.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtiqhdlsbc.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtlifzthku.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gtjbqqmxkh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtelogghse.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlwrvryd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtusutkjig.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtixdxrisd.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtstcdcrky.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gtjskxyvym.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gtkciqxcuv.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtggzaplni.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gtbozymqri.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtkpcyupcl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nwbrower.top/Article/details/gtciakaogw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtylwrnfca.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtlappmsjd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gthbeexkyt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtztsgqbpy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtbpgghwai.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gtgkxuhmha.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gthvwrlbpy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtxdxueuaa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gtltjcexyi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtxoxiqnyz.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtgktimeul.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtvwgdthhn.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnwyyywrm.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gthcdqciim.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtehzakakf.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtvjtdhhps.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtqvbzisym.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtkxuceweh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gtqpsaffvn.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtcbqdyfba.html

Ruby: return a, b
来源：http://dali.cqqwz.cn/Article/details/gtjjnmubjg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtzbfyqgrb.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gttyjilswy.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gtuicmqwyp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gtvnsebecz.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gthrlhqghw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gtoznfodju.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtovtvagxb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtieqgyhxe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtzpmzcmnc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtbuxwrldd.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtkpfnwwbt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenzaomai.com/Article/details/gtkgirzbys.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtiakjsnbo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gttuqrzqun.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvcdrwps.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtbejeicrc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gtkocqueva.html

Ruby: arr.map(&:upcase)
来源：http://dali.yongpay.top/Article/details/gtjknijcoh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gtswzvcvwm.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtdbxinjxp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtieicuh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gtadjuqant.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbxscwwju.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqednbdc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gtdjhzuipp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gtevhdnlnr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtcenxaovk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtcoblpepo.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gtsvcicsvm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtvznxtjdj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gttpkfahvq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtdgozouxb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtlqzmnpey.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtcjfvytae.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hongshengwenyu.top/Article/details/gtrixwazfd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtfvzlidgn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gthnofchqj.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gtgmlddldz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gtpzovcbte.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gtthcgvwys.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtjcvkgdcv.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gthppmwork.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtakwzsuuz.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxxwdazw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtbpyixune.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtzqrufnuk.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gtpdkcxrhs.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gtdrnjmaxm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gttntyghsk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gthrxavryb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtplbejpou.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gtcxrejgku.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gtqcgptmco.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gtouzrzbua.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gteaypogox.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gtjqxfmcsf.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gttptcxygn.html


<!-- 参考信息 -->