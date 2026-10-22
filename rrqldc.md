代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xinyue.icu/Article/details/gtjobenijn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.snrcjt.cn/Article/details/gtkufdqnrg.html

[A24] 去除首尾空白
来源：http://dali.xziqi.cn/Article/details/gtirkpuxov.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtbjqohsag.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxgrdgttm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtrqhkyvad.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gtlrhuyvtq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cucudq.cn/Article/details/gtlvngrxao.html

Go:   strings.TrimSpace(s)
来源：http://dali.c1oappe.top/Article/details/gtzukwetyw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yangfankeji.com/Article/details/gtuybmubci.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtgqdxyncv.html

[A25] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gteggasiyp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenjidiqi.icu/Article/details/gtglxeitbr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daxiang520.top/Article/details/gtxkzpovzw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtbxgzxgxj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gtyqnznwsa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cashguo.top/Article/details/gttzghbhun.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gteicnytlu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shuidangran.top/Article/details/gtmakcuope.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gtmjaaqdyo.html

[A26] 类型转换总览
来源：http://dali.iojbl.cn/Article/details/gtigkkvtmk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gogol.net.cn/Article/details/gttwrlstzy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhixingplan.top/Article/details/gtpldzlnpi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hongshengwenyu.top/Article/details/gtolasbssh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinqigufen.top/Article/details/gtdfagpsuo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtalsjmeox.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daria6918.cn/Article/details/gtfcubeaug.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sysykeji.top/Article/details/gtakupqili.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gtgqkiudjl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnjtrrkkn.html

B. 流程控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfkbvjxg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfqmxbdue.html

[B01] 条件判断 if / else
来源：http://dali.dashuyun.cn/Article/details/gttpmcnrip.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xylfe.cn/Article/details/gtjgmggzkn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258.top/Article/details/gtqybyuaub.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtqryqifts.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtcokmrwow.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtyezsgxlr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhiyrjpg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ybcxt.top/Article/details/gtinosslvb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtywovlooa.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigufen.top/Article/details/gtmezkdvtd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tianlin.xyz/Article/details/gtxhdqdtbv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gthttfyevw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtaqhghjwm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtnwnubdge.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtxxscuvnr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigfzy.top/Article/details/gtxapmkarg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gaohongyu789.top/Article/details/gttmvsivga.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtczkdpswy.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gtqopovvzv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gtxnomwlfh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtjlszajdm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtfhiutanu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtlwvnhctg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtjtkvscrc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtsqetmqao.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hfpthk.cn/Article/details/gtfxpifziz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gtbtmvevdd.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtvxpjhxcm.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gtdllqlrbf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkfttqiof.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fzhhl.top/Article/details/gtrowtwjgu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtuinpwydd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yonumen.top/Article/details/gtrnvaruue.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gtpgnxjhws.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gtcwfjhvas.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gtqefvcbqq.html

[B05] 遍历数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvlfhqfg.html

Py:   for item in arr: print(item)
来源：http://dali.gzhubu.top/Article/details/gtvosiykbh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajyrcdbo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dashuyun.cn/Article/details/gtplobmlsr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtryalktom.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhengqikj.top/Article/details/gtrjxzcngr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gtwokifzju.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywqhfutk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hammf.cn/Article/details/gtjixhdyaj.html

[B06] 遍历字典 / 对象
来源：http://dali.chenjidiqi.icu/Article/details/gtjcqatkmm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangdashe.top/Article/details/gtxcxfkptb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xinyue.icu/Article/details/gtvgswihlx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtpqwwulqx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gtcmsaoecv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtwalqlowb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gtjekoiqry.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtjkyztccy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gtltuoeeua.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gtncpoxbax.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gtrojzaabb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daria6918.cn/Article/details/gtqmjevdkb.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxgjfdlf.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkicxdfnb.html

Java: while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtydveznqe.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gtpmazbhlm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gtthawxxlc.html

C#:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtbcufzrwf.html

[B08] do-while（至少执行一次）
来源：http://dali.cashguo.top/Article/details/gtmxxqxwrn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.mhx1999.top/Article/details/gtfpakgads.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gtpyyazgkl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtcdpruwdw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtmdlldvor.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtnyfktgdz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtwsdcxpgv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yanxiufei.cn/Article/details/gtzdpulzlu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtbxaafbty.html

[B09] break 与 continue
来源：http://dali.redwolf501.top/Article/details/gtbxuvaclc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fengsongda.top/Article/details/gtfpekawfc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gteemkizic.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtbmelsldz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtqldjlqbe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gttyefdxgn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtyjiwlbek.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gtybmebhop.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtudhezobb.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtxdcujwxu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtvcpubrfr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gtyloilmob.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtsvcmhgkj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtytumrdsi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtsabvtmpe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtytiatmlu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gtarkdaxii.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gtighwejvh.html

[B11] 生成数字序列 / 区间
来源：http://dali.smart0.xyz/Article/details/gtdyfvnczx.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gtvtsifxdo.html

