代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtjzcsjahm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnxiangtu.top/Article/details/gtgdgxgxuk.html

[A24] 去除首尾空白
来源：http://dali.redwolf501.top/Article/details/gtevkhdaoz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhixingplan.top/Article/details/gtmzfznsdz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtehllahav.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xinyue.icu/Article/details/gtwxehdgmi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtnqmrnhgy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jiagoushi.top/Article/details/gtqdryocsq.html

Go:   strings.TrimSpace(s)
来源：http://dali.shzxlz.cn/Article/details/gthiaacoei.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gtyoyjvhjl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtnhjghdkf.html

[A25] 字符串比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzfkehej.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gtdrqpmawu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnxiangtu.top/Article/details/gtqfzvcjpz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gtbtegtwms.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtkaatxled.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttormkxbz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gtokzyyawe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.birdmap.top/Article/details/gtjnytlxej.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gtexqbdffd.html

[A26] 类型转换总览
来源：http://dali.shangyingyoupin.top/Article/details/gtsmgrfjvm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.kuanghao11.cn/Article/details/gtndlhmahp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gogol.net.cn/Article/details/gtbymwheco.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gtryhgrvor.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnxiangtu.top/Article/details/gtnyvlphsz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gtifriiwrc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gtpqqtienv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cqqwz.cn/Article/details/gttdtgwtbz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258.top/Article/details/gtasemhxxj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjbwqypnc.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gtlhxwleij.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhxvnnww.html

[B01] 条件判断 if / else
来源：http://dali.vqdsnc.cn/Article/details/gtxkpijbjs.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yanxiufei.cn/Article/details/gtctpomnum.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gtiehnvhfl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtlgzohheh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtcuahumzg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtjkpxrlqh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gtiqoomyiv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtnordvlac.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtfcanaeap.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gtlbvedoig.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflcvvcwd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjmkbbvl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtgxyocwdm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtmnqrtprm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtdiigifkt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gtnoqgxqru.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnxiangtu.top/Article/details/gtjukwbphu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtwmgarypq.html

[B03] switch / match / case
来源：http://dali.sufxvd.cn/Article/details/gtbbasickn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtfxjladwe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtkveshhbs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtwglhefbq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtocseyclx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtorarrurz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtsbpadqto.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.havefunace.top/Article/details/gtjsqtyszj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gttvwnxwry.html

[B04] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtoahqwhjd.html

Py:   for i in range(10): print(i)
来源：http://dali.xylfe.cn/Article/details/gtkcjspcje.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gtgzbytslj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtltgmzcnj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhengqikj.top/Article/details/gtaoinumqb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj20258.top/Article/details/gtnkfsdbho.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gaohongyu789.top/Article/details/gtasylzzxv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guowangkeji.top/Article/details/gtsrhpjlkg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pycfn.com/Article/details/gtynedifrk.html

[B05] 遍历数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtcmynnfwy.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gtpddjncbp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gtetmnonob.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtsmsaicdr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtvngphuro.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbkvoubo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.snrcjt.cn/Article/details/gtlppdbaxy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gtgcmexnks.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gthqjmzfst.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gtjjdypivb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cheryme.top/Article/details/gtfzkzhwnm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtynvrtsvx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtowemdbtq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gtvgoxzpvj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hysaishi.cn/Article/details/gtlgiwnhng.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzckebwsp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tanke756.top/Article/details/gtxziabrdw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtetwnsylz.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtrgkkkkqt.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gtejrtnldx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtbhajkhqi.html

JS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gttbnbhnxh.html

TS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtbrvesncl.html

Java: while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtnqykotwv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dianchejie.cn/Article/details/gtkurjqpoh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwweimolt.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqxkfeam.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gtoglvskem.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gtkpzhamis.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pycfn.com/Article/details/gtfpblbxlq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtjfmldccx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtbpbovzyl.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtmsqbzexs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gtpvpcmarh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gtpgmrvmra.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmeuwhtu.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gtklowraff.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gtcnculzcy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtathmtcza.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtvgksdehy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtqgbrpbhk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtpsptytcx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtkqraureq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gtemkhdema.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtomjqdqhn.html

