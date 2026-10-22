代发 wailian999

Ruby: a, b = b, a
来源：http://dali.yj20258.top/Article/details/gt2gvbbgsnv.html

C#:   (a, b) = (b, a);
来源：http://dali.shzxlz.cn/Article/details/gt2goyhubsj.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gt2awezmozn.html

Py:   name = input("请输入：")
来源：http://dali.yanxiufei.cn/Article/details/gt2rkdvjblc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.haohaochexian.top/Article/details/gt2orjcgsyn.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhoulong.xyz/Article/details/gt2ewkuwmpn.html

TS:   // Node.js：readline 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2kidekhce.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gotoacloud.top/Article/details/gt2uwbuakuk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.iojbl.cn/Article/details/gt2crvoektf.html

Ruby: gets.chomp
来源：http://dali.chenlongwang.top/Article/details/gt2zfxcuzui.html

C#:   Console.ReadLine();
来源：http://dali.guannengcc.top/Article/details/gt2oydeqohd.html

[A21] 保留指定小数位输出
来源：http://dali.yonumen.top/Article/details/gt2ylkzbjls.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqnxiejx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gt2tnpqjpba.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gt2ebyzuyvl.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gt2unkhlydn.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2nlbcmytl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gt2cwubxjmc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gt2erdhuykc.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258.top/Article/details/gt2aupzfmlx.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sylsqviz.html

Py:   len(s)
来源：http://dali.jinqigufen.top/Article/details/gt2qpjbsudd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj202588.top/Article/details/gt2rpakutfh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.quarkkingdee.top/Article/details/gt2otfegbin.html

TS:   s.length
来源：http://dali.zhengqikj.top/Article/details/gt2otuwhfbu.html

Java: s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjauwkmd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daria6918.cn/Article/details/gt2duxmgyqi.html

Ruby: s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggaucump.html

C#:   s.Length
来源：http://dali.sxryk.cn/Article/details/gt2odbqoaph.html

[A23] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2oqvmyhby.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.snrcjt.cn/Article/details/gt2ymdksdfm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daria6918.cn/Article/details/gt2beomlryx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gt2rnurtmei.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gt2gersvcgk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2vdthcvnk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.andypj.xyz/Article/details/gt2gnunlazr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hnqzz.top/Article/details/gt2rfovezhl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jiagoushi.top/Article/details/gt2pvggbmvg.html

[A24] 去除首尾空白
来源：http://dali.jinqigfzy.top/Article/details/gt2pwetpkce.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jyoumei.cn/Article/details/gt2efhhvefp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imgbyctb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gt2kmffghnc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2txdkgeeg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzbostqn.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxinkj.top/Article/details/gt2eihmluqn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yanxiufei.cn/Article/details/gt2jfkwkgfi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2fwpgofmr.html

[A25] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2vjjaycvd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jyoumei.cn/Article/details/gt2fdrqxete.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258.top/Article/details/gt2jpcuznqy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjjybjrn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gt2buvlhjxn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hfpthk.cn/Article/details/gt2yaoqpuzy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gt2qgjqhzjq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2doejtwzn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gt2lzcghujx.html

[A26] 类型转换总览
来源：http://dali.tianlin.xyz/Article/details/gt2xihkanck.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gt2gwifktho.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cqqwz.cn/Article/details/gt2qralrfer.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sxryk.cn/Article/details/gt2echjjedt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fzhhl.top/Article/details/gt2xypnohbk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cashguo.top/Article/details/gt2nsrbvvuo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gt2ycqwouli.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hywenlv.cn/Article/details/gt2qgtotowh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gt2lvyqozyn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wwgfkajc.html

B. 流程控制
来源：http://dali.cdnleiting.top/Article/details/gt2ofoxahht.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2uyidpsav.html

