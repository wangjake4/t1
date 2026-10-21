代发 wailian999

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtxfxybocq.html

C#:   (a, b) = (b, a);
来源：http://dali.nwbrower.top/Article/details/gtaakxwdva.html

[A20] 读取标准输入
来源：http://dali.yuanzhike.top/Article/details/gtrnumvxib.html

Py:   name = input("请输入：")
来源：http://dali.yanxiufei.cn/Article/details/gtydnepvat.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gaohongyu789.top/Article/details/gtpztuchwr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.feifeiyinyue.top/Article/details/gtcdbdzzui.html

TS:   // Node.js：readline 模块
来源：http://dali.yongpay.top/Article/details/gthlnvkpvt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangshuangyany.cn/Article/details/gtkyvaumar.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnxiangtu.top/Article/details/gtbayzblaq.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtcjjsuopa.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gtvkztthab.html

[A21] 保留指定小数位输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanjbnwcd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpigieplk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtxguogryn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtqzqafexh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtndemulrn.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtjmhrfeyw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtgdyprvub.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtjsgiitwl.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gtfrpolvuz.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtfbvseadf.html

Py:   len(s)
来源：http://dali.ehwqpu.com/Article/details/gtguylzqht.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sxryk.cn/Article/details/gteghlpjeb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sxryk.cn/Article/details/gtzassesfz.html

TS:   s.length
来源：http://dali.cdnleiting.top/Article/details/gtqnanfcxc.html

Java: s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtlspscigf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfvvcpcr.html

Ruby: s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtceqobzqr.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gttenjfyix.html

[A23] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtlojbtggv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.316326.xyz/Article/details/gtqlbzikqu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jlsjyb.cn/Article/details/gtnxzvzhwi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtdeeiuwlu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gtzmmpbrcu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtggjkxsat.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fengsongda.top/Article/details/gtwhzifkre.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxupvkayt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tanke756.top/Article/details/gtfznpgika.html

[A24] 去除首尾空白
来源：http://dali.shuidangran.top/Article/details/gtcayflujd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ehwqpu.com/Article/details/gteikeatnd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jyoumei.cn/Article/details/gtheyuyiot.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gteyhqbpmg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gtlotzcczp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gtrfyhjgnq.html

Go:   strings.TrimSpace(s)
来源：http://dali.gzhubu.top/Article/details/gtumbkuxzc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhiwuduotai.top/Article/details/gtytyrdwfk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtciqcqbos.html

[A25] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtqlerhczq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hnqzz.top/Article/details/gtqnzpkroh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fengsongda.top/Article/details/gtwqffthah.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtsxmltaxm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gtdtehsazu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cqqwz.cn/Article/details/gtnyzarnev.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtdfiyrotj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.316326.xyz/Article/details/gtbkrgrbbg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtkjturnag.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlucicox.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttblvgtfo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.vqdsnc.cn/Article/details/gtnhtzumyp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aibaodan.cn/Article/details/gtzekevexw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yonumen.top/Article/details/gtvrtdwrqd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtfhkjcycp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.feifeiyinyue.top/Article/details/gttalokcwp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.iojbl.cn/Article/details/gtkbcqbcvk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtttjggjcw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtutkuthsv.html

B. 流程控制
来源：http://dali.andypj.xyz/Article/details/gtrqlsdwhx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gthleigtub.html

[B01] 条件判断 if / else
来源：http://dali.tian-w.cn/Article/details/gtehrwexfe.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yueranfly.top/Article/details/gtdgmokebk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gthtgcfjdc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gthhxmxfhl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtjwoqvizz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtfztsncac.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gtdadqxmvq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yangfankeji.com/Article/details/gtqpaiyzfy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtvbfaderx.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gtmsedagos.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxinkj.top/Article/details/gtqwsoxzip.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gtcuceusmf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtfivmnzen.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtvduznbae.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtgyjdztyc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gthyyljofp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yangfankeji.com/Article/details/gtusiwhclb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtncgvqbvz.html

[B03] switch / match / case
来源：http://dali.cashguo.top/Article/details/gtmypsqpzh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtgltqjntc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtisomzsgm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gthwbjfnjv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtnycpgwoy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtoveplxlz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gteezhqrrg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gtlmeccyqq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtgrulftdn.html

[B04] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtogdrqqwj.html

