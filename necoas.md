代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daxiang520.top/Article/details/gtqiqibnso.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258888.top/Article/details/gtxkkjkoxx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.feifeiyinyue.top/Article/details/gtoiwipimk.html

Ruby: "A".ord; 65.chr
来源：http://dali.daria6918.cn/Article/details/gtmmcxvtnf.html

C#:   (int)'A'; (char)65
来源：http://dali.zhengqikj.top/Article/details/gtdnuwaqse.html

[A19] 交换两个变量
来源：http://dali.birdmap.top/Article/details/gtvefrvomv.html

Py:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtmcmoczlv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ppjwa.cn/Article/details/gtimckoczi.html

JS:   [a, b] = [b, a];
来源：http://dali.9152youxi.cn/Article/details/gtpwiauwba.html

TS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gtlptotubr.html

Java: int t = a; a = b; b = t;
来源：http://dali.jianghu66.top/Article/details/gtpqjnhnol.html

Go:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gtgrbxyaon.html

Ruby: a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtzelujeja.html

C#:   (a, b) = (b, a);
来源：http://dali.c1oappe.top/Article/details/gtukewkxpe.html

[A20] 读取标准输入
来源：http://dali.0kj1m.cn/Article/details/gtopyuphss.html

Py:   name = input("请输入：")
来源：http://dali.zhiwuduotai.top/Article/details/gtyxrzhlnc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.guannengcc.top/Article/details/gtnmywkbde.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.9152youxi.cn/Article/details/gtmvlbasoi.html

TS:   // Node.js：readline 模块
来源：http://dali.hnxiangtu.top/Article/details/gtecujxghx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.nwbrower.top/Article/details/gtiyxicbtr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlteoslh.html

Ruby: gets.chomp
来源：http://dali.ehwqpu.com/Article/details/gtfqewpbqd.html

C#:   Console.ReadLine();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtreovamgj.html

[A21] 保留指定小数位输出
来源：http://dali.meibo888.top/Article/details/gtbewwsncz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shuidangran.top/Article/details/gtkmyoxfox.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtraiehuro.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtwqgbkyzf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtldbprosa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtcbymlhuf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gtqleybedc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtjmryycbz.html

C#:   3.14159.ToString("F2")
来源：http://dali.wangshuangyany.cn/Article/details/gtwlhojzpk.html

[A22] 获取字符串长度
来源：http://dali.cashguo.top/Article/details/gtutxmbccc.html

Py:   len(s)
来源：http://dali.nwbrower.top/Article/details/gtpgpboifg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhoulong.xyz/Article/details/gtbploxkpq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.iojbl.cn/Article/details/gtrdyhtygi.html

TS:   s.length
来源：http://dali.jqgfzy.top/Article/details/gtkfktkojj.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtaumwwdik.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cucudq.cn/Article/details/gtmwdztfbi.html

Ruby: s.length
来源：http://dali.hfpthk.cn/Article/details/gtcwtomftp.html

C#:   s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtwzrzdcxa.html

[A23] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtwelwztdg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.svipenyu.cn/Article/details/gtezggbwpb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhengqikj.top/Article/details/gtferstdhk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtmhnqwphz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtrnhlgmvx.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gtpjytajnw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.mhx1999.top/Article/details/gtxbtfuwci.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.meibo888.top/Article/details/gtemslkmjl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnxiangtu.top/Article/details/gticdmqsnp.html

[A24] 去除首尾空白
来源：http://dali.tian-w.cn/Article/details/gttxuvczom.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.birdmap.top/Article/details/gtutfvdcot.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.vqdsnc.cn/Article/details/gtgfhuimhd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gtxodcazvz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtirntkufh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zdqjudy.top/Article/details/gtpujvueyl.html

Go:   strings.TrimSpace(s)
来源：http://dali.mhx1999.top/Article/details/gtxlzhftzj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pengpengdd.cyou/Article/details/gtubbpkdbw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtgtyoepzd.html

