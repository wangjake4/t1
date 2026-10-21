代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gtsgqhmqta.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shuidangran.top/Article/details/gtrkzwoepq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gthnrnlkmg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtugilnjaw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.smart0.xyz/Article/details/gtzctwaphb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gteiygakvr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gtvuroqvad.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gtsswibiab.html

[A26] 类型转换总览
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxsujxpz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.snrcjt.cn/Article/details/gtjcjgjiwi.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gzhubu.top/Article/details/gtvqddgher.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shuidangran.top/Article/details/gtjnssstlh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.havefunace.top/Article/details/gtucosnwpq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenlongwang.top/Article/details/gtemidcxbe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sxryk.cn/Article/details/gtymjklwob.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.andypj.xyz/Article/details/gtuzlaoqna.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yonumen.top/Article/details/gtbjjrynza.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfqleawpl.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gtscnpjaqy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfvdejstv.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gtqzlfhaak.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ybcxt.top/Article/details/gthvvzphqy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtmomuehsx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtgnsukuix.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtefipyagw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtiaqjbgvc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxuanxn.top/Article/details/gtukwquwxj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guowangkeji.top/Article/details/gtthneljnu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtzibawrqy.html

[B02] 多分支 else if / elif
来源：http://dali.sxryk.cn/Article/details/gtilyxskdn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gtquhicrzv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhoulong.xyz/Article/details/gtlmfkaogd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtxxeqvqld.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtusoiarvb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtolxbndqj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigfzy.top/Article/details/gtsbprnmfk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.kuanghao11.cn/Article/details/gtlfhxahke.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtnpyxiqou.html

[B03] switch / match / case
来源：http://dali.kuanghao11.cn/Article/details/gtiltvxigg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuanzx.com/Article/details/gtltyjuwbe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gttedmzkes.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtffzyftdp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtwqbmqenb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtcgukxqhz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtlvohwmdw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gtyraakzim.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtcyegtybm.html

[B04] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtopwizyqj.html

Py:   for i in range(10): print(i)
来源：http://dali.316326.xyz/Article/details/gtadyvcimi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daxiang520.top/Article/details/gtymumdowx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gtgmwhxcxj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtsvkcdgue.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcaglfkrw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sxryk.cn/Article/details/gtxagtvvtb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.fengsongda.top/Article/details/gtgyzsedyc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtiyjlbqvo.html

[B05] 遍历数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtfmqiofdj.html

Py:   for item in arr: print(item)
来源：http://dali.chenjidiqi.icu/Article/details/gtrktnlwot.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gtkcvccnal.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtjraynwsf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtuveogzjq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dianchejie.cn/Article/details/gtzazbjril.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtqutfzuuc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258888.top/Article/details/gtexybyhsm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.aizwys.cn/Article/details/gtpghoviop.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gtqlldylwk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuanzhike.top/Article/details/gtadfktzcv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gtqrqxmomo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtqdqtyqwr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gtntldifzc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hywenlv.cn/Article/details/gtagspwjcy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yangfankeji.com/Article/details/gthrjyonad.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gtjbwhefin.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gtgfdzfaju.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrnkflqo.html

Py:   while i < 10: i += 1
来源：http://dali.zhengqikj.top/Article/details/gtbwqsekgn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yvedp.cn/Article/details/gtusqylyyr.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gthzuhyejj.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtzghfoxuj.html

Java: while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtmikfglvm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ydzc1.top/Article/details/gtcgdownqp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gtpkvthkyx.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtakgttbyf.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gtjbyktxtq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gtnbormzll.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.meibo888.top/Article/details/gtsdhsvwbx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtizwxotud.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtdmnwvign.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtyozynyze.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gtjpgmjbgz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guannengcc.top/Article/details/gtmjgnsldd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtrecvkazv.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtkfxzywwv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gthkhubykz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtmvmuzbdq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtxknkqlqn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gterxekaen.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gthhqvojvd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtxfkwvcoc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sweek.top/Article/details/gtlwrctphq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtylhdgtrz.html

[B10] 遍历同时拿索引
来源：http://dali.xuetiantiany.cn/Article/details/gtxjpjugvi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gtognegruw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gtwtquwirg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtoharqioc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gtphsasygz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqnsytoy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gtrkxggdpe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtwktqetnq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cheryme.top/Article/details/gtcdcswith.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gtzpbxsgoc.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gteflcrqau.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gttiopbyox.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtlgpvilcn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtgkbhfaqy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtmcsrlboh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gtpfcwnzrt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpckmfjd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtriqblack.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gtgbzixvqr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaeemclz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yonumen.top/Article/details/gtigxksuva.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtdtcocnzu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gttiotmnvs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtxzzdyncn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtgrtdyxro.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gthyxqdwhj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gtahqacyiq.html

[B13] 判断是否为数字
来源：http://dali.c1oappe.top/Article/details/gtzfhvltos.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtrahpkcgx.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gtemtqthei.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtdgawkyjf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtedkdcdtz.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuueweog.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gtxlkzktaw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudrbkuux.html

