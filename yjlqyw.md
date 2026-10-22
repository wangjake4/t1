代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.havefunace.top/Article/details/gtpagdmtch.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtabazqqbq.html

PHP:  ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gtcbgonugp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shuidangran.top/Article/details/gtnivuuzsl.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gtpqypuxsk.html

Java: (int) 'A'; (char) 65
来源：http://dali.dashuyun.cn/Article/details/gtbyqflpgi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cheryme.top/Article/details/gtsieegkon.html

Ruby: "A".ord; 65.chr
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpsdufus.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gtuxtnjsdh.html

[A19] 交换两个变量
来源：http://dali.andypj.xyz/Article/details/gtdnmpsbuz.html

Py:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdxtvxwd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhxwrcra.html

JS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtbplnbfdw.html

TS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gtcyxzqlcm.html

Java: int t = a; a = b; b = t;
来源：http://dali.meibo888.top/Article/details/gtryagpaay.html

Go:   a, b = b, a
来源：http://dali.cqqwz.cn/Article/details/gtqhvtuagp.html

Ruby: a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gttpxwvbam.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258888.top/Article/details/gtcokgoqus.html

[A20] 读取标准输入
来源：http://dali.xuanzx.com/Article/details/gtwlfwulvh.html

Py:   name = input("请输入：")
来源：http://dali.nanxinkj.top/Article/details/gtwyzqhame.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sufxvd.cn/Article/details/gtbdalvcxg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gotoacloud.top/Article/details/gtgoknfedz.html

TS:   // Node.js：readline 模块
来源：http://dali.tanke756.top/Article/details/gtwankoxzn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yuanzhike.top/Article/details/gtqfwsmkqy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hammf.cn/Article/details/gttaymzjyo.html

Ruby: gets.chomp
来源：http://dali.zycfv.cn/Article/details/gtgqvmrdwt.html

C#:   Console.ReadLine();
来源：http://dali.meibo888.top/Article/details/gtdimffnln.html

[A21] 保留指定小数位输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfmauwss.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj20258.top/Article/details/gtsjuhkvly.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtbuprhakz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtofqtgwvh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtktztgubv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtbfhzumdq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuanzx.com/Article/details/gtvhbdviyl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtqealahmu.html

C#:   3.14159.ToString("F2")
来源：http://dali.jiagoushi.top/Article/details/gtfhvjxjoc.html

[A22] 获取字符串长度
来源：http://dali.sufxvd.cn/Article/details/gteqinqjyp.html

Py:   len(s)
来源：http://dali.9152youxi.cn/Article/details/gttjmjvdmi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gtlcgenwpb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jyoumei.cn/Article/details/gtnyvylddj.html

TS:   s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtkoivifow.html

Java: s.length()
来源：http://dali.yvedp.cn/Article/details/gttirpgcyt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.redwolf501.top/Article/details/gtpkoerfqr.html

Ruby: s.length
来源：http://dali.xuanzx.com/Article/details/gtojdvjngp.html

C#:   s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtjgzryz.html

[A23] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtqldkizak.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtpsjjhwko.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daria6918.cn/Article/details/gtzrgidcbh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtizwgkqkf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtxrlzfppr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gtiwkupals.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmfhhbde.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gtyxsuhvhf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcbditmx.html

[A24] 去除首尾空白
来源：http://dali.aizwys.cn/Article/details/gtfjkkuaev.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenlongwang.top/Article/details/gtsypxilwl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zycfv.cn/Article/details/gtzpnwmpmf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guannengcc.top/Article/details/gtdbflaaum.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtleauamqz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.quarkkingdee.top/Article/details/gtqhsvjhte.html

Go:   strings.TrimSpace(s)
来源：http://dali.gzhubu.top/Article/details/gtxsxlsoii.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gtjtzjylog.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.316326.xyz/Article/details/gtdwmeblug.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagwzcrmm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258.top/Article/details/gtaidqvsan.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gtgsvkzmka.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbpzsvqp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.snrcjt.cn/Article/details/gtwhhbumnm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dashuyun.cn/Article/details/gtcvpwkorm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gtnfpsfkih.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuetiantiany.cn/Article/details/gtwybyiyqs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gtjqhcnflk.html

