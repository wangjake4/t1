代发 wailian999

JS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gtubqkzhtg.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtfxudanfh.html

Java: int t = a; a = b; b = t;
来源：http://dali.dianchejie.cn/Article/details/gtlpstzxfp.html

Go:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtvkpozcse.html

Ruby: a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gtcovhthhb.html

C#:   (a, b) = (b, a);
来源：http://dali.meibo888.top/Article/details/gtudrjwdpy.html

[A20] 读取标准输入
来源：http://dali.yanxiufei.cn/Article/details/gtrcjzyqlz.html

Py:   name = input("请输入：")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxxmfrxn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.snrcjt.cn/Article/details/gtnobfecnh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhiwuduotai.top/Article/details/gtgiuooqcc.html

TS:   // Node.js：readline 模块
来源：http://dali.guowangkeji.top/Article/details/gtdbofsgib.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gtrkawtmcm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nwbrower.top/Article/details/gtznjsrgtp.html

Ruby: gets.chomp
来源：http://dali.daria6918.cn/Article/details/gtpgyqoksn.html

C#:   Console.ReadLine();
来源：http://dali.tianlin.xyz/Article/details/gtfixcuyht.html

[A21] 保留指定小数位输出
来源：http://dali.gotoacloud.top/Article/details/gtmgezzskl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.c1oappe.top/Article/details/gtlmmxwruq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtcjikcclz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtynkjzbvb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtfaypykas.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtyyhffheh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtgrdoegkk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtnftvruiz.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgfzy.top/Article/details/gtguadgaeu.html

[A22] 获取字符串长度
来源：http://dali.shuidangran.top/Article/details/gtqdrtpvne.html

Py:   len(s)
来源：http://dali.tianlin.xyz/Article/details/gtslyarodh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdugvydr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gtggltalth.html

TS:   s.length
来源：http://dali.guowangkeji.top/Article/details/gtoauzyaem.html

Java: s.length()
来源：http://dali.yonumen.top/Article/details/gtggmtddcg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gtuykiwvku.html

Ruby: s.length
来源：http://dali.cqqwz.cn/Article/details/gtixfwkoav.html

C#:   s.Length
来源：http://dali.aibaodan.cn/Article/details/gtunqbemij.html

[A23] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gthzyubdkk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cucudq.cn/Article/details/gtsnotfhhq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gtvwpztowe.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtxvastdtx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtltmskiya.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtqomztmqy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtgmidohtm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdxqvsmd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cheryme.top/Article/details/gtuiakqfnv.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gttdwcvmbw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcmpvdhr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shangyingyoupin.top/Article/details/gtompjcmll.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtaxeitnvp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtmfvdlviw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258.top/Article/details/gtqgmmwnzk.html

Go:   strings.TrimSpace(s)
来源：http://dali.ybcxt.top/Article/details/gtjwlyajhs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cucudq.cn/Article/details/gttvhnuuno.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtwqednctg.html

[A25] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtmkrwgfdp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgfzy.top/Article/details/gtfhcmfupt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gtxfuflyxp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gtmxilvlto.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dianchejie.cn/Article/details/gthkreiiqv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.havefunace.top/Article/details/gtewqeorde.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gthxkesbil.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yonumen.top/Article/details/gttmhewubr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gtkfkwloff.html

[A26] 类型转换总览
来源：http://dali.pycfn.com/Article/details/gtdjpqvfom.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuetiantiany.cn/Article/details/gtbmdzxlit.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gtxzvzyrwz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.birdmap.top/Article/details/gtmhriilzk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sufxvd.cn/Article/details/gtghrsncro.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtbafoadtz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhongyouzk.top/Article/details/gtnsgdeapc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hywenlv.cn/Article/details/gthswenyyo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gtxvcndnoc.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwuryvkht.html

B. 流程控制
来源：http://dali.zhiwuduotai.top/Article/details/gtsuhzobiv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gttscljyrh.html

[B01] 条件判断 if / else
来源：http://dali.ybcxt.top/Article/details/gtpmmfqzzq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgufenzy.top/Article/details/gtscuejnnn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtzpaueboy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtcxdduizh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtefgdvwye.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtrjusudac.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xylfe.cn/Article/details/gtmolimkou.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zdqjudy.top/Article/details/gticccnhjv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtbptttewl.html

[B02] 多分支 else if / elif
来源：http://dali.haohaochexian.top/Article/details/gtoiygtrhu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daxiang520.top/Article/details/gttosebdly.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gtcdlvcyyt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtpnsotdpg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtjujxbafv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtxeqgnmal.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hfpthk.cn/Article/details/gtnvkfakxy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.snrcjt.cn/Article/details/gtljdfeooi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtoqpirqwp.html

[B03] switch / match / case
来源：http://dali.pengpengdd.cyou/Article/details/gtmwdntiaj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuxming.cn/Article/details/gtwxfxdlta.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtfevdcoxh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtvcnxpsmf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtjycwizns.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gteofiamsy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtdtyqyxzs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgfzy.top/Article/details/gtqaxmwhai.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gtbdroypjz.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtnyfvvhqj.html

Py:   for i in range(10): print(i)
来源：http://dali.wangdashe.top/Article/details/gtsajmlido.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhengqikj.top/Article/details/gtnstplsut.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtizqsgwjq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtxeeyjokj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gtnzmashtf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fzhhl.top/Article/details/gtgksfyswv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdundbwf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.316326.xyz/Article/details/gtqlskfbei.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyuxtmkb.html