C#:   x is int or double or decimal
来源：http://dali.cqqwz.cn/Article/details/gtuwqvbftx.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtzwklkufq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtgysdidyz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gtkaarxiad.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtlvmxnwgd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtvhbwztvg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtluubewun.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gtwbrmfzvm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbxlknfs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtfhomnmtx.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtmzhufdud.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtrxdtpjpz.html

PHP:  $a && $b || !$c
来源：http://dali.jqgufenzy.top/Article/details/gtwpybclvt.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtubeeafma.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtemseufis.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtvavxtpby.html

Go:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtjzfbtwdo.html

Ruby: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtmcmcbicc.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtpqgdhknj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtrhxwbjsz.html

Py:   if not data: return
来源：http://dali.xinyue.icu/Article/details/gtmumlrzpb.html

PHP:  if (!$data) { return; }
来源：http://dali.daxiang520.top/Article/details/gtyvykuxvl.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseehxztp.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtvvlluiwe.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gteqfgbaqp.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gtyozvhjzj.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtvkvadbwl.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtarsrkmxn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsefomgf.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgjcbpgb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthfhjjmbb.html

[C01] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtlslczman.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gtdqxzbxvx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtaskjakqm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtzbpwdrhq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtvrrgupbv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtdqrvczrb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gtikabdfzf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtdgxucgkd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtslayslno.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gthmttzwzo.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gtcrnfgrss.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gtahugjhva.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtvgoqluiw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gthrhpcdpb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gtzqhxkyvy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gthgdcrsip.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gtynzetrcr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gtudsmfpll.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gtnvqxlyrk.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtpjcxeugi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtvdabsrxe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtnefeuugw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtfjqkhunz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlpccbasv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtwsryppsk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtwqnbzijk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gtkirpojoj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gtnftzktpl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtcxzvtycw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gthbhltrnq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtqlscrite.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtathvpwys.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtnbcajgqt.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gtvqfpisfg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtzpiygzwx.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gttspxswed.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gtktyuafml.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtwkpvlkbc.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtdydhygbv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtkdfnxeuh.html

TS:   return { a, b };
来源：http://dali.meibo888.top/Article/details/gtvbazztzr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbtxamxs.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtolcsmblt.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtleafluyh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjpsmwpj.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtcsjzlcso.html

Py:   square = lambda x: x * x
来源：http://dali.yanxiufei.cn/Article/details/gttfdzpgxt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtaeptipae.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gthiibsduh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtbibzhvft.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtsnipzgay.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtnrlqdivx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gtdvyyylhu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtwcafeufl.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gtzquzydjh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtrahxpkkc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtvtxquxtn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gtdwtieqae.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gtdoolfked.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.c1oappe.top/Article/details/gtqruvkijd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gtegnyfgmz.html

Ruby: arr.map(&:upcase)
来源：http://dali.cqqwz.cn/Article/details/gtwhclrojw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtckemytws.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gtczyemuea.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtcdxokxzg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gtnzescfvc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtjckyrpzu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtazghsriq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gtxqbijajt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuanzhike.top/Article/details/gtwhhbexaa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gtqpctjmzl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gtpbrqcnrh.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gtcpncxtpe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtkncjxuwb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gttamqkefe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtqojnkykk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtrrqfrlvg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtbfptvbmr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlomleata.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtbjjynijw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtqqkhuyds.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gttbecnazj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtjpktchyq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtscvyndrx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtrkrbrdyf.html

TS:   同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtguztropc.html

Java: 方法内为块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtoicqedqz.html

Go:   花括号块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtddjyoaxt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hywenlv.cn/Article/details/gttulgbkhf.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gtqiryoebb.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gtayjvtylv.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpizcdui.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtgzxzxwsr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtagtyskea.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhoulong.xyz/Article/details/gthjgqtvxw.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtehvhylnu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gtnflowrpk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtptcuefcr.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtxvyrykth.html

[C12] 立即执行函数 IIFE
来源：http://dali.haohaochexian.top/Article/details/gthhuwnone.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtofoeylsw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtepshrigj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajpednrs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtofpwzhyl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtpkgaunxk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtdgjkjlsp.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtziomqoez.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtmqyjkgka.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtunyrjvrt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gtlgtsfvjw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtlohgbruz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gthgqlmbqr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtvatglcke.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtkthefrdj.html

Go:   func add(a, b int) int
来源：http://dali.ivvv.top/Article/details/gtfvqwaqrw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gtrapqpspe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqhytozq.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gtiwaujogp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gtqkqjxtwd.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtyiqlculs.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtkhzysdna.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtlnbicvdp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gtbitlpvps.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtdwwstzkz.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gteucgzyik.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtbbwyksdd.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtswswuzlm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gtlxyvbhkz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtrfcwvhph.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtrunakgwe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtysxsszni.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtrzwxeusk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gtwpemndnm.html


<!-- 参考信息 -->