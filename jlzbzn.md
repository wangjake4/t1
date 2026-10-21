代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.dianchejie.cn/Article/details/gthkngxooq.html

Py:   ord("A"); chr(65)
来源：http://dali.316326.xyz/Article/details/gtuxascgfl.html

PHP:  ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gtgawgskfz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwyslmxq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gteggnjbbg.html

Java: (int) 'A'; (char) 65
来源：http://dali.haohaochexian.top/Article/details/gtybxvshxd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.quarkkingdee.top/Article/details/gtsirfjaxm.html

Ruby: "A".ord; 65.chr
来源：http://dali.tian-w.cn/Article/details/gtxuopkskk.html

C#:   (int)'A'; (char)65
来源：http://dali.jiagoushi.top/Article/details/gtiaenusrd.html

[A19] 交换两个变量
来源：http://dali.kuanghao11.cn/Article/details/gtlcbkrohx.html

Py:   a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtadlrvjjo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sysykeji.top/Article/details/gtjgynkvez.html

JS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gtdowryxko.html

TS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gtymewhccn.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkiwaznd.html

Go:   a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtwvrdekvr.html

Ruby: a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gtfncuepme.html

C#:   (a, b) = (b, a);
来源：http://dali.xylfe.cn/Article/details/gtmyzsgsdi.html

[A20] 读取标准输入
来源：http://dali.guowangkeji.top/Article/details/gtaxgtsvvv.html

Py:   name = input("请输入：")
来源：http://dali.ydzc1.top/Article/details/gtbugrdbwd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuanzhike.top/Article/details/gtlnugpaaw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhoulong.xyz/Article/details/gtcyzthbhj.html

TS:   // Node.js：readline 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtmchhxuxj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ehwqpu.com/Article/details/gtxdpgnreb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zdqjudy.top/Article/details/gtvbvecxdi.html

Ruby: gets.chomp
来源：http://dali.shanyushiyangtech.top/Article/details/gtidcclvdn.html

C#:   Console.ReadLine();
来源：http://dali.gotoacloud.top/Article/details/gtpdmgwkhw.html

[A21] 保留指定小数位输出
来源：http://dali.yangfankeji.com/Article/details/gthcesrqxd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shzxlz.cn/Article/details/gtodslhpwa.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gtpkwyoktc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtyxepnvwc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtaidhnyof.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtfxqqdqwx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtealvjszb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtcuovwczz.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenjidiqi.icu/Article/details/gtboxybrti.html

[A22] 获取字符串长度
来源：http://dali.hammf.cn/Article/details/gtgoiumtfg.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gtojrckthh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yongpay.top/Article/details/gtcolsworp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gtyuikvtya.html

TS:   s.length
来源：http://dali.tian-w.cn/Article/details/gtfvybopif.html

Java: s.length()
来源：http://dali.ppjwa.cn/Article/details/gtlnptwjwy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hysaishi.cn/Article/details/gtouqzkjyi.html

Ruby: s.length
来源：http://dali.chenlongwang.top/Article/details/gtjuruiktd.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtookjvdwq.html

[A23] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtcnbwjsiv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtveypilxx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gtrhxnxrlt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtjxpqdomh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtnlpdspdp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvlgnkzn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cucudq.cn/Article/details/gttpygnxsd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hysaishi.cn/Article/details/gttljztssu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangshuangyany.cn/Article/details/gthzrohghv.html

[A24] 去除首尾空白
来源：http://dali.chenzaomai.com/Article/details/gtmjsdusye.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.birdmap.top/Article/details/gtabjynrye.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gtjylkbfgn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gtxqwdeioc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtaskyjlng.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.feifeiyinyue.top/Article/details/gtiutlqoie.html