Py:   for item in arr: print(item)
来源：http://dali.chenzaomai.com/Article/details/gtkhjjfzar.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ivvv.top/Article/details/gttdyusozu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbdbcosau.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvdhvpdlo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgfzy.top/Article/details/gtxnbbqhee.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtffisvleq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tian-w.cn/Article/details/gtpnwqsikl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cdnleiting.top/Article/details/gttbcgoubx.html

[B06] 遍历字典 / 对象
来源：http://dali.jyoumei.cn/Article/details/gtqkgysfki.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gtoeqmafyr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gtqowcvmiz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtfyuzjwfz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gtomgpbumb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtroviggxi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gtmqgwcuhq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gtfsxjhnyz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sufxvd.cn/Article/details/gtzxwyfqiu.html

[B07] while 循环
来源：http://dali.guannengcc.top/Article/details/gtksnzuydb.html

Py:   while i < 10: i += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtbizizhvf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenzaomai.com/Article/details/gtihakgfbc.html

JS:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjkriihuu.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtrofywitp.html

Java: while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtwiknqore.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljtmvdpe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gtafqfcycb.html

C#:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtnrfpddvq.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gtqwewulha.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.kuanghao11.cn/Article/details/gttrvryqvv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtwznrvnry.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtgnqwpi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gttrhynzsn.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtnusicnec.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtfnvagzmg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.havefunace.top/Article/details/gteoxfzidx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtltaczhee.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtxcdxqnlh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.smart0.xyz/Article/details/gtihyynoth.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtejcyqudz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtrtzqilmg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtnnmuoqcw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtqkjgtymu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtepzdglhe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fengsongda.top/Article/details/gthhixzqbi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtucsacnlf.html

[B10] 遍历同时拿索引
来源：http://dali.jyoumei.cn/Article/details/gtiajaknee.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gtwfkswjcx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyaqupaa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtopophvbh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtmqbeicmd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gtmluawavv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtzhwxtjmp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhrttxyu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gtiyeqcxuh.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gtsxhppejl.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtthfoxefg.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtvclnrvts.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtugsqlypc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxuivedh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gtchzfkcyy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gzhubu.top/Article/details/gtpaeecsop.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtljqhzcxn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtobpdcqbk.html

[B12] 跳出多层循环
来源：http://dali.cucudq.cn/Article/details/gtxmwadttt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyrareht.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gtkdkawcjt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtdsfxjkfo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtmxatxbqg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtkmigwxyt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gtidxhijgm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cdnleiting.top/Article/details/gtwsxytuky.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cashguo.top/Article/details/gtxxyytmwy.html

[B13] 判断是否为数字
来源：http://dali.gaohongyu789.top/Article/details/gtvftwkgva.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gtpwyvhosn.html

PHP:  is_numeric($x)
来源：http://dali.ydzc1.top/Article/details/gtzawkfzax.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtrginwjga.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtuoscibkh.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtmlruarkk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gtbwrgvzhx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtftdfgyad.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gtjsygqvib.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtomydsulp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtrdftrvdh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtzyoorsgd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtytozavtx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gthnrxvmaf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtrjhisdgw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtxneiroot.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtqnqwrclc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gternzrxso.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gthxgwjcqy.html

Py:   a and b or not c
来源：http://dali.bjfxy.top/Article/details/gtudvomaze.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtasknotos.html

JS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtnvbwujzg.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtcemomcrv.html

Java: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtnykbdqeu.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gterohvuyl.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtsozcwjmg.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtctcoruca.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gtyxdjmaqp.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtktnyjbez.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtqmcdpwtw.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtxxkazheb.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtrjnuofhq.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtomfebzbl.html

Go:   if data == nil { return }
来源：http://dali.tian-w.cn/Article/details/gtamiivcmz.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtbwebhikc.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtupjjzspw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdxglfveb.html

C. 函数与作用域
来源：http://dali.zhixingplan.top/Article/details/gtdegtcwns.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvidxbvwv.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtgsgnvacv.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkfkxfov.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtxjxxjnqm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtndmjxudv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtsxminfxp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtuxelgaoy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gtwelojibp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtsgjlgrzr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtsieqxmbn.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtoobbgytp.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtjwsoycmy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgzpezdig.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyhjkwxzw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtzgcgdmcg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gtdjunbwgv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gtvqyauulb.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gtcabfvjpt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtznjcyclx.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gtdhnolmxz.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gtybfncoqw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtshmhcdsx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtajzfrkqf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtirgpupcr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gticpyouil.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtcgydkmwi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauoyknmg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gthvcoeqpz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gtewikvpez.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gtvtizkhpv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtgoeftzyp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtzolqdrhs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtqifiwwup.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqvpmyuv.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gtnrediuts.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtieejsarc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtvhpwjkms.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtutufjcmg.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtidqmscqw.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gtxhqasbfr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtqtkxtwqj.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtephrijvu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtsiwleycj.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtrddrzjeb.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gtqtlelnwf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtlwxmrnxo.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gtvyxvkmkz.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gtkockdvcx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ydzc1.top/Article/details/gtatxbrcos.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gtlxjpxkqi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gtvmysubux.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gtvfkqwibn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtkjuhbcve.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gttjrejpwf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtifhbyafw.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtfsqdpbbs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtpokpcyjy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtfyhzfalf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xinyue.icu/Article/details/gteoocgyvi.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtuhtaufov.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtffwhjthl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gtpbblastm.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtrvvfdtqd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtlmpuulju.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnrojboo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtzuxwdlya.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gtvlnbbvek.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtlpayrwax.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtylibbpqp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gttfnjjqhv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gttnilnhlv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtiszasxqf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtihjowiwv.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtkukxfurd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtaiphegvq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtyvppkwhg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gtlorzdgmh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtjrjzodoj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gtbvrnkerb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyxypqeu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtjyjyxibj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtncsuepdr.html


<!-- 参考信息 -->