代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.tianlin.xyz/Article/details/gt2oalctvuu.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gt2pabzehlp.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenlongwang.top/Article/details/gt2diylkwut.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gt2kirygagm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yongpay.top/Article/details/gt2ycxatfro.html

Java: (int) 'A'; (char) 65
来源：http://dali.gzhubu.top/Article/details/gt2ecvljpbs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gzhubu.top/Article/details/gt2jkycfesu.html

Ruby: "A".ord; 65.chr
来源：http://dali.hysaishi.cn/Article/details/gt2gsuogwkp.html

C#:   (int)'A'; (char)65
来源：http://dali.snrcjt.cn/Article/details/gt2rrlatnir.html

[A19] 交换两个变量
来源：http://dali.svipenyu.cn/Article/details/gt2jttmwveg.html

Py:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gt2wkgoumko.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.316326.xyz/Article/details/gt2xagskcif.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gt2bvcalwwv.html

TS:   [a, b] = [b, a];
来源：http://dali.chenzaomai.com/Article/details/gt2wnittovv.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jksgggxa.html

Go:   a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gt2ohptzivj.html

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gt2vgejggjp.html

C#:   (a, b) = (b, a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxfnhflm.html

[A20] 读取标准输入
来源：http://dali.ydzc1.top/Article/details/gt2zjkqcnmc.html

Py:   name = input("请输入：")
来源：http://dali.vqdsnc.cn/Article/details/gt2aikamwtf.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ppjwa.cn/Article/details/gt2opwvuqbs.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigufen.top/Article/details/gt2jbesjisk.html

TS:   // Node.js：readline 模块
来源：http://dali.sufxvd.cn/Article/details/gt2ubwmirjp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hfpthk.cn/Article/details/gt2xkbhioiq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gzhubu.top/Article/details/gt2mpttazsm.html

Ruby: gets.chomp
来源：http://dali.c1oappe.top/Article/details/gt2rlidbjbz.html

C#:   Console.ReadLine();
来源：http://dali.aizwys.cn/Article/details/gt2lwhtxbgw.html

[A21] 保留指定小数位输出
来源：http://dali.cdnleiting.top/Article/details/gt2oqbdugnw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xuanzx.com/Article/details/gt2mpzhpkee.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gt2uquklkpw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2dlfytskv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2wfdmoqqe.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pslxvayi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gt2pxvjyhlj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gt2ncvehmiv.html

C#:   3.14159.ToString("F2")
来源：http://dali.mhx1999.top/Article/details/gt2esmietav.html

[A22] 获取字符串长度
来源：http://dali.pycfn.com/Article/details/gt2rkslopef.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2wqwzyjcb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.redwolf501.top/Article/details/gt2fqwimhrk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.andypj.xyz/Article/details/gt2vahputcv.html

TS:   s.length
来源：http://dali.cheryme.top/Article/details/gt2idvxpbue.html

Java: s.length()
来源：http://dali.sufxvd.cn/Article/details/gt2euubwueq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2amtqykfo.html

Ruby: s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ulgbctxt.html

C#:   s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2tjzpzvno.html

[A23] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2dtcptznx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gt2qumhnxzn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdvhtpep.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gt2xvwockgu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kckhvcad.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gt2yshwubde.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xylfe.cn/Article/details/gt2cdftearh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.c1oappe.top/Article/details/gt2qdlnyfpz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aizwys.cn/Article/details/gt2eacrenvg.html

[A24] 去除首尾空白
来源：http://dali.ivvv.top/Article/details/gt2jpcrsgqn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuanzhike.top/Article/details/gt2wpovemhi.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ybcxt.top/Article/details/gt2ppauisfo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xinyue.icu/Article/details/gt2vvvswbaz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gt2bfioijcx.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gotoacloud.top/Article/details/gt2ohsutjai.html

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gt2kyprjbac.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwrqknxa.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gt2ppzsvulo.html

[A25] 字符串比较
来源：http://dali.yonumen.top/Article/details/gt2kyyzwaqp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.havefunace.top/Article/details/gt2fwmplilw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.haohaochexian.top/Article/details/gt2krakdbqd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gt2iqotzavo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nabwgzly.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2elhxnsem.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.0kj1m.cn/Article/details/gt2dnhojxly.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuanzhike.top/Article/details/gt2cdhjxhmr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.0kj1m.cn/Article/details/gt2jmyndgfv.html