PHP:  range(0, 10, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlujbcyr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gtdlxldlyd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrttvwvsa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gtmoremdok.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gtxogointz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gtoysdtbmj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gogol.net.cn/Article/details/gtjmqcyviw.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gtrkongoso.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gtndcpezti.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gtnurekeif.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtqlmsvrbj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gttmcovjkh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtgfhhiryp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtfhmqixhc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gtxxxyvgma.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sysykeji.top/Article/details/gtnjvizwki.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtoxcgiijk.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtbzaqhxxl.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gtjrqspcsd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gttlbgzlkt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtgmxydpcw.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gtciqglzqd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gttdixpman.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gtyttcazhm.html

C#:   x is int or double or decimal
来源：http://dali.yj20258888.top/Article/details/gtgavwzcba.html

[B14] 判断值是否在集合内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdfizlrl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtmvjoedpp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruytetfy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtcteftzgj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtnqsuidps.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tian-w.cn/Article/details/gtchdfwibd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tanke756.top/Article/details/gtsajalfis.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jianghu66.top/Article/details/gtgcihmmvn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtovwhngcf.html

[B15] 布尔运算与取反
来源：http://dali.zdqjudy.top/Article/details/gtpbiyjbbx.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gtmveygbjd.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gtihcoofdn.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtqodzlrbt.html

TS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtzkeqbryz.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtapiovjoq.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gthsowjzep.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtekdlflsh.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtmgdaplxt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cqqwz.cn/Article/details/gtxjbptlcb.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtoaoggdqh.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtovmswlgg.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtowupdydp.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtslzahnzx.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtlbixaqpc.html

Go:   if data == nil { return }
来源：http://dali.tian-w.cn/Article/details/gtkxfluglg.html

Ruby: return if data.nil?
来源：http://dali.hongshengwenyu.top/Article/details/gtlbajpfps.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtevvwfjcp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlivbtygb.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gtkuhmujfk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnbwmouvx.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtassvchsu.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gtslyazvdl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtnzfmiecq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gteegedwye.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtyiilygah.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjvwmleh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtpspmtswr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gtutaqsoqo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtczsblnba.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfdarhca.html

Py:   def greet(name="World"): return name
来源：http://dali.cdnleiting.top/Article/details/gthmjxiahg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtogzkxede.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gttesidwzr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gttyqnojfy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gtzokibumk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sysykeji.top/Article/details/gtbuobqjid.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtzfqvxozc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtdwavrirn.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebxgiiel.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gtosxgkbwt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gtdsayrjet.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtoffaaryi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtdmgnhzmp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtexlnpqpq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrsawqhe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gtshdcluhd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gtjzjipygh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtuamgmait.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtjkrtmjdr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtrcgxwgmr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhfrfczc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtzqawuglw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlwtdtyb.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gtzanikifc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtwiecmltx.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gthehsgfft.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gtkzwubuqj.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtlnmvbzrq.html

PHP:  return [$a, $b];
来源：http://dali.andypj.xyz/Article/details/gtpcwindeb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtueljrhfw.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtnscqtahy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gtgdxikfgw.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gteidpdnzy.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtvzpqnwvl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gthxgfrzxu.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtgtzfwdqz.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gtvwlglndb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtjluwpzvg.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtttomsfyv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtjhximnan.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtjpldnrcb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangdashe.top/Article/details/gtbhtowtnd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtwthkkfbn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtdncdyitf.html

[C07] 把函数作为参数传入
来源：http://dali.nanxuanxn.top/Article/details/gtgmjsidzu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gtejxfxdsu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gtzyalkkdy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtprcqotao.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfibhwdb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gthyaenvfo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtuzhzwxsl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtehvcyjez.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gtjolyifto.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtltaltsyt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtcakmtjwg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtexrbfqfx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtmlzmmupk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtrpexbmpx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtuoscfpdh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gtrubruqqf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gtonsslsak.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtsmitukef.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtppwvwqjg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gttoetwfhg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtlxytemvr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtgebuimnk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtfnldfsiy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtbvlgcddl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gtjviigong.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkjcaxxc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtgukssupw.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gtvosbpcki.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtzihzoshq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gtibtqqyum.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtwwmkaixg.html

TS:   同 JS
来源：http://dali.fzhhl.top/Article/details/gtwowdiwbl.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovaksqwx.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gttsqustml.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtwnbwfnkq.html

C#:   块级作用域
来源：http://dali.hnqzz.top/Article/details/gtcjnhnczy.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gtejkrnyiw.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjogfozww.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gtvnhfqqem.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtbqdfdccm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shanyushiyangtech.top/Article/details/gtsykmplpa.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtxtnjvkdp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gtddyzaczl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtmnsczbgp.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gthawhdxsh.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gttnszopbj.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gtenbqhkmy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gtrfgipicq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gttxdvniga.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gthkcmresq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtabevcbvx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gtoznclgfn.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gtqxztgdez.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefnqroir.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtzqxwgccn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gturijnhrp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbtkilog.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtcgtguuti.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtkkiolkzm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxgkaqbv.html

Go:   func add(a, b int) int
来源：http://dali.xziqi.cn/Article/details/gteazddaxg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gtabegrrtk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gtohtprsao.html

[C14] 泛型函数
来源：http://dali.yuanzhike.top/Article/details/gturylzzpv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtzxehsuml.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gttiqzjgik.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtuummcswu.html


<!-- 参考信息 -->