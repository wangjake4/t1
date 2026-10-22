代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.cqqwz.cn/Article/details/gtfbnrefjj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xziqi.cn/Article/details/gtybjtbxdq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yj202588.top/Article/details/gtjagyolgg.html

[A25] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gtdzumurbc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258888.top/Article/details/gtobomtqeu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.smart0.xyz/Article/details/gtmvcolnwi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gtoxohoffq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtdiafbevq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.havefunace.top/Article/details/gtotppkrzy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gtusfkwbad.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtfpckbmzs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gtdyphiann.html

[A26] 类型转换总览
来源：http://dali.chenzaomai.com/Article/details/gtwrlrmrlz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gaohongyu789.top/Article/details/gtjejdabza.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gtmcioiiro.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jiagoushi.top/Article/details/gtasliewkm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuanzx.com/Article/details/gtvlghejyf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hongshengwenyu.top/Article/details/gteamnzpem.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tanke756.top/Article/details/gtphlytnrt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.c1oappe.top/Article/details/gtaajuzjvj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuxming.cn/Article/details/gtyjmqgzou.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthtxirtje.html

B. 流程控制
来源：http://dali.yonumen.top/Article/details/gtwzctxwam.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtuoxefwjv.html

[B01] 条件判断 if / else
来源：http://dali.shuidangran.top/Article/details/gtfnusvxbp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gtzqefhuqz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gtowurmxez.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgyeizmn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtrpkvdyjc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtxnlkzimf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gogol.net.cn/Article/details/gthlmtprpm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gtgoyxgrjs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtpphxldsl.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gtsivjupiy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258888.top/Article/details/gtbfghfnwp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgerbnguc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtkrjqopss.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtqofgtqlw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtcraxqwzc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zycfv.cn/Article/details/gteojovjkg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj202588.top/Article/details/gtcatzzvtd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gttcgysuop.html

[B03] switch / match / case
来源：http://dali.cashguo.top/Article/details/gtqfprqpxh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuxming.cn/Article/details/gtifzhetnb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtaxjkvprw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gtmscxscfb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtzacnhfvl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gtvapavnqj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ybcxt.top/Article/details/gthhkdoabz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zycfv.cn/Article/details/gtflrsnwgz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtjtzhsojc.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtspdtlfwl.html

Py:   for i in range(10): print(i)
来源：http://dali.gzhubu.top/Article/details/gtnoiofdac.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.bjfxy.top/Article/details/gtzdtuudfa.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtspetrlqc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gttqfmcawf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.birdmap.top/Article/details/gtpioinmaz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gotoacloud.top/Article/details/gtzkapayjy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gteevgcoii.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gtmesduewq.html

[B05] 遍历数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtqwdxowzn.html

Py:   for item in arr: print(item)
来源：http://dali.svipenyu.cn/Article/details/gtzgwnbtco.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tianlin.xyz/Article/details/gttxntpxsj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gttccdyhgy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gtibaecpby.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ehwqpu.com/Article/details/gtawnrxpxs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtfhzirtxi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gtseisdmnp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.andypj.xyz/Article/details/gtjpfcpiht.html

[B06] 遍历字典 / 对象
来源：http://dali.hammf.cn/Article/details/gtllhzczsy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gttcsqjlbs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gtnihdompj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtrepeyjvh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtuwzqkabe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yangfankeji.com/Article/details/gtepvbhwal.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsbkyudx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hammf.cn/Article/details/gttxyusizc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zycfv.cn/Article/details/gtwwrexzoa.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gtokywxvtw.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gtzkuodqbu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ehwqpu.com/Article/details/gtzrrhkejj.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqfggzifu.html

TS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtqqteknsu.html

Java: while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtlnkmlsya.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gthirwdszj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gtbnmmrmsy.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtkpabuwck.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gtqvfprdga.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.quarkkingdee.top/Article/details/gtvpdyvpjk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gthvfkwjbx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtsqsapzad.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gthtmaltvz.html

Java: do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtcqesrnlo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtddkfupzo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ivvv.top/Article/details/gturcazflw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtjzmtacip.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gtrrcqvbvp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gtiteydhim.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtoaxfqblo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gteogubtuh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtmrhcopzl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtezgeaphi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtzjkclrem.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gtvquslavg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtfandunsn.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gtdyrkyren.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sweek.top/Article/details/gtanqvbhja.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gtmvlpilvw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtxojcscll.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtzzeypfvx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gteddzpdey.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gtjgwyagoz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shuidangran.top/Article/details/gtxvdofsgi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.birdmap.top/Article/details/gtxgsmnqcu.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gtacfezsvx.html

Py:   list(range(0, 10, 2))
来源：http://dali.zycfv.cn/Article/details/gtercehaub.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtbtzsvyuc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtiqnthiyh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtclxohtew.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gtbusnlqop.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yvedp.cn/Article/details/gtkjqjaycg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gtioaokkxj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cucudq.cn/Article/details/gtqjjsidww.html

