代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.daxiang520.top/Article/details/gtmtmxutzh.html

Ruby: gets.chomp
来源：http://dali.ehwqpu.com/Article/details/gtyefyawup.html

C#:   Console.ReadLine();
来源：http://dali.hnxiangtu.top/Article/details/gtyihwnfde.html

[A21] 保留指定小数位输出
来源：http://dali.guowangkeji.top/Article/details/gtsgvfteyq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj20258.top/Article/details/gtppkxxszl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gtytgszuot.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gtdxxdrgui.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtthilbuvu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtjvzkrweu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtktyzfkju.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtjmgtovwg.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258888.top/Article/details/gtnknjdiqp.html

[A22] 获取字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtdoecsnkj.html

Py:   len(s)
来源：http://dali.ehwqpu.com/Article/details/gtwlrnjaua.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgfzy.top/Article/details/gtdvdziymk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cashguo.top/Article/details/gtjfonnork.html

TS:   s.length
来源：http://dali.ydzc1.top/Article/details/gtvhikeons.html

Java: s.length()
来源：http://dali.yangfankeji.com/Article/details/gtcvetzsrf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yuanzhike.top/Article/details/gtknllprtt.html

Ruby: s.length
来源：http://dali.zhengqikj.top/Article/details/gtlxtqasii.html

C#:   s.Length
来源：http://dali.cdnleiting.top/Article/details/gtftnvgdas.html

[A23] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtjiuytkwk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtgewkmfln.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhongyouzk.top/Article/details/gtgypjtgws.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtoxmxzbjz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtlxqyirfn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtufaqfnfi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aibaodan.cn/Article/details/gtxzelsxdh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigfzy.top/Article/details/gtiostxtku.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.smart0.xyz/Article/details/gtsxzvrhgw.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gtjvddyjrh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zdqjudy.top/Article/details/gtfottdhpk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yonumen.top/Article/details/gthttrztbr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtblqizjue.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrnvjtjt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgfzy.top/Article/details/gtgcaoxoqx.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgufenzy.top/Article/details/gtyanrqmgl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.svipenyu.cn/Article/details/gtjbulbafj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cashguo.top/Article/details/gtglgsfevw.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvmswckd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gtpmnjkqhf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ybcxt.top/Article/details/gtauiykatx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gttitpayor.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtptllhdqz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gogol.net.cn/Article/details/gtwzrjjpkj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtiwfohaia.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jlsjyb.cn/Article/details/gtmvcmwkha.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gtoqwxsebc.html

[A26] 类型转换总览
来源：http://dali.shuidangran.top/Article/details/gtzghzoqti.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gtdmwtmxtz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuanzhike.top/Article/details/gttggnxbpi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gtdooykkby.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenlongwang.top/Article/details/gtpfsvadai.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtlejwirjb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gtxhsunoiw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pycfn.com/Article/details/gtacfblkkj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.meibo888.top/Article/details/gtyrjgyoey.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtchnficod.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gtwquyzmto.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthgaupyuj.html

[B01] 条件判断 if / else
来源：http://dali.yangfankeji.com/Article/details/gtzbpjaejl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqlmazpj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tanke756.top/Article/details/gtpwjzyneh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtbdmwarvr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtptjafldq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtrarsntlu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tianlin.xyz/Article/details/gtchtdbmae.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sysykeji.top/Article/details/gtniiyuloe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtfippcury.html

[B02] 多分支 else if / elif
来源：http://dali.jinyuanbaomall.cn/Article/details/gteukrwnhv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gtzqlrwgcw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.haohaochexian.top/Article/details/gtpvnrktfi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtbjmqehyu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gthmhuvczz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtpnhwlwvl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ehwqpu.com/Article/details/gtahodkniw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gtnoeuucta.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtmcjmpzsm.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gticwiuitf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gteaxflniz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtkwvmarez.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtitbuyzdj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtjiiikdtk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtvknrlbnq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxinkj.top/Article/details/gtuujwvlus.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.mhx1999.top/Article/details/gtdhxsncik.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtrthpckae.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtbmqcchhi.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gteskywvvp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudltxozv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.iojbl.cn/Article/details/gtyatlwrtq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gtfiwhqcqc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hywenlv.cn/Article/details/gthwfmqijn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258888.top/Article/details/gtixmejmsl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zdqjudy.top/Article/details/gtoahllsua.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gtempefjuh.html

[B05] 遍历数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gtrqkojihd.html

Py:   for item in arr: print(item)
来源：http://dali.daria6918.cn/Article/details/gtyhozjhyk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gthpeighaf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtsdqvbplr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gtuvjpdmrm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfjncjmkc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sufxvd.cn/Article/details/gtggdxtxaa.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtlliuksam.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gtwqwvwtgi.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtpindugjo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jianghu66.top/Article/details/gtmqmqzkgd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdgsebsd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gtdwwbmcze.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gtncltzdyx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sysykeji.top/Article/details/gtymbwzbvl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtdvuuusps.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gtbzzyjqwx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gtwobsyddi.html

[B07] while 循环
来源：http://dali.zhoulong.xyz/Article/details/gtzvyomvmq.html

Py:   while i < 10: i += 1
来源：http://dali.fzhhl.top/Article/details/gtmnluptuv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shzxlz.cn/Article/details/gtkwdwweby.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtblyluhbi.html

