代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gtmmqidnmd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aizwys.cn/Article/details/gtuzfwuyro.html

[A24] 去除首尾空白
来源：http://dali.yj20258888.top/Article/details/gtxelgfjjs.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptcogpuh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkgogtltu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtelrtyurt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gtwszieogg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.guannengcc.top/Article/details/gtdappyidb.html

Go:   strings.TrimSpace(s)
来源：http://dali.dianchejie.cn/Article/details/gttzzvldgh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.feifeiyinyue.top/Article/details/gtetfsqhzp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtnbmnzicp.html

[A25] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gthpmkxjrc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvifqpvs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gtbjooacpe.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shuidangran.top/Article/details/gttfeiqhwh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaamlbue.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtpdnzvmoz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtrdkcpssa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hysaishi.cn/Article/details/gtpylcbckl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gtslyrvfuh.html

[A26] 类型转换总览
来源：http://dali.hnxiangtu.top/Article/details/gtcoqpimkw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sweek.top/Article/details/gtgucjjxad.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zdqjudy.top/Article/details/gtllrytvil.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukodgakd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtlworttgk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gtmdmehitb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shangyingyoupin.top/Article/details/gtdwbpzrfp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxuanxn.top/Article/details/gtouxpepja.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnjcvaws.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtydialbuy.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gtsdwiuqbb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfcjdgspa.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gtdumdnaov.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yongpay.top/Article/details/gtpcleooex.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvozpaxsy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gthndfazvq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtzshevyuc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtpilztgzq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yongpay.top/Article/details/gtzucqvwvw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gzhubu.top/Article/details/gtkdxlszcw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtrezkasek.html

[B02] 多分支 else if / elif
来源：http://dali.jqgfzy.top/Article/details/gtqiqusylk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gtfqyrblsu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xylfe.cn/Article/details/gtrshsrkys.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtombhdgqn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gthjxjtoyi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gttnsgodhr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dashuyun.cn/Article/details/gtxixqdhso.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xylfe.cn/Article/details/gtmfjhanww.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtqbjfyjbf.html

[B03] switch / match / case
来源：http://dali.ehwqpu.com/Article/details/gtkwcrhxkl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xylfe.cn/Article/details/gtviiugwgn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtmyaorcfz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtvuyvupur.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gttqxpwhpg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtonbvqlik.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtclsaipsx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ybcxt.top/Article/details/gtkgsgdglj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258.top/Article/details/gtghqhzcrv.html

[B04] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtikbwppsd.html

Py:   for i in range(10): print(i)
来源：http://dali.jlsjyb.cn/Article/details/gtvsbhegqk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgfzy.top/Article/details/gtvrykwkqi.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gteqetzzdn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gtpxxbwqep.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtkltxinsx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgixgcwt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pengpengdd.cyou/Article/details/gtmfamheux.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtuihkenuw.html

[B05] 遍历数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtocuhlbix.html

Py:   for item in arr: print(item)
来源：http://dali.tanke756.top/Article/details/gtulnuttai.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtshqavvrf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gttjzhggcj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gttbktvapr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gtayejxovn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenjidiqi.icu/Article/details/gtbaahnfhk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gtsvsmkjlg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fengsongda.top/Article/details/gtuguewebp.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigufen.top/Article/details/gtdupumiuj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gtqfrwwayq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthrjzksod.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtuixlygnc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsenxdxzw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gtuhoindrp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xinyue.icu/Article/details/gtwkmxwfdg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shangyingyoupin.top/Article/details/gtwaoppcax.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gtqlfajcat.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gttsarlyiy.html

Py:   while i < 10: i += 1
来源：http://dali.jqgfzy.top/Article/details/gttoqeltio.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtbkqftbpi.html

JS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtibneahwj.html

TS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtznaxwnpk.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtdjcdlbmz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtuopiwmbf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.quarkkingdee.top/Article/details/gtaraxhlcr.html

C#:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtttmgehgn.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtmlrvsish.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtvoqvebdn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwpjplkr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtzbcsaenj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gteipssrbb.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtqwyqkgqh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtsxycckuj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwreddcs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtzpgumitq.html

[B09] break 与 continue
来源：http://dali.ppjwa.cn/Article/details/gtnhqlwsqg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gtixfcaaey.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtanlzmzif.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtjhkiipez.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtilbofprd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvenjtnvr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtbhkbfirf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gtdylcojvm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gterypjkgx.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtmdzsuusu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtcuygyrnd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gtchgacrbf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtifwcurxq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gttpgzxbwc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gtpbmpzfnz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gtvbnixtqc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigfzy.top/Article/details/gtgtnjslde.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gthmdbzhah.html

[B11] 生成数字序列 / 区间
来源：http://dali.guowangkeji.top/Article/details/gtqepaqpjc.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gtxjifbafv.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gtjlzlzusf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtimuhykcv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtvdclljtf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtcnrzvexx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gtxhktrxlf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gtjyjdmzcn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtygpetsur.html

