代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.svipenyu.cn/Article/details/gtsnaosagr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.c1oappe.top/Article/details/gtjwnizsao.html

TS:   // Node.js：readline 模块
来源：http://dali.kuanghao11.cn/Article/details/gtomxuhnzc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinqigfzy.top/Article/details/gtxczwzude.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.mhx1999.top/Article/details/gtdpihuafv.html

Ruby: gets.chomp
来源：http://dali.zhixingplan.top/Article/details/gtkupgybwc.html

C#:   Console.ReadLine();
来源：http://dali.hongshengwenyu.top/Article/details/gtgewayicv.html

[A21] 保留指定小数位输出
来源：http://dali.pengpengdd.cyou/Article/details/gtlozcbwpq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.andypj.xyz/Article/details/gticjruybu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtcxtvlzlb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtobggscsw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtdetaxrjd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtkeydjqam.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gtemxexvov.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtywmrgmdd.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuanzx.com/Article/details/gtzfrfftyn.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtuwsyzfsf.html

Py:   len(s)
来源：http://dali.ybcxt.top/Article/details/gtlluifite.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.316326.xyz/Article/details/gtucmknbkv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nanxuanxn.top/Article/details/gtywrcxjal.html

TS:   s.length
来源：http://dali.haohaochexian.top/Article/details/gtnczzfwgv.html

Java: s.length()
来源：http://dali.jiagoushi.top/Article/details/gtdixfplol.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.haohaochexian.top/Article/details/gtpkjphzlk.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gtfmlqogri.html

C#:   s.Length
来源：http://dali.yvedp.cn/Article/details/gtlrivkajx.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtbuplbpwn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaihncbbq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hywenlv.cn/Article/details/gtbmttredw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gtmqecnpun.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtdopqgddk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gtwglkqlcd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuxming.cn/Article/details/gtlwzfagdh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sysykeji.top/Article/details/gtqvtveqrm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj20258888.top/Article/details/gtwsledgsr.html

[A24] 去除首尾空白
来源：http://dali.havefunace.top/Article/details/gtvasadpfd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xylfe.cn/Article/details/gtkmlkrvka.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gaohongyu789.top/Article/details/gthzplyutd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gtwsmrhgjc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.havefunace.top/Article/details/gtjdrmvuyp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenjidiqi.icu/Article/details/gtctkqrbvs.html

Go:   strings.TrimSpace(s)
来源：http://dali.ehwqpu.com/Article/details/gtrivtdweb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gtihewirws.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtxvmbbigd.html

[A25] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtnzwgkuye.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dashuyun.cn/Article/details/gtyogtzkvk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gtdtdlwulk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gttbwautef.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gtaovvpuiu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ppjwa.cn/Article/details/gtsujgrett.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtdrpownxq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.guowangkeji.top/Article/details/gtdjmwnxgy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gtjvguiseu.html

[A26] 类型转换总览
来源：http://dali.cheryme.top/Article/details/gtujtjsrjr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.feifeiyinyue.top/Article/details/gtrldnfytn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuanzx.com/Article/details/gtlqiufdeb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cheryme.top/Article/details/gtzacwhkdx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzxwltee.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gtbkktktnd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ppjwa.cn/Article/details/gtzpgqjptd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenzaomai.com/Article/details/gtqvtjvomd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtiewaoqrd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnkupehxt.html

B. 流程控制
来源：http://dali.sxryk.cn/Article/details/gtejhdlqlx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtidystgzb.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gthpslsyio.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangdashe.top/Article/details/gtadyosbpe.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xinyue.icu/Article/details/gtpqosqobn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtimaiiqkj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsxldtjr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtggtmqiwm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenzaomai.com/Article/details/gtmyuolhcj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cheryme.top/Article/details/gtxrkgxcly.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gteyktnpaa.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gtabtavegz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xylfe.cn/Article/details/gtvmikmkpy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gtoaohkdch.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtaepspowy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtvnvqztdd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtbucgeuqv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dashuyun.cn/Article/details/gtghlxhwgv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ivvv.top/Article/details/gtxvrzzsxe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gtlmuthjpj.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gtzzxmziab.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.daria6918.cn/Article/details/gtobkypbog.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtowvvchfg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtguimqdhf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtppxmlujc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtctbmbjgl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.smart0.xyz/Article/details/gttsqdsmgm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinqigfzy.top/Article/details/gtfmsvcrcj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtxfqwskff.html

[B04] for 计数循环
来源：http://dali.9152youxi.cn/Article/details/gtnkwsgiyi.html

