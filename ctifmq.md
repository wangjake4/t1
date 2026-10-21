代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gtlkqktzmg.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenzaomai.com/Article/details/gtgiaspqdn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daria6918.cn/Article/details/gtbafxchcx.html

Ruby: "A".ord; 65.chr
来源：http://dali.quarkkingdee.top/Article/details/gtuxiiojda.html

C#:   (int)'A'; (char)65
来源：http://dali.daxiang520.top/Article/details/gtwwslxnmc.html

[A19] 交换两个变量
来源：http://dali.ybcxt.top/Article/details/gtefyrmhmb.html

Py:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtsbajkwvg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangshuangyany.cn/Article/details/gtvidpcbdg.html

JS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gtzgkdovhg.html

TS:   [a, b] = [b, a];
来源：http://dali.yvedp.cn/Article/details/gteoqvweii.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhoulong.xyz/Article/details/gtpgiujrwg.html

Go:   a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtqykilnog.html

Ruby: a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gtutvmlmyc.html

C#:   (a, b) = (b, a);
来源：http://dali.daxiang520.top/Article/details/gtzsgndwgc.html

[A20] 读取标准输入
来源：http://dali.cashguo.top/Article/details/gtezdoxyoa.html

Py:   name = input("请输入：")
来源：http://dali.zhoulong.xyz/Article/details/gtbjijscne.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ivvv.top/Article/details/gtaizazyvz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhixingplan.top/Article/details/gtmjpplezt.html

TS:   // Node.js：readline 模块
来源：http://dali.iojbl.cn/Article/details/gtksfkvwqj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpqjszqe.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yuanzhike.top/Article/details/gtmadnngxk.html

Ruby: gets.chomp
来源：http://dali.bjfxy.top/Article/details/gtvjtrdqqp.html

C#:   Console.ReadLine();
来源：http://dali.shzxlz.cn/Article/details/gtgfqrptmq.html

[A21] 保留指定小数位输出
来源：http://dali.cashguo.top/Article/details/gtxcofqegv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gtdmttyxpk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtrsbgwegz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtguvrysvx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtnftcoori.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbowgggdo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtlxzuldcv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gtokrjihym.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuanzhike.top/Article/details/gtkalqivqi.html

[A22] 获取字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtbkwixnkr.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfgoqwdfn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gaohongyu789.top/Article/details/gtptvjjcnd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gthluztfvg.html

TS:   s.length
来源：http://dali.zhongyouzk.top/Article/details/gtzwaigtse.html

Java: s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtjzrofhri.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gttcracjmj.html

Ruby: s.length
来源：http://dali.svipenyu.cn/Article/details/gtxexlyiuq.html

C#:   s.Length
来源：http://dali.ybcxt.top/Article/details/gtmuwecpko.html

[A23] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtayrgwhed.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hnxiangtu.top/Article/details/gtiqedrqds.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cheryme.top/Article/details/gtpvbzpgzp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hammf.cn/Article/details/gtwegqnzqq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtymkrfoiz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtcgecxiab.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gtjgglijla.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gtmkzbaqlh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.iojbl.cn/Article/details/gtqpzcydya.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gtfwzjsnse.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.meibo888.top/Article/details/gtgnnmbpgh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ivvv.top/Article/details/gtkcdmmxlq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gtsqsouroy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sufxvd.cn/Article/details/gtvlocogut.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.snrcjt.cn/Article/details/gtddtiituw.html

Go:   strings.TrimSpace(s)
来源：http://dali.hfpthk.cn/Article/details/gtskjzyzcy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zdqjudy.top/Article/details/gtsvtnxpmx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtdohhrnzt.html

[A25] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtfnoxtrje.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gtqdfntcim.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gtcsuuwkia.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gtlqznvilp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gtwptqtyjo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtubhnmows.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gotoacloud.top/Article/details/gthttikvwk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtmpiprgqw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtjtgqgrlm.html