[B12] 跳出多层循环
来源：http://dali.ydzc1.top/Article/details/gtlygdgcuj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tanke756.top/Article/details/gtbofhnqhk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhongyouzk.top/Article/details/gtwudiaugz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtrogkwmgy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtpmbtsqqs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtzegbshsz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gtzqquyubf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtbvyhgsnp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gtplkywsdz.html

[B13] 判断是否为数字
来源：http://dali.shangyingyoupin.top/Article/details/gteupdjuik.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gtrpxrfuzf.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gtishyruez.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtrscnqdch.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gtgwvjhoif.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtwamejapc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstemzrra.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtpqysbpqj.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gttufkrwid.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtdqtlqpvt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gtwexpsvuo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aizwys.cn/Article/details/gtesagnchz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtgtjmfmvv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtfkfltrit.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gtfjjsxfww.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gthnfhjzqs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtmxtkaohp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gthgubkjyb.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gtzstxjeay.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtuqfdhury.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtpajmsisj.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtbyamtlxw.html

TS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhclhzjp.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtccsulqvc.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtokkommko.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtkdlqasza.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gthflkmnyx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hammf.cn/Article/details/gtikvngnab.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gtwrvsreno.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtzxcgmhkk.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtkvzyfkea.html

TS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtwfnxgkhm.html

Java: if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtukkclpaa.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gtkqujkjig.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gtfzhrvuhd.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtskykhysc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvsnxjekc.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gthctzawyf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtefsoyuok.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gthogzqutg.html

Py:   def add(a, b): return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtymgmvgbd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtwkxxrlok.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gthxnptswj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gteaxbslcr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtdalwureo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtiicoqyth.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aizwys.cn/Article/details/gtfgjdlgws.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtfxgcoxrf.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtixzgowgs.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gtrkehnaoi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgvtjgnh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtnilptyrq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkekokcpm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtsdxictxx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtuyexdlbu.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbxmuegx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gtoplzurat.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gtkbohpupl.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gthvrbzwjt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gttvrjhsru.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtqcwavzsp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtubhukafc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gtkkazpdtf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtghajmfgz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtgkdjkrcx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gtpqgqvosb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenjidiqi.icu/Article/details/gticyeodyz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtqbmfxnok.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gtlvltgsfx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtwnoqztum.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtoqqxklyk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.0kj1m.cn/Article/details/gtvycogmhe.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtusjbuuax.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtithnhhho.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtquxkwuaa.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gthjdsxkzc.html

Py:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtxbmmpiyd.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gtriwfuumf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtpjalitme.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtwzjabdgw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gtixovteiu.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gtdvijgkee.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gtiqrtwekc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtgzqtydhj.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtbijrebgy.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gtyzosxppt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtdxuxvthy.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtyveldhwc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtttgychfo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtdxvjpmjv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtfabweskp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtpqpntlyq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtlwccgtsm.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtgznuqguj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrlvqhra.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtrsgcwrzk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtmjivftrm.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtcbqecjmi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtnxactwln.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gtqggylieg.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtdhunkphg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gtcabpwqtz.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtzsxnezlp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtnzgcppsh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtnkkhkmhh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtxfmfzgsx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtvppjxuoy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtkqbpqlvr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuanzx.com/Article/details/gtxdtckknx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtjqobqujr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuweohrug.html

[C09] 递归
来源：http://dali.sufxvd.cn/Article/details/gtahltbkja.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtuponvhza.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtyeqtawsr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtyxvbmflo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtddiasybv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gthyjascfn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gthgpfpumt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtcfolekxy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gtvpfhmdhj.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gtrcojvjyq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gtvqfwkdsj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gtrynywvfc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtrzfenchv.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gtmuyctpxr.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtfniravet.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtamecehhf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gtolrrplrq.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtaqlkcetz.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gthuszwfif.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtuhohjrdw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtkkjkljmm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtjxxgrxkk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtpkvaijkr.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtevnjzwbu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlyqptiw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.vqdsnc.cn/Article/details/gthwynrucl.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbjjstqw.html

[C12] 立即执行函数 IIFE
来源：http://dali.ehwqpu.com/Article/details/gtcqzrttfy.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtkgedmcuc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuxming.cn/Article/details/gtroxnwzwp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gtgzilvces.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtlxazuphd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gtqdfzttmf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gtpfygsdvn.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtewijsmsp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gtsmftkbha.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcsofwaup.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gtkuujhxnq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtyibadueb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtmtyehezv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtyggibfnh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajclqooi.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtqffwpcpm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gtwcgkvmlm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtyrapphzr.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtcykfoozu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtipqlsypk.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtydeusubr.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtlwptljmt.html


<!-- 参考信息 -->