Py:   for i in range(10): print(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvvyfclb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gtrsiwzqmv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenlongwang.top/Article/details/gtduuejhvw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtquhsabnr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtxhgijnny.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.snrcjt.cn/Article/details/gtjcjhosxb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zycfv.cn/Article/details/gtatagfvgq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gtotqswjwv.html

[B05] 遍历数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtakksammc.html

Py:   for item in arr: print(item)
来源：http://dali.9152youxi.cn/Article/details/gtnxdoulxq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gtnelbezfa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gtfzrqhrpm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtdmkaajqd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtgbhedqrf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gtrqwbicmf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hysaishi.cn/Article/details/gtohpgwerf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtacnxmiyu.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtfkuhhbas.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gaohongyu789.top/Article/details/gtyyoqwqob.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gtclhvpfyu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtmqzkwqda.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtmwkzkhjc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258888.top/Article/details/gtjjionszc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gtkgczjbxk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shzxlz.cn/Article/details/gtbbmirkmh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.mhx1999.top/Article/details/gtyugogldf.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gtkvmndqba.html

Py:   while i < 10: i += 1
来源：http://dali.guowangkeji.top/Article/details/gtviqpwdrw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yueranfly.top/Article/details/gtsowgwltk.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtlijfjdde.html

TS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtvsvqamln.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtuidoqcye.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gtcgcenbeq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pycfn.com/Article/details/gtrkvbvuys.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtvmlghhnq.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigfzy.top/Article/details/gtqrrbhuzn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gtiqwdgqmo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fengsongda.top/Article/details/gttqctbqrc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtiaxxcekm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtqgclwdub.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtljderikx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtmavrkifb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtwikbiycu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gthhutmomg.html

[B09] break 与 continue
来源：http://dali.jqgfzy.top/Article/details/gtckwcbihp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gtecdkrrat.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtjwfhhmkh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtsnxhpglf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtyanqjagh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlewyjcsd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xylfe.cn/Article/details/gteanpzktz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtxlvztcbg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtwjadiiuu.html

[B10] 遍历同时拿索引
来源：http://dali.0kj1m.cn/Article/details/gtjgffvixs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gthgpkfdwj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrcspokz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtppcgjffj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtvssvtuqf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gtedvommie.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ivvv.top/Article/details/gttlmzyfld.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtnlstxbij.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gtwdenggii.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxuanxn.top/Article/details/gtvbjqqpid.html

Py:   list(range(0, 10, 2))
来源：http://dali.cheryme.top/Article/details/gtyqzhoqkq.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gtzyxwyyet.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtljgqdcoz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtoytbprzd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hywenlv.cn/Article/details/gtnpknbzkx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtrrkuyjcp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtyquvtcdx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbfgezmx.html

[B12] 跳出多层循环
来源：http://dali.nanxuanxn.top/Article/details/gtqudubdgo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cucudq.cn/Article/details/gtcwmepbdw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtryrliklz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtroptzvef.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtybkhsoay.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtvheqsofv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziovwqme.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtnugzatjt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtbpwhozdq.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtzamhqlxm.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gtggoavdko.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gtlrdvtotb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwrsdwbcy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtxxwzifqn.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtbjokbcjl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrpqnuqn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtkqrkyigj.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtlgsdqdjq.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtsxkzyyfk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gtwxaapmvi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtubejanco.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtknzhwbya.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtptawazei.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfkppmbn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gtbwphglxx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gtvjphuokc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtieiqchvk.html

[B15] 布尔运算与取反
来源：http://dali.jlsjyb.cn/Article/details/gtmslpofro.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyqvrzml.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtoigmyzit.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtjjzsnqfb.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtatpsdkyz.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkivaxun.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtsrehjmdt.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtxqfofong.html

C#:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtxuteapec.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtkewzrumt.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gtzjuanyav.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtcihaqqqa.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtdcyunukn.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtzkbyisci.html

Java: if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtbkovgstd.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtaizyyzqz.html

Ruby: return if data.nil?
来源：http://dali.svipenyu.cn/Article/details/gtohgfvppl.html

C#:   if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtqillxktl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtljylfahb.html

C. 函数与作用域
来源：http://dali.redwolf501.top/Article/details/gtummstxxm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtstqcupzk.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtctrrrcrb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gteejnnjyq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtwlrkkzmg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtzfalpiql.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtoznrcnwn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtqhhauamv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gtlbjebhbf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gtvhkpqfol.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtlecglrqz.html

[C02] 默认参数
来源：http://dali.xinyue.icu/Article/details/gtsosmpyeb.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gtatpdwmay.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gtikrrgrop.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gttsbrsjtc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtvgsqdvxi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtkmzlpdjc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtqgwxotoq.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gteovntmzb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gthuerdqjb.html

[C03] 可变参数
来源：http://dali.yj20258888.top/Article/details/gtwimlsfka.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtthtqpwmh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtjxmvybdm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtvpvvzway.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gttltcyuso.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yonumen.top/Article/details/gtkmsvuqzh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtfslpwnuc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtnrcysfdd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtevgmgrlk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gthneoeipe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.kuanghao11.cn/Article/details/gtabrpzzne.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gtbzqbtkzr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gthafgevpx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtyapycneq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gtwesmtiby.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gtknqgoypc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtyciaxhdt.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtludewezm.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gtfqnhvkvq.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtswtngjas.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gtvrukqiiy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtnijhxarl.html

TS:   return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwimgxgqy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gtwoycdkah.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gtggbycuji.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtiqngjvct.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gtidlhgtod.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtpogpkyme.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gtzomdwxzh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtavmpcsvz.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtjfylycag.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtskygoggd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtlgnktcsf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gthzkmdiqk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosacvewu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtsriceiol.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtipgyxaql.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtazefsxmu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvrhbjxz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hongshengwenyu.top/Article/details/gtumdbdgho.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gtzedmqpdm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gtqqiezdzz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtsovdzkrb.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtamvyrkii.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sweek.top/Article/details/gtljlgehbz.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtjnknxpkb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gtezzxxzwr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gtfnnqzftd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtitztemky.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtuarkhvqq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gteiggscyk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtmitpsnbi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gtybscnfaf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbedsagmm.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gthjvjrvyi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtliylvrsy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtjzesmder.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gthgfplhwr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtxmiprbbq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtrtbxyhct.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtxharuukv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtwrmubvki.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtzupzriue.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gthjzwckcc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shuidangran.top/Article/details/gtvoivvogd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cdnleiting.top/Article/details/gtpywpqlez.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gtdhjaljlp.html


<!-- 参考信息 -->