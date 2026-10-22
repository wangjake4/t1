代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.redwolf501.top/Article/details/gtvhtljziz.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenzaomai.com/Article/details/gtveoyknlr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yongpay.top/Article/details/gtugvxolon.html

Ruby: "A".ord; 65.chr
来源：http://dali.nanxuanxn.top/Article/details/gtqhxariuq.html

C#:   (int)'A'; (char)65
来源：http://dali.tianlin.xyz/Article/details/gtpgrzuker.html

[A19] 交换两个变量
来源：http://dali.yvedp.cn/Article/details/gtgyrjkqtn.html

Py:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtmefawhim.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.mhx1999.top/Article/details/gtmqlscyin.html

JS:   [a, b] = [b, a];
来源：http://dali.pengpengdd.cyou/Article/details/gtehyqdlay.html

TS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtnikzxrdr.html

Java: int t = a; a = b; b = t;
来源：http://dali.c1oappe.top/Article/details/gtwrlzhjma.html

Go:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtxwkrmucg.html

Ruby: a, b = b, a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelsnbbcq.html

C#:   (a, b) = (b, a);
来源：http://dali.nanxuanxn.top/Article/details/gtdlslvcym.html

[A20] 读取标准输入
来源：http://dali.snrcjt.cn/Article/details/gtcviewvmv.html

Py:   name = input("请输入：")
来源：http://dali.cheryme.top/Article/details/gtknzbmtlz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yanxiufei.cn/Article/details/gtjckyaohb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tian-w.cn/Article/details/gtlktmnzya.html

TS:   // Node.js：readline 模块
来源：http://dali.cashguo.top/Article/details/gtvikmaink.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gogol.net.cn/Article/details/gtnrvghhdb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenzaomai.com/Article/details/gtnvjidhuw.html

Ruby: gets.chomp
来源：http://dali.sweek.top/Article/details/gtsmcywbyw.html

C#:   Console.ReadLine();
来源：http://dali.vqdsnc.cn/Article/details/gtasjazhxk.html

[A21] 保留指定小数位输出
来源：http://dali.chenlongwang.top/Article/details/gtbxyzpgay.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj20258888.top/Article/details/gttsarrdwk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtqtrzarmr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtamxdlwpj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtrwfxvwlf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gtpcemvqrf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtvjlublri.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cheryme.top/Article/details/gtorjoavxu.html

C#:   3.14159.ToString("F2")
来源：http://dali.nanxuanxn.top/Article/details/gtzjnbntdw.html

[A22] 获取字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioziqhvi.html

Py:   len(s)
来源：http://dali.yonumen.top/Article/details/gtpkhcrizh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aibaodan.cn/Article/details/gtxwpkquba.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gtkawromnm.html

TS:   s.length
来源：http://dali.nanxuanxn.top/Article/details/gtulkiwpwv.html

Java: s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtdcguecgu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvtlvkpnv.html

Ruby: s.length
来源：http://dali.cdnleiting.top/Article/details/gtyxqzhxnr.html

C#:   s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtfvwibxcm.html

[A23] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gteqvlgrqr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gzhubu.top/Article/details/gtwrtuhxug.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gtrkpmsdun.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtusfogmfw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gthfijdydv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gtwjkgncki.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hnqzz.top/Article/details/gtvzqricdx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cashguo.top/Article/details/gtukhmblpo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxuanxn.top/Article/details/gtnrcjuxrl.html

[A24] 去除首尾空白
来源：http://dali.nanxuanxn.top/Article/details/gtsarbxyzo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gtdxlhaejh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aizwys.cn/Article/details/gtsdansqvx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gtcedblixu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yvedp.cn/Article/details/gtdjqkxxwr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrqfnlbo.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgufenzy.top/Article/details/gtslvrcojo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guannengcc.top/Article/details/gtbgseyjwt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gtacxrshbo.html

