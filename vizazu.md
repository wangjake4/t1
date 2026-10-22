代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gt2sfqplhuh.html

Java: (int) 'A'; (char) 65
来源：http://dali.svipenyu.cn/Article/details/gt2brgxnkgw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.redwolf501.top/Article/details/gt2vgcfhtaf.html

Ruby: "A".ord; 65.chr
来源：http://dali.dianchejie.cn/Article/details/gt2jyfvfcti.html

C#:   (int)'A'; (char)65
来源：http://dali.cdnleiting.top/Article/details/gt2onkcfnfd.html

[A19] 交换两个变量
来源：http://dali.smart0.xyz/Article/details/gt2eazhhkzc.html

Py:   a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gt2yztcoerw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhengqikj.top/Article/details/gt2dxendmqk.html

JS:   [a, b] = [b, a];
来源：http://dali.jianghu66.top/Article/details/gt2rdqvleba.html

TS:   [a, b] = [b, a];
来源：http://dali.hongshengwenyu.top/Article/details/gt2moijtoxr.html

Java: int t = a; a = b; b = t;
来源：http://dali.tian-w.cn/Article/details/gt2yghksjvd.html

Go:   a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gt2yzamvwte.html

Ruby: a, b = b, a
来源：http://dali.yongpay.top/Article/details/gt2pccovtnv.html

C#:   (a, b) = (b, a);
来源：http://dali.andypj.xyz/Article/details/gt2zxjkirxl.html

[A20] 读取标准输入
来源：http://dali.aibaodan.cn/Article/details/gt2iqumdfyj.html

Py:   name = input("请输入：")
来源：http://dali.316326.xyz/Article/details/gt2craddkzc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gt2lptdezmf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuoztvg.html

TS:   // Node.js：readline 模块
来源：http://dali.ppjwa.cn/Article/details/gt2jgugxnhj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ieaplgez.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aizwys.cn/Article/details/gt2nysyhuhd.html

Ruby: gets.chomp
来源：http://dali.zycfv.cn/Article/details/gt2xmkeqzxx.html

C#:   Console.ReadLine();
来源：http://dali.9152youxi.cn/Article/details/gt2awtiqhtb.html

[A21] 保留指定小数位输出
来源：http://dali.hammf.cn/Article/details/gt2jvzjwzuy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zycfv.cn/Article/details/gt2lqtxfxrx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gt2jwkxwmlc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gt2zozfbhrs.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykpjuuim.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2xdzvttkb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gt2hshuhesx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gt2yohxlaui.html

C#:   3.14159.ToString("F2")
来源：http://dali.shuidangran.top/Article/details/gt2brcmecld.html

[A22] 获取字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbobeswn.html

Py:   len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2fbdavjpi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.iojbl.cn/Article/details/gt2boqhwbgd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daria6918.cn/Article/details/gt2revshcwv.html

TS:   s.length
来源：http://dali.ydzc1.top/Article/details/gt2qjofcfks.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gt2oozyruzf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.316326.xyz/Article/details/gt2gsoijbwg.html

Ruby: s.length
来源：http://dali.yj20258.top/Article/details/gt2vdhfmlxj.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gt2bxycppgl.html

[A23] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2upnvmsfb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2fhrvyefl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgfzy.top/Article/details/gt2nwqspohq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ywebhcnz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gt2wurwtrkh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gt2kcjmmlnx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ivvv.top/Article/details/gt2yruxurok.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gt2oprireqk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shzxlz.cn/Article/details/gt2ilxxtkev.html

[A24] 去除首尾空白
来源：http://dali.nanxinkj.top/Article/details/gt2qukveuve.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.bjfxy.top/Article/details/gt2cwavxvcn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2roebnlgv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sufxvd.cn/Article/details/gt2zsztrkse.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbgsayws.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tianlin.xyz/Article/details/gt2hqsehjgo.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2vjxdfdgx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.9152youxi.cn/Article/details/gt2ugpqjglu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ltchiutb.html

