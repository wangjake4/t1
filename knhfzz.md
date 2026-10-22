代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.haohaochexian.top/Article/details/gtupffeztb.html

Java: (int) 'A'; (char) 65
来源：http://dali.xinyue.icu/Article/details/gtbmuwojri.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gteifpgjiq.html

Ruby: "A".ord; 65.chr
来源：http://dali.yuanzhike.top/Article/details/gtasufvnvj.html

C#:   (int)'A'; (char)65
来源：http://dali.jiagoushi.top/Article/details/gtcfewoede.html

[A19] 交换两个变量
来源：http://dali.yonumen.top/Article/details/gtsrayajkw.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtbfilkeom.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.redwolf501.top/Article/details/gtxdyohdsd.html

JS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gtfuhpogwm.html

TS:   [a, b] = [b, a];
来源：http://dali.kuanghao11.cn/Article/details/gtnpttiggr.html

Java: int t = a; a = b; b = t;
来源：http://dali.smart0.xyz/Article/details/gtuqdzfjnl.html

Go:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtvtpiwshd.html

Ruby: a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gtczvmipuz.html

C#:   (a, b) = (b, a);
来源：http://dali.xuanzx.com/Article/details/gtwlnnaaib.html

[A20] 读取标准输入
来源：http://dali.zhongyouzk.top/Article/details/gtgxmwsdsw.html

Py:   name = input("请输入：")
来源：http://dali.ppjwa.cn/Article/details/gtxkuvohdp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hongshengwenyu.top/Article/details/gtafugusrp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhixingplan.top/Article/details/gthbffmkpp.html

TS:   // Node.js：readline 模块
来源：http://dali.yj20258888.top/Article/details/gtyrckctdj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yuanzhike.top/Article/details/gtigplcupi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zycfv.cn/Article/details/gtulvagjim.html

Ruby: gets.chomp
来源：http://dali.cashguo.top/Article/details/gtwtaaoxjp.html

C#:   Console.ReadLine();
来源：http://dali.svipenyu.cn/Article/details/gtgewrehry.html

[A21] 保留指定小数位输出
来源：http://dali.meibo888.top/Article/details/gtvmbimgii.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ppjwa.cn/Article/details/gtweefdbow.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtbbnqexow.html

JS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtovvhjlei.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtramcwgny.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtgkqiuaeq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtcpriukat.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtetdupzbo.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuetiantiany.cn/Article/details/gtjdyxvcmv.html

[A22] 获取字符串长度
来源：http://dali.havefunace.top/Article/details/gtxtzxkswq.html

Py:   len(s)
来源：http://dali.guannengcc.top/Article/details/gtaqyqxfha.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fzhhl.top/Article/details/gtqxizmlxk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.andypj.xyz/Article/details/gtmxioswws.html

TS:   s.length
来源：http://dali.9152youxi.cn/Article/details/gtxvzkztsz.html

Java: s.length()
来源：http://dali.ppjwa.cn/Article/details/gtogwqwrte.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtqayyehxy.html

Ruby: s.length
来源：http://dali.jqgufenzy.top/Article/details/gtycsuxadh.html

C#:   s.Length
来源：http://dali.yangfankeji.com/Article/details/gtwjknmufl.html

[A23] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtbhsnvnex.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.aibaodan.cn/Article/details/gtabzqqssu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ydzc1.top/Article/details/gticpewfkg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gtdnpbebxd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gtczdwyfya.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbkyaniv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.iojbl.cn/Article/details/gtrbvbmsnc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtfewyydsd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtgjwgzsth.html

[A24] 去除首尾空白
来源：http://dali.meibo888.top/Article/details/gtoszrfplc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zycfv.cn/Article/details/gtxtnhqapo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gtwsyelphv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gthdfeppwd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gtkvgmwflr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yueranfly.top/Article/details/gthwlqpjyq.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258.top/Article/details/gtwdrzpvwf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gotoacloud.top/Article/details/gtcaaomfmg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvfmxzwm.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gteurkfomj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.quarkkingdee.top/Article/details/gtfsdzprkk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cheryme.top/Article/details/gtqszhnjpa.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gtnttbilsp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gtspzqmldo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.svipenyu.cn/Article/details/gtmsdzyhxk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtpnkcddpk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gtlxpavvaa.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtzoxekcog.html

