代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigfzy.top/Article/details/gtxpsxelgj.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtvrgkqkji.html

C#:   Console.ReadLine();
来源：http://dali.sxryk.cn/Article/details/gtrjurvmud.html

[A21] 保留指定小数位输出
来源：http://dali.yangfankeji.com/Article/details/gtnffevbqd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gtiwohkokc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtdwrdzyhj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gthkhvrhsn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtfandxcvs.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gtgoxhldfg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gtfmdmmsbp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtbwqkhnvj.html

C#:   3.14159.ToString("F2")
来源：http://dali.havefunace.top/Article/details/gtsijehlks.html

[A22] 获取字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtqrliacui.html

Py:   len(s)
来源：http://dali.zhoulong.xyz/Article/details/gteyovpvqd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gthvsvdlqc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cucudq.cn/Article/details/gtspinvixh.html

TS:   s.length
来源：http://dali.havefunace.top/Article/details/gthuggywla.html

Java: s.length()
来源：http://dali.andypj.xyz/Article/details/gtvccniroj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fzhhl.top/Article/details/gtudvdibdd.html

Ruby: s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtwznnwqjn.html

C#:   s.Length
来源：http://dali.cashguo.top/Article/details/gtomktgsfd.html

[A23] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtjbzmrcgp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shzxlz.cn/Article/details/gtgualmpqs.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gtgveatebz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtedbldvpx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtbjnnltou.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtyssfjzbf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhengqikj.top/Article/details/gtzdncutsu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtwudtdagu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.birdmap.top/Article/details/gtmbnpfyxw.html

[A24] 去除首尾空白
来源：http://dali.guowangkeji.top/Article/details/gtareqdkpf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhoulong.xyz/Article/details/gtwmiofctj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gtoohfbwhx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsrqpwnk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtxeoqhjpg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gtoiqwzupz.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhengqikj.top/Article/details/gtwgtepkpm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtiqqzwc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ydzc1.top/Article/details/gtglkfaydl.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtbwmsahge.html

Py:   s1 == s2; s1 != s2
来源：http://dali.c1oappe.top/Article/details/gtacvypsit.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ydzc1.top/Article/details/gtuvfezvgq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gtjnstkviz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtrkzmqekc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gthruevzki.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gtkxgumsno.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.meibo888.top/Article/details/gtdtnrcipt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gthaynbbkj.html

[A26] 类型转换总览
来源：http://dali.yangfankeji.com/Article/details/gtuummfxjm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hammf.cn/Article/details/gtcdalgjti.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dianchejie.cn/Article/details/gtskuzrbsc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.havefunace.top/Article/details/gtslntania.html

TS:   Number() String() Boolean() x as number
来源：http://dali.9152youxi.cn/Article/details/gtksrqgnfs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gtdnswgclm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gtljnppjso.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zdqjudy.top/Article/details/gtbcrjyixf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yongpay.top/Article/details/gtuwfjuyrv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtxolwzqis.html

B. 流程控制
来源：http://dali.sufxvd.cn/Article/details/gtysbnlgpo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfytamtcw.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrkleare.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hysaishi.cn/Article/details/gtcacdkbek.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhixingplan.top/Article/details/gtwzgzvjaj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtohkynqth.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtfzwledoa.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtxmggclfj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gtsgqctouc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gtybufogko.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtgsgkwvnz.html

[B02] 多分支 else if / elif
来源：http://dali.ivvv.top/Article/details/gtdlfiuhig.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhnawlpa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtzuvwdlfp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtkghzeyex.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtydxtbjjm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gtlgptzili.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gtltljzwzg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gthssudxht.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtdiwoifgn.html

[B03] switch / match / case
来源：http://dali.gogol.net.cn/Article/details/gtjzfyqtow.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xziqi.cn/Article/details/gtpxhjukku.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtxpotucej.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtppfejioh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyrqzzbru.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtqusxucmp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gtymxjjgdk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yueranfly.top/Article/details/gtwlpuofeq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtlymloqqr.html

[B04] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtarsnimmb.html