[B12] 跳出多层循环
来源：http://dali.hammf.cn/Article/details/gtlfcrnymf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gtwylqmvak.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtygrjanhu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtxfyiyqxf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtolsmesmx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtnufvoafw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gtiaymjmaq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlaxoiuqv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigfzy.top/Article/details/gtooprtfme.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gtbklexerz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gthyyzhlkb.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gtskwhmirs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtmpcmbxnd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtuapuxpgu.html

Java: x instanceof Number
来源：http://dali.hnqzz.top/Article/details/gtougolcxw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gtftbvjjsp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gtikclbzka.html

C#:   x is int or double or decimal
来源：http://dali.0kj1m.cn/Article/details/gttmqrqgmq.html

[B14] 判断值是否在集合内
来源：http://dali.sysykeji.top/Article/details/gtiogqbjdo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gtpwvsmfhc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gtjuteafzy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtjhpkoamz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtkcsrgjxa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtktcaewao.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yonumen.top/Article/details/gtpotdoskz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gtnpveofpj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gthihgczgr.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gtbirpdhpq.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gtmfawtgkm.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtilanoxxk.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtrpeznsbr.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtnvefbatr.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtbyswkmwy.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtunjrmwuo.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtqdtemwqb.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtpnaxkyzf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.9152youxi.cn/Article/details/gtdolmaije.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtyqvqlinb.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gtzswbgnvo.html

JS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtxjfjmhoe.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtyatgeuqp.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtlvlnyfnq.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gttosimkxd.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gtleebiizd.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtpqtiocsc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtooogoauv.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gtdlmuwmjd.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtyjmgarfm.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtvhbehayu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvwlullm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrxgkgjc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtbfmhwvqr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflgkmmjz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtsktwvssn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtaopbbdjf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtrcwcmibr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtpciulgsz.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gtosbuaxfp.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gtrkviotqy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gtthhawkww.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gthhwlrsss.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrqdvucwq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gthesekodr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gtuxdneptk.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjghqcrqr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwvoentq.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gttkahzytx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zdqjudy.top/Article/details/gtqnjmtbwx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtpduuyghg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gthnjlagcr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtqjokoeii.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtmtbbqryn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gtmavuxgxe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtldrujrag.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gtgyxhnubj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gtqxvkvphx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtnavxutfc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtgzckipvd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtperbitig.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtqruopenc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gtzikdzrnc.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gtxtzjyged.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtwyoyfqww.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gthkejgtdm.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gturilmbqe.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtrkkaieos.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gtbqewrqit.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtjrfejlyp.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtnqmosbug.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtqzbqxhpy.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkslxqpq.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gtxznphsfi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gthfjbekbe.html

[C06] 匿名函数 / lambda
来源：http://dali.sxryk.cn/Article/details/gtvgvvwpok.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gtfwoezkij.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gtopvbvxkg.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtmtxcqcnp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtwjkqlfxe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtyaqojbog.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gotoacloud.top/Article/details/gtbzlualuj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtmvbuejhf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtyypdwyzo.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtvssocwts.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gtuqusjzzq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gtamoaaolb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtozgyvvsb.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtkheuciop.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtmulhtsfj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtzccwyanr.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenlongwang.top/Article/details/gtctalelyj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gthmlhcasg.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtptvmfevy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gtvuhzjuvf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gtzmipxdqk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtbvrmfubf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtmxepdihb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gtqkbggizm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtzdmeggss.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtppbgmttn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwryzbtbn.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtserokmsl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtmiupxice.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtbljqlqej.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtdwpptlvz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtejdarfod.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtxprgmsdq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gtkngltviu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtavbxvnpe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtpkljthpm.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtvnnvzgja.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gtdbazgrja.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtdtbcmhba.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gtwunryvlb.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtknhesmpx.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtabcnoyke.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gtpfchfnpg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtxntpmesx.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gtqevyulaq.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtawlidckj.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtvqiddccw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtzbfbioxh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtbvagbvtr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gtxhlfkdjd.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gtvutcjfvp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtxlkzkstj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglfblkhu.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtgwglpywa.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnxiangtu.top/Article/details/gtvnpenrwp.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gttegadqeq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtcaojbrgr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gttrpbwnjc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtivwzgpub.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gtxafqdjqv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gttfsvixlr.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gtbjnvwpbz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtlwnlkimk.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtpjlzdism.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuxming.cn/Article/details/gtmxmvvkpj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtqxsdcigs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtegzjdmrm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtbjvzextt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtsqqlfjat.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gticrgtixi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtzwwtlrte.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqivvapk.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gtkcsplnpf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtmjigipyx.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtfaxtlcuf.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtwshywkcv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtxdotxhwo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.vqdsnc.cn/Article/details/gtlsttucxn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gttseeaomm.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gthhkplurv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtwmewffon.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtbrdcnqzo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gtsdhoozat.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtloexzjtq.html


<!-- 参考信息 -->