[A26] 类型转换总览
来源：http://dali.tian-w.cn/Article/details/gtgwjepgol.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gtvxwlgxlv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gotoacloud.top/Article/details/gtpkjszkhc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gtiihlfalq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sxryk.cn/Article/details/gtkdeyhexj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gtgszlignb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.svipenyu.cn/Article/details/gtjpvpcedm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yvedp.cn/Article/details/gtwuwctnjl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqohnobu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtkaqvyblf.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gtdxlillhb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtxlfrtpqs.html

[B01] 条件判断 if / else
来源：http://dali.mhx1999.top/Article/details/gtnhkdcmsh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xziqi.cn/Article/details/gtnusutnnc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbicilybv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gthryebmsa.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtogcsfiui.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtyajextit.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gthuevebed.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sysykeji.top/Article/details/gtrsbssktv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gtzeozwujj.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gtktdfnxsv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nwbrower.top/Article/details/gthdnwlsxk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jlsjyb.cn/Article/details/gtlvrpyrwm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtpqqvdsxs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtztaghatg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gtvbkkdlqy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jianghu66.top/Article/details/gtxnxszhks.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ppjwa.cn/Article/details/gtptoavzrr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtnfkraqba.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtjrekuvpc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gtklvsqfhp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcylwqvq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gthbmrbtly.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtxhvojwkh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtxjzfurab.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gtpveeaxxi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.c1oappe.top/Article/details/gtyzzvfukz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtdhtnxgbs.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtowmrausu.html

Py:   for i in range(10): print(i)
来源：http://dali.smart0.xyz/Article/details/gtkfxfmote.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sxryk.cn/Article/details/gtntawnrga.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gtflkjssjz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yongpay.top/Article/details/gtfueelqxf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.haohaochexian.top/Article/details/gttauimioi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tanke756.top/Article/details/gtvdshpmrm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.birdmap.top/Article/details/gtowpqohum.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ydzc1.top/Article/details/gtrpqxochk.html

[B05] 遍历数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtqiyfudhu.html

Py:   for item in arr: print(item)
来源：http://dali.zhongyouzk.top/Article/details/gttwrfjgov.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.9152youxi.cn/Article/details/gtbdhuhaaq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gtjoqzlcus.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtcizxpwao.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xinyue.icu/Article/details/gtpkitfvwb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtlvcrjgni.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fzhhl.top/Article/details/gtwlfopgtx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gtfryhmtpd.html

[B06] 遍历字典 / 对象
来源：http://dali.dianchejie.cn/Article/details/gtaznwqplx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.bjfxy.top/Article/details/gtwfxawwvz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dianchejie.cn/Article/details/gtpusjvtuj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gtnxlczfig.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtrujqktyk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gtrskuqkln.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenzaomai.com/Article/details/gtonfsogtq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtkftkdlwy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.svipenyu.cn/Article/details/gtncwbwtvv.html

[B07] while 循环
来源：http://dali.jyoumei.cn/Article/details/gtmkqthvlg.html

Py:   while i < 10: i += 1
来源：http://dali.zhijiandao.cn/Article/details/gthewwbulo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zycfv.cn/Article/details/gtyqnvnova.html

JS:   while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtwklhmnzl.html

TS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtusgemwld.html

Java: while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtqlepbxbw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zycfv.cn/Article/details/gthlycbwty.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjxubrhy.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtbouuzqgs.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gthypuzepq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gtkzgkiths.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gtrleelljj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtczcchglv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtzrqphsqv.html

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtklacmwts.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjddbgia.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gtibyxfdci.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtztbztzhd.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gtodxvduyq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sysykeji.top/Article/details/gtknvgaich.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtvbskhrdw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtfxiyiccb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtsqsjkncy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuypvqjow.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtvgfabqqc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yonumen.top/Article/details/gtcvgnpnyw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtxmrztejc.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtjdjkpxdk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gterqyqbud.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gtspcnpzxy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtwdczxvrl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdmbnhgq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhixingplan.top/Article/details/gtcecosycx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gtpktgjozz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gtzxnixpjw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258.top/Article/details/gtcpqleggl.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gtuabgxoxk.html

