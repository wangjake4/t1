代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.aibaodan.cn/Article/details/gtuthjscwg.html

Py:   ord("A"); chr(65)
来源：http://dali.nwbrower.top/Article/details/gtnhrubdqa.html

PHP:  ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gtrfhcmmzt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yanxiufei.cn/Article/details/gtbwwyexvw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gaohongyu789.top/Article/details/gtbwoaufgc.html

Java: (int) 'A'; (char) 65
来源：http://dali.vqdsnc.cn/Article/details/gtnyxjhccc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxinkj.top/Article/details/gtdtyjfzqu.html

Ruby: "A".ord; 65.chr
来源：http://dali.sysykeji.top/Article/details/gtedtkwpjo.html

C#:   (int)'A'; (char)65
来源：http://dali.pengpengdd.cyou/Article/details/gtyogitqzm.html

[A19] 交换两个变量
来源：http://dali.daria6918.cn/Article/details/gtgvnyaboo.html

Py:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtjibwrbbx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.snrcjt.cn/Article/details/gtjbitlusr.html

JS:   [a, b] = [b, a];
来源：http://dali.9152youxi.cn/Article/details/gtgqgdxxsa.html

TS:   [a, b] = [b, a];
来源：http://dali.jianghu66.top/Article/details/gtoletkmfl.html

Java: int t = a; a = b; b = t;
来源：http://dali.tianlin.xyz/Article/details/gtwnyzwhdx.html

Go:   a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtsrrfkhio.html

Ruby: a, b = b, a
来源：http://dali.yj20258.top/Article/details/gtrunmhqdk.html

C#:   (a, b) = (b, a);
来源：http://dali.ppjwa.cn/Article/details/gtsmbswpal.html

[A20] 读取标准输入
来源：http://dali.yongpay.top/Article/details/gtibxodsal.html

Py:   name = input("请输入：")
来源：http://dali.cqqwz.cn/Article/details/gtejqjtspf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hysaishi.cn/Article/details/gtdbitfdqp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ivvv.top/Article/details/gthtfdjtjx.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gtwqwvfztj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hywenlv.cn/Article/details/gtihwcswsd.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ehwqpu.com/Article/details/gtufzhwsay.html

Ruby: gets.chomp
来源：http://dali.kuanghao11.cn/Article/details/gtwcmwwryj.html

C#:   Console.ReadLine();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobunqnsc.html

[A21] 保留指定小数位输出
来源：http://dali.shangyingyoupin.top/Article/details/gtgoitxmia.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guowangkeji.top/Article/details/gttyyylvrr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtbqxbwlni.html

JS:   (3.14159).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtajblkvnn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtsbrxgqzz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtgphbhzvc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtvawixrnl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtbnmobsdl.html

C#:   3.14159.ToString("F2")
来源：http://dali.cashguo.top/Article/details/gttkoaybnz.html

[A22] 获取字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtjylqvszm.html

Py:   len(s)
来源：http://dali.nanxuanxn.top/Article/details/gtefbeqzis.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hywenlv.cn/Article/details/gtjzwiqont.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258.top/Article/details/gtcxtzposg.html

TS:   s.length
来源：http://dali.hnqzz.top/Article/details/gtatnezcoa.html

Java: s.length()
来源：http://dali.nanxinkj.top/Article/details/gtgogqnuoy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cheryme.top/Article/details/gtdvxngtkd.html

Ruby: s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdquolqdq.html

C#:   s.Length
来源：http://dali.yongpay.top/Article/details/gtngssjoir.html

[A23] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtbgmqhkuv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtevlvjtto.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvdmnlptx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gttancckmi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtwxelphtv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fengsongda.top/Article/details/gtuwdagehr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.redwolf501.top/Article/details/gtuqrwutbz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtqzsjrxoe.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hongshengwenyu.top/Article/details/gtsarcvltl.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciwhhplp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sxryk.cn/Article/details/gtdmloumja.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guannengcc.top/Article/details/gtsjvjxwyj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtlhoygtqs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucylqidy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xziqi.cn/Article/details/gtlluiesxe.html

