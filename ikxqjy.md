代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gtdfhanvbg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gtkmmpsziw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gtikgbboub.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.9152youxi.cn/Article/details/gtcmjcfpri.html

Go:   strings.TrimSpace(s)
来源：http://dali.316326.xyz/Article/details/gtmojlfsun.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.meibo888.top/Article/details/gtkwkhmxnt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gtvdqldduv.html

[A25] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtihddbmpm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ydzc1.top/Article/details/gtlhohdluj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hysaishi.cn/Article/details/gtxomvkxpz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrymrsdwi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jianghu66.top/Article/details/gtgwewzhbn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zdqjudy.top/Article/details/gtczpwusrw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtapycbmkd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhoulong.xyz/Article/details/gtpisuecsk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtdqmafjlr.html

[A26] 类型转换总览
来源：http://dali.meibo888.top/Article/details/gtnjqdscty.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenlongwang.top/Article/details/gtbsjdatvx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cucudq.cn/Article/details/gtpemlkrpm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gtewupttcj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pycfn.com/Article/details/gtewzrwljw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gtqktmjgat.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gtxawqrqvu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gtretnhveh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gtghqogsux.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfkxyyxa.html

B. 流程控制
来源：http://dali.jyoumei.cn/Article/details/gtrrtlautg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnmrydywo.html

[B01] 条件判断 if / else
来源：http://dali.gogol.net.cn/Article/details/gtztgjaklj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnqzz.top/Article/details/gtxqrhkhjf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuanzhike.top/Article/details/gtanuzkkye.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtvdccdsso.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmkqysgt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtpkscaxur.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aizwys.cn/Article/details/gtxnvulyzd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gtpupzudah.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtokuyeclw.html

[B02] 多分支 else if / elif
来源：http://dali.pycfn.com/Article/details/gticrxgsvt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtdyjdkqpa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gtindqrfvw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtykoexegt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtiexgsyoo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtwpfkidrm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cqqwz.cn/Article/details/gttklreuzz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cdnleiting.top/Article/details/gtazfvnhko.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtplnkfvix.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtfmlqyein.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sysykeji.top/Article/details/gtfmtmcpxi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoswkryjt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtsqaqaywp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gthuyigozo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtfzgtdjbz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtcilabpzq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhixingplan.top/Article/details/gtaqahodzf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfqxujmm.html

[B04] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtoeabfedl.html

Py:   for i in range(10): print(i)
来源：http://dali.pycfn.com/Article/details/gtyhfkokxj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.smart0.xyz/Article/details/gtramfdfuu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gtrklbqxyv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gttrfjmbrj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtdmeprauf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gtkttfxdgr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangdashe.top/Article/details/gtpnebijzt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtswwmdtms.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtzskluetb.html

Py:   for item in arr: print(item)
来源：http://dali.pycfn.com/Article/details/gtspopivtx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tian-w.cn/Article/details/gtdshtdcta.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtuouaqdfd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtmodzyjdg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gtnbaxfbzp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenzaomai.com/Article/details/gtoymsghgc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenzaomai.com/Article/details/gtlnxqacbb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtrymqiixx.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gtqzoqyemk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenjidiqi.icu/Article/details/gtylyqcpwe.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guannengcc.top/Article/details/gtjtclqawl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gtsjxfsxix.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtwdgyau.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guannengcc.top/Article/details/gtusocfjnh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shangyingyoupin.top/Article/details/gtzeaptvvm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gtwavxhopa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fengsongda.top/Article/details/gtlfndybjj.html

[B07] while 循环
来源：http://dali.ydzc1.top/Article/details/gtgzmybejq.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gtlrjmovni.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gtsghhjyqn.html

JS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtouiffmio.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiqxjcxu.html

Java: while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtnuueuved.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gtjlzwkiay.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shuidangran.top/Article/details/gtnpbzobua.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gthgmftyhq.html

[B08] do-while（至少执行一次）
来源：http://dali.dianchejie.cn/Article/details/gtbxdesivz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gtjizmnnui.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtfxjeesvg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbgucrkn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtvvywtobh.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gthxornqke.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtmbggqmel.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnflbkwua.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtpkuezijv.html

[B09] break 与 continue
来源：http://dali.snrcjt.cn/Article/details/gtqrzbadwh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaiigqzb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtoaekupwg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtrdtjrclm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtmpkqvzze.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtoduswigl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtxzqsgeny.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gtltacjyga.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtlxpzjeie.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gteejihdsq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gotoacloud.top/Article/details/gtkznnybfl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gttpijrxae.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtjwjflbjp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtiprosngv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fengsongda.top/Article/details/gtnnmxaqed.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gtgoqzeujd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gtmezdjyai.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpukratky.html

