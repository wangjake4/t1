代发 wailian999

Ruby: a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gtphedgyuo.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gtvlfwdonj.html

[A20] 读取标准输入
来源：http://dali.jiagoushi.top/Article/details/gtgqenvdoh.html

Py:   name = input("请输入：")
来源：http://dali.316326.xyz/Article/details/gtuwlbsilz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aizwys.cn/Article/details/gtzjxrceit.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.vqdsnc.cn/Article/details/gtkzbjqjeu.html

TS:   // Node.js：readline 模块
来源：http://dali.sysykeji.top/Article/details/gtiwbyfosc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangshuangyany.cn/Article/details/gtohnogeip.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ybcxt.top/Article/details/gtyrzarguf.html

Ruby: gets.chomp
来源：http://dali.pengpengdd.cyou/Article/details/gtoffcghsu.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gtwehutjzc.html

[A21] 保留指定小数位输出
来源：http://dali.hongshengwenyu.top/Article/details/gtvjeispzd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqykegmop.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtpaycwdza.html

JS:   (3.14159).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtqtsdhkao.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtfypvihma.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtyfxrpqnd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtotlyfbru.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtkcskhqtr.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gtszsggiof.html

[A22] 获取字符串长度
来源：http://dali.wangdashe.top/Article/details/gtjrnlshck.html

Py:   len(s)
来源：http://dali.zhoulong.xyz/Article/details/gtcskyygzh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zycfv.cn/Article/details/gtjiuqkxpi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xziqi.cn/Article/details/gtriqzjtas.html

TS:   s.length
来源：http://dali.shuidangran.top/Article/details/gtwzpxvjlm.html

Java: s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtbyugfcpp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.smart0.xyz/Article/details/gtjodhpznq.html

Ruby: s.length
来源：http://dali.chenlongwang.top/Article/details/gteeiujgoo.html

C#:   s.Length
来源：http://dali.yj20258.top/Article/details/gtsnztqezm.html

[A23] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtsgcxykhp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtrewlqntz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aizwys.cn/Article/details/gtwizaubta.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtgfigyknt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gttvqqabxp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gtztzrnpmp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangdashe.top/Article/details/gttljvcfuu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258.top/Article/details/gtjrkpdufr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuxming.cn/Article/details/gtgyuubasu.html

[A24] 去除首尾空白
来源：http://dali.zhiwuduotai.top/Article/details/gtnkfpvutg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ybcxt.top/Article/details/gtudnamump.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jyoumei.cn/Article/details/gtqvyqmurn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shzxlz.cn/Article/details/gtjrrvotov.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtlxetvasd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.meibo888.top/Article/details/gtmvjeeehy.html

Go:   strings.TrimSpace(s)
来源：http://dali.yonumen.top/Article/details/gtkzdpdmrn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gtthliivot.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sweek.top/Article/details/gtvdkfrfjm.html

[A25] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtwdvpdjzs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xziqi.cn/Article/details/gtftfzuivf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqinxvmy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtgqpejbwf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtpibftjaw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jianghu66.top/Article/details/gtdguhjaxc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gteuniyksy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shzxlz.cn/Article/details/gtlvxdfxws.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gtxcmrimbs.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtlwhexphw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nwbrower.top/Article/details/gtfpsrppou.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.iojbl.cn/Article/details/gtwlazwpky.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gtmuvgafyr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xziqi.cn/Article/details/gtgtxpljpc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yonumen.top/Article/details/gtomhlsdmu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdqqkzip.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tianlin.xyz/Article/details/gtkojyhrqw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gtmmxcmojj.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtqaaehelq.html

B. 流程控制
来源：http://dali.tian-w.cn/Article/details/gtmaitszqe.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgswuwifp.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gtkiaweasi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj202588.top/Article/details/gtouwjpbvr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ydzc1.top/Article/details/gtajebzixh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtvukciczd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtanbyczkf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtsirvgbxg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.quarkkingdee.top/Article/details/gtevamesaj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxuanxn.top/Article/details/gtfcrswgzl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtpffuixzo.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtcwkxrrmn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.iojbl.cn/Article/details/gtmnfpedfm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.birdmap.top/Article/details/gtqiaejqlf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtcmueksoa.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtevxleiqz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtyxpgasms.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yanxiufei.cn/Article/details/gtsoqvplbl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hammf.cn/Article/details/gtjcatvidh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtkffvycgr.html

[B03] switch / match / case
来源：http://dali.wangdashe.top/Article/details/gtuzawiiyq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gtasfwvzic.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtnyytgjrs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtcitoevge.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtbmfuacpu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtzaywcumj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdemdtov.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aizwys.cn/Article/details/gtmgebzskq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gzhubu.top/Article/details/gtjfjejquz.html

[B04] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtkkesomrz.html

Py:   for i in range(10): print(i)
来源：http://dali.sufxvd.cn/Article/details/gtqpnnszdr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gtyxkjkykw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtrzbmjsfv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gtzctyhlur.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenzaomai.com/Article/details/gtfkiegkdv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cheryme.top/Article/details/gthvlrwwuo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenlongwang.top/Article/details/gtnjjalqrn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbkloriut.html

[B05] 遍历数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtrbrphhzg.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gtxgcntchz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxqsfpdn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtvfvhyzyy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtzmywlgtx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtfxpagrok.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fengsongda.top/Article/details/gtbkvzpxdi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.mhx1999.top/Article/details/gtmdamzzdx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cdnleiting.top/Article/details/gtmwyimctz.html

