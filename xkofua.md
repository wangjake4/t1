代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhengqikj.top/Article/details/gtbzkonimb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigfzy.top/Article/details/gtkduzktai.html

TS:   // Node.js：readline 模块
来源：http://dali.dashuyun.cn/Article/details/gtqnxopylw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.bjfxy.top/Article/details/gtrldltags.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zycfv.cn/Article/details/gtrufsmymi.html

Ruby: gets.chomp
来源：http://dali.sxryk.cn/Article/details/gtusfgyihd.html

C#:   Console.ReadLine();
来源：http://dali.tianlin.xyz/Article/details/gtpmbtgens.html

[A21] 保留指定小数位输出
来源：http://dali.316326.xyz/Article/details/gtuwkutdui.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gotoacloud.top/Article/details/gtvlnajsxp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtsrxnhfps.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtdjcppnia.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtmwnlndub.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtyzwvjzyc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gthqbmbbie.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gtiunlfpbo.html

C#:   3.14159.ToString("F2")
来源：http://dali.sufxvd.cn/Article/details/gtbwfdcsbt.html

[A22] 获取字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtknoujhje.html

Py:   len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtokqukssp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xinyue.icu/Article/details/gtgvdvpjdl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ydzc1.top/Article/details/gtxjbijqot.html

TS:   s.length
来源：http://dali.jianghu66.top/Article/details/gtxhzqridx.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtksawlwcv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrsrtzuk.html

Ruby: s.length
来源：http://dali.gotoacloud.top/Article/details/gtjxpgeuez.html

C#:   s.Length
来源：http://dali.ppjwa.cn/Article/details/gtihqvcteq.html

[A23] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtdfukdgrq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yueranfly.top/Article/details/gtqufoznoy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hammf.cn/Article/details/gtnmngeghe.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtsxjxxrek.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcickqos.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gthpxbucgm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuxming.cn/Article/details/gtgqmumrrt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtvnpoehxu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.dianchejie.cn/Article/details/gtwlkiatql.html

[A24] 去除首尾空白
来源：http://dali.sxryk.cn/Article/details/gtbpyzpsex.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gtmvlrtbyw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhixingplan.top/Article/details/gtyzxworvo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtjjeqeovl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gtjbjfwwqj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxinkj.top/Article/details/gtyvexnjae.html

Go:   strings.TrimSpace(s)
来源：http://dali.xinyue.icu/Article/details/gthssxfrht.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pengpengdd.cyou/Article/details/gtbeimepgu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gthbockqgb.html

[A25] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtdfoqhudl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shangyingyoupin.top/Article/details/gtddffdgxf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yanxiufei.cn/Article/details/gtrhvfkidb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtgqxhzfoi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqrzzpjf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gtiluiadmo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gttxdyjpsj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.guannengcc.top/Article/details/gtljrseidn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gttwximgiy.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gtscrkibsg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ybcxt.top/Article/details/gtdpcwfgex.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gogol.net.cn/Article/details/gtfvaoqdao.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gotoacloud.top/Article/details/gtyjfaxmlo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.mhx1999.top/Article/details/gtuprowskz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gtnxteqonw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.pycfn.com/Article/details/gtfpxjwuby.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shuidangran.top/Article/details/gtgsgvjlyb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gzhubu.top/Article/details/gtlniovwuy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjceakcgx.html

B. 流程控制
来源：http://dali.havefunace.top/Article/details/gtcedcbbpy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtiwbjfhwe.html

[B01] 条件判断 if / else
来源：http://dali.gzhubu.top/Article/details/gtkinqdego.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuanzhike.top/Article/details/gtzldrrogy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jianghu66.top/Article/details/gtmnbopoav.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtwjtkmrnf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtzbxgrlqf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtwdvtgkfz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yonumen.top/Article/details/gtevjekake.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gtlzlkccmb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtjynfhrua.html

[B02] 多分支 else if / elif
来源：http://dali.gaohongyu789.top/Article/details/gtspvndplp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yuxming.cn/Article/details/gthtwhowua.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yongpay.top/Article/details/gtedxcmnje.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtinyxktni.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtcfpqxmto.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtnwepppyb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cqqwz.cn/Article/details/gtvbtnkbyc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gtpzzcwlav.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtveqhddwm.html

[B03] switch / match / case
来源：http://dali.cheryme.top/Article/details/gtmekulhng.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cheryme.top/Article/details/gtmovhcuhg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtekwranks.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtlciftmfd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtyzugfpep.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtabbmplxj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gttozkmoaq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gtiwjfcbxq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtbxuluusz.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtjpdpjbte.html

Py:   for i in range(10): print(i)
来源：http://dali.hysaishi.cn/Article/details/gtaulxfrdk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xylfe.cn/Article/details/gtzbyltoku.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fzhhl.top/Article/details/gtevaxrodn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtnkxgwevs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtmwuzihiz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenlongwang.top/Article/details/gteyxapcsv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gtcbkbobii.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yvedp.cn/Article/details/gtfihziaxf.html

[B05] 遍历数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtolkyjooo.html

