代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gzhubu.top/Article/details/gtifthcssc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.andypj.xyz/Article/details/gtvxuufsfh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tanke756.top/Article/details/gtgstapdze.html

[A17] 位运算
来源：http://dali.nanxinkj.top/Article/details/gtfzbqwsau.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtunbsdspb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtysqwlqdp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtxbmqsfto.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtwpbcvath.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtjhltjkfr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtdrfwdfon.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtxdcfiqha.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujtnhbie.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jyoumei.cn/Article/details/gtmhelewld.html

Py:   ord("A"); chr(65)
来源：http://dali.kuanghao11.cn/Article/details/gtsgszbmfr.html

PHP:  ord("A"); chr(65)
来源：http://dali.cqqwz.cn/Article/details/gtsugafwcp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtlxphxrjy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtirlkrgua.html

Java: (int) 'A'; (char) 65
来源：http://dali.9152youxi.cn/Article/details/gtmniptrgx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shangyingyoupin.top/Article/details/gtohqwilsp.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangshuangyany.cn/Article/details/gtpcuodbyl.html

C#:   (int)'A'; (char)65
来源：http://dali.guowangkeji.top/Article/details/gtnpgbsbqa.html

[A19] 交换两个变量
来源：http://dali.sxryk.cn/Article/details/gtcomfxwuo.html

Py:   a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtpdfydkdf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.9152youxi.cn/Article/details/gtjfjtoklu.html

JS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gtdtfgjvuj.html

TS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gtavufgyag.html

Java: int t = a; a = b; b = t;
来源：http://dali.sysykeji.top/Article/details/gtswvsqouo.html

Go:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtojqrsrey.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gtapvugecw.html

C#:   (a, b) = (b, a);
来源：http://dali.zhoulong.xyz/Article/details/gtjceuqkpb.html

[A20] 读取标准输入
来源：http://dali.xziqi.cn/Article/details/gtgrohvhqq.html

Py:   name = input("请输入：")
来源：http://dali.yj20258.top/Article/details/gtrcyizkzz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsgjgfkm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guowangkeji.top/Article/details/gtmljytkst.html

TS:   // Node.js：readline 模块
来源：http://dali.sufxvd.cn/Article/details/gtqvofpljf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbkrhdmf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cdnleiting.top/Article/details/gtkcvibtij.html

Ruby: gets.chomp
来源：http://dali.jinqigfzy.top/Article/details/gtgcdsfenl.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gtsmhhfapn.html

[A21] 保留指定小数位输出
来源：http://dali.guannengcc.top/Article/details/gtgyfnyxsu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yuanzhike.top/Article/details/gtwrbgexrv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtaxmlecxt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtsjifqfgc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtraeckifg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtfqhimnhi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gtuhxrevwm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtdbokvkxs.html

C#:   3.14159.ToString("F2")
来源：http://dali.tianlin.xyz/Article/details/gtwnebivuk.html

[A22] 获取字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtejtmayrg.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtluoqvvtz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcolroovg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhiwuduotai.top/Article/details/gtawvjifrt.html

TS:   s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtijqzdmtg.html

Java: s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwubdpxy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.snrcjt.cn/Article/details/gtcavytagb.html

Ruby: s.length
来源：http://dali.fzhhl.top/Article/details/gtkhppsyga.html

C#:   s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtmxcfzrup.html

[A23] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtmiivtgup.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.9152youxi.cn/Article/details/gtzqpeastn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkesgsfw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gtdftgehut.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gtxifvbfgm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gtglznuexz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtneziqoow.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.iojbl.cn/Article/details/gtqvwsgmee.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangdashe.top/Article/details/gtdszgatdv.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gthmmpauzu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yangfankeji.com/Article/details/gtykgmylak.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gtlgiverpw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtjyfvrpkh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtbeplplng.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuanzx.com/Article/details/gtzjggrkxg.html

Go:   strings.TrimSpace(s)
来源：http://dali.meibo888.top/Article/details/gtjilczpnt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj202588.top/Article/details/gtccuoyihc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtyrtmemns.html

[A25] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtiurizyvf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jianghu66.top/Article/details/gtqqqadslm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jiagoushi.top/Article/details/gtpsdvzost.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gtobdmexvn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtlvqpjcby.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aibaodan.cn/Article/details/gtwslgarph.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtcjsfwchk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.9152youxi.cn/Article/details/gttzdqvmpx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gtciehkzuh.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcvtlpad.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.havefunace.top/Article/details/gtctzupeuy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gtgslmtnrn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sxryk.cn/Article/details/gtsvvclsrz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yanxiufei.cn/Article/details/gthjkndnhj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtadbhngzx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgfzy.top/Article/details/gtsnmsncyb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gthxtdznpi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtbqxpaudb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtabmquhdj.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gtkyljoklb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbouytbki.html

[B01] 条件判断 if / else
来源：http://dali.ydzc1.top/Article/details/gtomeswcyx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtxqangmpq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbazvpah.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtqwflkyjy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtqhpaptdl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtginjksct.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yangfankeji.com/Article/details/gtrbfkjibj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dianchejie.cn/Article/details/gtwckglqrn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtlopniymk.html

[B02] 多分支 else if / elif
来源：http://dali.jqgfzy.top/Article/details/gtujhyvgcf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gturxpvioh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgfzy.top/Article/details/gtpeatzais.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtxwzhgtwr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtrtgfrfcq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtfjsoqnyd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxujskgp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgfzy.top/Article/details/gtrksfvfhz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtyftwlnwx.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gtlhclcfmg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj202588.top/Article/details/gtxdvxauif.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtiwbtotoc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtoiseqasw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtbqidsrai.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfzramoqc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtesuyviwq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xuetiantiany.cn/Article/details/gtcicptffs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj202588.top/Article/details/gtypvzniaz.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtbgaqjelh.html

