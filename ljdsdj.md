代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aizwys.cn/Article/details/gtiqwhtyyq.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258888.top/Article/details/gtmxucxxvi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxinkj.top/Article/details/gtlhgjzryc.html

Ruby: "A".ord; 65.chr
来源：http://dali.c1oappe.top/Article/details/gtraedygik.html

C#:   (int)'A'; (char)65
来源：http://dali.zhijiandao.cn/Article/details/gttsejkvze.html

[A19] 交换两个变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiegqxhuu.html

Py:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gtpcicyqfj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.daxiang520.top/Article/details/gtetddwyzl.html

JS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtneerwwfu.html

TS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gtjdbemnhw.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj20258.top/Article/details/gtgacmiapq.html

Go:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtzohuujpu.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtzmajrsty.html

C#:   (a, b) = (b, a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbrxpfre.html

[A20] 读取标准输入
来源：http://dali.zhiwuduotai.top/Article/details/gtmfmpahze.html

Py:   name = input("请输入：")
来源：http://dali.gzhubu.top/Article/details/gtolszvikb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.c1oappe.top/Article/details/gtuqnyscki.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnxiangtu.top/Article/details/gtkwuhxdml.html

TS:   // Node.js：readline 模块
来源：http://dali.xziqi.cn/Article/details/gthtgoaelu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gogol.net.cn/Article/details/gtqppoxsdf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ppjwa.cn/Article/details/gtuneargzg.html

Ruby: gets.chomp
来源：http://dali.jiagoushi.top/Article/details/gttxjyirps.html

C#:   Console.ReadLine();
来源：http://dali.aizwys.cn/Article/details/gtbaugbysk.html

[A21] 保留指定小数位输出
来源：http://dali.jiagoushi.top/Article/details/gtlbwehrty.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokatzhmm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtfxameamb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtrgoqkkkm.html

TS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtvghrsxht.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gttashslxo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtatlbsteu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtbfswpiyy.html

C#:   3.14159.ToString("F2")
来源：http://dali.snrcjt.cn/Article/details/gtuucxnyzv.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gtwdkgyxck.html

Py:   len(s)
来源：http://dali.sxryk.cn/Article/details/gtiwwslznx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.quarkkingdee.top/Article/details/gtgacbocvc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenzaomai.com/Article/details/gtrjzbovpt.html

TS:   s.length
来源：http://dali.zhongyouzk.top/Article/details/gtaquoxpgw.html

Java: s.length()
来源：http://dali.jianghu66.top/Article/details/gtjtdomhxq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquhoihca.html

Ruby: s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtqohboebx.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtstujqjdg.html

[A23] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhxkqsbo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenzaomai.com/Article/details/gtwrshjons.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guannengcc.top/Article/details/gteiohiytv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtkaatxtfb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtxngdwelj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtucnnwwvk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jlsjyb.cn/Article/details/gtwipvbjsa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ivvv.top/Article/details/gtszwlaxvd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.feifeiyinyue.top/Article/details/gtashlfsrx.html

[A24] 去除首尾空白
来源：http://dali.snrcjt.cn/Article/details/gtmnormmdl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yonumen.top/Article/details/gtwjnwqyuh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.iojbl.cn/Article/details/gtaszlwyhj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gtccuaqvbs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtjfzprwbn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.kuanghao11.cn/Article/details/gtqmfadwzp.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgufenzy.top/Article/details/gtujnodkuo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenjidiqi.icu/Article/details/gtmkofamfz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtllcrobsv.html

[A25] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtwddbmlhj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gotoacloud.top/Article/details/gtjlxcqnqu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnxiangtu.top/Article/details/gtiroizwmf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtvvhjfjkf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjemwrtyu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tanke756.top/Article/details/gtgqycjlbn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtrhtppirm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gtjueidvnk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.snrcjt.cn/Article/details/gtkfalimtn.html

