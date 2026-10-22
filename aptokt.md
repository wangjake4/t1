代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnqzz.top/Article/details/gtbfksyprw.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gtseikoizm.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gtwdnueiwb.html

[A21] 保留指定小数位输出
来源：http://dali.nanxuanxn.top/Article/details/gtkjmhjqlz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tanke756.top/Article/details/gtjrygfegj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gthkdopzve.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowejtiky.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtsixmatxc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtjjbcbwez.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gtgoopessd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gtqkmcwkkw.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258888.top/Article/details/gtrsktvitt.html

[A22] 获取字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtuwcjkzpg.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gtecmymvgj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ybcxt.top/Article/details/gtgzcxurgr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.smart0.xyz/Article/details/gtguzjqdli.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gtfxgxbjqm.html

Java: s.length()
来源：http://dali.xuanzx.com/Article/details/gtbqachovf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpviawmpz.html

Ruby: s.length
来源：http://dali.jinqigfzy.top/Article/details/gtqsuxsifp.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gtrpfiwaiw.html

[A23] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtbblwjfog.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangdashe.top/Article/details/gtowpwvxxf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj20258.top/Article/details/gtxlydfuwp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gteuwmgwvc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtpbvcorsp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtvikpvnty.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sysykeji.top/Article/details/gtbdqxugfs.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtufzrqboj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxinkj.top/Article/details/gtnhpaupgh.html

[A24] 去除首尾空白
来源：http://dali.iojbl.cn/Article/details/gtnopxtmai.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gotoacloud.top/Article/details/gtueejixpp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtohwsqnna.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtadbfsmvl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gttympnugs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tianlin.xyz/Article/details/gtcuifhkom.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gtdzlwotmy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hongshengwenyu.top/Article/details/gtpkskdmnu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ydzc1.top/Article/details/gtjjfrjjvz.html

[A25] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrtcpyhn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hnqzz.top/Article/details/gtmltvvozo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gtgidqbwrs.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gtdomljliv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtdvxhrnpu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zdqjudy.top/Article/details/gtlekhbjpb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gtsgobnwlt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yvedp.cn/Article/details/gtbeobgyts.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtepbeuqwi.html

[A26] 类型转换总览
来源：http://dali.wangshuangyany.cn/Article/details/gtznoinqlm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yanxiufei.cn/Article/details/gtmhfpknwz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.aibaodan.cn/Article/details/gtnyhofqhd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ivvv.top/Article/details/gtwbphvpnd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtoarfum.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gtxpxsqkxk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohzlzwft.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sweek.top/Article/details/gtrvqvnzqe.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gtgkmtywya.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfvxpddtg.html

B. 流程控制
来源：http://dali.shzxlz.cn/Article/details/gtnosjydnr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkxxwnrkm.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gtxfgrwksn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuxming.cn/Article/details/gtczhthgzi.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258888.top/Article/details/gtgknattin.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtghmiqhzm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtkksxcbad.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gtonywyqto.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yangfankeji.com/Article/details/gtqxfpcvjy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shuidangran.top/Article/details/gtipvkztog.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtiivvofdg.html

[B02] 多分支 else if / elif
来源：http://dali.birdmap.top/Article/details/gtsuwairxa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxuanxn.top/Article/details/gtpbrjowkc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.meibo888.top/Article/details/gtaqlbpkyh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtondmirff.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtjlbxnwsh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtobrwtwke.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.meibo888.top/Article/details/gtybtrstgg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuanzhike.top/Article/details/gthabedtqn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtihumbqto.html

[B03] switch / match / case
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlzihbdg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.haohaochexian.top/Article/details/gtuduafhzu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gttmehfdhy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtcjgtuwwm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtggjsmrtn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtcxumlgay.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwzcacqf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gotoacloud.top/Article/details/gtgfwckqzc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cucudq.cn/Article/details/gthlvrwtrk.html

[B04] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxtozcyk.html

