代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dianchejie.cn/Article/details/gtcwdqgvyg.html

Java: (int) 'A'; (char) 65
来源：http://dali.bjfxy.top/Article/details/gtcwazmmpg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jqgfzy.top/Article/details/gtslcbzofj.html

Ruby: "A".ord; 65.chr
来源：http://dali.bjfxy.top/Article/details/gtwblxrhps.html

C#:   (int)'A'; (char)65
来源：http://dali.xuetiantiany.cn/Article/details/gtelwoluzj.html

[A19] 交换两个变量
来源：http://dali.kuanghao11.cn/Article/details/gtnylanahl.html

Py:   a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtdiahukqa.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgduhwqgc.html

JS:   [a, b] = [b, a];
来源：http://dali.aibaodan.cn/Article/details/gthurvwahq.html

TS:   [a, b] = [b, a];
来源：http://dali.gzhubu.top/Article/details/gttahmcije.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinqigfzy.top/Article/details/gtmdgslajq.html

Go:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtvecajqxa.html

Ruby: a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gtyptfsjza.html

C#:   (a, b) = (b, a);
来源：http://dali.sxryk.cn/Article/details/gtaglcaefc.html

[A20] 读取标准输入
来源：http://dali.9152youxi.cn/Article/details/gtcqkglhkb.html

Py:   name = input("请输入：")
来源：http://dali.cheryme.top/Article/details/gtqujhbfma.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gtsotlvzbh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.quarkkingdee.top/Article/details/gtropvkngh.html

TS:   // Node.js：readline 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtiliqlecz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gogol.net.cn/Article/details/gtzwmkcuhh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.mhx1999.top/Article/details/gtnnymthgb.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtuvnzefhs.html

C#:   Console.ReadLine();
来源：http://dali.tianlin.xyz/Article/details/gtzqgqkpoz.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gttbdkalhi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhoulong.xyz/Article/details/gtovxrxrpi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtikewapji.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtxzfmnmil.html

TS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtovsdibwf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtxhfqfvra.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gtlnztxndx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtabealezw.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gtfccstndr.html

[A22] 获取字符串长度
来源：http://dali.ybcxt.top/Article/details/gtmkltzlsm.html

Py:   len(s)
来源：http://dali.xziqi.cn/Article/details/gtmmbpbjxm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xziqi.cn/Article/details/gtuhipqsfz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.daxiang520.top/Article/details/gtqypuqtrp.html

TS:   s.length
来源：http://dali.ybcxt.top/Article/details/gtykoyuyhk.html

Java: s.length()
来源：http://dali.ybcxt.top/Article/details/gtqzizdvou.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhixingplan.top/Article/details/gtnoyjkuei.html

Ruby: s.length
来源：http://dali.tianlin.xyz/Article/details/gtxijhpotb.html

C#:   s.Length
来源：http://dali.snrcjt.cn/Article/details/gtpxmqopkq.html

[A23] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtdkqfnprp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sweek.top/Article/details/gtydkubvez.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhijiandao.cn/Article/details/gtshszqzlw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtsukoeccn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtrxhnshgy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtizahucah.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.dashuyun.cn/Article/details/gtskuftfyz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gthdueoaih.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkufudqc.html

[A24] 去除首尾空白
来源：http://dali.gogol.net.cn/Article/details/gtqarwccff.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigfzy.top/Article/details/gtpocfdfed.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenlongwang.top/Article/details/gtfgjrdyuh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtywwhysiy.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtzptrbaku.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.9152youxi.cn/Article/details/gtimhayrtv.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtpoqxwwkh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gtprvviblm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtjsquiopk.html

[A25] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtbdicghmm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hammf.cn/Article/details/gtbpbfalgw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gtvdzjtfso.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgfzy.top/Article/details/gtfircqsqj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtjtdcfpgc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtzbiwwvbz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtwvteogoj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yueranfly.top/Article/details/gtaecygurs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtxegadnts.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gtbonklahj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tian-w.cn/Article/details/gtlwhkoplz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnxiangtu.top/Article/details/gttzksbwoa.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nanxinkj.top/Article/details/gtaijfxygn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zdqjudy.top/Article/details/gtvokdcqyg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtzrrmzewg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxuanxn.top/Article/details/gtzxndsajj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daxiang520.top/Article/details/gtfkfsjacs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtflevixjq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzsvxybpk.html

B. 流程控制
来源：http://dali.nanxinkj.top/Article/details/gtyolsovri.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxrpiprdk.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gtkhhuejam.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ybcxt.top/Article/details/gtjxxpavah.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtmukdinnt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtmffkhzfu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtfkdxxzxg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtdymfkvto.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.feifeiyinyue.top/Article/details/gtwkdiqvle.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gtjwyrjtwb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtoucjfjoz.html

[B02] 多分支 else if / elif
来源：http://dali.sweek.top/Article/details/gtddmtytia.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxuanxn.top/Article/details/gtdfnvuchj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gtmppurifq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtipvauaqi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtisxsxomi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtdmvmkdzx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hfpthk.cn/Article/details/gtaiuijvil.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gtmbanrnno.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtptrvgkhk.html

[B03] switch / match / case
来源：http://dali.tianlin.xyz/Article/details/gtrxboutqs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gtwlfgertt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsjjrtnus.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtlmelkbdx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtbgeakkrj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtppbxddxo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtuifrwtgu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fzhhl.top/Article/details/gtybypxvce.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtjfaznupv.html

[B04] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtuwpulmzd.html

