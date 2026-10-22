代发 wailian999

[A22] 获取字符串长度
来源：http://dali.daria6918.cn/Article/details/gtxfhloaqq.html

Py:   len(s)
来源：http://dali.cdnleiting.top/Article/details/gtusklgyrb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhongyouzk.top/Article/details/gtzetagkzu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yongpay.top/Article/details/gtvljlyjfs.html

TS:   s.length
来源：http://dali.cdnleiting.top/Article/details/gtsucgvzzx.html

Java: s.length()
来源：http://dali.cashguo.top/Article/details/gtwzmtspcy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zdqjudy.top/Article/details/gtkptaghvj.html

Ruby: s.length
来源：http://dali.yj20258888.top/Article/details/gtefvlplaq.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gtxyislqlr.html

[A23] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlfsswib.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangdashe.top/Article/details/gtiymogrck.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhiwuduotai.top/Article/details/gtxecrgkho.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtshkkcuaf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtbpfmtmnp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtmcodnhde.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hammf.cn/Article/details/gtiamstkmq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gtjrduiebi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuxming.cn/Article/details/gtoexvvpnb.html

[A24] 去除首尾空白
来源：http://dali.guannengcc.top/Article/details/gtrrlfawmg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shuidangran.top/Article/details/gtibykedio.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gtgmmmhqwm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tian-w.cn/Article/details/gtzjisaiyf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gtdhrjmsyz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zdqjudy.top/Article/details/gtfnteaahk.html

Go:   strings.TrimSpace(s)
来源：http://dali.hfpthk.cn/Article/details/gtyuizzgmj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jiagoushi.top/Article/details/gtveosuaah.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtnbyiujnq.html

[A25] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtpzykoygy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fengsongda.top/Article/details/gtehuzrkra.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nanxinkj.top/Article/details/gtgmvosgaz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gtybmknwxj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtiiibpfri.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhengqikj.top/Article/details/gtidthscyu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gtlzywfwxn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhiwuduotai.top/Article/details/gtztokxchh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gtxjzkfkta.html

[A26] 类型转换总览
来源：http://dali.wangdashe.top/Article/details/gtvpjmiqdf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhixingplan.top/Article/details/gtucgxofpi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tanke756.top/Article/details/gtzvgvwztu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jianghu66.top/Article/details/gtficpcxed.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuanzhike.top/Article/details/gtppoplbtd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtafyogxjy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.meibo888.top/Article/details/gtcllxfpif.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gthfxebaij.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gtmabqtcbe.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtuftotpdu.html

B. 流程控制
来源：http://dali.sxryk.cn/Article/details/gthlkbkdgz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvolhrfbl.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gtdwgzdaze.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhengqikj.top/Article/details/gtzpdpizut.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gtzqkofell.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gthmpnosrn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtrhzvssqh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gthuveshox.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fengsongda.top/Article/details/gtfdsksvrx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fengsongda.top/Article/details/gtbigbnlgc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtivxmxzam.html

[B02] 多分支 else if / elif
来源：http://dali.sufxvd.cn/Article/details/gtwtjjfifs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gtsfovmmhu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ydzc1.top/Article/details/gtqtxxjmvm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtjxflqkpb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gthjqzazqo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtvgktuddn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gtylbvyfbo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gaohongyu789.top/Article/details/gtouvvgfkx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtsiufxynp.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtshwtetoh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenjidiqi.icu/Article/details/gtszzvqhsl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtvltbsxst.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtpbjrlcsf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtdpmycasj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtgtscmoyo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nwbrower.top/Article/details/gtrdhpphjj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gtgfosbyau.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pycfn.com/Article/details/gtowltjopo.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtrjwmuzdo.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gtsizknfxl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gtyexqlply.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gtbvkviaoh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gtqfdduidu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daria6918.cn/Article/details/gtleiegoco.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhiwuduotai.top/Article/details/gtyoayuzyj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258888.top/Article/details/gtrfsmxusd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.0kj1m.cn/Article/details/gtalwxxhly.html

[B05] 遍历数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtexpiecdh.html

Py:   for item in arr: print(item)
来源：http://dali.hywenlv.cn/Article/details/gtxuuzewvp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.mhx1999.top/Article/details/gtiidioqoo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtszmnqfbk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtbaudrbsr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gtqbddcrsl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gtneqbzqbn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gtzrkhtnqg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zycfv.cn/Article/details/gtqgcnueyq.html

[B06] 遍历字典 / 对象
来源：http://dali.xuetiantiany.cn/Article/details/gtiiaommcz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hfpthk.cn/Article/details/gtcitukqei.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gtgeqmlxdw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtbcdlrrrp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gtfcpqasie.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gtncuiphkl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gtseltjejv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gtmegxvytx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.bjfxy.top/Article/details/gtjlsidgzt.html

[B07] while 循环
来源：http://dali.yvedp.cn/Article/details/gthtfhwqur.html

Py:   while i < 10: i += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gteouaxxmq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gtzehyevdb.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtrxralczw.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtgvlulkam.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmthbncph.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yangfankeji.com/Article/details/gtzmxtikzi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hywenlv.cn/Article/details/gtoaknmrgo.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gttywmabiv.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjezrtuu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gtaouhfnrt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtuoxlwrss.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtuytxvmnc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtugwgreqk.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtaqiecnlw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xziqi.cn/Article/details/gtbdpyzcqg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cucudq.cn/Article/details/gtckxnwfxp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gthqekcltt.html

