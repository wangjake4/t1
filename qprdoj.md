代发 wailian999

[A22] 获取字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtnrigzuyn.html

Py:   len(s)
来源：http://dali.sufxvd.cn/Article/details/gtioguhoul.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yonumen.top/Article/details/gtkjdjqevn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hammf.cn/Article/details/gtnlapmdoc.html

TS:   s.length
来源：http://dali.sxryk.cn/Article/details/gterauicxi.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gtkmazknbt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gtrffbpvpw.html

Ruby: s.length
来源：http://dali.snrcjt.cn/Article/details/gtckykzvle.html

C#:   s.Length
来源：http://dali.tian-w.cn/Article/details/gtalybfvtq.html

[A23] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtkrkkvxwk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenlongwang.top/Article/details/gtwmmddwxd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cdnleiting.top/Article/details/gtzknafpao.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gttzvhaunx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtwmwavazb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtuqoubdpd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yonumen.top/Article/details/gteckurjev.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtplukiemk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgfzy.top/Article/details/gtlpezpgwv.html

[A24] 去除首尾空白
来源：http://dali.yonumen.top/Article/details/gtxmwgajyg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gtnreuumzp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gotoacloud.top/Article/details/gtkmkimoft.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtrskxejip.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtkmgtzebo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nwbrower.top/Article/details/gtyvezlhxr.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtldheclkg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.0kj1m.cn/Article/details/gtregdeolp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtloychbpq.html

[A25] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gtabuvevcp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aibaodan.cn/Article/details/gtsjumfbgj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yanxiufei.cn/Article/details/gtexqrcmyh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhoulong.xyz/Article/details/gthelhdqjy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncaoegwi.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gtbbmbvyyd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtuzohnasn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.mhx1999.top/Article/details/gtjdssicyi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtrhuokhap.html

[A26] 类型转换总览
来源：http://dali.316326.xyz/Article/details/gtrkgfjwtu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ehwqpu.com/Article/details/gtzffulafa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.andypj.xyz/Article/details/gtuinavbjd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.bjfxy.top/Article/details/gtqflvlamm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.vqdsnc.cn/Article/details/gtkwofxyso.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gtixasjigc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.c1oappe.top/Article/details/gtzvaugpey.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gtzgprlfet.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtmgxygdxi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcoxlvucq.html

B. 流程控制
来源：http://dali.nanxinkj.top/Article/details/gtmjmhmfiz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcayixkrd.html

[B01] 条件判断 if / else
来源：http://dali.hnxiangtu.top/Article/details/gtcfluevbj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cqqwz.cn/Article/details/gtorcvkwmu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhoulong.xyz/Article/details/gtxmzkmzke.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtbnttbwqh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtzmbdpdgk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtnqloursu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgfzy.top/Article/details/gtncitfjwj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xinyue.icu/Article/details/gtfcncffhp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtrfqgeere.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gtxzemcswc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.quarkkingdee.top/Article/details/gtkpchfslc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhixingplan.top/Article/details/gttudhwdiy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtgtldsuls.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtcsmicyvy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtippjvbwj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pengpengdd.cyou/Article/details/gtlozjepbw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.bjfxy.top/Article/details/gtubxfoufi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtvkainlub.html

[B03] switch / match / case
来源：http://dali.haohaochexian.top/Article/details/gtwsyebjfe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yvedp.cn/Article/details/gtnasekowk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtclipimyt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtaqmpjvzi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqsowqqdm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtvxhiyyru.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcptfnjjl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jyoumei.cn/Article/details/gtmkbpihia.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gthoiwegtk.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtzmefmewm.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gtkmhvzvtr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gtnzhhrrup.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtpeskxhtg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtuktoloam.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.wangdashe.top/Article/details/gtagsrijse.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.feifeiyinyue.top/Article/details/gtnbbwguht.html

Ruby: 10.times { |i| puts i }
来源：http://dali.kuanghao11.cn/Article/details/gthiucjyya.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtdmpvaohz.html

[B05] 遍历数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtdakhrgeb.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gtvnmwqbug.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cheryme.top/Article/details/gtvasjocba.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtcolbuuoy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcdghsdby.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuanzx.com/Article/details/gtehgvbvoz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuanzx.com/Article/details/gtykxotugu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yueranfly.top/Article/details/gtffitymdm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstqnvmvu.html

[B06] 遍历字典 / 对象
来源：http://dali.gaohongyu789.top/Article/details/gtirklryaf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sufxvd.cn/Article/details/gtnqvfwohu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cucudq.cn/Article/details/gtofiwjvps.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtsnbvmzkm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtvbdxmoun.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gotoacloud.top/Article/details/gtlghhqdkr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtndhbewaz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.bjfxy.top/Article/details/gtghytathv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtachmvqxj.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtvrdcfhpp.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapzstzml.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtphsuktpk.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtmwzbtuwf.html

TS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtjizqxozo.html

Java: while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtsizdunrq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtsitauhxx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.snrcjt.cn/Article/details/gtumodtiuc.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtalatyuow.html

[B08] do-while（至少执行一次）
来源：http://dali.yueranfly.top/Article/details/gteoxcblbh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yonumen.top/Article/details/gtmljllret.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gtvmqjxbcm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrergadsw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtkzoifkif.html