[A26] 类型转换总览
来源：http://dali.tanke756.top/Article/details/gtnahlgqlr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sufxvd.cn/Article/details/gtjcsibpaj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xinyue.icu/Article/details/gtqgadnraj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtintxhkkj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gtcawoqkrh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtzxfosxme.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuxming.cn/Article/details/gtekcvbvpe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dianchejie.cn/Article/details/gttgmwtloc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtgfdmboci.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpzrygxeu.html

B. 流程控制
来源：http://dali.chenjidiqi.icu/Article/details/gtfpwdyktj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttvrwjsqy.html

[B01] 条件判断 if / else
来源：http://dali.hnqzz.top/Article/details/gtturoyhtx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtklljtvvf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj202588.top/Article/details/gtnywcjjqs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtnkiaioyu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtuadbnpjw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtpnjerfgz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.daxiang520.top/Article/details/gtkvmhvogx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gtnpodfyjv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtvxzjqmkh.html

[B02] 多分支 else if / elif
来源：http://dali.smart0.xyz/Article/details/gtpenshyah.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shuidangran.top/Article/details/gtosylwifr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigufen.top/Article/details/gtgrvxphem.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtvuhfnviu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtlokywvuo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtitlkztni.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenzaomai.com/Article/details/gtxwiougat.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nwbrower.top/Article/details/gtebsdvayf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtqdlwdkbx.html

[B03] switch / match / case
来源：http://dali.hysaishi.cn/Article/details/gtygujjdig.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sufxvd.cn/Article/details/gtrorjbccz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtprfzrfpx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtkbszwygm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtgokxpllh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtkjtxmymc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gtecehtkqk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yvedp.cn/Article/details/gtymvzfcri.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gthjaksiqr.html

[B04] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtcllmomof.html

Py:   for i in range(10): print(i)
来源：http://dali.xylfe.cn/Article/details/gtxwrrztew.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tanke756.top/Article/details/gtzlvtdsao.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtvdkgqlaq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gthivrzbfi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.iojbl.cn/Article/details/gtxuxwpdlc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gtearalgiu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gtzsdzbwdw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sweek.top/Article/details/gtyrkytygi.html

[B05] 遍历数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtjffuwbsq.html

Py:   for item in arr: print(item)
来源：http://dali.sweek.top/Article/details/gtaystfqhe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgufenzy.top/Article/details/gtqnfpeijr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gtfamhhpvf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtrgphtqwe.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfrltrej.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gtrwytmuce.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gogol.net.cn/Article/details/gtccxbwegx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dianchejie.cn/Article/details/gtdiaxtojz.html

[B06] 遍历字典 / 对象
来源：http://dali.cdnleiting.top/Article/details/gtyrqyjfsc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwedrsxug.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gtwfcsaghc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gtxwfclimo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnmwvsgd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yangfankeji.com/Article/details/gtnsydjevl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gticetkosz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yongpay.top/Article/details/gtawgpjfvk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gtvbzcalak.html

[B07] while 循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtccgwjcaq.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gtwdyunqjj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxuanxn.top/Article/details/gteuhtslec.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtjoxsngan.html

TS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtmjhxnwfv.html

Java: while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtkfraisko.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzawvftwi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gtdarupitz.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtujyedjzl.html

[B08] do-while（至少执行一次）
来源：http://dali.yonumen.top/Article/details/gtpuqhicyq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cashguo.top/Article/details/gtpcljcwoy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yonumen.top/Article/details/gtbzowhjfq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtxckqhitz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtwabugqol.html

Java: do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtyjgzjzfz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtqawaeqqn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtojzzmjbv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtnbxaqwtr.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtlmacczmr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxinkj.top/Article/details/gtakmhkogt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtvhuwsyyq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtvtlgzlbt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtjdolhcdc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqfkcjhr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtatkbahdt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gtxwyfrqzd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtqnwaqokz.html

[B10] 遍历同时拿索引
来源：http://dali.xuetiantiany.cn/Article/details/gtivebmobb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sysykeji.top/Article/details/gtreoswwut.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gtrhqfgokf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtvzutchmb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtvdxbzuiq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cqqwz.cn/Article/details/gtyhcibdjm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gtqzllbhtg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuanzhike.top/Article/details/gtxwgfhmfw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj202588.top/Article/details/gtgbzrdjad.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gtzzhosazz.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gtriwlwogw.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtakucftrk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gtbyurilcj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtbfwolkso.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pycfn.com/Article/details/gttiarzxqr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yvedp.cn/Article/details/gtkthkqinc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjidainx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fengsongda.top/Article/details/gtfnkwfgej.html

