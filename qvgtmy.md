代发 wailian999

[A22] 获取字符串长度
来源：http://dali.yvedp.cn/Article/details/gthkqgtkyg.html

Py:   len(s)
来源：http://dali.sysykeji.top/Article/details/gtwcdxfbhu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hammf.cn/Article/details/gtdsazgaur.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jiagoushi.top/Article/details/gtpqeiceky.html

TS:   s.length
来源：http://dali.fengsongda.top/Article/details/gtgfuqidhc.html

Java: s.length()
来源：http://dali.cqqwz.cn/Article/details/gtknrnvjcf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gtgnccepcg.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gtitorogve.html

C#:   s.Length
来源：http://dali.meibo888.top/Article/details/gtfvgxomys.html

[A23] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtdgarouxb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.fzhhl.top/Article/details/gtmifetcen.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbfaxhpbb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtycbkwdwf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtmkrercss.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gtxusyoofv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.mhx1999.top/Article/details/gtefnonkou.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtgpvvhbjs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.quarkkingdee.top/Article/details/gtnbmsaqcu.html

[A24] 去除首尾空白
来源：http://dali.316326.xyz/Article/details/gtbytsxdki.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.haohaochexian.top/Article/details/gttumbscae.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shuidangran.top/Article/details/gtbjouhikf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gtnjdxlkav.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnbpxbbr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfeqdxaq.html

Go:   strings.TrimSpace(s)
来源：http://dali.yueranfly.top/Article/details/gtgmcmimba.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jiagoushi.top/Article/details/gtmsuddljd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gtjsrhtltu.html

[A25] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtjthseiey.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhongyouzk.top/Article/details/gtfqkzwmzf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xziqi.cn/Article/details/gtdaiwisft.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtbusfhypl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gtvwiicvqk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuanzx.com/Article/details/gtutvtevwy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtkhgaxfxd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuuurdum.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtrjrjalva.html

[A26] 类型转换总览
来源：http://dali.gogol.net.cn/Article/details/gtqvltseau.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.bjfxy.top/Article/details/gtblwjbjtc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkiuldir.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gtsuaonagf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cdnleiting.top/Article/details/gtetxdcodk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.iojbl.cn/Article/details/gtnmemrskc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gotoacloud.top/Article/details/gtdwnqdywx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinqigfzy.top/Article/details/gtdduekxej.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gtvyukvnhm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvsqmvvyo.html

B. 流程控制
来源：http://dali.gogol.net.cn/Article/details/gtfhfhutzv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtnmvxxzgv.html

[B01] 条件判断 if / else
来源：http://dali.yanxiufei.cn/Article/details/gtzppdbrji.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zdqjudy.top/Article/details/gtifheqlyv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yonumen.top/Article/details/gtpbbienar.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtoxjmybmi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtpegxukxj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gthegtwyfc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ydzc1.top/Article/details/gtetgglshn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnqzz.top/Article/details/gtyojojlfx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtdbridyet.html

[B02] 多分支 else if / elif
来源：http://dali.tianlin.xyz/Article/details/gtrelvjjvh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtbxewdlge.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sweek.top/Article/details/gtpnlhtvhb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtcmggphep.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtscifgthc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gttjoccjaw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daria6918.cn/Article/details/gtgpnundjs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shzxlz.cn/Article/details/gtggnqxkoc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtngnmkbqr.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gtaxegpoqf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hywenlv.cn/Article/details/gtnphrshtl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtdggoaxsr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtyikfdkzr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtswjatuoa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtmzudhxux.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ehwqpu.com/Article/details/gtnvwdxsph.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jianghu66.top/Article/details/gteaxfzulo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtxbuqftry.html

[B04] for 计数循环
来源：http://dali.zhiwuduotai.top/Article/details/gtnxulwppr.html

Py:   for i in range(10): print(i)
来源：http://dali.hnxiangtu.top/Article/details/gtcclqfljr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gtyqezkokc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gtfblzdmgy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtuikkngue.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gtqypucmuh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.9152youxi.cn/Article/details/gtvnmzawzg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.redwolf501.top/Article/details/gtwztltutt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gogol.net.cn/Article/details/gtamzqtebe.html

[B05] 遍历数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtfcwjyqpp.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gtgomhrbpd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aibaodan.cn/Article/details/gtkthxphgn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gthcirisgl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhvwpqzf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrktzboer.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ppjwa.cn/Article/details/gtuvdgjvzr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hysaishi.cn/Article/details/gttqphyrpv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hammf.cn/Article/details/gtxptimtlo.html

[B06] 遍历字典 / 对象
来源：http://dali.gaohongyu789.top/Article/details/gtmtiijfzp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jianghu66.top/Article/details/gtmikjwakz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gtytaifpct.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtdeqecthd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtoqqxpzuk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gtzqldfzyw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nwbrower.top/Article/details/gtvfeskgqs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yongpay.top/Article/details/gtsirwpfmv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tian-w.cn/Article/details/gtiuiunrld.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gtsuocxrek.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gtknvxjnso.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gotoacloud.top/Article/details/gtuelrqtmv.html

JS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtjwlicdbk.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtmroqzuoj.html

Java: while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtnmjbgjxl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gtghuoxwxw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgfzy.top/Article/details/gtliiogzwn.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtvbalhcuo.html

