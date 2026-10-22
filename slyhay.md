代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtpybwpifx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.kuanghao11.cn/Article/details/gtcasmsgci.html

[A24] 去除首尾空白
来源：http://dali.havefunace.top/Article/details/gtdaktlzqq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgufenzy.top/Article/details/gthlzishhs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sysykeji.top/Article/details/gtysletxof.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtqabpmefr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtlbnkqaas.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cqqwz.cn/Article/details/gtiavwkxop.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnagngzlh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yanxiufei.cn/Article/details/gtwlrgrqhp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.daria6918.cn/Article/details/gttvmhryzp.html

[A25] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtqyoxwogt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gtlbvzfdhi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.aibaodan.cn/Article/details/gtnrndebti.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gtprqajkcb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gtcprnduwo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aizwys.cn/Article/details/gtdgbhbcnk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtktjoaosq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.daria6918.cn/Article/details/gtfmniobiy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gtfymzuknn.html

[A26] 类型转换总览
来源：http://dali.zhiwuduotai.top/Article/details/gtclqqjsat.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.vqdsnc.cn/Article/details/gtvhmtkzww.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dashuyun.cn/Article/details/gtjbwuadsx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgufenzy.top/Article/details/gtbcrtkkbe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zdqjudy.top/Article/details/gtssrqikwv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtyissdyse.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmgfrwdt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.aibaodan.cn/Article/details/gtqpjladkj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sweek.top/Article/details/gtufjbwcaw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkynzcomm.html

B. 流程控制
来源：http://dali.aibaodan.cn/Article/details/gthjmvsmmt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtyfcfrz.html

[B01] 条件判断 if / else
来源：http://dali.dianchejie.cn/Article/details/gtlbeyjhxs.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenlongwang.top/Article/details/gtxbjjztow.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdzehbczk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtycgzejce.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtdzcbcxxt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtqzhynjsj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.316326.xyz/Article/details/gtysnhabwi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.bjfxy.top/Article/details/gtvnqqdsot.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtcxywjqgs.html

[B02] 多分支 else if / elif
来源：http://dali.jianghu66.top/Article/details/gtyneqplii.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.feifeiyinyue.top/Article/details/gtkzrsexxv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gtsjytmiwe.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtfcfrlwpr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtdjibuqkq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtjmqjyind.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gtjxaftzvr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxinkj.top/Article/details/gtmgkuxufr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtrvdyvxpj.html

[B03] switch / match / case
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqehiymk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gttkiccytg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtawqwehal.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtxlfvauol.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtuvfenbqq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtqthqozxr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gtlsrmzgbp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nwbrower.top/Article/details/gttzwdrcyw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daria6918.cn/Article/details/gttafnsnij.html

[B04] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtnjsnhskd.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gtsfecafav.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shzxlz.cn/Article/details/gteqxgxiuh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gtwltmkhbl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gtepzncagb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvdgowdqb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gtvozpyrgq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gtozhfluxj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrggfgfou.html

[B05] 遍历数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtmukbfmfa.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gtllacrnfx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aizwys.cn/Article/details/gtluutyrdh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gtxutwlwyb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuinrtls.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tianlin.xyz/Article/details/gtdmshzxqv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtmmjwkxga.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfhwouru.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gtvctvebvi.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gtcznnkehw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtmgxudbuq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gtnvjlogmg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwnoexmp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtjxamkmig.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gtnxbovsbn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aizwys.cn/Article/details/gtdixclynj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dashuyun.cn/Article/details/gtxywnajxc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cdnleiting.top/Article/details/gtlmmmwlym.html

[B07] while 循环
来源：http://dali.aizwys.cn/Article/details/gtxdxgvllt.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gtfvqlhepl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xinyue.icu/Article/details/gtqobfqudt.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtffhcasze.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtkkcrqoug.html

Java: while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtiqhvhqzj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigufen.top/Article/details/gtershndjy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nwbrower.top/Article/details/gtgkunsrez.html

C#:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtgrpykmbp.html

[B08] do-while（至少执行一次）
来源：http://dali.jlsjyb.cn/Article/details/gtidlqcidp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.birdmap.top/Article/details/gtfwxqpnwa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nwbrower.top/Article/details/gtiynlclvv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlxidqzu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtifzlafcg.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtikngbmgo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gtokdmrtod.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtjbebwkdi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtfehrjdsc.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtwcwptmxn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyqfolbq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtqlahkkzc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtcgyhzlxk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtkveotgwf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtxepcjsok.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtdxfwtbgd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gtfquqyfgc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtexoukosx.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtqmqvmplu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yanxiufei.cn/Article/details/gtdnrwdhgi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gtivphyqnz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtwyzqwltc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gttpwvqmtb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gtdimfshqe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gtljrcvqny.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtxabkijlm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangdashe.top/Article/details/gtdugxcklg.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtbnkoryms.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gtlzsbcoci.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gtnrvllnta.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtmgvjwnub.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtdbayltmg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sweek.top/Article/details/gtfwkutkdt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gtdmiftosx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtcufjvgsl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aibaodan.cn/Article/details/gtowtegvwx.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gtakcxovwo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtkbypptxw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtzhdbyxxf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gttvfatjfg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gtxfnfpytf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfhzfmgm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gtnyyfbvtc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zdqjudy.top/Article/details/gtitvtwedx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtbuqdtjoh.html

