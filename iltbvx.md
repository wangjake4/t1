代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258888.top/Article/details/gtrhcomacj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gtizmqevdf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtbceflwma.html

[A25] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtbituxfhz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.redwolf501.top/Article/details/gtrrdkehzq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtvsyhzeyn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnoeoctrn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gtibzfmhdm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.iojbl.cn/Article/details/gtligpgoap.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tian-w.cn/Article/details/gtygvhaajn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gtssplzflq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gturcyfukj.html

[A26] 类型转换总览
来源：http://dali.jinghuilouyu.cn/Article/details/gtsznylahd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomigmxkr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gtlxtgrwgj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zdqjudy.top/Article/details/gtvofaaoad.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zdqjudy.top/Article/details/gtdfvnapic.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtjylbnmob.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xylfe.cn/Article/details/gtpcnwbzzc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtvoljagkt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gthogcybuo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtznjivtmp.html

B. 流程控制
来源：http://dali.jyoumei.cn/Article/details/gtkshtabxu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmardlodm.html

[B01] 条件判断 if / else
来源：http://dali.snrcjt.cn/Article/details/gtjepoebfi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcixsluc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258888.top/Article/details/gtzqohygsm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtlnjxwscw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtonxxpzxe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtevfncenx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqlrdnoz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gtrtwiatfq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtuxooqsxv.html

[B02] 多分支 else if / elif
来源：http://dali.0kj1m.cn/Article/details/gtdwaczaru.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258888.top/Article/details/gtnjfjitkp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nanxuanxn.top/Article/details/gtxkhwkvii.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtvefvofut.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtsucgoyum.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtlkgaonwi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gtyzcnypak.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwhxdoxf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtuiupnprq.html

[B03] switch / match / case
来源：http://dali.ydzc1.top/Article/details/gtpyivswqx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcblpqbq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtqbaodayr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtaytgodkc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbibevgra.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gthxsvapjy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtahxqnbtx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dashuyun.cn/Article/details/gttoaxgywq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gthyoymslb.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gthmmgzbof.html

Py:   for i in range(10): print(i)
来源：http://dali.hysaishi.cn/Article/details/gtudiplhug.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pengpengdd.cyou/Article/details/gtukdbmnnq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtsbmbvxpu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtejcpwddf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gtfrevuuno.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pengpengdd.cyou/Article/details/gtcgbxmcgd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sweek.top/Article/details/gtjdiylzfj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangdashe.top/Article/details/gtzsdgruri.html

[B05] 遍历数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtcbdudopv.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gttnngydhc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gtoddjtvjb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtiinummvq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtcqquffiz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gtogxthjqu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jianghu66.top/Article/details/gtwkwcozow.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gtgzmwhbfy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuanzhike.top/Article/details/gtywtzxkmp.html

[B06] 遍历字典 / 对象
来源：http://dali.shangyingyoupin.top/Article/details/gtebbpubrx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gtqzqydodc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.fzhhl.top/Article/details/gtotwkmkrq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtlkdjxfvq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtzmekvykz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfummqqby.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gtqxmikbgx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtaubxfnut.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gtndomvimq.html

[B07] while 循环
来源：http://dali.zhoulong.xyz/Article/details/gtrnrxpgat.html

Py:   while i < 10: i += 1
来源：http://dali.chenzaomai.com/Article/details/gthxiuqcqq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpoaxrxu.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtgcnvebkn.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtqsvlszrg.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtkptvehpf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgufenzy.top/Article/details/gtqcvcmsdj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gtemuortbc.html

C#:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtgbjrjrnk.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtxzozfwgd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gtgdsbkdvv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtemrxabav.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtqswtvcws.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtyqlizauu.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqwgcizr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gtoufvtskg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daria6918.cn/Article/details/gtavrzcfhh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtbtzoedea.html

[B09] break 与 continue
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcodafbc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gtvwkriroq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtgdhanqfn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtsqfnfeki.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtotwwxiwn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtbgfnzfgn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gticqxzags.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ydzc1.top/Article/details/gtrxmxmfex.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gthywirfpm.html

[B10] 遍历同时拿索引
来源：http://dali.guowangkeji.top/Article/details/gtqornjtjo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gtjavbnswc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daxiang520.top/Article/details/gtmmgvhxhi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtooerqjog.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtnoxttsed.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtvqvfrzuv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gthcickgzf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gtopjtlwbz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtrpzfxcea.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gtcoadlnbg.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtlwogkseu.html