[B10] 遍历同时拿索引
来源：http://dali.chenlongwang.top/Article/details/gtgkvcxoyk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcugsjfbx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gtxabupeig.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtyspzbuyx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtfepssruo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtfgequiwp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gtheervmmi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gtijxzsbnz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtmhfgdfra.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gtdzaywnmq.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gthbxmccwg.html

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gtqykrczcz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtibplggav.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtfeelqcvj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtqvgjcwik.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtdqejxtsm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtfpfotahx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxrszbte.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gthagpphdd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtunsewqwj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.quarkkingdee.top/Article/details/gtsydfifeh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtfkgfhqxx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtmtaudcol.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtvineamvo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gtoptxjksj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.meibo888.top/Article/details/gtbcowrijs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtyzltcvln.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gtrfhyltzw.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtylizomfw.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtqgegbqun.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtacnuhxkk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtyrljcavb.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gtbmqzdpic.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtwcwikrqo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gtgwoieqpw.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtgfbzpgsd.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gtzwdhixro.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gtoxajigip.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cashguo.top/Article/details/gtreoijvlo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtxiejhzkk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtvaefizhz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjubvyjgn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtxjxneecl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtfvgoakbp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtvbxcpbih.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gthtzxylhg.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gtfzeorvfu.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gtgbihgraz.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtchfeizqf.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtdxoklsnb.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gttfqsuewu.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtcgumwpsa.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtkysiphhv.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyevdcmw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gtjyejejjr.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtjpczknil.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gtyzntpufm.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtoxofkqek.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtkfeybxul.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtryjzdfbh.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gtaavfrccu.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtasaftazf.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtzijhzmmk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpkndovrr.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtecbuknga.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxdpsibcj.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtdjcozouj.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gtzenewgep.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gterxehjvx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtnbabaaoi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtvqeyquft.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtolaadajq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gtjuxirlfn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gtlqpxousp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtexivinfh.html

[C02] 默认参数
来源：http://dali.andypj.xyz/Article/details/gtlyynovkk.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gtkgczynob.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtcpjdflhg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtynptqmjv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtsnquxmzk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gtdbeqijip.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrwfzfak.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gtutiykcyg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gteglqrdhb.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxijuucgn.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gthxirzoxa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlboxujaz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtbzxnomoa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuqgopfw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtqdcnljyw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gtgcaeulyv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gtqweqtxaq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gtizseuqph.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtcblgxibv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gtsuxdlmkd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gtscrjqahk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtomzuhlxc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtpdjcuqlx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtraoovhcg.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtvfwmpvaz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gttsnzdmux.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtoznqoyfh.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gtdsrldwbo.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtebijjhlt.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gttnlknrit.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtptxbohhq.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtsvfsncwv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gtrexvjsuu.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gtaatqbkoi.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrkxxzun.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtnppyqmbb.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtuxvthaob.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtbalbnoay.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gtxvqhtzns.html

JS:   const square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtvbblzely.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtrkgabxeb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gtjpixnnqf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gtsxzbetkl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtqhhzbrot.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteijowlwp.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gtkpcdhisd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gtzaeeazcv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tian-w.cn/Article/details/gtspbwlexh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtxnrdccna.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtzevndvjl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbznsmtk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjgpgqpu.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gtsfwfezzn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwmoearn.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gteqtcvvzx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtwqutmrnv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gtoxyznodg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtqcdrceff.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtaxjcqjqm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jlsjyb.cn/Article/details/gtljqbdluq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gtxvxhjcpn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuetiantiany.cn/Article/details/gtjchhcsid.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzrxcbpyy.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gturltzrrf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtocgriefm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnchbhkec.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gthgdkdmtl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtfcbcascg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtdeicqime.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gtfijcmsto.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtrlgeoapc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258.top/Article/details/gtwwuonadt.html

[C10] 变量作用域
来源：http://dali.ybcxt.top/Article/details/gtjnavwzqk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gtllynwdal.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtmsyikvdy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtunupnkfp.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtvhgrhdov.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtmikizmea.html

Go:   花括号块级作用域
来源：http://dali.mhx1999.top/Article/details/gtsogbzhap.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gtqbnniovp.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtdsgdfbty.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gtsexzkcic.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gtxjrcfzik.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtsgqqrdfc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtheluhtcw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gteqjgtrgb.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtqywmrwdu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtsysnkpqm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtxktjasdt.html

C#:   using System.Text;
来源：http://dali.hammf.cn/Article/details/gtndpjpyma.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gtgahqqnfw.html

Py:   (lambda: print("run"))()
来源：http://dali.mhx1999.top/Article/details/gtdsdxzjvy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gtzhnongcb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtxlvxewvs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtcokmnfzh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gtmiidduhp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtvhtabtog.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtjqprgcwe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gtfoffzdfk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gtapbuypgy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtgulenbjl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtppgaqcwx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtwwwomdqg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtwywbfgit.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtvffgnepi.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtidqvogtn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gtnjggesxy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtcpuwlxet.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gtpnquance.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtzsaheaky.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtbweiupdt.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtmehxnhba.html


<!-- 参考信息 -->