[A25] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2bnilkqmb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbdjqlta.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.bjfxy.top/Article/details/gt2rfkdurad.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gt2netgznmf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yangfankeji.com/Article/details/gt2jrfklabr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tian-w.cn/Article/details/gt2ozqodtjz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gt2dhppffmo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuanzhike.top/Article/details/gt2mlqvoqkt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gt2kdzqmzny.html

[A26] 类型转换总览
来源：http://dali.yanxiufei.cn/Article/details/gt2gxhoxoqp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.vqdsnc.cn/Article/details/gt2pkpsyyed.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqxogtwn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gt2yhhfwhke.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cheryme.top/Article/details/gt2kdujevov.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gt2hlhadxxv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yueranfly.top/Article/details/gt2pavltzjm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnqzz.top/Article/details/gt2ahhqpqoh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gt2shbrrpyr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2nnysmbcb.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gt2bkawitxw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afwgycim.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gt2pgsdpwzp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.bjfxy.top/Article/details/gt2iwjgsytb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cdnleiting.top/Article/details/gt2mgffybrj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gt2hwggaisd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2alflgepm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrrcxowg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gt2vcgjrnni.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yvedp.cn/Article/details/gt2sfruabln.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gt2lcadesij.html

[B02] 多分支 else if / elif
来源：http://dali.hnxiangtu.top/Article/details/gt2xoiqljwo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gt2igopuddm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nwbrower.top/Article/details/gt2nfwuwzzj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvvpqowe.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gt2htooxxvw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2jkifpsfh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj20258888.top/Article/details/gt2wpgwmafc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ehwqpu.com/Article/details/gt2bakkhsya.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2svuswnia.html

[B03] switch / match / case
来源：http://dali.kuanghao11.cn/Article/details/gt2noyopucr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dskagadr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gt2vhrxctfn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2dgtxndty.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2hgethmdd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2ylxjcqge.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2digujfjg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cheryme.top/Article/details/gt2ueneclnp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gt2whrufzkv.html

[B04] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gt2vfgnchpz.html

Py:   for i in range(10): print(i)
来源：http://dali.gzhubu.top/Article/details/gt2wtfbtfvu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yepoecns.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gt2wfxqktue.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gt2sesiqrtb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtjxknlm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2alcuwyog.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gt2avqdoqjy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xziqi.cn/Article/details/gt2oogmjhrc.html

[B05] 遍历数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2yfmbaglr.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gt2pkgwtfom.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gzhubu.top/Article/details/gt2fdzdpckm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gt2zizesaoc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gt2toxgiwfi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258888.top/Article/details/gt2qoxdxqxn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gt2jwxidnnc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gt2cntqspis.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gt2gdjgxtzn.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gt2yguvpfxs.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyucfntz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cqqwz.cn/Article/details/gt2hbsepfch.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gt2znkcbkmt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gt2hfxpdqhr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fzhhl.top/Article/details/gt2tsgfurcs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gt2itnvqxiu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tanke756.top/Article/details/gt2dzspctyl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zdqjudy.top/Article/details/gt2ybfzgrhr.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gt2vxvydqgp.html

Py:   while i < 10: i += 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2iojldzim.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.c1oappe.top/Article/details/gt2oylqqogi.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gt2ovyrnlxe.html

TS:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2shzagalg.html

Java: while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2kezhzlps.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yeisiydq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2fevbnrvl.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbczfsai.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gt2wyrldzqm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcchzwct.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2hpcdzmbi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2yqmmcfse.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjfhmptd.html

Java: do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2sgzmgeei.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gt2uqclglqf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ybcxt.top/Article/details/gt2nhvswclo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2wdtunjrk.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gt2etwxnzmi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gt2vaypuuvp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2rihokcui.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2qrtiixjt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2uymjlctz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2ndfqwfvy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbtvltln.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.0kj1m.cn/Article/details/gt2dqepcwnl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2sumyxuov.html