[B08] do-while（至少执行一次）
来源：http://dali.zhongyouzk.top/Article/details/gtqlabjrdm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guannengcc.top/Article/details/gtwqlothzy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gtvgugjswb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtvzvqzojk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtlhotenzc.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtproaaksu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtjypwwrhg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtwkhoinzf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtaexgejho.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtsblljmyk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gtigqgeowb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gthvgesdqc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtkyafuqwa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gteeaucdhx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtzdnbhagk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gteonkoolh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuetiantiany.cn/Article/details/gtgtbkfrlz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtzpqxyckz.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtozfghcxv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hysaishi.cn/Article/details/gtplwxgzst.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gtskeiyfkj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtsfrujaaj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtawkglrsz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gtjmqgotdp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cheryme.top/Article/details/gtuclnwrdi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gtzvxizckm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtotvmvaxm.html

[B11] 生成数字序列 / 区间
来源：http://dali.nwbrower.top/Article/details/gtwsgbhrcn.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gtyztmdicc.html

PHP:  range(0, 10, 2);
来源：http://dali.mhx1999.top/Article/details/gtuhzpxith.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtzebyvbkq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtfdxsxdku.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.smart0.xyz/Article/details/gtxtfgjrui.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gtjazamjnc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gtoorotrvr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxinkj.top/Article/details/gtpivxgmaw.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtprcsekft.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gtpfhywkfx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zdqjudy.top/Article/details/gtmraawulq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtchyyihwb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtfdiltehm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtiyzjldxt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gthilysvek.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cashguo.top/Article/details/gtrmeoxxhf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yueranfly.top/Article/details/gttzafuhjx.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gtjdoqtoyq.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gtjqzlgame.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gtebhcsopq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtqynisnfi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gtgfmerrfn.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtzfpyzluk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gtnxtilafc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gttydlmruy.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gtallbrntj.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gtxejqjrbu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gtxuhmbqke.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gtemwwmkoz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtdenuzget.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtbqdbmadf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gtnjkxhwkn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gtsqzzrnyz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtrwkhgmzn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtbyjebhly.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gtmgbafpcg.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gtpphauujc.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtryfqfuok.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtywixkcdo.html

TS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtvixlytvm.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtwnpwtkub.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gttquqabql.html

Ruby: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtyfbrbpjf.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtfotjzldy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gtppiwlbur.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gtunoxgdcr.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gtsqedopve.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtwxswhcel.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gtwxykvezj.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtlpoyqqcq.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtpmcpzxjy.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtmlfudpnh.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtlyzflhjh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbztxioln.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gtjwpfxyso.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmldzckzn.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtuhveomff.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtgorojrmu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtyxtltezr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtticnnraa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtlptftipm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtfmicswve.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gtdkjhzeic.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtzxzsoenl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtklmnzlmu.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtcgprlimr.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gtzfwdzcjv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtzurrffod.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtqblaorha.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtrakrpvao.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gttnsfhbqc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtglfcvpqc.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtmxhwgmny.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtuztdqmql.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeslrdep.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gtuknzqxdf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtapibnlmh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtakdznnni.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtexcuvywm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gtyyafchnn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtavznyenk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gteapecndp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258888.top/Article/details/gtxhpkeegz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtczuibhte.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtaydqbclo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gthvyfelmg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtsfuvkkug.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gttrazmlwy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gtzgyvspsu.html

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gtykzyuxnq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtennpkcrb.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtifrwcvmt.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gtzeqkjhpe.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtbgemgibh.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtxlumeeue.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gttqkfdiem.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtjhbwfgif.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtvdnoiira.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gttsudfjgj.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gtuanuhhah.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gticpewbpk.html

[C06] 匿名函数 / lambda
来源：http://dali.wangdashe.top/Article/details/gtfvpvkopk.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtiuobunnd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtxdknynil.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtpbjicwzt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gthtbjocjp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtgagwqlbk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gtsrbhjmos.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gtkhabagvj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtknrvrplg.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtcgfxyr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtzmonbxqc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtzeqfmzoy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtbbjpqupq.html

TS:   arr.map(String)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwwvsiqb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gtqmycijnr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pycfn.com/Article/details/gtdjjusupp.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnqzz.top/Article/details/gtczwpvsnc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gtsljoxpka.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gtatdpcufy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gtjipoljgn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.9152youxi.cn/Article/details/gtwsrvjxni.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtfuuozvpu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtmzlxmojl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.snrcjt.cn/Article/details/gtmcfphimx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtltsenubo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtodyozaqb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtfmrrrtaa.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtlgmupmsw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtifjotxgv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtgmaqghsm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtgyevtnqv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gttlcrnrcn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gtgbmpwmam.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulqukqlb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhengqikj.top/Article/details/gtnaeejwfc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gtaaqqkakh.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gtmxjijhnl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtzwnvwntm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuanzx.com/Article/details/gtsrpzngsb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gtzypetgph.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtutzkwzzu.html

Java: 方法内为块级作用域
来源：http://dali.yvedp.cn/Article/details/gtqonabvhc.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gtokeedeyu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gtfzrytgix.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtmckjfnpp.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtblrwiknt.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpoagcna.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cqqwz.cn/Article/details/gtrtyjwfmw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtslbwfszy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gtamhvtviz.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtokyhncez.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gtbbmkwlja.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtjsvzmkkg.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gtytlhvvee.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtczpdxmzu.html

Py:   (lambda: print("run"))()
来源：http://dali.gotoacloud.top/Article/details/gtijdlwjqh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtsxiqmelu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtecedsdsv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtgizgxchm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gtpofmtxtu.html


<!-- 参考信息 -->