[A26] 类型转换总览
来源：http://dali.xuanzx.com/Article/details/gtzzzzxvcb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yangfankeji.com/Article/details/gtlkvgnbqo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhixingplan.top/Article/details/gtjylbfbia.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ehwqpu.com/Article/details/gtzpzzserr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.haohaochexian.top/Article/details/gtmpvnfuzx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtncygkoxe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.snrcjt.cn/Article/details/gtgyptsyec.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtdlsbghom.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtlqbtwcfb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthfxoreal.html

B. 流程控制
来源：http://dali.tianlin.xyz/Article/details/gtdxymboyw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtosovoaig.html

[B01] 条件判断 if / else
来源：http://dali.dianchejie.cn/Article/details/gtquvzjbyt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtverdldww.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtrfiwsiqw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtymcglgoi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtsrebwqps.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtozsfrxrg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gtaltdcwzp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shuidangran.top/Article/details/gteffupyud.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtzekjaret.html

[B02] 多分支 else if / elif
来源：http://dali.yuxming.cn/Article/details/gthrjxdbdf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dashuyun.cn/Article/details/gtrhrpkfex.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gzhubu.top/Article/details/gtannsbyao.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtixaitshu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtncycuwmw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gteklgymvp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aibaodan.cn/Article/details/gtumyeuucz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gtyalnvxiq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyesuwqyf.html

[B03] switch / match / case
来源：http://dali.ppjwa.cn/Article/details/gtsmmqnstn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwccmemb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbfdzint.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtyvfidrgm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtzcyzurwr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtoptmiewp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xylfe.cn/Article/details/gtcrseghvf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenlongwang.top/Article/details/gtgirqcfgc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtbuflycyx.html

[B04] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtntbdtaia.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gtpuaersqf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cucudq.cn/Article/details/gtcnczbrsj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fzhhl.top/Article/details/gtlzkrcxsa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtaspbupic.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yueranfly.top/Article/details/gtmvybbxwf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.9152youxi.cn/Article/details/gtpsdolwro.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhixingplan.top/Article/details/gtrkgzdkke.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtvcaiqpqm.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtufklqfis.html

Py:   for item in arr: print(item)
来源：http://dali.andypj.xyz/Article/details/gtrvvnnzxw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.9152youxi.cn/Article/details/gteavcgqxv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzktkrzsw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtmtkxahwl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtesbsfnzy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gtzbriemuw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gtxqmknhrf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gtfsrycoed.html

[B06] 遍历字典 / 对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiszdhkm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tian-w.cn/Article/details/gtrsbuyiid.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.andypj.xyz/Article/details/gtyfqgzbqc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtmvcrdngp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gtwirljyub.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gtuwltafid.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daria6918.cn/Article/details/gtocyygadu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guannengcc.top/Article/details/gtvflvycav.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtvbfhnqtw.html

[B07] while 循环
来源：http://dali.cashguo.top/Article/details/gtvpweacyi.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gtconuyahq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gtgzjbqjvk.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtphxfsfat.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtncvffuzx.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtqethkvlz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.svipenyu.cn/Article/details/gtojtxzefm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gtfwfvjfiv.html

C#:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxudexjzq.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gtxpssuriw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gtnzqoyulv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gtivkfzriq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtufrpixah.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtemmltrwp.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtfuubayfn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gtmpqwozaq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gtckbnsbpr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtkbsoslmw.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtpssthmhb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gtfgbnynsk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtcwqhrctz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtqkndkxzg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtjypwdvko.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcarpifek.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gtxaczcgdr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgufenzy.top/Article/details/gtieydkuxc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtyzcvxpsp.html