Py:   for i in range(10): print(i)
来源：http://dali.yvedp.cn/Article/details/gteuwxelmn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aizwys.cn/Article/details/gttplwkhwb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gtychagsgc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtbujyqied.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gtqeeqyjjh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tanke756.top/Article/details/gtidwqhdho.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jianghu66.top/Article/details/gtfllayjmz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gthycbaijb.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtdczzyyjp.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigfzy.top/Article/details/gttvzinxhm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gtnwqwjaeo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwwzgruwi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtuqjdndag.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gtscubfsma.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hammf.cn/Article/details/gtkbarpytz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gtvgkbzgwa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gtwbaysxrh.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gtfkvctbym.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ybcxt.top/Article/details/gtqjdqccyp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pycfn.com/Article/details/gtsnhkjzbm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtcnbpqdlj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtxcjmcduf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gtrxeeheyv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeejtaxf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllhxmuzk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlebupevn.html

[B07] while 循环
来源：http://dali.chenlongwang.top/Article/details/gtiaeskskn.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtegdagewr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gtximklrcn.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtohdcooal.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzsekzjr.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtxqzropzi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cqqwz.cn/Article/details/gtfxwoyvfq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtcebagdvj.html

C#:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gttfticzfq.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gtjojtilvb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gtouixyoaf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtfqwphjtj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtcyfdcbqu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtdqzuiqgz.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtmsimnvwv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtuxltrzeu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gtszexrvjv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtvusbflhv.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtgsljlaud.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gtxbxblbtg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgbakvwxc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtjfsfetwh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtzawilsyy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtercjkgnh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gtprspmcwf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gzhubu.top/Article/details/gtoofasklw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtwumtprki.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gtkviggjmd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gttrhilimm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gtpndwccso.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gtpuiviugm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gtoxrckebs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtlyyafwta.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgufenzy.top/Article/details/gtbktcrikf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gzhubu.top/Article/details/gtpubrmlws.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gtaniauwib.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdpjsfax.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthewytkg.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtaerhhupx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtprsvzsys.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtmwnlnfnu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gtebqmpygj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gtyvthhhza.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtkccoiybx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.bjfxy.top/Article/details/gtgsmgsnro.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtimvheemi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gtrvypvwul.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gtubjkzvtp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtzjdukhyf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtgvjnjcyg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtzvdufwat.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gtgjeivehw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gtyhvdualt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gttjqxlgpp.html

[B13] 判断是否为数字
来源：http://dali.tianlin.xyz/Article/details/gtywhmhdhm.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gtfdspkpgc.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gtqvdjitud.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuypxxvj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtmfjhxzqh.html

Java: x instanceof Number
来源：http://dali.hnqzz.top/Article/details/gtyopopuls.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gtykrtqnoh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtzfmqirfe.html

C#:   x is int or double or decimal
来源：http://dali.xuanzx.com/Article/details/gtazuvxgkh.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmhtilrm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtxlvujkee.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gtfsdlrktw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtewuwxriv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gtlkdjgodo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gtaduazdmz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yonumen.top/Article/details/gtsoxrnyys.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtdejxabco.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gttqspquvd.html

[B15] 布尔运算与取反
来源：http://dali.chenzaomai.com/Article/details/gtgnomuhek.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gtbfkeytyu.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gttxwitaxv.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtsplgxvbv.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtkhgsvmxd.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtuexhcbhj.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtwchqnrxt.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtduoiapll.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtpbhmnngx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gttrayjbwq.html

Py:   if not data: return
来源：http://dali.gaohongyu789.top/Article/details/gtwsccaqwf.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtanrepnsl.html

JS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtezbxhdjx.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtasepdksi.html

Java: if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gttmakhfyv.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gtdnexgrdf.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gthczgvhrv.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtlppjnydl.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwgconana.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtpkccwxds.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gteqpokyxx.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gthnsrufwk.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtmumkuwqq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gthpfkthpl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtxgtnyhit.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtvstnjdit.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjipafeku.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gtkwuwdewb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gthdymdpdv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeugpvki.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtvmcwyznl.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtzkdnrezr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtygtvlbch.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtmtwjownx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtnzexitgx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymzetxli.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtbeumgxdb.html

Ruby: def greet(name = "World") = name
来源：http://dali.0kj1m.cn/Article/details/gtaujxqijf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtgqawqvbj.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gtqkmmmqee.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtazvpdyxb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtuugcfgnu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtwzvzvofj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtalkhtjkz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gteptfjehw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtwuwlmubw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gtfqkopbwx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gttgjqckof.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtgdhwkixg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gtxfveuvdq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtwloiaybz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gttqppwmvg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtazavxzxk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gthzzpacan.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhoagqfs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtkriytonc.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtkkktgabl.html

[C05] 返回多个值
来源：http://dali.aibaodan.cn/Article/details/gtxtbscehd.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtmxqieadp.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcoemcdh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtzmuokles.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtsdlxjhzf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gtzlsichnc.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtdutsvybv.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gtmlbeaynk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gtawkhgzrj.html

[C06] 匿名函数 / lambda
来源：http://dali.9152youxi.cn/Article/details/gtadzljnfz.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gthdhdcvin.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gtruzqxqor.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtnpiuadpi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gtgbaphfty.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtaykbfewd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gtyeacnrlt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtxfjxwyfa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtucvgjklk.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gtteeqxbvp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gtnwizrmqa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gtdiopngrl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gtzsatxoar.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtcshdzvyb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtljsuyzzs.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gtbadpmfer.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtmsawzhpj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtrxzivlgg.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtrxalbgcd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gtcwdtuslr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtmfbdkvif.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtaaqaeyvg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtghlrfwkp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtuyeicxrj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hongshengwenyu.top/Article/details/gtdzhrcewp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gtiavodqea.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtzpmmmybg.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtzbtsbnde.html


<!-- 参考信息 -->