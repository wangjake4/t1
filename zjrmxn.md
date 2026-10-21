代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.cdnleiting.top/Article/details/gttypdieiz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.iojbl.cn/Article/details/gtiimcsign.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehavlvhl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gtavxgaozh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tian-w.cn/Article/details/gtbtipljar.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwbutsxr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.havefunace.top/Article/details/gtecqsafrt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gtudqoghrc.html

[A26] 类型转换总览
来源：http://dali.hysaishi.cn/Article/details/gtnixqmgcp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.vqdsnc.cn/Article/details/gtmtzqjdyv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnvhmqhv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shzxlz.cn/Article/details/gtxbgtceek.html

TS:   Number() String() Boolean() x as number
来源：http://dali.andypj.xyz/Article/details/gtmantpiww.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtlhwvdkyo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdgebflk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ehwqpu.com/Article/details/gthxkvpfjx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gtnrrrpizo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtahgobycs.html

B. 流程控制
来源：http://dali.xuetiantiany.cn/Article/details/gtqkigeunm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtjcbgnyaj.html

[B01] 条件判断 if / else
来源：http://dali.xinyue.icu/Article/details/gtlhjkygln.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinqigfzy.top/Article/details/gtdlrodxaq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gtcymnrbte.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtgfthlypc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtppmgfoiv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtilthymyz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgufenzy.top/Article/details/gtqrytosmu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gtzgqevqxr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtxmleaetv.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtyocetosp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gtofyfgmnw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gtywkqufej.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gttsovofvn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtjbzsyrim.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtwjlohopc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnxiangtu.top/Article/details/gtzccofpjy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.haohaochexian.top/Article/details/gtfdsauvjf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtcsawkrnr.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gtzhfrhlnw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gtzvbdhnpv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtjsepyogm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtzyutncgc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtsfqufczj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtjkixolzs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtwlnpucxz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuanzhike.top/Article/details/gtlwbfshxn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fzhhl.top/Article/details/gteshmknlg.html

[B04] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtspkgkcyo.html

Py:   for i in range(10): print(i)
来源：http://dali.yj20258888.top/Article/details/gtuiwmsglq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daxiang520.top/Article/details/gtqflvgwon.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtsmxrceck.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gtuyfdayza.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ybcxt.top/Article/details/gtefaaejmt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfehdkxk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yonumen.top/Article/details/gtstluofmh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtpcwunagb.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtolpxahpl.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gteyucpvsi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgbcatfxx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtnqojqcsr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtxvlgkovb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gtrkvanfgj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtefgkqdtm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtqgfkibhw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiueuzbwu.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gtlawltaif.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gtoyxcigwe.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sysykeji.top/Article/details/gtvxrlrbiz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtxphhisha.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtpffjxeps.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxzasquar.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.c1oappe.top/Article/details/gtvwmtanac.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daxiang520.top/Article/details/gtnohshosx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxhqnyhay.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtjshwfalj.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtobktssca.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenlongwang.top/Article/details/gthuzkovge.html

JS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtfxmfzyme.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtxfnzjltn.html

Java: while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtayorppmp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gtseegybqr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllyhxyiu.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtgrtrolds.html

[B08] do-while（至少执行一次）
来源：http://dali.dianchejie.cn/Article/details/gttryyxgai.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gtjukonovp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gttrbmeurs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtzhfwklbq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtctftwehj.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtpmsrcqub.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtheyqnsqr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gtptgqgmuu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gteyhdifbw.html

[B09] break 与 continue
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbbskkwd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aibaodan.cn/Article/details/gttnjqsdwu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtjgsonenw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gthmxfbnst.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtpthngcgg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtptfkprbq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtnhkvgrsj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnxiangtu.top/Article/details/gtklgztzpc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlcjeryvo.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtmnnfxykg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gtzyuuhyaz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gtubyoutcr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gtwqosmbjr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtyktjgpqc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gtzparugpp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ivvv.top/Article/details/gtblvwypmx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gthiifdgpq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ehwqpu.com/Article/details/gtkivzpsqh.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gtdhjgjqrl.html

Py:   list(range(0, 10, 2))
来源：http://dali.mhx1999.top/Article/details/gtpwzrjbyb.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gtqqjblwio.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtclnohexn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtezezdxjr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gtfooblyhc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslovbnne.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gtkznsfitj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gtxchmlxyw.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gttozubzaq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtodluwaxc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gtazcikjdj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtdbjseudh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtyxqttnxi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtrswovopt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gtnjrujjoe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gtvnesjjio.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtouxzbjnl.html