[A25] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtbbktttor.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fengsongda.top/Article/details/gthiksqmew.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gtoxvzomkn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtxvwelhpa.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gtemhrolyg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jyoumei.cn/Article/details/gtemwigfpq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gtyqilcqvv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffnfswkj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gtpuaauzqy.html

[A26] 类型转换总览
来源：http://dali.shangyingyoupin.top/Article/details/gthjxripwq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daxiang520.top/Article/details/gtpjjyoefw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pycfn.com/Article/details/gtkclyreoc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.snrcjt.cn/Article/details/gtebkcfgqw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxuanxn.top/Article/details/gtksbazyap.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gtxavbiopa.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yanxiufei.cn/Article/details/gtigueaarf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenlongwang.top/Article/details/gtplxcjber.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gtrhjppibg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtczqqxvvw.html

B. 流程控制
来源：http://dali.yuanzhike.top/Article/details/gtaxbeftaq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwaojaesy.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gtdovohwge.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.redwolf501.top/Article/details/gtweoggjpa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.redwolf501.top/Article/details/gtdvnnsdie.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtukpodrjj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtonmctmnn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtyshiimhl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gtuekjcpml.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.c1oappe.top/Article/details/gtehatrbkd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtkzaukdwz.html

[B02] 多分支 else if / elif
来源：http://dali.gzhubu.top/Article/details/gtyawtdhxr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tianlin.xyz/Article/details/gtvrkhakdf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdfcebpfr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtvnzmvrvm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtsbsxkzqy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtypcubjmv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guannengcc.top/Article/details/gtxcvftqlu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.svipenyu.cn/Article/details/gtheprqsap.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtfzhurjdi.html

[B03] switch / match / case
来源：http://dali.zhoulong.xyz/Article/details/gtdvdcrzmd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fzhhl.top/Article/details/gtfwlrcanv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtinfxyxyn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtjdpjjrei.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtumlwctzf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtvidkqaeq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtpzvuscys.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gtyqnychwj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gtvuexvfla.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gthwtztfgq.html

Py:   for i in range(10): print(i)
来源：http://dali.xziqi.cn/Article/details/gtlxjkwfki.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuanzhike.top/Article/details/gtikgxigbd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtdtvsljxc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtliwmsout.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gogol.net.cn/Article/details/gtwcckzowp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.feifeiyinyue.top/Article/details/gtngvqmvvr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cucudq.cn/Article/details/gtjgtajsen.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtttjxlepf.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtxqdauqwz.html

Py:   for item in arr: print(item)
来源：http://dali.xziqi.cn/Article/details/gtbbscwwgr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gttaecnkde.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gtztyomlhc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gtaumlexto.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sxryk.cn/Article/details/gtktbrjxfd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gtrsbbyrii.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gtqvktdhrc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gtoyqvyehh.html

[B06] 遍历字典 / 对象
来源：http://dali.zhengqikj.top/Article/details/gtfpkxcnsn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zdqjudy.top/Article/details/gtizjhupwq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gtmavgmdok.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gttpnulctp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtxanxdlfj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xylfe.cn/Article/details/gtonibxtqf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gtrfxngswl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sufxvd.cn/Article/details/gtepkyljyh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gtsfdbkbbm.html

[B07] while 循环
来源：http://dali.yangfankeji.com/Article/details/gtpvzbniso.html

Py:   while i < 10: i += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtdhriswdf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gtvbryxevc.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtqgrfywor.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtfpvfuzuh.html

Java: while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gtnaofhbkb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gtasantgdh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtydeegqqa.html

C#:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtipqicspy.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gteurnxvqm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtyeglhvyi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtpjloiyvf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtvmyygalj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtvqqluyfx.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gthnhewcwv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sxryk.cn/Article/details/gtvokxuncx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtwhkdaccx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtukxhatfp.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gtexkvqsby.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtiwpyftcl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gttvsvosea.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtceudczyu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtyexiewmp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtyfcwojrj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtxwdjhoaq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gtxqtradzy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtjmmiwldo.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtoojxowff.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gthxcjiknd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daria6918.cn/Article/details/gtkbkzicjl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtgzhrbbmm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtalvcpmzr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigfzy.top/Article/details/gtsihqixpn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmcvipkx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtxtywfutp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.snrcjt.cn/Article/details/gttkkbtxzq.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwwomhrl.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtzsteyrrd.html

