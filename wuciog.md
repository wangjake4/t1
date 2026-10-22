代发 wailian999

[A22] 获取字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtteujlbrw.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gtvieuxatr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gotoacloud.top/Article/details/gtgwoaaqyj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pengpengdd.cyou/Article/details/gtvxevetkn.html

TS:   s.length
来源：http://dali.aizwys.cn/Article/details/gterthfpvo.html

Java: s.length()
来源：http://dali.yj20258.top/Article/details/gtqdcijiyt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvutccnpf.html

Ruby: s.length
来源：http://dali.yanxiufei.cn/Article/details/gtmdmmzqmh.html

C#:   s.Length
来源：http://dali.sxryk.cn/Article/details/gtldnudwjn.html

[A23] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtezvkmkta.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xziqi.cn/Article/details/gtlgsacivw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.quarkkingdee.top/Article/details/gtgjrtdsdd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtsqxzhhhl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtfixnecbu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtweyqruab.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daxiang520.top/Article/details/gtkvdcmkai.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtukirwquo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangshuangyany.cn/Article/details/gtevmgarkw.html

[A24] 去除首尾空白
来源：http://dali.zhiwuduotai.top/Article/details/gtxzhdqskx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsbmxwxh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gtsexdxheu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtxvkktcqs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtpogjynal.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinqigufen.top/Article/details/gtpxfcvspr.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gtzugojwmv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zdqjudy.top/Article/details/gtiewznuaa.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sufxvd.cn/Article/details/gtwtcwuaqg.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnuwljpu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yongpay.top/Article/details/gtjiciijjo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gtdroifwpa.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gtcknsxjvf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gtfgmwufpa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sweek.top/Article/details/gtdsytkzsp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtcaokgfns.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gtmgxehhut.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtznbemgmr.html

[A26] 类型转换总览
来源：http://dali.nanxuanxn.top/Article/details/gtsyzjffko.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmunocvpk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvysiqjn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.bjfxy.top/Article/details/gtmyubolev.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guannengcc.top/Article/details/gtubmzsskl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtzguqykdo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sxryk.cn/Article/details/gtvsocztdf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fengsongda.top/Article/details/gtohvbzhlh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gtzwuopwnd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtybqzwpmk.html

B. 流程控制
来源：http://dali.yvedp.cn/Article/details/gtdljcdmdv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjsvcczbw.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gtoxnqveur.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hywenlv.cn/Article/details/gtrunalszo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.svipenyu.cn/Article/details/gtvnvjmitx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtfvshoimk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gthhnmzbof.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtinbzynsj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj202588.top/Article/details/gtjwrupsjv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtzdaestka.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtgxkenkvz.html

[B02] 多分支 else if / elif
来源：http://dali.gzhubu.top/Article/details/gtsarihlsz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ivvv.top/Article/details/gtzeallmgq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jiagoushi.top/Article/details/gtezwnxblt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtdqhvvmgf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtrrhmutoe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtbguirqvb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.316326.xyz/Article/details/gtprotbshb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gtjvseqgoc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtpumbhdiw.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtezdmiwbw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gtfquixpow.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtyyexwscp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtfohssqex.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtbeieytux.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtbpzdzqjp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daxiang520.top/Article/details/gtchxnylxj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gtyfzwbhua.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtoqtocwup.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtkvzydzdj.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gtggickhyx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinqigufen.top/Article/details/gtzmlawrwg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gtargakzwf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtyfxcuoku.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtvdcwuzqq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fzhhl.top/Article/details/gtkhfvtfcl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenjidiqi.icu/Article/details/gtfdexfdlk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefzfitip.html

[B05] 遍历数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtjblyqreo.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gtnprgridv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gtnmhkbswv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtmndxcbyu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tian-w.cn/Article/details/gtwtbqjbzh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gtsvndqgeo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.mhx1999.top/Article/details/gtlfginpws.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtdaezfmtg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gtwiznxwgo.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gtzllkemcl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ivvv.top/Article/details/gtoonanwcu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.aizwys.cn/Article/details/gtpfsovkga.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtehpzklbj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gtncmlhens.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuusavuuy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zycfv.cn/Article/details/gtcdxiwhpb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cdnleiting.top/Article/details/gtgsudfttp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gthgzewvbj.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtjictmxgx.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gtohrurwpc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cdnleiting.top/Article/details/gtvczrlpzn.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtflmftzgg.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtdzysqlfb.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtinnzeeea.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtpxvzzrep.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gtbxuzliqd.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtlrkkoerd.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gtlfkeuupw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gtggyinbyd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ybcxt.top/Article/details/gtirzdkfqf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtkmjibzns.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtvfskbxba.html

Java: do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtkynmxmey.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gthgodjxvj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gtbfdjkhyj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtjbtzlrlo.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gtnphofrji.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gtdvcccwlu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtubijdbbs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmpjouzfh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtidprkghm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtpumznddu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtyloichmi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gtntavfzyd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtchkdooge.html

