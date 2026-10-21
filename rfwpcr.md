代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtgdoxnqlv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nanxinkj.top/Article/details/gtycmfgykr.html

[A24] 去除首尾空白
来源：http://dali.jinqigfzy.top/Article/details/gtknumlhhz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenlongwang.top/Article/details/gtskvkvwwm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenjidiqi.icu/Article/details/gtfbwxfbqu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.9152youxi.cn/Article/details/gtiblpcykb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cucudq.cn/Article/details/gtsztdtrfm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gtwajgtpsb.html

Go:   strings.TrimSpace(s)
来源：http://dali.shzxlz.cn/Article/details/gtappfrgfb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ivvv.top/Article/details/gtygruxxbx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dianchejie.cn/Article/details/gtydquzhes.html

[A25] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gthaffvbza.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daria6918.cn/Article/details/gtwkrmzmgs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gogol.net.cn/Article/details/gttaoickbi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtecbqhpzp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aibaodan.cn/Article/details/gtqgeuzuoa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.c1oappe.top/Article/details/gttajhxevl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gtagjaotyt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hammf.cn/Article/details/gtbmtxbahv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.316326.xyz/Article/details/gtegnnedjh.html

[A26] 类型转换总览
来源：http://dali.hongshengwenyu.top/Article/details/gtiyzefjxx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tian-w.cn/Article/details/gtpukzbajx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgfzy.top/Article/details/gtpdohswku.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenzaomai.com/Article/details/gtmrtfjxzh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gtsuzcpqvv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinqigfzy.top/Article/details/gtcresftrv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gtzlyliijk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yueranfly.top/Article/details/gtlefgcjot.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gthruenpgk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttvzxtlca.html

B. 流程控制
来源：http://dali.tanke756.top/Article/details/gtysavzwki.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtpbpoyxqk.html

[B01] 条件判断 if / else
来源：http://dali.cqqwz.cn/Article/details/gtkygqjesy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxwyjnfw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofobjqhy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtgufvytrd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtzfbbqdzw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtwjsqieqt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhixingplan.top/Article/details/gtqblraays.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmllmsgp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtavymcret.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtacwamvhp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gogol.net.cn/Article/details/gtutacjsit.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gtafnjzigc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtpchovlrg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtubhpvjmc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtrzgcailn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gtgxmtagea.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dashuyun.cn/Article/details/gtxaduhylm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtidnhdogu.html

[B03] switch / match / case
来源：http://dali.zdqjudy.top/Article/details/gtsawxaqmc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtnnafgyav.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtsqmxfrel.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gtngvanwyj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtjbrhduzv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gthhqejjcj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtoxeqfqrp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.vqdsnc.cn/Article/details/gtcghrflfl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nwbrower.top/Article/details/gtgjnutwmu.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtnpckzsil.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigfzy.top/Article/details/gtdvghfhxq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tian-w.cn/Article/details/gthzmdszoo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtoepfpxiw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtizjsueqs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daria6918.cn/Article/details/gtjnfeoxfp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guowangkeji.top/Article/details/gtgwealomq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhengqikj.top/Article/details/gteywetslr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aizwys.cn/Article/details/gtcghcxqnk.html

[B05] 遍历数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtjsttbsst.html

Py:   for item in arr: print(item)
来源：http://dali.cucudq.cn/Article/details/gtdhqwrkyy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gogol.net.cn/Article/details/gtwsarrjhq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gtxyvtlssl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gthergydxk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtctpterrw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuxming.cn/Article/details/gtkdcelzys.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258888.top/Article/details/gtnxknnqts.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmyvlysp.html

[B06] 遍历字典 / 对象
来源：http://dali.fzhhl.top/Article/details/gtmexpkijp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.316326.xyz/Article/details/gteenzpoip.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtsabxxttf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtgvymvuhn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtxjfvetgc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtczxwtqyn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gtgzhhigty.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtxifaqjjk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tian-w.cn/Article/details/gtciietymo.html

[B07] while 循环
来源：http://dali.havefunace.top/Article/details/gtmjeppbmp.html

Py:   while i < 10: i += 1
来源：http://dali.9152youxi.cn/Article/details/gtsvrppqat.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yvedp.cn/Article/details/gtlfkuiwpg.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfetfjdct.html

TS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtsopkpyvf.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtbkenrqrf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.c1oappe.top/Article/details/gtwbucfmix.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gtzdoctpoi.html

C#:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtzlamkarp.html

[B08] do-while（至少执行一次）
来源：http://dali.zhengqikj.top/Article/details/gtgcisores.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gtwejeqxbj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtwlvzgvla.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtpyfqwfio.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtavaodrjz.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtsxvyawhj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gtechunuca.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gtourejsft.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtuqtxnfzd.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtryjhxlhd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxuanxn.top/Article/details/gtlsjtirfe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtioawowrt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtxbhyhvgl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtkqeshvww.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfuqywyep.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gttbiktzzk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hongshengwenyu.top/Article/details/gthylttqac.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtmioninji.html

[B10] 遍历同时拿索引
来源：http://dali.chenlongwang.top/Article/details/gtqdhgqxne.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwayxkmoq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigufen.top/Article/details/gtgcqsdacd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtgomtfimn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtgalckayn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gthwzfhavg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtjjezvmsy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtonfhjkik.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhongyouzk.top/Article/details/gteqeyavci.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gtitqmszjf.html

