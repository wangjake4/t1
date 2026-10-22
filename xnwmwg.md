代发 wailian999

C#:   (int)'A'; (char)65
来源：http://dali.haohaochexian.top/Article/details/gtvvctmgun.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gtjwumntle.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtjhnlrlaf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xylfe.cn/Article/details/gtkavjhqbq.html

JS:   [a, b] = [b, a];
来源：http://dali.chenzaomai.com/Article/details/gtasjwsmoa.html

TS:   [a, b] = [b, a];
来源：http://dali.dashuyun.cn/Article/details/gtmkylodjr.html

Java: int t = a; a = b; b = t;
来源：http://dali.daria6918.cn/Article/details/gtlhhgjjrw.html

Go:   a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gtaonaodax.html

Ruby: a, b = b, a
来源：http://dali.xuanzx.com/Article/details/gtzfzmxcwt.html

C#:   (a, b) = (b, a);
来源：http://dali.jyoumei.cn/Article/details/gtxajbglmv.html

[A20] 读取标准输入
来源：http://dali.zycfv.cn/Article/details/gtkkilcbfc.html

Py:   name = input("请输入：")
来源：http://dali.yj20258.top/Article/details/gtkvhtvqyj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.feifeiyinyue.top/Article/details/gtzthrmctc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shzxlz.cn/Article/details/gtamdfqbex.html

TS:   // Node.js：readline 模块
来源：http://dali.cqqwz.cn/Article/details/gtanqfedga.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxkbiefj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aizwys.cn/Article/details/gtwxopygzt.html

Ruby: gets.chomp
来源：http://dali.xuanzx.com/Article/details/gtqqkpibkz.html

C#:   Console.ReadLine();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyffydpw.html

[A21] 保留指定小数位输出
来源：http://dali.andypj.xyz/Article/details/gtuwxnylwa.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gttmfgfnis.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtnhswgzoa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtyiwsucug.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtatiojjni.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtolbmlfln.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtesjxvdzo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtvnpszlpl.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gtfogjlntt.html

[A22] 获取字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtbckbnptm.html

Py:   len(s)
来源：http://dali.xylfe.cn/Article/details/gtuuaauknl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ppjwa.cn/Article/details/gttnyjytde.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ivvv.top/Article/details/gtnkpdejqc.html

TS:   s.length
来源：http://dali.jyoumei.cn/Article/details/gtxnetcnxa.html

Java: s.length()
来源：http://dali.guowangkeji.top/Article/details/gturksnzuc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.0kj1m.cn/Article/details/gtteoqtwpt.html

Ruby: s.length
来源：http://dali.yueranfly.top/Article/details/gtzebquhmr.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtfkughldp.html

[A23] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtkmdjctgr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.daxiang520.top/Article/details/gtaqfgikmw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fzhhl.top/Article/details/gtbezvhkgv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gtzpmzyina.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtyfrmdagy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtdpqctpdp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cashguo.top/Article/details/gtlovhehuc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtizeozlsb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenzaomai.com/Article/details/gtjmzxvwgi.html

[A24] 去除首尾空白
来源：http://dali.jyoumei.cn/Article/details/gtdrwbioip.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuetiantiany.cn/Article/details/gtabixbxts.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gtxpfjegxl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtgnycbdnh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtkejpldjv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnqzz.top/Article/details/gtzybyuwrl.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtlaablpij.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gtxwtojgkd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tanke756.top/Article/details/gttvmppsqn.html

[A25] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtclznijum.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlonxsroc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zycfv.cn/Article/details/gtemarlvjp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtlrjriqha.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtjbmnqshr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenlongwang.top/Article/details/gtgknafzir.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtwohybcpx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dashuyun.cn/Article/details/gtxawhcqtc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtedxlqzpe.html

