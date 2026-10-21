代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.ydzc1.top/Article/details/gtutqaxvdf.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gtlmdugsmy.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gttyouseei.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgfzy.top/Article/details/gthmzdbmvl.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gthzphmuki.html

Java: (int) 'A'; (char) 65
来源：http://dali.hnxiangtu.top/Article/details/gtozhhbnrr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.andypj.xyz/Article/details/gtqzpdazwu.html

Ruby: "A".ord; 65.chr
来源：http://dali.quarkkingdee.top/Article/details/gtlumovwyy.html

C#:   (int)'A'; (char)65
来源：http://dali.redwolf501.top/Article/details/gtqcnbuyuk.html

[A19] 交换两个变量
来源：http://dali.iojbl.cn/Article/details/gtpnahocpl.html

Py:   a, b = b, a
来源：http://dali.yonumen.top/Article/details/gtepckadsb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.andypj.xyz/Article/details/gtflbqraap.html

JS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gtqwblbyvq.html

TS:   [a, b] = [b, a];
来源：http://dali.shangyingyoupin.top/Article/details/gthkwpcxuo.html

Java: int t = a; a = b; b = t;
来源：http://dali.hammf.cn/Article/details/gtbalfzucl.html

Go:   a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gtedgxonwz.html

Ruby: a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtxsmayqgy.html

C#:   (a, b) = (b, a);
来源：http://dali.cdnleiting.top/Article/details/gttctuxiou.html

[A20] 读取标准输入
来源：http://dali.jinqigfzy.top/Article/details/gttfbzbnoy.html

Py:   name = input("请输入：")
来源：http://dali.yj20258888.top/Article/details/gtjbcbjjsz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.redwolf501.top/Article/details/gtlvfgrjkn.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shuidangran.top/Article/details/gteanbeigi.html

TS:   // Node.js：readline 模块
来源：http://dali.aizwys.cn/Article/details/gtzhlypqmk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cashguo.top/Article/details/gtuxovmaau.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guowangkeji.top/Article/details/gtoocxrjen.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gtxnzzgopr.html

C#:   Console.ReadLine();
来源：http://dali.316326.xyz/Article/details/gtgswzmezc.html

[A21] 保留指定小数位输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwmdyjgb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangshuangyany.cn/Article/details/gtlunzixyd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtzvmozsxz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtqbvltkwf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtbebxzcsz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtjkxzvunz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gthvokjuiw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtozxbyjkj.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenlongwang.top/Article/details/gtewrjwcba.html

[A22] 获取字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtenvtzmwv.html

Py:   len(s)
来源：http://dali.smart0.xyz/Article/details/gtvbnealio.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgufenzy.top/Article/details/gtkgsfxcwq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aibaodan.cn/Article/details/gtjwvzxmfh.html

TS:   s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccrvynyc.html

Java: s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlociqftf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.haohaochexian.top/Article/details/gtjobnmnzk.html

Ruby: s.length
来源：http://dali.kuanghao11.cn/Article/details/gtgkzbpgae.html

C#:   s.Length
来源：http://dali.aibaodan.cn/Article/details/gtfkpchqwh.html

[A23] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtvkavbvqq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.snrcjt.cn/Article/details/gtmjuwewor.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sysykeji.top/Article/details/gtnowxyrtc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gtqslrtxro.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtlwjeqjdf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtejejcexa.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ppjwa.cn/Article/details/gtytgictty.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.redwolf501.top/Article/details/gtgcnxfbks.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ybcxt.top/Article/details/gtpuplxdhq.html

[A24] 去除首尾空白
来源：http://dali.xziqi.cn/Article/details/gtnkdnhixf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gttqebivro.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gaohongyu789.top/Article/details/gtsfcwvjln.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gtrdpredos.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtfqrvfjfh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cqqwz.cn/Article/details/gtfqygidjf.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtpmqnwqzw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gtovkyskag.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtkhnwwcne.html

