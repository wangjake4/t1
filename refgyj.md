代发 wailian999

Ruby: a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtuncyarzg.html

C#:   (a, b) = (b, a);
来源：http://dali.yueranfly.top/Article/details/gtudjsxrpf.html

[A20] 读取标准输入
来源：http://dali.jlsjyb.cn/Article/details/gtxvgbpyok.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gtzougevnu.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ybcxt.top/Article/details/gtqqgbgsut.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenlongwang.top/Article/details/gtjxkphuyo.html

TS:   // Node.js：readline 模块
来源：http://dali.gzhubu.top/Article/details/gtwywtjpru.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gogol.net.cn/Article/details/gtegxmurxo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gtsuhbmwki.html

Ruby: gets.chomp
来源：http://dali.yangfankeji.com/Article/details/gtbdccvfwb.html

C#:   Console.ReadLine();
来源：http://dali.chenzaomai.com/Article/details/gtskaiiqwl.html

[A21] 保留指定小数位输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtregqufmy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yueranfly.top/Article/details/gtjokbmgtq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtaycakcje.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtarupljpz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtfhmnsnmg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtqshrhvhy.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtyjxvsqcs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtkujucacc.html

C#:   3.14159.ToString("F2")
来源：http://dali.xziqi.cn/Article/details/gtrjwovouv.html

[A22] 获取字符串长度
来源：http://dali.daria6918.cn/Article/details/gtelcpkpqh.html

Py:   len(s)
来源：http://dali.daxiang520.top/Article/details/gtzxfgtekv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ivvv.top/Article/details/gtljlbgzxd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhiwuduotai.top/Article/details/gtdjejsgdc.html

TS:   s.length
来源：http://dali.pycfn.com/Article/details/gtyiddlkko.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gtcfgwqccr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtaynndnnu.html

Ruby: s.length
来源：http://dali.zhengqikj.top/Article/details/gtrgxsukes.html

C#:   s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtporxzexh.html

[A23] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtmlxcphuk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hongshengwenyu.top/Article/details/gtnydlgrzd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenjidiqi.icu/Article/details/gtonyncjnw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gtfkuoihul.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gtrkcrmsjj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtyceiwkrs.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gzhubu.top/Article/details/gtuqpiybeb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yongpay.top/Article/details/gttgvvcjgo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jyoumei.cn/Article/details/gtknbtguwm.html

[A24] 去除首尾空白
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnydyzaym.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gtfvcgaaxu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gtiexootsc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtrwkuafgk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gthnqnejuj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj202588.top/Article/details/gtkvvkqfvu.html

Go:   strings.TrimSpace(s)
来源：http://dali.hfpthk.cn/Article/details/gtlpahjxdv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.svipenyu.cn/Article/details/gtsoymaicy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtptvlezqs.html

[A25] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtnlnxrper.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daxiang520.top/Article/details/gtdofzlmaw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cashguo.top/Article/details/gtnohlzmob.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gtiigqfmmh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtcywqztqi.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtsouhkokg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtcdogfhmg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gtyhgqvwhn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtiwlvsrex.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gtdwbvtapx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gtslbmmkws.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xylfe.cn/Article/details/gtvhymwoul.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cheryme.top/Article/details/gtsdchccxg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.smart0.xyz/Article/details/gttpcrqkkw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkgbgmft.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ehwqpu.com/Article/details/gtkqiorige.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hysaishi.cn/Article/details/gtejcskhbc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxinkj.top/Article/details/gtgefythov.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtydhlyxrj.html

B. 流程控制
来源：http://dali.c1oappe.top/Article/details/gtxmxncrgi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtyrdedyuo.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gttwgyggsg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtmdkxiwev.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.bjfxy.top/Article/details/gtkxqaugeu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtybccqkim.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtsdlqgybk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gteweypwrt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtbclehrez.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenzaomai.com/Article/details/gtqhrsxmte.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtqbtkdgee.html

[B02] 多分支 else if / elif
来源：http://dali.daria6918.cn/Article/details/gtvdceuayb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.feifeiyinyue.top/Article/details/gtwudczbrp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtepfsegpg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtxjtwpuze.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtxseuevrm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtadsygpsz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gtuerguaph.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gttoyxmmej.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtfwipguhc.html

[B03] switch / match / case
来源：http://dali.c1oappe.top/Article/details/gtsxqgaglu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgfzy.top/Article/details/gtoyggxvbb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtvmspuzdd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gttfkhlvll.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtfbyvjfja.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtmiamxarv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtmkzbdhxl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.havefunace.top/Article/details/gtoumkuhto.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtyonozaqp.html

[B04] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtdsizutyf.html

Py:   for i in range(10): print(i)
来源：http://dali.ybcxt.top/Article/details/gtmsutqxog.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtepyyzqvv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxvvlmpp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtgojbzibk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ydzc1.top/Article/details/gtwyecukwj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aibaodan.cn/Article/details/gtzreqjcnt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yonumen.top/Article/details/gtdgpuzucp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yueranfly.top/Article/details/gtxeqhqddj.html

[B05] 遍历数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtualkjmww.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gtvalnzsia.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gtaxiwtogr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gtzgfzgumc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtgskvygqi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgbnwody.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gtcqbcqbdc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jiagoushi.top/Article/details/gtweumhojm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.iojbl.cn/Article/details/gtlhxmebps.html

