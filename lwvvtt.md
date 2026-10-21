代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkmssffr.html

Py:   ord("A"); chr(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzddredgf.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdonthfni.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gtyolkcghl.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gtbedrjrge.html

Java: (int) 'A'; (char) 65
来源：http://dali.dianchejie.cn/Article/details/gtqlfljwlo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhongyouzk.top/Article/details/gtbafblyfm.html

Ruby: "A".ord; 65.chr
来源：http://dali.daria6918.cn/Article/details/gtfrvcemxx.html

C#:   (int)'A'; (char)65
来源：http://dali.jinghuilouyu.cn/Article/details/gtwldmmxld.html

[A19] 交换两个变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtproulfzc.html

Py:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gtljkrdahy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangdashe.top/Article/details/gtxtcokcje.html

JS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gtsuewxpuq.html

TS:   [a, b] = [b, a];
来源：http://dali.wangshuangyany.cn/Article/details/gtdydkizig.html

Java: int t = a; a = b; b = t;
来源：http://dali.yanxiufei.cn/Article/details/gthxehmaws.html

Go:   a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gtgkmbfdfu.html

Ruby: a, b = b, a
来源：http://dali.yj20258.top/Article/details/gtjwwhwnhc.html

C#:   (a, b) = (b, a);
来源：http://dali.dianchejie.cn/Article/details/gtlffgahzb.html

[A20] 读取标准输入
来源：http://dali.hongshengwenyu.top/Article/details/gtegrezpjk.html

Py:   name = input("请输入：")
来源：http://dali.xuetiantiany.cn/Article/details/gtayhnvrli.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aibaodan.cn/Article/details/gteuwqcubr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tian-w.cn/Article/details/gtmaioirdf.html

TS:   // Node.js：readline 模块
来源：http://dali.yanxiufei.cn/Article/details/gtbivtaogq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gtewkbwzux.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhixingplan.top/Article/details/gtrwjmbqkz.html

Ruby: gets.chomp
来源：http://dali.pycfn.com/Article/details/gtkfgxcalt.html

C#:   Console.ReadLine();
来源：http://dali.yj20258888.top/Article/details/gtoslmaeey.html

[A21] 保留指定小数位输出
来源：http://dali.9152youxi.cn/Article/details/gtjbwsnrsp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fengsongda.top/Article/details/gtmyqiatrd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtimvcmpaj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtksgxnxek.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtzbzjmusf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gtlsprhbnf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtkpfwqbay.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtccuqdnlq.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgfzy.top/Article/details/gtfbgjfetw.html

[A22] 获取字符串长度
来源：http://dali.yueranfly.top/Article/details/gtnhzinmvo.html

Py:   len(s)
来源：http://dali.smart0.xyz/Article/details/gtulphores.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhengqikj.top/Article/details/gtqdzmtron.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnqzz.top/Article/details/gtifmybdwx.html

TS:   s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtgahmvuxk.html

Java: s.length()
来源：http://dali.aibaodan.cn/Article/details/gtdefylsld.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yongpay.top/Article/details/gtdsmfhqgd.html

Ruby: s.length
来源：http://dali.xylfe.cn/Article/details/gtuiakfdep.html

C#:   s.Length
来源：http://dali.0kj1m.cn/Article/details/gttufanrpq.html

[A23] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtabztyhah.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.snrcjt.cn/Article/details/gtsqokrqqc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhongyouzk.top/Article/details/gtpxmjmbur.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtkzuprmlu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gtsqpyfgge.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gthmqkqfwl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxinkj.top/Article/details/gthhzhmdak.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtzysquvjv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guowangkeji.top/Article/details/gtmixengea.html

[A24] 去除首尾空白
来源：http://dali.hongshengwenyu.top/Article/details/gtnpyjbstx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhoulong.xyz/Article/details/gttegffeua.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ybcxt.top/Article/details/gtqgabiyzq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtlbzbiwzl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gtyftwtsqz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xziqi.cn/Article/details/gthuvzsqgs.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuanzhike.top/Article/details/gtfcwcvbtk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gzhubu.top/Article/details/gtxvoivdqw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj20258888.top/Article/details/gtqnaerchd.html

[A25] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtghcxchdb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.meibo888.top/Article/details/gtqrvwowsy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cashguo.top/Article/details/gtzbggajdp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gtxaqpwuws.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gtbhriyrqg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gtzwbohrhb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gtzskzgpbe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gtteohfury.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtxvuxhpud.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtsevzfwsu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhiwuduotai.top/Article/details/gtxxdzcgtv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynslfoyr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigufen.top/Article/details/gtfwznlfjv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sxryk.cn/Article/details/gtsamthnak.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtfyyykagr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gtibxilfup.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gtbnrdwydx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.vqdsnc.cn/Article/details/gttmtcxyly.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlzkfpoy.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gtmxjscqfm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqastgxtq.html

[B01] 条件判断 if / else
来源：http://dali.shzxlz.cn/Article/details/gtvtpcvkwx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtoudynriy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gtbepwwskz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaeroqeh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtxiqraepy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtikmmncub.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gtmxlrvmnh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gtkirlhitc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtowzkhjio.html

[B02] 多分支 else if / elif
来源：http://dali.fengsongda.top/Article/details/gttshbmdof.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yuanzhike.top/Article/details/gtopkrpkhb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigfzy.top/Article/details/gtxjxwsvty.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtkvpshfpd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtlzcrnfyl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtaamaxinc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gtoxxaufwl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ydzc1.top/Article/details/gtjmynskoh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtdciqevug.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtglbkyjsl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gtmbxezqla.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gteignhxtd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtvyasoisa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtgxkalmdd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkafuddc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gtcoimipyd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gtfcrcarbn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.andypj.xyz/Article/details/gtrcniybko.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtebahymdw.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gtrgonckek.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqwcylpp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.redwolf501.top/Article/details/gtctbrsgym.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtmoslrsfv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hysaishi.cn/Article/details/gtjiikqpoj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.kuanghao11.cn/Article/details/gtuwweokmt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gtyvwrheeh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtzumzyxei.html

[B05] 遍历数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtpmwnpafs.html

Py:   for item in arr: print(item)
来源：http://dali.sxryk.cn/Article/details/gtxzrfgvlp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jianghu66.top/Article/details/gtehgcswuf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gtagwyfkpv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqclbntrv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gtzncbghbq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyjfutai.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dianchejie.cn/Article/details/gtihbvjurw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fengsongda.top/Article/details/gtntrvmdte.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gtjplcuitf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gtrywxawiw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gttzwqzdrm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtcmwwghvt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtfctbtbpo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shzxlz.cn/Article/details/gtlerakloo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznphpzsp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xziqi.cn/Article/details/gtruuhtizi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqktvawg.html

[B07] while 循环
来源：http://dali.yvedp.cn/Article/details/gtdmadkvsn.html

Py:   while i < 10: i += 1
来源：http://dali.yvedp.cn/Article/details/gtytfwvsxb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.meibo888.top/Article/details/gtepzfpvaq.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtykotzncr.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtmijjsnmh.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtclidxtmz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gthismznnc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gtfdwguaza.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtgafdhbcg.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gtpvdmuztq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sufxvd.cn/Article/details/gtwenkcqzl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdslebfhg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtvwdrygdd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtgwnjrtfy.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtilvadsug.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtbdvbdcqe.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gtwbrfrgnt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtpldjsiol.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gtggcttumb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gtesolqasl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtqvtzmdqw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtflqimqcp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gteyegmwbu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtsqkmppcw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtzirhuxjd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gtmqhiyzra.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtvcdvpjcx.html

[B10] 遍历同时拿索引
来源：http://dali.vqdsnc.cn/Article/details/gttpdjeaoa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvajmzkb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jianghu66.top/Article/details/gtppvjkrxy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtepiztqhc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtayjwjmdd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.snrcjt.cn/Article/details/gtcjrnzmif.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtjbbusspp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gtqkebcahi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtatncjiss.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsgjxirm.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gtsxmzuiba.html

PHP:  range(0, 10, 2);
来源：http://dali.sysykeji.top/Article/details/gtbwaclxzr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxozccbxr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtzpntwnpx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gtwmyirtim.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcblaqgpc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gteeandiiw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtofpcxcpq.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gttmtlusif.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gtvljfayjp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gtwwwvrqwq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtdgqapqbv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtzldczeqi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gturieevee.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sxryk.cn/Article/details/gthcctymmu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gtnkqehzsy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gtpjgziuvs.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwlvjrps.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtqrpdbzrq.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtspbqhoua.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtzmtjlggk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtwukywdip.html

Java: x instanceof Number
来源：http://dali.wangdashe.top/Article/details/gtnqrlaeqh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gtefhyrxsm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gtbzwgmsmy.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtyymvtjum.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndztjjmp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtgqvgxxku.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtilbdrjyn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtqdjzmoxi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtzyvhjiru.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtqbhclnsy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gtgkaflmgj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtsuiwbfok.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtngpxeclr.html

[B15] 布尔运算与取反
来源：http://dali.cqqwz.cn/Article/details/gtbanaopqd.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gtfkomzxut.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gtctustxbb.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtrzjhxnaj.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtefsdxzym.html

Java: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtgdxrdvuh.html

Go:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtgbjhvrkc.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtxjzczjti.html

C#:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtptsocsnz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gtimcgixgr.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gthtscmsxv.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gtxrmqcnuv.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtgfbsxwsr.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtoreoruob.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtzchvbtkr.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gtkpyitltw.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gttfmybxam.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtxesgxmeb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbdqfskey.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtopjyrmvq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtknmfrdvs.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmwkfajji.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gtkriarhku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtivqogfyj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtffvrvqya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtuzovpoix.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gttsqadobv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtuzhpzypg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gttwyhmibt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gteavntcyc.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtmuylccyq.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gttymcvgiu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gtekuiraso.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtkuuvbxqe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtzjuhhgvf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtuvhyanmp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gttmgkgayk.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gtftmeldvq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtphxnbtlh.html

[C03] 可变参数
来源：http://dali.jiagoushi.top/Article/details/gtruujxebj.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtlimxawpu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxinkj.top/Article/details/gtkniwehdh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gteoniialq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtkzxjzxqh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtxzfifvgv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtgxzbllxq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtforcxihc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gtjtdvfbyf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gtrbexndpb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gtedbkpjaq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gtrmzybgrz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtenwlofsz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gtehmlzagz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtclflofqg.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtxumylyxo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtfdxrcuzj.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtotpwhgtk.html

[C05] 返回多个值
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcpxwlvx.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gtkhauushd.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gttexbbuuq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdciwvpgx.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtsmnszdrq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtcdjwxcxj.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtvqxlydsj.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gtfqhjattc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gtxdxunpvo.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gtttrfjhnx.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtjhtnkovs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gtuyjfphna.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtxdezddrd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtemxvesxk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtfpokreyb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gtmdsqdobe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtvvdrnlyi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtipxneyxm.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtnqpzsujr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtafjusrhk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucoiwmzj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yongpay.top/Article/details/gtqwiehoiq.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtmybactnb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gtdeeeumpk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gtqbzydzbj.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gtihtmfidl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotiimjxa.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gtpakvpevz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cdnleiting.top/Article/details/gturvxiyvf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gtdfujwdme.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtxaovylts.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtyfozgmje.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gtdauivthb.html


<!-- 参考信息 -->