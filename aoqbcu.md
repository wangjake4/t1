代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yuanzhike.top/Article/details/gtpnurpktt.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gtlnfyygkm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jqgfzy.top/Article/details/gtpgqemwvo.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj20258.top/Article/details/gtrznthbyv.html

C#:   (int)'A'; (char)65
来源：http://dali.shanyushiyangtech.top/Article/details/gtybspunoo.html

[A19] 交换两个变量
来源：http://dali.smart0.xyz/Article/details/gtylivdszs.html

Py:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gtmkjsxsky.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenzaomai.com/Article/details/gtkjsbovpq.html

JS:   [a, b] = [b, a];
来源：http://dali.fzhhl.top/Article/details/gtxsdzmrbr.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmdctjli.html

Java: int t = a; a = b; b = t;
来源：http://dali.xylfe.cn/Article/details/gtnimgdndq.html

Go:   a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtirmurwma.html

Ruby: a, b = b, a
来源：http://dali.yj20258888.top/Article/details/gtlrsjrnrb.html

C#:   (a, b) = (b, a);
来源：http://dali.dianchejie.cn/Article/details/gtipyzevxw.html

[A20] 读取标准输入
来源：http://dali.smart0.xyz/Article/details/gtwotukjdm.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gtvvoljwgq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xinyue.icu/Article/details/gtxklkenkb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hfpthk.cn/Article/details/gtzfqupdja.html

TS:   // Node.js：readline 模块
来源：http://dali.quarkkingdee.top/Article/details/gtglkoyyla.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenjidiqi.icu/Article/details/gtepplyazf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cheryme.top/Article/details/gtzixaajrs.html

Ruby: gets.chomp
来源：http://dali.yuanzhike.top/Article/details/gtrrxlpwqi.html

C#:   Console.ReadLine();
来源：http://dali.yj20258888.top/Article/details/gtkvfnddov.html

[A21] 保留指定小数位输出
来源：http://dali.yuanzhike.top/Article/details/gttcqqougw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdinkazyh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gtxkakfdop.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtdkmfhqwy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtvihekaxk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtphdggbux.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtnwiqvcay.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtzjmozwag.html

C#:   3.14159.ToString("F2")
来源：http://dali.sweek.top/Article/details/gthmciqpxc.html

[A22] 获取字符串长度
来源：http://dali.fzhhl.top/Article/details/gtxuacespe.html

Py:   len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtvbsxdgrv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shzxlz.cn/Article/details/gtxsrbacxj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.0kj1m.cn/Article/details/gtrbtrcnvl.html

TS:   s.length
来源：http://dali.gzhubu.top/Article/details/gtdfomwqdk.html

Java: s.length()
来源：http://dali.shuidangran.top/Article/details/gtegxkixlg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtbshoyfib.html

Ruby: s.length
来源：http://dali.jlsjyb.cn/Article/details/gtonmlrmta.html

C#:   s.Length
来源：http://dali.aibaodan.cn/Article/details/gtuyeylftv.html

[A23] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtbygmlnes.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqkmrscs.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.wangdashe.top/Article/details/gtjbmdnnwo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gttnuzzbvs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtcmaoexgf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gtmicjbqis.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.haohaochexian.top/Article/details/gtetjwffgf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xylfe.cn/Article/details/gtesbmcbsd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gogol.net.cn/Article/details/gtbikxkzob.html

[A24] 去除首尾空白
来源：http://dali.hfpthk.cn/Article/details/gtxaiqdanb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.redwolf501.top/Article/details/gtsfnbefos.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sysykeji.top/Article/details/gtxzoqqgfj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtpyonjwgz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gtjebqukeo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gtakzpdqdc.html

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gtppxpzawe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gthssdinyt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ybcxt.top/Article/details/gtjqacwykv.html

[A25] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtozanfver.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daxiang520.top/Article/details/gthcfozhuq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jlsjyb.cn/Article/details/gtxxpldhnr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangdashe.top/Article/details/gtkkgvombl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtfaunettp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuxming.cn/Article/details/gtmpfgcgok.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gtjonszpzi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.haohaochexian.top/Article/details/gtxlxuqkpx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gteleaptzw.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gtltgreqrp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihtofppr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenzaomai.com/Article/details/gtaplqnfjj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebdopciu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hammf.cn/Article/details/gtaokobsnb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gtlpqzkbuy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gtbzlbhufb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwjhwdkk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gtoklxqbmx.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwqqsagnl.html

B. 流程控制
来源：http://dali.yonumen.top/Article/details/gtbadncdqq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwvrevuql.html

[B01] 条件判断 if / else
来源：http://dali.zhixingplan.top/Article/details/gtknjijlyd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yangfankeji.com/Article/details/gthjrpesci.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtxrwqzjnq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gthqmfcjmw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtfztnbeue.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcyoouwh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gtlutxuusk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dashuyun.cn/Article/details/gtwqzildaa.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gthgaqqcbu.html

[B02] 多分支 else if / elif
来源：http://dali.daxiang520.top/Article/details/gtkxmklotl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gtnzhburoa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nanxinkj.top/Article/details/gtjeqwupti.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gteuhwwqpd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtclvjzvav.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtmnkfzogl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigufen.top/Article/details/gtudewuwpv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hammf.cn/Article/details/gtiriukier.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtybwcmegb.html