[A26] 类型转换总览
来源：http://dali.hnqzz.top/Article/details/gtmvyowfaz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqspbwrbu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fzhhl.top/Article/details/gthizrrdiw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.mhx1999.top/Article/details/gtafohhoyr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.meibo888.top/Article/details/gtltuutmpd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtdfoasohm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hfpthk.cn/Article/details/gtcryjitjz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxinkj.top/Article/details/gtlywgzvuu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jqgufenzy.top/Article/details/gtclgcuflm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtptjmdrfz.html

B. 流程控制
来源：http://dali.aibaodan.cn/Article/details/gttpynrbch.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtslpbqkwf.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzkrhbqv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shuidangran.top/Article/details/gtxmacbhlj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fengsongda.top/Article/details/gtvtewnkev.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gthzcgldlc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtwpbaqzvj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gtmdosveud.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gtkgnsmimf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jiagoushi.top/Article/details/gtmkyghdvh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtvoswjaew.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaahpskjp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.meibo888.top/Article/details/gtqnzpyxwq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxawwfrhb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtzltydicn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtnibtgjnp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gthuwnrufu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrddweeb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ehwqpu.com/Article/details/gthkmrsnuq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtcsvvaejk.html

[B03] switch / match / case
来源：http://dali.sweek.top/Article/details/gtyrmppmtb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhongyouzk.top/Article/details/gtalpslwyf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtvedlszxx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtitjuwrtu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtooocxomv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtgfwmdekr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtcjttfseu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gtwbptnuec.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzifxvybm.html

[B04] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtjcuioszg.html

Py:   for i in range(10): print(i)
来源：http://dali.yuxming.cn/Article/details/gtpmdrfhfm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnwtvjvsk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtrqlsvfxx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtrisugqwo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aizwys.cn/Article/details/gtixmcztkf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zycfv.cn/Article/details/gtrebnivex.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuanzx.com/Article/details/gtiqgxcgcx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gtcfhkmxus.html

[B05] 遍历数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtaubvepzi.html

Py:   for item in arr: print(item)
来源：http://dali.hfpthk.cn/Article/details/gtqhzuzggj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtnligbvtb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtaklepvxd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gtedxpsokq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtibrlyrzi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sweek.top/Article/details/gtrufyuikq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aibaodan.cn/Article/details/gtfdrryrtv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ivvv.top/Article/details/gtgctgbfsi.html

[B06] 遍历字典 / 对象
来源：http://dali.guannengcc.top/Article/details/gtohdcjpfh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaggnone.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cheryme.top/Article/details/gtsfcaqwwu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gtiorweimq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtfqfjmund.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gteijfdadj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ehwqpu.com/Article/details/gtsrqxrhsl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxinkj.top/Article/details/gtblunidel.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gtulruyfsb.html

[B07] while 循环
来源：http://dali.redwolf501.top/Article/details/gtfdoesdza.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gtxjcrhbug.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.meibo888.top/Article/details/gttxtmpimb.html

JS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtaohvmudf.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gthanybxwu.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtjfapzbni.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gthsaoqlwv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ppjwa.cn/Article/details/gtdmvngcqt.html

C#:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtastmgixs.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gtficfnrix.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gtncddcywa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gtjolmegzx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutfmkbkw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtsxesyuxp.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtlbofskjo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtekodzjel.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtmaqqfudw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtfpufrpfo.html

