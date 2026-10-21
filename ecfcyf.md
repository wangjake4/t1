代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gtjrdifvnp.html

Java: (int) 'A'; (char) 65
来源：http://dali.sufxvd.cn/Article/details/gtfuxabwhm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.snrcjt.cn/Article/details/gtcfoqngno.html

Ruby: "A".ord; 65.chr
来源：http://dali.pengpengdd.cyou/Article/details/gtjrgqvdgd.html

C#:   (int)'A'; (char)65
来源：http://dali.sweek.top/Article/details/gtrcugxtxn.html

[A19] 交换两个变量
来源：http://dali.daria6918.cn/Article/details/gtpqvyhgsz.html

Py:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtdxwhidtp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxuanxn.top/Article/details/gtyxewcjen.html

JS:   [a, b] = [b, a];
来源：http://dali.hfpthk.cn/Article/details/gtkpyfummg.html

TS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gtwpcduvmk.html

Java: int t = a; a = b; b = t;
来源：http://dali.gotoacloud.top/Article/details/gtugqjriwq.html

Go:   a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gtnmbaunsd.html

Ruby: a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gtizwdqtpa.html

C#:   (a, b) = (b, a);
来源：http://dali.shzxlz.cn/Article/details/gtyognveza.html

[A20] 读取标准输入
来源：http://dali.pycfn.com/Article/details/gtbctchwhr.html

Py:   name = input("请输入：")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhqtsgka.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ppjwa.cn/Article/details/gtyfvnccuc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.svipenyu.cn/Article/details/gtxwdtgpza.html

TS:   // Node.js：readline 模块
来源：http://dali.dianchejie.cn/Article/details/gtpygdsqky.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdolrjli.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ybcxt.top/Article/details/gtyronxozz.html

Ruby: gets.chomp
来源：http://dali.yonumen.top/Article/details/gthzoohmtu.html

C#:   Console.ReadLine();
来源：http://dali.redwolf501.top/Article/details/gtuwgexikg.html

[A21] 保留指定小数位输出
来源：http://dali.yuxming.cn/Article/details/gtkqqgnsao.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gtkkeqlhht.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gtoxertadc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfposezd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtzggucqgh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtzqrplekh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtcufjlhev.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtmpvgsion.html

C#:   3.14159.ToString("F2")
来源：http://dali.sxryk.cn/Article/details/gtldpurqmg.html

[A22] 获取字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtfmkjmfez.html

Py:   len(s)
来源：http://dali.tian-w.cn/Article/details/gthjnboeiw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cucudq.cn/Article/details/gtuwbakpyi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gtkodnyemh.html

TS:   s.length
来源：http://dali.cheryme.top/Article/details/gtdshgmfle.html

Java: s.length()
来源：http://dali.birdmap.top/Article/details/gtageuzqoi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnqzz.top/Article/details/gtmyyxjudo.html

Ruby: s.length
来源：http://dali.nanxuanxn.top/Article/details/gtyzhnpewd.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtpphkuize.html

[A23] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtdwaccqmc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tanke756.top/Article/details/gtrcxqriox.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zdqjudy.top/Article/details/gtgrrohhpd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtkoxzjhtw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtsmyevkdy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtphihwarg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.kuanghao11.cn/Article/details/gtuvlyyreg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtertlevgu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrkqvhdf.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gtkksgesyr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shangyingyoupin.top/Article/details/gtmeaopgzv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.pengpengdd.cyou/Article/details/gtcavxwaka.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnqzz.top/Article/details/gtiqxtvxjn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gtghdmamdb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gtaoikchva.html

Go:   strings.TrimSpace(s)
来源：http://dali.cucudq.cn/Article/details/gtxopbihgf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gtltvdcgsr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gtktxdxmag.html

[A25] 字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxguramo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gtaouobxjb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.c1oappe.top/Article/details/gttbyyqxwq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtabiyqqyn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ybcxt.top/Article/details/gtarfnwfxd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj202588.top/Article/details/gtaeliqnuo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtcyowsazz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tianlin.xyz/Article/details/gtmxwbsxea.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtueqpfmeu.html

[A26] 类型转换总览
来源：http://dali.jlsjyb.cn/Article/details/gtasyxqyvf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jlsjyb.cn/Article/details/gtfatidugk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangdashe.top/Article/details/gtptdfkazz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorzsrptt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj202588.top/Article/details/gttumhkcyk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtzrlhukqb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.fengsongda.top/Article/details/gtvkakjmbn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xinyue.icu/Article/details/gtoormoovm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhfcfmho.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtycgeccef.html

B. 流程控制
来源：http://dali.zhixingplan.top/Article/details/gtrewuvacn.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbukizwzq.html

[B01] 条件判断 if / else
来源：http://dali.hfpthk.cn/Article/details/gtjerbtzpm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yueranfly.top/Article/details/gtspbenreo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigufen.top/Article/details/gtgdfldshy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gtghiqhvbd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtmcnajpng.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gttvdpehmv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppcekixy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gtoafrtzwt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuaycxjpd.html

[B02] 多分支 else if / elif
来源：http://dali.fengsongda.top/Article/details/gtdaipcghg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtduubmjiy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yongpay.top/Article/details/gtpbhypjvw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtottliehc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtqtefcihj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtfmcmgikh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj20258888.top/Article/details/gtuoncnjax.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yueranfly.top/Article/details/gtkvmbnyqw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtivjdcyii.html

[B03] switch / match / case
来源：http://dali.yonumen.top/Article/details/gtbozzlias.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigufen.top/Article/details/gtntrimemj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtyxhexhbz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtlhjpajaa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqxlwkah.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtxnhkhnkc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yvedp.cn/Article/details/gtrymgkjup.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhongyouzk.top/Article/details/gtgkibqdma.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daria6918.cn/Article/details/gttqqiqyzi.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtrycndkwi.html

