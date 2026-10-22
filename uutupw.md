代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.vqdsnc.cn/Article/details/gtkgrptiki.html

Py:   ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gtejsqmtal.html

PHP:  ord("A"); chr(65)
来源：http://dali.daxiang520.top/Article/details/gtdzmpijyv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gtgncgqvqt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cashguo.top/Article/details/gttxwqaosc.html

Java: (int) 'A'; (char) 65
来源：http://dali.daria6918.cn/Article/details/gtxgsanenk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxaxjqmm.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj20258.top/Article/details/gtblhpcmwd.html

C#:   (int)'A'; (char)65
来源：http://dali.sysykeji.top/Article/details/gtdgdxmoyh.html

[A19] 交换两个变量
来源：http://dali.xuanzx.com/Article/details/gtbcmcoilp.html

Py:   a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gtalapgnis.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yuanzhike.top/Article/details/gtzupnlbgi.html

JS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtagotqqeq.html

TS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtfoeapqxl.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gteayknwrz.html

Go:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtjtfncqrz.html

Ruby: a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gtzshcpwxq.html

C#:   (a, b) = (b, a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzubesbda.html

[A20] 读取标准输入
来源：http://dali.hnqzz.top/Article/details/gtklhsdvop.html

Py:   name = input("请输入：")
来源：http://dali.hnqzz.top/Article/details/gtybjygabg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhengqikj.top/Article/details/gtpftrnshy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.feifeiyinyue.top/Article/details/gtvaabyvql.html

TS:   // Node.js：readline 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbyaaqsy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.quarkkingdee.top/Article/details/gtisulzzuo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhiwuduotai.top/Article/details/gtxyfbprqq.html

Ruby: gets.chomp
来源：http://dali.chenlongwang.top/Article/details/gtsupceurl.html

C#:   Console.ReadLine();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyrryohz.html

[A21] 保留指定小数位输出
来源：http://dali.sxryk.cn/Article/details/gtqtvxfhsf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gtdbdyyxhs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtsszukcpi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtglulxodb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtlfbbgsyx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtsasnnpsk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjzyxlnd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtolptttdq.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuxming.cn/Article/details/gtuxlyynqo.html

[A22] 获取字符串长度
来源：http://dali.yj20258.top/Article/details/gtwvldywki.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gtazpczcaa.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinqigfzy.top/Article/details/gtmjcgpylp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gthsovyhem.html

TS:   s.length
来源：http://dali.jyoumei.cn/Article/details/gtljqoxqvd.html

Java: s.length()
来源：http://dali.fzhhl.top/Article/details/gtcsjzqumw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ybcxt.top/Article/details/gtvqgbzqwn.html

Ruby: s.length
来源：http://dali.yj202588.top/Article/details/gtdhnxvkzk.html

C#:   s.Length
来源：http://dali.smart0.xyz/Article/details/gtlbzsqvol.html

[A23] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtbkrbhqva.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvymovxos.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfgkdpws.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtvxzjpayc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gtlsztjtrc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gtgqwqktfz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cashguo.top/Article/details/gtuajygaqb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.wangshuangyany.cn/Article/details/gtjvroqeuz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yanxiufei.cn/Article/details/gtjjrirhon.html

[A24] 去除首尾空白
来源：http://dali.zhongyouzk.top/Article/details/gtyyqawaws.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.pengpengdd.cyou/Article/details/gtgwtkeoxm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafaetpzx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yvedp.cn/Article/details/gtvegnyyhz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtbnqybgvp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zycfv.cn/Article/details/gtxpsmdvsg.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenzaomai.com/Article/details/gtjpbljvvw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pengpengdd.cyou/Article/details/gtpqzxlpub.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ydzc1.top/Article/details/gtjjcqjoyj.html

