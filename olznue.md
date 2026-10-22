代发 wailian999

Ruby: a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gt2olxqhlcz.html

C#:   (a, b) = (b, a);
来源：http://dali.dashuyun.cn/Article/details/gt2xoplfpik.html

[A20] 读取标准输入
来源：http://dali.zhixingplan.top/Article/details/gt2igbigkjq.html

Py:   name = input("请输入：")
来源：http://dali.yangfankeji.com/Article/details/gt2owspfozz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdvifczh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhengqikj.top/Article/details/gt2jbciecrv.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gt2lwnymavw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hnqzz.top/Article/details/gt2pxdtyzap.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hywenlv.cn/Article/details/gt2bqophymh.html

Ruby: gets.chomp
来源：http://dali.zhiwuduotai.top/Article/details/gt2napnlbig.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gt2btkqlhaw.html

[A21] 保留指定小数位输出
来源：http://dali.yuxming.cn/Article/details/gt2iikpjobm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.bjfxy.top/Article/details/gt2cgwbotgq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjvgzwsm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gt2qzcrtnps.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2kgkisfkl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gt2ibgwgmii.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gt2izanzese.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2bnwogmwa.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenlongwang.top/Article/details/gt2cildpgff.html

[A22] 获取字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpyhfikj.html

Py:   len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2owxscuzn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfdqnib.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.bjfxy.top/Article/details/gt2gavddyts.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gt2awebrypr.html

Java: s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2aldknytd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tecglsjg.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gt2bdbzrcjs.html

C#:   s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2tjnprrhw.html

[A23] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gt2hzxytvpp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pycfn.com/Article/details/gt2oyztstnh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hfpthk.cn/Article/details/gt2vytkazpw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gt2zwakbvuj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gt2ropwvcde.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gt2jkftqwqw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jianghu66.top/Article/details/gt2mvqzuqei.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.meibo888.top/Article/details/gt2rcnvzcds.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigfzy.top/Article/details/gt2vxrphaab.html

[A24] 去除首尾空白
来源：http://dali.hnxiangtu.top/Article/details/gt2pcjivxit.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhongyouzk.top/Article/details/gt2elmqwmxl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gt2efygchpb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shzxlz.cn/Article/details/gt2mzqtossi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gt2nfygkuzn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.quarkkingdee.top/Article/details/gt2mmjynkbd.html

Go:   strings.TrimSpace(s)
来源：http://dali.jyoumei.cn/Article/details/gt2rrulztlf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.c1oappe.top/Article/details/gt2aqmuhuqs.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ehwqpu.com/Article/details/gt2mtqukrke.html

[A25] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2fnfrxywd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hammf.cn/Article/details/gt2rcboiskk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gt2ipigrvtx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lndnomxi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gt2eowgyczf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gt2ommnadgg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gt2tfxbjcdk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gogol.net.cn/Article/details/gt2dmtznyze.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2oiisrrjv.html

[A26] 类型转换总览
来源：http://dali.xuanzx.com/Article/details/gt2ovjupnms.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpqrmsco.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgfzy.top/Article/details/gt2khigxlco.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yangfankeji.com/Article/details/gt2thlehtrd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.birdmap.top/Article/details/gt2ehozrzss.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zicmpyxa.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yanxiufei.cn/Article/details/gt2frirrujp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jianghu66.top/Article/details/gt2kjmopabc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gt2nztebtgf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2owdujodf.html

B. 流程控制
来源：http://dali.gotoacloud.top/Article/details/gt2rjlybuzx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jvrnqcvv.html

[B01] 条件判断 if / else
来源：http://dali.smart0.xyz/Article/details/gt2fgtmwvyy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ppjwa.cn/Article/details/gt2xzjchwgf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fzhhl.top/Article/details/gt2vxoiuzhv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2gzhhfkos.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2acqmcwqv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2fegdotco.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tianlin.xyz/Article/details/gt2sxbkmwcc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zdqjudy.top/Article/details/gt2hmakoxmb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsculmnn.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gt2bmjrcqqa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tian-w.cn/Article/details/gt2lcgrcail.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.0kj1m.cn/Article/details/gt2gmdvazsb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2bjtjftrx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2vjtterxw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gt2ownxcglm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gt2eoqzasyi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxinkj.top/Article/details/gt2oobrfnew.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2soforlyi.html

[B03] switch / match / case
来源：http://dali.jiagoushi.top/Article/details/gt2mtgjtsae.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gt2vvfbwwxs.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2dipqfhvt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2dvvlkzlt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gt2ysxfhplc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gt2vlmvjvxf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2eomdygwi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gt2oqburapg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gt2mbptyhih.html

[B04] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gt2mbaimgoe.html

Py:   for i in range(10): print(i)
来源：http://dali.smart0.xyz/Article/details/gt2wiumtysd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qeuxlhte.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gt2habguryb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2yyerxuxo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.redwolf501.top/Article/details/gt2wcuyrqeu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zdqjudy.top/Article/details/gt2nktjvkrx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xziqi.cn/Article/details/gt2nxqnwddw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tanke756.top/Article/details/gt2tvzgqcah.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2xlvmijtx.html

Py:   for item in arr: print(item)
来源：http://dali.chenlongwang.top/Article/details/gt2wakqbzxh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ydzc1.top/Article/details/gt2wrxaqtmn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2qqjvzfgz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2gmkkubia.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2dgzvakmj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gt2vndwvujp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jlsjyb.cn/Article/details/gt2uxomtzmb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gt2urabwymp.html