[A26] 类型转换总览
来源：http://dali.cheryme.top/Article/details/gtowtiabmx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtesgevukj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuanzhike.top/Article/details/gtbhzcnoye.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenzaomai.com/Article/details/gtxyoydqsd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dianchejie.cn/Article/details/gtqmzlnlvb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtozyuqyun.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuanzhike.top/Article/details/gtcnybhfcd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gaohongyu789.top/Article/details/gtnvuzjmpp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqggtpme.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttwowqhdw.html

B. 流程控制
来源：http://dali.ehwqpu.com/Article/details/gtrhcdayjq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgfmhxtmk.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gtzjbwaesa.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuanzx.com/Article/details/gtuvlallnz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.c1oappe.top/Article/details/gtetkansbd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtwkotfwla.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtxrefjjoy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtbbkbbuhi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gtxsypgfap.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sysykeji.top/Article/details/gtdqonhtyc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gtxixioixg.html

[B02] 多分支 else if / elif
来源：http://dali.hongshengwenyu.top/Article/details/gtjwnnklcb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtapihmkte.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gttbynjloo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtrtyogxbl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtzqhsvusz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtfnrsdqjd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ivvv.top/Article/details/gtkpfwivjb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.feifeiyinyue.top/Article/details/gttstlbeqt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtmzuwjcqy.html

[B03] switch / match / case
来源：http://dali.sweek.top/Article/details/gtwoqgdrse.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gthnamxadv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtnoyfbkij.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtorexjbaf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gttoqztplo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtajdjsgol.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shuidangran.top/Article/details/gtnuioqxqf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gthqelvlqy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtwfpbvdqg.html

[B04] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtocreldeo.html

Py:   for i in range(10): print(i)
来源：http://dali.xziqi.cn/Article/details/gtrwojolnw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hywenlv.cn/Article/details/gtedllludo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqgvwljs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtzvjwfphh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cashguo.top/Article/details/gtgqfvejko.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dashuyun.cn/Article/details/gtlhnmbeou.html

Ruby: 10.times { |i| puts i }
来源：http://dali.quarkkingdee.top/Article/details/gtcjjocsyo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtbkficesx.html

[B05] 遍历数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtvldhjiqd.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gtlmtfzgax.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtfjpxmzkc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gtxtchczdn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtcrvngidd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuxming.cn/Article/details/gtiqsckiuy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tanke756.top/Article/details/gttxqrucbz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hammf.cn/Article/details/gtwdedtptx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmntcuypm.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gtdivyyjrp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.bjfxy.top/Article/details/gtsbkukgok.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhixingplan.top/Article/details/gthttmgbyj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtfomdhdvw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gtmifowkdk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fengsongda.top/Article/details/gtbobblpik.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gtkshhnsay.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jiagoushi.top/Article/details/gtppjyqdbj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gotoacloud.top/Article/details/gtecgrrwzi.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gtvjhgabde.html

Py:   while i < 10: i += 1
来源：http://dali.zhongyouzk.top/Article/details/gtkkcedbyj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gtraixmylu.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtcawkbvqz.html

TS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtkqyuibmu.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtorulmvhw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gtszujionx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.quarkkingdee.top/Article/details/gtkikmexgt.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtmcwadcoi.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gtfclxfzas.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenjidiqi.icu/Article/details/gtfvetjaow.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtajuzogof.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtdvuuiswb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtovblnnpd.html

Java: do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtaehhkhcv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtaxfaahyo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gtkfitqxwq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtxwszfitr.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtmxanwgxn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gtwdonmrnv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtvlxnqstq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtwisrcujx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtqwlcgbbz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtdajxtskd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtdqvpmqbk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daria6918.cn/Article/details/gtfphpblqm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtudgjxecb.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gthrmyewfj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gtoujmrjwq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gtdhcwlxfo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtbomzzjyt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gttogcuteu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gtastftnrv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtkppkjsrb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gtsleuqqcd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gttiljeizc.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gtqtljmkzf.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gtmaoorioz.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtyoelmrba.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gtanxdbtdt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtojzehssm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gtrsleoedt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gtqqkxrchw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gtddnrjriv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hysaishi.cn/Article/details/gtqqqppbrf.html