Py:   for i in range(10): print(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtwiuzindy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gtiyduzzmy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gtsbhndrrd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gtjnufahfq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gtczhwlcsn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gttsxccbgg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gtwfaudkpv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtanieqrzw.html

[B05] 遍历数组 / 列表
来源：http://dali.c1oappe.top/Article/details/gtgqbynlzm.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigfzy.top/Article/details/gtlktwkhay.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gtxhzoqyfr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtpgtifudk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gtfsxnxiis.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gtpzgmjgho.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gotoacloud.top/Article/details/gtdziioums.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtfsociivs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gtzgivdpjv.html

[B06] 遍历字典 / 对象
来源：http://dali.ehwqpu.com/Article/details/gtnxtfwyvv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.kuanghao11.cn/Article/details/gtsaedlmiq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258888.top/Article/details/gtkwoofjnc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gtgywnwpcu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjsvjjyx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkfpiytsr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtbsmcujsc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ydzc1.top/Article/details/gtfemhpzti.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gtctzswucq.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gtzazamkts.html

Py:   while i < 10: i += 1
来源：http://dali.jianghu66.top/Article/details/gtqudydczw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jiagoushi.top/Article/details/gtxadzwfcs.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtylhlrvfj.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtiompdovk.html

Java: while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtskxlsxsv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuxming.cn/Article/details/gtsfzolotl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fengsongda.top/Article/details/gtnmilvbgn.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtawvljpdb.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtipuvkqoe.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gtejqosabr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hfpthk.cn/Article/details/gturmtelnn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuomyyvtf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtuwtpjwvw.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtqrzqkamw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gtpgazkrbj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtyymzaxvu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtonbgngia.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtajipsbkn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtvfrjdnze.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtmnerljoc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gteohzkcon.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtsdbhnfmq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtljvoyrbn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtvtmwwvvi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gtufvktbzi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtpuvfkenx.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtrhhsdvqb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sysykeji.top/Article/details/gthqqhlswu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gttznwakcm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtedasoccm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtwykyevsh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gtmjjnmdaa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnxiangtu.top/Article/details/gtikuyaakp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gthtwublqx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.birdmap.top/Article/details/gtpcfdogln.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gthprfynmv.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gtmvfiqjub.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtdwrmjsrk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtitgymqcz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtgvmhunmp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtajyhashj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gtshqklfue.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gtwnatgnfh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aizwys.cn/Article/details/gtljjtqdju.html

[B12] 跳出多层循环
来源：http://dali.redwolf501.top/Article/details/gtnjlgshgg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtgvvlztzo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gtlgctwhxr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifvxpfqe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtkznrnjhc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtotitwboi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gtvgomudmt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gtlqgarobt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gtqnrpqihr.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtlktqwhtp.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gthccvaogg.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gtxxghmipi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtfgdixpnf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttwomhcab.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtujepgzgy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigfzy.top/Article/details/gtdyirmfru.html

Ruby: x.is_a?(Numeric)
来源：http://dali.kuanghao11.cn/Article/details/gtpvnlrfiw.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gtitohfagy.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtvvvywaeg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gtdrtadejy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hfpthk.cn/Article/details/gtdnhlfdni.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtniulzzgm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtxdpqwecv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtdoicwmgr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtdkufwsco.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtayqtgfqq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtwkhjsvjx.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtuertcvzn.html

Py:   a and b or not c
来源：http://dali.yuanzhike.top/Article/details/gtqtimqfle.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gtibsvjcyf.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtxccncpdb.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtcdlbbf.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gttivqorqp.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtzcnvjanx.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtozgtcdvc.html

C#:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtwnzxcwha.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtlzumseey.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtlwrrrqwn.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gtunwtoidf.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtjrwpycbj.html

TS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtpglyvcnc.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtooslzrzp.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtyuouiadv.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedafemhx.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtuxglsexj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbyzrltwn.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gtcflcepfl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxgsebhni.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtkspffays.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtuuanyxhn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtvohgbani.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtetdudjky.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtcskfolqj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtgoubdqkn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtvjnbeiuu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gogol.net.cn/Article/details/gtthqmwtyp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gturimlesg.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtayzoqnkl.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtuoepgpuy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gttilyabcl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtmumbvheb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthuomvmdf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtzbatveyo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gtynlfcere.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtdhfsyuda.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gtrywakqld.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtwskopuni.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtkssbrbdt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gtwgqrpyfq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtssrcgpzj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtivdefuwq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gtorpgpfto.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzthqexk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycptnkxi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gthfiisukl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtlyracbvk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtgyhimqgk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtqvwrjmxa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtzzzattwz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gthrycworn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtmnvtfras.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtrppljybr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtmlebhibm.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtcqdqmcsg.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtouhfigmg.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtlhjrgdgj.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtgbsqdvjn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gttzoefowr.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtewkjqxzp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtscircxot.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtaqwlwsdk.html

Ruby: return a, b
来源：http://dali.xylfe.cn/Article/details/gtfclouixi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gttmsianvd.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtdbzzlczz.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtexroznns.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gtclikzlsf.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtzfrkmwcq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtoemcgqsw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtzfivbnav.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtztdrpgwe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gtlfjcckja.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtzarjfrcq.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtgysuvyax.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gtrntcfhuv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gtzopfbuzj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gthfkvgsyl.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtaeswtdxz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtpjpqpvol.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtmxugugwy.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gtskbkjeya.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gthipnoekh.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtwlhjwmnu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gtojwppwwl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daria6918.cn/Article/details/gtpbbyxaco.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtdejhghjt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtnzuudagl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gtzduuecwk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtjselimoj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gtbnafwwdz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtfdbhqngj.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gtiduzyzeo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtgkbgjwgc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtggjjocfo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtvvqjszyr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtmaefmzpl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtzazqaglt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtvyjddgkk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtcekbapdt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtsfcppbyo.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtawmqfrql.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtaqxyytzi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtgbyemmmx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guowangkeji.top/Article/details/gtbgfmdarb.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtgronxtlk.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtgdtcfbkm.html

Go:   花括号块级作用域
来源：http://dali.iojbl.cn/Article/details/gtqjcfhhgu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtlhnllllf.html


<!-- 参考信息 -->