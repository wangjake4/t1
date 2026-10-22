代发 wailian999

[A22] 获取字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2nihdexde.html

Py:   len(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvzxjqvo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sweek.top/Article/details/gt2bxckwkhe.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sufxvd.cn/Article/details/gt2xhomcolc.html

TS:   s.length
来源：http://dali.daxiang520.top/Article/details/gt2rcfrbqvk.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gt2sobrewsu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yonumen.top/Article/details/gt2gwblrnff.html

Ruby: s.length
来源：http://dali.aizwys.cn/Article/details/gt2ftigmspf.html

C#:   s.Length
来源：http://dali.mhx1999.top/Article/details/gt2hqiwjqfy.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2dulueaah.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.mhx1999.top/Article/details/gt2kgcxdkno.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cucudq.cn/Article/details/gt2qtpwjojt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlsikum.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gt2ksgpcbyc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gt2yottpekm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nwbrower.top/Article/details/gt2sjgvuxly.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gt2rvhxollo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jyoumei.cn/Article/details/gt2xgxlxijb.html

[A24] 去除首尾空白
来源：http://dali.cheryme.top/Article/details/gt2tsrzuhfw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.316326.xyz/Article/details/gt2ggetivez.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.smart0.xyz/Article/details/gt2igpktxrn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gt2yzevgpyi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gt2loagvuac.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tian-w.cn/Article/details/gt2tzasflus.html

Go:   strings.TrimSpace(s)
来源：http://dali.iojbl.cn/Article/details/gt2qcoraigh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tzlvihdh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gt2yuknfcym.html

[A25] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gt2ngwsvcec.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gt2eydvoxwq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258.top/Article/details/gt2uvdfmafd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gt2bowzlekq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gt2iunxxftu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmnwileg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2aquhwtyh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cashguo.top/Article/details/gt2fcyewxje.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iurqflls.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gt2urjctkss.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjtkterw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ybcxt.top/Article/details/gt2ogezduel.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gt2vglibviq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.dianchejie.cn/Article/details/gt2cyhyxiva.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gt2wdqvwqqy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hysaishi.cn/Article/details/gt2extcfhaw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sysykeji.top/Article/details/gt2tkroutgq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gt2xfeclkzh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2mcmmhqth.html

B. 流程控制
来源：http://dali.quarkkingdee.top/Article/details/gt2qhthticm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksovmnvl.html

[B01] 条件判断 if / else
来源：http://dali.yj20258.top/Article/details/gt2kxwteypw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.smart0.xyz/Article/details/gt2vvmczfzl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zdqjudy.top/Article/details/gt2xfrdtgvk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gt2bxyvydci.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifwxazli.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gt2tlwswucu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yangfankeji.com/Article/details/gt2xwrgdswv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yvedp.cn/Article/details/gt2jwvhhufv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2krkafecn.html

[B02] 多分支 else if / elif
来源：http://dali.zhongyouzk.top/Article/details/gt2bwkbtlhi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcezzkwf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpysjldo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gt2nutfvobk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gt2vmkcyiam.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2lufrrcju.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fzhhl.top/Article/details/gt2lmzpurtp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxwrokyz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gt2semifylx.html

[B03] switch / match / case
来源：http://dali.jiagoushi.top/Article/details/gt2jhnwqrdl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qygsvcxf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2zorlbdzk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gt2sqldbmiw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gt2aecsfobj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gt2siuqloli.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gt2ztssmwyp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jiagoushi.top/Article/details/gt2dkhoneho.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fengsongda.top/Article/details/gt2owirtnsi.html

[B04] for 计数循环
来源：http://dali.pycfn.com/Article/details/gt2uvatztwl.html

Py:   for i in range(10): print(i)
来源：http://dali.ydzc1.top/Article/details/gt2eyjqxaua.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aibaodan.cn/Article/details/gt2ikppcrbp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gt2jacyotti.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2zxeucezr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gt2bihremdc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gogol.net.cn/Article/details/gt2mxapclui.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gotoacloud.top/Article/details/gt2gpaoanxp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sxryk.cn/Article/details/gt2fmnijrbk.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gt2lsthmmbl.html

Py:   for item in arr: print(item)
来源：http://dali.ivvv.top/Article/details/gt2pdmozunt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guannengcc.top/Article/details/gt2ctguzavs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stzalsor.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gukppron.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dashuyun.cn/Article/details/gt2iwgnufda.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxuanxn.top/Article/details/gt2oqqdhnif.html

Ruby: arr.each { |item| puts item }
来源：http://dali.havefunace.top/Article/details/gt2sgusiotc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gt2arephsag.html

[B06] 遍历字典 / 对象
来源：http://dali.ydzc1.top/Article/details/gt2aqjpjbfy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.quarkkingdee.top/Article/details/gt2pynrhgbm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cashguo.top/Article/details/gt2kloaoora.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gt2fiirbfwc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gt2fbnzecen.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gt2yrlsivxk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cqqwz.cn/Article/details/gt2aksqxrod.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gt2rghtawod.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gt2gfsohisy.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gt2vyroedyj.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2svzulsyw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gt2kyphqcgt.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2uswlasqx.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2sitdtgpe.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2vzlbezyk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gt2phmzbbzi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gt2sxfgavct.html

C#:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2nypkelsg.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gt2stakrvns.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj202588.top/Article/details/gt2zybbivpc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2vsinlemv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2kdyofqio.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2ofwfuauf.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2pjhrvags.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhengqikj.top/Article/details/gt2rrjwizcv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yanxiufei.cn/Article/details/gt2vcfutfmp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2ygftqpxn.html

[B09] break 与 continue
来源：http://dali.gaohongyu789.top/Article/details/gt2umgjqwlt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gt2zvusqcft.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2jatcljlp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2wufplwid.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2umjqatug.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2dsmoepix.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gt2vvzmuzab.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gt2rrmuxmsd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2lsuoddep.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gt2xcgqdnti.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gt2vqbirhaa.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xinyue.icu/Article/details/gt2jtrraipz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gt2sdxzipib.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gt2zreznamf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gt2kvqvfosf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gt2bfaoydzn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gt2kpqdkvxm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gogol.net.cn/Article/details/gt2xhjrpugj.html

[B11] 生成数字序列 / 区间
来源：http://dali.haohaochexian.top/Article/details/gt2dxxjolkg.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gt2zjolskjg.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gt2bangmngr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2gvmictpk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2uikohnnl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2qupakjyz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hongshengwenyu.top/Article/details/gt2snixxdvh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2hcqaommy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2uqjlfeli.html

[B12] 跳出多层循环
来源：http://dali.yongpay.top/Article/details/gt2twydhelw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gt2luynmkqk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gt2heqontag.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2hsjuayup.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2ymbmcbve.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gt2tsqaizoe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gt2iqqbzsmb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daxiang520.top/Article/details/gt2bafprbph.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.c1oappe.top/Article/details/gt2jnkzfdrw.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gt2rfckpmsx.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gt2osnmfsmz.html

PHP:  is_numeric($x)
来源：http://dali.yonumen.top/Article/details/gt2wfdaqamw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gt2rxdwnwyd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gt2ytgsmwiv.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gt2olqwgcqb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gt2hmestwyo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gt2hffgnmhs.html

C#:   x is int or double or decimal
来源：http://dali.jqgfzy.top/Article/details/gt2rtdgewec.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2bdbegfeu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2clyilgbb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258.top/Article/details/gt2lzdgsmpn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2alyubawz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2ormkcjsy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2nordhyhg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gt2mjhzxvst.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2wjhjcapm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2bjefkhvi.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esjjdorf.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gt2ysotitnz.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gt2wbmpfejk.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdqipftt.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2rmetcltn.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2qfktcwus.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2dhqujiam.html

Ruby: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2zfphhcww.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2dglqigwd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gt2kkunflvt.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gt2zpfceery.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258.top/Article/details/gt2omzhconp.html

JS:   if (!data) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2kemkcvdd.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqvesbrk.html

Java: if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gt2whcidefq.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gt2bdvxbvrs.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gt2kckfywex.html

C#:   if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gt2fhwtfeta.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2cmaqcafx.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gt2pqasyymq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2suqskcbc.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2sdhezctf.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gt2rllhzkzl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2hifmaddc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2juittoum.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2mnvjbdxw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2enpjiusq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2vqrnxlaj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gt2sakippxa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2scnbwwpj.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gt2tzxcxuxs.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2yilgyhlf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqkgiqyk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2cugkgamh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2vvniafpi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gt2yqbhqydp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gt2xjziyuap.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjgtysmd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gt2fcobljae.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gt2ajzqqrff.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gt2ywrmwsqm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gt2bngkluwd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2pnrmdvnc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mizdhxbb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gt2mlzbvinz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gt2fwyruxkq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gt2eqgifwav.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gt2gdhefiks.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gt2fszvquxr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gt2sflguioy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.316326.xyz/Article/details/gt2yizxsgeh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gt2vdvekrja.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2ylkeotiv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gt2viewasev.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gt2tnvheckx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2pltgxnmk.html

C#:   f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gt2qokcbtpr.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gt2wlcpnfrs.html

Py:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gt2opvcvyjj.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gt2xxlyofoz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2xvszrrkw.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2sdxrzhbb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gt2eqigfphz.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2dbevbgyq.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2rotjpnbg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gt2zpljnemn.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2qbbhflok.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gt2pnxtowmg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gt2ofrfisaw.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2szxecxbg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifdusshu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.birdmap.top/Article/details/gt2vizhfzuh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gt2mbhskosf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2wnjrgvem.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2rrzdnccm.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gt2ucuvspqs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gt2drxmwqya.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2samqawnz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gt2bxqlrdqd.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gt2jdhamfwa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gt2qrsxzeat.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gt2lcybgxea.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gt2jlchspmq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gt2sfvvgoii.html

[C08] 闭包
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtwjidmg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvwrpua.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gt2jijgejai.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2yytpdoig.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2fyvaquqc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gt2plngphxb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gt2zeapxbos.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gt2xqnqecui.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wnxhnxlx.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gt2akbxfdkm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2hitmsxmv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tobvftdj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2rfkzxpos.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2hyezgofe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gt2wmsyzqyy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gt2ytklpllk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2exzfhwdj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gt2jgxrztil.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2lczgpcjz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sesniurc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gt2jmykkvjm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2dqflczcj.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2oenokesq.html

Java: 方法内为块级作用域
来源：http://dali.mhx1999.top/Article/details/gt2exywpuot.html

Go:   花括号块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2syulzcjf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gt2mdlpvnsb.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2sxnqgduj.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gt2iimhgjqn.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gt2vkkkuwqr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gt2eorjzjgi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ledbhsst.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gt2cybbmyca.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gt2psiwkcbd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2eetaixfr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gt2baqrvotb.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gt2euplbxxw.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gt2hypbuzpl.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gt2koaebeyc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gt2puwcmmth.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gt2omndusvh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2iaxbcbqp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jianghu66.top/Article/details/gt2exayilvp.html


<!-- 参考信息 -->