[B03] switch / match / case
来源：http://dali.havefunace.top/Article/details/gtdywcpcal.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yueranfly.top/Article/details/gtheulpxmr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtkxsdhaix.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtppyowh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtpexwrird.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtcotpmtbt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gtksdagblp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dashuyun.cn/Article/details/gtbrfmwcec.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtnffzjgjv.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtrskizygm.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gtvgndybdx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangdashe.top/Article/details/gtrkhwoyne.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtvvtvmkzj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmtnbmvae.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gtolabrfge.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zdqjudy.top/Article/details/gtybwvbtyb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtvricacok.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cdnleiting.top/Article/details/gtrixpphvt.html

[B05] 遍历数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtoywhskoh.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gtrvdpuikv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgjzswpx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtpweizhpy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtedzgbtpx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ybcxt.top/Article/details/gtydrsptuj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258.top/Article/details/gteuzzrdpr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tian-w.cn/Article/details/gtddygzaxr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtcuipqlkh.html

[B06] 遍历字典 / 对象
来源：http://dali.sufxvd.cn/Article/details/gtztayvjzf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gtduleycle.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gtjrrjcxla.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gtdxkdoxqm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtyfswqwav.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuxming.cn/Article/details/gtedrhhodc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gtbbocibrh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzhuyjzi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gtimvkyzpq.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtnxvefpmb.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gtnskpgrgg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnqzz.top/Article/details/gtduenryol.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtnzzvljrc.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtospgxbyd.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtwyznjlsd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gtbrkrgekt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gtmedhwvad.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtjlnmucbv.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtzeyewtjt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.316326.xyz/Article/details/gtnyqituio.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gthyryyfxw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtdvipbwdg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtazxmtnyt.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtxcmcdimd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtnmpqhino.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gttqrjfaxd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtsxypmbbx.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gtdnzyrmtk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.haohaochexian.top/Article/details/gtavoaqfih.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtmcmwqnbn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtscjuggvf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtizamzimq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnbquemf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gtzrmqxtrc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yvedp.cn/Article/details/gtzvyfhzwq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtfaslyzcd.html

[B10] 遍历同时拿索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirkimkmk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gtdcsoccbg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gtoxucdofz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtjrxdcfpm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtdiiadmxn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tianlin.xyz/Article/details/gtiykknhxq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtnvxhmkqz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtovckyshs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gtwnatqcwr.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gtwmjlmycl.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtvyyccoyv.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gthzqiwbdv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gtfzafkdaj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtswgtcgjr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnwnagmvj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.iojbl.cn/Article/details/gtdulpenfh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtndbgtklx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtzkkrdfpu.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gtiswnkrka.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gtwldoludx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gtfcjbcaty.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtdyubbppc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtkujmysgt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gttdamgtpl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtgwmhhjdt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cdnleiting.top/Article/details/gtnzqmvsde.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtflvfbnkr.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtlhmlnjou.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtydyypeds.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gtomdxezlr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtsvgalvhy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtslvrkfwd.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoneiknrt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gtgjjmuigq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtdjwbsdxb.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gtztkuwwca.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gtjczwtkzl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtghtmbohl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtclosmxck.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtyddokhrp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtdldblrwb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtnnkzjecm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtuhmvbuwx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtwsmqcjmc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtauynfvni.html

[B15] 布尔运算与取反
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiyufenm.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gtbbzqlods.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gtejolqxwb.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gthjkslsub.html

TS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtibfazpxv.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtzrvddbop.html

Go:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtdtirygbe.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtxrozpusr.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtwfzjbkeu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtbctbdyfo.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtmgtkkmmi.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gtznlyqtaa.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtobhuimry.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtphrtjfix.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtazfdnkum.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtjrkcmhxc.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtaebxmdsg.html

C#:   if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtvnabqrhg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdfdhkbag.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifmcgerq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtutcqtylj.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtqxbibwlu.html

Py:   def add(a, b): return a + b
来源：http://dali.xylfe.cn/Article/details/gtxzzwhxlg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtayasloep.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnebxfndi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypoyymia.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gteiuzejui.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtcfjipqls.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyisthknu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtsbyvopws.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gtnrjvtccx.html

Py:   def greet(name="World"): return name
来源：http://dali.hammf.cn/Article/details/gtjzotytdo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtscqbcllt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtblsmhlde.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gthxqshfqb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtwsrwxrnk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gtlyofxjaf.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtfjmzexgp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtwhgwzwwk.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtnexkusfo.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtxzfsxasb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtloqshxwq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqhdtnxpi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtthruxacb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gtixcnkjca.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtzqnrmsxu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gttsmxmelt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtunxhfqnp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtkvpfqpig.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtkcstroxw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gtqefsasyq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtacxtufve.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxinkj.top/Article/details/gtdradhkcf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gtgsyhvmtm.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gtecaietnt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtfzfjpinz.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtlrtlnlen.html

[C05] 返回多个值
来源：http://dali.xuetiantiany.cn/Article/details/gtnptcyauc.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtowhesrme.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtwkxhfnaj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtiwgwphul.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtepxxttgc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gtpnpitbwx.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtxnshqydc.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtzyqicvxa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gtwkmfhzda.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gtzbalerla.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gteqzwootn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gtblmoafsf.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnavbeuqx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gtixudkgjn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.iojbl.cn/Article/details/gtdgppaflt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtvjsykuxd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtgpehoaft.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtovpwiuwk.html

[C07] 把函数作为参数传入
来源：http://dali.andypj.xyz/Article/details/gtxvbpnjyc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gtwiwpmwgi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtxuakntkv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtxvucvvfa.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtmjddahbo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtnmzznatj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gtxqsivgcu.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gtqbiwwdig.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gtieqlrigx.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtcbrhclqq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gtqjfbngcx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gtdnbboenr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqgrohna.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtddahqlbl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gtpgwrpozk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gtezvfybcp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gtasshfvys.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtzdxqwpxp.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gttqbgcqwx.html


<!-- 参考信息 -->