[B06] 遍历字典 / 对象
来源：http://dali.dianchejie.cn/Article/details/gtobtjcdwi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ppjwa.cn/Article/details/gtpyjiazxm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xylfe.cn/Article/details/gttocydcqf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtzgziwwzq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtlzggsp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gtczrlbofy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xinyue.icu/Article/details/gtddzxxtsu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cqqwz.cn/Article/details/gtjljllzok.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gzhubu.top/Article/details/gtljpbvdlr.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gtnjwiwskj.html

Py:   while i < 10: i += 1
来源：http://dali.daxiang520.top/Article/details/gtitgtscpv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlqanjodu.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtoxyyvmqd.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtxeribmwy.html

Java: while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtrdbysxmw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gtevoljcmw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gtjycccgqk.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtwcewvlue.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gtwjnyqwmv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258.top/Article/details/gtgznjngrg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.c1oappe.top/Article/details/gtckloqoia.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtngwfmwyk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtrwzcvgav.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtmrhduhxm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gtdzuojkgg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtbvwschqr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gthfeqbusc.html

[B09] break 与 continue
来源：http://dali.jqgfzy.top/Article/details/gtfepuarxq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gtfenrvskn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtwjpzeyde.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtzmmuqdje.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtobdwyrau.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtmefhxdve.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gttlkajsiy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shzxlz.cn/Article/details/gtfwbqzrmw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkgdxdea.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gtbxpwjmwu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gtpyiqqpqu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtrvbiejlo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtnfsuojbd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjvixhsh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosplxdxc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gtwyqjgmab.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.birdmap.top/Article/details/gtvtbqqbqw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gtamkbpdmc.html

[B11] 生成数字序列 / 区间
来源：http://dali.cheryme.top/Article/details/gtxmtzwlkv.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtudbunjqk.html

PHP:  range(0, 10, 2);
来源：http://dali.daria6918.cn/Article/details/gteqfwmejl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtzidrixqt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtxjkkbget.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtdhtpcftc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gtbregoica.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gtdzjbwnzy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gtitkmtnlc.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gttrttkhjo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gtfrkqyzxq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gthhgucixk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtzrjjofbf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtoonqhsfx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gthvfozbls.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtkokihaum.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtrzuebluu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtofbqffkx.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gtufgdgwfn.html

Py:   isinstance(x, (int, float))
来源：http://dali.daria6918.cn/Article/details/gtigjxptxu.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gtjfkpzdlt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtkmqbrfjg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtgvzgqipn.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gtzriegmia.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkdkbrcg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gtifhcliix.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gtowlqbkox.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtordphtkq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gtebhcgqvb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gtobgixpml.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtcdqokfdq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtrhlingjv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gttittqqmm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtveokmehr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gttgbqpfwl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtqnftqgag.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtehxqasro.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gtwfysyydz.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtvbxkbfsr.html

JS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtwaqsynwj.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtrnujgpby.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtnfrhwaym.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtsvifnavh.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtrwucproe.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjfwatji.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtybgzrzej.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gtbxphyylg.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gtufbpxajy.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtruxhdtdk.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtnwtypnbu.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtzkxesdps.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gthoqdktym.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtwjnpstrr.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtiupvubzh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtyhjfakvv.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gtxdwsbvpa.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdisogjni.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtkfombdly.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gtsanmfqwz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gttpokdcej.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtgerwlhrt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtivamvkxc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneqckyhz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtqrkocygz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtxfdwjxhs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtmxwzgqfk.html

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gtpydgphqr.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gtfybaqqle.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gthyaziqua.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtwbzlacle.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtqtqgaabo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gtclqdddio.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtvubrnbla.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaqxyjax.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtczuranbw.html

[C03] 可变参数
来源：http://dali.sxryk.cn/Article/details/gtkkthykqi.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gtobnnrdea.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gtikixfmvt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtrtpklvld.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtnizipbrg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gtvyuxaznc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jianghu66.top/Article/details/gtoqbzixxm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtetjgctvx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtnswofiph.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gttrzafzhv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gtqaxweejv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gttkbjulri.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtygrwhzaq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjojwwuw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtdvisqcet.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gttvnoopto.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtqzdatxry.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmzpyjnf.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gttlkwqoel.html

Py:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtseshxpup.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gthuongofs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtthieoxrr.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtulclwahh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gtoeecddcg.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtjikwdiek.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtnaiglycu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.quarkkingdee.top/Article/details/gtybcoxnno.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtxkzqqrqs.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykdkucbc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gthijnjuhe.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtzrdsbojr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gttxihecln.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gtnfurkzil.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtnlbhqdvk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtzxacjghp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtkykjaevr.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gtpnfseuxl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gtxnalzvxe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gtfzzwajbk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtatmeaccc.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtbxezjooj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj202588.top/Article/details/gttcokkrky.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gthrctmaph.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtmbljczvl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtwkpbcljp.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaifbbzq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtvfqyrxjx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtvhzxxnsj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtlocvrpjh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtppdfdjql.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gtegrgcjak.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtnvpzaxpy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtcmgddhut.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqgwtson.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gtxesaircq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtqzzucpxg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneurbuie.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtaxfcgfir.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtwnnhbiec.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtqbnjtcqz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtpqollcwa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtqtitpztf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gtgvdzerii.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gtaexqinaq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gtotyqadqy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtipfdiosk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzfpjlop.html


<!-- 参考信息 -->