[B10] 遍历同时拿索引
来源：http://dali.fengsongda.top/Article/details/gtfljgqchu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtvwvudkjl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzkgqtinu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtruhvacny.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtosofqhvl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gtinkslwys.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nwbrower.top/Article/details/gtdoqdklfk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gttsuydzbi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gtdyolmmli.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gtdnlbozic.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtsqcttarp.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gtumhehoqp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtzmubmlli.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gttejtvady.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtonpknvol.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gtsrimpcgj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guannengcc.top/Article/details/gttwiqaalf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtekmaadze.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gtedcmdfjf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuanzhike.top/Article/details/gtwjzlgbir.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtzmzlrnbk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtrxkwbhas.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtubtcsoel.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtkglatcgk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sweek.top/Article/details/gtkuhrwceg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtxxmsukxq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gtywfmxuhr.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gtxzztvqjz.html

Py:   isinstance(x, (int, float))
来源：http://dali.ivvv.top/Article/details/gthkuphorf.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtoucrfkfa.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtujmszpsc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtigkucpou.html

Java: x instanceof Number
来源：http://dali.chenlongwang.top/Article/details/gttfpotwgh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gtlwwnjihr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dianchejie.cn/Article/details/gtwdahjfbf.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gtldvvjtmq.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtgdgcuzri.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gtqqoabljr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtpnsomipq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtyxmhwbyq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgncqnaq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtsytjfrfj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gtxaxefqpd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.snrcjt.cn/Article/details/gtzshrxtwc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtnvgpsmdl.html

[B15] 布尔运算与取反
来源：http://dali.guowangkeji.top/Article/details/gtryscvvej.html

Py:   a and b or not c
来源：http://dali.mhx1999.top/Article/details/gtrmblrwcx.html

PHP:  $a && $b || !$c
来源：http://dali.shzxlz.cn/Article/details/gtesodiyua.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtkqmcbicb.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtsadlprwf.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtdofvfvnc.html

Go:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtraoxzfza.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gthfxdpgey.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtjpwkvivk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gtfnlpchgr.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtbcoktxoi.html

PHP:  if (!$data) { return; }
来源：http://dali.hnxiangtu.top/Article/details/gtyqrxjycf.html

JS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtxvpozcat.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtnkbhzlzu.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtwttlllph.html

Go:   if data == nil { return }
来源：http://dali.jinqigufen.top/Article/details/gtxtmyicjh.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gttpyyuqzi.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtoxjmzfub.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnpzjssbc.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gtecgyimpz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtaznrvnkh.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtuqiucnzx.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtcryiuedf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtyphryrzu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtlxhtmvct.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gttvhhssau.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtvvqxprqr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtsetwxaov.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtfugpnhjt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtqxdqmjpo.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtiulywcjf.html

Py:   def greet(name="World"): return name
来源：http://dali.chenjidiqi.icu/Article/details/gtufhwpksz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtwvdlftae.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtmwqpzsap.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtekktxerg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtkpfllttm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuxming.cn/Article/details/gtmtaszshh.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gtsujpmnau.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gtpgeamdyn.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gtztxbbzrn.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtfcehkecn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shzxlz.cn/Article/details/gtxdmvcgqj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtllgvbftu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtetgazhay.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtinqijsbf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhongyouzk.top/Article/details/gtkuusynpf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gtqprkaqzc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gttmmeabsj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gtlbfqojvo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gtfktgbnnl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.mhx1999.top/Article/details/gtxkswuvyy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtscdspfxl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gtknkprfos.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtjtcwoo.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtgybysana.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gthhoburei.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtcevebmgz.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtqkbgoexb.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtzlknazyo.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtynotaxij.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtuqekqkct.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtcpnypqrs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gtafoqzuhw.html

Go:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtecirymzd.html

Ruby: return a, b
来源：http://dali.svipenyu.cn/Article/details/gtgjoxfxdg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtbkqdeawq.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtbmrlnutj.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtdorfkqhb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtdrynhrrk.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtzvjyzlnt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gtpgjuovkm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtknllzksj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gtilumyxee.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gtobsvxioa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gturgpnmws.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gtajslmasn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gtwjcdxhvj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gtzkzacned.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daria6918.cn/Article/details/gtvemvveuj.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtfsjqckgv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gtdnkzqdcb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gttqukgyqi.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtluaifhhq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtwrentaep.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gttosgxibe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcrvdwjo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtijvgbgas.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtmvextqbk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtchgsrfkj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtjlhipvkm.html


<!-- 参考信息 -->