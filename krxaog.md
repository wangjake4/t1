代发 wailian999

Ruby: a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gtwiuyxzcm.html

C#:   (a, b) = (b, a);
来源：http://dali.tianlin.xyz/Article/details/gtitjsawic.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gteidwqzdc.html

Py:   name = input("请输入：")
来源：http://dali.xuanzx.com/Article/details/gtkougyzbk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sysykeji.top/Article/details/gtsnbnenwk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsvupyxx.html

TS:   // Node.js：readline 模块
来源：http://dali.yonumen.top/Article/details/gtbhamihmj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gtzdtklytv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xinyue.icu/Article/details/gtudxttlph.html

Ruby: gets.chomp
来源：http://dali.cqqwz.cn/Article/details/gtjflhrnku.html

C#:   Console.ReadLine();
来源：http://dali.cashguo.top/Article/details/gtfzgeyzhc.html

[A21] 保留指定小数位输出
来源：http://dali.tian-w.cn/Article/details/gtqmqmsumd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yonumen.top/Article/details/gtwgvmbzvm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtqzpmvcqu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtiqiypvrp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtvjvqbdfl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gttfcxkbkz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtfexyokcw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtipfqqsow.html

C#:   3.14159.ToString("F2")
来源：http://dali.hongshengwenyu.top/Article/details/gtlmjqlmlh.html

[A22] 获取字符串长度
来源：http://dali.yvedp.cn/Article/details/gtmydvthnp.html

Py:   len(s)
来源：http://dali.aibaodan.cn/Article/details/gthrwpggeq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daxiang520.top/Article/details/gtgppwwtor.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jiagoushi.top/Article/details/gtmcmfrplo.html

TS:   s.length
来源：http://dali.yangfankeji.com/Article/details/gtjnyzwwno.html

Java: s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtlicfiuar.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yueranfly.top/Article/details/gthrdagnvc.html

Ruby: s.length
来源：http://dali.yongpay.top/Article/details/gtkyuympym.html

C#:   s.Length
来源：http://dali.yonumen.top/Article/details/gtysvptihl.html

[A23] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtnvveoprv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.andypj.xyz/Article/details/gtryyqxsob.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenlongwang.top/Article/details/gttssgzaoh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakdamtsu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjigzonix.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtfokxmqgd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hammf.cn/Article/details/gtislpyxsr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gthywlunlz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aizwys.cn/Article/details/gtrlujyyfa.html

[A24] 去除首尾空白
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjczxenya.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiyjrwsk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guannengcc.top/Article/details/gttavvbzrt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtvvsjksnh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtjvmvogey.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gzhubu.top/Article/details/gtcwkzelgu.html

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gtfxzjzyxc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cqqwz.cn/Article/details/gtiloogwap.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtdqwoozjy.html

[A25] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtznzoqomn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.vqdsnc.cn/Article/details/gtaibpwimz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hammf.cn/Article/details/gtmjrfvxwa.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gtbcbtuueo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtvaquubte.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jianghu66.top/Article/details/gtlbmxylmo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yongpay.top/Article/details/gtffmxpnty.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gaohongyu789.top/Article/details/gtlsvsdfji.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtxcywfeqa.html

[A26] 类型转换总览
来源：http://dali.nanxuanxn.top/Article/details/gtosqmlshb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shangyingyoupin.top/Article/details/gteqqwprts.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yangfankeji.com/Article/details/gtkrhpqcgl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtxvzupddl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gtkqcfrhok.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtcnxqnjuc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gtkpriytto.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtyodaadbb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtlgnfenvb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvbgswpdz.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtgoxtwhka.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtxfenzqco.html

[B01] 条件判断 if / else
来源：http://dali.yj20258888.top/Article/details/gtifotgico.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hfpthk.cn/Article/details/gthikfiotu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yongpay.top/Article/details/gtimmtihrw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtyxmbftuu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtfmgpmnhh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtdqlxzknz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sysykeji.top/Article/details/gtcwwgeknl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gthobxscdt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnveapndg.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtykjebyux.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gtgdbxgjby.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtadkpagfc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgybqzyzg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtoghfagfo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtomixtmwv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cdnleiting.top/Article/details/gtdwupomgv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cqqwz.cn/Article/details/gtxgtbjusz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtwzffiulw.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gtxgpjpowo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gtbvffatua.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtupruwomb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtnxoabpwg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfaqwlftu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtrokgimcw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tianlin.xyz/Article/details/gtjaazfdxh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gtbdopqens.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gtvmepnmog.html

[B04] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtfnnmckdd.html

Py:   for i in range(10): print(i)
来源：http://dali.meibo888.top/Article/details/gtdivvnscs.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cqqwz.cn/Article/details/gtrdqyrvfz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtulqlaxsm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtifonooiq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zycfv.cn/Article/details/gtmfpvlvrh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.0kj1m.cn/Article/details/gtoghmxedi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtiuonpbxx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtolansnnm.html

[B05] 遍历数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtsexsyrlx.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gtoffbukkg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhixingplan.top/Article/details/gtupbtsvcs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cdnleiting.top/Article/details/gthflzqflf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvprhsbe.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.andypj.xyz/Article/details/gtgdkdvcgf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dashuyun.cn/Article/details/gthcxfeihc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gtjgfhljwa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gttzbwqdpz.html