Go:   strings.TrimSpace(s)
来源：http://dali.redwolf501.top/Article/details/gtzxvmgkux.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuanzhike.top/Article/details/gtyuxexvoq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtzkjfnrje.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtrnwfeyoz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gaohongyu789.top/Article/details/gtjtzglaxx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgfzy.top/Article/details/gtwnwnhqsa.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtsfkjtioj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtsvruiedh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnutwtpgw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gtihetcnaw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yangfankeji.com/Article/details/gtsqnvpxmv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tian-w.cn/Article/details/gtvvufabmw.html

[A26] 类型转换总览
来源：http://dali.jinqigufen.top/Article/details/gtqdijelmq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gtouxwcfhn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xylfe.cn/Article/details/gtjzmbzaij.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.snrcjt.cn/Article/details/gtemrijbzs.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yanxiufei.cn/Article/details/gtpcjtbafm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gtdaerczzc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigfzy.top/Article/details/gtasopyuhb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jqgufenzy.top/Article/details/gtdggjrigq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gtbudmjdwv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttynlzaot.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gtzlnpsehv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgyzaavox.html

[B01] 条件判断 if / else
来源：http://dali.hnqzz.top/Article/details/gtuvtuqlmu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.316326.xyz/Article/details/gtioyqwnqt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daria6918.cn/Article/details/gtmqyyzsci.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtuqzonwbm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtrggapzyk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtdjimuzpz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtwxetfkgo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtpsoeipjj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtlpmfafnn.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gtqypppdtz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dashuyun.cn/Article/details/gtolqinybz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gtfmbafjqa.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtsmhvvefz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtffjqbugw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtegrhhhex.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xylfe.cn/Article/details/gtlskqqaoj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.vqdsnc.cn/Article/details/gtgjldyloa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gthrcctvfq.html

[B03] switch / match / case
来源：http://dali.hnxiangtu.top/Article/details/gtvubgulnx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gtaltggzfh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtpsxkqvvi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtmldsrfvw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtgqneqfce.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtvhttsitf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtayozfdyy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gtcksrbcxe.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtvpolzjmu.html

[B04] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtjrfmlqkw.html

Py:   for i in range(10): print(i)
来源：http://dali.guowangkeji.top/Article/details/gtqctwjtod.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cheryme.top/Article/details/gtalytzvdr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gtmjljksbf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcqffbeie.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsnqkymxi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gtuszphmat.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gteqgptmmg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtrcxaggte.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtxsvypsmq.html

