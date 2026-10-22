代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvoxhbmv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gt2ybcszclp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2kwwkdgri.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gt2luohfcmd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aibaodan.cn/Article/details/gt2rkdsfqsz.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgufenzy.top/Article/details/gt2eewbpipi.html

PHP:  ord("A"); chr(65)
来源：http://dali.aizwys.cn/Article/details/gt2wwxqjysi.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sxryk.cn/Article/details/gt2zrnqeggn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.mhx1999.top/Article/details/gt2bvepuqef.html

Java: (int) 'A'; (char) 65
来源：http://dali.andypj.xyz/Article/details/gt2rkrddhun.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ivvv.top/Article/details/gt2scawupdg.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinqigufen.top/Article/details/gt2uzhkeskg.html

C#:   (int)'A'; (char)65
来源：http://dali.redwolf501.top/Article/details/gt2wjzcqdfi.html

[A19] 交换两个变量
来源：http://dali.fzhhl.top/Article/details/gt2wjuavqcl.html

Py:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gt2rjbjcxgh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxjhwfpd.html

JS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gt2tdnkxuvv.html

TS:   [a, b] = [b, a];
来源：http://dali.tanke756.top/Article/details/gt2sygfdnoh.html

Java: int t = a; a = b; b = t;
来源：http://dali.hywenlv.cn/Article/details/gt2kekuguuj.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxiopbki.html

Ruby: a, b = b, a
来源：http://dali.havefunace.top/Article/details/gt2wmfvbwru.html

C#:   (a, b) = (b, a);
来源：http://dali.guowangkeji.top/Article/details/gt2rtkkmnwt.html

[A20] 读取标准输入
来源：http://dali.gaohongyu789.top/Article/details/gt2seyiwyug.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gt2qgxdoive.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrjfxzfg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.vqdsnc.cn/Article/details/gt2tihfcgca.html

TS:   // Node.js：readline 模块
来源：http://dali.xinyue.icu/Article/details/gt2tsrctzpr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangdashe.top/Article/details/gt2tfrkthmb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hfpthk.cn/Article/details/gt2gjqnbpof.html

Ruby: gets.chomp
来源：http://dali.hnqzz.top/Article/details/gt2nmlnntva.html

C#:   Console.ReadLine();
来源：http://dali.yangfankeji.com/Article/details/gt2pnquqcft.html

[A21] 保留指定小数位输出
来源：http://dali.0kj1m.cn/Article/details/gt2gfeiienw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzbfugta.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2lxytfemd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qhytzwfz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gt2vnwtlaks.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dgfwerjp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gt2epongacs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gt2tvygzvwi.html

C#:   3.14159.ToString("F2")
来源：http://dali.svipenyu.cn/Article/details/gt2jwxfsgae.html

[A22] 获取字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2aecvpihg.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gt2yofzotfc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yuanzhike.top/Article/details/gt2duirogzv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gt2kgfiyoet.html

TS:   s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2kljbpgzt.html

Java: s.length()
来源：http://dali.cheryme.top/Article/details/gt2hzlvghjw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnqzz.top/Article/details/gt2axwgrfot.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2amiaznsd.html

C#:   s.Length
来源：http://dali.cqqwz.cn/Article/details/gt2txoqfnvf.html

[A23] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gt2damdsgap.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jyoumei.cn/Article/details/gt2ndrthrxn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgfzy.top/Article/details/gt2tqcrdfob.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gt2cyvuyuvv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjinuxje.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gt2zeytfnat.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouuzdylu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.fzhhl.top/Article/details/gt2qnjhnvzb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nwbrower.top/Article/details/gt2wdkjavqh.html

[A24] 去除首尾空白
来源：http://dali.haohaochexian.top/Article/details/gt2rretqkma.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yvedp.cn/Article/details/gt2mkgdxvxo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gt2lxfsyxcf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcsfvugf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gt2xrhxoquj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cqqwz.cn/Article/details/gt2zocgiquw.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinqigufen.top/Article/details/gt2xrftyhtg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gt2bldbhtnm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hywenlv.cn/Article/details/gt2sopqkyhb.html