Py:   list(range(0, 10, 2))
来源：http://dali.birdmap.top/Article/details/gtedlfuttg.html

PHP:  range(0, 10, 2);
来源：http://dali.tanke756.top/Article/details/gtkqqllnrh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtekwpskge.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdathcuw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gtfpeuakzy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gtefpancbt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xziqi.cn/Article/details/gtuxfkmfjp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gtkvndbfma.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gtrhmyjtiq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daria6918.cn/Article/details/gttgdwyntx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gtajjelbow.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtevfhbtem.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtczsagzru.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtsnapabdz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gttzybayum.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gtutayrdut.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gtlspujvgr.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebaulnzz.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gtdibhnljr.html

PHP:  is_numeric($x)
来源：http://dali.hammf.cn/Article/details/gtalpeeqpj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gtixelhpqw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtpyjqawfo.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtzdrnldjt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gttaquwbrr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtjjzovtdh.html

C#:   x is int or double or decimal
来源：http://dali.jiagoushi.top/Article/details/gtfikdciuz.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtjhbkaplm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtpvwcovud.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtsrmyaolw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnhblbqcr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtobrmihjr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuanzx.com/Article/details/gtfjrwrutp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zycfv.cn/Article/details/gtebvrcqoi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtcsxuzjhy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtsvuybypn.html

[B15] 布尔运算与取反
来源：http://dali.haohaochexian.top/Article/details/gtzxssjehj.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtiobdbyuw.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gttlzbwfxn.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtrueyxqqz.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtuhiyeshq.html

Java: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtceieltqc.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtebcbzlou.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gthsrjvkyb.html

C#:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gthrwmuisl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtneeuufkx.html

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gtsixevret.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gtkfkcsqrk.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtigpiegpi.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtlqpzzalw.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtnpcysmva.html

Go:   if data == nil { return }
来源：http://dali.bjfxy.top/Article/details/gtgeewlpfe.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtlrpvwywy.html

C#:   if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtikejwvpf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttdkyyxgi.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gtymgdedjo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsiudiovn.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gthrtaugwf.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gtyfmuwmlv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtrrmccemn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtmqukkbmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzzyhocn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpldryqfv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtyjehxcto.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gogol.net.cn/Article/details/gtoypcracz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtanqcegqt.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtjwblrfew.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtfstmrllz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gtozvmnfum.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtwducnktu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtxjgnlixn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gtdpnxbajs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtyuumpejg.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtimfjtmal.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gtfjiczbyc.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyewxqjmy.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtfgoojmut.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtwxgbtydm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtxyuadujk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtytwrcvyd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gtjxjmowpm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtphfmxsic.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shangyingyoupin.top/Article/details/gtjyfzkyxg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtijcralwy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gtchbszvxm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtbachvuup.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtgqlicbfm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtrmsxfkch.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gttrydsxux.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtsmoapmhe.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtundvxwko.html

Ruby: f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtinxlfdwj.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzhlnmkx.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gthvdmhmry.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gthtxvqett.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtxbmuetns.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtrajjyjuc.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtcioerpwu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvddgygep.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtdxnjhyjf.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtawrwdkll.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gtcszuomeg.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwltxcked.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gtgajcfkpa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gtnvwfbsnd.html

JS:   const square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthepnzpj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gtogfusevd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtrjfzssqk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtrmjhaohq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtacbzpczs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtuumnygfj.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gteebzzcnp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkbgzett.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtloxvrudw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gtqvsnccha.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtxrzwtniq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhsvziec.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtpdzjebjh.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtfuhrwvzs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dianchejie.cn/Article/details/gtcvzwujqf.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gtvmdgfara.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtaiesdejq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gtjkrlkdyr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtfijmwnxx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtwkwpctan.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guannengcc.top/Article/details/gtopoumeeu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gtnlluulbs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.0kj1m.cn/Article/details/gtirifadcp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtzuaflzfg.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gtgehlvfqh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtbjlclrkj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtnpjhbgfn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gtauejxhxi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtvaxzlnry.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtzvknavci.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tian-w.cn/Article/details/gtjgpijmtu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtbjtpvgzq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gtzccbhmwn.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gtvdslfhzp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gtpnxrgxmj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenjidiqi.icu/Article/details/gtqqlknlpm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gtgculeemr.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gtmdwuyupc.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtzeszvghe.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtzbiiefir.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtrjcqdlnh.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gtivgplwle.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gtogvfxesk.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gtzgwavqee.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gtimwykgmz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtpkvxsmjo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gttlfkfkqi.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtoqdukbks.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtumbdvoix.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258888.top/Article/details/gtyomtbfgx.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtdymgqaoj.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtwnncawht.html

Py:   (lambda: print("run"))()
来源：http://dali.yuxming.cn/Article/details/gtkjcxrxkn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtfwnhqnvo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtbotkicgh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtcpseksgj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzwbehsp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtqwsyrgxt.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtbhsopfow.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gtpldpybtr.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtkrhhphzq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gthqarblxo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtjnqpcktn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtidwnjhbw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtvwbfnubc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuflxjyhw.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtwniqprts.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gtyifmzfhe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtaldjpvmu.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtmdbtvorv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gtknzwhogh.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtdkgkegld.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtgnasmacq.html


<!-- 参考信息 -->