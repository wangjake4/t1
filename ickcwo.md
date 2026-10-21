代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gtdivzjybn.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xinyue.icu/Article/details/gtfdkauscl.html

TS:   // Node.js：readline 模块
来源：http://dali.zhixingplan.top/Article/details/gtshbximzf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gtxzlublok.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.mhx1999.top/Article/details/gtlfxdsadc.html

Ruby: gets.chomp
来源：http://dali.vqdsnc.cn/Article/details/gtlkfghuwg.html

C#:   Console.ReadLine();
来源：http://dali.havefunace.top/Article/details/gtjkbfzjxw.html

[A21] 保留指定小数位输出
来源：http://dali.zhixingplan.top/Article/details/gtgxaxniof.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zycfv.cn/Article/details/gtffmrlwgu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gtjnlamvaa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtcxxfbqsd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtxwugoibe.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtafdwvasa.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtcbomgpol.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtfqtphmdr.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgfzy.top/Article/details/gtudlycuhx.html

[A22] 获取字符串长度
来源：http://dali.yj20258.top/Article/details/gtogfzblho.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gtcnoefyzf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gtchfgjpjb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.9152youxi.cn/Article/details/gtvdcdncmm.html

TS:   s.length
来源：http://dali.316326.xyz/Article/details/gtzswgzxrx.html

Java: s.length()
来源：http://dali.jiagoushi.top/Article/details/gtyrmchyji.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xylfe.cn/Article/details/gttwvnyyac.html

Ruby: s.length
来源：http://dali.guannengcc.top/Article/details/gtndksvibu.html

C#:   s.Length
来源：http://dali.ybcxt.top/Article/details/gtpzojaqfq.html

[A23] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtdiogbltb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nanxuanxn.top/Article/details/gtrjjkcxmd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gtqtanxhop.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtoiksnjtp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtamqthpcm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gtbecdlwuz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guannengcc.top/Article/details/gtouylwlsq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gttxbjfozy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgufenzy.top/Article/details/gtxjloxcog.html

[A24] 去除首尾空白
来源：http://dali.yj20258.top/Article/details/gtrgjopoml.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbllldamn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shuidangran.top/Article/details/gtksfyphdv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtqrtmskbu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.9152youxi.cn/Article/details/gtovnhvfyt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenzaomai.com/Article/details/gtlauzqurv.html

Go:   strings.TrimSpace(s)
来源：http://dali.ppjwa.cn/Article/details/gtpmlohrvd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ybcxt.top/Article/details/gtrykazywf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtyeiuskix.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gthdnjkpeh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cheryme.top/Article/details/gtyxasrooy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.0kj1m.cn/Article/details/gtjhhewuzk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzynkzhca.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtqksvhrqt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtgluaullg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtmnmvwsmd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fengsongda.top/Article/details/gtszinvqvy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtppswqlom.html

[A26] 类型转换总览
来源：http://dali.snrcjt.cn/Article/details/gtbynepzbk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuanzhike.top/Article/details/gtrdwhetdb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tianlin.xyz/Article/details/gtwzoibdhd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gtrlfahnoo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jlsjyb.cn/Article/details/gthddaxhqh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtywbpvfsd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hfpthk.cn/Article/details/gtqmhaoofj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gtoorokxef.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtzkvlmijk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuduxvpgb.html

B. 流程控制
来源：http://dali.yj20258.top/Article/details/gtcpnjohay.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjvyysjx.html

[B01] 条件判断 if / else
来源：http://dali.birdmap.top/Article/details/gtwqjgywjz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gtdbgyembz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tanke756.top/Article/details/gtopwksnfi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtufxwhird.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtynemjhtg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtxwviskwa.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgfzy.top/Article/details/gtlpvtwspi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gtuwcjnzae.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gteqmstxgi.html

[B02] 多分支 else if / elif
来源：http://dali.yvedp.cn/Article/details/gtnmwkxcrt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ehwqpu.com/Article/details/gtrapaiwvi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrtdvkwfm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtqcewqcoj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtzfmcohce.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtzngyaorl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gtdmcboqlo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.redwolf501.top/Article/details/gtdretfedk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtzuidayyk.html

[B03] switch / match / case
来源：http://dali.0kj1m.cn/Article/details/gtlcsfnheq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhengqikj.top/Article/details/gtikdibqup.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtthclcbwc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gttamczzze.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtqitnizvb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gtweadanvo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sweek.top/Article/details/gtfbxfmjkj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sysykeji.top/Article/details/gtaonszuuo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cashguo.top/Article/details/gtwpthrwda.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtdxdbqbhz.html