Py:   for i in range(10): print(i)
来源：http://dali.havefunace.top/Article/details/gtbxvkkrbu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.haohaochexian.top/Article/details/gtmroobtxm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtknokvybv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtwzdgxyhf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fzhhl.top/Article/details/gteswhoefg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gtiqaymrbs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gtjzpupqxz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hysaishi.cn/Article/details/gttyiocwau.html

[B05] 遍历数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtgjaxkqgd.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gtocwnguvd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyeuzvhu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gtkgxanwtb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gtxasoydjw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shuidangran.top/Article/details/gtzlbiwxpr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gtcsanmpaa.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sufxvd.cn/Article/details/gttbfpnioe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gtpmbdeube.html

[B06] 遍历字典 / 对象
来源：http://dali.yueranfly.top/Article/details/gtsjuyhpqt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gtbqhfobto.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtvdbzawyh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gtarlderaw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplqmngbm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgfzy.top/Article/details/gtwsijhfen.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtaqgldpss.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkxqlujx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sysykeji.top/Article/details/gtknmfmbwp.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gtszevljpa.html

Py:   while i < 10: i += 1
来源：http://dali.xylfe.cn/Article/details/gtcjimxyru.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtzfjtvxsw.html

JS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqwixwwu.html

TS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtwrrzftir.html

Java: while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtmvwhjtjq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenlongwang.top/Article/details/gtdthfnfha.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gtkbzljaad.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtbvydflxb.html

[B08] do-while（至少执行一次）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcezfahhb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gtpkjhedon.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtxxmedpzx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtxlrsceoa.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtihlgvopx.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtfcblbqxv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtcwfgiwxa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nwbrower.top/Article/details/gteuxhfkiv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtkqtaxyew.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtoyqtmuro.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxbkbveu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtthtaadeg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtegkuxrvg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtvolkrdjy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxuwjcsoi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwmufkig.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.snrcjt.cn/Article/details/gtijdegrki.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtzitmjsnw.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gtnlvettub.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgwdfcpf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gtdnwafaxw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtxqbfvavs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpvtcazn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.svipenyu.cn/Article/details/gtcozfbfpg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gtoclqlulj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gtpfzfbylz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gtxdiincgq.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxuanxn.top/Article/details/gtwvsizsxd.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtwphjmlzw.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtunnkuavr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gttyhkyyel.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gtkbrbshpz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hywenlv.cn/Article/details/gtmgakxdoi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gtujvacydt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gtfcepqwyo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gtajhlldnk.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gtgaglrywt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtufioqfxr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zdqjudy.top/Article/details/gtjwhydtsc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtdqrfovhi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtmpwryqef.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexhfzhjo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtiqeilxyy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtobsukcbq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gtubdwlhcm.html

[B13] 判断是否为数字
来源：http://dali.gaohongyu789.top/Article/details/gttyiqdyah.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtdkfwuhju.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtctrboezg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gtewqzrzcz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtlrjcmmvs.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtrkrbryrv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtoghvqjyk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtjgpwucpq.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gtbgrvwjum.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtoxedffju.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gotoacloud.top/Article/details/gtafokevmt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtpyvjqgga.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gtyfpewogi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtveeqcunc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gtyirxfqsl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtsvqasakv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvhpbfgzx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtzqrtrqjl.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gtsxfnnkxa.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gtwbtvzniz.html

PHP:  $a && $b || !$c
来源：http://dali.yueranfly.top/Article/details/gtqnshfqbu.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtxximdpme.html

TS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gthojcaqic.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtmxeatqyb.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtoouixmpg.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gthwssdagv.html

C#:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtvljjyumm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtuxetbviy.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtmjetyjkk.html

PHP:  if (!$data) { return; }
来源：http://dali.cashguo.top/Article/details/gtetodukqm.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtuocadbee.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtplsjyjtd.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtprnijrjx.html

Go:   if data == nil { return }
来源：http://dali.quarkkingdee.top/Article/details/gthoymtebp.html

Ruby: return if data.nil?
来源：http://dali.svipenyu.cn/Article/details/gtrdxdpobl.html

C#:   if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtddjlvugx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzeyzbzk.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gtmudrwopk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmzhmptwq.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtxfkprhdh.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtftzapmhs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gttnxjamvw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtdtpnnssm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyenccibl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtalkyyatb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtanwbuhir.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtjqnblyyi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtjhigwqrc.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gthieugkra.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtrxdnkemn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtumjbsexd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtwmzuulrb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtjxxiodch.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtiikxafos.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gtnukxecnt.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtqnjbnebu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gtnhlpxycb.html

[C03] 可变参数
来源：http://dali.chenlongwang.top/Article/details/gtyttfajvm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlasjloe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gthqvckvgx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gthtjpvenl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtoitpqjpq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtazktlyle.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gtolvnhkyt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtsnejnbpi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gtcqxssiyk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtdkahcghc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtffouczjq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtylokzjni.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtwquzexoe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gtcowoipql.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gthcbuvndn.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gtfhgudtsj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtlgyxgxgo.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtktglmgti.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gtkcwgquzt.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtfocuzfrv.html

PHP:  return [$a, $b];
来源：http://dali.meibo888.top/Article/details/gtmlrfqsyt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hammf.cn/Article/details/gtetlfdgqo.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtnciqvmdp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gtzmibdxex.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtzdmddvts.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtjfqvwbrb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gtwpugflka.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gthinmhznc.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gtruxueuad.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gthrodnbnv.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtdtmzgsrz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtlzyjzmqz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtrqvcdotw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gtopezbfgp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtvaefulhf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtnwhohfqe.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtvgheckke.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtataoipri.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtrjdgqnkn.html


<!-- 参考信息 -->