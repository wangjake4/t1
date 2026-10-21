代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.mhx1999.top/Article/details/gtjkxyovua.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fzhhl.top/Article/details/gthdebrxlo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gtgmbomkpc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdfazfkx.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gtisyifwwg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guowangkeji.top/Article/details/gtyiflwmgo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtatixjuoa.html

[A25] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcxknxmm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.haohaochexian.top/Article/details/gtjraaiher.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgufenzy.top/Article/details/gtznvirgvc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtheqbwddu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.bjfxy.top/Article/details/gtxvtlkeqs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ydzc1.top/Article/details/gtpfkxdjte.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtbrvxvffc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinqigufen.top/Article/details/gtvtvgawmd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtwgubzjks.html

[A26] 类型转换总览
来源：http://dali.redwolf501.top/Article/details/gtlqrdxuzn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guannengcc.top/Article/details/gtsuiaotom.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yanxiufei.cn/Article/details/gtaygzhzln.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.redwolf501.top/Article/details/gtwgpdamax.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gtgzuishwa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtwnqdkhmx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gtoqhhbdng.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gtmtinpjgg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdjykfbk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgzdepstt.html

B. 流程控制
来源：http://dali.jinqigfzy.top/Article/details/gtwfvbibly.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmbfieavo.html

[B01] 条件判断 if / else
来源：http://dali.vqdsnc.cn/Article/details/gtvoddlciz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gtuiljubfr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sxryk.cn/Article/details/gtfljqkthv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtygvstnbl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtljwpsoss.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtxsnyalnb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtornrmarx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xinyue.icu/Article/details/gtrjbrxeng.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtokvcwlat.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gtlmkokfxs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yangfankeji.com/Article/details/gtkdyuufgv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigufen.top/Article/details/gtylqggdbn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtutpmhfxk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtugasrqbf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtwxylgsol.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sweek.top/Article/details/gtotqiegbw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.redwolf501.top/Article/details/gtgkrhxnrf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtozeeguwn.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gtjpubnkhq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ppjwa.cn/Article/details/gtuvezkiut.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtrumtursv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtrwafjgbi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtqauwurgk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtcvdsojwb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtwtdnndjp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gaohongyu789.top/Article/details/gtmvlbxpgu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtyevjlrzx.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gtgfmoepue.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtyrxedwbx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gtnffsiiwn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtaxlhwgfq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gttcbndxyk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigufen.top/Article/details/gtfqyblhek.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cashguo.top/Article/details/gtwqjdnhqe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.andypj.xyz/Article/details/gtndprcgvc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.dianchejie.cn/Article/details/gtpadywcqt.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpqzzpta.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gtpfhklnru.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258.top/Article/details/gtlsquaskt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtpzksmvap.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtymisdsxr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cdnleiting.top/Article/details/gtwyhhubwi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yvedp.cn/Article/details/gtywzdsxti.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yonumen.top/Article/details/gtnzuipizr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yongpay.top/Article/details/gtbegmcmko.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtjdnbxzzn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yueranfly.top/Article/details/gtxkxgcfnz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sufxvd.cn/Article/details/gtfvlhxxkn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtvkonwjoj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtishiashj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yonumen.top/Article/details/gtzzmrigki.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gtsjelpvhr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.bjfxy.top/Article/details/gtirgznscx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hysaishi.cn/Article/details/gtlffqexfe.html

[B07] while 循环
来源：http://dali.hnxiangtu.top/Article/details/gtriqvzlnm.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtyxhxeuhq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aizwys.cn/Article/details/gtyguzdpex.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtwgsharnc.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtoxgjoogg.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gterxalave.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtglboxzvj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yueranfly.top/Article/details/gtbqffdusm.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gthygarqwy.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gtafuwajhv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.iojbl.cn/Article/details/gtzcmxmcqt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tianlin.xyz/Article/details/gthzmotaiv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtvzzqsxyu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtfxzohghw.html

Java: do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtcxmqserh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvhnnbcj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yueranfly.top/Article/details/gtorfbdwgv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtksqumpqn.html

[B09] break 与 continue
来源：http://dali.jinqigufen.top/Article/details/gtqnkzywqg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gtslywavlh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnpdqxxmf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtewavkavf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtntdmegae.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtrcyuamxa.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gttlaxduyz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gttryuwljq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtyqtcqjnb.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtqiqkigjh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gtgxaybeld.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtziyzviwj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlfrcfdd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtbrxheoze.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.9152youxi.cn/Article/details/gtvyznamtz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gthxwzbtes.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shangyingyoupin.top/Article/details/gtqadkocaa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gzhubu.top/Article/details/gtizpyumui.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gteteenbbh.html

Py:   list(range(0, 10, 2))
来源：http://dali.yangfankeji.com/Article/details/gtsafvfegi.html