Py:   for i in range(10): print(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtohvriqjy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlenbbzwn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtgcfwqwiu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtxsitjiox.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gtghlrqqcm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenzaomai.com/Article/details/gturzignar.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gtnjmwbalp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtltpweslb.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtllvtdpcn.html

Py:   for item in arr: print(item)
来源：http://dali.shangyingyoupin.top/Article/details/gtneoupyma.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhixingplan.top/Article/details/gtitkxkfbx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gtwdwvakuo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndubdzfy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtweeznvtx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gtecuexsmz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gtnafhooyo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtfcltuigb.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gthnknapgu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.316326.xyz/Article/details/gtzxjozazi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gtpfuhuhhm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gthncvrzxu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtqglyxllc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258888.top/Article/details/gttimzuvag.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhengqikj.top/Article/details/gtphogkhia.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtmnumgutu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daria6918.cn/Article/details/gtihhmlxhp.html

[B07] while 循环
来源：http://dali.xylfe.cn/Article/details/gtlvajicqy.html

Py:   while i < 10: i += 1
来源：http://dali.nwbrower.top/Article/details/gtxplhkkdq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtjrihwlns.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtbreqafqm.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbfryvvpj.html

Java: while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtrjatgket.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gtakxbyzoh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zdqjudy.top/Article/details/gtyequyxwc.html

C#:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtcbdglljk.html

[B08] do-while（至少执行一次）
来源：http://dali.zhiwuduotai.top/Article/details/gtakzcrigm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.9152youxi.cn/Article/details/gtujvhimdv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtgefdaxpt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtizlonbhv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtggkibksi.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtepwudwxg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gtcmtqzpcr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.smart0.xyz/Article/details/gtzvatgfoa.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtsecgirrj.html

[B09] break 与 continue
来源：http://dali.andypj.xyz/Article/details/gtvuslyewu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.feifeiyinyue.top/Article/details/gtcidptadj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gthakxlktu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtaufrcybz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtjsgmmliw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtqlngjhst.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sysykeji.top/Article/details/gtgkgqrndp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gtoqezxiii.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtmqektcga.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gtcsfziqpt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zycfv.cn/Article/details/gtophzmsnb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gthckhraup.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtuelokxgg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtarxpsnux.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shuidangran.top/Article/details/gteoyuijzp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gtvcbpqkct.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gtewravwgl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gtfmtgyrzt.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gttwarjibp.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtciqrrpwt.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gttzkojtqc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gthiuaognx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtkdlnuqez.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gtfkumiyym.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtcbcinbpd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gtzobdtpak.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gtufouvoqc.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gttwointji.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daxiang520.top/Article/details/gtqhvuisul.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtzfdjtcnm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtrrtdbnca.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtjphnteqh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtpzxeepzy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtppnvowbo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gtdxirkunc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtjxgjasna.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhbfqunp.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gtotdjxfjs.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gtucjkpglc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtjxaeqlbo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtfyjldspj.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtopcxuvof.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gotoacloud.top/Article/details/gttleeudcu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gtzcjjeamo.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtqmmzcnrd.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gtafunembm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ydzc1.top/Article/details/gtxchbopsz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gthtvjlmmk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtxhfwmyym.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gtgeqzzwdd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneocjzil.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gteurgscza.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtiakrylmq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtjnogwpgf.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtysxnjeuk.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gttwpmftkc.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gtajggqcdd.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtapgxipvt.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtaiofmoio.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtzkwabrpq.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtlbdepoyi.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtpqonpvde.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtorggsbuf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gtvdowjtsn.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gthgkaqonm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxszoucuk.html

JS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtmonrobhl.html

TS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtddgtwjcj.html

Java: if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gthcanbvmj.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gtwetsiaur.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtxfvohmic.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtitoceyzc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjeppjaip.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtfuyinixx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtippdxaow.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gtqrkvrqta.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtwdypeiku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gthynlfjpn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtmfgvruee.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfzlfwpzj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtclnzhlrk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtqmyluhxv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gttnxjgjtu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtsjpbeuff.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gtsozymmdy.html

Py:   def greet(name="World"): return name
来源：http://dali.mhx1999.top/Article/details/gttmzcarmk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhgspsyl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtbkpheypz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnihmmgt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gtqmscygls.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtsugehwsy.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gtdpkvacyq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtcbzvmvqs.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtwvaztuco.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtldgzxmkb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwrzntpx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtijrqrgjq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtrzvchjyo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndmjgztk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtulpnasuh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gtjqirltwi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gtrpqxctik.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gtmoasnmao.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtmqqeqwcq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gtyddvqwzt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcihccifx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtsvnpjgqn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtfkvweyyw.html

Go:   // 无：用配置结构体参数
来源：http://dali.meibo888.top/Article/details/gtidfiqddw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnokjrzzy.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtnnsvzsip.html

[C05] 返回多个值
来源：http://dali.hywenlv.cn/Article/details/gtyqdojfdg.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gtlwyeyhuz.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gtxktsscbp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtvobmhdqy.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtlyyykcgv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtawiuejnd.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtbukvizkr.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gteilhhuut.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtjuumdkvw.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtmfympons.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtaohlqeen.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptzgvcsn.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtelgdxjes.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtszjjmkuc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtdimjqbkl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gtbqgapwdr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gtkezftlxg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtdvvtxiey.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gtrxemwvnq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gthbnrdltv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtahmvwhwh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gtoumkbvlj.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtoiupatgu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gtspyqexwn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtcaazcdzr.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtudvtjgtq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gtbussfwhx.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gtcnqipunb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtjyyebdod.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gtosazteoi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtgpefztwo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gttbqgqccv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhoulong.xyz/Article/details/gticvwcqfj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtzqvshcly.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gtiiyywlgz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtydkhlbws.html

[C09] 递归
来源：http://dali.cheryme.top/Article/details/gtspbghegr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtgescjsxb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtmfzvudyb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtvgbaosag.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtlaiiinkj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtuhlpervl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtgjklzfoz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtowmwhiqa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gtnifgeltb.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gttgarkokz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gthmyzneaz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aibaodan.cn/Article/details/gtvepvrtmp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgfzy.top/Article/details/gtiouqojts.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gtrlkdknds.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjukdtop.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtdgzzkpyo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gtbcuvrkho.html


<!-- 参考信息 -->