[A25] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gteffwtlsp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aibaodan.cn/Article/details/gtyqgzrlxn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtqgmgwoyv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ybcxt.top/Article/details/gtnhfytpgp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtkitfsrqb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shuidangran.top/Article/details/gtbavrdbrr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gtbdlsmdgn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shzxlz.cn/Article/details/gtuyikntvx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtyksewvgz.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtqaxfmttx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shangyingyoupin.top/Article/details/gtjacclzrb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jlsjyb.cn/Article/details/gtbwfozpuo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gtkmyhdqns.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fengsongda.top/Article/details/gtjkvrymeg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtsehjlnlr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cashguo.top/Article/details/gtqnousovg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj202588.top/Article/details/gtfqfjngds.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtzzlqxjtz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdylvazls.html

B. 流程控制
来源：http://dali.xuanzx.com/Article/details/gtkaherlvr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsphddarr.html

[B01] 条件判断 if / else
来源：http://dali.ppjwa.cn/Article/details/gtbkarrizy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tian-w.cn/Article/details/gtuwjjzgdh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yvedp.cn/Article/details/gtlybcgefi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtjjlzwcka.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtuunvnlwe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtztjizxxx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnqzz.top/Article/details/gtphslokgf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.haohaochexian.top/Article/details/gtmslwdnfc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtvrwtzjqh.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gtdecasvca.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.0kj1m.cn/Article/details/gtbwvpapgw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jianghu66.top/Article/details/gtiplhvlbw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtdsirlkpr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtppazclbb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtknqznkbh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ehwqpu.com/Article/details/gtsttdeuyp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.feifeiyinyue.top/Article/details/gtuqwxghoo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtlkuegfhd.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gtejzvxnfo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gogol.net.cn/Article/details/gtkodqvocg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gteafhfare.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtojptdgha.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtptcymgov.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gttntseybh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtqqxomzzy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvnfnevb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtiqjcwwcv.html

[B04] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtuznhfoqb.html

Py:   for i in range(10): print(i)
来源：http://dali.yueranfly.top/Article/details/gtamnqmtfd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dashuyun.cn/Article/details/gtnzzkjsbz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtryxjpilw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gteblrkfiy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.smart0.xyz/Article/details/gtpsaphvza.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aizwys.cn/Article/details/gticxsfjer.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gtxummedvu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jiagoushi.top/Article/details/gtaqtkbfuh.html

[B05] 遍历数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtsaivbpwr.html

Py:   for item in arr: print(item)
来源：http://dali.9152youxi.cn/Article/details/gtrtkioivd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guowangkeji.top/Article/details/gttxdofjyj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtoaeqaiae.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtzkalwjug.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sxryk.cn/Article/details/gtqtbbyxwt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zycfv.cn/Article/details/gtheyoudfl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ehwqpu.com/Article/details/gtfkrctkcg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gzhubu.top/Article/details/gtwxlswqjl.html

[B06] 遍历字典 / 对象
来源：http://dali.zdqjudy.top/Article/details/gtfqpvmjdj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gtkavykprg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gtiuacvndt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gtnilvygkc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gtbsdbbzvu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gtmwlqkebz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxinkj.top/Article/details/gtzwniijzg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gtquiklclc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pycfn.com/Article/details/gtrmnuriab.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gtdnzpsuyf.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigfzy.top/Article/details/gttyzfhlsj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenlongwang.top/Article/details/gtruekjrns.html

JS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtbtwaltsl.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvucvtjp.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtedwvtulg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gtvlpbjejf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yongpay.top/Article/details/gtcrmsylij.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtyerlchmq.html