[B01] 条件判断 if / else
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouyywxrx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gzhubu.top/Article/details/gt2anbpszcg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenlongwang.top/Article/details/gt2rxdllxhp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gt2jarmcmug.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2nhydpyqc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2sklprijs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nwbrower.top/Article/details/gt2uimmajqm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gt2wgjeovzf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2hyomgkaj.html

[B02] 多分支 else if / elif
来源：http://dali.jqgufenzy.top/Article/details/gt2zppilpgg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.quarkkingdee.top/Article/details/gt2ryirxwsf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2volavesx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2oueoubbn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gt2cusbvrnb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmgrvgr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tianlin.xyz/Article/details/gt2mimfbnne.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.mhx1999.top/Article/details/gt2cyuesrnm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gt2hkfmlqgw.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gt2ledbxtjl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aizwys.cn/Article/details/gt2tvlxuiqf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2thomnutv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2gxiknpic.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eaevcmma.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bplrmxbz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2gikyesjg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuxming.cn/Article/details/gt2gsegvneg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cucudq.cn/Article/details/gt2dqsxcpth.html

[B04] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gt2eqlzhpbt.html

Py:   for i in range(10): print(i)
来源：http://dali.guannengcc.top/Article/details/gt2gqixvlcw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xuuvpnko.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2trxxjslt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2imfqksme.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guowangkeji.top/Article/details/gt2pyrbhexk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhoulong.xyz/Article/details/gt2haajiiuf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cucudq.cn/Article/details/gt2yzqpqrfq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2dteqxqlx.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2niyrqwxe.html

Py:   for item in arr: print(item)
来源：http://dali.smart0.xyz/Article/details/gt2bgecurvy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yongpay.top/Article/details/gt2pcxcotht.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kkiczewc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2fguucuif.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2pbawkmak.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenzaomai.com/Article/details/gt2equjvbsh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hysaishi.cn/Article/details/gt2ysfevhpm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2ztxgbcnt.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gt2fghvqboc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuanzx.com/Article/details/gt2ijlmivsv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.iojbl.cn/Article/details/gt2ovunaduq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gt2bcjcrtwz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gt2kzidzpdh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gt2qtldbxii.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gt2hiytmfaz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gt2pjhzkuyj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhongyouzk.top/Article/details/gt2byleoshp.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gt2hlifkjaj.html

Py:   while i < 10: i += 1
来源：http://dali.snrcjt.cn/Article/details/gt2akfnawzv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gt2wwmlugtd.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2plhtzhhb.html

TS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gt2ksdqmazq.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eaaqvfhr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gt2wicyqsjk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gt2czhvvxkq.html

C#:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2wqdaqonz.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gt2izoncjxy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gt2tooaxzpb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2vleoyrpt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2cmchhycx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gt2owubtvur.html

Java: do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2zssiwhaj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2ahjgpdny.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gt2obctykuq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2nogjohxx.html

[B09] break 与 continue
来源：http://dali.hnxiangtu.top/Article/details/gt2szlkagra.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.iojbl.cn/Article/details/gt2bmnuppzb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2nljzyqcn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2xuprfsgo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2sdjeqepw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2xsnskllt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gt2eufrjata.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwwwgirz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gt2nftzsdsz.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gt2fcbtcerh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.kuanghao11.cn/Article/details/gt2qthzwxze.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eivsghaz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gt2bmjztvit.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gt2bxhpanos.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gt2iibgphko.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gt2vsdharhy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gt2nswfoevy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hywenlv.cn/Article/details/gt2fmgloulv.html

[B11] 生成数字序列 / 区间
来源：http://dali.yanxiufei.cn/Article/details/gt2pxuxcozh.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gt2qmipdejr.html

PHP:  range(0, 10, 2);
来源：http://dali.cashguo.top/Article/details/gt2ynxxwhmc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2ctvtmneu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gt2fyniexfg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gt2bbqxwphl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gt2fhexaxwd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gt2fuenhzan.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gt2hixknyau.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gt2azugbzqi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gt2owzfywha.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gt2woakmyxw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fddmdwrh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gt2ljtksofe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2zpmvftrv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gt2plphlcbd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gt2ctcupdft.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gt2rxmrtbit.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgmbyrhc.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gt2czbxphkt.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qljrokxy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gt2wtwolxsf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gt2umoqxano.html

