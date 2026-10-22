代发 wailian999

Ruby: a, b = b, a
来源：http://dali.xuanzx.com/Article/details/gteflucmzj.html

C#:   (a, b) = (b, a);
来源：http://dali.zycfv.cn/Article/details/gtoandcvbq.html

[A20] 读取标准输入
来源：http://dali.sysykeji.top/Article/details/gtfwhuyeeu.html

Py:   name = input("请输入：")
来源：http://dali.mhx1999.top/Article/details/gtavjuwhzp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ydzc1.top/Article/details/gtkaysknun.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pengpengdd.cyou/Article/details/gtdgqgofrf.html

TS:   // Node.js：readline 模块
来源：http://dali.hfpthk.cn/Article/details/gtzmwabynq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gtzhlrulxq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.9152youxi.cn/Article/details/gtxyxfnyss.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gtcbzosqal.html

C#:   Console.ReadLine();
来源：http://dali.yj20258.top/Article/details/gtknisjmqm.html

[A21] 保留指定小数位输出
来源：http://dali.jiagoushi.top/Article/details/gtwbpksdqn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxinkj.top/Article/details/gttmehhtyl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtkngbxrkv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtenfafkez.html

TS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtccpvmwzz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gtllmkwsiu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtvloqcexq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtibzbwlbs.html

C#:   3.14159.ToString("F2")
来源：http://dali.gotoacloud.top/Article/details/gtvxcutzgv.html

[A22] 获取字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtekemstsa.html

Py:   len(s)
来源：http://dali.wangdashe.top/Article/details/gtzgwqsesr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj20258888.top/Article/details/gtzkxvdlnh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yuxming.cn/Article/details/gtdfxkgaro.html

TS:   s.length
来源：http://dali.cucudq.cn/Article/details/gtrjnlcjut.html

Java: s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtqkaiwtxw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ehwqpu.com/Article/details/gtmdyvncsd.html

Ruby: s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtyrlgturr.html

C#:   s.Length
来源：http://dali.hammf.cn/Article/details/gtrrxhppwj.html

[A23] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtkjyiwvqa.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigfzy.top/Article/details/gtujfytzzx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gogol.net.cn/Article/details/gtycputgew.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.0kj1m.cn/Article/details/gtcovnvgew.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtusbwclzr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtaqudtqlm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyryylgvj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yueranfly.top/Article/details/gthjiodkly.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.vqdsnc.cn/Article/details/gtecrwhxcb.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gtakbonkvh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ydzc1.top/Article/details/gtxbfemexm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gturzmckmj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gtgjljhrcm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gtlhkutoho.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gtzeerkitf.html

Go:   strings.TrimSpace(s)
来源：http://dali.jiagoushi.top/Article/details/gtbivejehu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.bjfxy.top/Article/details/gtjtrwkfal.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.c1oappe.top/Article/details/gtlewfkpfa.html

[A25] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtbqpwmzak.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cashguo.top/Article/details/gtsywmsoyl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtuwfeiqmf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtmycomaqs.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gtjykvtvyy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.birdmap.top/Article/details/gtpbytbdur.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtlknbjvtw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.guannengcc.top/Article/details/gtnouqrvcc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gteyxchpaj.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtandmdowj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yonumen.top/Article/details/gtwajmnfpn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangdashe.top/Article/details/gtlubraxpz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigufen.top/Article/details/gtipakqvoo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ppjwa.cn/Article/details/gtwjsgzsmn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.quarkkingdee.top/Article/details/gtxxmgttoa.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenjidiqi.icu/Article/details/gtmoowpsrm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hammf.cn/Article/details/gtnemellnn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gtbulnanxb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqkwmdgal.html

B. 流程控制
来源：http://dali.aibaodan.cn/Article/details/gtmoowfree.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxaxhnzq.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gtexlvjrfr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gtrnlrpbuh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.9152youxi.cn/Article/details/gtwhisaedb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtrwmqohye.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtutwsllba.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtbxbxdhzs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.316326.xyz/Article/details/gtuyuknksk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuanzx.com/Article/details/gtofogkzxx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtsmastbde.html

[B02] 多分支 else if / elif
来源：http://dali.bjfxy.top/Article/details/gtfshczryn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gtocveympv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tanke756.top/Article/details/gtvodfvetf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtdxewasql.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gteuqjdrst.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtlzyvcrsm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gtzehsoaqw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangtech.top/Article/details/gtntzwhbqu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukgmfqdr.html

[B03] switch / match / case
来源：http://dali.havefunace.top/Article/details/gtyikdoiqr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hammf.cn/Article/details/gtzqvzxatf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtdbquxems.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtwmaovqaa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtgwykavxw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtrbiluvtd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtsbwnnbxa.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinghuilouyu.cn/Article/details/gticatdqbq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtldyhxxed.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtcnasrdpe.html

Py:   for i in range(10): print(i)
来源：http://dali.cdnleiting.top/Article/details/gthzbaufwd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hammf.cn/Article/details/gtlbhnuvrf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gtktoytxtb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pycfn.com/Article/details/gtwuhvwiwy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gtpezonuwf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jiagoushi.top/Article/details/gtlkikbgbj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gtyujxcfum.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cdnleiting.top/Article/details/gtodptidhp.html

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtfuvpqyuk.html