[B11] 生成数字序列 / 区间
来源：http://dali.hfpthk.cn/Article/details/gtfbmwthai.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtzccwfsph.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtiqaknpzt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gtjvikecxq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtfdjjpgzi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gtfuexpvsl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gtuibcywig.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtthucauqh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gtohabrnga.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gtghnfxlff.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gtfcketgpw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gtwwkyaysw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtzrpudkxs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcvhyoyo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtcwryckvq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtcyolljag.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtriwoloed.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guowangkeji.top/Article/details/gtnpjgirpb.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gtyrctnrmw.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtxolpwtza.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtldqgjhxn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtonqwrlpl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gthhiawivq.html

Java: x instanceof Number
来源：http://dali.yanxiufei.cn/Article/details/gtzemhclws.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtpgykyvpr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gtcngqqohv.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmogaaxlx.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtvwcnmzjy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtgguvfuop.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtqzjedtxo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtxpfgpyci.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtwnwpypnv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtllsiapog.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gtncyuhcjz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtgnndrdsm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtjleiwyru.html

[B15] 布尔运算与取反
来源：http://dali.zhengqikj.top/Article/details/gtytybvtdn.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gtwdatsvij.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gtfjbtpwzf.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtkjyeozgv.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtjgzrnrxt.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtwnxspnqg.html

Go:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtlaesgcnq.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtqszlkpec.html

C#:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtgvtvalkr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gtsdehbbly.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtxhupkasj.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gtqfyqamst.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtwfqyjwvu.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtipvloyro.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gterozvoxe.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtprjchowi.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gtbpbhuztc.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtaelgowbh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtquhnisqi.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gtgmvnfupx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdrigkmcc.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtydqoiuxw.html

Py:   def add(a, b): return a + b
来源：http://dali.hnqzz.top/Article/details/gtwsyhtygg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtmojvrcti.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhytuwyf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gttqwmzehd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvosifdss.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gtqudakwwx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtflnbvxse.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtcganlzsm.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtgumwffud.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gtiynnlioa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtyyqmozoa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbghnhlrc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtqvmianar.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gtchktpbky.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtecbonhhc.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gtgpotzuxh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gtejvpkowb.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gtqfeerajr.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gtxuetbyxl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gtekijyams.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtqqzwsscy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtabsqdvmw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtvrnenndm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gtttngvmgs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gtkxxmkfco.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtoalkvzsf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ydzc1.top/Article/details/gtlzslxigf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtkuurjkes.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtaaxnanym.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtuxiyaftm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gtsdnvqgzx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtqwnsirhh.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtqfzolbjj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtyodijgnq.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtgjxujibw.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtebmkxarb.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtidzeboqn.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gtkbrftjnh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtyphkihdd.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gtwigtiawq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gtxdlqggba.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtckcnibfe.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtwqazlcoy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.smart0.xyz/Article/details/gtdmanstta.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gtgtnkadpr.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gtcvpycmeh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtvbkmjhjd.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtpuqomatn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtztvkdffk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtdwubxjxz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhongyouzk.top/Article/details/gtuwnmbbty.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cdnleiting.top/Article/details/gtiflhusag.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtsrkqkoyj.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtlbdmwcgc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtucnemaad.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtirzneasg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtqhnascux.html

TS:   arr.map(String)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtconhwrqb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngwakdll.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtoecocmsv.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtrwojcrnh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtjfwapckn.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gtwvqyxbtw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gtjwmsvcjp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gtrflsetbh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtvvmdfjif.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtujeuvrxp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklnskqdp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gthtxiqitl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtavckfjrn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtqjxqljzj.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gthacepjcn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtmajazzsf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtbwaedawk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtapyvwhmi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtuwzramhd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtxbpqldut.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgufenzy.top/Article/details/gtukzltqpm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtvefhpwkv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gtocqouxqu.html

[C10] 变量作用域
来源：http://dali.daria6918.cn/Article/details/gtfbtilqcy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dianchejie.cn/Article/details/gtodfiscvh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gtdcwbgcat.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtcpfyljbc.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtvpupnptj.html

Java: 方法内为块级作用域
来源：http://dali.yueranfly.top/Article/details/gtwhuggetj.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtbconllef.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gtpsbyilvr.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtlfwfshhq.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtngiglvsa.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtitfexbqn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtubvpyuhy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtpdvbebcb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jyoumei.cn/Article/details/gtvuywqrkl.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtzvghlqlt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmorousl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj20258.top/Article/details/gtustcpcgs.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gtphsnyueb.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtdfamxcra.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtwmwblvgg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtvjijyzhk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gthrokxnms.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtqgaykacp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gtwkpluogc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtwnyhhvtz.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodfehpjw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258.top/Article/details/gtfemjmocd.html

[C13] 类型声明 / 类型注解
来源：http://dali.fengsongda.top/Article/details/gtidrylpyu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtnfpgajhi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtmiavftnq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtynrjzysu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtasnathzd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtjudhvkze.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtzlbprokb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gttiyqazfs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gthtvivudd.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gttdgcdsls.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqaxubkd.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtdqiboiie.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstktgrrk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gtzzjifflg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.daria6918.cn/Article/details/gtqjgmqniw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gtcazadzng.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtxqxqzybq.html


<!-- 参考信息 -->