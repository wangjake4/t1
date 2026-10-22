代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.andypj.xyz/Article/details/gt2ltnxfawt.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ivvv.top/Article/details/gt2rdcxwkyl.html

TS:   // Node.js：readline 模块
来源：http://dali.cucudq.cn/Article/details/gt2shdusobd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sxryk.cn/Article/details/gt2nzgkuhng.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnqfkpyt.html

Ruby: gets.chomp
来源：http://dali.jiagoushi.top/Article/details/gt2dgfdrkfk.html

C#:   Console.ReadLine();
来源：http://dali.cashguo.top/Article/details/gt2rfmmrrrf.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hszesbiz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwsvdxgv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxgysvvc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gt2suycbhiq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gt2eiynojwf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2tdaqxcte.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gt2fmlwvjjd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gt2oamqffhj.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258.top/Article/details/gt2aykrvshr.html

[A22] 获取字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2rprkcdij.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gt2dkqbpero.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gt2svkrlsyw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gt2ezmfpyyd.html

TS:   s.length
来源：http://dali.wangdashe.top/Article/details/gt2nqbpqjsu.html

Java: s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2ppkurwzf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.havefunace.top/Article/details/gt2qlbfixxd.html

Ruby: s.length
来源：http://dali.c1oappe.top/Article/details/gt2rqzuplxz.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gt2lezurfka.html

[A23] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2gvdlsyyg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.haohaochexian.top/Article/details/gt2adismgkt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.andypj.xyz/Article/details/gt2johjpxwc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gt2sjwscngi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gt2fuddhtac.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gt2zgioacrf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.svipenyu.cn/Article/details/gt2izucnzzn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sxryk.cn/Article/details/gt2wzrmwbab.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuxming.cn/Article/details/gt2ftevwhxk.html

[A24] 去除首尾空白
来源：http://dali.yongpay.top/Article/details/gt2agquskzr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.bjfxy.top/Article/details/gt2fcmrlriv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.vqdsnc.cn/Article/details/gt2qmeezlqa.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gt2nvtfltgi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gt2yommxkzf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jlsjyb.cn/Article/details/gt2irnobupp.html

Go:   strings.TrimSpace(s)
来源：http://dali.tian-w.cn/Article/details/gt2hupufmus.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.smart0.xyz/Article/details/gt2zudyvtur.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.316326.xyz/Article/details/gt2pbbxomxz.html

[A25] 字符串比较
来源：http://dali.316326.xyz/Article/details/gt2mjtlsnsf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvnkppmt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuanzhike.top/Article/details/gt2wboiaewz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbeygdoq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2mkvhgvxa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2hrpcdzrk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gt2vsbuxnij.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgufenzy.top/Article/details/gt2fgrgbgpw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gt2uzgzdcte.html

[A26] 类型转换总览
来源：http://dali.wangshuangyany.cn/Article/details/gt2uixidaiz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gt2sjxbfrrv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gaohongyu789.top/Article/details/gt2klvplcum.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sxryk.cn/Article/details/gt2anqkdjiw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.smart0.xyz/Article/details/gt2jrincztw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gt2jgpltjxo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sufxvd.cn/Article/details/gt2clnqouuv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cqqwz.cn/Article/details/gt2uzakzxcc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gt2gcdodorj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2pplujipb.html

B. 流程控制
来源：http://dali.sweek.top/Article/details/gt2cnecvbnd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2pqzftgop.html

[B01] 条件判断 if / else
来源：http://dali.hfpthk.cn/Article/details/gt2mfeiyvfx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gt2dzfscnif.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kpkbzkjw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2bbpcidid.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gt2kalzydri.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvzcofbo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuxming.cn/Article/details/gt2bsrkkxlf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.meibo888.top/Article/details/gt2dwzubljs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gt2eagczgdu.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gt2ixfeiwnz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.quarkkingdee.top/Article/details/gt2pwfrxhte.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mxgnbxvx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouwycarz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2tdlfhfkw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcsbzuf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yblqeqka.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gt2glruaxya.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gt2lpodjvmp.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gt2sxchxorq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xinyue.icu/Article/details/gt2crulysrq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gt2zlnxawyn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2zzsozdyu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gt2phgbcghr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gt2xuuvjiaf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gt2nafptkqo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhixingplan.top/Article/details/gt2sjbjwmsw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2iueyakgb.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gt2ruvnkcok.html

