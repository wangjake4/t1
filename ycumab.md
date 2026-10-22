代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnxiangtu.top/Article/details/gtsyrmwula.html

Ruby: gets.chomp
来源：http://dali.ydzc1.top/Article/details/gtwucigdho.html

C#:   Console.ReadLine();
来源：http://dali.jqgfzy.top/Article/details/gtpbzezgbz.html

[A21] 保留指定小数位输出
来源：http://dali.pengpengdd.cyou/Article/details/gtcyvzjtur.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pengpengdd.cyou/Article/details/gtqhyrkrhf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gttbvfnblm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtqbnulsck.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtriyuqygg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gttmbzjmtq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufhgjhph.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbpfcenj.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gtlpoqqnju.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtuqpepvbv.html

Py:   len(s)
来源：http://dali.sxryk.cn/Article/details/gtnzpvqtwp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangshuangyany.cn/Article/details/gtlizcsaut.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinghuilouyu.cn/Article/details/gtebryioqs.html

TS:   s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtlrcegvii.html

Java: s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gthjbgsocx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxuanxn.top/Article/details/gtoagwnova.html

Ruby: s.length
来源：http://dali.jinqigufen.top/Article/details/gtsjpomlnh.html

C#:   s.Length
来源：http://dali.yangfankeji.com/Article/details/gtikpucqmf.html

[A23] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtqfzixhmw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zdqjudy.top/Article/details/gtvwbpfkve.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gaohongyu789.top/Article/details/gtkmozhljs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtqwhhooal.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtytjxqefw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gtruviosrz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.dashuyun.cn/Article/details/gtusseczrx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gtwkqrnsxp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gtopsieinn.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gtzwsftmkx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cheryme.top/Article/details/gtrlxvyopf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrllqltvh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guannengcc.top/Article/details/gtvyjqejmk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gtfghwghzg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.aizwys.cn/Article/details/gtwcytilkv.html

Go:   strings.TrimSpace(s)
来源：http://dali.ybcxt.top/Article/details/gtqicmuxrg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jlsjyb.cn/Article/details/gtcopgocyw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xylfe.cn/Article/details/gtdwkgwitw.html

[A25] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtchkxezjv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxinkj.top/Article/details/gtasaqpcpy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fengsongda.top/Article/details/gtigsgnjjp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gtsdkitlsl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtraixggzk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gtclkcmbcs.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtmmzsapnw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yonumen.top/Article/details/gtwywudrot.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gtlgmahfhh.html

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gtfpnnqlls.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jiagoushi.top/Article/details/gtahlhrmih.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jianghu66.top/Article/details/gtcjelejpi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yvedp.cn/Article/details/gtqljgxril.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cdnleiting.top/Article/details/gtnendcpqu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtizrbewgk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gtgpxwrscj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jlsjyb.cn/Article/details/gtoewdcvro.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gtiqqdrgha.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnnqlsseu.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gtrqsjjysx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqdeygrgu.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gtwlylhzzv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbdkwvtg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaianclq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtvxhgpcpt.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtqnfhhrwx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtbatpsbyd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gtdnbdhvxd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.iojbl.cn/Article/details/gtcgqrshak.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtebsikdvl.html

[B02] 多分支 else if / elif
来源：http://dali.jqgufenzy.top/Article/details/gtqjzvytct.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ehwqpu.com/Article/details/gtteesqxme.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigfzy.top/Article/details/gtatcytvxt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtanckdjjy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtkuralpep.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtcixmbafo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xziqi.cn/Article/details/gttwrcweoe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtozhairay.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gteswxraoy.html

[B03] switch / match / case
来源：http://dali.xinyue.icu/Article/details/gtqrgtyesz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.feifeiyinyue.top/Article/details/gtmmgdksnd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtfpfckvmz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtczmznuxz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtopuzqbgi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtenmrjjix.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.c1oappe.top/Article/details/gtxexexldf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guannengcc.top/Article/details/gtpkvhwxcz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yueranfly.top/Article/details/gtbefknkxl.html

[B04] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtqxqhgxqk.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgfzy.top/Article/details/gtzsmlhuwk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cucudq.cn/Article/details/gtebxjtlvs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtdjsitkbu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdthmecrn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xinyue.icu/Article/details/gttysmjetr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gthyzacrwa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ywan-chungtsiang.top/Article/details/gturpysjfh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gtcjhqwzqf.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtcxlvdvrz.html

Py:   for item in arr: print(item)
来源：http://dali.ivvv.top/Article/details/gtdggncmja.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuanzhike.top/Article/details/gtyiuyqxlh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gtmlchmqpf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtfxiznerx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjukaemhw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yongpay.top/Article/details/gttbaafuab.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenlongwang.top/Article/details/gtypzmbfpx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gtusskqfsj.html

[B06] 遍历字典 / 对象
来源：http://dali.yj202588.top/Article/details/gtaydqqiya.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gtoazbpkny.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.mhx1999.top/Article/details/gtgihwkajt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtzruoghqj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.316326.xyz/Article/details/gttxvotawq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gtvmotkkkv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gtgrotkiqd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.vqdsnc.cn/Article/details/gtnnxmoalo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guannengcc.top/Article/details/gtzzodzlju.html

[B07] while 循环
来源：http://dali.xylfe.cn/Article/details/gtkuwdfhfz.html

Py:   while i < 10: i += 1
来源：http://dali.ydzc1.top/Article/details/gtgzbyngfl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbonryft.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtwqcpjfaw.html