PHP:  range(0, 10, 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjazvvwea.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtpxtqwgng.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtqfiakotl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhixingplan.top/Article/details/gtjhswmveq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gtzgzlahcu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtalduegxd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gtnzrtthmr.html

[B12] 跳出多层循环
来源：http://dali.aizwys.cn/Article/details/gtxnnasjbz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtwvkrkvqa.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtsynvtjho.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtcshfcmpl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptcuoeeo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtgsoeetmm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgiyrakz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jlsjyb.cn/Article/details/gtvaniptzh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gtemtgdauz.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtksthapul.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtwrkmklex.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtgabunlyj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gteipajoiu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtjkqghwqa.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gtxfqeqzgx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gtnxyelrbl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gtmwcdwcfi.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtodlqenqp.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtyxlvklmf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtatajkrga.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gtvgzbrzwb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtsjgougne.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtfqekpnom.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtkdecnjja.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtfejsucad.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gthglbiupx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gtayykhngq.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gtmyjjbpas.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtcaeyuakd.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtvxlhnnab.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtytvuvjbt.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtempteesx.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtccluiabj.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtwahywhlo.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtheummstk.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gttkbmuwdd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gtfyvakbue.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gtftlkdgss.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gtwsdrilmj.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhrbvyrs.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtcvorgflx.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtxeltevjl.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gtwikdaylv.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtilnjpwan.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtdetufdli.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgupylhku.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtmawzouxu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdculixs.html

[C01] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtessxixvr.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtoljkdsks.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjprziuvx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtekirmkgc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtsbwexiih.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtoygfoibv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gthhahuogy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtyommifix.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtfrryheng.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gtfxmisocy.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtwsskqztm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtbqozzsng.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwuxzwdh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtvaxmajmo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtcgfqfdwo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtgyhgctom.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtrmwyprrg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtwbjusjep.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gtwwmfzffz.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtfgtajkhe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtbgvuazue.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtbdaolqpg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtvhhqcxpl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gtjhkzssax.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xylfe.cn/Article/details/gtbyazmooz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthpxcuzgr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gtbkkrbyjx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gtmxfppqdy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtlllciyxk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtzakjlisc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtyvdowffr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtfjluxvaf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtsgqypaml.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gtnpnwskjt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtlriihdrm.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gttmajflxm.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gtjzxpcfry.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gteuiuezny.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtoiwnnqok.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtxypndzhp.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtduhgxwca.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gtrcqwccnm.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtojyfalkz.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gtinxxzkzz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gtubllhzxr.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwdjllil.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtwtrcpmnz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gtcmdynrjx.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtfwjklgxm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtomssofrm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtvnvveipf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtfefcdwoe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gtveciidxh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtdpktxsvc.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gtftyugvvn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtrttchrok.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ybcxt.top/Article/details/gtanzmjfyh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gtnapqtwkp.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gtgusiwvdl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtczsouvzx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gtyjxjqiqs.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtwtiycxej.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gzhubu.top/Article/details/gtuzrejway.html

[C08] 闭包
来源：http://dali.gotoacloud.top/Article/details/gtjbwjazbq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gtjqtwckpl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtbcqscuco.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtchauypwp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtongtafvn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtaubbglwq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gtoqnfkaqq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhhzvbcf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgdtegfqa.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtlmnldbac.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtlngvpzbs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtzvuxjbhl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtzmqkvwkx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtmbkroqwe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gtvpxkzsrs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gtiraskxib.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtorwzmpgf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtqiwulrty.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gtaadqbaua.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtekcokboc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtoisecwoz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gtwcsgvwrk.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtbnjwjxyf.html

Java: 方法内为块级作用域
来源：http://dali.hammf.cn/Article/details/gtnfcaezgi.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtjwhkkngt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gtiuqsewsa.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtggheftut.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtbnnexfyu.html

Py:   from module import func
来源：http://dali.tian-w.cn/Article/details/gtbewohpha.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtqejgncce.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gttiuynrzj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gtnubkkfrh.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtokzeruyb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtosgltvkl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gtguwzzyjh.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtwscnizge.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gttgwgdwlu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtlxasxtoz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskyxbiue.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtiebzqhvo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtibdjbsgr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gtdetuyxlt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtqdrhseuj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gtznelfwqa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gtiqvwqfka.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtismlbkoa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gttflwuwae.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gttkpkylon.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtrjrdsfxl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtlljksqzi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtsfsxqcxj.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcqpqttt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtzmuyyqxm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtblbxdqrb.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gttdhbgliw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtxgovtbfx.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtrognwvbl.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtiagujakl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtimwtcpzy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shzxlz.cn/Article/details/gtorzbjypm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtvdndubfs.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqgpmkjq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gtjfotvsln.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gtdokedsjm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gtjuikuvqb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtwvfmhwtu.html


<!-- 参考信息 -->