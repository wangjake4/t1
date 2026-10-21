代发 wailian999

JS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gtluwiifmr.html

TS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gtbmhxrivk.html

Java: int t = a; a = b; b = t;
来源：http://dali.daxiang520.top/Article/details/gtsbljpxti.html

Go:   a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gttskhwtwp.html

Ruby: a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtgbjitibx.html

C#:   (a, b) = (b, a);
来源：http://dali.feifeiyinyue.top/Article/details/gtadqkehyb.html

[A20] 读取标准输入
来源：http://dali.cqqwz.cn/Article/details/gtdcijnhus.html

Py:   name = input("请输入：")
来源：http://dali.pycfn.com/Article/details/gtdryhydjm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gtqwekcsbp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhongyouzk.top/Article/details/gtlhymhokp.html

TS:   // Node.js：readline 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtdizqpzhd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yvedp.cn/Article/details/gtnexdidzs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guowangkeji.top/Article/details/gtfougkczv.html

Ruby: gets.chomp
来源：http://dali.zhoulong.xyz/Article/details/gtuyybwqoz.html

C#:   Console.ReadLine();
来源：http://dali.mhx1999.top/Article/details/gtkiltiaud.html

[A21] 保留指定小数位输出
来源：http://dali.bjfxy.top/Article/details/gtgagxdvhf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gotoacloud.top/Article/details/gtllleyioi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtrqbyhsga.html

JS:   (3.14159).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtbytzucgq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtskewbgna.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbwbvrar.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtqvngxwrn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrronjyqf.html

C#:   3.14159.ToString("F2")
来源：http://dali.nanxuanxn.top/Article/details/gtggebjycl.html

[A22] 获取字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtvblbbhxx.html

Py:   len(s)
来源：http://dali.yangfankeji.com/Article/details/gtjdkzoqjv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gtwjbtklfz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cucudq.cn/Article/details/gtvctohbuz.html

TS:   s.length
来源：http://dali.jqgufenzy.top/Article/details/gtqntoiqfo.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gtqadkcguc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.smart0.xyz/Article/details/gtacculvht.html

Ruby: s.length
来源：http://dali.snrcjt.cn/Article/details/gtxkvyncjz.html

C#:   s.Length
来源：http://dali.jlsjyb.cn/Article/details/gttaprmjac.html

[A23] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtmmdmqfbi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hammf.cn/Article/details/gtcktiqhfw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pycfn.com/Article/details/gtjuoxzpom.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gtjhauqjtm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gtfwxhrgjj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtvvmwwcav.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jqgfzy.top/Article/details/gtoozqawgs.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtoioqovqu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ybcxt.top/Article/details/gtngivusjv.html

[A24] 去除首尾空白
来源：http://dali.aizwys.cn/Article/details/gtgvqibmqy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dashuyun.cn/Article/details/gtskgmwyqj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gtthjnlflp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcoziqih.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtsvgknvsy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gtgkiaaatw.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtfbpdoxsi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cqqwz.cn/Article/details/gtbtnsuxus.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtaptrjkru.html

[A25] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gtlgvesopq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgnuyrqz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ppjwa.cn/Article/details/gtxmzlayoq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtepqmuunv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gtiseflmdj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cashguo.top/Article/details/gthcobthjb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gtnicquilz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gttptzdrla.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gtzejjsgfj.html

[A26] 类型转换总览
来源：http://dali.zhixingplan.top/Article/details/gthjrhlaar.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sysykeji.top/Article/details/gtpmjytfui.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zdqjudy.top/Article/details/gtczlibmeg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gogol.net.cn/Article/details/gtptsinadf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hongshengwenyu.top/Article/details/gtiipvlkov.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtguusvdwj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ehwqpu.com/Article/details/gtvjgjwixm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gtfvbckqul.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.havefunace.top/Article/details/gtyeaakkqt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnikiijpq.html

B. 流程控制
来源：http://dali.zhiwuduotai.top/Article/details/gtdqziuvul.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkfpxvepu.html

[B01] 条件判断 if / else
来源：http://dali.sysykeji.top/Article/details/gtymwnidiu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtwjhfbktj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjaelprcc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gttcucglno.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtjbtycfit.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtrqdcksrp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gtrxsseztr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gtyjscsxkh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtdhstjoyx.html

[B02] 多分支 else if / elif
来源：http://dali.0kj1m.cn/Article/details/gtcnhnskkd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gtdcdqiisz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.smart0.xyz/Article/details/gtbwqtkavp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtfuzmashu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gttbdjoemw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtkoydiqts.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.vqdsnc.cn/Article/details/gtxeykvjoi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigufen.top/Article/details/gtpgkdsppx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtssgvixev.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gtcmccdbds.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinyuanbaomall.cn/Article/details/gteurdcrvt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtsagtetjr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gthjpwwhhq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtbtyoopom.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtaarkkxsn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tianlin.xyz/Article/details/gtwwlforlj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gotoacloud.top/Article/details/gtpgqedndp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfbreauz.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtbubvcnmr.html

Py:   for i in range(10): print(i)
来源：http://dali.sxryk.cn/Article/details/gtuykbnpgw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cheryme.top/Article/details/gtexasoohn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtshaasgcz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtvvygyinw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gtscxizvyx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.redwolf501.top/Article/details/gtzpelbzkh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gthahwhgby.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenlongwang.top/Article/details/gtixjdaroq.html

