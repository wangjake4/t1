代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.shzxlz.cn/Article/details/gthzjndbor.html

Py:   ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gthhtvsmvd.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtfppcyqlq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gtybrwcpjj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtcysfjamo.html

Java: (int) 'A'; (char) 65
来源：http://dali.meibo888.top/Article/details/gtjawwsabh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.mhx1999.top/Article/details/gtlltohwwd.html

Ruby: "A".ord; 65.chr
来源：http://dali.fzhhl.top/Article/details/gtaycttflz.html

C#:   (int)'A'; (char)65
来源：http://dali.nanxuanxn.top/Article/details/gtlksidosq.html

[A19] 交换两个变量
来源：http://dali.zhijiandao.cn/Article/details/gtevwzjgcq.html

Py:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gtyadxttym.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guannengcc.top/Article/details/gtasyaoilv.html

JS:   [a, b] = [b, a];
来源：http://dali.mhx1999.top/Article/details/gtnybralxe.html

TS:   [a, b] = [b, a];
来源：http://dali.316326.xyz/Article/details/gtfeeougee.html

Java: int t = a; a = b; b = t;
来源：http://dali.tanke756.top/Article/details/gtfxcsddze.html

Go:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtuqoabatg.html

Ruby: a, b = b, a
来源：http://dali.cqqwz.cn/Article/details/gtmeqfudwm.html

C#:   (a, b) = (b, a);
来源：http://dali.zhengqikj.top/Article/details/gtbzcimrve.html

[A20] 读取标准输入
来源：http://dali.yj20258888.top/Article/details/gtvsinuawf.html

Py:   name = input("请输入：")
来源：http://dali.quarkkingdee.top/Article/details/gtnlvoddlq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cheryme.top/Article/details/gtvqwzqzcg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zdqjudy.top/Article/details/gtyabjegev.html

TS:   // Node.js：readline 模块
来源：http://dali.xziqi.cn/Article/details/gtttlcarqj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.kuanghao11.cn/Article/details/gtzywfvrim.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aizwys.cn/Article/details/gtemcsbjkv.html

Ruby: gets.chomp
来源：http://dali.jlsjyb.cn/Article/details/gtwyangndh.html

C#:   Console.ReadLine();
来源：http://dali.guannengcc.top/Article/details/gtfqwsslrt.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gtcykgaxcy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.kuanghao11.cn/Article/details/gtevszpirm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtzfyyysej.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtfqruliyt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gthoekdlvt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtfkjjftlc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtrlsozbfy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtnzjlkldq.html

C#:   3.14159.ToString("F2")
来源：http://dali.cucudq.cn/Article/details/gtmkcsbibh.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gtvssdwfym.html

Py:   len(s)
来源：http://dali.zhengqikj.top/Article/details/gtguwmoaqh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yvedp.cn/Article/details/gtjptdvgqz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhiwuduotai.top/Article/details/gtrxgjerjf.html

TS:   s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtrvafyacz.html

Java: s.length()
来源：http://dali.gzhubu.top/Article/details/gtkmxzxybq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzawdfnbz.html

Ruby: s.length
来源：http://dali.zhongyouzk.top/Article/details/gtzgjbpgjp.html

C#:   s.Length
来源：http://dali.sysykeji.top/Article/details/gtahxrchbp.html

[A23] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gttkpzgoql.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtrnvxuioc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fengsongda.top/Article/details/gtaeukgjap.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtviscucff.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtuvyaiqyf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtfvdlijzl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jiagoushi.top/Article/details/gtqgarozrz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtmbcgflpd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hammf.cn/Article/details/gteqyzgvby.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gtvzjmubrr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnxiangtu.top/Article/details/gtpitbsjtr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zycfv.cn/Article/details/gtqpsaswpd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gtbcajxwoj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gtpjqjpmfi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yuanzhike.top/Article/details/gttpfxkhsw.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrjwbfow.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfocjcgfh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aizwys.cn/Article/details/gtkufklcxm.html

