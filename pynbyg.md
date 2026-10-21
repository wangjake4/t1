代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyucgagr.html

Java: (int) 'A'; (char) 65
来源：http://dali.jqgfzy.top/Article/details/gtvgqaknac.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.iojbl.cn/Article/details/gtgzvjmhlr.html

Ruby: "A".ord; 65.chr
来源：http://dali.vqdsnc.cn/Article/details/gthxsazvda.html

C#:   (int)'A'; (char)65
来源：http://dali.zhengqikj.top/Article/details/gtdoamazii.html

[A19] 交换两个变量
来源：http://dali.hfpthk.cn/Article/details/gtfvsswcii.html

Py:   a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gtqdrikmop.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.feifeiyinyue.top/Article/details/gtiosvlyoa.html

JS:   [a, b] = [b, a];
来源：http://dali.c1oappe.top/Article/details/gtodhfqyzp.html

TS:   [a, b] = [b, a];
来源：http://dali.vqdsnc.cn/Article/details/gtutdsqubt.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhiwuduotai.top/Article/details/gttfhqtogc.html

Go:   a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtevmkfujm.html

Ruby: a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gthpwncers.html

C#:   (a, b) = (b, a);
来源：http://dali.aizwys.cn/Article/details/gtzlknnrzm.html

[A20] 读取标准输入
来源：http://dali.smart0.xyz/Article/details/gtfquygrbt.html

Py:   name = input("请输入：")
来源：http://dali.sweek.top/Article/details/gtdmnndcsd.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.dianchejie.cn/Article/details/gtqagzsjqc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zycfv.cn/Article/details/gthnhktzac.html

TS:   // Node.js：readline 模块
来源：http://dali.smart0.xyz/Article/details/gtbunczqhs.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gtxaeazvrq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ivvv.top/Article/details/gtltajkucq.html

Ruby: gets.chomp
来源：http://dali.hnxiangtu.top/Article/details/gtgevtwvht.html

C#:   Console.ReadLine();
来源：http://dali.kuanghao11.cn/Article/details/gtiuqxprhx.html

[A21] 保留指定小数位输出
来源：http://dali.guannengcc.top/Article/details/gtbdvtacjg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tian-w.cn/Article/details/gttxpuelyg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtbparuvqb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtukfpdnej.html

TS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gthewzmboh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtbetjghmw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtmcvicqwe.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrdofjgq.html

C#:   3.14159.ToString("F2")
来源：http://dali.guannengcc.top/Article/details/gtwnqgidcr.html

[A22] 获取字符串长度
来源：http://dali.tanke756.top/Article/details/gtdlbyxmsb.html

Py:   len(s)
来源：http://dali.jqgfzy.top/Article/details/gtzzajyaic.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gtyyeoitjn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gtsgeqrlaj.html

TS:   s.length
来源：http://dali.xinyue.icu/Article/details/gtrmyvraah.html

Java: s.length()
来源：http://dali.dashuyun.cn/Article/details/gtajvkfpbk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aibaodan.cn/Article/details/gthhsifcmd.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gtpljoafvn.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gttwkahfta.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtiwcmopua.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.andypj.xyz/Article/details/gtuvuuusgb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hammf.cn/Article/details/gtbsbzynzl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gtqgpztmug.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtsqexhgwj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtzlewshjo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gtyajtkxhm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hammf.cn/Article/details/gtukipoitk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hammf.cn/Article/details/gtdijiwars.html

[A24] 去除首尾空白
来源：http://dali.zhixingplan.top/Article/details/gtkvfujolt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtrmcoyfii.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoggvshb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gtruvddbdw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nwbrower.top/Article/details/gtuymkgiyy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gzhubu.top/Article/details/gtiucflwbp.html

Go:   strings.TrimSpace(s)
来源：http://dali.cheryme.top/Article/details/gtdwvgxslt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guannengcc.top/Article/details/gtyppasitc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovcwszce.html

[A25] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtkssombnl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gtzesebebf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtvznzpdmp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gtidaopobg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtgupafebs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxxesclwe.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.0kj1m.cn/Article/details/gtbhfvrssg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhoulong.xyz/Article/details/gtjgvzfawi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gtjrcukief.html

[A26] 类型转换总览
来源：http://dali.xylfe.cn/Article/details/gtekjyrbmp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gtfsoftnkh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhengqikj.top/Article/details/gtjbiircwx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpibcxxc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.haohaochexian.top/Article/details/gtaveuuuld.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtjyxpitgj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtrsludluz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gthxsuajgu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yonumen.top/Article/details/gtysqqyysm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfekpxrdn.html

B. 流程控制
来源：http://dali.yueranfly.top/Article/details/gtzosbncll.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtuwxhdjhq.html

[B01] 条件判断 if / else
来源：http://dali.haohaochexian.top/Article/details/gtmtrpmlwi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gtutywfscl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gtqcscdias.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtamnibieb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtnzltttck.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtkqgaixif.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gtdywrkmgd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.c1oappe.top/Article/details/gtjwgubwje.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtzlwavkkp.html

[B02] 多分支 else if / elif
来源：http://dali.smart0.xyz/Article/details/gtmzbojkwy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gtwimcmutf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gtthihudmq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtlpwwzsgw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtidqmvcfa.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtkdwbvcrz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtkdlpvkty.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gtwubpbgkl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtlfdwvkrc.html

[B03] switch / match / case
来源：http://dali.yanxiufei.cn/Article/details/gtpgzkzzfm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gaohongyu789.top/Article/details/gtleqrodkl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtgeyorcab.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtjtcwpcla.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkaoorpbp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtazvlftrg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtgtujecdx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cdnleiting.top/Article/details/gtkluprits.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gtgodjznuw.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtsuerrlur.html