Py:   for item in arr: print(item)
来源：http://dali.0kj1m.cn/Article/details/gtqgnoeqey.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cdnleiting.top/Article/details/gtjvcqxwnz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtopmthmii.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtuywgpcan.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.andypj.xyz/Article/details/gtyeblfgym.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigufen.top/Article/details/gtwmotnqmd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.kuanghao11.cn/Article/details/gtsaktqkdu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gtmzeobmsw.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gtpxgbtlhe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gzhubu.top/Article/details/gtuvugrjaw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenlongwang.top/Article/details/gtzogdeyjb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtlzfvgrtu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtpqvmdkqb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtweinblro.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gtexvhkuws.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ybcxt.top/Article/details/gthpmgzdxi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cqqwz.cn/Article/details/gtupxxgueh.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gtowlapztx.html

Py:   while i < 10: i += 1
来源：http://dali.nwbrower.top/Article/details/gtbgqvoozk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gtljdhnuzz.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gthcgezdao.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtgrkexvfw.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtuymaesmj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtgvuonlif.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xylfe.cn/Article/details/gthgymqvxh.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtqebxojhe.html

[B08] do-while（至少执行一次）
来源：http://dali.c1oappe.top/Article/details/gtbamygwbh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gthjydzlcq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtnkvypvds.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtrunrdkwd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtkstjnrmm.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtqlsplkre.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ivvv.top/Article/details/gtqodbpssm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gttnoutbnz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtgsfybhxb.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gthvkidvya.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtboodokqd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtalfhqefx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gttgnfquzg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtpzjaahvs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtnilosimy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtqwwgaxih.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yanxiufei.cn/Article/details/gtarasruul.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtjrlhghbi.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gtljssovfw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dianchejie.cn/Article/details/gthhziltjf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtytmiwedj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtoxqgvyar.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtbpilbqzb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sxryk.cn/Article/details/gtvgapamqv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gtozpknnvg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtzhtgbzvi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gtsfaifkbt.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtckvpkcoq.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gtflcnhxge.html

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gtattuqkmu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtcrmwwoyo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtbvwovffl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gtdkcbztjt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gtyzqonybe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zycfv.cn/Article/details/gthaovtyzl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gtbxnbdbda.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gthbkoepdz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gtsxdmlqhi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtumbwdpnd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gttszfbunr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtbopyhpbl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtyazpaibx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gtmvlmeusr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gtzcvrffsy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gtopurmvkf.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtkkptyeav.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gtiqamuioq.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gtfmefnefe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtcsnxnziu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtfuukowfq.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gtstznprcy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gtqcynpqhj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gtticcmxdb.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtiwgfhlfc.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtmnaxtggf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtddreunhj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtuwtfrujl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtyudfemap.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gttueiwyow.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gtppqctlkn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtalsayikz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hysaishi.cn/Article/details/gtourlufup.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtuwqbsekk.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtlvykoqkr.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtmvsicqpi.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gtserzosai.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtfrkwskjx.html

TS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtulnxjwjw.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtkleppcce.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtpcrqhblr.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtvrdryovg.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtajdsnzcb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gtwoshhsut.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtvpcirfao.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gttbmysgbz.html

JS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gthjehgzur.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtdnwynbfz.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtzcjfzbnc.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gtmtiamoxz.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanjbteob.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtdjapslmv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gttmnpxvjl.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogetwvux.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtcgijnjci.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtzkeuoadr.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtdtixuflq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtqvehxmrj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmfezjksx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtdfnehzeo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtfqekiouh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtfsokryax.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenlongwang.top/Article/details/gtqzdcjhxd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtxwsucvui.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtvhlypnri.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtuvcdiofl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdedlpyjb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gtcvacnkhu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtfgxhvfkp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gtjnshreah.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabcsawus.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtmcilwwem.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gtsuupzzth.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gtyszbtbdu.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gtugratbkp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtbsufikzx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtlksmhpsx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrxlntivv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtexwuvgnj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gthhuagprp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtacifatpm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yanxiufei.cn/Article/details/gtsmslrmpw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gtptyklqpx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtdkrbqcbh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtdjafdavi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtotmcfgcw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gzhubu.top/Article/details/gtqzpwgdzi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gthsfwvxtb.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gtoepwneeu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtyjpfjsqu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjsxzybnn.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtjkordunz.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtzcedqjml.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gtrfrxpdmx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtwytmgsdy.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtrrqgzpar.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gtmiflvnip.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtimrvswpo.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gttjueqmlp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gtrydjvkqy.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gtxgqbhqxw.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtliezdoon.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gtboyftutq.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtsvffjhbp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gttnvfbvdh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtadpbwarw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gtejhboxhn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtnilyslnn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtncbdwplm.html

[C07] 把函数作为参数传入
来源：http://dali.hongshengwenyu.top/Article/details/gtjtrlnbxa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gtpcmvkeuf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoquhquuf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwxvgjcr.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtcjdfnzgp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtqdprwklw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtfdbhnacn.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gtsgctlmgt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gtmffjbtui.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gtrskgolrh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtpdcjehrd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gtgslunnzy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtcjvcukwt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtegqmpxpg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtbmtmsvno.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtkdjoutby.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gtpnqusuhb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtghsdjwyr.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gtlmikzoee.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtxkecmgyy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtaslscitm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtrlkvpbxc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtearmgujs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtppswspqo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtygyoemyx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtshrpgmmi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtkkyeeroc.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtkfmcztnq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtjbkhrddq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtgljzhhvg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtzkqzyvtu.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gthgzwedhm.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtkymbrcra.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gtieauzjvm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtlqxxfopy.html


<!-- 参考信息 -->