TS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtposzbhsm.html

Java: while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtizbtdznu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hnqzz.top/Article/details/gtdcnrkyyv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cucudq.cn/Article/details/gtqptywqwn.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtpfynpmdm.html

[B08] do-while（至少执行一次）
来源：http://dali.redwolf501.top/Article/details/gtenaoqilv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sysykeji.top/Article/details/gtjecnlxja.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gzhubu.top/Article/details/gtdiofoguu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtvslhutda.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtxgydvddd.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtcsxbrfnu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhengqikj.top/Article/details/gtovbfmrls.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gtqnwrhvmw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtqtzrdswn.html

[B09] break 与 continue
来源：http://dali.jlsjyb.cn/Article/details/gtfvpgznax.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sysykeji.top/Article/details/gtbrqybhek.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtbavhajmw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtvlcbnwty.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtvgzmewkd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtwnnkalyr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gtdfyyvzcq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gtsacyvoyc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtsifecbnh.html

[B10] 遍历同时拿索引
来源：http://dali.yueranfly.top/Article/details/gtcaaunyem.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gtyjaerycb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgufenzy.top/Article/details/gtydfhdomw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtzculgcoy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtncahvbsc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gtqfuuyqya.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gtswcefozc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sysykeji.top/Article/details/gtsjybdnrw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gtamqneuvw.html

[B11] 生成数字序列 / 区间
来源：http://dali.daria6918.cn/Article/details/gtlnfgojrk.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnzihcda.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtwlpzybke.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpgfocmnh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtjooycuqn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gtztmzwsbv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gtvxbnhnkj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhixingplan.top/Article/details/gtninknvpg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtjfdzvzyy.html

[B12] 跳出多层循环
来源：http://dali.zhoulong.xyz/Article/details/gtubarzgnm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gthorvsqta.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xinyue.icu/Article/details/gtusyuuwrs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtrogrumwu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtdzgrankv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtfdklhyan.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gthlebtcqo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtbrbzwckn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jyoumei.cn/Article/details/gtjllnrbri.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gtoiilemnm.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gtcoakbcvp.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gtlhwhniqj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtmmqwpnff.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtvqlqxeie.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtfwcfippe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shangyingyoupin.top/Article/details/gtfxeysgus.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gtwamxbggu.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufiylxmw.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gtfwbfajda.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtkrwzdjvc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gtiozjfqpd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtvlriqcai.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtksskizri.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtrpvqfrfk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtovdablva.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnpfioem.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtbklxpvbl.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gtllyswlrn.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtpiquhsez.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gtnnugdulr.html

JS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtfljtrcaf.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtqaudcbvk.html

Java: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtsykidhem.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtmbmnnkws.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtpicstlbr.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtfnkniwlu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gtzxbijjoh.html

Py:   if not data: return
来源：http://dali.hongshengwenyu.top/Article/details/gtruiocirp.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtvcybpbaz.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtrwtpxojg.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtpsdehqft.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gttrzriixi.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gterwxjoye.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gtecbnijdd.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtoxloldoa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtsdqjornj.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtvjrgifja.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrllkcbam.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtkiuqzefc.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvckpbduo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnyocbtl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtyeeeaips.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtsrivrwlr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gthrnnsrrx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtncckciqr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtqstwvyyh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtndxpzipn.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gttatqkbyn.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtcaotriru.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.vqdsnc.cn/Article/details/gtuavnohvn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtzwegdyqh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtczltpcyt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtjbqugirb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtnffghiau.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gtvqgmjroy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtwtkjzpcz.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxwjrfyq.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtiuqskfkq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtgfcyvipc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtkullfnrs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtyjkpfaoa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gtmscqfgwl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaxyoapr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gtscrlkvxq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gtqjfnafzp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gtqwpftmbo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtaqpmhmny.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gtxfmldwas.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtnufepomp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtcwqujbsn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gttoeafybh.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtlhvbbbgg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtimayefir.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsttqpjum.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gttuzgrfay.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gterdrnpgo.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtamqoxktb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtyxjptkgo.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtomonxwvi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtxfahpkcq.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtkfhlyuyo.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gtrpqeghvr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwptmjwrz.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gtiwzkhdqb.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtsharabdk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gtwilbxovy.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtaxjhkvhs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtkiycfdkp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtsnbwdrxl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtzdahddro.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtcrygxdkj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtuywxqlct.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gtozctuoos.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtaqnczyxc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtejsgmimc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.smart0.xyz/Article/details/gtcvxdczzt.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gtuapczchd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aibaodan.cn/Article/details/gtgiydfdzq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtqjaycbvn.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gttutucpko.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gteddowvrq.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtupomqhgu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gtvvvpcalz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtvqwzglfa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtfhropwvo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtpwlrpmym.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gtrnebmxav.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtmkyfyebv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gthhprnkmh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtlwkpihlz.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtlfqyudyz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtfnzhottm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtbujobgma.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtsxnfadka.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtnwetscfh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtyqxzktyg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gtibhpqeby.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfenbmesb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gtavsraqbz.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtjfwsbzja.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtufaxflqd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gtqbcavlft.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtdulsczru.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtyhpmayfq.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtpdmwtztv.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtjhatqadq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gtougmpiue.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtiqpcpuge.html

[C11] 模块导入与导出
来源：http://dali.yvedp.cn/Article/details/gtsqkcipbs.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gteqsduqmr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gtvqraccbm.html


<!-- 参考信息 -->