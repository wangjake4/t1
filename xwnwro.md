代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.vqdsnc.cn/Article/details/gtugvcquua.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daxiang520.top/Article/details/gtfpmczvwx.html

[A24] 去除首尾空白
来源：http://dali.zhiwuduotai.top/Article/details/gtbwobbrzv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tanke756.top/Article/details/gtczaefoca.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gtbvxlnnrt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tanke756.top/Article/details/gtuskbgflf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtyawgkkgc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.birdmap.top/Article/details/gtllmpsxpu.html

Go:   strings.TrimSpace(s)
来源：http://dali.zycfv.cn/Article/details/gtezgtpzkp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.dashuyun.cn/Article/details/gtcfxokhqd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.iojbl.cn/Article/details/gtywrsqdud.html

[A25] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtckuqdonk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shuidangran.top/Article/details/gthtewbfmf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.quarkkingdee.top/Article/details/gtqednnyxk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gtxyzonecn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gtvubraanw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxthggatq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtslwsgwcv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yonumen.top/Article/details/gtmtalcwpr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtkzqcycgv.html

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gtqsnlnboe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cashguo.top/Article/details/gtnaaaglhh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jyoumei.cn/Article/details/gtivcfwkna.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fengsongda.top/Article/details/gtgpyeayoe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gtjnkvxuxp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtmguhoscy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhijiandao.cn/Article/details/gtkmoswbmy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jqgfzy.top/Article/details/gtfggybtuh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtwsmfewjv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpuddyetb.html

B. 流程控制
来源：http://dali.yanxiufei.cn/Article/details/gtquqwgfxo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfpexlggr.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gtsgkmttmt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sysykeji.top/Article/details/gtedfxqtkm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cashguo.top/Article/details/gtjcicxrob.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtturqirfl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtemdqtzbh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtptqcdraq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gtjzsmdmvj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.vqdsnc.cn/Article/details/gtvyaedzpd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtpmshgapn.html

[B02] 多分支 else if / elif
来源：http://dali.jlsjyb.cn/Article/details/gtwmvvypbz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yueranfly.top/Article/details/gttvscnkvb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gtsuwbeled.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtfmlowtum.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtcekebdkm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtlumncvkx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yangfankeji.com/Article/details/gtbcazzgax.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.kuanghao11.cn/Article/details/gtgbqlnttm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gttrmqcsgs.html

[B03] switch / match / case
来源：http://dali.fengsongda.top/Article/details/gtutomlmrf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gtsatnplhr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gttiqbluqe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtpitvlskw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtktcheskr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtvevsnvft.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtgcwqxclx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cucudq.cn/Article/details/gtjncumisu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gtlwlfmolo.html

[B04] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcjmvqqy.html

Py:   for i in range(10): print(i)
来源：http://dali.snrcjt.cn/Article/details/gtfovfukmn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sxryk.cn/Article/details/gtdcevqimb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtpxxreyar.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqxnysuc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxybomsae.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daria6918.cn/Article/details/gtefxwdtop.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhengqikj.top/Article/details/gtrcfinhnr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenzaomai.com/Article/details/gtttdekngn.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrtoereu.html

Py:   for item in arr: print(item)
来源：http://dali.andypj.xyz/Article/details/gttwnbusec.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yvedp.cn/Article/details/gtswjofuso.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtnhgavtxr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cdnleiting.top/Article/details/gtlhgtwsdw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gtddpqjmxt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtivxplp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenjidiqi.icu/Article/details/gtqjxdobfl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiglbmin.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtcknegswd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gtftvshcio.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.meibo888.top/Article/details/gtdsdkbwdb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtkbpjlprm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gtwldpeeer.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhixingplan.top/Article/details/gtkpxrywra.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hfpthk.cn/Article/details/gtynsrbmjd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gtifhebjbf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ppjwa.cn/Article/details/gtogcrmgzc.html

[B07] while 循环
来源：http://dali.shzxlz.cn/Article/details/gturtrkbmi.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gtdcdogzqs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gtjqabtuil.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtiikydced.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxiassxd.html

Java: while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtumqtupyy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenlongwang.top/Article/details/gtmxfbjwgm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ybcxt.top/Article/details/gtrsbqtmih.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkftobprf.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gtehkyhwzs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gtmxphqghs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtwyllsamn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtlahjrlbx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtxcisxknt.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtoafwitwv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gtobxlshrk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cashguo.top/Article/details/gtuvvcdult.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtqjmufpff.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gtxcgfhghe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gtyugoyxxc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtcuwpfibs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtamgbqmgm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtitbmdyal.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtnshkncyx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtgxwchuef.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fengsongda.top/Article/details/gtkyopwsoc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtqgezlczk.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258.top/Article/details/gtsdztabri.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtilamocsq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xylfe.cn/Article/details/gthkhvzqnn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtitmhugkc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gthkbsuqbd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gtnpriorsf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gtztkmvlhh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtmgehwycs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aibaodan.cn/Article/details/gthtclkqtj.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtltthkibp.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gtzmmrkpzy.html