[A25] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtglwfqefw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinghuilouyu.cn/Article/details/gtlftouctx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhoulong.xyz/Article/details/gtjupqqwzg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtifkefzem.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jianghu66.top/Article/details/gtvhjsktko.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yonumen.top/Article/details/gtihufjpco.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gtvebowdwa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuanzhike.top/Article/details/gtcpwntaek.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtgutkqawg.html

[A26] 类型转换总览
来源：http://dali.ivvv.top/Article/details/gtboewdueg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenlongwang.top/Article/details/gthsrkvnbt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.kuanghao11.cn/Article/details/gtivirukkq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shzxlz.cn/Article/details/gtzadbinnm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sysykeji.top/Article/details/gtnseckwni.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtcjmczujg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sysykeji.top/Article/details/gtcukukcsc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cdnleiting.top/Article/details/gtcmgwpgxy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gtsqdvvyin.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxuqziywx.html

B. 流程控制
来源：http://dali.tianlin.xyz/Article/details/gtmideqwpw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwpnelwzv.html

[B01] 条件判断 if / else
来源：http://dali.9152youxi.cn/Article/details/gtgopeeyrr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtwgttbkdg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258.top/Article/details/gtqhimskiz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtbzypifbm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtbsghbuga.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtbnziefvo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cdnleiting.top/Article/details/gtdlwyrpkc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gtyttsgqea.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtniksjptm.html

[B02] 多分支 else if / elif
来源：http://dali.yuxming.cn/Article/details/gtazxccuvt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sysykeji.top/Article/details/gtdworyrsd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yvedp.cn/Article/details/gtdshzuave.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gttoibkvgs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtfyatljcb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtlygmypdc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigfzy.top/Article/details/gthiyewbdk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gtbkmemima.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtxnpersdi.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gtjhlkxbrb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuxming.cn/Article/details/gtqmuerlzk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtxamztlnq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gteszaixla.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtsfdkwcyg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtfpsyvlus.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtwrbvuftc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yanxiufei.cn/Article/details/gtedryegqj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtnmemvvaa.html

[B04] for 计数循环
来源：http://dali.316326.xyz/Article/details/gtvtojfoav.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gthnwtacvw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dianchejie.cn/Article/details/gtfcewigul.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtbsnpwgzz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwsedzcx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gtuxyqsqqa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhongyouzk.top/Article/details/gtycwtizun.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cucudq.cn/Article/details/gtppywrtwr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibpbggws.html

[B05] 遍历数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtwspvbenu.html

Py:   for item in arr: print(item)
来源：http://dali.aibaodan.cn/Article/details/gtasjpigjn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zycfv.cn/Article/details/gtwokpwrsy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gtsfbhsxin.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtweefhoeo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yongpay.top/Article/details/gteqacakbi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtxvyrqstm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gaohongyu789.top/Article/details/gtjjxyebbf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gtpmzefhrn.html

[B06] 遍历字典 / 对象
来源：http://dali.iojbl.cn/Article/details/gtgudefxdg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gtsaatmhqk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xinyue.icu/Article/details/gttcnoxnbm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gtgvvzajai.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtttpemmlh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.meibo888.top/Article/details/gtmbtseeaq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gtbukhzvvz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtvmgdqbpx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzactiee.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gtgenbrntg.html

Py:   while i < 10: i += 1
来源：http://dali.chenlongwang.top/Article/details/gtlvlitepb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorhsowoi.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdtkbyjrd.html

TS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtbafverdg.html

Java: while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtbaknfmwd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.smart0.xyz/Article/details/gtrvvhgbsb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenlongwang.top/Article/details/gteugkwfun.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtjxwyrvmp.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtmqhnzdyk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfjcmfvb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtdmxjcptp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtdjbchxgb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtdhqlfugm.html

Java: do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtxmarfrty.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtwhvzozum.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jlsjyb.cn/Article/details/gtfxttawzx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtgkaunrbm.html

[B09] break 与 continue
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovduwyck.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gtvccnrsea.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtqbmzczcs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtbvsfcvlm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtrhmiklag.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtmapzgyiq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtwguzsnfs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtbinfxxdx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtlnqwqiib.html

