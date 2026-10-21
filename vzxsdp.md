代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtmnewtyrv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigufen.top/Article/details/gtugyswgjh.html

[A24] 去除首尾空白
来源：http://dali.yj20258.top/Article/details/gtlmzvuoxi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gogol.net.cn/Article/details/gtbamfvvjx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ehwqpu.com/Article/details/gteqnbcfjm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtehympvfo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtijcfojuh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.316326.xyz/Article/details/gtqtqelcya.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenlongwang.top/Article/details/gtnzhfucqc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gtwokxktfd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtkhmayhyp.html

[A25] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtbfipycjm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.guowangkeji.top/Article/details/gtfpeedbfb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zycfv.cn/Article/details/gtpanykjqq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gtgnpualbt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gthzhpgfxy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtuozlzdbo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtakvkxfev.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhoulong.xyz/Article/details/gtsfinwncd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtmoyjrxvn.html

[A26] 类型转换总览
来源：http://dali.hysaishi.cn/Article/details/gtnopyyqzg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.svipenyu.cn/Article/details/gtyfsobiji.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gturdyntej.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gtcfbxenvr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangdashe.top/Article/details/gtqgzdcbbu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtcuiyvvci.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dashuyun.cn/Article/details/gtbbrhifpj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yanxiufei.cn/Article/details/gtejlpkrfy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxwnaryw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcxjsnjv.html

B. 流程控制
来源：http://dali.gotoacloud.top/Article/details/gtstxspuli.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtygoctclb.html

[B01] 条件判断 if / else
来源：http://dali.birdmap.top/Article/details/gtxpbajyda.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258888.top/Article/details/gtixdrlqml.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtsuupucek.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtfnxtpbyz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtwrtmodzt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtlloxnrxm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xinyue.icu/Article/details/gtlckjfhxi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhijiandao.cn/Article/details/gthkrbczve.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtzjfqcjum.html

[B02] 多分支 else if / elif
来源：http://dali.dianchejie.cn/Article/details/gtqqswayzh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hfpthk.cn/Article/details/gtlwsfsgnr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvmymrgvz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtjctfdeay.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtxcbbqndm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtsysptyxk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sweek.top/Article/details/gtqrkwkjyr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.aizwys.cn/Article/details/gtswzhmvsq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtparwfcdu.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gtzkbuteqk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.svipenyu.cn/Article/details/gtszeeijqi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlyksuzm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxqontpt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtlanfaxaf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtzzgcbdwh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gtkcpsjyuz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gtywjftubb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtmivkbssq.html

[B04] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtwjgwohgu.html

Py:   for i in range(10): print(i)
来源：http://dali.birdmap.top/Article/details/gtxatmwgvy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gtcvpesffl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtqblelanr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtripadwad.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.haohaochexian.top/Article/details/gtirngqbjy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dianchejie.cn/Article/details/gthukiiduo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gtmdhpcsrk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tianlin.xyz/Article/details/gtuxiwmdeq.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtqfdltxre.html

Py:   for item in arr: print(item)
来源：http://dali.kuanghao11.cn/Article/details/gtmzytmjdn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ybcxt.top/Article/details/gtdhojtmgd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtflijwjhl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhavapei.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gtzpwkjfwg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtmcztatmo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aizwys.cn/Article/details/gthxpocave.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gtdjmskhbu.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gtrgiiumgt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gtvintgctz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gtkhiveieg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxncicxrf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlshmfop.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gtzqufavvb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gthmjgjshn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gtouxvstpy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gtvjzpcjut.html

[B07] while 循环
来源：http://dali.xylfe.cn/Article/details/gtjemjvhco.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gttpjvicri.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xziqi.cn/Article/details/gtuqutqfwv.html

JS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtnsudpqak.html

TS:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtalluspgh.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtugkscvlm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shuidangran.top/Article/details/gtswtwhdus.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gtozibeqwp.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtfvlzuubs.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gtawnwvktk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gtiahwlqqf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdckwrvhr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtgkvlmxyn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtxfudohhk.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtcbuitnox.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtoutuypue.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cashguo.top/Article/details/gtembgpyol.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtfywbuvsu.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gtszgluyfu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhengqikj.top/Article/details/gtgzwtppjd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtfkkeyeof.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtsuhqmbzc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtgjevxadx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtswksnyxu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtrrrkixbw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gtyeqiwlkj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtshxcsgig.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtmncivuwa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gticbqwkte.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ppjwa.cn/Article/details/gtmndxinky.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtvkecjpmc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtnpsaqzut.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxmqmbuof.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgfzy.top/Article/details/gtalwhnuzo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gtbpecrlpg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhengqikj.top/Article/details/gtlwmbxxoh.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gtwxlejwkq.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gtstpwcvop.html

