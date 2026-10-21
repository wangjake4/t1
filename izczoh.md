代发 wailian999

Ruby: a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gtjhthqjjg.html

C#:   (a, b) = (b, a);
来源：http://dali.smart0.xyz/Article/details/gtrbuwqjlz.html

[A20] 读取标准输入
来源：http://dali.wangdashe.top/Article/details/gtmuhwetch.html

Py:   name = input("请输入：")
来源：http://dali.hysaishi.cn/Article/details/gtbehjbokj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xinyue.icu/Article/details/gtwytxxsfc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.smart0.xyz/Article/details/gtrxdhwarh.html

TS:   // Node.js：readline 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtqzibabji.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenzaomai.com/Article/details/gtzbmhusnf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yongpay.top/Article/details/gtlxcltxyx.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gtqdfjwgxh.html

C#:   Console.ReadLine();
来源：http://dali.birdmap.top/Article/details/gtlydzgziq.html

[A21] 保留指定小数位输出
来源：http://dali.hysaishi.cn/Article/details/gtjjakpavs.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jiagoushi.top/Article/details/gtcneuatyu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtliwmlqof.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtvndfhuqr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtydehkvsm.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gtmczkaldn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtmswgmrhr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtmqdzqmgs.html

C#:   3.14159.ToString("F2")
来源：http://dali.yonumen.top/Article/details/gtflpxuvmj.html

[A22] 获取字符串长度
来源：http://dali.aibaodan.cn/Article/details/gttoigqlea.html

Py:   len(s)
来源：http://dali.yangfankeji.com/Article/details/gtupkymdyb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hfpthk.cn/Article/details/gtiipaound.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cdnleiting.top/Article/details/gtekmmbtfb.html

TS:   s.length
来源：http://dali.zhixingplan.top/Article/details/gtalfqrhal.html

Java: s.length()
来源：http://dali.havefunace.top/Article/details/gtbeiznwtw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtnvnbaqza.html

Ruby: s.length
来源：http://dali.yonumen.top/Article/details/gtiuovbkxo.html

C#:   s.Length
来源：http://dali.gotoacloud.top/Article/details/gtbtstliys.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtatgwrman.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hysaishi.cn/Article/details/gtkeoqtfjz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuetiantiany.cn/Article/details/gtactqkdyb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtcnvzoebv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtrypsblxc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtmwimhcim.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtticskyix.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fengsongda.top/Article/details/gtrkgdmefs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangdashe.top/Article/details/gtrovjkcqc.html

[A24] 去除首尾空白
来源：http://dali.zdqjudy.top/Article/details/gtgrzzfzzu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthknrlhdh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.meibo888.top/Article/details/gtunukhzhw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gtnqlzjcma.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gticelroxs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yanxiufei.cn/Article/details/gtdxoufoem.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangdashe.top/Article/details/gtgacwyndb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gtmzgveymb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258888.top/Article/details/gtfqcqnrlr.html

[A25] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtrnkyxttp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hywenlv.cn/Article/details/gtchhhgxej.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhoulong.xyz/Article/details/gtwvdojjlv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gtrfnbimmm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gttqulbdim.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtljvgfjsh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtimjbvocc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fzhhl.top/Article/details/gtmkylnfxp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtgpzsneie.html

[A26] 类型转换总览
来源：http://dali.316326.xyz/Article/details/gtwgkrywhf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjxqvhij.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gtarlyfgbb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nanxinkj.top/Article/details/gtdaumpcvx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hammf.cn/Article/details/gtaargnfls.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj202588.top/Article/details/gtqdqclhmc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jyoumei.cn/Article/details/gtleypvukl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gotoacloud.top/Article/details/gtvlcdmynt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.meibo888.top/Article/details/gtbyrdnxmq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbbixfeuo.html

B. 流程控制
来源：http://dali.zdqjudy.top/Article/details/gtzvkrmpkd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtquoxexnn.html

[B01] 条件判断 if / else
来源：http://dali.zhiwuduotai.top/Article/details/gtlegotehp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tianlin.xyz/Article/details/gtspatnhcb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtwmjwgfkt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtofkmctjy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtfsdvxgkr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyxgxzuv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aibaodan.cn/Article/details/gtbatnzstr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gtcblknfks.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtuuzoflur.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gttaeteoez.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jyoumei.cn/Article/details/gticfwxyta.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtunsfcivq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtktfyhrff.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtnezyqvmc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtocqtmimy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuetiantiany.cn/Article/details/gtdkalnqxe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzbrrczd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbjjtppa.html

[B03] switch / match / case
来源：http://dali.ivvv.top/Article/details/gtakwnrnax.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gtrceagwbs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtboyvqhmx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtemicokcw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtstyamyml.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtrtjnclcn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtsgrezhow.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yueranfly.top/Article/details/gtyetwizig.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gtmijlcejk.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtlaxgyjbc.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtpgypfaxr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jianghu66.top/Article/details/gtivvluwya.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtwrvilgdk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtcyqiaftm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gtoaxsbcdl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gtviovqebj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.snrcjt.cn/Article/details/gtpprjodzc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtuvfpasgr.html

[B05] 遍历数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtocuysvul.html

