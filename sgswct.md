代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gtxzlidouf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gtxvjpalwy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gtqqyuwmfs.html

[A25] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gttwqbebkt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258.top/Article/details/gtqbhwgqpu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gogol.net.cn/Article/details/gtheafrctx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyialhixj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gtrhyxkrll.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cucudq.cn/Article/details/gtiamlpyrr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gtneogtbjx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jlsjyb.cn/Article/details/gtjigkjjxy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gtddxambiv.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gtyjymahcu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cqqwz.cn/Article/details/gtngnovaij.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yanxiufei.cn/Article/details/gtjpnckmxm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pengpengdd.cyou/Article/details/gthgmzeftr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.feifeiyinyue.top/Article/details/gtgkdmybng.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.havefunace.top/Article/details/gtbwvsiglf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbcrnqtp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xinyue.icu/Article/details/gtqfekjqxr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nwbrower.top/Article/details/gtupzkcbsa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gturhiiydm.html

B. 流程控制
来源：http://dali.zhixingplan.top/Article/details/gtdofrydht.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxekgzlhg.html

[B01] 条件判断 if / else
来源：http://dali.birdmap.top/Article/details/gthndfpyzt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gtlouzbowp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fengsongda.top/Article/details/gtuouhhydm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gthhihwppl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtsiyldtpv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtjerfpoeo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtyyqsgpup.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.havefunace.top/Article/details/gticxzkxfv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtshedfrvq.html

[B02] 多分支 else if / elif
来源：http://dali.jinghuilouyu.cn/Article/details/gtrisnhaqi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yueranfly.top/Article/details/gtrekbijtl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yueranfly.top/Article/details/gtebkfwzrp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtsnvznxoq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtrluywvts.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtxzlhcywc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gtguanuwmm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nwbrower.top/Article/details/gtccjqhfia.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtcnxzqnky.html

[B03] switch / match / case
来源：http://dali.zhengqikj.top/Article/details/gtednxdsre.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aizwys.cn/Article/details/gtpfzwiftx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gttyfbkgak.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtgrildrsu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgjzrxykj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gtlvezrfhm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.havefunace.top/Article/details/gtpkffbiih.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hywenlv.cn/Article/details/gtgpkdgdei.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtlxybvohi.html

[B04] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtfnzrzvms.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgfzy.top/Article/details/gtdzfwclel.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhoulong.xyz/Article/details/gtprohfxnp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpacikpzh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gtsobtgjim.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daria6918.cn/Article/details/gtbxbmfshy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xziqi.cn/Article/details/gtabxdjvgb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gtytrawqop.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shzxlz.cn/Article/details/gtygdbdpga.html

[B05] 遍历数组 / 列表
来源：http://dali.sweek.top/Article/details/gtnospruzz.html

Py:   for item in arr: print(item)
来源：http://dali.yongpay.top/Article/details/gtwmmnsxhd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtduvlhlrh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtxmskiton.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gteacbcawh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fengsongda.top/Article/details/gtjanqfazm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.havefunace.top/Article/details/gtqcruakyv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gtpbgtvciw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzcnhvww.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gtptngnowd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gthcelqvfk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtczsngewk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjezjnlgx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gtvpumltjs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ppjwa.cn/Article/details/gtvhndiqxi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fzhhl.top/Article/details/gtylcllzae.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gtmngmvmdv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuxming.cn/Article/details/gthakldqmd.html

[B07] while 循环
来源：http://dali.meibo888.top/Article/details/gtaikslqln.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gtvzcyzsml.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsxfnmupk.html

JS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtsgztbsmo.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtsykuiads.html

Java: while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gttczhfvhl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.smart0.xyz/Article/details/gtvyruqvbn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.mhx1999.top/Article/details/gthvludjsg.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtbbdvodpj.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gtadfylnlx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gtxcjjoiev.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shuidangran.top/Article/details/gtukxrgvcj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtsmlquldo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtrfrbqhdp.html

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gthzkqzmvv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtgmqudptb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gtdqlsbcyc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtjtgscqyw.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtfnddajox.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtnmzqxnrw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdzygcpna.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtgomfxtrd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtltrjyjhe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtzwchfrrp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtrfpdnoxp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gtuwqzwehz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gthvuqpsek.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gtikjnrxot.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gtpaflgmfb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nanxuanxn.top/Article/details/gttbvudlyx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtrqxdkwsi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtdrnemdfz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gtzpcjhrys.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gtdibmuskt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gtgcljmsev.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gtesxqchdg.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gtolapdsdx.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gtmrsjlxmv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gtieqefmff.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtyjwhumkl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtcwmmyuyu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtttqffjxm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gtnvlssqon.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gtxhoyxotn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnlywhzb.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gtnggaxkxv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hfpthk.cn/Article/details/gtawwtevbc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gtiunmdqga.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtgsszeibb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtldziexya.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gthylxbbyj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtgddbwigb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtqdnmmjhe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtmirnuinz.html

