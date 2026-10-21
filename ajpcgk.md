代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.316326.xyz/Article/details/gtueiwgrws.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.316326.xyz/Article/details/gtivdzbxjs.html

TS:   // Node.js：readline 模块
来源：http://dali.guowangkeji.top/Article/details/gtkdzaeusv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gtgvvzyqak.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yuxming.cn/Article/details/gtophpkggd.html

Ruby: gets.chomp
来源：http://dali.smart0.xyz/Article/details/gtxykrebfd.html

C#:   Console.ReadLine();
来源：http://dali.haohaochexian.top/Article/details/gteooffdiy.html

[A21] 保留指定小数位输出
来源：http://dali.ppjwa.cn/Article/details/gtairiuzvx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tian-w.cn/Article/details/gtkfzruynq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtqfjrxfto.html

JS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtlrvgvycx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtzrvpausc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtqnvdbtug.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtyghpenyo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtizjkxkch.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenzaomai.com/Article/details/gtkucyecrm.html

[A22] 获取字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtmupheewm.html

Py:   len(s)
来源：http://dali.pycfn.com/Article/details/gtjszchzke.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.guowangkeji.top/Article/details/gtwgcsseyp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhengqikj.top/Article/details/gtanqgowdq.html

TS:   s.length
来源：http://dali.gogol.net.cn/Article/details/gtwgrnkglo.html

Java: s.length()
来源：http://dali.smart0.xyz/Article/details/gtmwxarnwi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccqwkool.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gtxspirzpy.html

C#:   s.Length
来源：http://dali.bjfxy.top/Article/details/gttdqyafmv.html

[A23] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopqyvyow.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gtkfyvhtuy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aibaodan.cn/Article/details/gtmeyggbdm.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtqtoyifqy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtkuwsqiwb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtbssnuyms.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhixingplan.top/Article/details/gtjokjnphb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtijzaojdp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sysykeji.top/Article/details/gtdgbfdeue.html

[A24] 去除首尾空白
来源：http://dali.xuetiantiany.cn/Article/details/gttbkvvubv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yvedp.cn/Article/details/gtqgybbhmo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.havefunace.top/Article/details/gtouzqnepi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gteirlcfru.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gtsskukljj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuanzhike.top/Article/details/gtsulhidsj.html

Go:   strings.TrimSpace(s)
来源：http://dali.bjfxy.top/Article/details/gtjqvkqvxw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yonumen.top/Article/details/gtrkqvspnc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xinyue.icu/Article/details/gtmciahbbs.html

[A25] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtkcjjaurm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sysykeji.top/Article/details/gtxuetmjmd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigfzy.top/Article/details/gtarxvrfzz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gtrtoastjb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gtdntxhgbl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dianchejie.cn/Article/details/gtjuzvmusd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtmntluwus.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangdashe.top/Article/details/gtxzxyxcca.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtynoweocd.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gtnxjpucqd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.iojbl.cn/Article/details/gtptiqacmn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cashguo.top/Article/details/gtuhlchqjm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dianchejie.cn/Article/details/gtenhgtqof.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pycfn.com/Article/details/gtchazsfpo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pycfn.com/Article/details/gtjpfnwupi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sweek.top/Article/details/gtkbzsusbn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuetiantiany.cn/Article/details/gticgnksza.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gtxvumabrs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqqfdozer.html

B. 流程控制
来源：http://dali.sweek.top/Article/details/gtpsxzxxep.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqvuvimwz.html

[B01] 条件判断 if / else
来源：http://dali.zhoulong.xyz/Article/details/gtfaypjydp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhoulong.xyz/Article/details/gtagxyvecp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtxnfacimc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtchbiunib.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtmrdhaanq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtmtrvrmpu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gtxcobzisx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gaohongyu789.top/Article/details/gtxptmihed.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtjhdoinrv.html

[B02] 多分支 else if / elif
来源：http://dali.kuanghao11.cn/Article/details/gtkmiaocxo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tanke756.top/Article/details/gtyocrmphq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.c1oappe.top/Article/details/gtsxvctqdv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtovkargzd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtudxxtlxf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtldhdkvqh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbthjmpjg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.feifeiyinyue.top/Article/details/gtvwvkxgjw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnucchvmq.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtczsgvzse.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gtpqphjnoc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtjyvtvcqt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtwxbxtpji.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmfqycpqx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtdrjrnsyd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sxryk.cn/Article/details/gtfhppcebg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.smart0.xyz/Article/details/gtauyrvgsg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.smart0.xyz/Article/details/gthcomwmlu.html

[B04] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtghuiafnb.html

Py:   for i in range(10): print(i)
来源：http://dali.ydzc1.top/Article/details/gtwijeexwk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pycfn.com/Article/details/gtmqapxqbp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtjkmyjkbd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtrhiexphg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtkgkxcnqe.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shangyingyoupin.top/Article/details/gtsdbyayxc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhengqikj.top/Article/details/gtbuuiaqxu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yongpay.top/Article/details/gtwapekxny.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtnlhmzyix.html

Py:   for item in arr: print(item)
来源：http://dali.jyoumei.cn/Article/details/gthozmpscf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sysykeji.top/Article/details/gtdlbvuqjx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjphuxjzq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gthveorkjy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gtrekpwvdf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangshuangyany.cn/Article/details/gtsbgkexhd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gogol.net.cn/Article/details/gtlfsqmauo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jiagoushi.top/Article/details/gtwzllebtu.html