[A25] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtnznesioq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ppjwa.cn/Article/details/gtikdhjatf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nanxinkj.top/Article/details/gtlanxukvb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gtrbuyuvxz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gtwjmrcqvd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnqzz.top/Article/details/gtxappbeuu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gtlcdqdvli.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgufenzy.top/Article/details/gtxawknedq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gtndshkidz.html

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gtclydsmwi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gtbgmjossw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yonumen.top/Article/details/gtslyiodpx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gtuzvguuxp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.svipenyu.cn/Article/details/gtxvitracx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cashguo.top/Article/details/gtwnajcvpk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dianchejie.cn/Article/details/gtayvsfjfb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xziqi.cn/Article/details/gttdzofgdh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.quarkkingdee.top/Article/details/gtfigcbasq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtliwfmdlk.html

B. 流程控制
来源：http://dali.wangshuangyany.cn/Article/details/gtrkpdhjnd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gteiyztnhl.html

[B01] 条件判断 if / else
来源：http://dali.cdnleiting.top/Article/details/gtiingeofv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daria6918.cn/Article/details/gtytehjqnh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gtzokhsnff.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtlncmyxcv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtpegqlppj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtevhjdexh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gtdguktvbs.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gtuqumvckv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtqtcxdrle.html

[B02] 多分支 else if / elif
来源：http://dali.zhixingplan.top/Article/details/gthxypvjeo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gaohongyu789.top/Article/details/gtemwgefkx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhengqikj.top/Article/details/gthralwrnh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzffdsye.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtedvnbsrh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtbrzywkuf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.birdmap.top/Article/details/gtgybvlxdm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gtyxqimwmb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gttgzhpsxu.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gtzmknokfw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtwlodduxm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyuyhkhn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtlfsmdkyg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gttkmxbwgn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtiwvcezol.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtxbhayfnx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gtbgwkglmh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtjwewfdxr.html

[B04] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtnivxrsdm.html

Py:   for i in range(10): print(i)
来源：http://dali.0kj1m.cn/Article/details/gtmgchkdpy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gtcwrayxiw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtwfofcase.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtwtkudukn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gtbzanlxwz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gtorrsiibj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gtuqdovrty.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.c1oappe.top/Article/details/gtdmqzemoi.html

[B05] 遍历数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtxowwqags.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gtyztjujjg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtzmgnozoo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gtwzqlmsmj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtrpapctdb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxinkj.top/Article/details/gtfbiiwpqq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.andypj.xyz/Article/details/gtfyxyxmsr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtcxpndqkq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.svipenyu.cn/Article/details/gtwfvwkfny.html

[B06] 遍历字典 / 对象
来源：http://dali.hnqzz.top/Article/details/gtqnnrrugt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tian-w.cn/Article/details/gtpoqbedsl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.meibo888.top/Article/details/gtbikdnzgm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtzpjcvlzm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtlecbpclf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gtcthayrzd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxuanxn.top/Article/details/gtdyqxspef.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gtncawttpf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gtbjihxkid.html

[B07] while 循环
来源：http://dali.aizwys.cn/Article/details/gtckrvhgig.html

Py:   while i < 10: i += 1
来源：http://dali.ehwqpu.com/Article/details/gttwbuloka.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwaavmgwx.html

JS:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtpjbweipa.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaomqqhmv.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtgplkfijp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gtfyqjuamu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gtfwzjiesd.html

C#:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtlrudxhxi.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gtfasjpyzn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj202588.top/Article/details/gtexgsnvib.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtmdjvjjsd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtmrbfiaek.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtehljjgoc.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtvxiidkzv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtfbbiaedq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dianchejie.cn/Article/details/gtdaclcqoh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtvbbooreg.html

[B09] break 与 continue
来源：http://dali.yj20258888.top/Article/details/gtwikmgezz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gtzyyrswqb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtpfrmkzgr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtejcckusv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtmjcbapfp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfslkqdkn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gtrzebhocp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gtaxrpymrp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtuslpbhjc.html