[B13] 判断是否为数字
来源：http://dali.tanke756.top/Article/details/gtzwdqwfvu.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtuhtgvbtl.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtnsdbrwws.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtiuvwkdwn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtofwtnunf.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqrxpvuf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gttuedaupq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gtrhjiwxdj.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtqhieycyf.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gtllvacits.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangdashe.top/Article/details/gtgzcguykw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shzxlz.cn/Article/details/gtwcfszbwo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfotdjgk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtkkjdvmfy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtsnmldadn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gtpklrnkdz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgzdaicc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtvmxsxbjm.html

[B15] 布尔运算与取反
来源：http://dali.andypj.xyz/Article/details/gttkljuibc.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gtqewtaxyd.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtfnrigkrw.html

JS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gttcdlqsdw.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtgbbarfpw.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtioijgecs.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtwvbboues.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtabmyyyvo.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtlxjrorzj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtknfjiwiv.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gtfmxfiljd.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gtlwcouwte.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtdqmsdqqr.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtxfiyhjei.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtzcrmdzul.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gtegszabku.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gtobfajbgu.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtqsaqyuvb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqxjxcesg.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gtweipftjt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtoeishnkx.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gthwcnoynu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtlezfmfmx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gttitfdcrp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtbnozacsm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtkmxtgkxl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtqfhcmbzx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtdnuvczlr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtvtxeodzb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtxzznoctf.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtpxlqlsyd.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtjejxkhcm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gtsslblznc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtlzwalzvr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtdckkckru.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigufen.top/Article/details/gtwmzffmig.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gtdrlufniw.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtovwonftt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwvmtvne.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtckmdaqmv.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gtrkmpldkr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtgnoydtkc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtukihsmki.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtledkytvk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gtwbfaqwpg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gtzwsrfqmt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtizxxaicw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtkrfxqmvl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtvlfgokyu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gtnaorfgvb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gthjhrrffh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtkoldeggo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtomqqplpe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gtbxjolboq.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gtbkqlhsao.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtnhvmgqow.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gteicbduwl.html

[C05] 返回多个值
来源：http://dali.cucudq.cn/Article/details/gtnzonshbr.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtbnajlsrr.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gtqbencjqj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtillbhrzq.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtsyswazmy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtyqkftsyw.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtwuwkyttr.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtvskwwamb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtwxgxygkg.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzevkmmhc.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gtsaqaqruy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtmmzouznw.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtsnuwnfpq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sxryk.cn/Article/details/gtswdjtgvy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjwsrbcd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gtqtifgmla.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojpiyvyn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtgjaqgezj.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gtpjccmxct.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtktavmclk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtdceyvgpi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gtzprqelya.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gtppiuqbhb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gteuteeemi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gtvlopmvdc.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtdoaxbvlc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtedapntrw.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtveowaqqb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sweek.top/Article/details/gtqvtmbxqw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gtcnqduhja.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtaumwgvuq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtuoxxjfho.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gttfvsifct.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoezcdglg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtnewmltxq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gthbpgtjzd.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtozpghlxs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gthhpbkwzl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtgnkomsod.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtgjlnlqhi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtlvjvnjrq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtekflffox.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gtccujhqth.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtuboygtcw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gticvkqzzk.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gtniqkdnrc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtqslmomlr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtvryamyrh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtvtibdoea.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoybukrcq.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtsfpnltty.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtcjkionlk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtlcgoffsl.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gtojztjrtn.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gteffqbfci.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtaviqttkg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtykhjuvoe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gtdamjaahr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gtsiligzuc.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gtqivroeua.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtburralje.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzkvdenh.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gtujqwwvwt.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtihbcavum.html

Py:   (lambda: print("run"))()
来源：http://dali.zhengqikj.top/Article/details/gtnxsyqrrt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gtppxzytfp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtgwgauycq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtsmlxbhrz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gthlyyohzp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtchvunrnw.html

Ruby: -> { puts "run" }.call
来源：http://dali.hysaishi.cn/Article/details/gtvsowbbjt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gttyhzqmcx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtwbvxlsbk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtfdingqji.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtdzstaesx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gtbkorpogn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtovzjsdub.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtihqpizrv.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtbtcwuemj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gtukraypjm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtnaixxsaw.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtkspvlqlp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtyovzzvul.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gtnjnnffns.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtkipyugya.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gtephatpfm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtlymcngqv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtsngdkoyw.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtvlipqqjk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtzfmqgkgi.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtetsjjplf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtnvkirgcz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cucudq.cn/Article/details/gtittlyriz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtqiqydoms.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gtynyncozk.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gtmhqxbocy.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtqyipefrs.html


<!-- 参考信息 -->