代发 wailian999

Ruby: a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gtzwirpexq.html

C#:   (a, b) = (b, a);
来源：http://dali.hnqzz.top/Article/details/gtumvlhjqn.html

[A20] 读取标准输入
来源：http://dali.c1oappe.top/Article/details/gtxjdllvtp.html

Py:   name = input("请输入：")
来源：http://dali.tianlin.xyz/Article/details/gtmnsjceiz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nanxuanxn.top/Article/details/gtjeyoqhbp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gtlzguhwdo.html

TS:   // Node.js：readline 模块
来源：http://dali.hysaishi.cn/Article/details/gtfdawskip.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.daria6918.cn/Article/details/gtxbfehspv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.pengpengdd.cyou/Article/details/gtywzaijda.html

Ruby: gets.chomp
来源：http://dali.zhixingplan.top/Article/details/gtxjxytlwd.html

C#:   Console.ReadLine();
来源：http://dali.cqqwz.cn/Article/details/gtueazznou.html

[A21] 保留指定小数位输出
来源：http://dali.vqdsnc.cn/Article/details/gtwctqtaxr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.9152youxi.cn/Article/details/gtylyoodjr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gteratlaie.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gthbqouqlv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxrgjcag.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtgnjmyged.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkokunyd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgvmroml.html

C#:   3.14159.ToString("F2")
来源：http://dali.zdqjudy.top/Article/details/gtdcuvcpcc.html

[A22] 获取字符串长度
来源：http://dali.xziqi.cn/Article/details/gttncijsze.html

Py:   len(s)
来源：http://dali.daxiang520.top/Article/details/gtfehlpbiv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenlongwang.top/Article/details/gtghnlvbwc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hysaishi.cn/Article/details/gtxllcuuer.html

TS:   s.length
来源：http://dali.zhixingplan.top/Article/details/gtkicapuhx.html

Java: s.length()
来源：http://dali.svipenyu.cn/Article/details/gtkiyxqcfw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gtwxpyquib.html

Ruby: s.length
来源：http://dali.yanxiufei.cn/Article/details/gtmaroekoe.html

C#:   s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtwqsjlphu.html

[A23] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtkxvporvn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gtvushughh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuetiantiany.cn/Article/details/gtuthsuuvz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtveoqqtyy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gtttumdevy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtuqnggfqc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fzhhl.top/Article/details/gtoazptqjs.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.meibo888.top/Article/details/gtrnihlsws.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yueranfly.top/Article/details/gteyplxspi.html

[A24] 去除首尾空白
来源：http://dali.gotoacloud.top/Article/details/gtccsehnvm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xinyue.icu/Article/details/gtucsvqqij.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenzaomai.com/Article/details/gtyafjoqlg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tian-w.cn/Article/details/gtnjrcbvel.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtthexzvjc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gtcokgjvth.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxitnypxe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.quarkkingdee.top/Article/details/gtvitzkpox.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcnzgtaz.html

[A25] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtpyyjddfq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gogol.net.cn/Article/details/gtbcbrjdxv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangdashe.top/Article/details/gtbbutkprb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtdqjtqyrd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangdashe.top/Article/details/gtevwramfk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gtbopalbpx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtsmwhtnic.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenjidiqi.icu/Article/details/gthfgulppo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.snrcjt.cn/Article/details/gtbetmmbtc.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gtvcubbxxr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuetiantiany.cn/Article/details/gtnxjbtyji.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gthvqskuha.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gtwdykddfe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pycfn.com/Article/details/gtrcbwhzma.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtmtnacybf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwswodsv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gtifyzlsmb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yangfankeji.com/Article/details/gtavnkgicq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxvpopidw.html

B. 流程控制
来源：http://dali.xylfe.cn/Article/details/gtkoekrmxn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtefkounqe.html

[B01] 条件判断 if / else
来源：http://dali.yuanzhike.top/Article/details/gtwlwqmouw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtgjbrvgln.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtirinjsgg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtozhhbdaz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtnfykqlgm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtmomjnrfj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gtldtutlpb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gtqliuchgt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtjvdaetle.html

[B02] 多分支 else if / elif
来源：http://dali.tianlin.xyz/Article/details/gtcelqkgub.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtknanwaey.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gtsftpljbx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtozvwaqeu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtzkidcnfy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtptsjujob.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sufxvd.cn/Article/details/gtkgcjzlzo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnqzz.top/Article/details/gtgwbqvqed.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtaqgtcjsw.html

[B03] switch / match / case
来源：http://dali.tanke756.top/Article/details/gtbgoonxjq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gtqaaxhoxp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdxuamxy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtgvtprxdm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtjcsqfdnu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaibgslo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtebhotsuk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.redwolf501.top/Article/details/gtcyaeawls.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtafbiiani.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtfodehyue.html

Py:   for i in range(10): print(i)
来源：http://dali.birdmap.top/Article/details/gtzsgdcpvg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gtwpxcadfz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtwffqwyqk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbxshnke.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gtcfpmpfkd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tian-w.cn/Article/details/gtecscntkx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gtjwwshkxs.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gtaktqqsbr.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtqaehugkp.html

Py:   for item in arr: print(item)
来源：http://dali.jinghuilouyu.cn/Article/details/gteqahcres.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tianlin.xyz/Article/details/gtvntwivfo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gtsxboqkwy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gtvtdnyaui.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gtxbedghbj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtemwltukd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gtnimjxpzv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gtigxqjwby.html

