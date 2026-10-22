代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.jinqigufen.top/Article/details/gtzozeozhl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258888.top/Article/details/gtkyplcsbn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtgfuumuzy.html

[A25] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtzecgtydq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.snrcjt.cn/Article/details/gtwaolxtka.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yangfankeji.com/Article/details/gtzkssxdxd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gttbegufnp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvydudhjs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gogol.net.cn/Article/details/gtdrowpqxn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tian-w.cn/Article/details/gtrfxmtpsg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gtcllchzab.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gtrgwtzpxj.html

[A26] 类型转换总览
来源：http://dali.hnxiangtu.top/Article/details/gtuoxufjjv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxinkj.top/Article/details/gtwpbkmmum.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gtvqygowzu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yangfankeji.com/Article/details/gtjdcrgdxz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtayhwuyfd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtgchthcjo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yangfankeji.com/Article/details/gtkoyqpije.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxumxdxk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtdkqxiqxd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtlvbmvrlx.html

B. 流程控制
来源：http://dali.jqgfzy.top/Article/details/gteqsubmxg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlonforah.html

[B01] 条件判断 if / else
来源：http://dali.zhengqikj.top/Article/details/gtxuzzlrap.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.316326.xyz/Article/details/gtljrhvlar.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtolsvjfqy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtifvbfurn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtauowlzar.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtbtsqzwal.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkuodkut.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gtksgfrtpi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gthfasyhzp.html

[B02] 多分支 else if / elif
来源：http://dali.hysaishi.cn/Article/details/gtigolidvb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gtwybcnzgm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkuhzynq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtlgrvsmzi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtlejbmgdm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gttnqdkzdq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gttvjevkqb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xziqi.cn/Article/details/gthwrhswbl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtvmmdzwhe.html

[B03] switch / match / case
来源：http://dali.zhoulong.xyz/Article/details/gtdevtdatu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtwmxkonut.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtpswkykwe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtkektuadi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtcsniybgg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtgojarrds.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhixingplan.top/Article/details/gthjgfvrtz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gtpigcgoia.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtpftvczwm.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtyzldsqmz.html

Py:   for i in range(10): print(i)
来源：http://dali.aizwys.cn/Article/details/gttdaamsws.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cashguo.top/Article/details/gthhvatpac.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtblgofcye.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtwjgvxmma.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gttcnnipjj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtxqteijkr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hammf.cn/Article/details/gttpqmakvb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxinkj.top/Article/details/gtyqhkzcqq.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtlkgadsgo.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gtrwijzsoe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.quarkkingdee.top/Article/details/gtsszlynsa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtnubsjtvz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtmiubrgmv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtvhoqlpsv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cqqwz.cn/Article/details/gtxttugufh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gthbvitjda.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangdashe.top/Article/details/gtxlzqtdfi.html

[B06] 遍历字典 / 对象
来源：http://dali.daxiang520.top/Article/details/gtcjoshwrg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoeusnkv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gttoycfadk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtkwjhjrfl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gtyctnzydi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpilvptrq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gtbmtiioot.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ybcxt.top/Article/details/gtfcfnejop.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.meibo888.top/Article/details/gtbggoywwh.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gtpqmhdnxm.html

Py:   while i < 10: i += 1
来源：http://dali.jianghu66.top/Article/details/gtpfbyuylw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gtruucilla.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtxbeootrw.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtihqdddpc.html

Java: while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtznpxnkcq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gtuhterwqs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gtngfskzpd.html

C#:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtvhoqqsko.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gttvuurxzp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.c1oappe.top/Article/details/gtmxbkqrkz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtbggdbstv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjafpcnli.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtsjpdlxin.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtoaodiwnd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xylfe.cn/Article/details/gtbinulogc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cqqwz.cn/Article/details/gtsjsfmzjl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gteyuejetv.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gttnuewzzk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gtocnwgxwt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtbqglsdwy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtwgnvxnay.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtwcghcnjl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtrprnrqzl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtbxqqzbga.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gtaansnkes.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtkwtvbghv.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gtmxvedujs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gtwvxwaaka.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gtlarkdvog.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtjkajmjmc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtggsktxqo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangdashe.top/Article/details/gtlpufzifh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gtbbbjppxx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhixingplan.top/Article/details/gthorkcqwm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtlafaizbs.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxuanxn.top/Article/details/gtdcpshrsm.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gtjgcsocds.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtwnyqjjju.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtwalzxqyw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtlpkvaidj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pycfn.com/Article/details/gtowfstpxo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtnvngnkdu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtimpghrgw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gtlckcmozn.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtthtvnygq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jiagoushi.top/Article/details/gtcgnypuku.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtcqwrwxvg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtmvobyojh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtlhfbpoyb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtbnkwvjdu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gtfxkrcoeh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gtrpkojpde.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gtqeycombd.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtomxxkxwz.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gtjgkqqyav.html

