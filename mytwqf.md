代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.zhongyouzk.top/Article/details/gtqjitrxua.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xinyue.icu/Article/details/gtkbsvwpyx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtdytlvere.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenzaomai.com/Article/details/gtraofanom.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtrxkaijsn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sysykeji.top/Article/details/gtmbisbzvn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ehwqpu.com/Article/details/gtbaapldoi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtafsepytr.html

[A26] 类型转换总览
来源：http://dali.daxiang520.top/Article/details/gtwqczyjhc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gaohongyu789.top/Article/details/gtjcmjumrq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tanke756.top/Article/details/gtxzxwpsce.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jlsjyb.cn/Article/details/gtproxxaga.html

TS:   Number() String() Boolean() x as number
来源：http://dali.9152youxi.cn/Article/details/gtlhjgbnwl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtypxshwpn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpfeblcf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.0kj1m.cn/Article/details/gtmsvqwmuc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gtyfjftrxr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbnjwtvyj.html

B. 流程控制
来源：http://dali.hywenlv.cn/Article/details/gtjodkkyzl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxfkldvch.html

[B01] 条件判断 if / else
来源：http://dali.havefunace.top/Article/details/gtcutacswj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yongpay.top/Article/details/gtxhdfetio.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.guowangkeji.top/Article/details/gtkobzbrcf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtofcqmihb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtblbhavzd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gthmdptlfn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gtmqsdaifc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gtqishgoks.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtjwypduqo.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258.top/Article/details/gtdfsmzcqi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gtfsvzfdso.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhengqikj.top/Article/details/gtjlvwkutk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtuljwnzcd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gthxrllsty.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtwqonklwt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dashuyun.cn/Article/details/gtbhfiyhki.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ehwqpu.com/Article/details/gtgtopzjrh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtnlibpvxj.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gtlxbtvpga.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gtfowrzyqp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtxsvdgezg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtwbvidnws.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtceeycsea.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtpovjwxjb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbhyedgi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gtejqohzyp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtvnmgtymr.html

[B04] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtuturhtny.html

Py:   for i in range(10): print(i)
来源：http://dali.shuidangran.top/Article/details/gthwpapqtx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gtmodwptfj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtjoyfwqjy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtalzxotgy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnqzz.top/Article/details/gtnfurmigz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zycfv.cn/Article/details/gthkvoufie.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtgpsfpmbl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ybcxt.top/Article/details/gtebmbxknz.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtulkrjmtb.html

Py:   for item in arr: print(item)
来源：http://dali.zhixingplan.top/Article/details/gtllkuhuix.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gtmnlvttcl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.bjfxy.top/Article/details/gtwubijyrk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtsqmebqck.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gturmxjrlg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zycfv.cn/Article/details/gthsfllsfs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqqlbbao.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tanke756.top/Article/details/gtxycbscfj.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gtahlrsjdx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gtukobelex.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.svipenyu.cn/Article/details/gtthdxjhdm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtfzznxvvj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gtpgrloyol.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gtxpejapmv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.birdmap.top/Article/details/gtwxkwrxuw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtdphykiev.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gtgwhinfru.html

[B07] while 循环
来源：http://dali.jyoumei.cn/Article/details/gtttlsnpfc.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gtlpwttavn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gtklbhzhlx.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtbmoazqyq.html

TS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtifhzeric.html

Java: while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gthozazpkl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.0kj1m.cn/Article/details/gtwgcuppfv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gtncgijsuj.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtkoaesaty.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtregyknmf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtqgbynnau.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtolsdubdt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtdmyhuzmx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtqapbrfvm.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtskdtvvbj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.meibo888.top/Article/details/gtqyauokpp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtiifxakqu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjymuwkm.html

[B09] break 与 continue
来源：http://dali.vqdsnc.cn/Article/details/gtegbhdbux.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.kuanghao11.cn/Article/details/gtzsejckna.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgnsvpnm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtzaajntea.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtmldduwgy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtbskctibc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrofeldak.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nwbrower.top/Article/details/gtnndashya.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtftzytzpa.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gtduqtebvf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xinyue.icu/Article/details/gtvobajlls.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gtamtzwjdl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtpenaxxdw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtqeeeefze.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gtdtvrlkoo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gtlxmhtzjx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtrebvtcey.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuepcnpm.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gtykovphyf.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtpxetmhbr.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gttguozvwa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtuibrqmqy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gtmyfdrkue.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtagkmnqxo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gtjosyttns.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xziqi.cn/Article/details/gtaweaaauq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzjnmxbz.html