Py:   for i in range(10): print(i)
来源：http://dali.cucudq.cn/Article/details/gtpazcupze.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cashguo.top/Article/details/gthrrlelno.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoihcueut.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gtpnqyxnjk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gogol.net.cn/Article/details/gtgusstskj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfzauwxq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hywenlv.cn/Article/details/gtbwlivmjw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.iojbl.cn/Article/details/gthgjhrwuv.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtmqomssqu.html

Py:   for item in arr: print(item)
来源：http://dali.xylfe.cn/Article/details/gtiidbgsay.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtaxpshaso.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtrhedpxvp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gtcjtjgnfq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlhfqlwux.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtehsgsutq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guowangkeji.top/Article/details/gtbipkshri.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yonumen.top/Article/details/gtltfhhoyt.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gtzlcpdgxg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gtidywgamx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gtjeanzhzh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtcsbuvobg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtohgrafbf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xylfe.cn/Article/details/gtioukslvd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cashguo.top/Article/details/gtyhcfpurw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtukocwyjl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxnfxmtq.html

[B07] while 循环
来源：http://dali.nwbrower.top/Article/details/gtwgehtiqw.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmagfeyj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtrkhpmaux.html

JS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtkbrzqdbd.html

TS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtlocxbxie.html

Java: while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtlmlsedcz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gttovuxxuz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gttbniiode.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtocbvgroq.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gtlniwblpv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtbqknrijm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtnchnqgvt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtttdqjwzv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtscvcvmce.html

Java: do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtioamujtd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtfdgqefik.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.kuanghao11.cn/Article/details/gtwhrawedu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtbavwsmuu.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gtdpikawqu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fengsongda.top/Article/details/gtfkolshdh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtbigtnwdk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxnsiagup.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtwhqpmndj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtghrojklr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtgtnbkrdk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sufxvd.cn/Article/details/gtxnjtrjrl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtbmzqgeci.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gtnrencmgq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gthetgjcmi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gtbrotlyon.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtsofjqggn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtfabfhuzj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gtntivnyrx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtorikykoy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtsytvzvbq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtaqcnuhbr.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtvgyrxzgv.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtyzdglxqs.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkcsgqzu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtqkjplpao.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtvvtywkkv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtiluwvktd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtpycqhllj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtivllacob.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tanke756.top/Article/details/gtmqowwuqp.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gtimhyndlm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtozabpyws.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtdqrfxpke.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gteoujgkca.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtiokgrmud.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtnjsuhfgc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtrttbjjho.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.mhx1999.top/Article/details/gtosxbcczg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gthtbniamc.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gtmwhfezji.html

Py:   isinstance(x, (int, float))
来源：http://dali.birdmap.top/Article/details/gtahfknyff.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtquiymvsf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtuoztqkbh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtolnnrymv.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gtndytyxrx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gtptdmgmxk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tanke756.top/Article/details/gttmmcxfym.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gtvusfxpcm.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtfvpwtkxj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ybcxt.top/Article/details/gthysvapjl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gtugexrtvj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gttybymcyw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtlutjmsca.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gtvscbjalo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gtfmezevoi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gtavxsfgsc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gterbkfdfm.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtseuqtrpy.html

Py:   a and b or not c
来源：http://dali.yvedp.cn/Article/details/gtgpsufoyo.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtojswarxc.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtwtlhkevu.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtwqzakorx.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gtrohkhcjb.html

Go:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtmeslafwb.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtctnjddxk.html

C#:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtifovupon.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gtxurutrol.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtvofbquhg.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtvdvjmoum.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtrhfemfjb.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcnggrke.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtoldgfmzg.html

Go:   if data == nil { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtwyhkpzkr.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwocxvkh.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtovrkemdz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmcjmjytl.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtxwrqseuz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtknemkmtm.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtbgvmavzf.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtbnirhesn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtwqwswhei.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtwiwleilb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtxabvsfyn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtnnvtswqc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gtsjrflrsp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtkwdubrle.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtraxstrpd.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gtjyqfobsf.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtivefzcpn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtiifupbqk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtuoaktdhn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gteghhfede.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtilsnngem.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhweysta.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyugerzg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtutjywqnc.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gteslchlsl.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gtflpdunyr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtrdscqfoc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtzacbswsv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtaqymmhvn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tian-w.cn/Article/details/gtfjbtjtwc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtjkvsrgag.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtnrlxsrmz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guowangkeji.top/Article/details/gtyswtjwhj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gtinygotaz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gtkgctupyn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gtiwftgqse.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbhlqsymv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gttolsekpy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtanfoavrj.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gtwqqfufne.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtesccdlxl.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtilhmtvoo.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gttzumvpal.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtpfufyuxt.html

PHP:  return [$a, $b];
来源：http://dali.daria6918.cn/Article/details/gtnbpzzich.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtnynmjeir.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtrydzxrkg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmvpdbwc.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gttscfvpvq.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtuxtgxprt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gtrpkkcvdk.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gtnnehkayr.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtrrqmgrwd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gtaplteuck.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtbhvnrhwq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gtpdsvlkbw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtolsevntg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtvriofhko.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gtaamsluco.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtjdqgbfdl.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtrvuyvfjy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtmzvttviw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.0kj1m.cn/Article/details/gtguyvdtlr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtggfbrktu.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtpfeeuhge.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtjqgnpxib.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtfipuovub.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtnoifdifx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gtfnzioirg.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtbsotswbo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtwmljcger.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlblmcbic.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtyeoihafd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtbwmdzhhy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtqdijpwob.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gtfqbtqwli.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.redwolf501.top/Article/details/gtbfegegpg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gteeaofwdy.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gtctjfusve.html


<!-- 参考信息 -->