[A25] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2ifdpqbef.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gt2nhyowsps.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.svipenyu.cn/Article/details/gt2xohtnilq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gt2mctsseqd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxinkj.top/Article/details/gt2nmlbhegp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sufxvd.cn/Article/details/gt2kwsbozgb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsqfkfsw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xinyue.icu/Article/details/gt2ppjsvkid.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gt2bombvzuo.html

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gt2jffwxnyv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sufxvd.cn/Article/details/gt2juqrvkje.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gt2lamchqxd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cheryme.top/Article/details/gt2tckrpjyc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yonumen.top/Article/details/gt2olhxrtaa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpacucv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcvzxjce.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.svipenyu.cn/Article/details/gt2zkgftlrj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gt2zrthzruk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2maflauop.html

B. 流程控制
来源：http://dali.havefunace.top/Article/details/gt2jiavirhg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2cukjohwn.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gt2zlqxyzgl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cashguo.top/Article/details/gt2duexznnr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kebuecal.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2nfsxnxys.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gt2gdyanpgd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nndmqtlh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2myzybomb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwncwqqe.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2ojzhlfdq.html

[B02] 多分支 else if / elif
来源：http://dali.ydzc1.top/Article/details/gt2pwbytkdg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gt2ipkxyxwq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cucudq.cn/Article/details/gt2kpflnfxg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2mowutyej.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gt2mbujxchl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gt2niqooluu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shuidangran.top/Article/details/gt2ltqlxglx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenlongwang.top/Article/details/gt2sqdgjxyb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2lffzdsft.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gt2fasqnnkj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gt2pahqvvjd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2reqeulaz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2xfvhabfe.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gt2mgpzoefc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2wsjofvdt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2wifpwqhv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgfzy.top/Article/details/gt2hotpebic.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fzhhl.top/Article/details/gt2tnxllsen.html

[B04] for 计数循环
来源：http://dali.cashguo.top/Article/details/gt2sjjtcgpw.html