[B13] 判断是否为数字
来源：http://dali.jqgfzy.top/Article/details/gthbvdyioy.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtupkbzuua.html

PHP:  is_numeric($x)
来源：http://dali.daria6918.cn/Article/details/gtevnaydfr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtwpacbcex.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gtosdjrgzh.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtqppwblcv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jiagoushi.top/Article/details/gtncingopf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gtxayblaqa.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gttcsrdxch.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzwwcdij.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gthcvckmoi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gtjahjjvao.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtyhfcaaqu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtkawnuqut.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gogol.net.cn/Article/details/gttvzaaueh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gtervjcxzj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gtfstgilln.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtmjrceshs.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gtgtggeaik.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gtofyfvrle.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gtdmlrlsds.html

JS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtwbttrlaz.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtodyodrnt.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtoljhknvu.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtfpkapxos.html

Ruby: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtfszrtyxq.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtculnfkwd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtvikmpqru.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlivfbxa.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtmetfwsib.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gteykawill.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtpfoxlouq.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtamxlrmfs.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gthwuqbxuv.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtdknejnec.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gttwuvufaw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtihciclqy.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtbqfexfdf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtwgyvtnmz.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtpwadprmi.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gtxqnexwgo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvgnokis.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtmsshjpup.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtjeccfujf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtjriwxgjd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtezswifvi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gtgaktumqj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtkdcclqab.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gtpikkwkii.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtcadkzxvc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gtxjkuocsr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtccdghzrc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtwpaqcgtf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gtrdpvxgsc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gtkqessjkz.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gtopcdbcgt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gttsotmtye.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtkxnbzthe.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtdmlrstev.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtlngdexsr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtfhcvvtto.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtodmnlemf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnyutuaf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtokmcosoi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gtnkksffvy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtxdouxhra.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtjqstekoj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtecvwdqgm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtmsffewgm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqqyxqxiz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gtjetzptxj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gtipieffab.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtzpnmqchv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfjmvqyo.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtpxhstdcd.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtpwbwgcgv.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtrqtvfyud.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gtyxbkzgsx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtyivwzufa.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtwgjtpuwm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gthcifwsxl.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtqfuwnszw.html

Ruby: return a, b
来源：http://dali.sweek.top/Article/details/gtlotetexg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlmawqfd.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtpnnifhdq.html

Py:   square = lambda x: x * x
来源：http://dali.jiagoushi.top/Article/details/gtqoiyohlf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gttfxiuvij.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvteacwr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gtrtoojxzl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtksohwzrl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtxwakqjyt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gtestxohro.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtnpdocsme.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzohjubw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gtwytaabfz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtiycxgula.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnyhqcpp.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gtlrkoxfel.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gtyfwoenjo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gtuyrfwram.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gtdifvabgn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gtjviomprr.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gteyolyqyv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gtjvjbvokl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gttbiikmjj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtbojizzgn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtaoxdwdsm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtmyuotwre.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gtdajuzytl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtukaaqkls.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtuvepqwwn.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtqhvpzlka.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtucmyjwah.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtrulfudhg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gttbfhhqve.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtetxitctv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtwtfbqinn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jiagoushi.top/Article/details/gtrmpyozbt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtreylecvm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gtwrzyvqsp.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtmxnvbtoh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtqzkmwqpn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtxydpfnij.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtffeqtdoq.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtgtijbdce.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gtlkxhuwda.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gtyclauchi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dianchejie.cn/Article/details/gtyidwvemd.html

C#:   块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtoktgrkdn.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtmnyfevud.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gttdzhoeox.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtukwkzugy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtuqnjbtny.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gtwixihisn.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtpfkqjimc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gthnvdfwkz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtxevhnydp.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gtzwphtxsm.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gtbrocxfbm.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtfukiunyq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtynrnxnam.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtbsyfhtpy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtdohmqihv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hammf.cn/Article/details/gtvvybyfvi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gtytottyyv.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gteeuxudbq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtnuofwthn.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gtzuxqnbbf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gthxpjbgur.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdzfadntr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gteidiyvik.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrnjyislo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbrhqkau.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtedihggvr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtfduysuwl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gthjltrpil.html

[C14] 泛型函数
来源：http://dali.jinqigfzy.top/Article/details/gtxgjyzqcj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtybrkslym.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtxhittfjc.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtiynaicfk.html


<!-- 参考信息 -->