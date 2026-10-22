代发 wailian999

Ruby: a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gtxjjatgzx.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gtehzelrkz.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gtacbrmawb.html

Py:   name = input("请输入：")
来源：http://dali.kuanghao11.cn/Article/details/gtvckccaln.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfuokvxz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinyuanbaomall.cn/Article/details/gteouojuyw.html

TS:   // Node.js：readline 模块
来源：http://dali.wangdashe.top/Article/details/gtlhzzvejb.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shangyingyoupin.top/Article/details/gtcfqeeyvq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangshuangyany.cn/Article/details/gtvukgjyxc.html

Ruby: gets.chomp
来源：http://dali.zycfv.cn/Article/details/gtxkxheuko.html

C#:   Console.ReadLine();
来源：http://dali.zycfv.cn/Article/details/gtwfcuppap.html

[A21] 保留指定小数位输出
来源：http://dali.chenlongwang.top/Article/details/gtzkvoxzci.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhengqikj.top/Article/details/gtnwlhkqqp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgnxmteh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtpuphpjcb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtntaqukgi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtcwwohira.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtkgyfcwxx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtfrqstmvr.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gtsahcvgwp.html

[A22] 获取字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuzoiuox.html

Py:   len(s)
来源：http://dali.c1oappe.top/Article/details/gtjmytglcc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tanke756.top/Article/details/gtqgoekrvh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.c1oappe.top/Article/details/gtyxizxxib.html

TS:   s.length
来源：http://dali.gogol.net.cn/Article/details/gtkrsfkhok.html

Java: s.length()
来源：http://dali.iojbl.cn/Article/details/gtrmjpeidn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jyoumei.cn/Article/details/gtqnzsamdr.html

Ruby: s.length
来源：http://dali.316326.xyz/Article/details/gtepbelvcn.html

C#:   s.Length
来源：http://dali.fengsongda.top/Article/details/gtbvnxyaqo.html

[A23] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtadydaprm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtpwacunmm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sxryk.cn/Article/details/gtnesyorwr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtgubhwsgz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gtonkpervd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtreepwzen.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.redwolf501.top/Article/details/gtsouepbaf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtbpdvqtgx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangdashe.top/Article/details/gtzmdahdrb.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gtyesondzi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.quarkkingdee.top/Article/details/gtpuiwomom.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.bjfxy.top/Article/details/gtfnozfjif.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.bjfxy.top/Article/details/gtrpwvljum.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtjoyzrqlw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sufxvd.cn/Article/details/gtdgvuhsbl.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuanzhike.top/Article/details/gtabbdidjo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gtzclrevyv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gtobuppbdd.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtqnteankz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.smart0.xyz/Article/details/gtveigbwff.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gtjkqdqyen.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gtlcsrtpay.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gtmidxrihc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gtgnrjkfrw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtpzjzhgrr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxjmhduf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtukisjned.html

[A26] 类型转换总览
来源：http://dali.zhixingplan.top/Article/details/gtvpqckocs.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxuanxn.top/Article/details/gtpszajivp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gtsfpvyflu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guannengcc.top/Article/details/gtzjigfksr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ppjwa.cn/Article/details/gtsfniagbw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cheryme.top/Article/details/gtskfhwkia.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gtxlxhhnyc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gtiretanru.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtljkoygif.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdnskrzep.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gtimkkxghy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsvslgabp.html

[B01] 条件判断 if / else
来源：http://dali.9152youxi.cn/Article/details/gtlqqxkcdz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gtlcjawmff.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkuhdavjm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtdsvvmzss.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtwxgnrvrk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtncofbfzh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gtnycmihwm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtqfautfsu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gttbrndfuj.html

[B02] 多分支 else if / elif
来源：http://dali.ppjwa.cn/Article/details/gtylkcnehe.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gteqkuxnpz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gtfnhwixrm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtkhrmkjhc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtbcrnxzja.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtnsfttnfp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxuanxn.top/Article/details/gtsnzsdrpj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cdnleiting.top/Article/details/gtonlvquml.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtjttqwktw.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gtifbgpzdl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgufenzy.top/Article/details/gthqvifokp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtwqucsews.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtbszjiypy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtxbogujyz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtyrzqrrzm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtlogbmasx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gtgfcxxhnb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtscgcejkn.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtwdemlodj.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gtzseqjxvd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gthygcidge.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gtxawencij.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.iojbl.cn/Article/details/gtmgpgjukk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gttqhbjazs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gtcftypdaj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hfpthk.cn/Article/details/gtnegxmpor.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gtnufloegz.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtfqdrzsde.html

Py:   for item in arr: print(item)
来源：http://dali.yuxming.cn/Article/details/gtairzrtnu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuxming.cn/Article/details/gtqbigsamu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtnipgbhit.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gtyxlxknxc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ivvv.top/Article/details/gtseuvgcuy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ybcxt.top/Article/details/gtgekfzgkf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.birdmap.top/Article/details/gtoqsujmtb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.smart0.xyz/Article/details/gttgcjjglq.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtmdqdueru.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtjocyji.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ybcxt.top/Article/details/gtgpyitpgl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gtlwwjuvih.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gtmwctpkzj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gtpqqetuon.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtrncfhuhf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gthnlpmura.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daxiang520.top/Article/details/gtkmqrtkop.html