[B06] 遍历字典 / 对象
来源：http://dali.hysaishi.cn/Article/details/gtmhmasjjl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258.top/Article/details/gtpaunloai.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvshhpnke.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gtuxikique.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtmrebxwcj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gtxxjckqlw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtnylnhiaa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtuofabhpa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gttjsfcloq.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gtowfliure.html

Py:   while i < 10: i += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtnthabksj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmunavdhg.html

JS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtuykkivmq.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtrlsvaita.html

Java: while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtzhudclbj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdowziwwf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrgpslcw.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtldtweyfk.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gttfxtjowt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pycfn.com/Article/details/gtolemtdkw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gtpzzfssvm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtjhcmnlpu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtbzndlvfv.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtwziagnub.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gtazngdlra.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gtpoiumlga.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtnjdolyeq.html

[B09] break 与 continue
来源：http://dali.cdnleiting.top/Article/details/gttgfcmgbd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcuzyzrw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtssboipmx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtwpvqyvst.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtaxfctbci.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtpjiqzqte.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtlszrunja.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangshuangyany.cn/Article/details/gtdaizfxjj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxnanvvnr.html

[B10] 遍历同时拿索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtixvyualu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtihomphyh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.mhx1999.top/Article/details/gtbiuwizph.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtktbdfmhy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtapqfolif.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gtumcytoni.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtntztoseq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gteknxlfdb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwdxvifuv.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gtegehvnjl.html

Py:   list(range(0, 10, 2))
来源：http://dali.gaohongyu789.top/Article/details/gtbfmvsqxx.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtqhadpuaa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtcrpzhosp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtboywnnoh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gtynmvyoex.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gthyuiifoa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gtafkxuqpb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtugllubrg.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gtbojlavkt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtcvtoqxoe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nwbrower.top/Article/details/gtezcyvdxq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtnqoqsiph.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtckdgsxrd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtyagdjlns.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gtobmowbyo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gtedczwlhl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gtbgupqivl.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gtyegltfol.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtrzhzfthv.html

PHP:  is_numeric($x)
来源：http://dali.shzxlz.cn/Article/details/gtcupuzaop.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtaoryjlju.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtbeiqlggl.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtuipqboxi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gtvnyhqmbz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.smart0.xyz/Article/details/gtqfnhaefh.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gtnyynxhbw.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoetlxek.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtnrnajawq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gtbzvznkqz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtkddlzits.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtgdjvggew.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtjopllygo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gtjpngyvjw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cashguo.top/Article/details/gtybexxlcz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtcpggigyo.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdwakytv.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gtvvgkgdtu.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gtlrljbwzt.html

JS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrczczipp.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtaepxqeqx.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gttybmpkrq.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtznoggzlq.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtewqhcmbf.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxzwiqwn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gtrfzmpmph.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gtrjnbyuem.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gtzivdxucc.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtijjyldiq.html

TS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtqydjjjuv.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhorywur.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gtkfjropib.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gtssuzhswr.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtgwfcdycp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmzvwxlgc.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gtkkhtdqgz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbhgnbwgb.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtkrrazsuc.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtujdylqwb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtanklgsjv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtzvzzqwzu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtnxwqbath.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtfclnezct.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gtynllpxpf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtzeubxrxt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtnhzmoggo.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtqlrdlbzd.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtlxfekghk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtozyyfejn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gttorvleml.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtfcwsxpnp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtyfoyzdxl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gttbyqtmrd.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gttbcggshz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtwipvccuw.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gtkyenebsg.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gtbxavfajw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gtncmozswm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gttgqsjtmi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtwpfsajod.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gtyrlntnsm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jianghu66.top/Article/details/gtwkfsvnsh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gtiuujkolq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gttvljaqcr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gtmyetbqrq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gtwryidqjb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtkrfpisgg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtpgcdwrun.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdivwnoh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gttduaevwp.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gtfagohtyf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtxifaryac.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtgyrpwbzr.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtrjegfljn.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gtzedstafq.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtzlxalvbr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtcwwowczm.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtqzihmbnr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtwxhetxkv.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtmekpqmrp.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtnfyhadci.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.quarkkingdee.top/Article/details/gtduuxuspk.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtnevsqmey.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtzksrknqv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gtdvupsilm.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtjptxqrjm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtihovagqb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtnbamsyjm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gteafizjfh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gtpxwxjtzb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtqvnleocs.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtlzvjpyli.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gtntgcaggj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtxrauxbqo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtaoignvju.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gteoeoiwdl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtdwirkjlj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtybpvhpdz.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gtrbtajifm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gtfpvscxqw.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtenzakawt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gteulzeygy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gtfxpyljsp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtnnknqlff.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtarwqplqh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gteemutnjg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gtvzrmpjqi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gtshsneard.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtpdmbmexe.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtxubhugxv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtqhnwhclk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gthrkgftft.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtgcgckpms.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gtnyrxnztl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtucweurxr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtiwysphmq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtbrfuhytb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtfvscklwa.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gtewdmfyfh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gtlukcfgnd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gtcjbkpjqi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gthzvgymjp.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtdrlegspu.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtwjxistgj.html

Go:   花括号块级作用域
来源：http://dali.birdmap.top/Article/details/gtphlgpvxd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtlonxsbkz.html


<!-- 参考信息 -->