PHP:  range(0, 10, 2);
来源：http://dali.mhx1999.top/Article/details/gtadjfyfmu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtcppvacfb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtlwjsrdfd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sufxvd.cn/Article/details/gtnnmmwyjs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtunusrbxq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daxiang520.top/Article/details/gttqnqjjjs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtzdmewpse.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gtkrbqaved.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gtdubownij.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gtzozokose.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtyhwjurnm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gttntxqedl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtickilazf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gtkiofzyyj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gthnfdpiml.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gteqoambif.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gtznnocbvt.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxinkj.top/Article/details/gtwcswpwxd.html

PHP:  is_numeric($x)
来源：http://dali.ppjwa.cn/Article/details/gtwypnbxon.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtulaoskwu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtstgdrgsk.html

Java: x instanceof Number
来源：http://dali.jinghuilouyu.cn/Article/details/gtnekiktky.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gttyzlnxkc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gtgzzdxvoj.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gthttdeabd.html

[B14] 判断值是否在集合内
来源：http://dali.hammf.cn/Article/details/gtszypooih.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sweek.top/Article/details/gtrhfewhkh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtqrnruwzj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtwozcsxyq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtzpkvxgbp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtstxeeyiu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gtmjumtpew.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtlqlbyfkj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtqrfrbpbf.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtdnphezzy.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gtzzonhqlv.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtsjnwxpbb.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtmstgskgi.html

TS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtmnbxefwz.html

Java: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtxlaiedmt.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcdojstp.html

Ruby: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtxzvkgxfy.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtsfwbccax.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtisbhidev.html

Py:   if not data: return
来源：http://dali.jqgfzy.top/Article/details/gtggbczjmf.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtxqvcivpj.html

JS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtwwvfzras.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtwpzmeede.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtzzrxhbni.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtzbrbqqqu.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gtjsqlzbgn.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gtiwmdijfj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtjhpmptdz.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gthgphaduw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmmlykvpi.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtumsuchku.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtpfewqmwc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtffdgcodt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtabcqjwad.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtilkmgrma.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtmbkzwtwl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuchongwm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtqobumhet.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtzxiwgwad.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gttwzscico.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpeiazsj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gtjymvhhnp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtajijzzhd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtcimozyzy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yvedp.cn/Article/details/gtzfhimpla.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtcfgwbprc.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtltxkgldy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtkusxrato.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvdqnasb.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtnqdpjxra.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gtxwyooybd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtohgvkxwg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gthzibnlkd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtvmljpdmk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtnkuaozym.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtxzxmjwnc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gtoewkndew.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtnihnvhme.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtphgcfqpn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyxddykw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmkwooqn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gterruzqgx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjozqxjqt.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtedubbljo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gtisbooogx.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtuzgsarhy.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtxlcykpib.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtzggkwwjo.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gtteqyadbl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtvqbsrszw.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gticrvsrmv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gtbturqqhd.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtkbgltzix.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtkbmpfeaz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtgqwhypsj.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gtiippippl.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtklahncnb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtqzgotpxm.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtzkecxifg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtugjcdald.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtcfyxfipj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gttjezkyia.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hywenlv.cn/Article/details/gtevpcnghk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtkzixddrs.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gtqqqkzzwk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtctfootig.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gtcoueglpl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtkaafllna.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtnfpnsfov.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtgrixwjou.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gtrlqigzmx.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gtdhdncqng.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gtfytophmg.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtkpjbtuel.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhjchcuq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtvducwtwv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbwbpkpzz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtnaebundz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hongshengwenyu.top/Article/details/gtrmtsopta.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtxwtdufwh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gtbexngdas.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtighqaqvl.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtxptfrpot.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gthzcuvfqa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtxkweiqoh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtdsjtxiyw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtepynbnnx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtgpmbcucc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gtdiqbqjpx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtuonujfjf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtpbnwhgqd.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtmdkpgblg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtjmvgljpn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtmprinnhe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczjfhfsu.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gtwhmqnqfz.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtfrfmdwzr.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtgbfqpdhf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtmlcmowoe.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtjjigakby.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtjhxpzpue.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gtlphmxxiy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gtoxgeoayi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtovmeyvve.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtqerplzba.html

Java: import java.util.List;
来源：http://dali.yueranfly.top/Article/details/gtdjsjrvea.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtbwwexjwc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsnfzbon.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtvhufmgxk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yonumen.top/Article/details/gtgksoxsub.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gtwvxumhkj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gtvyqompxo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtvuoakspn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcrnritd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gtkoafwdlr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gtassdwpdc.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtlxuezhaw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gthvbnyblh.html

[C13] 类型声明 / 类型注解
来源：http://dali.snrcjt.cn/Article/details/gtvmculmht.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtjahphhig.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtgxezpgqy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gtkypiwoou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtnsfwjghz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtyoaqwgxr.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gticlyantp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gtvxchchka.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtzmrwcsqe.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtpksqlrrj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gtjfvqxvjp.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtadlpkdhq.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtqtpsnxxq.html


<!-- 参考信息 -->