[B10] 遍历同时拿索引
来源：http://dali.xylfe.cn/Article/details/gt2rhchytqi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258888.top/Article/details/gt2cwkierts.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gt2qvavajyr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gt2pyrgyxhp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2fmctcrka.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gotoacloud.top/Article/details/gt2jmdcelwo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nwbrower.top/Article/details/gt2nutacwbx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wilgddrb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sysykeji.top/Article/details/gt2srnjirzb.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gt2ocdtuspu.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gt2vfosskgp.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gt2uidzotrg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gt2ndqaqhoa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gt2szifzblb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2tvrbeaaj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cucudq.cn/Article/details/gt2fvyapwyp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gt2syphyvgz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2vsbvzder.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gt2okbzxmqq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.0kj1m.cn/Article/details/gt2gwvxzzbc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gt2tbwhinrs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gt2eehfvkps.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gt2dzdohcjd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2vhicfcne.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangdashe.top/Article/details/gt2spnydues.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2tqssblse.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gt2nvywcqtn.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gt2ljdmyeho.html

Py:   isinstance(x, (int, float))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbuizixz.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gt2zebchvlf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2vqpvxkim.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2pqlotjxr.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpgwijdg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gt2gtaishzn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gt2aidempda.html

C#:   x is int or double or decimal
来源：http://dali.iojbl.cn/Article/details/gt2erexwsby.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gt2liyhkdwq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gt2nazqlhib.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gt2slnpijbc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2udhhdslt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2kwxmpffj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gt2jidlonwu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2ssbvemwa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2emuwsrly.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2gjtixfxc.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gt2oaiquled.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snmseabe.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gt2ichgfbdw.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2mxfyoldh.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2poljibzq.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2rlizguzb.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2ntuujgru.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2qmegaluv.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2zkbovqcg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gt2qpkxpuah.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gt2ybazdyen.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbkpyjem.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2nuojjcsf.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gt2guujmgyw.html

Java: if (data == null) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eleeswif.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gt2vcdgwhzl.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gt2ayfmniyg.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2shshpkkw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjeckagm.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqisgxpj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2rhvefgkb.html

[C01] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gt2pjqirkyw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvxvvvak.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2cbqphrps.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2alhbncms.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2ovllflpj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2hemrgezb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gt2gyzmqnkc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gt2sasfdrue.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2mfzddejg.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2jedbvaux.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gt2dpfbqszp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rptjvmyf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2dasihexi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2ttdqpgda.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gt2remrtlpn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gt2fgdzlqae.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gt2zlnplqge.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2piscirsn.html

[C03] 可变参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2yusfxdbi.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gt2ugkiorss.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kfxrusor.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gt2qtfysnhx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gt2sahjwkco.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gt2rfapneks.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gt2ebdtjtte.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gt2bfflkmmp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gt2hmwdelfx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gt2rproyapb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gt2uuqfodjq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnqzz.top/Article/details/gt2bkjrjnlw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2oqceyofe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gt2hgcopgru.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gt2cmbfwwlt.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gt2skeepzqq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2wjzkvuig.html

C#:   f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2vyaxlnfs.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csgfkrxn.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2hzwhqlmw.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gt2mbyrkiut.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2toidpmjn.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gt2dvlxpbol.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gt2dyquhbtx.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gt2vwdmktvh.html

Ruby: return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2yjvluzcy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gt2cncxyqem.html

[C06] 匿名函数 / lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntemfqod.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2cppgefsn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gt2bnoxjpny.html

JS:   const square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2frgqymqi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sweek.top/Article/details/gt2uyfwyelj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2qnobxwto.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2msntxpge.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gt2wyxlngja.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gt2fcqvubtm.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gt2dnvqnmrx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gt2pklwyucz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2pmeqwdtq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gt2beipilpn.html

TS:   arr.map(String)
来源：http://dali.gotoacloud.top/Article/details/gt2ruiywrtn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2mresmrkt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gt2pbrbhhjy.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2emkonoee.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gt2wzkxyjpp.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gt2gicdlikk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gt2ozpagjpc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gt2qnysqlvc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2zloywtvr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2nyedkcox.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gt2cylxldxt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gt2cmvwmwqb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gt2xsdebdjh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2pvfjswvp.html

[C09] 递归
来源：http://dali.zhongyouzk.top/Article/details/gt2mtmphcbc.html


<!-- 参考信息 -->