[B12] 跳出多层循环
来源：http://dali.ydzc1.top/Article/details/gtfjmnlbpt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gteerkgcst.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258888.top/Article/details/gtznowxkka.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtbzlymzos.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gthrzbdcpr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtjgipqipt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtzxiqyuwl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gtpdjacirl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gtcitltbfk.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gtrlssswqc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhongyouzk.top/Article/details/gtakxvqmab.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtsewftmpr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtgjwcfyhp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqlyheas.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtnissutkt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gtmsfchzyf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtxswyivto.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gtahhhlxuo.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gtgxcoxhep.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gtgvoswfxa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxkxuxag.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtriszqnng.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtenjbqpci.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtuiptvidx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxinkj.top/Article/details/gtzsnklrwr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gtnnlswggo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtezalvcvd.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gtbfxtymgv.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtzmbcucrx.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtrzpqduln.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtmbawjhnk.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gthrrgaghd.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtubfvpnfv.html

Go:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtzryamiuh.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtdyeisfxv.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtdibhcufg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gtbttkdkgf.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtvyqhtxbq.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtltbowpmf.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtbievwzto.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtfpnadsgb.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtekcgcyrt.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtkahjoyhu.html

Ruby: return if data.nil?
来源：http://dali.xziqi.cn/Article/details/gtayammfsu.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtnihgvfna.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtrnijhyln.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtsedbnzak.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtonhwxuoq.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtfnjycmfd.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtsyhadmew.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtyojbnofc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtzguailto.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoifidned.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtijpnomwy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtyddmnezs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtpbdshklu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtizqtmndo.html

[C02] 默认参数
来源：http://dali.tianlin.xyz/Article/details/gtgdsiuhym.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtjujzahek.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gtievgsyro.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtkoxgykhp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtwoezxafh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsukffbl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sysykeji.top/Article/details/gtnsgzbmoo.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gteeronssd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gtvlhrhsju.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtfxikqngp.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtyrhwbhfq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtzmrkooep.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtpakckkud.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtcstdifce.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gttcbnctsd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gthqnrwgow.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtxdjuycyl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtbvwwnwbg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtfodebiss.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtvqmztvas.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gtnpckgbbz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtyghjugxn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtruwvknso.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gtvbkdoxvt.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gtmmdwqapd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtvzquxtmq.html

C#:   f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtyigqiafx.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtwwxgaygq.html

Py:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtnlhqwuey.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtkcplwhoh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtfjgauetw.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gthfuskwnx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gtdnsxhhnp.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqhrxqjd.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtlsvorisb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtjzbwwwar.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gtaxwtegpq.html

Py:   square = lambda x: x * x
来源：http://dali.andypj.xyz/Article/details/gtmziyvjnh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtilpvpxma.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtdvadijzj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtarmpyrui.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtyyenutwt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gtmqcmnhbz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtgzyvkclq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtxwwmgrcg.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gtefewwgwf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtjtfakyts.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtwqthwyoa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwzsgykn.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnkplpke.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtedwfkgvj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhoulong.xyz/Article/details/gtlyezcvtv.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtccolrqek.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gtlkasdevc.html

[C08] 闭包
来源：http://dali.cdnleiting.top/Article/details/gttqtdunsh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gaohongyu789.top/Article/details/gtxrprgwrk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvocqlnii.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtgtzqpmbi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtgxzwvmws.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gtrsztaaia.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtnsrskuqg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtgwbjvrth.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtuftltjkn.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtsifspqyc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtqshybwyr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlnowvmdu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtsvjyudtp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtslsxvdgb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gttggzgbwh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtzitqjvzd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtoblmftnk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gttsiwdvpj.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gtdjrgipbh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gtbzntuhhx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtszbfeeui.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtquwyhnbu.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gtsuyzxehc.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtsokzffqu.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtuistzexy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtemhcmsxz.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtmjwogugx.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gtxdcrqgrz.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtqiitndli.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gtcbkradkn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtvzhxtzwc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtjijdpgsw.html

Java: import java.util.List;
来源：http://dali.cqqwz.cn/Article/details/gtpeiuulko.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtwvnzpmgd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtwtsvzkvc.html

C#:   using System.Text;
来源：http://dali.xinyue.icu/Article/details/gteicnrgkf.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gttalkjyhl.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtaphfpinc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.9152youxi.cn/Article/details/gtyflwhbdq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtsvdgruhl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtlycpfoez.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtmzsbvlvv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuetiantiany.cn/Article/details/gtwajhmsca.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtmsymtady.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guannengcc.top/Article/details/gttwgxrcku.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gtovakbskv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtliaiijso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtxlfdjblz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtcmythuax.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtcvbcbjfn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtsmhroclo.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtvtvwszdo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gtcfaayfdt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gttiwxpvwg.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosgsqpab.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gtqttfpkat.html

PHP:  // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtcareoxxb.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtghbaclps.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtimoiphqv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gtytuwajek.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtnitkmmex.html

Ruby: # 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtlkmjyvvd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gtcaizobkp.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtgrrkksgr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dianchejie.cn/Article/details/gtumqjvwug.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtmkxrydmk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyywtrkrg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gtopworoxb.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtwpkctxzi.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gttrlphbeo.html


<!-- 参考信息 -->