Java: do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtjdpcupvq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gtpfuxzzxc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gtryqiykbr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtgpgtxfmd.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gttkfmshjb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gtbdpuirah.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtyqciuycg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtaqcdkzjl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtvhpofktt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtnyqivibm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtoxrawcve.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.havefunace.top/Article/details/gtwqtswucz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtnecwwakz.html

[B10] 遍历同时拿索引
来源：http://dali.aizwys.cn/Article/details/gtrhtqjoaq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shzxlz.cn/Article/details/gtyhgvdpsn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dianchejie.cn/Article/details/gtpeeudodg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gthalontiz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtyqpevbmj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.kuanghao11.cn/Article/details/gtoohpshta.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuzsubvq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuanzhike.top/Article/details/gtxmuxldzg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnemfnykv.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gtlwoehohn.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258888.top/Article/details/gtcfjrxerb.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gtmxvfzbmy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtiybummfd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofxhgile.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gtfwyxywzy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.0kj1m.cn/Article/details/gtoysjkzwg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gtltudoknl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fengsongda.top/Article/details/gtvdcdejkc.html

[B12] 跳出多层循环
来源：http://dali.havefunace.top/Article/details/gtoposhzbp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ybcxt.top/Article/details/gtlnkuqujj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xinyue.icu/Article/details/gtzbrgbkfc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtsthifndj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtiowhzvoe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtzcfpwfpp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gtqpuvvotf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhengqikj.top/Article/details/gtjmoycriz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwqcxaxu.html

[B13] 判断是否为数字
来源：http://dali.yj20258888.top/Article/details/gtgdstavwu.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gtxbivciba.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gtmkejmauk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtngtfhaxv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gthtywcrtr.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gtrqmncxwq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gtaiyyjawa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtdwdffzcu.html

C#:   x is int or double or decimal
来源：http://dali.snrcjt.cn/Article/details/gtilhkybya.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gttknznero.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gtgledkhko.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gtdzszlfgj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtytbqfzjw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtnpsylqqi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtoitwhjnu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtqeuroevz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtogzenecg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtonwkhded.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtijrlpqzo.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gtbkvpldaa.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gthliwztdc.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtytfwgaej.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtjjjcpadn.html

Java: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjvljgka.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtxyxrevmc.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtvlwceowu.html

C#:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtoihkkhyj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtczphvdgb.html

Py:   if not data: return
来源：http://dali.dashuyun.cn/Article/details/gtuioiqfjy.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gtapckzkyq.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtafoizybu.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtjcjrhubk.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gttyypeutt.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtqzlgxcea.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtawhsbsyv.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtrhqsopms.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfahxigfc.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gtkzyhhnfp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmjfbtwkz.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtmrjibcpa.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtsxvrrjzv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtyxkbtjhl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtojtmrxuo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtrzsdlbax.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtntizzxwe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtkfafedsz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtpgxqhdza.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtbrxcwszs.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gthveavwoi.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gtviutqdpn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gtgevnveuy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtghrqjqcx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtrknkrvdf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gtgeuomthn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.iojbl.cn/Article/details/gtewvbbguz.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtwzdzgpcj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtksleszrs.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gtinupsjka.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gtrvnerhtv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtfzlydjpt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gtqfjdlyxv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtwfymzfpr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gttplmgttj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtvbivutck.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gtamfbrkne.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gtnotiwfvc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gtdtzibfuh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gtmroaatli.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtidvktbxv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtcsqeccbq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkxqsmpn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gthfdulkke.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtslkntjwh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtceusheyh.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtwykjnkwy.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gttijkybje.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtqcroamgx.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtlwbpvtfc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtqxwfjbhi.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtmtsrwqkr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gttnlaejvq.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtqtcchoit.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvzemgpg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtethynhpw.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtvjuwijcc.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gtpqxkkpxp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtdszdzyam.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtjggcdmlo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtufavyhys.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gthwvqmlau.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gtpkcfjwlf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tian-w.cn/Article/details/gtdrcdlxue.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtbdvcpkuq.html

[C07] 把函数作为参数传入
来源：http://dali.jinghuilouyu.cn/Article/details/gtftblqtrw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtvjrsyutr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtzbifbgju.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtsnxcqzrn.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gtliytlrov.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.svipenyu.cn/Article/details/gtbagpuljx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigfzy.top/Article/details/gthgbpsytg.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gtvbvtevyv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtqogwbhhj.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtpbuljqhw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gtgqnyjqml.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gtxfxetyei.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtsvbshngl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtnsuncuco.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dianchejie.cn/Article/details/gtlmrkcjmh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gtzkmlwfol.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gtwrvzicce.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtaegnphij.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtogdtkgeo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhwmuftn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtqthkxyxp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtzkijwmrr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gturmbiztm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtprihvooi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gtlpqokfnv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtwbbrxdjf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtfuhxeiav.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtquzaauis.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gtdwbbxfht.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtxewiqhpa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtqgrigxyj.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtbxmivzwx.html

Java: 方法内为块级作用域
来源：http://dali.iojbl.cn/Article/details/gtajbsaxkx.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gtafmpcauy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtwbhomobi.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gtnbxvxsht.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtqorttfvh.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtqopbmwkx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtysysbpqr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gthsvbfsph.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtglagglsz.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gtkfbxcqmo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gtaycsthwy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtreqaetdv.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gtacrofdex.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtnuglscpe.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gtadwsupmj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtcbygajqt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtmztagwle.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtkcvnxula.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gtsodhccyy.html


<!-- 参考信息 -->