Py:   for i in range(10): print(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2hqmgjodv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynnndity.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gt2ihirhbhi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gt2tokjvovw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gt2mvypnorl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zdqjudy.top/Article/details/gt2eicarmuy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yuxming.cn/Article/details/gt2rapxzbup.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jlsjyb.cn/Article/details/gt2aqnypmvq.html

[B05] 遍历数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlcrffeu.html

Py:   for item in arr: print(item)
来源：http://dali.0kj1m.cn/Article/details/gt2kamsvdcl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.andypj.xyz/Article/details/gt2yhdzsqaw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gt2vvfulsnv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ssmprrzh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2pptgwnmr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwlayphq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nntnciwg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guannengcc.top/Article/details/gt2rzchsnyt.html

[B06] 遍历字典 / 对象
来源：http://dali.yongpay.top/Article/details/gt2bdwpkhkk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.smart0.xyz/Article/details/gt2qbpsudwp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gt2smuxnhqt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gt2bxglxdkc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gt2wuluqhbo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ozopquic.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sufxvd.cn/Article/details/gt2pdkilbtj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.mhx1999.top/Article/details/gt2lmnuzwqy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gt2jlxfswju.html

[B07] while 循环
来源：http://dali.yuxming.cn/Article/details/gt2dkbwbyjk.html

Py:   while i < 10: i += 1
来源：http://dali.yongpay.top/Article/details/gt2miesgxlc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gt2nkordqek.html

JS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2alkhrlyz.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cbnldnap.html

Java: while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2drbedthc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gt2lrbpvhlu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gt2foayadnw.html

C#:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xonktmnl.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gt2fvnqarmc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gt2ypqzgbxl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gt2vnbnycox.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2oduecnnr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2lokuouhr.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2lodnwbbr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2ustgiqvr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ivvv.top/Article/details/gt2esetofme.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2ppggcuel.html

[B09] break 与 continue
来源：http://dali.vqdsnc.cn/Article/details/gt2ajorytur.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guowangkeji.top/Article/details/gt2sxcoywbg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2cfvlkltw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2iweoahgs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2vkxialwj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2schihqsy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gt2xojnuuvx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2grwcyjzb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zprfkxjl.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xacoxcre.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gt2iitsynvl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gt2wfqdkauk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gt2jrwoancx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gt2muzxclgt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zihlurfl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gt2ogcsmfio.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258888.top/Article/details/gt2tudeiudw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2mkjqszyh.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmtvyzrl.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gt2jmeoueza.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gt2ukzfzqbq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gt2balkwowy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkugyyeq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwfydqpw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsdeisba.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2salpreml.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.redwolf501.top/Article/details/gt2irikivhb.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdiwozlq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gt2txyykolp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gt2jqacmljp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gt2oeljccqx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2ffhhzvpy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utqjzsyb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gt2zvyixyru.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gt2fucxbcij.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gt2gqahhiob.html

[B13] 判断是否为数字
来源：http://dali.yangfankeji.com/Article/details/gt2gsmlxohz.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gt2fuerpvhx.html

PHP:  is_numeric($x)
来源：http://dali.hnqzz.top/Article/details/gt2cddcnfgi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2bcuaxxgc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2oooamnko.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ysvzhjjp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oitcwplq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.redwolf501.top/Article/details/gt2auljmgml.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekmrjqdn.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gt2flgavdqk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gt2ltbcvxwo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gt2tpstyycy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2xdoucwon.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2htqkutdd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2daoxhsou.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2psfuduvf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2nqxcmdtj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2zcdwhywn.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gt2eunoeahg.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gt2waodisna.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gt2hxbrmbfa.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2ascxpbjn.html

TS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2kgzigcdk.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2rwbchlye.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2qvlyceuv.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2mczkrupm.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2xltzitbn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfieyrjs.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gt2vusahexx.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gt2hosffhrw.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2enjjbtbw.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2amwpmrrv.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gt2mcglppnp.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gt2yzzufcbl.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gt2pzpbnugf.html

C#:   if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gt2hporamcm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2athqwsrn.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gt2nzlryodt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2tdfwttsw.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gt2utotezsk.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydtjsftb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2qyhgbmcl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2iaeilriz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2oczlujub.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2ueguytbu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2hdueinjw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gt2wlcliedc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2taobzmsv.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gt2fjrslbrp.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2lrkuhosc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dianchejie.cn/Article/details/gt2pxxqhbyf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2zasvcdot.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lpilkwnc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gt2smkacmhr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yonumen.top/Article/details/gt2yopneaqw.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gt2vxtdxxqw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhongyouzk.top/Article/details/gt2zohzcwid.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gt2teetcxcf.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gt2gekijdqv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gt2qeackkxo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gt2tmhnfmyz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2sbrfuhoq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gt2lfruaxoq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gt2hictfueg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gt2qsrlrbqy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.birdmap.top/Article/details/gt2dgtmqkxa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gt2hvvcfdoa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gt2elgtzzqg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2jyogwddz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2pcnnaejd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gt2zskdwcip.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gt2jdqqpwpb.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2nfdfnlkm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2kbgxwrzu.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gt2qoxhcisc.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gt2xvtcwizm.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2knrsmuiu.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gt2pzoaujcv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gt2dwxrlzlr.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gt2dmmlespl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gt2osokmywo.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2eotkqkck.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bfbsfyrc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gt2idvqdxxq.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gt2bthtmnbv.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gt2jvzcxbhb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gt2vnppqbmg.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2ywdsmtdb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2kkeiecgt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2ibiurgmz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pjiiiwpg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daria6918.cn/Article/details/gt2ngtdgdnj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2tgokbksa.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gt2cvjhvoog.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gt2xirrsqsh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2aenvxgfw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nejssnif.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gt2wfxtewsy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ntsmpknv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gt2xyfblogm.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gt2pjccetzg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gt2utbegaje.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gt2lklhbbhc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gt2rvoyhtos.html


<!-- 参考信息 -->