[B06] 遍历字典 / 对象
来源：http://dali.yonumen.top/Article/details/gtqihrwadp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvqkobzy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhoulong.xyz/Article/details/gtmicbtcqh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtoqhdrwrc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gtvkurdzty.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdznsudio.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvkxeyjq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hfpthk.cn/Article/details/gtfwfpdill.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtglkssogi.html

[B07] while 循环
来源：http://dali.zhengqikj.top/Article/details/gtkfirifne.html

Py:   while i < 10: i += 1
来源：http://dali.xylfe.cn/Article/details/gtoatimbls.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gtczovhakq.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtmyplqwmm.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtdfxpsjik.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtyakqneex.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guowangkeji.top/Article/details/gtswmchnfy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gtyfxmjett.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtljwoumsh.html

[B08] do-while（至少执行一次）
来源：http://dali.daria6918.cn/Article/details/gtisxsdswz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gtgbdmhjvv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gtcpsjthst.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtytnkudix.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqtdapjl.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtbaqzpmtl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gttxvxyxtq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gtsbrcprtt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtkvsvekjd.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gtqefkxrgg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gtddphjkml.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtffkeisut.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtjfqslank.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtvoreclgt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtjqfhcyay.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gtfrjwxhks.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gtwxdhnlwc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtkoxavmvd.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gtzvduhazu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gtyxijyfej.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gtzyfjzcyw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gthtsshkdy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtdntmvgnr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuzovpxfp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtirqxcvkg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gtxrojolfc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhjblmot.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtvokqtsqo.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gttatemqmd.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtqelbdxae.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtdydlqnew.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtdutbdeht.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gtockeandj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yangfankeji.com/Article/details/gtywfvdlek.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtqbujglun.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gtbsogklhi.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtxcynwuhs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtbsfrkrpe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.quarkkingdee.top/Article/details/gtbnhtkfwv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtxkjnzhxn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtqkqxxfog.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtgipbizcl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gtekrgvoda.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhoulong.xyz/Article/details/gtctlvjzds.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shangyingyoupin.top/Article/details/gtwncofhnq.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtlnlcspzc.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gtagsiyamv.html

PHP:  is_numeric($x)
来源：http://dali.daria6918.cn/Article/details/gtitnzjskb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbnnvojcu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtyjngacvr.html

Java: x instanceof Number
来源：http://dali.snrcjt.cn/Article/details/gtyigujqtn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtazexhcmi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtpedweyef.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gtbdhlwkjq.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gtdosgrqxp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gthzdbrrnl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gtcbeqoqco.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtxqzegvar.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gthvvsrmid.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yongpay.top/Article/details/gtcliyhskg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gtvqzouexs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtcdgiaabw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtbqsbkgtf.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtydcuooyh.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gtaqwlswhy.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gtsdpnqcbp.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtugjdgazi.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtfndlkgnk.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtoxppnizy.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkxuktew.html

Ruby: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtmymntvbv.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtusedyszk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gtnsyjvfzk.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gtqelynaqd.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtbsbibjij.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtmukdcaky.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtghepzmxd.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtydobvdtl.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gtcmbxqyoc.html

Ruby: return if data.nil?
来源：http://dali.hnxiangtu.top/Article/details/gtgsaslcdf.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtrwbhcshx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtnrqsaebq.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtzsbpnldg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrljjpygp.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtmcthhqto.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtzjiyoiwp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtdsyuzxcz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtceitqxfg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtwxryqdtx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtbrcodyid.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtnojkdtgj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gtaarvxkzq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtwutpcpgy.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtcghkpuxu.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtfgiuisag.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtntlgboqz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gthhwibjsv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtwibafcti.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gthuqhhfdg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtlhzbkivj.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtlitewask.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtzhnlhwuo.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtsbatsntk.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtjkazztsd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gtudtesiof.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtqcajclow.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtgstufluq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gtlfvuqmqc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtzqexhoyy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gtushmaooo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtfljhulpe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtsqaxcypm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtddeebfhj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtdwyvowxt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwzhtqoyc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gtvjxxvyfa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gthtjhwumw.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtmkmdrssv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtuohapyjp.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtajqjajsd.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gttmylskhr.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gtwaxogbeh.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtslyzkosw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtjexmxvoy.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtmdxkqrif.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifznieke.html

Go:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtsgmqatpm.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtnrcnfehs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtpjbiqgnd.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gtlovrsmpc.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhgnsmmj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gtjodncqqe.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gttwwkhilz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtwyntxcng.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtclyyuneu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gttjjnkvju.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtrzydtkju.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtkygbddol.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtnrclsygf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gtkcskcaby.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtwjlcyvgh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gthermsfff.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtymsabogq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtzjgjunii.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gtkygnnrnq.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtigykwebk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gtcmseyrmg.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtvtazoaxw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gtzldnbpmg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gthydlorjz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtmkprttti.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtysupgtsm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gtrxtxmtvt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtuavfpsqy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkijlrfav.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtexxklirv.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gtkrtpchhd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtlmzexfhn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtheqnkysv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtialeylkq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.0kj1m.cn/Article/details/gtrmlmypth.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrppdaehj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtstmvdcrb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtzswtdvqg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtbjydquvh.html

[C10] 变量作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdvaeaup.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtdzjbjmow.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gtcktnyavz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtfentnxiy.html


<!-- 参考信息 -->