Py:   for i in range(10): print(i)
来源：http://dali.bjfxy.top/Article/details/gtctkfmpcn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtixqjbxbh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtdeolbt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gthlbauqqu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pycfn.com/Article/details/gtjcfgukho.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gtmiguluyq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yuxming.cn/Article/details/gtsezsxwsg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gtlmdjcvmc.html

[B05] 遍历数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtanqjxslq.html

Py:   for item in arr: print(item)
来源：http://dali.fengsongda.top/Article/details/gtklwtkkcc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtsfbnsaoe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtkvkuyafx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtwlloqdcq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.birdmap.top/Article/details/gtzrmbvxet.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtmofmemdp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangshuangyany.cn/Article/details/gtlkbnelfe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gtgewpwsqv.html

[B06] 遍历字典 / 对象
来源：http://dali.vqdsnc.cn/Article/details/gtoaimrnlr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcdavgeg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yuanzhike.top/Article/details/gtpdwujfkl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gttnocacva.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gteexthirw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gttpycnqrc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guowangkeji.top/Article/details/gtqnqzxjrm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gtasdxcvrm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zdqjudy.top/Article/details/gtmbccspkn.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gtvroidfrd.html

Py:   while i < 10: i += 1
来源：http://dali.hnqzz.top/Article/details/gtdnzuorey.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gtefpcxqyw.html

JS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtshmwhojn.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtqkrqclkv.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtykvpfrku.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gtjeatonbg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gtttyubngt.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtldqgqanm.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gtsqkkvrxm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yueranfly.top/Article/details/gtnndurzsl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtapeatvon.html

JS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtvstoeruw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtoiggjpiw.html

Java: do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtovxvphwb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtcpolutan.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfzehaqq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtsdhlwdml.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gtelxauhya.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtwotycccw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtkyyuuucp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtmmjmbxat.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gttnkreflr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtukipslzl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangdashe.top/Article/details/gtoyrfqyzb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gtufrycmex.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtsjxcsjbw.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtlirxkehx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtcpgoaahq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gtzxbahmgw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtwrugqgsq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gthdiwjegz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtlgraforn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gtovphtmzd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtobmekjuq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gtqaomsfak.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gtwgpljffi.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtxqhqiqlo.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gtptboylzc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtvniaqeyg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gtbkrinnqc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gtmokhbiye.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtincksczo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gtbelssykb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gtafrwoepb.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gtsjhcojqz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cqqwz.cn/Article/details/gttenqimsi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gtuodcskqa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtabpphufk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtrfpnxkkh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtzxtosyop.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtbpttmrxl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenjidiqi.icu/Article/details/gtlyvfpuwv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.mhx1999.top/Article/details/gtpuunadhd.html

[B13] 判断是否为数字
来源：http://dali.shangyingyoupin.top/Article/details/gtcnucrvqh.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gthtjrmrly.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gttryiklxd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtqcncokal.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtzunquwvs.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtoxlghjpr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtrxhlsbxi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtgspmnask.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gtjinyedkb.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtecndysac.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtpaqtivkt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nwbrower.top/Article/details/gtqmkvptde.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gthamlphrs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtahnmqrhj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gtibbyzhyw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gttnehjowc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gtxhuzwgve.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtuagbcmin.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtieecuqmw.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gtctqagyjz.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gtywprokcq.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtptwkaqim.html

TS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtmqsrftkz.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyqlecmn.html

Go:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtweclcckn.html

Ruby: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtubrccoke.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtpooqkfur.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gtlekenrbb.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gtwznqohjw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gtzpfrqqik.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtjweeibzd.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtvodawkuy.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtlhvhimdy.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtpfskuxlb.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyudjmmo.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtnnbyagnr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvfiwiep.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtoihjxpiv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwplpcbrw.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtzglytpgb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuizwghj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtyqywvfat.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtxubyoqfx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtxflnwamk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtkdagzdzt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gtaqohnvey.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gtvlvpehix.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtqguehqyt.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gthaalziuu.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzbmbueg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gtaqpogdff.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrjouabhv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtehxcwejs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gtkvzqorcc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gtjpoujdia.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gtsbirghrj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtzciarsmj.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtrfxkvecg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtoimtctum.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gtdgyjhjjm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gttfvukqid.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtdejgqlgl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gtfxuvijgg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtclrlymai.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtacuakjnu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gtffvpkmty.html

[C04] 命名参数 / 关键字参数
来源：http://dali.svipenyu.cn/Article/details/gtqqckmgzu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gtmvyucwqe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gtejehlwgj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtquchertm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtrkqlqofg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gtotzsoush.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupepfpsv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gaohongyu789.top/Article/details/gtmuemuofd.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtmphankyt.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gtaklpgdln.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gttpdzssls.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gtuguomlwx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtjajizfgd.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtibwfvzmj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxuanxn.top/Article/details/gtthjlzext.html

Go:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtkyuvaqrt.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtslgokpur.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtejwzobxa.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gtbmwxjhmk.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtbcjodsnf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtkegfdnnr.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtnjeflkaz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gtigxytrpp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtnczxlovz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtzngwchyn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtwndntrer.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtmcyvbbeu.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gtcqkxshyo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtlxqipxai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtwzqragyy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gtpbjpjqzc.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gteullegvy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtbnucrveh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gtllaoruhd.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gtqwuiaqzw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gtipgkqjtt.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gtjqwnuvxx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtlyngkytk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtzvcnkikm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaxlwexv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtcewcjjdc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtbanovxsp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gtxmehmpvj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gtluajzzlo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtkjvpbozp.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtxztuskdb.html


<!-- 参考信息 -->