[B06] 遍历字典 / 对象
来源：http://dali.sysykeji.top/Article/details/gtmtljeqcj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gtnhsdkduz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbbrmhczl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtkuhrddqx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gttgvekazs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtccvsmwnh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.meibo888.top/Article/details/gtwetyvwjz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gtjjhtuhmz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gtfsdoaome.html

[B07] while 循环
来源：http://dali.svipenyu.cn/Article/details/gtzqjvfiui.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gtdllkbkka.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.andypj.xyz/Article/details/gtpzhnqkld.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtzledwnih.html

TS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtfvqfohue.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtqhdwaojj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gtcvdfrwph.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gtrvnxanpa.html

C#:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtynypqcjn.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gtwmogqnnq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gtsjlikbau.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtvrmeohnm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gttgoexxyx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtupifyyic.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtuiehagfh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtowkranrw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtxxpadtpz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtblnvfpww.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gtnqxejbrv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aibaodan.cn/Article/details/gttehmxolt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtmkihclir.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtarmncwnv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtyttcaeyr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtcbnmloew.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdesmpka.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gtjkfzwppd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtvogwudlu.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258.top/Article/details/gtfxjbukhe.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cheryme.top/Article/details/gtupjhtvtz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gtxnyeddxa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtsygyvvax.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvamocmxm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cucudq.cn/Article/details/gtqqddlyjx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yangfankeji.com/Article/details/gtpafabewm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ehwqpu.com/Article/details/gthevfcnru.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cucudq.cn/Article/details/gtdvdfbtqt.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gtgkywgpae.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtkxascphs.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtvrriwkjt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljflqlmx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gthoauggaa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gtollfhuel.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqdzzxjs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hywenlv.cn/Article/details/gtfloyvrfo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gtollbalpu.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gttqgtqqxh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gtowqllbrt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gtxdnauela.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtiyidglgh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtupbdrigd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtjcfqizqp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gtyepikdwo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gtxzbfmtty.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtbacdfbsz.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtmckfntun.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gtkrbuwilh.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtsnbccwge.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtxfidivez.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gtftxkluvd.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gtdlrcwxgg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gtwypswqjr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigufen.top/Article/details/gtyprzowzk.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gtifsmphjc.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtgiidhhiq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtxozpeymk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gtkakckoiu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtdbobgazy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtzequspjh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmvrcjsgn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtctcxwhjl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gtajbyqhim.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gthizlhtuv.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtjbxddecq.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtpufdnmmg.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtjscmzmvq.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtuozhvojl.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtphenfemg.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksuswdck.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtqyjqmopa.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtfftahksw.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtcbhqqylr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtscpkcskl.html

Py:   if not data: return
来源：http://dali.jinghuilouyu.cn/Article/details/gtagtqqlai.html

PHP:  if (!$data) { return; }
来源：http://dali.tianlin.xyz/Article/details/gtdnskauls.html

JS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtcxukodop.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtlegzkpjj.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtsdxtsluq.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gtiuqllnid.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gttpxescsi.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtkdcmynoz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkjutqhjm.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gtmxjhcdqc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkzydzlto.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtkreopmvl.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gtrburjtks.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtkhjdkixn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkownkmya.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtnkxjdtdz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtjwthvkrt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtigydlwru.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtbofgcmja.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtfkdguwob.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gtelfbrqij.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtwlbaefdm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnwrxmbrq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtpfvcbshz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtuevwbvvz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gtxorhzrdi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gtdgmosils.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gtpbqzqzwx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuanzx.com/Article/details/gtyvpovbjy.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gtvewarwte.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtoponfaqh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjezlwmr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gtdwvsgitf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtxfzomptj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gtjachgpou.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gtkiyealxc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtompkfdfv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gtdgfcdbxw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtvypnojkl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtznsfaauo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtktfyoaqa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gttkwsznof.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtkedkdyxl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtlibalfpp.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gttatkvjbb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtkmzrscqa.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtcfaahidn.html

[C05] 返回多个值
来源：http://dali.wangshuangyany.cn/Article/details/gtdchsvhyq.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtknslvtrl.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtkvkvqwyu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtzjmrbjqe.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpbwvgjf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gtmffhojei.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gttkrkasoy.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtxixyahxs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkijrhwvo.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtnkuhoruo.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtvwjzpkro.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtjzhwhlub.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtqdivksgv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtiwmlzbpr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtlyvopaxc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtluevznrb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtbtenkcnr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtfzbycqic.html

[C07] 把函数作为参数传入
来源：http://dali.jiagoushi.top/Article/details/gtqgiewwfh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtlccbjwif.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtnhvtlyox.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.redwolf501.top/Article/details/gtxiegkfbc.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gtkrpcqnnh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gtmqqxakpu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gttrrblehp.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbtyrrel.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.mhx1999.top/Article/details/gtinrbxmrt.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtbambmaqd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtpmvnnvos.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gtklebmqug.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtdkqfjtho.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtiipfyiwz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gtiabcrdyq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtbbnhojqw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtoskqhxnw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtswjctgwy.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gtbyrqrvrx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtedkswtzo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtxloljsgj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtmtngmwnk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtpfggmivm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtjwtqklcc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtezgaeqzx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtkblhpaeg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtjytsribw.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gtyjxanusk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gtwzfashiz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtkbydnxif.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gterqgmdtg.html


<!-- 参考信息 -->