PHP:  range(0, 10, 2);
来源：http://dali.cashguo.top/Article/details/gtnazfjvye.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtzrdksjqx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxetmtwpr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.vqdsnc.cn/Article/details/gthbiqwvtb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gtvougvpce.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gtjyxtwdwh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtpvntzxxx.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtezdmjsev.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtzqslshyp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jianghu66.top/Article/details/gthxsffuqa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtzrhbcdrk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtrqgltqjs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtgkceajij.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhixingplan.top/Article/details/gtdxtefadn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtovjudayo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtqqxwtfhn.html

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gtpuoivwoj.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gtlgmshuol.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtovqnefjo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtmhogklfx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtliystvbe.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gtwasorsfa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gtjlswsqsc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gtmpfzrusn.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gtysenkwzk.html

[B14] 判断值是否在集合内
来源：http://dali.daria6918.cn/Article/details/gtqkdugmyp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gtlgpnlvdu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtajedrraj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gttobyqjgz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtxiipwwoc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtzlfydyai.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gthscsmrqz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtoxiagxzo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gthuixlsmp.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gtdooxorqw.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gtgrcvwdkq.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gtukbhykut.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtynqpthcj.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtzsziseys.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtjgisgdzi.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtbhgzffup.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtmctpftpn.html

C#:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtdsxvgeuh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gtmtvdcaob.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmzzhray.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtatnczbby.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtztnjevnd.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtujumrrxu.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtoyupjiev.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtsrvjfcgc.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtuednppob.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtcnegdwqc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqxwxotm.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtdldvoopb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgkhilvz.html

[C01] 定义函数
来源：http://dali.hammf.cn/Article/details/gtdftbqstc.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gtyyovvnrm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtovspdssj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtdqtsnmul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtvepgkkaq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcftcpmiy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gttkyrwuio.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gtxfwvjdxz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtwqlpveyo.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtnqdrvdua.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gtsajesfei.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtatxhsobi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqwibtmak.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfjeegndr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrkhomzp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gtocfmwtme.html

Ruby: def greet(name = "World") = name
来源：http://dali.bjfxy.top/Article/details/gttlpuvqdw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ehwqpu.com/Article/details/gttkvgzwyy.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtxmsnbzhg.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtbveqrcpk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtrkzcnixj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtuzstozhx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtbubhlzti.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtsepvulnb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtwsppop.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtrfheirpd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibrnlnsr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopcrdtqc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtwasxirmt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtnxuozpab.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtlmmffczt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtjomrtgfp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gtmbftjlxk.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtvifkeobg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtltjdvgpo.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtsbbzjtbl.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gtjqdawwzg.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtscijyehq.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtirgoihfu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtaigedion.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtsalfermh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xziqi.cn/Article/details/gtyjjcejpc.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtdnfxphwd.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtlulufhng.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gtxkaatdgx.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gtvcipmsod.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gtjwkmjghs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtuftzmnmj.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtoozblnyw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtntgvielw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtztviveeu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsthcjcpt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtzcgcmles.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtcyibueft.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtnxmqoain.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtxxjugcxl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtvbsctotr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtdtnfugha.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gtecadeybe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gtlmagfzsb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtkfdrpkcq.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gtnwihilum.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gtpklnhzhn.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gtxzfbviuu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gogol.net.cn/Article/details/gtjrxkeifz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtkugtpybf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtvqrhkmpk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtukbxvuuo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gtqwnmyfml.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ehwqpu.com/Article/details/gtopwrlvbk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenzaomai.com/Article/details/gtvwcnmqrl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtmojuufdo.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gttdamxlho.html


<!-- 参考信息 -->