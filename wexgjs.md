代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gtnmuzdjyn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gtjbtdegbl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dianchejie.cn/Article/details/gtrzdfzeja.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daxiang520.top/Article/details/gtgtphkqce.html

Go:   strings.TrimSpace(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzxjufajq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gtsamypwcm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtbanqblnc.html

[A25] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtujtkutho.html

Py:   s1 == s2; s1 != s2
来源：http://dali.pycfn.com/Article/details/gtlzufoikr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gtgfognplm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtnzdmizur.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxkqwmdpu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbklcrwoy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtcuelboiz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.feifeiyinyue.top/Article/details/gtuidjjuxh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gttadnthje.html

[A26] 类型转换总览
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjmhzuyy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldzyyvjx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhiwuduotai.top/Article/details/gtlhqvzbkq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tianlin.xyz/Article/details/gtltragjdl.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuanzhike.top/Article/details/gtrbdgmjvu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cheryme.top/Article/details/gtjviltarw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtuamkuwji.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangdashe.top/Article/details/gtzcbluvit.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yonumen.top/Article/details/gtnbbipsin.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnrmueyoa.html

B. 流程控制
来源：http://dali.smart0.xyz/Article/details/gtljrcenuc.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtiuswfeas.html

[B01] 条件判断 if / else
来源：http://dali.cqqwz.cn/Article/details/gtsapxkpjj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daxiang520.top/Article/details/gtmwlxsnnm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gtgxbftqoc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtlwgyhoif.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtbyuswsxt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtpzbpqool.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnqzz.top/Article/details/gtgercfovm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gtehmaibdi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtlhdgwngb.html

[B02] 多分支 else if / elif
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocrjfipy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gtsufnmdkx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nwbrower.top/Article/details/gtsqvijqkj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtvbmynbtp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtzxazpryh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtxnkrodve.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnxiangtu.top/Article/details/gtywxfwgsn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuetiantiany.cn/Article/details/gthowzpqeh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhivpvjb.html

[B03] switch / match / case
来源：http://dali.wangshuangyany.cn/Article/details/gtgfrdmezb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtuzgzyxxb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtqtnghpzo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtndvssksp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtvzuyisex.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtidiwcaeu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yueranfly.top/Article/details/gtpgzibbze.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnqzz.top/Article/details/gtzfkjmquc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.vqdsnc.cn/Article/details/gthjynetiu.html

[B04] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtdmaqivxo.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gtzeuqlfnq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.316326.xyz/Article/details/gtikfjhclf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtuesdncio.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtzapwfwdr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtorakkpni.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cqqwz.cn/Article/details/gtbziwahlv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhtdzktz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtzplfhguc.html

[B05] 遍历数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gteyiadjfo.html

Py:   for item in arr: print(item)
来源：http://dali.xylfe.cn/Article/details/gtekxqahjk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yonumen.top/Article/details/gtezhqyhmv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtypbbmzvd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtqmmampre.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ehwqpu.com/Article/details/gtesxfoozc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtexcnmfql.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sweek.top/Article/details/gtuldqrujq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gtyaccnufb.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gtbgrfenfa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shuidangran.top/Article/details/gtaogtnqzq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daria6918.cn/Article/details/gtvbbngdbk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtwppbiyqu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gtghdzjdsi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shzxlz.cn/Article/details/gtvozifezq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ehwqpu.com/Article/details/gtdnmxdlzj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fzhhl.top/Article/details/gtfnjbpdut.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxinkj.top/Article/details/gthbnftzga.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gtnmcbjzji.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtrlmucfkw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlkqguvq.html

JS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtzfpxrgqi.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtxrehghuu.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtrxhtggur.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gtupdshtxl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.havefunace.top/Article/details/gtzlmeqrmw.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzurupkml.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtvucbkarm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtwqehkzqk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gtafzzemxs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gttxdgynck.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtwkljspzl.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtbsmutssi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtvselvllw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hywenlv.cn/Article/details/gtrynqllpw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtggiqlfwo.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtcdrhvihb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gtpksrcscb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gteynxiazg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtrxtcnhhe.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtwmwroxtu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtuthbpbgy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gthnswczjk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gtjlzbxovk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtksjujvcf.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gtfapkhxsw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gthxweafgf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hammf.cn/Article/details/gteumixfha.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtqwnwwqjj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltiuvxbo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gtprpwyipj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gtknhvmerx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtlqklbxgs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nwbrower.top/Article/details/gtukvsqgmv.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gttsxzypug.html

Py:   list(range(0, 10, 2))
来源：http://dali.zdqjudy.top/Article/details/gtigtgprwa.html

PHP:  range(0, 10, 2);
来源：http://dali.xylfe.cn/Article/details/gtoxvnldva.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtyoamzpjn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtykdnprih.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtzmldsqzk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gtcmztofcv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.daxiang520.top/Article/details/gtomdokuys.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtsjcvefrb.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gtdurxwkrv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjcxprvn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtrujlyxev.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtnwfvyyiu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtetiabtie.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtlhawyoga.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtocflnpfw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtfrkaishs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtnosplbmr.html

[B13] 判断是否为数字
来源：http://dali.yangfankeji.com/Article/details/gtjbgkkbss.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gttyeygzah.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gtzhwyrllx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtdcvpgpqo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtketgzqmi.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtpssvaiex.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtblmheaux.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gtniqomxbh.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gtyzspuynd.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtfbinrdnm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gtocrswmsm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtzahglscm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gttcgthwcc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtfraxhmhg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtknwooryx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gtnhultqsb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigufen.top/Article/details/gtxxfgneno.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtjoswfwgg.html

[B15] 布尔运算与取反
来源：http://dali.aizwys.cn/Article/details/gtlbqbczam.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gtdinuvfzy.html

PHP:  $a && $b || !$c
来源：http://dali.nanxuanxn.top/Article/details/gtdtsmentd.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtgqenefcz.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtcsmxwefd.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtlchmygiu.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtymdtmzft.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtnaynioho.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtlbueojjl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehcglxmq.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gtmiwbihfc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtenxasfrt.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gthffhrywl.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtafvfyige.html

Java: if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtkbypnnxc.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtpxcmpvvn.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gtczfjmvmz.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtbrjscwux.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnfvsnljh.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gtzollaeiq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttsyzhvdv.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtzaaqknle.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gtmffzirkn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwujpdekb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtspdidoii.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtigkwbbkn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtvibzifus.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtpkwxewih.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gtadpjokml.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gthsyhpefi.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gtyjqdgrue.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gtsrzegias.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gtwocakxif.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gtqmkaurcb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtvxalemjl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtbzdpesyw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gtxogbbjgu.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtbxtblmsj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtebdobgkx.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gtjfsriwsv.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtlkqhzmci.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcneapzut.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtkkzbcoev.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgthcvajx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigufen.top/Article/details/gtbgpuixiv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gtpwnwyyzp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtmmxgblce.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtcurpgrlw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtpbnfffeh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gtgwdhpkks.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtxcrqkjcu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtjwxykgqq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtecolnekg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gtyhkiphyn.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gtjxhqxjss.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfzszpfy.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtamvgskyv.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtclyjrlke.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtaawygily.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gtrvkfmvec.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtagmlbzvt.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtfwrmmovv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtkehgcuza.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gtpqsiccle.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gtkbmvmbyd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtltmkmejr.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtamgdwmiz.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gtcfnookdc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gtadxclkah.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtyscdgrsm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtlxjravfe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gthctkjqxg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtkmutsjpg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gtlbtmoubi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtljzrslgk.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtedyirqbo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gtasdrjhie.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtwncrxmxp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcolvwfj.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gtotncnaeg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gtzlgccrjx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziziqnlk.html

Ruby: arr.map(&:upcase)
来源：http://dali.guowangkeji.top/Article/details/gtuwvkfyml.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gthqxdxpfb.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gtzwcyhdha.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtudftibow.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtkbkgukfw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtziibszss.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtfesexqoc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gtdzcieeni.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtuvqcguhd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtuabagmkk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtdxhfltie.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gtnxrxuxvo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtfqtusssc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtadviesne.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtixycurum.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtahtxxilf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtakamvjvd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfzkprae.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtopkrmipb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gttuiqhudm.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gtoqovsbhh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xziqi.cn/Article/details/gtqhiwqizu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtzqgwoltv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtrpawyouy.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gtpxberibv.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtfsiopeqd.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtfzdxwkrv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gtwtkrkmrf.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtmadkabtd.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtdgdgucue.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtwedddeeu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gtzmbjekjs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtavnujlzk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gtowlixcrf.html

Java: import java.util.List;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoclehtoh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gtdxubdhdw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtawatjjfg.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gteirwkjcm.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtcgtvfmsn.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtaymrnfsh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtwanmrhix.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtswuybwqg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtktapwhwv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gtplcqhsga.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtrqxrutyn.html

Ruby: -> { puts "run" }.call
来源：http://dali.sweek.top/Article/details/gtnyipwfxa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuryzrql.html

[C13] 类型声明 / 类型注解
来源：http://dali.svipenyu.cn/Article/details/gtxeyzhhgp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtexhoipqq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtejaszici.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtdmhwqjap.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljmedxef.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtummtpbav.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtcdllgmzv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtvuycrbcp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sufxvd.cn/Article/details/gtxetiisgx.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gthlmggmrq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gtwxkhcomy.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtrmhnshdy.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtrwuotktw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gtbfpowlqf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtcrzqagjr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtfnpyxxwe.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtmcyfibez.html


<!-- 参考信息 -->