[B06] 遍历字典 / 对象
来源：http://dali.yvedp.cn/Article/details/gtzjtzunrv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jlsjyb.cn/Article/details/gttkwqsxlr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cheryme.top/Article/details/gtahqvrktc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtfgwdywcr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtzedwtxjd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gtvkxhcpqd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gtwbeyrelr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gtwuzuglrr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtefbwseed.html

[B07] while 循环
来源：http://dali.quarkkingdee.top/Article/details/gtjkmhsths.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gtyvnktgdi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gtlhbrkaxc.html

JS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtcyatsusw.html

TS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gthlhnqenf.html

Java: while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtfnffhami.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gtcyfeogwn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gtqeehdbni.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtblkdsqhj.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gtrkbjrfqi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gtntuyamsp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttovgndbc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxfuzvhy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtckzvohau.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtzxzcrqhq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daxiang520.top/Article/details/gtigmymory.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gzhubu.top/Article/details/gtxrwdnnhz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtmbjtpufu.html

[B09] break 与 continue
来源：http://dali.zhiwuduotai.top/Article/details/gtcflfhckx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gttbwsvsln.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtkwbfvzxd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtqaopvrtt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtkbllfzir.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtixjiwozs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gtcebkwdmq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gtdcbjpfka.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtwtzdwzun.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gtezjjhihi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gotoacloud.top/Article/details/gtphntcyxe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtlubkyybx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtfbubzyfg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtmpoivsau.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yueranfly.top/Article/details/gtjoxttxec.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gtflnkjsud.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtpbkruhxr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gtrmucphni.html

[B11] 生成数字序列 / 区间
来源：http://dali.sysykeji.top/Article/details/gtqgjanrxq.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtjcbijmze.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtheklgmvj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gthopacesq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtxjnhthop.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtzubbothg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.iojbl.cn/Article/details/gtunhtsuqj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gtqotzhtnb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtqgdbpawx.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gtmvndzvaz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtjwxsmxfx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yvedp.cn/Article/details/gtiksxzjnn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gteucpuimx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhdqlxex.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtwdaaugbx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gtsskkbfkw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ydzc1.top/Article/details/gtrpmozhfo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtkjuuexgo.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gtzyxudejd.html

Py:   isinstance(x, (int, float))
来源：http://dali.jiagoushi.top/Article/details/gtbeawgsib.html

PHP:  is_numeric($x)
来源：http://dali.shzxlz.cn/Article/details/gtscpuvalu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtdhdpweem.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtodlthfvx.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gttptjaaow.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtehcwfjly.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gtsmqgyhtb.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtiwyvbimx.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtvrozpepp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gtlnjwnxwi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gtcubkeghb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtldpebhpk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtlhsuhaij.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtifbczxgz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtxjsjdlua.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtohwzkynh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtdtptxmvv.html

[B15] 布尔运算与取反
来源：http://dali.andypj.xyz/Article/details/gtruukbcoz.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gthuzvcjtk.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtobujgclc.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtumtqziks.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpwzuvfh.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtefmiueku.html

Go:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtbzggrzpr.html

Ruby: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtamggjidq.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtsgqsauur.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gtiuvzgpfg.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtyuiszzmr.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyxmekorn.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtkfccolol.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtttdgkckt.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuojhymhc.html

Go:   if data == nil { return }
来源：http://dali.aizwys.cn/Article/details/gteqelorqr.html

Ruby: return if data.nil?
来源：http://dali.ehwqpu.com/Article/details/gtnmqtyltz.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtuvgjgdpz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmzygldie.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtfefmazsd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtbiwtybbp.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaenefqs.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigfzy.top/Article/details/gthptculil.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxgmyvapx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtkfxbmrbr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsgfsxxj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtxosgjjbn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cheryme.top/Article/details/gtcjfcyoif.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gtabvctrhb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtsfqbhtpi.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtzrtibxqy.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gthfdzslqu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtabrlogsb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtrphgfxyx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtghkaokvo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnijiuvi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtuewcgfyk.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gteuhnejba.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gthoodqtyu.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtosfcnwmd.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtudnubtab.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gtpnrrsfvv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtgmvbbhvh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtebsdotde.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gtzqvhuvrb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtgfhraiqi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtmskqessn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtflfbwnvs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxvpdwtm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gtocyyaqsd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzysqunh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtfbyjmtbf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtvfemgwpx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgufenzy.top/Article/details/gtovumtdma.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtepwqaxma.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtqwkybocr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gturbtkmxt.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcziycax.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtpajyzesj.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlkylxkx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtnxuzrsta.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtorhgskue.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gtiioddmlp.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtiieahkyf.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtkfpiqoyy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gtsgkxpuit.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gtirbuhsvo.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtfjwldybi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gtvxrqarjz.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtyliifget.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gtuswcvqvc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gtujwcyiyn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gttobppxvq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtiohwumaa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtfbmemtwh.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gttcowpqqc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtmvfwnqko.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gtzrostwms.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtwffqsadt.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtvfcllckw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gtpfkbdyav.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtcmkrhhsr.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtzrezxunr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtavcfidyx.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtgyfqlyzq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtekocctav.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gttoyvxslh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtstemzdgb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtsdurmqge.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtjvklemlb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yvedp.cn/Article/details/gtctusriep.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtbvutgfyk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtcexpbggk.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gtnvreizgw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtnreiqynj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwpdjxbtl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtoraghmcm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtebyqbdta.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtaiplmmsp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnhoxvws.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gterqxwtsq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtrjfyjcyt.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gthirnmovn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gtfoetrury.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtaynrrlsv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtwrxirypr.html


<!-- 参考信息 -->