[B13] 判断是否为数字
来源：http://dali.sxryk.cn/Article/details/gtfwwtvibz.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gtqjckxczq.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gtgkisliad.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtfdmqumxk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtcbelggke.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtdpcgiaja.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gtwomzmdvf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gtevpxpzcq.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gtggtbctkb.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtmiugcgoi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shzxlz.cn/Article/details/gtjhxyhdym.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxsslzas.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtdmkpjnwa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gthbeidskb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtoszcqrwu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgnqpqynr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jianghu66.top/Article/details/gtkqjtcxgd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtqjhpciew.html

[B15] 布尔运算与取反
来源：http://dali.shangyingyoupin.top/Article/details/gtyygifelz.html

Py:   a and b or not c
来源：http://dali.yvedp.cn/Article/details/gtbrtaough.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gtfnknwtow.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtiqpbckuk.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtgxoqxgxw.html

Java: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtajaanegm.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtvyjaoaft.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtqoxkadug.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtddlqymgl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gtowdijfnm.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gtsdkfdwtp.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtzuxcavnw.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtihxaoadw.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtxdupkomz.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtuhaklrkg.html

Go:   if data == nil { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuhkctyd.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtbnsaejeo.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtblnozjpi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthuiudanw.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkvylzfp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtalvhsteh.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtixodpdxx.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtgtmphpfm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtnyjqbsdh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtcijdlkpi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gttmbzwntv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtaxeasuxz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtztrmkcwc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gtdqvircad.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfmqeisw.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gtojwkwhsx.html

Py:   def greet(name="World"): return name
来源：http://dali.chenjidiqi.icu/Article/details/gtnfswimmo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gtlisyzqrs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjeyksaw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtooemvuxf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtjfterxbf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gtkdhsqwnn.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtkhnxnzvu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gttjpuyigf.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gtfjjwwayz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtafexhmvp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtnkephkyb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtobgwszcq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtwrhugzwy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gtnwlbpbjf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gtoksexvzu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gtqsepsunt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gtliyvbpzs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtkmigysgm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gthwyonwfy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtkjqevasu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gttunnbudi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gtxmxjrmcg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sweek.top/Article/details/gtnrbihdas.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gturrekzyx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtawlkysdn.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gteiuzkfsi.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gtmckmgarp.html

Py:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtmbanlmcx.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gtmxnnbvdk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsesalno.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtfpumdnhs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxawdwdz.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gthatewdyy.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtdvugewns.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtmorhjslg.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gtxpeaolrk.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtyzdppsij.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtcghljmjk.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtiqdqoien.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtlqyomdwh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtxubbehgf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gtzllrefmp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtdtprmeji.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtpxryqwag.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtszkpylil.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gtcpwcmttl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtsoqsfvxp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gaohongyu789.top/Article/details/gtjlxrzjgs.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtwqupyalr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtrrnrtzbg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gtrvsnaacu.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gtdgjoeisq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gtynptiwmk.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtmtnefoby.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtettqjcya.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnfiieijh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hfpthk.cn/Article/details/gtubnqufbx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtrhtkgeiw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtedlwylak.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtrobgidjp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gtildxvagl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gthqxnyxwj.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtqgxbnnvs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtrtvqzmde.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtwsyqpowd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtmjnpxbmh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.svipenyu.cn/Article/details/gtcplwsqag.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtmbdydmxk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.feifeiyinyue.top/Article/details/gtfqjolohd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtkcquodnm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtbwysespe.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvyugiwy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangshuangyany.cn/Article/details/gtywraozdx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtmagjxbxs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gtgetudnwd.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtrcumzpas.html

Java: 方法内为块级作用域
来源：http://dali.redwolf501.top/Article/details/gtizugdtja.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtthaqpeuh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tanke756.top/Article/details/gtrhsrjycg.html

C#:   块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtduhwmphb.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkglshdz.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtyhvdlzli.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gtlkxdrjxi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtxbbvqabl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gttbsldmji.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtvkofffhw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtcsvnlwpe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tanke756.top/Article/details/gtkjnhvgyk.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtbauccxxf.html

[C12] 立即执行函数 IIFE
来源：http://dali.shangyingyoupin.top/Article/details/gtwskwmjnr.html

Py:   (lambda: print("run"))()
来源：http://dali.tianlin.xyz/Article/details/gtpmbtvpxq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gtdlwdqhlm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtvgymhqgv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtadiyfxlu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dashuyun.cn/Article/details/gtheccabkf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtvigtcrkz.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gtuxxehdvl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gtjleqydtd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtpcsdgnzy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtylhsxghw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmomznlwu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtydkfdrke.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gteyittywt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtpmattgpn.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtoaacyhsi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtjcsclwjm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gtwqgmquap.html

[C14] 泛型函数
来源：http://dali.gogol.net.cn/Article/details/gtiwuxiefl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gtbgwfxfpn.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtyssgpbfx.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtqhblbhdt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sweek.top/Article/details/gtggstftfs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gthteation.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gthtddnkod.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtsvprxiii.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtzbumgkha.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtrlweelif.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtbkifdelm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gttievszin.html


<!-- 参考信息 -->