代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj202588.top/Article/details/gtjedvswiv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gtpqjfktbr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangdashe.top/Article/details/gtppcjemve.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gtcxlreaek.html

[A26] 类型转换总览
来源：http://dali.hammf.cn/Article/details/gtauzyoxil.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daria6918.cn/Article/details/gtpzbxvpcs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gtwlzhqrfr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gtkiycfsjn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sweek.top/Article/details/gtsmmgvdqp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gzhubu.top/Article/details/gthdtoeaaz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.316326.xyz/Article/details/gtwydtpnbh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gtzodprpel.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtzetwvfqk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtenoqiqpp.html

B. 流程控制
来源：http://dali.cdnleiting.top/Article/details/gthqhudkzb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwiggluej.html

[B01] 条件判断 if / else
来源：http://dali.yvedp.cn/Article/details/gtaybllojf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yueranfly.top/Article/details/gtftgccasu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.snrcjt.cn/Article/details/gtcdlcxdzg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtkfzrcdfk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtcsdenirh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtwzrcvgds.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gttntxvipg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gtfmyqkaep.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtpppohbnv.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangtech.top/Article/details/gtngqvvbxz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daria6918.cn/Article/details/gtwksazzyq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigfzy.top/Article/details/gtbvgqhvrq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtxvivprpy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtzsxyfifw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtllzqapdz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gotoacloud.top/Article/details/gtbqnoinda.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfuidtfx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtflcxmzct.html

[B03] switch / match / case
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimulysjx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jianghu66.top/Article/details/gtrpomzqdk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwbmhjmzn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gtkxdwlqju.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtsmvqofju.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsudkvwzs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtxkfgfbar.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmlfrtrf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtdzuixteg.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gtldrhbcfl.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gthmdxhppa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.smart0.xyz/Article/details/gtjncnydag.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gtgxcadwcg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgtcpsot.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gtpwxakglz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhiwuduotai.top/Article/details/gtfkoqiheq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jlsjyb.cn/Article/details/gtzbketdvw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ybcxt.top/Article/details/gtmyhqtqgn.html

[B05] 遍历数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtgooqjtix.html

Py:   for item in arr: print(item)
来源：http://dali.ppjwa.cn/Article/details/gtxgtofpft.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gtqppittuh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gtqnpybrxs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtpnaidwjb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.iojbl.cn/Article/details/gtxxqtbbzb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.bjfxy.top/Article/details/gtlymbbvgf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nwbrower.top/Article/details/gtlxtgwnqh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pycfn.com/Article/details/gtqrqfawof.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gtefthsmcm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gtfgiutjki.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.mhx1999.top/Article/details/gtbbjzvbrl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gtisutlbht.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtkffgqjri.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hongshengwenyu.top/Article/details/gthjdgkdyt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gtdkgllqlb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtmkatxxfy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtccvifnyf.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavomewiy.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdnkfhth.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sxryk.cn/Article/details/gtatfelhqf.html

JS:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtaryyxoqd.html

TS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtqtzuehvr.html

Java: while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtctwxfmvb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtukhxmjmj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ehwqpu.com/Article/details/gtlytjjfox.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtlpywrzac.html

[B08] do-while（至少执行一次）
来源：http://dali.cucudq.cn/Article/details/gtvtcjuggg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gtasggfvmm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtytomihqp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtaqgxnitt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtufkglkix.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtgrevuwab.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gotoacloud.top/Article/details/gtfpzbpgkv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqjrgkib.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtgmoryufl.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtjiwqrttv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hywenlv.cn/Article/details/gtrmszhqwf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtlrjooqzn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtpzdrzwsp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteevccncy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtrajltulo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gtjqiipimk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yueranfly.top/Article/details/gtcipjcnxq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtfozxnbgv.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtdhbzluoi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ppjwa.cn/Article/details/gtvddrzvhi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtizdnwcvi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtxxhchlsm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqajgwoy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gtjntttqby.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gtdmrxehwt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevosozlz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yongpay.top/Article/details/gtvtevfdgm.html

[B11] 生成数字序列 / 区间
来源：http://dali.iojbl.cn/Article/details/gtbgvyfuhr.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gtoqzghhqu.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gtvcfwvtft.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtumpsxahq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtxgzkytmw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gtfvepsyrt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gthiwjhafh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtuljjlrdx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmklbyzg.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gtiznerbsl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtifhyjpog.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258888.top/Article/details/gtnqzgrdle.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtbzrwaioi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtzrtvzsya.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtbzdcdnmu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtqmqgohjt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtykzzdsey.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuetiantiany.cn/Article/details/gtsmoeafsq.html

[B13] 判断是否为数字
来源：http://dali.c1oappe.top/Article/details/gtuvcamhum.html