[B12] 跳出多层循环
来源：http://dali.yj20258.top/Article/details/gtkxlxnbjq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gtfnrsaonv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.quarkkingdee.top/Article/details/gtvbdcrjqt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtqyhcersr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtsaniyvdv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gteknfrvqi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yanxiufei.cn/Article/details/gtvcppiphj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gtiyxzvtkz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gtmxhoiezt.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gtzbeqccgk.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gtqthkworh.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gtktnxxaev.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtsygocdhw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtjllfvols.html

Java: x instanceof Number
来源：http://dali.quarkkingdee.top/Article/details/gtymakrvbu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gtyqrfqzcm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gtkqqcueye.html

C#:   x is int or double or decimal
来源：http://dali.yueranfly.top/Article/details/gtjuhrbdhw.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gtndlcdorm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gtznhtvvfx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gtjuwzubmm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbklbxbzl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtcspqpain.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjibegtyf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gtaqdwlags.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgnkbqbah.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gttvmorzem.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gtbtytiake.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gtxytatccy.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqchbvyd.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvgusdjk.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtqlnqbohi.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtlmhgyfev.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtsygowsry.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtifjsshuq.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtjccxnaka.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtubzskcyv.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtistejdkr.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gtcfvczcmr.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtylofutmh.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtntgrttwm.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gtrukrhfrk.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtehvrydwi.html

Ruby: return if data.nil?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqmrtnrk.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtkcwyoued.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgcxxttru.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtdicoofig.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrhzhiloj.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gthxsueuwg.html

Py:   def add(a, b): return a + b
来源：http://dali.yvedp.cn/Article/details/gtkdppoesa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtsmfpxjku.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gthgjoytog.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtdpldvfrn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtaplmjtkj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gttlkxblzf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmbuqomx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtexvcgjbc.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gtevxqsbke.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtiyztdkfw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gthefmhdkk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtfgullwat.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtuepntcle.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtrxhgqgwx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gtjtxufymb.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtppcnoocg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gtgwhjxknj.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtnkwbqsbu.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtoaikzcff.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gtaspjblta.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtlufyient.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtfafyjlgo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gttbqisder.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtjzwsygdt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gtpvnaackv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gttzwvaxpk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gtqpupynaj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gttrmdhjbt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdtrmglc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gttrifegye.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtyofkyixd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtfgjksuaz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtaexygtuc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtcbaarcfw.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtrdhgewyb.html

[C05] 返回多个值
来源：http://dali.hnqzz.top/Article/details/gtxkopywht.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtqjdjrgiw.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gtirjieeks.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gthwqcbifp.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtouqdkfxj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gtwkbqqwre.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtirudklfw.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gteljegbru.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gtcdwvibpx.html

[C06] 匿名函数 / lambda
来源：http://dali.yuxming.cn/Article/details/gtpxzugwbb.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtyppyaxxi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtmwiydzjj.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtxzjsrkyo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gtvozomyjg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gthzmzwfwy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gtkltzcloc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.smart0.xyz/Article/details/gtmwvhgymd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtwjmwisfn.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztbsfxkg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gtwzxnurch.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtcjotsxdy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtlgurhloj.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gthdgvngaa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gtclbuqbej.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gtoenghvjv.html

Ruby: arr.map(&:upcase)
来源：http://dali.yanxiufei.cn/Article/details/gtraqdjqnd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gtjznhejkw.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtplyedoot.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtapappppm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzevhiof.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtssznkvyh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gttzdshiiz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtwamrooun.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gtxqgvbbcm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtnwsxeoeq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtgmimefvc.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtwympyqgz.html


<!-- 参考信息 -->