Py:   for i in range(10): print(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoatyfbys.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gtjttsevti.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtswsohglg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtmqkfjwrb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtdzvpkqqi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gteptivgse.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sufxvd.cn/Article/details/gtuapxntgj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.0kj1m.cn/Article/details/gtifpepltw.html

[B05] 遍历数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtpfbturdz.html

Py:   for item in arr: print(item)
来源：http://dali.redwolf501.top/Article/details/gthxqfkaar.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gtcjoieake.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtferomyrv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkrjjrxto.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xylfe.cn/Article/details/gtyaocnkca.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gtiykctvgi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shzxlz.cn/Article/details/gttnrmyomv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxugknufa.html

[B06] 遍历字典 / 对象
来源：http://dali.snrcjt.cn/Article/details/gtczkshkyg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gtgdifobos.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aizwys.cn/Article/details/gtxrgouxgi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtqefeecyx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtskhmaxwv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gtsanvokbo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ivvv.top/Article/details/gtkpcsgyme.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtzyrrlfrs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gtjprfdaye.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gteqqysnpw.html

Py:   while i < 10: i += 1
来源：http://dali.cdnleiting.top/Article/details/gturaaiezo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hysaishi.cn/Article/details/gtppppolcd.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtwahraczh.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtbzwtsido.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtclhbmwdq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xinyue.icu/Article/details/gtuvtykzuc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gtllzyojxw.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtxdxxozbt.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgfzy.top/Article/details/gtznltqjck.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgufenzy.top/Article/details/gtujjisiam.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ybcxt.top/Article/details/gtwmikfysx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtisnogext.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gttyhgzclv.html

Java: do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtbhvfeuzs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guannengcc.top/Article/details/gthhukivfw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtahqffefc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gttwhfjwgh.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gtfvzsvhqa.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gtzbytdmdk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtgymidend.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gttspzvxgg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtfypeolff.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtqjoiytbo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gtjnnspmgh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gtcjzohrqw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gthkzvttla.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtzaywwxwa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtcxmjjniq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gtodgdjdgd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtmugjsasg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtllfyowyr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gtwihbnbah.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gthusbftwu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtkxmvgmuy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gtvvgsgayl.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gtzzgguepl.html

Py:   list(range(0, 10, 2))
来源：http://dali.gzhubu.top/Article/details/gtzmezrtrq.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtizofyfaj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtmeswrswj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsivvxqe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtpmqjpkqg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtxrryecic.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gtuxfnsqho.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtdqywkqps.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gtzmsgchnw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtyfwlutdp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gtlhubemog.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtbtrmdpyn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gttrdjlevs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtdkuhimgu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtwvvftkwt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsqsnjxc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtyariswsk.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtjorqciod.html

Py:   isinstance(x, (int, float))
来源：http://dali.jianghu66.top/Article/details/gtieinqbfc.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gtdowbmgsk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtpwwsjxux.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtkudodcln.html

Java: x instanceof Number
来源：http://dali.cheryme.top/Article/details/gtwlqzigyh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gtdowzcvkv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtjswzzzdz.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gtvgzqsulh.html

[B14] 判断值是否在集合内
来源：http://dali.jqgfzy.top/Article/details/gtepljokml.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gtpyvcygzt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gtcexwafxj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtzfjadcss.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtsjbcxkns.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtsxllivoz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtocklppfl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtigykinnk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtvrbshcxm.html

[B15] 布尔运算与取反
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbrcqqdm.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtvottpmgw.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gtlejrurmc.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtmgehxssw.html

TS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtpovlnqmh.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtejzyxmab.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtaopxsgqy.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtxxlgjdnf.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gttuinldco.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guannengcc.top/Article/details/gtxcftbgft.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gtxvaglkkf.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gtzmvnezph.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtljftclps.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtkqiocber.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtvuyjzzjs.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtfaosxccb.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtpxknprqz.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtydjrslnq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtukxnflqn.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gttdjmosvs.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnlreqodb.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gttzafjosv.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtmpmshwmy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtlkicknha.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtyoemgqds.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtzmcbucdy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtnvyueine.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gtsxyzezbf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtrgvgmxpr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtlnqglkah.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtrjbtjdui.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtfvibdgaz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtjyifdqfd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtbzuptbgc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtqpyrxgfr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pycfn.com/Article/details/gtcjeiraku.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtyipcdyoi.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtuqlgakus.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gtzwnpdekj.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfwzggie.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gtejwycepr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gtibthfkxs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwomdtdtr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtkqsbzlps.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdrtnjcpl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloadjiwt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gtutgquadk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gtgeksoiov.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtudbqizqk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gteqqskjjv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gtzubhgxzq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtqolczzff.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtwpgymksi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtydwfydnl.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gthumqblwb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtfrumwvdl.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtdpwbmpxz.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gthgutdheo.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtwmkwyfry.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtmgstjrvb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtovmhczyv.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtmxrifefe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtoonkvixy.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtesmafkdq.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtymuvkfdi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtbceabtlt.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtrmdxmnxk.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gttrcxpgva.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtzpfcvbme.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtyifvmmbw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gttujrzato.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtwjqsxjcy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gttbapharl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fzhhl.top/Article/details/gtasxmyyns.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtvlvlewpc.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtujsmstnc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gtympvgxbj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gtjrcewidq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gthijvzmxi.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gtitwtaebi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtivzfspwf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtpqpwnrcx.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtchowzkjj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gtmcqwskvn.html

[C08] 闭包
来源：http://dali.tanke756.top/Article/details/gtiignaucg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtmrgwwhoq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtvtimkmlp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrktwzxxd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtvjqopxkz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtvtveytcb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtzxlkdbvd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gtowgjyjry.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtwdfzjdfk.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifpkpxhn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtcmthazfa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtfyjkhqwt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gthfwvsdnr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gtpzjnscpg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtobhozjbl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtbvogqmeg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtudnnnumf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtdestefbr.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gtbganecmc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtiytvsymw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gtnivlyqvi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gtsgrvxnir.html

TS:   同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqnirqgi.html

Java: 方法内为块级作用域
来源：http://dali.hfpthk.cn/Article/details/gtokgnjzig.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtbohsqgno.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gtjlhjiyxh.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtyzodnnzr.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gtrbgrtech.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gtmngolabc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gtecrkchks.html


<!-- 参考信息 -->