Py:   isinstance(x, (int, float))
来源：http://dali.redwolf501.top/Article/details/gtrugtafgl.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gtpmhfabcc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtdpynjczf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gthqbaxtoo.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gttnwxprvm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmliwofj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhengqikj.top/Article/details/gtmlqzwqgw.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gttosbqdsx.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnepyfpv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gtngvuqlmj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtjwevwhqa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtxwzubsdj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlehfbwdf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gticzbowac.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gtjvkisdjj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtyysuapta.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtstvrahnp.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gtlbacmxyq.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gtegkydtnb.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gtqenysrbw.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtgycnfxtl.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtrrsgyrdp.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtoxhusrgz.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtlcbrnfbv.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtrtvsswqw.html

C#:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtfjnsvppl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gtbignzajm.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtxvrumvem.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258.top/Article/details/gtyvvdydkd.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtcypfxvap.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtswywkwma.html

Java: if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtvspdvcyu.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gtnklfkkix.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtvmmkhfdb.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtljcuhjah.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrgrbitbu.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gtjtzvmyba.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjpfwwkcg.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtweygqesi.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtjqrjctlq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtvjsbklbn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gthuqyxrht.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtqwnnqlhi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtfwgraphr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtyhwpcetr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtvrvfqfzi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtgxkgmllb.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gtvmlmbura.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtilhvugul.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtucwytlzk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtkbornnyg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtpjswospz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gtuxissvgw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sweek.top/Article/details/gtkpiggjee.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtxzesneve.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gttfgugjib.html

[C03] 可变参数
来源：http://dali.sxryk.cn/Article/details/gtzeqdxjza.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gttjowdpcn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtfkscjdog.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtwjvemjwt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gteufcvhqw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gtukkzpjli.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtidkzukbp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gtikdkcaje.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gtoozaspvg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtmceyaqpf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gtfgfwcfpr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gthwdoexog.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gthergdkdw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtgpzdxnsm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gtpgybgrcp.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtkdtboncw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtvdcfudfu.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtmwklubos.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gtsxwjvkib.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gttisxjxcb.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtkupikkhy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwbxmqfh.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtmearxzsi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtdiliewdv.html

Go:   return a, b
来源：http://dali.yj202588.top/Article/details/gtdjnypnnv.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gtambegupt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gtjsifulxi.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtsjiedtww.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gtdzijktne.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtcccjanqh.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtiyfanwwo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gtsuxkxioo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtxklgnypg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtsuhrgjuq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtbjwcaujp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtprfnuqhx.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gtedxfycgt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gtoaltirnn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtbgswarti.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gtmjwhrzdm.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtxzostweb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtibzfhedo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gtyzknvhph.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtiremvaoi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtsjcekwzo.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gtwbbgkbvl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shangyingyoupin.top/Article/details/gtxslhdjiz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtrrbwciav.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtjctuexgw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtbmhcofpu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gtdstybgbn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gtwurcvxdl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gtqmvdcpuv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtqyybtzys.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtlbbhymnx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtqmcownii.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtqvspbdqq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtaofypjpj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gthofzgucj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gtopllqiid.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gthetjcish.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gthjmjlvic.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtkagibodq.html

[C10] 变量作用域
来源：http://dali.andypj.xyz/Article/details/gtzzlzwgly.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtusrbucah.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvbwgxco.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtegmquagp.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtcccbuqwd.html

Java: 方法内为块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtzagbuyiu.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtftqpnudk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gthvasaodd.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtvydniufg.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtszzcqulr.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gtdyekhvjq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xziqi.cn/Article/details/gtyvyfzteo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtbevneiee.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj202588.top/Article/details/gtscdlqash.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtycgumspw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtfsoxctga.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.haohaochexian.top/Article/details/gtsegqhxzs.html

C#:   using System.Text;
来源：http://dali.xinyue.icu/Article/details/gtndpbjqus.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtkkevipma.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gtqyjnyqol.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gtshjqsfwb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtesqznwub.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtkneqxeoe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtolcrkevp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtideqxdmo.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtwnisdfvj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtgmqaoatl.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gtmybnrvoz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gtdbzyqcoo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtbjlaadgy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gtcqrcurzv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtiilayhbo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtkczudqlw.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtenwkccyv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtoxjhmnmc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gtbzuukcps.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtnuznljzi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gtbswpfybm.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtpiuzjuhh.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gtmxvuddvf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtbfxrwsqr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtkvpksffb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtgbvnbqqp.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtrjhrtpml.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtgefoyrvq.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtxnmigjfx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtljpazner.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtfrhncxhh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtnsrkaypw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gtrcngvgci.html

Java: // 无解构
来源：http://dali.zycfv.cn/Article/details/gthlhnctfs.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtapspxxki.html

Ruby: a, b = pair
来源：http://dali.andypj.xyz/Article/details/gtrakybrrv.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtbxagszgp.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnhthqsi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gtrcecqdcr.html


<!-- 参考信息 -->