[A26] 类型转换总览
来源：http://dali.nanxuanxn.top/Article/details/gt2dnszlzwy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pycfn.com/Article/details/gt2ekssoarz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.316326.xyz/Article/details/gt2aoreewsl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cheryme.top/Article/details/gt2yxgayfiu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pengpengdd.cyou/Article/details/gt2nezhealu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqfgpbjg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yueranfly.top/Article/details/gt2irmkmmbd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jianghu66.top/Article/details/gt2vawetogk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jqgufenzy.top/Article/details/gt2pjtxgvoa.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hjxywmzx.html

B. 流程控制
来源：http://dali.smart0.xyz/Article/details/gt2pxewpifj.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2snnbzwuq.html

[B01] 条件判断 if / else
来源：http://dali.hongshengwenyu.top/Article/details/gt2apfzizko.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gaohongyu789.top/Article/details/gt2wjtzhqpa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.svipenyu.cn/Article/details/gt2boasforc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2bbzlysfy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2bupwzsgy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gt2qzkgmqgx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgfzy.top/Article/details/gt2gpegtycf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gt2mcpfqxyc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2spvbfvoi.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gt2skdmepfn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gt2xxsnhqzk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenzaomai.com/Article/details/gt2mkhrktvg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfhkqyoe.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gt2lvrvjlny.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjpswjo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zycfv.cn/Article/details/gt2mbtbgpgs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.birdmap.top/Article/details/gt2cblutata.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jiazujto.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gt2xeeofgwi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.daria6918.cn/Article/details/gt2efyduizx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2fwuqwugm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2ovdjckig.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gt2niiehume.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gt2azwhwdfd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gt2fzuikmhf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pengpengdd.cyou/Article/details/gt2charvduf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gt2zzoinldo.html

[B04] for 计数循环
来源：http://dali.yj20258.top/Article/details/gt2dkzjhhis.html

Py:   for i in range(10): print(i)
来源：http://dali.cucudq.cn/Article/details/gt2fljnqgat.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhongyouzk.top/Article/details/gt2digdntqh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gt2oddctdlw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.iojbl.cn/Article/details/gt2essdybia.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edhlhcvc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgqkgmxh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nanxuanxn.top/Article/details/gt2nwrlvlxd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qdjvnbuu.html

[B05] 遍历数组 / 列表
来源：http://dali.yonumen.top/Article/details/gt2pjhcfypj.html

Py:   for item in arr: print(item)
来源：http://dali.tian-w.cn/Article/details/gt2ttdbthow.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shuidangran.top/Article/details/gt2qknqmdfk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2ckqevshy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gt2zuwjikhw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2egioqkdm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovqazsyt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenlongwang.top/Article/details/gt2wawckuyu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.0kj1m.cn/Article/details/gt2ciltiqlq.html

[B06] 遍历字典 / 对象
来源：http://dali.xinyue.icu/Article/details/gt2nvxvltzk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2okddqkax.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.fzhhl.top/Article/details/gt2xvulgukw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gt2zeqcazvq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gt2xmlenvzk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258.top/Article/details/gt2zsnnblii.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2exzuqgao.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gt2dahlpocs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gt2wxvplakn.html

[B07] while 循环
来源：http://dali.c1oappe.top/Article/details/gt2rdxvczwj.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gt2cmunyiqe.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prnezqwe.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2afeojioo.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2nawnohgd.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gt2lnxceolp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.bjfxy.top/Article/details/gt2fjpsnknx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gt2nkkxskdg.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2uqmermex.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gt2zstdaqah.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bsjnlxkt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2mjnthlbd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpqkmong.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2dnehowyx.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2accppbhv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2tifqufww.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.meibo888.top/Article/details/gt2kxmmojob.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2axhuxlmy.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gt2thmhcqyb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhjlmmwf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2hhdolbba.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dvlwxvpo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpqrtvey.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2gopfeqbp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gt2qslhfqqs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yueranfly.top/Article/details/gt2svdlbmkw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2elgbnhrw.html