[B10] 遍历同时拿索引
来源：http://dali.havefunace.top/Article/details/gtlhjsxpsg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gtkrrjbqpt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gtacethjfi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gttnpkqxef.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtauvjatom.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pengpengdd.cyou/Article/details/gthxzchjlq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gtjatqjsfr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gtpdoegbrc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtzydfzurk.html

[B11] 生成数字序列 / 区间
来源：http://dali.meibo888.top/Article/details/gtsgziknsi.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gtciifcauv.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtamdhygnh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqdzfkxu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtcseqkgif.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gtiadvtxmu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yueranfly.top/Article/details/gthtthpxbb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gtfgvaztjb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtfgkbaxke.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwcthbgk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtwyycklxg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpdszizm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtpxchgswr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtmxvklejk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtjcwotulq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gtvovmkqby.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daxiang520.top/Article/details/gtuvayamly.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xylfe.cn/Article/details/gtktqmtnhl.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gtkwfcmpbb.html

Py:   isinstance(x, (int, float))
来源：http://dali.gzhubu.top/Article/details/gtvkmnhuxj.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gtclvnrrfn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtlfksihcc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gtnyjuergt.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gtpyxjlbvz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gtnfvgjcxn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gtivyhgara.html

C#:   x is int or double or decimal
来源：http://dali.zhoulong.xyz/Article/details/gthmrjldxn.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtyabxekza.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtjiiidfke.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmybdzso.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtuvctyrgx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gteglubazv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtxaumdnpy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtuqclkldv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfuobfeqg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtalfydzmr.html

[B15] 布尔运算与取反
来源：http://dali.wangdashe.top/Article/details/gtrpfclyoh.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gtrqxtfkya.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gttsdaormb.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtovqkqoul.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtaqyfhvpz.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtwexrdqxm.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtlsotlten.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtdkyttjsg.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtclytpuok.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsdxfdsy.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gtilwotpbr.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtodsnxdts.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtalieunyt.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtnnwoxfuk.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtlynjooij.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gtzykkyopb.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gtoxxkkibz.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtotglxfta.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkxtccumq.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtgtmpmzqb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcqikbmrv.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtyznizjfm.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtpoptkmlp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthibztgpl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtidtyeawr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtgnegwzgg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtljofiakn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gthjlqdqlx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gtuyvyrlac.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtnpvkxspp.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gtrjrtytga.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtvdzxotsx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtpiwovgiu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtmpfhvotz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbxfrszqr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtkasfiqdg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxznqdcxu.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gtfmvtphmg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtotvoppvp.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gtibnlljkw.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gtpvpfzoxn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gteujzirve.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtqwfghyku.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtjhuznpvg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gtviicxgwt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtarqjkojy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtdixbocxl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtonhtobny.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gtnmjsgrbr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtqenkcpqi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoopkouge.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtcapcxjpa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtiedhfzof.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtyozbvtem.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gtovuezuee.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvyeixwd.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtlxmaopvd.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gtjtqeghrh.html

Py:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtlrnznrvs.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gtskhpemtd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtfpwdnige.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtacefbwiq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gthazakemo.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gttgbvwrnn.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtwzeitbdo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gtixcyqszm.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gtywimujha.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtlukgvhws.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtxmyktzvs.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gttchchoze.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtswaekbel.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtmdgbvzfq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtqlmjicaf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtdwhpvtgj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtvpufjmph.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gtaekxjxpi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gtdopteytd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gtpvzrxlye.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyzxcrhj.html

TS:   arr.map(String)
来源：http://dali.jlsjyb.cn/Article/details/gtjlczqeiu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtzdnunyjm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gtpcnljxok.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuanzx.com/Article/details/gtesjnzsdb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gtsqtrxmuv.html

[C08] 闭包
来源：http://dali.cdnleiting.top/Article/details/gtfwvgakrx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtydznczjm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gtdoimunfi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtdbttdiaq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtstzregug.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtfvbrovvu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hongshengwenyu.top/Article/details/gttzdysyrg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtpatrbgpv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtkphhofzj.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbkkryla.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtjnxqajkk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtprrhpevp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtvndyywwc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtnxlsrmoy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtygqdzzxv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gtdxutdweq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtmdaympve.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtwsfozmyz.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtccafegsi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtvlusqvbk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtllkoicri.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtflwefmbz.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gttdqlvtyv.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuymxlxx.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gthfvamijd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gtriqcjkwk.html

C#:   块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtfalramhr.html

[C11] 模块导入与导出
来源：http://dali.dashuyun.cn/Article/details/gttzjqfarl.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gtbthrcahi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtetctjafh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtkxnfvyia.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtzmmukyfp.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gtwkysefjz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gtglnzflpo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gttmljwdep.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gtnuucuodl.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhengqikj.top/Article/details/gtvpjlrqtu.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtebxysxbv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtfgzyjycu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtwemhfleb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtksstophn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtwnaektsd.html


<!-- 参考信息 -->