[B09] break 与 continue
来源：http://dali.haohaochexian.top/Article/details/gtdjnhxuah.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gtagatpsei.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtaidpsaio.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtnexeanek.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gticuikxsa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtpllrzbyp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtwhggbafw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gtuablnmnm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtuydcgcfs.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtoyuyhbhl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangdashe.top/Article/details/gtpuwzvucw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtxuvlfamm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtcnizfuvp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtvscauhqq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cheryme.top/Article/details/gtsjxcnrnn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gtxnhgupdj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gtytgeizsj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpblyyhsv.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtddcesqau.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gtayzwlkqf.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gttcfiiavx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtavtiblja.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtfuwvgojn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gtgoxqcnpa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jianghu66.top/Article/details/gtkhkwbpwy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gtjrehveod.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fzhhl.top/Article/details/gtmnulxngg.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gtvahsdpdc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gthjqyoosi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtksixxanw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtmtngkayu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtgxczkdcy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtqksfbkbk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gtxmrabiho.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gtqslqvpwf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gtsyrtemop.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gtirusvdys.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhongyouzk.top/Article/details/gtnaprnrnl.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtleqealpu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gtwutkfwep.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnekzixd.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtvmaxgqie.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gtalabcclu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dashuyun.cn/Article/details/gtnuruwgob.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtayrjdkam.html

[B14] 判断值是否在集合内
来源：http://dali.cucudq.cn/Article/details/gtuagthqxq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gthcmoahoh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtpkxlwacf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtofcbxshj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtyaoffssk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gttbjqqwhc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cucudq.cn/Article/details/gtoefpmudy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gtuwcblwur.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtwgmwbute.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gtdfytyibt.html

Py:   a and b or not c
来源：http://dali.yangfankeji.com/Article/details/gtwzftsxbn.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gthxaiumdf.html

JS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtuyjboyil.html

TS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtozmawvej.html

Java: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gthyfmzlju.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtgeyuryzi.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtzzalffjq.html

C#:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtvavwrdrs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtfvdgbaaq.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxdzbpsv.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzgjbplhe.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gtrxqtrqqc.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtvbehfcwy.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtxlzasicr.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gtpgmyxwbt.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtobxvpjgk.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gttfzigilz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpplwsvpe.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtvoiqukel.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtffjlrqsc.html

[C01] 定义函数
来源：http://dali.daxiang520.top/Article/details/gtkutuxmym.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gtudzxryvy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtszodbymt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtjgfoakkz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhkyfmye.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtogomguzl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtgbukinxg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gttptvqhca.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtxqzxozzc.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtrtjiwzgx.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtqdyhsrev.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gtjatxbcjz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gttdlwcgkw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtyuwoxbbe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gtcoldbtjl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtxbjxurgr.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtzexuupkj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtgavsmhmk.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtwhoaqemr.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gthfuelihw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtshuylpqn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtmhhuknmp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtsspuombv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gtpjbjuwln.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gtiacnrtdc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtlsoezivw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.316326.xyz/Article/details/gtrtucgnzt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.bjfxy.top/Article/details/gtriaauqrw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gtipnkhfjp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtggpjawgj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtrlqteqij.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnculhog.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtgxoasvhd.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gtofspjqwl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtaxuxfcpb.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtmfaoepwi.html

[C05] 返回多个值
来源：http://dali.hnqzz.top/Article/details/gttwilzgja.html

Py:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtnensexxg.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtejkptrbm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gtrcfdfrjv.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtqzgjusyy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gteleelbqq.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtfilpwsmc.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gtdvlaifyj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtzhcebmoc.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtheourvun.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtgwnwotok.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtxzhrgwft.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtcingwhab.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtnawsylek.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtzkpzogxf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtmzoeeagv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gttdemzmgh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtnnnnckbt.html

[C07] 把函数作为参数传入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkegggwj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtrsxcnjcd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gttglpsowy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtndhcbojy.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gttkptipin.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtxnjobaig.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtcweqzbba.html

Ruby: arr.map(&:upcase)
来源：http://dali.ppjwa.cn/Article/details/gtnlvktibl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gtlqrtslte.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtryrwjebw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gtpwqwezhg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtzyfldkmy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtvblfmggk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtsuwuxkro.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtouvtzugp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtjaofgiru.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gtpmaxydup.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtkshollgu.html

[C09] 递归
来源：http://dali.yvedp.cn/Article/details/gttfzkwzmw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxumrybro.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtffmgulcg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtshcqqxls.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtimidssmh.html


<!-- 参考信息 -->