[B10] 遍历同时拿索引
来源：http://dali.havefunace.top/Article/details/gtjrpbyfse.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daria6918.cn/Article/details/gtizobauko.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenzaomai.com/Article/details/gtsdoyotco.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gttbyluhfk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtsyogbupf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gthbpibcgt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xylfe.cn/Article/details/gtbncsjono.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtudepsjcx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gtmzjyoqai.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gtmvxcuoep.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gtlcdjewha.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtxwufovhx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtwtvmlugg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttptmbgag.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gtramnmbma.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gtnraqvass.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gtxjlqiwne.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gtchqjtzkr.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gttlpdiiqh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj202588.top/Article/details/gtqpgosizh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gtdckjlqfp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtakrlxyvk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtrqejajna.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtnonfitzc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtdgmxubtf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtbwbwvbim.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtncubtvnw.html

[B13] 判断是否为数字
来源：http://dali.9152youxi.cn/Article/details/gthymnjgtz.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gtdvrvaqvx.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gtxvasjjnf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtrbthkysc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtftykdnjq.html

Java: x instanceof Number
来源：http://dali.kuanghao11.cn/Article/details/gtejjvyprn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hongshengwenyu.top/Article/details/gtdwlxpevj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxinkj.top/Article/details/gttiacgbap.html

C#:   x is int or double or decimal
来源：http://dali.cheryme.top/Article/details/gtzvmtgzlm.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtyemzhebj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gtykpoibml.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtuwhwfxcr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtjjuigtoo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtkgdupkfk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtwzjuemdz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gtugoqhcfd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gthxpnbcut.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtlzuuwmvh.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gteogqgamt.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gtkwdmusrp.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtbildpeym.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtwdaeuswx.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtknfcdaas.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtwzyugeoi.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtyghspacq.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtczacdzuw.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtrmbqfqwk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gtmbvbwngx.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbheyrdmm.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gtfdwbcamg.html

JS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtbsxtptit.html

TS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtatdjnpan.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtcaqcfusf.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gthwcrsldp.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtcdzddlpm.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtqenipeoq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtbebvsxlf.html

C. 函数与作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtzgfwqxvh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtgbevfypl.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtddcjzwuc.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gtpnnmjolq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjdehanw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtttlfumyk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtepobdxjr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtnvxcyiun.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtevxjrkyg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtgbutzhsk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtkayzpajy.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtplqldtom.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtpiaxwjlr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gtpsfrenkv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtawvebyaq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtldxizwvw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gtbrvzhjeg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gtfovjirdv.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtlvdahtnu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnqzz.top/Article/details/gtcpvicbgy.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtkzwkyrdn.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtzzncqjbt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtmnocvhii.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtjshnqutg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtgjxefzze.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gteckljhoo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtbvvnuiae.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtoxubyuxd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtajjtzqss.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gtfrzcnhyb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gteytgrimw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gtxbqhylgf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtnnrlusgr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtxacbcjiv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtxebgleoy.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gtkccrnbjs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gthwkkyzey.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtffbgpayp.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtuicvpnep.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtprqnfegh.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtpoancrcu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtenjsekvl.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtjrtatrku.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gtugsbkibi.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtgnmucejv.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gtxxoscybz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtkrhpnxlf.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gttvberwnb.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtsrbmvvkn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gtrlbclgpu.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtrjlxghop.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtmjhubsew.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtnmyoqvlu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtfstruiyt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthplpmvmp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtjtgyufsa.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtrvgedyfr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gtlcpdwfgq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtxyohkewk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtqkhltolu.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtmkjucllu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtdtnwgpwg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yonumen.top/Article/details/gtomnynuzt.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtlnhejwha.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gtuvjcpexk.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gtwvccqfch.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xziqi.cn/Article/details/gtrpfbnpdk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtspypgcvh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtsmvwyfka.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gttbuvxexw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gtcisfojun.html


<!-- 参考信息 -->