TS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtaufzuczk.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtvnubtfsx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shuidangran.top/Article/details/gtfgxasksd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xinyue.icu/Article/details/gtmejjeexq.html

C#:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtxjwzdrht.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gtpisayozg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yvedp.cn/Article/details/gtcayefbaq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtrjoqskei.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtobmimazm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtamydwvek.html

Java: do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtxqcjxurg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.meibo888.top/Article/details/gtjuiikjpk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gtlasmkyky.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtfdinylgj.html

[B09] break 与 continue
来源：http://dali.yonumen.top/Article/details/gtuztiogom.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gteqfegahr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtpxvgqiph.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gteaddxhdl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtbtrxwqeb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjgqdouj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtzmtdgiil.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtwtrpqosd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwpailysl.html

[B10] 遍历同时拿索引
来源：http://dali.sysykeji.top/Article/details/gtjscjdjlm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xziqi.cn/Article/details/gtxkxhzpnx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gtdtpzuvyq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtjrtwctzz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtjshdkuzg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.andypj.xyz/Article/details/gtqyvcqwzv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yueranfly.top/Article/details/gtlychykdy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gtjgasfxnp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.meibo888.top/Article/details/gtoihxsyed.html

[B11] 生成数字序列 / 区间
来源：http://dali.yueranfly.top/Article/details/gtqkjjgrio.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqvviaze.html

PHP:  range(0, 10, 2);
来源：http://dali.ivvv.top/Article/details/gtfxuvdzsu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtnktupdjh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtlztesjbc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gtlyzomefy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtayzqdrkw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtapfkoele.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gtmvxxblvy.html

[B12] 跳出多层循环
来源：http://dali.jqgfzy.top/Article/details/gtvvxxriys.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvplbbgk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guannengcc.top/Article/details/gtpuaeukop.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gtwikjdbzz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtyshylqhg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtdhfrdhbk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gtopsvdpin.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gtbjgrmcvl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gttvwtnsxp.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gtzdoijbfa.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gticblfhgx.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtzkskqwdt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtycliuzkv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtcafxigqw.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtnxnrttii.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtoencijtj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gtyekgghpz.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtikrtgaqm.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gtawbzuyzi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtufxafltn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtpszkadrm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtipfzmrfz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtoabifgyj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcigofzhc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtggvidkzt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtpkxxzpep.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtexqrkfku.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gtschxklaa.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtjfyejbac.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtjogexgjw.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtzetwahgk.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtuzdkqsvf.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbnfxycw.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtmcssxpni.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtnmyfdqkm.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtjiyqwgdp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gthbikxhff.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gtsnvuuihk.html

PHP:  if (!$data) { return; }
来源：http://dali.tianlin.xyz/Article/details/gticmresrj.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtpdpqbiea.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtcohcsemw.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtdvbisgxz.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gtznbjukgl.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtpjwzeaws.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtaqkwzrcj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtltiemfaq.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gthpefzzoo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtifderqvk.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gtqrzetstj.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtqhynkooa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtkmltumtg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtbzaecygb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtrliprizl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwkblobj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gtghfxvncx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtgcncgtnp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gturxvjslg.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gttdecwqsp.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gtfeeidjew.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtohmzzzik.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevhgolxb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtupqbapin.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gtuuklkocq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gtazuptasz.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtkijmnizl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtolqgttak.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gtxxepxwpc.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtufadmfha.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gthyotwcxs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcjoxnksp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtfiaoeycu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gtntwgcmgt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtdqcjjnwq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gtcfymyfnq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtzbwimeyj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gthzflkwdw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtqpkksbpp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtozvoqfuv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyauqjie.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtzejqluak.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gtwjjgdcsc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtdvwujqdh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gttedaixov.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxcrcpjyf.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gtuqqrinco.html

Py:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtpkmjfyzf.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtzeidxbch.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtibqtvenc.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gttivtogei.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gtaejsecbi.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtqhdvtdtz.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtftjcfyal.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gtzmechhod.html

[C06] 匿名函数 / lambda
来源：http://dali.ydzc1.top/Article/details/gtwjeftznv.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gtossvrwph.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gtrysrydql.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtqobwjcqo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtrbphkusu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gtqmmubwzg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtlkcshclh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gtshefwbcc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtqsgdbige.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtvuuahbzg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gteuxueuss.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cdnleiting.top/Article/details/gterjjgbcm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtdptjocst.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtokgxauuj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cucudq.cn/Article/details/gtacwhomek.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gogol.net.cn/Article/details/gtemqusodw.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gtihvfcity.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gtgemlzflw.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtroqjzokc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtqkjkfacc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtdvjddimx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtactjeueg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtaqzerlal.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmtsrwvj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gtjqbfxheo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtvbhvdplh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtcnxhszwo.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtuynujnqs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtbvhyfjbs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrpxrcplf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtrmpnrwru.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gtjswfilob.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtctpijrzy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtdazmivmg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gthyqaoyng.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovafhpmq.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gtgwkvalqn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gtddemgiqf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszbwkdvz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtnowcpjvc.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtlrlnghhu.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtxkbtypgo.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtzqblhybj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtngqrpoef.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gthoxopcqq.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtbpsundji.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gtmdlbqned.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gtpdinqeyf.html


<!-- 参考信息 -->