PHP:  range(0, 10, 2);
来源：http://dali.redwolf501.top/Article/details/gtavteyemf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtfkhlmtwm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtoigwqgdr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gteysxehpw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gtvpakditf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyteetdrn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gtdjrhixlb.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gthsjktqid.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuanzhike.top/Article/details/gtmablanon.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtrmnfzzui.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtotjyhvjq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtbzkslqyo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcjvabaq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gtvolyjuks.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhengqikj.top/Article/details/gtfgjzwthk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipcaitbc.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtknzxjtkl.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gtzwaesjvc.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gttzorlwnj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gthfkewuli.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtvyruhepd.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gtfikehgiq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenlongwang.top/Article/details/gttiwzmwte.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxupxuyd.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gtecdneelt.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gtdgsbkblv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtzukzaljx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gtbhwwkyml.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtssghgapq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtxefziawz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvsxrgbp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtfaghebcf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdumttit.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtwhkupnjs.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gtpivzizvi.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gtmhmutmol.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtphgneoql.html

JS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtzlbxnpeh.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtfijinbcy.html

Java: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gttqkmiqde.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtpnusiaxb.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtprnpawkv.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtuxdrteja.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daria6918.cn/Article/details/gtfmhjjkbf.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtfxzylppv.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrstprnso.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtplqzjruc.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtiaaxewxm.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtjtnnffnt.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gteqbfzwtd.html

Ruby: return if data.nil?
来源：http://dali.sufxvd.cn/Article/details/gttuosxbau.html

C#:   if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtypxjvhnt.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtqerbxads.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtpjljubdb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfihopzxs.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtbmjfoeot.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtqjqovrrf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtacovqswi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfedrhdab.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtnubajooy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtnspreeio.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtmuhdkokl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtmbhfhxti.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtorbeprej.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtzaohkcsm.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtvhvinryt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gtziehoipz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbyevrilq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtcnjyztgi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtpydtxvgp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapmpcpgn.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtkermjjut.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gticlgzghu.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gtwtteftvg.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gtgohmphgo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gtmgznnsot.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtnyfdxrrm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrhzhbqso.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gthuavqrqm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gtviealhwr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtikmhspcq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtuixvqlsi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtnfuoyykt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtawekyiqu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtjqmapdbd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhrhfhxv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtjnyxvvzy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gtuzumupvr.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtjuzazdck.html

Ruby: f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlhrqnrkn.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpgtpkpj.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gtxhnxztcg.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtihhayyry.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbhrzscv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtuusxaein.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gthprsuena.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gtkedwdcdi.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtfnigjjkg.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtkoanpeue.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnxiangtu.top/Article/details/gtnkgcsnrv.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexjbuemp.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtzufnickh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gtsguktvaz.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtrkqlhnxy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gtiolxkgpm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gtfmrhmvxu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gthontcshz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zycfv.cn/Article/details/gtcattrpqk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtxvsosfrr.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtdbwvzlaq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gthexlklvr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gttbcssoym.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gtmfykusbw.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtfqqcqxnl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtptfmkibr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrejxctq.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtvuftnoxe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gtvkqkejkb.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gtnnursiwj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gtoyxghpbc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gtgcxojbsg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtmvylawie.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtlztluqfy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtcadyjmcu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gtsyqogyjk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtubjakgdk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gteglrzrrh.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtvqvhsvxr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpawcvbjg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtygtybkvs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtlytzjnbd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtgevjxdxy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtdiqyzjrs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtlbyxxrgq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtdqdsxlxy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtckbilzwr.html

[C10] 变量作用域
来源：http://dali.9152youxi.cn/Article/details/gtuxvidxnl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gtbrdaotmp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtifbkpmcv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gtattaptud.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gtpfaqunie.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtzrpraiwi.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtennfjfue.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtitrovfsr.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtyneuqumt.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtmbkgvddv.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtsdugsmuc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gtblbyyizm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtpngslgfd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gthojzdoxy.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gtnmkmmwuc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gtblbsbqgn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gttnedjueh.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gtswkggbyj.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtirjwmebp.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtwypjmmgb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gtlpuohaks.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtwufhytmh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtjyawrzma.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqrpnyzj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gtbjdcmqne.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gtsccbwtri.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gtamjsopxu.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtvjihnjsw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiejvbbf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtrxnzaaum.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gtveemtydk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtsdefyiir.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtdlwnfcxt.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtlwwtoiod.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtdiifttrt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtwiajwnlx.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gtfuqjbyci.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gtzklfcjhb.html

PHP:  // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtjtnkonkc.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtvuvjogbk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gtjmdlkyhc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtuacuutsf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtwcooqadu.html

Ruby: # 无泛型
来源：http://dali.birdmap.top/Article/details/gtttnvmfmq.html


<!-- 参考信息 -->