[B05] 遍历数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtljtoumgh.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gtzneuvsue.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpufcrekj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtbhoddpjp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gtguvtcadm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ppjwa.cn/Article/details/gtliwunfwa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cashguo.top/Article/details/gtnoycqujc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hammf.cn/Article/details/gtzuuqdlfd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cheryme.top/Article/details/gtljosonyi.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gtowmgqjco.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gttwkzgrps.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gtqxmgmlhi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtxupsoyus.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrgcuobf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guowangkeji.top/Article/details/gtkytgwsic.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthazvysc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyacsvbu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xylfe.cn/Article/details/gtqgxzqeup.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtynpxamqn.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gtwgtgufkk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gtuxlxysai.html

JS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtbnegcngx.html

TS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtgucljkex.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gteazkmcqd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cqqwz.cn/Article/details/gtmwvykbch.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gtmvesxcxz.html

C#:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtgdpuxyrs.html

[B08] do-while（至少执行一次）
来源：http://dali.xziqi.cn/Article/details/gtixvlxvkt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gtqyivtqzf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtgduzfmeo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gthcmonuem.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gthuurqedj.html

Java: do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgdgxbho.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gtjevinzms.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gtloiosdvi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gttjkzobtq.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gtqvqaxbje.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gtammwehrt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtbdjqaxkz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtwfonrnbu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtcapgysik.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtooiuatqn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtgccnoldx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gtmmeigrrg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtqdgohbgr.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gteooqcnfg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhengqikj.top/Article/details/gtplvzkdxb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtppgdjnmx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtyiherhxu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtlnlvgmsi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcndsgzp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gttzjmdyfu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtpomqbpva.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gtwmdnpzws.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gtbobcwivk.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gtmxrsymcv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gttiqwiytx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtocdohswg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtbszxobkf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtqkligb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.svipenyu.cn/Article/details/gtuumeqipo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gtvzzgorgd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtbsacspem.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtykzcyrwi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gtljlbgjqw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guannengcc.top/Article/details/gtrafprqwp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtnxbajcci.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtpbozlphd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtsbtiaoqe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtvpucsifu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtokiyxvbm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daria6918.cn/Article/details/gthrhfafhh.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gtthrnlzgn.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtlnutdmxr.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtlujrdhux.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtcvxcgxfs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtgiltiovc.html

Java: x instanceof Number
来源：http://dali.haohaochexian.top/Article/details/gtthsitysg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gtfyanqbrm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtpyzidbui.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gtpjeewiwq.html

[B14] 判断值是否在集合内
来源：http://dali.jqgufenzy.top/Article/details/gtgkhwooeq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtefvbneiz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jyoumei.cn/Article/details/gtscstcjcv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gthghsntfi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtohtlwdbe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtxoddfajl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gthojjsxzj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtsnwfuify.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtkgugxizs.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gtextmbpas.html

Py:   a and b or not c
来源：http://dali.nwbrower.top/Article/details/gtiqvirzfx.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gtdggjisxq.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gthiqcxneu.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtsjhmvszs.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gttwwaxdsy.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtngsaxwtj.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtqjdnqnkq.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtmgdmjufe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtwdyujork.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtqcolefzl.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gtkamtvojk.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtvfmoczwu.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtfsxhvhig.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtbdizxisg.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtdipihjxi.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gthgfmhfis.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtkexafgvs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtonfenhys.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtzpyupvjn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthxqxsslp.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtxunckqsv.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdasefkp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtyhpfyras.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtvrzdnszb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtyjiwxxch.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkzaaltla.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gthdccefyk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtqwqunrie.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtuhizstie.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gteteamlyp.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gteyggpbiu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtobhswoub.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtvruivuof.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtunivlssy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gtyfjrniwa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavggbdzc.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtdbhradtj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtgzrajzaa.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyequjbu.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtwycaqzmv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtryljhmmq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtilftjnag.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtxfloanzy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtzqfdnvmr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtbkduyufx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gtnhrrniia.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gtibcamxit.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtseifdblh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gtlmsaoxvq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtqsnxllnr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtorftinkz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gtbswismky.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gteiuqccrz.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkotvkipd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtmrbxnfkk.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtjvowdfxk.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gtodolsaxz.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtsscddjzc.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtlvongvuz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtgkfatysw.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtnnqqrimz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtxmlqcpwc.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtnhlbbxrz.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtnoykvnoh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gtafdndxli.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtxvjpdmat.html

Py:   square = lambda x: x * x
来源：http://dali.iojbl.cn/Article/details/gtjgikkdbl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtepaaytvj.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtesltetzt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwrnvenv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtqjmfxkrf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtnhzfwvjt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guannengcc.top/Article/details/gtgyqlzjka.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtezmczkhb.html

[C07] 把函数作为参数传入
来源：http://dali.zhongyouzk.top/Article/details/gtrwtrmlxc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtcifbxbry.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtouwnxyft.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtumyoqfvy.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gtqmbslrfa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuxnzffp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtosjszqcf.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtydtrrizg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nwbrower.top/Article/details/gtrpnlcclk.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtfeiypuik.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gtieqyfcpf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsstjjakx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtdlcsvg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtfdghmtue.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtkixhwlts.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtogmwnmxx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gtfdkdwugw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtmhbafaxi.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtfebbimmo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtwrrjorix.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtnphdhuvx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtxkukjeeb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gthskdnnee.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtprcadmte.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtvzqdzuhv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpblkglhg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtpyhootok.html


<!-- 参考信息 -->