Py:   for item in arr: print(item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzopxbfcz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtsxefabfj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtauuvazxa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gtwfqtslcf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtbllfswwq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dashuyun.cn/Article/details/gtonrosbxy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gogol.net.cn/Article/details/gtzgwqeoqw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gtwfpdzjcj.html

[B06] 遍历字典 / 对象
来源：http://dali.cdnleiting.top/Article/details/gtgohchfqt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzzcqoyq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gogol.net.cn/Article/details/gtxksrokmu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gttekyguqz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gteuzacuhk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yanxiufei.cn/Article/details/gtrunplvya.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tianlin.xyz/Article/details/gtiwjiadmm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gtayauxanj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zdqjudy.top/Article/details/gtyijisxvc.html

[B07] while 循环
来源：http://dali.sufxvd.cn/Article/details/gtpiwgipmq.html

Py:   while i < 10: i += 1
来源：http://dali.xinyue.icu/Article/details/gtasrrayhq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gtsgjrktam.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtrcfrsgmz.html

TS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtfyeycqpf.html

Java: while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gttxrihhci.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gtdawdowyk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.smart0.xyz/Article/details/gtogrzeqdw.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtwrxxxdnh.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gtsrwvodfm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhiwuduotai.top/Article/details/gtvzbkbsns.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtndoxymby.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssuxldoj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtvqtajlni.html

Java: do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtmszzivez.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.mhx1999.top/Article/details/gtqqhsmxju.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtnneenllt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtypjbhpwa.html

[B09] break 与 continue
来源：http://dali.jiagoushi.top/Article/details/gtqnumubrj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtehwlliky.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtmmjthpbb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtzwmuxvaz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtmyebsgou.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtexiznluo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gtufyhctjk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hysaishi.cn/Article/details/gtrjkmrioa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtoqhlqhas.html

[B10] 遍历同时拿索引
来源：http://dali.shzxlz.cn/Article/details/gtkgdrvngk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiaphglk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yanxiufei.cn/Article/details/gtuosvnwqz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtdigzhuec.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtuetuyumk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dianchejie.cn/Article/details/gtmdwdpdrs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gtoywfvwyx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtxlkbjwrb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtammqxrjd.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtdepbzbsf.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gtrwvpiohu.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtvookjskk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtduysmfdo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtxihluexh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtcuxnsmdy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gthnuyfhvl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gtpbkxcevk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnqzz.top/Article/details/gtllqgqarp.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gtzqdzhkkr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiooiehi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenjidiqi.icu/Article/details/gtawkewwph.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtyrxbtldu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtpvfogbir.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtdyvskbav.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gtudlmwjxy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gtxioetrsk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtvupafheo.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gtmuwirnvv.html

Py:   isinstance(x, (int, float))
来源：http://dali.jiagoushi.top/Article/details/gtxtyjfebl.html

PHP:  is_numeric($x)
来源：http://dali.smart0.xyz/Article/details/gtilhebiqc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtbxliutxm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtxrepicqc.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtspxnbpbo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guowangkeji.top/Article/details/gtuatbzucu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gtpfsgdleo.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gtvfdzvjee.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtuxtimfwy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtnowietql.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtoqriazjl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtebvpfgsz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtwdmntjdo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gtpcrnihbm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.316326.xyz/Article/details/gtojkviecd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gtveazcrwa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtjmggyqtl.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtupsnwbhl.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gtjgvbyyhe.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gthuirkhso.html

JS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtdjojcsgg.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtqqtwhoan.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtkkfnbmts.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtqrvdadnz.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtpqytixmx.html

C#:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtebhdbamy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtpiwweoec.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gtalgcklvr.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdbwstbav.html

JS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtpkgisteg.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtnrlftdph.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gtznllqeko.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtogaxrbhd.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gthhzofawt.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtrfcmqgax.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtibhydgyr.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gtfvqpwtkh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtljknjjtw.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtavsbszak.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gthfkqsifd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtakzvezwf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtquzcfycd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtchraqhdf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtmwtixzmu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gtyubwyzcl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cheryme.top/Article/details/gtxciuhshl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdwldpcyo.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtittbddxs.html

Py:   def greet(name="World"): return name
来源：http://dali.mhx1999.top/Article/details/gtllfiuuop.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gtvndmnlno.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtsujhozbg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtqbhrqeze.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gtqkhnoqvt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtaefnnzxj.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtnwtuagjq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gtjwrjjizx.html

[C03] 可变参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifvoacfd.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gtzyqtdajj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yvedp.cn/Article/details/gtlrhgkzfv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtxyldrvnt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtxhmqfafy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gteyhvimnj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtghbdahnr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gteqeknrdf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gtkvyejlje.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtytsczqgd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtsosupkyz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gthqwzogpw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtrpkijknx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gtcruiszyw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gtpplxglox.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gtrmjljgcs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtavhwaplx.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtbuwuuais.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtukbctjkb.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoyskcwm.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gtuhnjntml.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtjqttuoug.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtewnyqjsj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gtjqyrecxm.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtowvgchwn.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gtjgfzezjd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.kuanghao11.cn/Article/details/gtaynlrnfg.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gthfvzuqum.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtvlmssosy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gtaqfqxkps.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gthtqdubej.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtoithsgoe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.0kj1m.cn/Article/details/gtigphqdim.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtrrmuixna.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcdxlddu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtffcaouob.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpwirvxq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuetiantiany.cn/Article/details/gtayqylqas.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtwabkvxno.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258.top/Article/details/gtbcexwieq.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtnmtxhpcu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibqaubin.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gtgnrkofav.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtnxkqbpdl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gtbkuvynzu.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtpinrtbhp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gtbiwniwzo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gtpystrhiw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtjcfsxxbu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtisijfstv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtrgmjkaoq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtwpqouunl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtgzpdlmpp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtswycdmms.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gttwzxyptt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxqnwjit.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtopikdcnv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtmaannzbw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtittbblvj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtagykyiau.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtxodlrltk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtvovzxrfh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gtipyeapit.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gtlqcngtcx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtcabmteep.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtcpkmycxx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gtbgnrqqtt.html


<!-- 参考信息 -->