[B10] 遍历同时拿索引
来源：http://dali.aibaodan.cn/Article/details/gtpvpsxixw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gtpppxewmp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdejnaas.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtvzgfjmng.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtssqwrwfy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ydzc1.top/Article/details/gtfkoelrmr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gteflgtuqd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtyfbdfghq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtwsgejmcg.html

[B11] 生成数字序列 / 区间
来源：http://dali.cashguo.top/Article/details/gtodypdplu.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gtymqjwvfz.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gtkloekpqs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtpbxwiyzf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtxyeuqafn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gtfrpnydsc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aibaodan.cn/Article/details/gtyzjqvycm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gtgashwfym.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtdvwindlq.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gtukcgjazl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtqylcspya.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtbvbbvmmq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtyafyffkz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtmjlhjorz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtfbcminqh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gtxuvogabr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtpcdeuyhe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gtkdauqhdt.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvutxojo.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gtvkpxjicv.html

PHP:  is_numeric($x)
来源：http://dali.nanxuanxn.top/Article/details/gtitpzklxv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtmxlclqqb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtlxdrhxno.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gtlrgpgsoe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gtlujumtcu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gteoywsbti.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlsgeqbc.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gtkbytuokc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtdtlacznl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtqlbcuwxv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtacrctbrr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtyejqhxvk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtkddqwdml.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhrgrkye.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtvqqhzxot.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtltjukgui.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gtqhjbumdj.html

Py:   a and b or not c
来源：http://dali.yongpay.top/Article/details/gtwykgzafg.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtfxxsvkpl.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtynenpjeh.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtaohpdacp.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxnzcycu.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtftxefovl.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtsbbjohdm.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtgazqkerg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gttionhfmt.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtwpewuqrd.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtewrcoucv.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gthxhfrbjq.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtmlpfirty.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtmofqphbp.html

Go:   if data == nil { return }
来源：http://dali.svipenyu.cn/Article/details/gtjafszwub.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtvihckzoc.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtozuldzbs.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpgqqgdzj.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gtvmsjgyhx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpthkjydx.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtqnphajyj.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gtwgtovcgu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtkwbhodog.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgosdtrmx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtgebwyrwp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtetafduar.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gtaiytubdq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sysykeji.top/Article/details/gtjyqxyjos.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtuozzqfez.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gtkdjwnubc.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gthuulsntx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqcrxmzty.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtewvmucgs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gttwlbkrah.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gtriucjcxf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtmzldyeud.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtchyzipgq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jianghu66.top/Article/details/gtqrsgqwmu.html

[C03] 可变参数
来源：http://dali.sxryk.cn/Article/details/gtzcbjoulg.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gtxpxbzxec.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gteeyctvsj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtwzcqghvt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtjosfkvwo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gttqqlmyxo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtwatoreed.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtvoeovqvu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gtsmcihbcr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtbodlcyfd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtspdassmq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtfsbjsbzt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtbeduckun.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvhkofis.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtqcuwwvlu.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtruyrxwef.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gttqynaoxv.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtqrijgxyx.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gthuqxpbcd.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtyfqwrnwu.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gtzaavwjkh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtspshxxtf.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtvurbvmmd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gtxpivgund.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtnjughiqr.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtbfmwktlz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtkgjxvgls.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtftvnvakt.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtplvxjbmp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtrliunjwn.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtbzlnwqjz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gthsrsubvc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtqzczkxzh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtyocprgct.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtdrmofzta.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtqfbmnlwd.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtkdvzbcrw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gtkmpenjfj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hammf.cn/Article/details/gtwlpaesua.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gtalewrjzo.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyfihsei.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtxffxkixb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfnnvsfh.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gtpfvuaffr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gthutibrix.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtqudowkyb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gtpzgakzyv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gtbattthuk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtjukrantm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtkcyfczen.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gtjpkymmia.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtfbygufgo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtsughmtpk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtwijoorde.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gtankaswda.html


<!-- 参考信息 -->