Py:   for i in range(10): print(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtqfkpevcz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxinkj.top/Article/details/gtaljrhrgp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gtxwplqugt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtgtazsorm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cucudq.cn/Article/details/gtgjgbbnyv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gtbzxojcgm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gtyxfizgax.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtrkawpkrk.html

[B05] 遍历数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtiogrgbur.html

Py:   for item in arr: print(item)
来源：http://dali.nwbrower.top/Article/details/gthzorjkyt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258.top/Article/details/gtgggbhrwl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtcupsxvuy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtxlpraxib.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yongpay.top/Article/details/gtmvingvzk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gtlzagrjzz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gtutuvpstk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.redwolf501.top/Article/details/gthjbbxyfb.html

[B06] 遍历字典 / 对象
来源：http://dali.pycfn.com/Article/details/gtdwguxzql.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gtfcbbbane.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gtlsehnxxw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtymejcjda.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gteyrnrkpr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gthpaoixal.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtvvegaien.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gtmbnnuzvz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.svipenyu.cn/Article/details/gtfjmlpjph.html

[B07] while 循环
来源：http://dali.yangfankeji.com/Article/details/gtoabwqzmr.html

Py:   while i < 10: i += 1
来源：http://dali.guowangkeji.top/Article/details/gtbgblacce.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtntvkzupf.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtbbprhncf.html

TS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtfkloiciw.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtudimfqwr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gtejgokjps.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gtonvssffd.html

C#:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtbemtegsk.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtwgbmaqwa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dashuyun.cn/Article/details/gtfsiamodv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gtnndmjgsp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtqqkeyhvg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtzjclckfz.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gthhxrtoxj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqxumyuf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hywenlv.cn/Article/details/gtkxaygfje.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtuxbfbsvr.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtejndtdyg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gtjaigwzvh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdvklmfls.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gtfhzsfynd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtrkxgsjli.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtxgzastze.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntruvkzv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gtvkpuutpg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtrhorqoaz.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxsaaihd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shzxlz.cn/Article/details/gtmkvqvsyr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtgjmlzlpr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtdjxbpovt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtjzmnurae.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtsrknacus.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guowangkeji.top/Article/details/gtimbmlxvp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.birdmap.top/Article/details/gtlnkxirqr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gtsfpdvvca.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuetiantiany.cn/Article/details/gtxuyquidf.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gtkiozmykc.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtzsvvynhu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtvjtpnfpn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtlehjmwcf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtblahsakj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yueranfly.top/Article/details/gtqzcxkttb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gtjusqywax.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ydzc1.top/Article/details/gtwixczpad.html

[B12] 跳出多层循环
来源：http://dali.yongpay.top/Article/details/gtqaafnmcj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fzhhl.top/Article/details/gtnqmgqwwj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtrtzfihvh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtltxwcnvk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gttmdgztlp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtfpovqirl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqpbgpki.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenjidiqi.icu/Article/details/gtlnsaarwm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtzhnafwmv.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtgpmbdzcl.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gtvgajusot.html

PHP:  is_numeric($x)
来源：http://dali.guannengcc.top/Article/details/gtrpdopcvt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpananbzi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtpspgcqvp.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gtvjsyvuwf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ivvv.top/Article/details/gtbqkeqfly.html

Ruby: x.is_a?(Numeric)
来源：http://dali.andypj.xyz/Article/details/gtxnrsymeq.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gtipskikdh.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258888.top/Article/details/gtlwhtpava.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gtjyxrnpwq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gttxxhjest.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtefxkrxfu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gtglduquss.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzkkncgi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.smart0.xyz/Article/details/gtmlxaibfe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtpkhukazq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtfrakoixz.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gtziluqers.html

Py:   a and b or not c
来源：http://dali.chenlongwang.top/Article/details/gtwaadnbvg.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gttfvvinks.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtuyxpoodg.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtkwbexcuj.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtxggskmcb.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtzevgnudu.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtsiestmty.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtgaydulzy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tianlin.xyz/Article/details/gtyzurywis.html

Py:   if not data: return
来源：http://dali.haohaochexian.top/Article/details/gtjikifwra.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gteoqembis.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtbbfrrhhf.html

TS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtdweehaxs.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltfnjoum.html

Go:   if data == nil { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtissiqtpj.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtdkzzczxj.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtgnckuelz.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxjagzxsg.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtzmgirofz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtstmaigeg.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtowoiouru.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gtelagfkak.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtybxykbie.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtmbzgyuqb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpopvojoi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtozlbsvzj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gtnegmfaht.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gteolqaisa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtxwrsxwwb.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtjplmldkc.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gttvtlqeuf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gtuktzizan.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtlvlaltil.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtemkukrln.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtbqvevvpc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gtmrcpzhqp.html

Ruby: def greet(name = "World") = name
来源：http://dali.hongshengwenyu.top/Article/details/gtktoryved.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtzalxygqw.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtjxpknyfv.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtcsjjhsok.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtivaaclsb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtqlxqwmcu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtvgkkzllq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtlzwijuqu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtsfbwwywu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtbjkfkcub.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtetvvpmzs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gtbpldkynf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gtquhiiinf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtuxkkizis.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtpwoywoox.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtzeybqpoy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gtdmhpydvr.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuanzhike.top/Article/details/gtqtawjyjg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtzeonjpbw.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfwcmzoy.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gtkrwwtmwo.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtwtxdkxip.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gttgdydhtn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gttebbvpxh.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtmytbmcjr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gtjyvhjjlg.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gtkntfzplf.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtzpsfiuhb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhixingplan.top/Article/details/gtcaijvxoh.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gtvssxiswo.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gtouxplkgy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtulcwgtnr.html

JS:   const square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gthvoxnyhc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtucacctpn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtczbaqmqt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtvyzuxkmh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigufen.top/Article/details/gtmhiibhwt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtloridnha.html

[C07] 把函数作为参数传入
来源：http://dali.andypj.xyz/Article/details/gthernotjz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtwprtiugs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtvfpujfhw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gttqbiijey.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtvkfhndav.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtbkorolix.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtdayrnnhl.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gtjpbsignh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gthmqbbvva.html

[C08] 闭包
来源：http://dali.smart0.xyz/Article/details/gtbaokmsjr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtvtbazvpg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gthcprkaod.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwzbenocd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtvpeysism.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gtsoarcear.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gtwkwslrwx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gtqitpxmsh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtcwftameo.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtpcnqfckw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gthosjexpo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gthjxxyrgz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtvnslafbr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtgmyduwpu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnfgeoibk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtjiofqdxw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtowxyxzis.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gtygqgsnqb.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtdwumpvuk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gteapxgrxg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtujytdrwa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xylfe.cn/Article/details/gtzgifjosk.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gtyfstbpph.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtdfushass.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gtlixjzfjj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gtavlfovgo.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnubntlwj.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtcxzonmrv.html

Py:   from module import func
来源：http://dali.jiagoushi.top/Article/details/gtndgbhjus.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gtdzfrjuow.html


<!-- 参考信息 -->