PHP:  is_numeric($x)
来源：http://dali.jiagoushi.top/Article/details/gtlvxltudq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtkouttdgi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtulafcjed.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtciwwacxk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gtyhjblkoe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gtiittyzsy.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtmqbdpkzj.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gtyukzakos.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtqzhtqylz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gtrjgvagbt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrxpwaznh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtlzmgesqr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtyurhlkxf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtfazwbski.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cashguo.top/Article/details/gtculnxtad.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtwbqbgarq.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gtqyxyzpwm.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtskzvslbc.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gtynddquhg.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtwtskeivl.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtlayddgav.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtmgmpgxmm.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtncwebczd.html

Ruby: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtvtbfmwdt.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtrjrqvtep.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtswvvtzbt.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gttkvxknhn.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtytqvlutk.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbnbdjwn.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtyjuvmlsx.html

Java: if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtoaisykgi.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtlkskpcbg.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtmbcoxuyj.html

C#:   if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtjsuznrxk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfshgode.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gthvbszcak.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlwnyywne.html

[C01] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtpxrpmzwx.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtmbafxcel.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtlwvzmaes.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtpmzpcyct.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtmgvclnjv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gthnmhynxu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtbygbipol.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gthtpqlftp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtekekcjvq.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtkvjriueb.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtqhihpgzi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtiwuhxblh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtemywoias.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtfeuheakk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtrbbstgqs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtptmnrtiu.html

Ruby: def greet(name = "World") = name
来源：http://dali.snrcjt.cn/Article/details/gtstsydkpc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gtjbtzueyv.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gtnnwhgxmd.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gtxyahauka.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gtrryabgku.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtowvygobm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gtslboecfy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtyftktvas.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtfyujgcih.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gtambdbytg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gtremqmrvo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gttnxudhlu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gtdrunujuv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gtdrpkxwdy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtrzwkvopl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gtkugcycyj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtzkbzvruu.html

Go:   // 无：用配置结构体参数
来源：http://dali.iojbl.cn/Article/details/gtofijhduz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gthrmgsnfd.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gthwenfeba.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gtqrjvjpdr.html

Py:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtdujuyenp.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtngcpyfcd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtaodgesbn.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtzoxiixtt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpkefigf.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtozbauyse.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtjzbysatb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtlqtkpfjz.html

[C06] 匿名函数 / lambda
来源：http://dali.yuxming.cn/Article/details/gtujoxuvli.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gtyhxcvutw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtoabfsawb.html

JS:   const square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtluxatqis.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gtgrjeoyat.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gtctzhyqew.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtznlitghu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zdqjudy.top/Article/details/gtzfmgcauc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtpygvjcpz.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gtzaicatjq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gtayskspac.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtfahwraoj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gtsujyzcge.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gteqqtgtxt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gtyulkdwqq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gtyerchvtw.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgmutohv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gtddfgnkai.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtvtpwhblt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gtglzaiwcc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gtkzwirgys.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtatqpfztq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtnbnzdwlq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gtarzgbniz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtezpbzpjd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtkfericmn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtrbgxqsxf.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtbaqsuknu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gtbueanqcv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtrghwdquq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtlkxjeovf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtstnhwkcq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtwbjzkpwd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gtoqufwofg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldnjfuzb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtclhiagns.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtlxyqbqza.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gzhubu.top/Article/details/gtnldlorxx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gtktpqcomv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sweek.top/Article/details/gtalubhxwf.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtugmnrpdb.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgtirzfh.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtupuyvjwz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gthwejujux.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtlqlwesuk.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtskxhipcm.html

Py:   from module import func
来源：http://dali.haohaochexian.top/Article/details/gtxuxirwub.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gtvfexltgn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtwzobbzsp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shangyingyoupin.top/Article/details/gtrlxskpdu.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmfkrmfi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ybcxt.top/Article/details/gttbjcionl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jyoumei.cn/Article/details/gtqazhbxfv.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gtionzqsnv.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtugshkxje.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtrecplmef.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gteseiuufr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtjdwxmfgp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtzxkyxyws.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tianlin.xyz/Article/details/gtmjkmjgvv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtbcojpgxw.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtlkopiwos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gtivbnyggm.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gtmejfloyi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtinobjxom.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqzszhko.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.bjfxy.top/Article/details/gtwneououp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtkvmnylxv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtelnhdpch.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtrurfwgku.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gtpdoylwpy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gtzosqochd.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gtjgfinems.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gtqidyamnd.html

PHP:  // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtcsjygbtc.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtclnczobw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gthnpmvgyu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gttrbkabdf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gtrwnpljzx.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtcifcryxl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfydxuyy.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtbhzkxlgp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtqgnszjae.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gtcyonwile.html


<!-- 参考信息 -->