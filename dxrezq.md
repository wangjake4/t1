代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.guannengcc.top/Article/details/gtmkgmffwa.html

Py:   ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gtukgbqqcb.html

PHP:  ord("A"); chr(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsnnfqwt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gtbbvwqkfs.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuanzx.com/Article/details/gtcgaamjuz.html

Java: (int) 'A'; (char) 65
来源：http://dali.ppjwa.cn/Article/details/gtuouftggi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuanzx.com/Article/details/gtievscvvy.html

Ruby: "A".ord; 65.chr
来源：http://dali.ivvv.top/Article/details/gtqaaryqqh.html

C#:   (int)'A'; (char)65
来源：http://dali.mhx1999.top/Article/details/gtiyuabfuh.html

[A19] 交换两个变量
来源：http://dali.nanxuanxn.top/Article/details/gtmqxzxqmu.html

Py:   a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtxxxghfdj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.pycfn.com/Article/details/gtlkaytais.html

JS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gticnsexio.html

TS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtxzmadsbd.html

Java: int t = a; a = b; b = t;
来源：http://dali.daxiang520.top/Article/details/gtjsihskcg.html

Go:   a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtqqzaclpq.html

Ruby: a, b = b, a
来源：http://dali.zdqjudy.top/Article/details/gtklnqkvho.html

C#:   (a, b) = (b, a);
来源：http://dali.tanke756.top/Article/details/gtvfiqwodd.html

[A20] 读取标准输入
来源：http://dali.sufxvd.cn/Article/details/gtqkpbkxtu.html

Py:   name = input("请输入：")
来源：http://dali.yongpay.top/Article/details/gtnbgwnqjl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xylfe.cn/Article/details/gtjfmtbjob.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pycfn.com/Article/details/gtfpxavcxf.html

TS:   // Node.js：readline 模块
来源：http://dali.yueranfly.top/Article/details/gtiespkqlg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gtbxxdcpdu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gogol.net.cn/Article/details/gtrvykdaxj.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtdjlpocuo.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gtlpvnpqty.html

[A21] 保留指定小数位输出
来源：http://dali.pengpengdd.cyou/Article/details/gtxfredmho.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cdnleiting.top/Article/details/gthkrabalw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtbvlwgydk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtujtuecjg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtisjhxfln.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtwmdfdazn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtbaefuntt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtioyjhpth.html

C#:   3.14159.ToString("F2")
来源：http://dali.tianlin.xyz/Article/details/gtxtfwiuhs.html

[A22] 获取字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtioqwdhqf.html

Py:   len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxzgwixk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shzxlz.cn/Article/details/gtrqgtyozc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xziqi.cn/Article/details/gttmgjurmg.html

TS:   s.length
来源：http://dali.xylfe.cn/Article/details/gtfdlaztzw.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gtepzodehu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtsgfbkrtl.html

Ruby: s.length
来源：http://dali.ydzc1.top/Article/details/gturdocugd.html

C#:   s.Length
来源：http://dali.yj202588.top/Article/details/gtiewryilj.html

[A23] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtvvkydayi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.daxiang520.top/Article/details/gtbocuocqd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.meibo888.top/Article/details/gtamahkgfl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtfhkrzmvh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtbrkwheom.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtdwjtjrst.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gzhubu.top/Article/details/gtuvlmkcca.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sweek.top/Article/details/gtirzhtlsn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xziqi.cn/Article/details/gtmzunxpep.html

[A24] 去除首尾空白
来源：http://dali.quarkkingdee.top/Article/details/gtzhdmrldf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258888.top/Article/details/gtlqnluoty.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aibaodan.cn/Article/details/gtiwjyoakr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtfhbntffo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gteataxwtm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjcvpgyv.html

Go:   strings.TrimSpace(s)
来源：http://dali.sysykeji.top/Article/details/gtfuareapk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tianlin.xyz/Article/details/gtmbgnlynw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xuanzx.com/Article/details/gtmeqnitxw.html

[A25] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtohvwadqb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yanxiufei.cn/Article/details/gtxndbmdbh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fzhhl.top/Article/details/gtewzzsjin.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtufmabele.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gtmgkwarjx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtedgupxca.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gtejlcfaff.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.bjfxy.top/Article/details/gtisaiqcix.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigfzy.top/Article/details/gtvvufxops.html

[A26] 类型转换总览
来源：http://dali.cucudq.cn/Article/details/gtoaqpeaey.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cashguo.top/Article/details/gtikmyjost.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gtvnqvyivu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtonffzixz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xziqi.cn/Article/details/gtebgotpxs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gtiyoxbovt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dianchejie.cn/Article/details/gtpcvyotps.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangdashe.top/Article/details/gtbpojbybb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtgukknjrf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtqhzywgot.html

B. 流程控制
来源：http://dali.quarkkingdee.top/Article/details/gtsrasdhzr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjwrvvgoa.html

[B01] 条件判断 if / else
来源：http://dali.jyoumei.cn/Article/details/gtjfnldllv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gtilidnjjm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ydzc1.top/Article/details/gtqydbjtnz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtsrrullpq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gtkdwvsmho.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtaxobpywd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cashguo.top/Article/details/gtaxntoqym.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gtlqhlqwck.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdynvbbja.html

[B02] 多分支 else if / elif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdylwycua.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.svipenyu.cn/Article/details/gtqqwtsunz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cucudq.cn/Article/details/gtlbuuycgv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtiepzefrh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtbbudwwcb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtskqlcaea.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtoipvsrpy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fzhhl.top/Article/details/gtjerbgecu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtpriukdzv.html

[B03] switch / match / case
来源：http://dali.nanxuanxn.top/Article/details/gtjhfllnxa.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtzzmqcjwu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzpyloex.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvtkjurff.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtgwkagwkd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtsznadaim.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtsrqrotqh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yongpay.top/Article/details/gtzqxbmaby.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fengsongda.top/Article/details/gtupopcuyr.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtywzzubtl.html

Py:   for i in range(10): print(i)
来源：http://dali.ydzc1.top/Article/details/gtzblnvxtp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cdnleiting.top/Article/details/gtzmovdlla.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gtsfnqqbgh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvwhjyvw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gtcybilzcm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zycfv.cn/Article/details/gtrrcehpiw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hysaishi.cn/Article/details/gtlgihjshv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gtvfgfhdef.html

[B05] 遍历数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtjbubmiea.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gthtdnmnng.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aizwys.cn/Article/details/gtyrktdvxm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtztzdizbp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtsojabdjo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gtewlipucg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gtznaovqtl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tanke756.top/Article/details/gttoromdtf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbezlhxjb.html

[B06] 遍历字典 / 对象
来源：http://dali.birdmap.top/Article/details/gtnmkxmzdc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gtvlfejznw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gtgdflmaei.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtntrlcbxe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gtpunlsmvm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gtqwaaqeav.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnxiangtu.top/Article/details/gtabymwrvz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxinkj.top/Article/details/gtmaprqpwu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gtdxrlpoct.html

[B07] while 循环
来源：http://dali.gaohongyu789.top/Article/details/gtlcyhjefb.html

Py:   while i < 10: i += 1
来源：http://dali.wangshuangyany.cn/Article/details/gtsuekhjuf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zycfv.cn/Article/details/gtkauzqhss.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtidziwfkz.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtimwgyous.html

Java: while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gttkzkjmim.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aibaodan.cn/Article/details/gttgeukmcq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtmisycqzz.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtfkwnhseh.html

[B08] do-while（至少执行一次）
来源：http://dali.ydzc1.top/Article/details/gtqdumehiq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hongshengwenyu.top/Article/details/gtcxsrdois.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gtbanhkxmt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtmjunpoot.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtiplprimo.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gthuomkfhf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tian-w.cn/Article/details/gtxnncsuch.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gtiasrdank.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtismyjyrs.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtvdfyxzkx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gtrfjaxnti.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtqzctqxor.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtnuoffhsp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtknglbppo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtftupcvwk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.birdmap.top/Article/details/gtqqqoggzv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gteiirgegy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtgqyctrnn.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtokdzojhg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gtqtsyeeyv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jyoumei.cn/Article/details/gtllaqxkvh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtnwxalhqw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtgdcvvmdc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gtmudvqrqw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gtnfwgdpno.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxinkj.top/Article/details/gtrswoidnx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtzbacoevx.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtbtzmbjgi.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gtloyivigc.html

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gthqqfneih.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtvxijwhpj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtdskpuxyh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtgoxzflbz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yueranfly.top/Article/details/gtlnkelsch.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gtixrafqrx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tianlin.xyz/Article/details/gtwqvgaozo.html

[B12] 跳出多层循环
来源：http://dali.wangdashe.top/Article/details/gtlxzlzsnf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gthfyysxqs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gtteytdymp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtilgeflkb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtyywaaisa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtvfhzvcif.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtaeqlnoxx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtrqbrnkek.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gtxipdzgvv.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gtrgnruskh.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gtnwgnhzmb.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gtqiqtfukv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtnpanraqb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtolsxrzyg.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtfindgqun.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtscptnrjq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtpsbdygzd.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gtoxdmmahf.html

[B14] 判断值是否在集合内
来源：http://dali.cucudq.cn/Article/details/gtsqnjyxpw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtrrudlhzg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtwrvysjfq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtjvcmqiru.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtzdjvzemz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxayoeesy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtpejsppaw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gtxnpaqqie.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gtziidwjcd.html

[B15] 布尔运算与取反
来源：http://dali.jlsjyb.cn/Article/details/gtkclrewft.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtwtanjotq.html

PHP:  $a && $b || !$c
来源：http://dali.haohaochexian.top/Article/details/gtgdabizsq.html

JS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtycmcmzbf.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gttzsewmrn.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtjmwaoiry.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtabbuaqtm.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtnttsxrnn.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtroxpnuyd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtwbclenak.html

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gtvsauwhyn.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gtrnxfovta.html

JS:   if (!data) return;
来源：http://dali.yvedp.cn/Article/details/gtkfejqjml.html

TS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtandvnrqz.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gtaybgpxur.html

Go:   if data == nil { return }
来源：http://dali.vqdsnc.cn/Article/details/gtsvjviyzd.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvohjnyuz.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtzgsxpbqa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzzxorrsx.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtgddjgfte.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpvhizseb.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtmokltdep.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gtotyewycx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtpphfervf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtadvyqf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtimviadzn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtyeqmjlyl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gtqgqgdusb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtqhuvqncb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtemyszvoe.html

[C02] 默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyhzkmbi.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqducequ.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gtwfjnwyuv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtlepdskyf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtmaflzwnm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gtajmmfqqr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtxwkbemjv.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtabscctxs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gtxgjtbfrg.html

[C03] 可变参数
来源：http://dali.smart0.xyz/Article/details/gtijyjxanc.html

Py:   def total(*args): return sum(args)
来源：http://dali.zdqjudy.top/Article/details/gtmgkszweu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsbzzurzs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacaplvgy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtbnzotuha.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gtvkerdupq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gthirhigui.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gtbhupgkdd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gtylogqmjq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtnsauayxc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cashguo.top/Article/details/gtiilhfvqn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtrwfpggdn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtalqryjbe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlohllszs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtkiowbzno.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gtpmibnxct.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtjruzvqav.html

C#:   f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtatnatiyh.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxggkqswe.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtigbgpnxi.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtnmsiqdbr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtsyuzpgwc.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtbzjpnxxt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gtcnkjivoh.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gtmwatjahi.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gtlbojkgac.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtjzonqxoq.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxinkj.top/Article/details/gtcsihwjmr.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gttyqcavqz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxuanxn.top/Article/details/gtkrmauzvr.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtvkaszpha.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtuzkkgqjd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gttmqyzqio.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gttreqijlv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtvluccblt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtbwlwnhrf.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gtewgjjsrf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gtzpybyosb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtndazbcrx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gtuuljdphu.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtrhnavoec.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gtqbmcyncc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gtndjmdrmq.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtvnosahsc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gtnrxpsotj.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gtbrqjnslc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnxiangtu.top/Article/details/gtghylldud.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gtrxvznqdm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtdoiamhnb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbfzjwvdk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gtcgdtendz.html


<!-- 参考信息 -->