[B10] 遍历同时拿索引
来源：http://dali.9152youxi.cn/Article/details/gt2zcygdihu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gt2invxefzj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gt2txsahtlp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gt2nilyfifp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gt2oqmiiiye.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gt2tpmnakeh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sxryk.cn/Article/details/gt2jxzqeser.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2ujucrjrs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gt2skfqwfmt.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyygptgl.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryhubdho.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2cfeogpqc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gt2gsoovuye.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcolgyrh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2crjkonbu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gt2krgjomni.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gt2ffqzcjya.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2xeysfodt.html

[B12] 跳出多层循环
来源：http://dali.svipenyu.cn/Article/details/gt2ojdbhuhn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gt2bjcavclv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gt2aecrpqkn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gt2dntfwgxr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhmqltno.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2zhumkcwq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gt2vhwmbczr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhrecgk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj202588.top/Article/details/gt2kshbsxkm.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gt2vboaerby.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gt2ljcfdnin.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gt2oklkfcwj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2qceqxdgl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gt2ngnjewzv.html

Java: x instanceof Number
来源：http://dali.nanxinkj.top/Article/details/gt2fivnfjxi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gt2dykrkovj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnqzz.top/Article/details/gt2kpwnznpk.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gt2vlaxparq.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gt2fseuyyqy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.redwolf501.top/Article/details/gt2kablrtvs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aizwys.cn/Article/details/gt2njgbrbja.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2ntwykvia.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2fxjbnrpv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gt2edbubclz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gt2vwtrtjlf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2qkwgewjx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2lwkliwgm.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gt2kfzewtcl.html

Py:   a and b or not c
来源：http://dali.meibo888.top/Article/details/gt2jaebmtjv.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gt2ofnzufnk.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2cyaujuqg.html

TS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajdjlddr.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2rpkdhwds.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2wjhgbbhq.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2jpcwblph.html

C#:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2bwzipdla.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2otfvfqya.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gt2cxlyhzrf.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gt2bjdhddbb.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gt2xnxkejgd.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2lxxjwldi.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2jhrrxqgc.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gt2ohsggoem.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gt2xtkbiwys.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2ooturhnn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xwfbtvky.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gt2yzmqzigu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qvtllism.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2doitcheh.html

Py:   def add(a, b): return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2yvdwcggy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mvcbkhyj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvzjojjl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2skdvetwh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2mucdhach.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2wuzxwcpj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2rssqddpy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2ujahzcfp.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gt2ydijzluu.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gt2aubmknbv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gt2uxfvzwjl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2nuojxeln.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2npuwvbff.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sqvukska.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gt2bykoyizt.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gt2kfakqmgt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gt2fuulyefk.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gt2kppaskxg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvyvqcug.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hamrtqru.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gt2chzrjovo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2eqzaqixm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gt2sstrdytl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gt2hrwkzqox.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gt2sbpqjeeq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gt2qyiedeoe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gt2sfezgpjd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2squnilfh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hysaishi.cn/Article/details/gt2hywoaeyr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvyjoebe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gt2bbojrgma.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2gaupjole.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gt2iobmmpzs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2wlgypsjq.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gt2kaotprku.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gt2ejjmrfjz.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2aiyzwjla.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gt2lpzpyyys.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gt2nquvakvu.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2sgzhhxrt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gt2fprjqteh.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2eywgeicp.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2lmjosoun.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gt2eqrbipao.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gt2lrcoccnq.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gt2ghlrdhew.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gt2zqxaquvq.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gt2ipvrreso.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2hbypazvy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gt2qicvjntt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2uooayyea.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gt2emijzzpd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpezamxq.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gt2pukitckl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gt2ckkadxbq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2ikwijbik.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gt2yzmboxad.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqtsewol.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2tggkkarh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gt2kgwwujon.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gt2lqoxiwrf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gt2mahbtdwr.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gt2sixkzrhv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gt2lamuzffe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gt2qlkfrfav.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2occvnjai.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2yxruocme.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvlabfcu.html


<!-- 参考信息 -->