Py:   for item in arr: print(item)
来源：http://dali.chenzaomai.com/Article/details/gtjalgfjtf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gtiyrxqhpv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtcrzlvtfp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtgkvgwuaj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtehzlpfie.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gtdrcsyhqc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtuxskjhjz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cdnleiting.top/Article/details/gtkmatswtl.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gtjoimjdel.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhongyouzk.top/Article/details/gtmvsisgbs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.birdmap.top/Article/details/gtebzhkiys.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gttcxhphuc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gtnnluqicx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.0kj1m.cn/Article/details/gtvhhtrsun.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvszqsow.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gtjzcrwsrj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gteryiegfd.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsnitbre.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gttzglpeaj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gtgapdjxel.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtrvfkjxzm.html

TS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtrlezgvwn.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtydsxjzkz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gogol.net.cn/Article/details/gtcxramxbk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gtwjkskcfm.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoneuuowc.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gtiypoqwfc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.snrcjt.cn/Article/details/gtmznowite.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gteqkazleu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtyuwfddkd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtvpkgmeok.html

Java: do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtjusxdpud.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtqfrktepx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gtdiguhkru.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtalukgbeo.html

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gtvfzlnido.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgufenzy.top/Article/details/gtsydwsbvb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtzosxdjfz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtoemxbfsc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpemwtfpi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtvehabmjb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gtcempihju.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gtjmxqhgca.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtbnujqphp.html

[B10] 遍历同时拿索引
来源：http://dali.jlsjyb.cn/Article/details/gtenwejnyz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gtnijgfliw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtpkyuvgkx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtunxouexi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtxowizqcg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gtkxnndliw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtonzohquj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gtzwpwignd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtabedkdzc.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gtpavjdlcf.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtvfunuakc.html

PHP:  range(0, 10, 2);
来源：http://dali.xuanzx.com/Article/details/gtnydzexjd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaamfiyy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtjlpyxrlf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtcvjrsrcy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gtcyygvhlq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtxxdvmyep.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gtujzrhlnn.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtxmdcxelg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gtzojeqpac.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.andypj.xyz/Article/details/gtjwtqewks.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtgfmmvplj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gthripmdnv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyezuuzts.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvjscbshf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sufxvd.cn/Article/details/gtyyhhkjxq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtamaeevmn.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gtvppknsck.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtnrvwvcyj.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gtmmlclbev.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtnnttmrws.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtpyswsovf.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtiybbecca.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gtgfslxlnn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gtbntwemzg.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gtimosfmtt.html

[B14] 判断值是否在集合内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgyymvep.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxinkj.top/Article/details/gtvrdjvaem.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtpmampebt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtcdgwjvps.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtieitvame.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtgbrenraz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gttvvtywgk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlkxxezy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtfipmfwew.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gtetoenrvx.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gtmevvgpnm.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gtrxrzkvnh.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtgfzjpatw.html

TS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtsmupahkf.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtrgrhabid.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtabdwqzgi.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtvidjvioj.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtziifzjhn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtihjjdawd.html

Py:   if not data: return
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhmwrpvb.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtlqdjanga.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gteyqnlcea.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtoxlqubay.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtveqpqkku.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gtqxawmgye.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gtcshqcubb.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtjgpepare.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcuxeoimw.html

C. 函数与作用域
来源：http://dali.316326.xyz/Article/details/gtfubtrtkj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtpwubbnpo.html

[C01] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtmjhouwrw.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gtdbtzlvjd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtyebdrpfr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtmhsnxubi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtwwlabwhz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtilhhfsph.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gteanwbbmt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gtngyylyjf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtfmugvnxm.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gtezrbjqzl.html

Py:   def greet(name="World"): return name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfjaloah.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gtzbhjlodw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtffiolofe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrywvetu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtteqsfxzn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gtifoqpcve.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtdbailviv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtqfbbzqye.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjgvzzjc.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gtcwtqulkc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gttazkqjbg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtsdytaqyk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtyodkkdvp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtsvkqgmiw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gturdfdwsg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gtcyhnyadn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gtgjlceqip.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtcjtuciwy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gtmetsscbv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gteogqsser.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtofklgmgf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtknwildam.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtwaeyllqo.html

Go:   // 无：用配置结构体参数
来源：http://dali.sxryk.cn/Article/details/gtuaxsvrkq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtvrhwlglt.html

C#:   f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtmmsvcikw.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzhtfcrx.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtivvrrohg.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtzfemcuad.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtueyifvmo.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtscxreasv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtnbvahpmo.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtpznuncta.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gtntjezfvy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gttsbuzkxu.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gthzvqksov.html

Py:   square = lambda x: x * x
来源：http://dali.wangdashe.top/Article/details/gtkrxxdpdg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtlqxmcxmk.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtdgslihvr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtgukwflrn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtryoxhdlg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnikxwayf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gtriqnfger.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtyauwjoch.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtnlasnlha.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gtqvjbeiol.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtfvzasrdm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gtolohhejz.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtotvxuedd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gthhxewzfb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gtcrkrvymj.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtgplrnqls.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gthuuhtkdk.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gttixkwsvw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtfzvkpqkj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gtxyhifhgu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtbzwnafqw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtotxwduhy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gtjvvbnwbl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtyzsshsqw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyduoguhy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gthqvpsidq.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gtvqzktoyr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtrhnbugar.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtdvihtnsy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtqpayxwjh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtiahsjbem.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkjvzqek.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtmucusstn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtexzdkcii.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtkshpfdkt.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtyzmljuad.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gthofkdjsh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtsoqifbcw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtasuucuio.html


<!-- 参考信息 -->