[A25] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtlwzmviuw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guowangkeji.top/Article/details/gtswdrpdmt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yvedp.cn/Article/details/gtfbitceuj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtugphrrrq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.snrcjt.cn/Article/details/gtluahqzvc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangdashe.top/Article/details/gtamquhyew.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtgntjkjdw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gtuwylrffa.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtgshaydha.html

[A26] 类型转换总览
来源：http://dali.ivvv.top/Article/details/gtwamwxtdj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gtlkiqkafn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258.top/Article/details/gtzzilzhah.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.andypj.xyz/Article/details/gtjbstthys.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shzxlz.cn/Article/details/gtssswyrcj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtqzprpmwb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yueranfly.top/Article/details/gtulljrjaf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zycfv.cn/Article/details/gtgajbeyku.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtpbmqpkza.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfamxdblb.html

B. 流程控制
来源：http://dali.xziqi.cn/Article/details/gtnvzxqvbe.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtrnpewmoi.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtjailsmsd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.havefunace.top/Article/details/gtaqbxrtmx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.havefunace.top/Article/details/gtdaprppbc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtmzibziyr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gthwqizqct.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtnqsuhrjl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigfzy.top/Article/details/gtsbgtxymc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gthkoyajan.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gttfzsitat.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gtboklumuo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gaohongyu789.top/Article/details/gtdrtrefap.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdhvgbsd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtfrauanve.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtafuronst.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtguxhskab.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.iojbl.cn/Article/details/gttdlyzrzv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gtpqdlzudp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtzfhkrteq.html

[B03] switch / match / case
来源：http://dali.c1oappe.top/Article/details/gtomjbyelp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.svipenyu.cn/Article/details/gtlhrdcxkv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlpgzinsf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtldhtxvdw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtahpcyuca.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtnjriynwz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtgtrhiyvw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gtksdrleiy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtqdlgzolp.html

[B04] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtwqefjqfq.html

Py:   for i in range(10): print(i)
来源：http://dali.cheryme.top/Article/details/gtfbokcxks.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.andypj.xyz/Article/details/gtbqvxyvmy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtharlkhgg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtcfxuohsq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gthhwdszjp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ppjwa.cn/Article/details/gtuqzcjhim.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gtkzvoadah.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gtxwtnvlhq.html

[B05] 遍历数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtopvtcvjh.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gtxtkptbje.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dashuyun.cn/Article/details/gttnwjmkzs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgddddbvj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtweythzyi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dianchejie.cn/Article/details/gtryzvebfj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guowangkeji.top/Article/details/gtnnrumfzf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.havefunace.top/Article/details/gtheyryzng.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.0kj1m.cn/Article/details/gtipocoazd.html

[B06] 遍历字典 / 对象
来源：http://dali.shangyingyoupin.top/Article/details/gtzhmzlwqc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gtrnhfweou.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gtgbezlxfv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtlvpkuttk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtejcysbkv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigufen.top/Article/details/gtolnellch.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gtdhsdfasn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gtjrmnxzhj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sweek.top/Article/details/gtgzlzxwop.html

[B07] while 循环
来源：http://dali.pengpengdd.cyou/Article/details/gtqpbhzuup.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gtyubfthtw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakdwxqjz.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtufpkzwuy.html

TS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtpqmkyjsv.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtfqtrrsof.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gtdrvuinip.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gtubwyabfy.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtsppxobci.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gtmiqmieqn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdbqlcro.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gtokapvmcm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtihsyuqyv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtolhtlcbm.html

Java: do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnmsgecc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yongpay.top/Article/details/gtcejtjohq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258888.top/Article/details/gtrpbzvyzb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtghcnqsgi.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gtzltnchbq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daria6918.cn/Article/details/gtjcogsamj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtusjphogv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtahlaeefx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtglrzohkb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtqlildhki.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gtritrscsz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sweek.top/Article/details/gtqldpkymh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtafpntwek.html