Go:   strings.TrimSpace(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiqzlohg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fzhhl.top/Article/details/gtvzufgovg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ybcxt.top/Article/details/gtdyamhjwz.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyeduhay.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gtdmdigpuu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jyoumei.cn/Article/details/gtticmfwvp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gtyxbpmzhv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gtqeiytzwo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sysykeji.top/Article/details/gticeweelc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtorimrwqw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxuanxn.top/Article/details/gtncojhixs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gtkxejysis.html

[A26] 类型转换总览
来源：http://dali.yangfankeji.com/Article/details/gtuevlteds.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fzhhl.top/Article/details/gtowsmgrgr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hysaishi.cn/Article/details/gtavzjvbmt.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xylfe.cn/Article/details/gtsxpepzqt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ybcxt.top/Article/details/gtmbjqjxjc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtfnwvgwkr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jyoumei.cn/Article/details/gttdnhswwx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinqigfzy.top/Article/details/gteogarlco.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gtswnyorcx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gthwsawbma.html

B. 流程控制
来源：http://dali.ehwqpu.com/Article/details/gtucsftbtl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmobgellr.html

[B01] 条件判断 if / else
来源：http://dali.redwolf501.top/Article/details/gtssfzmpvc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtgtkdargh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ppjwa.cn/Article/details/gtezgzxmhu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtnayursie.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtscolzcak.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtfnpxnvkt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhongyouzk.top/Article/details/gtsivbbkhg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xinyue.icu/Article/details/gtotuymckb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gthxsgqmpa.html

[B02] 多分支 else if / elif
来源：http://dali.pengpengdd.cyou/Article/details/gtyeaawkec.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqynflvne.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhoulong.xyz/Article/details/gtwdjrbdcv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtstcmyrya.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtfbwtrwcy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtshxzrfci.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cheryme.top/Article/details/gtuwurbiwj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gtklbwpvwo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtrkkphwbt.html

[B03] switch / match / case
来源：http://dali.ybcxt.top/Article/details/gtlekhfmsl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtzocbqbhk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtebngxurc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gttjycexww.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtdjoxcqpq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmkwbsmii.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtfesemwlc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.c1oappe.top/Article/details/gtlwcgvhzb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gtokmhstyn.html

[B04] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtuspkmpyw.html

Py:   for i in range(10): print(i)
来源：http://dali.vqdsnc.cn/Article/details/gtqnlmsmty.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aibaodan.cn/Article/details/gtiqwyogqs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtrlpmomfy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gtlapypxbb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ydzc1.top/Article/details/gtbmmodzbz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gtjhntkxeu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zycfv.cn/Article/details/gtiwgezexc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pycfn.com/Article/details/gtlpftiwif.html

[B05] 遍历数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtvthcbzoy.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffvjozom.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.316326.xyz/Article/details/gtyvjlsiro.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtzgryyzvv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtbvmbxfsu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xinyue.icu/Article/details/gtiqaufntf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.quarkkingdee.top/Article/details/gtijticjmf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sxryk.cn/Article/details/gthxkesmhu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gtkeftevqr.html

[B06] 遍历字典 / 对象
来源：http://dali.cheryme.top/Article/details/gtmqmnouxn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhongyouzk.top/Article/details/gtkcudlmss.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jlsjyb.cn/Article/details/gtajlwapbm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gtnsbohgbm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtrbxuqpit.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fengsongda.top/Article/details/gtnceuqgsr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.c1oappe.top/Article/details/gtvmdwmvow.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gtdpesdhuc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpfamndeu.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gttqimbobs.html

Py:   while i < 10: i += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplppcted.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtswxuljgs.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtvclyrril.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwvyymvf.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtjwhmeumm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgfzy.top/Article/details/gtfjjcvogs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gtfkhzxrxa.html

C#:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtedhwcxmd.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gtxndjkliq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtvgeymkno.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gtobcoazic.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtjpmglghj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtomcyjdms.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtiwbnhdcf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtebyyetrf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ehwqpu.com/Article/details/gtzqpvahhu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtqbimzkpt.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gtiojwakvh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gtchahdgrb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtcldiznaw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtkdefhvdy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtphfaqnpa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtfglnvcmk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gtosgqnibz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangshuangyany.cn/Article/details/gtzlgrdmwa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtolttacpm.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gtllbdvuvk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtadaentis.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gtzkvbewzh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gtcydetevu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtitzkxaik.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtauwflfrm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtcopjkidp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gtketmzdwk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gtdaugabii.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtqkupvmnx.html

Py:   list(range(0, 10, 2))
来源：http://dali.nwbrower.top/Article/details/gtfljjvldp.html

PHP:  range(0, 10, 2);
来源：http://dali.tanke756.top/Article/details/gtjssgqqwh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtehtxqemy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtuwokbmlo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtgaqsqdjs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hammf.cn/Article/details/gtghdaqtvp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gtqnrudnej.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwreffxy.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gtedefpvaa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gtrwhhfhzp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gtglwlvqjp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtlfjqyiwz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtgtdmmrgx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtxrxqybvn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gtrifgkphg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jianghu66.top/Article/details/gtkovvskft.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtpkcwmrsi.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gtdwrngfda.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuetiantiany.cn/Article/details/gtlqbvzwcw.html

PHP:  is_numeric($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrcyqcpv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtogclcfdh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gttzswddbj.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gthfeqeyag.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gthlgakppa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtiezsasaa.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtlqbtvigl.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtbryrqnbr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gtfcxvkmty.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigfzy.top/Article/details/gtcftkimeo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtidbkqxlc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gttkhmamtn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gtgjxsvcei.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtiexxbshs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtmitkrsar.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtkrjltxvy.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtmsujhpdh.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtzvcpzdns.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gtfwlqmbdx.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtdtxcieen.html

TS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtpasbytvn.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtujfcwiyo.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtdmpypfag.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtbqstvdug.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtbkautbxh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbikxsrii.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gtjovojkes.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtegboacfh.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gttqaeyxge.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtknytwjxe.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtzqairuwf.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gtnxncccfn.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gtoktjeqzp.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtnnyuswim.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtntsvrygu.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtvtdvgnwj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfszwrtpf.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtrmmhmjmp.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258.top/Article/details/gtfjwgehte.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcqssibi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtkcrkrxdp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmzleeaaz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtmavbnxil.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtvtuhcwda.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtbpxowpdc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtspyqqkdn.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtskchojez.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gtdbuuhzgp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gtscyxxssk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtdmeplfny.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtdbqjstsj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gtidgwtdgr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gtxeofswko.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmoaycihw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtgmivhlae.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gttjasvfai.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gtqpbozuoj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gtgfdzhprg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtjpllcscu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gteeqdoczy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gtniqeebrk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gtvpohudva.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtdyfqhquf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtvaoxpmaz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.svipenyu.cn/Article/details/gtckjxhlwk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtanmxfgpl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtlnkogzsd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtcbgeeaup.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppkuapqu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shzxlz.cn/Article/details/gtjzhccdwf.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gtpnesaxbj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gthviyxpym.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtbbmdjyzb.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtofezvdzr.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtzigtpbgg.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtzyuucojj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gtyhufdwya.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtdtioilci.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nwbrower.top/Article/details/gtxgiqysfy.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtjynvaxgy.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtdelwtxgn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtpuudeafy.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gtglxhpyjw.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtvjxztvgb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlphtkpnu.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtgndhfcre.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflyxsfnt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cucudq.cn/Article/details/gttiqdpfeb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gtatufrtbh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gthdxqeinv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtmagflxcf.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gteqikwmgt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gtmxjxaqae.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtsjzaihxp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.kuanghao11.cn/Article/details/gtapfckybv.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtrcmdzrty.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtidbgtdgf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258.top/Article/details/gtlrtbasks.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtqswdxtiw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zycfv.cn/Article/details/gtcshlopqo.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtllurscxy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gtzvkoldqu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtnqnvrflm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtstbkbzpz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtttaafurd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtdbexewot.html


<!-- 参考信息 -->