Py:   for item in arr: print(item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqknfcpmh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlwlylzjs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtuwofyees.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gtfiiyqwba.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gtdujobwkt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sweek.top/Article/details/gtvoskfwgx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgufenzy.top/Article/details/gtpiycdceg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tian-w.cn/Article/details/gtsupmejei.html

[B06] 遍历字典 / 对象
来源：http://dali.cucudq.cn/Article/details/gtochljbms.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.316326.xyz/Article/details/gtzodcxoil.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjpcaqewi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtiijolgut.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtwrwpykyv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gogol.net.cn/Article/details/gtpesyzrzr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gtrqawcvrz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtpwepcaae.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvcuvbre.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gtfxebhrqt.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gtbmjpkoho.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gttgyzckgk.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrxyglruq.html

TS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtrdbytmya.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtbwhqludj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangshuangyany.cn/Article/details/gtxcszrjcl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gtvbzmlyeb.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdodhvsq.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gtwvpaisqm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nanxuanxn.top/Article/details/gtoyifgvot.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtgjqcvlom.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtznxhdpdf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtrdvrowyz.html

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtyykxgskp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gtxjoqmoei.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenzaomai.com/Article/details/gtvagwbbxg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtxbuemamj.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gtkmwbjxzk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtrwkujzba.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbbmsfgqo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtkfhneavm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtomhuxswm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtrkcljinf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtfmmsehhl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtmevgxxex.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtbcbjulpa.html

[B10] 遍历同时拿索引
来源：http://dali.9152youxi.cn/Article/details/gtfdjefnum.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtdbahdmdo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxuanxn.top/Article/details/gtymxaerxk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtvktylluc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtlkfzurmf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtklhaogiv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daria6918.cn/Article/details/gtjrrllrjg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.haohaochexian.top/Article/details/gtscurkqom.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gtuulyevfx.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtgdnhgodc.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuetiantiany.cn/Article/details/gtovuezyzw.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtehhhfcfa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtmacchbyo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtugygvbuk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gtheeocqzt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtwjlobcvb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtqibwdkzh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gtoalprbjy.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtmmtragtj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtkpqbcfva.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.andypj.xyz/Article/details/gtkjansmrw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtiewjsbkt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtmwlcepwr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtotlqjhad.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gtwynirdzv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gtuqazwrfa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtezbhrfhd.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gtlxikgfmd.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gtescaqwyl.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtwmmhmozo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdajhvqg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gterhrsmdv.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gtzmwjncin.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gtemgawisr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.smart0.xyz/Article/details/gtflobbvcm.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtfptfdklo.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtreieboqb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gtnnnwquhe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xylfe.cn/Article/details/gtyhsguvrr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtudjnfrff.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtdopjaiaj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.bjfxy.top/Article/details/gtlvtmjldb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhzqzyym.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtqnplzvkk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtlfknisxl.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtrkaymnvj.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gtzgkqilxy.html

PHP:  $a && $b || !$c
来源：http://dali.daria6918.cn/Article/details/gttfrbrbhk.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtukrupejl.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtyyvkbnoa.html

Java: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gthsgkuies.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtjisdxygi.html

Ruby: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtjyhjysxa.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtkksurjbb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gtmulpqdtt.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gtzfwnvtey.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gtahnguvgl.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtwykaaokx.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gttotqoxbj.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtrucbwfud.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtoycubldm.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gtvfygrfav.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtffbbxfvd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtplozptnc.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtahffnwpw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmrhpwrrh.html

[C01] 定义函数
来源：http://dali.cashguo.top/Article/details/gtxkucwvpo.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtbzwrorla.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gthdlxaazt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtbkbabinv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtorybsgtp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtvtwtwjns.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtjbbdjvvq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtoqkaxoib.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtgnccskbb.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtnepfoxag.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtzelcixhe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gtijutihzw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtckhncxid.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtfvxokwsz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtlwipbstp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gtsdmosmif.html

Ruby: def greet(name = "World") = name
来源：http://dali.yonumen.top/Article/details/gtlskzbjev.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtbwhdpzze.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gtzpbtpdqv.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gtvfjlaokl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gtatfsqrtt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttipiprek.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtmxbzuzju.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtgoaqvbau.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtztsssvxl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtdmwezrpp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gtvqhfryae.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtsdnwpnnq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gtnaimcnjb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gtcbuyirvn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtptsqjdol.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gtjknpehki.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gtpzttfnuc.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtalvxzgzo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gthhocxmts.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtoarvhasp.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtpnprwyfs.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtdehsjkar.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gtrtdatmye.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtrnfekibl.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtwmyrkiye.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gtvpixidpb.html

Go:   return a, b
来源：http://dali.yj20258.top/Article/details/gtcoqlwcsa.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtqqfkzupr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtoimvdvqj.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gtqkbpulhb.html

Py:   square = lambda x: x * x
来源：http://dali.hfpthk.cn/Article/details/gtyeccwhgu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtiyaxlurp.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtnwvnllmz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtjpxsxkch.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jiagoushi.top/Article/details/gtfjoqmjsq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gtljrtryfi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zycfv.cn/Article/details/gtetuaerow.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtwomrggcw.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gthitxawbt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtljebjxmy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtgdxxagyv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gtjrpwqbac.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoioiycp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.316326.xyz/Article/details/gtigrstvkb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhongyouzk.top/Article/details/gtnqkocbne.html

Ruby: arr.map(&:upcase)
来源：http://dali.c1oappe.top/Article/details/gtfpezqnxm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtfdqlryxj.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtflqvxfxy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtgmivgdpi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gtkgndxwwl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtqkclfypj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gteyxydbfa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtnnnypuje.html


<!-- 参考信息 -->