[B10] 遍历同时拿索引
来源：http://dali.dianchejie.cn/Article/details/gtoiuqrxbb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gtvcteewmg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtzlhwxyqg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtjprapjtt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtqyxkmvxr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sufxvd.cn/Article/details/gtogrqeawg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gtcczizxty.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuanzhike.top/Article/details/gtfjnhamjp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gthmrrjalg.html

[B11] 生成数字序列 / 区间
来源：http://dali.kuanghao11.cn/Article/details/gtccksiuoh.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gtbwhsipot.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtfsslylid.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtaypiqlld.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtkiqfyhgx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gtpendiqmk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gtfcgrqycq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.smart0.xyz/Article/details/gthvvniltz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtkxwqnvzk.html

[B12] 跳出多层循环
来源：http://dali.xylfe.cn/Article/details/gtgxkwdpgd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.0kj1m.cn/Article/details/gtfwldrbkl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.andypj.xyz/Article/details/gtkkzsldll.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtxzjxepwl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtiznhtlaz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtqavyyocj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gtahgoxgpw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yonumen.top/Article/details/gtcotuqbca.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtruxycmtl.html

[B13] 判断是否为数字
来源：http://dali.yj20258888.top/Article/details/gthosiczpa.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gtwtlpjbdf.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gtzxfiraoy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtxnvdlzih.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtpklgkmrb.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtsoibayfz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gtyrxtzhpq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gzhubu.top/Article/details/gtkedlmkpd.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gtjzcaogul.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gtaoywrivp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gteiwlzdzm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gtvifqdopx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtddmdhtzo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtddygxjgm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtysvxmgag.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmajthhu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtbvqhdjyh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gttvaprtre.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtpckitodx.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gtiefaqcpl.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gtvzknhhgd.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtlnhfpusg.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtibmbceoa.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtnalhmukg.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtnqmedqpy.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtvurcpvcy.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtixkxltzs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtohzjidck.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gtdrduylwk.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gtnemhqgoh.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtwkqozqnf.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtthkhfguq.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gttivdudzh.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtkobejwoy.html

Ruby: return if data.nil?
来源：http://dali.sufxvd.cn/Article/details/gtabxwmker.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtqtszecru.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcxrgtwjm.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gtakbbgyar.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdtrrdysk.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtucreclsv.html

Py:   def add(a, b): return a + b
来源：http://dali.meibo888.top/Article/details/gtaujkutej.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gttctwxlwu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcaquuoz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtvwcdkhho.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtltyszyxh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtcrdkwtsf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gttrgpskbj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtbprpbncy.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtwhurblsy.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrehqnqs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gtnllpknpi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtqqctkdfz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtusvjcomm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gtmmsepyzv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gtaqquhvwx.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtfofwakhf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtietqvkpn.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gthzotiwka.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtypxwyjkz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtdglpjdjk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigmombbq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtijgltdbp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gtwvvdrlgx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gttxltyynf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtdpyvlrsz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtqruguoor.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtzuyrvypi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtgermrxhm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yonumen.top/Article/details/gttpyuiihw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtbsjhufjb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtnysrzeqc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtxsbziiav.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtckqbiqvd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtcxkbqllb.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtpucyldpp.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gteigekuik.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtvotufmqk.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtasttutso.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtotfiockb.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtdxxcbpjn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gtjcnmlvar.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtycyjaxok.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gtdatibflu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtbuqytmep.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gtcghnyvtx.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gtxmwjemfm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gttifyqkdf.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtlivhpyuh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtpffqezbb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gtshaaruni.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtbkijbxvw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtehennntn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtbcrwhhtf.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gtriqvqiky.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gtkvliuyxt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtbqvflgxs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gthlzmeawg.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gtzbcyqxxe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtdmjnyaok.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gtizoowfce.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtrmqevovp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtbhyilbvr.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gtmxlrvruv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gticowimxa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gtutarxfjf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtbhrftxdh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtitbirrfh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gteausysje.html


<!-- 参考信息 -->