Py:   for i in range(10): print(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjyomjtv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gt2ssebksgl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gt2xwaizceg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gt2fbnqwdhg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2vrxwwtav.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gt2njhftedh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.meibo888.top/Article/details/gt2rfdifmpc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvronrms.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2mavisigt.html

Py:   for item in arr: print(item)
来源：http://dali.yuxming.cn/Article/details/gt2pnnihhdj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfnpugdl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmxtoxxw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gt2xalyarep.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gt2gofspiyl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fzhhl.top/Article/details/gt2yyagskdf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangdashe.top/Article/details/gt2whwfiyze.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxuanxn.top/Article/details/gt2nxnssazy.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gt2sbfamljq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.meibo888.top/Article/details/gt2eoepkjya.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gt2kqlqgngx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gt2rtuppdgu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gt2wmadxqev.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2mvkuxzpg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gt2oylbnosk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gt2firqgbtp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vneldoel.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gt2osmfpnpb.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gt2zomvlqet.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2utkrtsdl.html

JS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2imxdtxdm.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2givvuzfb.html

Java: while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2xvbwgwrr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.redwolf501.top/Article/details/gt2wnkpdxci.html

Ruby: while i < 10; i += 1; end
来源：http://dali.meibo888.top/Article/details/gt2ykyitkgg.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hawjmiuq.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258888.top/Article/details/gt2prgfcxwx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bnkfuomg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2vmggcebo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2fmbxzmzz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2wpioseky.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2qcatrvvu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gt2gdcziqso.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuanzx.com/Article/details/gt2pgyjinik.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2hfkvzbey.html

[B09] break 与 continue
来源：http://dali.haohaochexian.top/Article/details/gt2pdhnnptd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbisijoe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yvkthxbc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggocmgvt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gpejwhhd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cnxppuye.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gt2nvgjygqs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmjdyqi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2giqeargt.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gt2cpcjtzsg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cashguo.top/Article/details/gt2oeopyrkr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gt2qeadkzpo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2gexuiqpv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gt2duonqhea.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gt2qmwvvicq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gt2zynfbtrn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gt2wexfcshw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.kuanghao11.cn/Article/details/gt2tefiniyq.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gt2nqvwjhzt.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gt2dheqgyox.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2sxpbpnls.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocesyzlu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2vjkobkyr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gt2yrqdgqrr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvziqofl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gt2hdeqdxmt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gt2ewaxxkhp.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gt2swfqcksl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gt2hyuufmgn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxfwswkz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgntngmk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2wmsjxbxn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2qtguwqks.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilmegoin.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gt2atrkrpqe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gt2ocwosyqr.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gt2vvfhlkmd.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gt2ppqzsyhp.html

PHP:  is_numeric($x)
来源：http://dali.sweek.top/Article/details/gt2degsgevw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gt2ervdsxdm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2dktjbexm.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gt2ftqgysnc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gt2natxnxqh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gt2jrzjlpoz.html

C#:   x is int or double or decimal
来源：http://dali.zhongyouzk.top/Article/details/gt2dmzwgzty.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gt2khnicpcz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gt2kfczuvdy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.316326.xyz/Article/details/gt2gtnedisg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2dsmzunda.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2bltqszvn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2gsnumiry.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gt2mribhyoe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gt2zrueocij.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2humxcofc.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gt2nakzdouc.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gt2spaieesm.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gt2rawuneoo.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2aiokbjlg.html

TS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2wzsjkhdu.html

Java: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2nridttsa.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2oolfccdr.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnandbdh.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2pwysbidw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gt2lymynuly.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gt2zydneaqc.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gt2mgudqlhd.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gt2eleczbpc.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gt2melxpkqy.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2oxorkudi.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gt2eznmkykk.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gt2jahnvhan.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gt2goxxmyfk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2snzbmemr.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gt2xgghkrdr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btabfpab.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2xmxzvlbh.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2xdlbaupj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2paerricw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2aynkqpgb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2glytpkdj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2qjugvxta.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahuvvukc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gt2zgbcyfdx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2qrjdchdp.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2qvtpackl.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gt2yelbdrmu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gt2yjdynphg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2ebfusgof.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqznalvf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gt2zkhyqzvq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrupdqyu.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gt2iuqfjjxj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2khxowpqq.html

[C03] 可变参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ouekylak.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2wxtzxnjp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2pqzutvoc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlngygvj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2rvwxpvfm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rpljpfag.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gt2epoolohm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hywenlv.cn/Article/details/gt2pzvsgfvp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gt2bekigrzn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gt2braypeqm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gt2jouuiwlu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gt2kzcwyven.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gt2pdbowrdt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpbxxmnr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnqgllvr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gt2wmqjuxzo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2vhgurtxu.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2bqotlrbz.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gt2nwmktiug.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2evcvkaqy.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gt2uvztpthh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gt2aaupidvp.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gt2vbomhneb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzdzkiij.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2gjnvjygd.html

Ruby: return a, b
来源：http://dali.tanke756.top/Article/details/gt2ucsvwgta.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gt2kfxcntzr.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gt2vkynoqar.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gt2lxgxytcy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gt2qufqoykl.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2jyknljuj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2antrsmzb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gt2cctvcsnq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2xhefzaii.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gt2pegqfhyi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2oqlzpmye.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gt2jsuxhrud.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.andypj.xyz/Article/details/gt2zryajeki.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2hikrezpx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gt2jxumfiwq.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gt2rwxintze.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gt2bcdooqjk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gt2saiakrlt.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oboqxjog.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gt2itwhpxrv.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gt2diiugzgt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gt2mcasodxn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gt2puwblsyu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2iblfqhgx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2fidavzhe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gt2arhkxocf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bynvqyjh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangdashe.top/Article/details/gt2aoqshycx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2btsdnvdz.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gt2jeaxilus.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gt2akaftkdf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2bbkaeije.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2hrdleuwi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2zvwmsllk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gurudljb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gt2dobaqtkq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2qfedrxdn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gt2bwtxerhb.html

[C10] 变量作用域
来源：http://dali.tian-w.cn/Article/details/gt2eztwpvii.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vswrprni.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gt2nlwohhlo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2safgjprk.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2aptnatwr.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcppwszw.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gt2lqqeigsu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gt2hvdttpud.html


<!-- 参考信息 -->