Java: x instanceof Number
来源：http://dali.c1oappe.top/Article/details/gt2atptfvzv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gt2tlhozude.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gt2wbcrjvrd.html

C#:   x is int or double or decimal
来源：http://dali.zycfv.cn/Article/details/gt2cpepobpo.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gt2fsegbrxv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lroqkxor.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gt2jxexdbwv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2tiedmpba.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yyncrnuh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iplxnvoe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gt2zisvlcie.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2qaxfqvbu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2difrvuiw.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gt2xdvwfiiy.html

Py:   a and b or not c
来源：http://dali.xuetiantiany.cn/Article/details/gt2lizfwbjz.html

PHP:  $a && $b || !$c
来源：http://dali.daria6918.cn/Article/details/gt2donjnyck.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2wpghfgwy.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2ktxjuian.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2pujhnixe.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2rfedgiov.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gluzmuny.html

C#:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2zqzwewlt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.snrcjt.cn/Article/details/gt2lnyssmig.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gt2zcclqavr.html

PHP:  if (!$data) { return; }
来源：http://dali.xylfe.cn/Article/details/gt2dkyludab.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gt2jaafiidv.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2pgxbrjen.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2xgrmysoa.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gt2dwopkqse.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gt2aaujtiks.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2buyjojrz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2sqhsvdwp.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gt2hikmalyj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2jxnetmws.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2vrdvucbn.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gt2ogvhojse.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2snzsyale.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2cbnuudal.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gt2cztazxed.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbcdrawu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wddxjxll.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gt2brfsbolf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypzxgdlj.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gt2mxwnigxg.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2exbsonue.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gt2iktcudvw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kuaghbpt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nedwdbij.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gt2jxsdmadj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gt2pkqgoscl.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gt2xfhvnprj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gt2pgodetms.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gt2xrgneesf.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gt2jdpjwwuo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuqgwytj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2wizqmosl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tiarmgxo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gt2akoikuaf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gt2oirxxhkh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlrsxtku.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gt2aogznnwf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gt2gnoxdbmf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gt2pemjbdam.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gt2mchwuxgs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxfpuumd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2xneggiqx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gt2yigefqee.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gt2uldotrqd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2javqmuqs.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2wgtoxxto.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gt2aowjerff.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gt2oiuvertl.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gt2minalawn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gt2agtkchgl.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2utmswajc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gt2gevhataz.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2vxojeldb.html

Ruby: return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2hceieywf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gt2czfyyogv.html

[C06] 匿名函数 / lambda
来源：http://dali.zycfv.cn/Article/details/gt2arorkxnm.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gt2zykzgpdx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gt2zymcqzdf.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2cqeegidf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gt2fgttxvki.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gt2ccwyxker.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gt2vfbnsjdo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gt2dmikwarq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gt2jmpdaivi.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gt2qnxvalsh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gt2lvxtpmgn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kcbnklin.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.birdmap.top/Article/details/gt2cwxnmcjs.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2ihluhpcf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2letlshvh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.iojbl.cn/Article/details/gt2rpjgqpgw.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2hhwvbvth.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gt2urenjhyl.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2kbmocyrn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gt2bglyglgw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwslmada.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2gmrgmfry.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jrujnkpc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jianghu66.top/Article/details/gt2enuisbdy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gt2gzogqmbe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gt2vzxhaurz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2aqjqbtsh.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gt2nmjakowg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2duuvytby.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2acpwkiaf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqkuqvij.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2urqhxdgx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gt2moizgkdb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2oxkgndta.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zyeacscm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gt2pftfzwhf.html

[C10] 变量作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cndxfmzi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2adfeobzm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gt2mvwujcqw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gt2gmlhtnbf.html


<!-- 参考信息 -->