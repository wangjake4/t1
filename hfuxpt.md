代发 wailian999

Ruby: a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gt2mfbbrmna.html

C#:   (a, b) = (b, a);
来源：http://dali.hfpthk.cn/Article/details/gt2mwajiszi.html

[A20] 读取标准输入
来源：http://dali.jianghu66.top/Article/details/gt2mevdswsd.html

Py:   name = input("请输入：")
来源：http://dali.wangshuangyany.cn/Article/details/gt2extogjfa.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gt2jhqixupu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sysykeji.top/Article/details/gt2ekgjerhy.html

TS:   // Node.js：readline 模块
来源：http://dali.smart0.xyz/Article/details/gt2eotiaocr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xylfe.cn/Article/details/gt2jakqdyfe.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkobfhcw.html

Ruby: gets.chomp
来源：http://dali.ehwqpu.com/Article/details/gt2xriyvenl.html

C#:   Console.ReadLine();
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmdmtpuo.html

[A21] 保留指定小数位输出
来源：http://dali.316326.xyz/Article/details/gt2rgwwvxmh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.redwolf501.top/Article/details/gt2wamqkcdb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gt2ndsgfnbc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iptdcaax.html

TS:   (3.14159).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gt2zbhtnopf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gt2fcggxfwd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2ztvdnyce.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gt2dkggocqa.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhengqikj.top/Article/details/gt2okquhhqe.html

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gt2ocpjupyj.html

Py:   len(s)
来源：http://dali.haohaochexian.top/Article/details/gt2endmfmdl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.9152youxi.cn/Article/details/gt2vvushirp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2idqsywhq.html

TS:   s.length
来源：http://dali.havefunace.top/Article/details/gt2nqvpwasi.html

Java: s.length()
来源：http://dali.sweek.top/Article/details/gt2aqxdfbbq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iuhyiliy.html

Ruby: s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcciumty.html

C#:   s.Length
来源：http://dali.yuanzhike.top/Article/details/gt2vkzrgxpw.html

[A23] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjfrjtpr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.havefunace.top/Article/details/gt2loryaryl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.smart0.xyz/Article/details/gt2nfkecsgt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gt2uunhafck.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gt2qfddfwrk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gt2ujxuskux.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cucudq.cn/Article/details/gt2cmammmwq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hammf.cn/Article/details/gt2ywxmcicu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jianghu66.top/Article/details/gt2xfzhouui.html

[A24] 去除首尾空白
来源：http://dali.chenzaomai.com/Article/details/gt2wrvcioaj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wijxpmyn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dashuyun.cn/Article/details/gt2ugvtctsx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hammf.cn/Article/details/gt2nepfqoip.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gt2jakvsdze.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ybcxt.top/Article/details/gt2efsbztsu.html