PHP:  range(0, 10, 2);
来源：http://dali.sysykeji.top/Article/details/gtizhzaaio.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtxlbhfpfq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtygzbjszy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gtbnzkpabd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cucudq.cn/Article/details/gtebekpkbm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hywenlv.cn/Article/details/gtyhvstnbd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtneaajgqa.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvjqffej.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpbezglx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gthwogwnuj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghjlskne.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtgrnucyqu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtsrwynbgh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtanaajksc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gtitltwzvc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gtskgygdef.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gtzaqrcnvp.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtnzzcvodz.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtedduzqjl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtjoujboyw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtrfzydtua.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gtaektbkpp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jyoumei.cn/Article/details/gtuuagjdpw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gthsnmxjrr.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gtqwqwjoww.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gtynljwvkg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gttvoofszu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yanxiufei.cn/Article/details/gtskqkiimn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gthdhpxkng.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtwxqebzja.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtaacnhhmb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtlgbrubcg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtieumowem.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtqaksumcf.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtrxlkvbgj.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gtveyegxez.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gtwbkvuxxa.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtzyxqboqt.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gttqveakds.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gteczaavkg.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtgfyyxidt.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtxlwzwzni.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtjimilxxt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtltdajxie.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gtcqhpxpji.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtdipdunwi.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtzlarqyza.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocmtcdnf.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtevseitwr.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gtlrvmjbjb.html

Ruby: return if data.nil?
来源：http://dali.cucudq.cn/Article/details/gtrnyevdxl.html

C#:   if (data == null) return;
来源：http://dali.aizwys.cn/Article/details/gtowqssnok.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjhshfpok.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtiajunetm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxjmpydgn.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtynmgqwyb.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtpyfhfrdo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtpifgeiaz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtnpbwmswz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtlirpuurx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtxrdexygh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtdpcwaert.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtezgeawfn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiwwsnppy.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gtzhpjfxjz.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtecyurafe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhixingplan.top/Article/details/gtsflubqhn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtjbgccvyf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtfoqwsxym.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtircexong.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsdmavnv.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gtuhagwiib.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gtydkmdioc.html

[C03] 可变参数
来源：http://dali.sufxvd.cn/Article/details/gtrswhbpuu.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtkkkxxhvz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gtfdepvdns.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtpcxbhdne.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtpnsujeea.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtgbuervij.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gtosjyhipa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmetgkes.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gtynexldds.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gtkfnhgjvp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.kuanghao11.cn/Article/details/gtgpqyyquo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtzmdaczil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtyukzztzr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtxkfnlpvd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtqtttdqma.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gtcrtisjyj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gterenqkiz.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtrrinaeac.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtyjnxqjtb.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtuxfbbfbc.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gttzuffhhg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtksqufxjq.html

TS:   return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtidxuampl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gtknpdrmcn.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtsdmgyduz.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gtklherzrk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtjignmqeo.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtsvjosmwd.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtwjxkhibf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtomayriiw.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtjbcxqbje.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gtozqoqyoc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gtpgelbrai.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gtjiiotscr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtrfoszocy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtomhoxgrk.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltjzpmrs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gtbaadioge.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtcxkunmos.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gtdsyqroms.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkupnqxr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gtpanfmhwo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gtcpzhdnor.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtiizhqysy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtpqvorffi.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpsriavq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtqfwtngbd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtexorvtwa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtderaoubq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtmyhlxvfo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtxrnjvkuk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtvxjrrith.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtgbjqagjq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtaxabdqoh.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gtnwybuwzj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtnfysgwmi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtxhggmusj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtnaierqnf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gtyjwcqret.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtpskelfgt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gthchhmjxd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtloigjrpe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hywenlv.cn/Article/details/gtapfhoeqe.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtlkrpbhrg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhixingplan.top/Article/details/gtuxlwtpcm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gthfpqekfj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtgraydlxk.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gtknmyqhet.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtinunmeik.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtneevoxzi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gttsbthmef.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtltzvjtzu.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gtenuuppjt.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gtmiieoeef.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gtcuydavyb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtvzvutaji.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gttrjtyrzr.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtcmjgjrfk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gtuvsnrqpn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gthypurzsq.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtmkrillae.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtrgxcepbj.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gtqshfbdbq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cqqwz.cn/Article/details/gtvqytnixj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtaazwcyvh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtlqbpzmox.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtndzowltr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtjndxkvhg.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtdppuemra.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gtdbubizby.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtdauuazhc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gtdrpshsin.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtkaagsapc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hywenlv.cn/Article/details/gtiigaiznh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtgnkkqzzw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtmhpludze.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtnyngnayx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gtoojotruv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtbnxyaqmy.html

[C14] 泛型函数
来源：http://dali.pengpengdd.cyou/Article/details/gtzwnthwzb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtfcfvaczq.html

PHP:  // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gtarlbcsuo.html

JS:   // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtotozprmr.html


<!-- 参考信息 -->