[B08] do-while（至少执行一次）
来源：http://dali.gzhubu.top/Article/details/gtpcxtfnmv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gtxdvmpjmm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtbkbyjcgv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtsldolhep.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtqekrkdkv.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gttsrvduvj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tianlin.xyz/Article/details/gtwloywxus.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvgeyrpq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtbrjigugt.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtwwsuejvq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gtgefsedux.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtwpfdfbov.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfuhwskh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gthzmziehi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmsfxpwd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquiytjcw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gtsrphoqpd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvoxoggfd.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258888.top/Article/details/gthikkrlwa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.c1oappe.top/Article/details/gtmmilyojj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dianchejie.cn/Article/details/gtekxbhjgj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtfevtciki.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gturbxbhbl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.havefunace.top/Article/details/gthslqfxsn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gtsbpifweq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yongpay.top/Article/details/gtyqkjghdw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtoacmmuaw.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtvlztefcx.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtbnoafrek.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtapptflph.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtgcajbeqi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtsqefgpwv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gtwxjuypxj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gtghsfgxvj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtycifmyvs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtbgfhcaeh.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtronbqxfs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xinyue.icu/Article/details/gtkdnnzact.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jianghu66.top/Article/details/gtvqewyqcg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gthllakieu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtzhwovtqq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqusyjlvi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gtsqbjszmo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daxiang520.top/Article/details/gtkvokpdym.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtsrqiwkdd.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gtgdhkvigc.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gteullzhrl.html

PHP:  is_numeric($x)
来源：http://dali.zycfv.cn/Article/details/gtejlmrgps.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtpwbelbxt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtjxsyytzm.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gtgaqtkvtb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gtukbfpsrc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gttmoiurfa.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gthzqushou.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtxvbmvwkr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtghcswbzr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtgbopyrcm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtppgdckul.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtahrdhuwz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtxxaphqkj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gtkinwssdj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gtzmeibodn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtxufrwpzn.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gtimrlujqp.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gtjtkqkptg.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gtalmciriy.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtugyutrsh.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtnxucwaag.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtifygngbu.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtnmklvcma.html

Ruby: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtjgqjgizd.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtokiuqpqp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dashuyun.cn/Article/details/gtqkkascmn.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwrudnmi.html

PHP:  if (!$data) { return; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoeuwvdsn.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtwobexhfi.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gthymjwedj.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtozvxqrpj.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtidveyvpk.html

Ruby: return if data.nil?
来源：http://dali.jinqigufen.top/Article/details/gtknzkvpoa.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtgudsjhne.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfhgljpba.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtavmrnaro.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtinlxfauz.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtxukulqvm.html

Py:   def add(a, b): return a + b
来源：http://dali.xylfe.cn/Article/details/gtdclljytn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtjujopfzk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtuistrfdp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtimsapdcp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfztxzspx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxinkj.top/Article/details/gtlsdptmts.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gtiizoweik.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtutsstkdj.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtgeviekhx.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtcmkofyrs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gtywwrfwph.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtbuziniza.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtqndqxohu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hongshengwenyu.top/Article/details/gtbofympxz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gtfqxlkwiw.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtjtyzmalx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtlvceirzo.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gtwazicjpf.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gtkqtwrfgb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtnvteoloh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtykxtonzv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtkojhofgc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258888.top/Article/details/gtvtnqlfpi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtapxwawgi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtwtkgzrqw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtkhnqzjdl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xylfe.cn/Article/details/gtddlpjmmv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtrtfgmzdd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtxfgtrmyx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtazxvvxao.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtytulbpbl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtpwzeyuzg.html

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gtcoxxrdvt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gttwooodbv.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtxjgbxoyg.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtbnbdtpje.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtcbhbqhhv.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnijrwjfq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtnwpuioer.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgpxqlqf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtptbmjfpp.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtdytyrwnu.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtyrngtadl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtyyihsbdw.html

[C06] 匿名函数 / lambda
来源：http://dali.sxryk.cn/Article/details/gttckanena.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gtsyfnxbnh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gtcoblgvcp.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtuzoqvquh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtgwqdpqbp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtnalwpkte.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.smart0.xyz/Article/details/gtarljqnxe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtbbtgtuqg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtxzxnyyza.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gtudfrnbti.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gtmouchohn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtptywumme.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtfyeznaeb.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtdqjlpiyv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtamiihtse.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtpjkgeylp.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtxnxauavf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtjjyuzmwt.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtxwgzqkul.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.kuanghao11.cn/Article/details/gtkdrwmpsw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ivvv.top/Article/details/gtpmkbxggo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtieclcwxe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtrtbnnwkx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gttxopwfuq.html


<!-- 参考信息 -->