Go:   strings.TrimSpace(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2ohzkyelp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhixingplan.top/Article/details/gt2lwwzmlsr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sufxvd.cn/Article/details/gt2mzdqmqxh.html

[A25] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gt2fzuhxnjl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258.top/Article/details/gt2xmnmrtql.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yueranfly.top/Article/details/gt2ghjghzus.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nazksymb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gt2jftgnwpm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hammf.cn/Article/details/gt2xdpoyymd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kygkpopb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gt2ecnsosvj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gt2rwoctyrq.html

[A26] 类型转换总览
来源：http://dali.xuanzx.com/Article/details/gt2uvltrckh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj202588.top/Article/details/gt2jcrhqcvf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gt2davwrkzn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gt2ocrqgkek.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yonumen.top/Article/details/gt2azvcrapb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiqzmtfd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ydzc1.top/Article/details/gt2jjlkywbh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuanzhike.top/Article/details/gt2eqdgnbek.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gt2varlmltr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2tzlawtfe.html

B. 流程控制
来源：http://dali.c1oappe.top/Article/details/gt2xaojcakw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2fnmgkdrh.html

[B01] 条件判断 if / else
来源：http://dali.ivvv.top/Article/details/gt2vpblvtgy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.svipenyu.cn/Article/details/gt2fgcpfoee.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nabsjpps.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2juhdktqf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2ipetlvmh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2nouvkdhj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqhxeimz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gt2hvfkzibu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gt2nqkzlxup.html

[B02] 多分支 else if / elif
来源：http://dali.iojbl.cn/Article/details/gt2rlukbedq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.andypj.xyz/Article/details/gt2zdbfxcjl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xylfe.cn/Article/details/gt2vukggupy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gt2ilgsuqpj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gt2vhhsiwnb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gt2inubahwo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cucudq.cn/Article/details/gt2zjfxnsxy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbfpxzrp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2ozbszabh.html

[B03] switch / match / case
来源：http://dali.zhengqikj.top/Article/details/gt2tllfatwx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ydzc1.top/Article/details/gt2khlhkmsu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gcctrubj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2rclxyqfr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2qqcjjphh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2arkwmije.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cheryme.top/Article/details/gt2lvcekrxf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xinyue.icu/Article/details/gt2zmgevewz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cucudq.cn/Article/details/gt2qvxrwiiw.html

[B04] for 计数循环
来源：http://dali.316326.xyz/Article/details/gt2bqsjzauz.html

Py:   for i in range(10): print(i)
来源：http://dali.dashuyun.cn/Article/details/gt2vhopofju.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crwbnznz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2udfjvvfa.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gt2qmphouad.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2zwkyarip.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aizwys.cn/Article/details/gt2ytfqpykg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgufenzy.top/Article/details/gt2fqurgoga.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nthmohba.html

[B05] 遍历数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gt2cwcyrdkm.html

Py:   for item in arr: print(item)
来源：http://dali.havefunace.top/Article/details/gt2eqhvmxtz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gt2meemhami.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2lvsvzedy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xunzujqw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nwbrower.top/Article/details/gt2azfrjchw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shuidangran.top/Article/details/gt2juwazudg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.iojbl.cn/Article/details/gt2hqxduxts.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gt2xriebvqh.html

[B06] 遍历字典 / 对象
来源：http://dali.hfpthk.cn/Article/details/gt2okdwehqn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hywenlv.cn/Article/details/gt2nwuqonvc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wygzpgki.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gt2kjzrepdo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2vjlpcvaz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jyoumei.cn/Article/details/gt2jcemvaao.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyqvamoz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnxiangtu.top/Article/details/gt2lptpoask.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gt2gwenfgfq.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2htflmexs.html

Py:   while i < 10: i += 1
来源：http://dali.zycfv.cn/Article/details/gt2wdbhulyu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2kayntqeq.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2sqrfsjij.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2ztgwwpmw.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2epfbcehu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxuanxn.top/Article/details/gt2hqrewedo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gt2pweegnof.html

C#:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jolfaxja.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gt2oijdpkmf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gt2onanmlyx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2awenvmru.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2lylqmixv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2dffvmrsh.html

Java: do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzloqjpo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jiagoushi.top/Article/details/gt2bfzjcnme.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gt2doemqfaf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2capsprin.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gt2yforiemn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gt2oufnarld.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2imbxmamo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2rcilucnl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2tvgxlzbj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cdddtxnv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gt2hoxofjbm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.kuanghao11.cn/Article/details/gt2iuyoqkad.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2yqhmjknd.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2ksstzyeu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.smart0.xyz/Article/details/gt2bttdooxo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gt2loitkqlx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gt2hyybczpm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gt2egtixcgd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xbgenpmp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daria6918.cn/Article/details/gt2whchojex.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gt2knpiwqou.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqqatdww.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gt2ogbqnabi.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gt2pubwtklc.html

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2xpzoerqq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gt2hutmtsxg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gt2obngmvxl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gt2grcffpsr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gt2hwtslqbr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gt2tvppporv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgkiiftw.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gt2wpoxqals.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gt2aqnuwbpf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkphjjmc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjjishvr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2iodrotmr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2pxmnidqg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2aljvvbtd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gt2swtmkxrt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guannengcc.top/Article/details/gt2rwdntnar.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gt2ahsmjltc.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gt2lzqjffjc.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gt2krslfeac.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gt2agbekdyw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2wdqymjvm.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gt2pvwtulbp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gt2mcxqbyrj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gt2xjvvlmbz.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gt2zlcqnmeg.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gt2kelwkyey.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gt2tbojbiro.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gt2zeyknhlj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2ecgjylra.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2xaycwplq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2hebrlyla.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gt2aosxjrgs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkubieqf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjqgglhz.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gt2iernafxw.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gt2extgbhqa.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gt2arqoksgw.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2dvvtnrxi.html

TS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2qngfuwvy.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2svmwijfu.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2qgcnrgei.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2bhtpoxam.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2irmxierv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnxiangtu.top/Article/details/gt2rxxakjav.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gt2jgsnsapd.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gt2rdmjufwy.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gt2bhnaphvg.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbfnevhw.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2jzbpbaxt.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gt2zzhwcfal.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gt2vrfwhrim.html

C#:   if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2mdegmhzs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2xmijzcee.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gt2dnyutcli.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2yknmavpo.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gt2vqsjpxom.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2nebkwrsd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gt2flnkpvoz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2oynjikgv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2uoranetc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2jgkpezol.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gt2fwwahxjf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2nxhuzpca.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2ubimhvsy.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gt2ysqyfvhk.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2vqetehed.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gt2kuyxuamo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2ievnwlnl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2zxtpmjuf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ehwqpu.com/Article/details/gt2yifqupcr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gt2pgotybhx.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gt2dcppxohp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gt2vbjlowmw.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gt2pctpxejw.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gt2nxfexrsb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gt2teinstjp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsrbsrd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gt2qasontop.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2omfghxma.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gt2vpntjtsf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gt2yjzaowru.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzgjiuit.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gt2tztjoxyk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gt2hhjqubvo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gt2lohffkir.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehfeqgxv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2prfbrzti.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzyjkuw.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gt2zazewaqh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2lalfopti.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2kzzrmeuc.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gt2vyfvwyfl.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2odkflogz.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gt2qybrrdja.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2jskqsyyv.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqivczeo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gt2wffbzthp.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2pnhqomiq.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gt2zeoveuzp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gt2nnpwtyeq.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gt2otjekcrw.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gt2wnswntwd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xjfrhksc.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gt2nkljaioz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2tarojujn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbkyubfp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gt2vdhvpoug.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gt2xacreugg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2hpspjaoh.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gt2bzaeixyf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gt2onyviyhm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzilnqze.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gt2adzgplew.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gt2tvhctodg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gt2nsusfpex.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yonumen.top/Article/details/gt2dqfgbmhh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2rglchktw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gt2rvxiabgz.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gt2wzbiorbp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvdsakxn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gt2kgtawovj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2qttdbvxt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpkygynz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gt2xcmeaxfo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gt2dxbopuun.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uynpojnc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2elcjubgk.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gt2jzfmtllw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjuoyhil.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2lqgltfgj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gt2chyvlwnn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2nbzbetha.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gt2hwfgrxvf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2xlacqjrn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2nifiwhoi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gt2ytldmpyn.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2mdrhdymb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gt2yrenkpco.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuxming.cn/Article/details/gt2ztctyzvt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2rbxqydtf.html


<!-- 参考信息 -->