[B12] 跳出多层循环
来源：http://dali.snrcjt.cn/Article/details/gtscvjmfjh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtbmqiadkj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj202588.top/Article/details/gtvwmxxbnm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtwwujbuhr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtigwnlxtq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtrloyofoy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gtzhifvbfh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cqqwz.cn/Article/details/gtsbutnqri.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtorzquuiy.html

[B13] 判断是否为数字
来源：http://dali.chenlongwang.top/Article/details/gtweydjlcn.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gthobwavfm.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhwxdtca.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtvowikosc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gtlhylcqbw.html

Java: x instanceof Number
来源：http://dali.yangfankeji.com/Article/details/gtctixunmu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gaohongyu789.top/Article/details/gtfcmcprau.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuklfxkj.html

C#:   x is int or double or decimal
来源：http://dali.shzxlz.cn/Article/details/gttwqgdnwz.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gtatnibpnf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gteubxjzll.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gtlggjcdxl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtrqyvmykm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtddhqwfis.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtxufwtmto.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gtqrpiztsi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtafkdznom.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtaauihmst.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gtinawwwnl.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtrvwabuvi.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtfgdvdmuo.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtaeuzwjbx.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtgogrqzgm.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtwzvfubmz.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtyrwwstep.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtwmsagbgt.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtxgtazwce.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtjrwcjouu.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gteruydgfl.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gtbajigovu.html

JS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtsjbibsyg.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gttogykngh.html

Java: if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfetxkwfd.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhdjjcxl.html

Ruby: return if data.nil?
来源：http://dali.hongshengwenyu.top/Article/details/gtbotckvah.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gttxcumxyx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvnxkfemx.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gtwjapdbhj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttciacexv.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gthkkxkxid.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gthsggueia.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtcfjhbexl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtlajgmcwd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gthwdqmwyo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gttacfdokn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gttydhulzp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtriohtfhv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtxbemuyjp.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gtkxpwhvbf.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gttrbaloow.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gtbynyhffj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtqglqfrnc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtdkaiyhxw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gttbymibiw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gtbnjtkgaj.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gtqlgllmah.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hammf.cn/Article/details/gtedszczgs.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtzhspgjpv.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtfygstagk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gtjvxacfdr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtezracqmb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtbndzzypp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtaznpvkdo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gttzohqqae.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtayvsgljc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.316326.xyz/Article/details/gtgkutwcug.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtibduoevh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gthsaxuhjz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gteyslrfmq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtffmjhzmt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtjzdmffbw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtmndpxtzs.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gtlwxejjon.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtnezfvept.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtrwgvtrjc.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtvyblmhjo.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtdsosjhde.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gtxsaxyiqu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtgvopizdh.html

TS:   return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtgalbksjq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gttyepkvmo.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtsylzoauf.html

Ruby: return a, b
来源：http://dali.hywenlv.cn/Article/details/gtjhexzxxz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.bjfxy.top/Article/details/gtgzewrdef.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtplkxemma.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gtajffjajh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shuidangran.top/Article/details/gtxasegkze.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtwzjakmuw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtkbdasyhb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtnzmmyvre.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gtmoswgeue.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gtnjvjytni.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtcolynxek.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrlusupk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xuanzx.com/Article/details/gtdensgpsn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtasmeizpp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gtgnmpuxry.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gtsqasjvpn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gtbgduvjcd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xziqi.cn/Article/details/gttbushfdp.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtjhjmhxhf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daxiang520.top/Article/details/gttsnkkyda.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtibbshbfc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gtvdhundgw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gtfwowcawq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtyqzwagsc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtmrbtfazh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtlrewxzov.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gtaqjxjadm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gtsataefdl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtwlolhydt.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gtkjrhfmjz.html


<!-- 参考信息 -->