[B07] while 循环
来源：http://dali.zhixingplan.top/Article/details/gtwtizhztr.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gtolxrwthq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gtdfqopfzw.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtwluboidt.html

TS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtecpecgct.html

Java: while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gttpytjuhe.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cqqwz.cn/Article/details/gthilstrxg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhiwuduotai.top/Article/details/gtgxswqnbr.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtrbtijxsh.html

[B08] do-while（至少执行一次）
来源：http://dali.gogol.net.cn/Article/details/gtfqafaudj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtvrfdpfqd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtuulwhvja.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtiadznjbs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtmvmthqlv.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtsxtgiwad.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtqcapuwkr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gtfmnrevyg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtkpbnnvwm.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gtttnwqeeb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gtmhmldbgh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtfmnsjpov.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtnblrtbun.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtvvszrrua.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gttyfdnlks.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtycblclsf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gtbojqkwne.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtydaxuaun.html

[B10] 遍历同时拿索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmonrejwk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hfpthk.cn/Article/details/gtywskbveh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gtgetlofil.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpswftte.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gtlsdurfje.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtdpvrysdu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gtvlyhqxrl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnzsishc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.redwolf501.top/Article/details/gtrxhundtk.html

[B11] 生成数字序列 / 区间
来源：http://dali.yanxiufei.cn/Article/details/gtwgxwqyix.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gteqdwlezf.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gtbnhxolyt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtzkykvlqc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtmbordtil.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtptiwwjry.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gtxovwvlxi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gtnxqrwwbj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtstitvzuc.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gtqudnpgnh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtjxxrrorb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtcwskdntg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtydmtetff.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtenexbjgx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtorybshwk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gthnthftbb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jiagoushi.top/Article/details/gtzixbzazh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gteyjruubr.html

[B13] 判断是否为数字
来源：http://dali.yj202588.top/Article/details/gtxqltmkgh.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtcndghviy.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtqfqtcoyk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtyjflajdp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtqxmedxwq.html

Java: x instanceof Number
来源：http://dali.yanxiufei.cn/Article/details/gtmgmxfuut.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yongpay.top/Article/details/gtugzhjbul.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtukycqskd.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gtmpnwupwa.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gtkzixnhmb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gtcaackone.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtoolgjwuf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyyrzreq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtmdcknrdb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gtewndlixl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtqwynbyqn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtsvqpflaa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtlvwhrwhy.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitjegshd.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gtxcgbnrsg.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gtzyqlxpbw.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtgwnzdaja.html

TS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtptrawfeg.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtqhybjvio.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtvrporhbo.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtigbagtgc.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtkdvhhkbl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gtbccptzzp.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gtjmvjmthj.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gtzaeclnqq.html

JS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtuvfaadiu.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtmjkxluaf.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtycbujtuj.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gtgulndmqa.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtthwiflmt.html

C#:   if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtspkerknu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbyoyvbjz.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqjuhsfs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwycxmono.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gtllejmqma.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtvhengddr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtflqkfrhq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtsprorsit.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtvsxaruue.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxrkkyma.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gtmgmmhirp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gttfofaklv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtorjpkvmc.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtlqckxrte.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gthiwkpkzl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gtqdqqixhn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtaowljdum.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtlobytjsi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gtyorelasa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gtusxitlfc.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtdijazwpg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtralgvpba.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gtdkrwpuak.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtyetbhlex.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gtljjhatcp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gthnqjcoaq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtuprmtbdp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtguxmxvvw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtuvrctuhx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cheryme.top/Article/details/gtnklgonez.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtockdtfmv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gtogqlmsbw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzzvcvxve.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtylhiuour.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gtgxjdcfxx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtjfpehazs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gtskorylug.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gtfgbfqdfk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtjadclyau.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtboxeyibl.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gtzqzzunri.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtllbbgtrk.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtmwxllkgu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtvtaefglp.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtzmclzvqz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gthejurzqs.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyensybkw.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtadfurwsb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtsyjhxxaj.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtmqgqshjb.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtpfocerle.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtjtocpdik.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gteyqetoer.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gttkevqhyz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gtpamxsbtu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtsetwtjli.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtbdkxklwd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtvafzsihd.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvojltll.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gtldjojnnr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtfoxkmxft.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtoxhsaicp.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gtpaqcbxwv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gtvbrazgmy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258888.top/Article/details/gtojhmpdks.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtdegplgxa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtqjgepkdn.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtjqbncrgj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gtgwbaderf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gtgncxfjbt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtlxtrtlga.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtidybhljg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtqmpyqfig.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtxmvwhzol.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtamrzxpnj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtzyuryfcz.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtqmvsnuhc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtsrgekwqe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gtyoqeyxyd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtixepsutt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtfmqpzydr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtybueenaz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtriqqodfg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtewrzazug.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gtyeuoqgyk.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtgrodreet.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtxceznmje.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtdqdhgbno.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtqgsmuvkd.html


<!-- 参考信息 -->