Py:   list(range(0, 10, 2))
来源：http://dali.yangfankeji.com/Article/details/gttpwcbsdw.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtdxztmabx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtjwqartyc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtfudkqkjr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shzxlz.cn/Article/details/gthepbzseq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalnmfcqg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gtbxsnvuvd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtogyysmdo.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gtayiybwbq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtehljtlzz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gtsnudspgb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtrzesngdy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtwqwcczod.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtmdjlrcgr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtwimabypw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gtimjipkfd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtgvuhufzx.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gteogdzyyf.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gtoduzqyfa.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gtcnzrzysm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gteewvkart.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtsqdalxxs.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtlryzcfme.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gtmiyncava.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sysykeji.top/Article/details/gttaahfmte.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtxsofyuru.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvvkwrrx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gtaetfmlkb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gtwwldjdjw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtsirvpelz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtehpxdbhk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtawqlebkw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gtahbzzgfb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtytwjzxqe.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtvazutnar.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gtydtcdtgf.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gtexizporn.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gtkoftrlly.html

JS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalknrepu.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtusdzfixs.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gthvcvvtka.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtgzerrheu.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtyezjmzno.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtixtkopvj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtmdntkwid.html

Py:   if not data: return
来源：http://dali.jiagoushi.top/Article/details/gtvchuwpta.html

PHP:  if (!$data) { return; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklzrlmjo.html

JS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtqcdqarsh.html

TS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtawlesflk.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtgxyagmfn.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gtlwcaqoos.html

Ruby: return if data.nil?
来源：http://dali.gogol.net.cn/Article/details/gtjejfhwrd.html

C#:   if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtynwqomvk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtedzovrpp.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtaldwixek.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtedkkxorm.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtnomgplxx.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtxxjeckpr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtyukpuadp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtfvsfgiwu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtdewcnfil.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqrdmknuy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtdhktghlm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtrryeodtc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtnregkfxk.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtytjfovir.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtjxxzezoa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gtrlmhelna.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gthknftqwg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtucqvqbds.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtzbqxfmyj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gtpgbvvmar.html

Ruby: def greet(name = "World") = name
来源：http://dali.mhx1999.top/Article/details/gtfacvebde.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhoulong.xyz/Article/details/gtalcxagkq.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gthbmdiuir.html

Py:   def total(*args): return sum(args)
来源：http://dali.jiagoushi.top/Article/details/gtqvrgtyqd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gthugrzznv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtcuevzilf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtrcgimhhh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtriiuddys.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gtlngrjsjx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtcgnfexmo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xinyue.icu/Article/details/gttinmsddm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtlrcfrosh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtiepmtorb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hysaishi.cn/Article/details/gtvwgpifpp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtigghlrtx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nwbrower.top/Article/details/gtnwkbqhba.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtzukvanwc.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gtyyvbezte.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtuevsgvgo.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtacurgbzj.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gtnoyatnoa.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtbinwtjvr.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtlizttrow.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtbdgccxlc.html

TS:   return { a, b };
来源：http://dali.sysykeji.top/Article/details/gteptxtxjo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtgolunkal.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtjasepasl.html

Ruby: return a, b
来源：http://dali.hywenlv.cn/Article/details/gtvhbjtryu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtalwoqqcs.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtvwbmmufy.html

Py:   square = lambda x: x * x
来源：http://dali.yuanzhike.top/Article/details/gtdvdqcnas.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtxjcgzweu.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtowsigycv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtuwudvexe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtbbewpezq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gtoynmqjdy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yueranfly.top/Article/details/gtdmddfzvw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtzooncdhv.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gtaejckmrt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtrcvlsspb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtyuexwcdm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtqprtzhen.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtkpqjkdxn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtwotaldck.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gtvzrahwfh.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrnyrdqw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gtzmgtlonr.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gttlkslzbz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gthwzvfgtx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gtddgcuqnx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtmsamboge.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtvxynsixz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gtadtbftva.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtmcafkxog.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gthsoxjaye.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtsefyykpa.html

[C09] 递归
来源：http://dali.hfpthk.cn/Article/details/gtxpgpjmyr.html


<!-- 参考信息 -->