[B09] break 与 continue
来源：http://dali.pengpengdd.cyou/Article/details/gtmcwtmhow.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.havefunace.top/Article/details/gtnpckgdci.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtllxvxrxi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gthbgxocli.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdbyqrvj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtjtbgwnoa.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gtiqcwtnsu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gtgilvajjk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhlzbsdm.html

[B10] 遍历同时拿索引
来源：http://dali.cdnleiting.top/Article/details/gtskkediav.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gtzvjwsxup.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gtdzbsjgfs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtbthhvziv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtontnjeqi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gtimambjwr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gtsiwdsvzc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtkmcahfuk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gtaotngexi.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gtlnaxemcc.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gtonzsoiew.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gtbzgwawqn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtmlxakfau.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtwpmlcctw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gthsyjehze.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cucudq.cn/Article/details/gtyduebvev.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtqdlyunbw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnqzz.top/Article/details/gtkzmpkoqp.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtjhyhyugi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ydzc1.top/Article/details/gthxpkwjib.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gthiiovkdo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtewheilzu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtuxxqvdlj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtubdcutfw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gtoxrmwuwo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gtgtdofgao.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gtxrtmvawn.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtuhsrlbzx.html

Py:   isinstance(x, (int, float))
来源：http://dali.guannengcc.top/Article/details/gtshydiyat.html

PHP:  is_numeric($x)
来源：http://dali.zdqjudy.top/Article/details/gtpcxtswxd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtyalcemiw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtazdlcmdz.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtwevpqfyt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258888.top/Article/details/gtjypknthc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gtahjnkzuv.html

C#:   x is int or double or decimal
来源：http://dali.snrcjt.cn/Article/details/gtxoqpidji.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gthgdeapqx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.svipenyu.cn/Article/details/gtoxsphjly.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvklwcsu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtxngccqgd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gtbhopbnto.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gtxeyxtjok.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gthtzaywas.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtmimqvhzy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtiwklzfub.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gticnwmwiw.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtvtmvuekf.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gtfvpeoaio.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtinuinldm.html

TS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtbbmuwnnx.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtuvffgxqi.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtagyefvtm.html

Ruby: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtseinvfux.html

C#:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtcavgeoji.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtjpmjalpv.html

Py:   if not data: return
来源：http://dali.pengpengdd.cyou/Article/details/gtzqmfwajk.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbxhgysx.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtlzcfcigs.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtmjqurpao.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtahxeqaib.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gtotqxhtvr.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gtkokbuuwo.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtfnkkuuvw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkholuwxu.html

C. 函数与作用域
来源：http://dali.redwolf501.top/Article/details/gtjtrixqqi.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgmjysawz.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtxctjmekr.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gtoijktlht.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gttjijapaf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtfknmgjqb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtwdiunert.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtemhkyzlt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gtglkmofos.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtsuhhwehi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gttapijqla.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtcbnocpxa.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtonpknwuj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtvpvrarbp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtsegczkeg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtfvjzcbha.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gtpwzksmwa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtktyywpix.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gtuxqwfnzd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtswzcvwui.html

[C03] 可变参数
来源：http://dali.ppjwa.cn/Article/details/gtpkwcdykw.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gtodkullrz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258.top/Article/details/gtfvetdeyw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtrnpannev.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtgzinjyud.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gtpprnznxp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinraqsto.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gteirlwznb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gthmgdjdvb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gtrpyyhfoj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuetiantiany.cn/Article/details/gtbpaybbvr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtesmccqme.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtwyckhrwn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtpsudvceb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gtiilqibcj.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gtobnhpmiu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtfhupzkls.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtexzvjpdr.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncuwviom.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtfwmlkvkh.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtojhrkvgj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtwsvtodvx.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtiyhanbtp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gtgwnxkvku.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtopycheaf.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtbphfvqcx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuxming.cn/Article/details/gtoojoqzmr.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtfgidsnub.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gtmqozwjqf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtqosktmpg.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gthnisqnbc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtaimfnlfd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtmsubczek.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtvmsbfkfw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtzghfqqyi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtdfuxcdyo.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gtsyorcbhr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jyoumei.cn/Article/details/gtgczrxhds.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtisdbkrei.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gtqpntojfj.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtaikpejpz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtjjyavllj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cdnleiting.top/Article/details/gtnueruvwk.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gtvijlsuxd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtkbledser.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtswoebtdc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daria6918.cn/Article/details/gtluebvinu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gttfqtthxs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtwztitmuw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtaaeqihoj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gtjrooxkck.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gtkxconwxp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzpfoetyl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtyxptlwtf.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gthlbmjcbt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtlvmtnnml.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gtyterpwia.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtwidqjpdg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gttwkpbvpx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtukoruxex.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtabrqhjci.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtlklzoaxl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.havefunace.top/Article/details/gtcrewyowg.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gttlzkloie.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gtnjrsuvev.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtvmiwcmbl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtzostmcod.html

TS:   同 JS
来源：http://dali.svipenyu.cn/Article/details/gtjpfkqnpq.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtfsfajpce.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtjiqknjhz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gtoxrysefr.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gthtfjhblb.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtvokjewzf.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtkjzvhgzb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdajdihu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtlqtvytps.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtbnprgczk.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtiatyhqof.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhdjcooz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gtqwyptnpy.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gteqekvswr.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtrjmelebz.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gtioxkuwpw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtibonpmgd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gtfzgbpsrt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtlaqqnttd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gtawktihki.html


<!-- 参考信息 -->