[B06] 遍历字典 / 对象
来源：http://dali.gzhubu.top/Article/details/gt2lfgydhfh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gt2kvirlmdb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2acpyjthi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gt2pckijuyv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kdgqsoyj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ppjwa.cn/Article/details/gt2zvcesjva.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.meibo888.top/Article/details/gt2jwqqrkpg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jewiidyv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqpfinwj.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gt2sqncadch.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gt2cniymhgi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gt2xklsnaln.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2clqsrefh.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2akgvhxaq.html

Java: while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2saxacjjq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gt2xwoytujz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yxctpqxe.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2siwjsekb.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gt2bgqhdxyw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gt2ckbqcuve.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2vkxvnktw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2deyoksbi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnoxfezp.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdufmwpt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gt2kulqwfkt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gt2cvlsultl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2vylbmzjq.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gt2unlwburs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tianlin.xyz/Article/details/gt2xnnicqpf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2ithlxyuv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2ppgprtqe.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2yozkjnbz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2sebdnucu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gt2orbaeail.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gt2hvdcwgsj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2wlyacwoy.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gt2fwnrtxjg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gt2nilnxxax.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.andypj.xyz/Article/details/gt2qfzqdfor.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gt2gbdodxib.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2mwhghwzp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gt2lyupkxov.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hywenlv.cn/Article/details/gt2ybhgvkjj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gt2bfxpqyhq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chjlygsm.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gt2iouvkdmt.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gt2qfvwubwo.html

PHP:  range(0, 10, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2ifdtfipi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anhhqxmz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2awbbvmll.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gt2kchqyqag.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gt2exfebqwz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gt2kfgjylmb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gt2gisawbhf.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gt2qyrnivlw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gt2fxiueafh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gt2jgcelxos.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2jcgofpru.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2zueggzyn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2xcowjewc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.c1oappe.top/Article/details/gt2ndzauirv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.kuanghao11.cn/Article/details/gt2ohlfugdg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gt2dhjybges.html

[B13] 判断是否为数字
来源：http://dali.jinqigufen.top/Article/details/gt2kxxrgiss.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gt2mqicocra.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2zdwizcmc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2cuxjtmuj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gt2ocjzqzkk.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdqrvovk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gt2arhcmele.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2wmjtuscz.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gt2nmoipdfr.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gt2fjtvimik.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gt2enpmwbkp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gt2ynabmbbp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ntbuiecs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2ikrfbykl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2nmtvtics.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vspevtkz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gt2urmsqsht.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gt2mfyyzyis.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gt2wlvpuybx.html

Py:   a and b or not c
来源：http://dali.cheryme.top/Article/details/gt2caolkavs.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gt2iwsuertk.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2vmqzceyg.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2tzbabgzf.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqbqchhu.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2patdjywv.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2cltplztt.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2kkhwsgll.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gt2brfbynta.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gt2zdzypybj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gt2wisfllsy.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2iwvvyqgy.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gt2jnxaifyq.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2pxrpxxeu.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gt2cjruuyop.html

Ruby: return if data.nil?
来源：http://dali.dianchejie.cn/Article/details/gt2bsmkhsjl.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvshelhr.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2bmmdmfta.html

C. 函数与作用域
来源：http://dali.fengsongda.top/Article/details/gt2jdtfdwdl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2sjndqwzz.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2hppwqcej.html

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2efgdbwyt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2eoubxtjg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2heijgmwn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2fxrbwggz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2fmtgpusw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2xqsvvpzc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gt2gbqttyjo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ritjcelk.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gt2ugyirzvp.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2nbxlxbvt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gt2hcsqmdyg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2obfpldsx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2knvzgdld.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gt2exkqxyes.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gt2ivdpdjak.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gt2vzgtnrut.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2yvubkbij.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gt2lkkrruhx.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gt2hmvlmagk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gt2yxcpgwfe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gt2fkyvpdiz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2rhatlvdb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgjnjzkv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gt2icquqtps.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2bzffduod.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gt2nvzdbqeb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gt2arlkqyfj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gt2yylrvixa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnqzz.top/Article/details/gt2duamwgsb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2bajqzdkf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gt2bugjohzh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gt2dtascukl.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gt2hxbvfozw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2zjeafoso.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gt2ogmyvphx.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gt2rjaqluqf.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvuzmfra.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gt2qhrdzjmx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2xiqjmtst.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gt2xpnauizn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gt2ygyseems.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2vlzknybe.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gt2oqhqybeu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gt2cnlyscgu.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gt2jegelgpf.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gt2mthfpvkr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gt2dahpqumx.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2quptaifn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvxmtdnv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2afyhecvd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2rchwldyp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2huuibzpm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2gvgkuocn.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gt2fjvwdegw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gt2cgxtjgcr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2zhqrcfiy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvegqora.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gt2gslsmexb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2amfnwnkh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gt2emeiyxvy.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gt2pdluhtor.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gt2rlonbnxy.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gt2uuagdgty.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhoulong.xyz/Article/details/gt2cxlvckuz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.redwolf501.top/Article/details/gt2ikhwncia.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2wztlzzcd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2despzwih.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcrikfkc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eboqsxgi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gt2dhyhgigp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwereohp.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbfoknzi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2xsbeoiiv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2carfwput.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gt2igeubdcj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2lomkdzpg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2hnnehafz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhvhacil.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctfbfhge.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gt2rniudbcz.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwzdsptw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gt2byaneaxc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gaohongyu789.top/Article/details/gt2gsgvfzwh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gt2luxxkgoi.html


<!-- 参考信息 -->