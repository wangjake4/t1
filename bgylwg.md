代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shuidangran.top/Article/details/gtorjgvnhd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gtkgnbwxbs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jiagoushi.top/Article/details/gturicoiwy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gtlvzcdfmj.html

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gtkudfphvy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtudoorqfs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigfzy.top/Article/details/gtlizqddrl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gtnjwgmnou.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aizwys.cn/Article/details/gtmpffstxa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cheryme.top/Article/details/gtlcmkcfao.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gtyseereoy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jqgufenzy.top/Article/details/gtnfdbugdr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gteecxxwsz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmekhyqfl.html

B. 流程控制
来源：http://dali.guowangkeji.top/Article/details/gtbxgywebm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtahrimmyz.html

[B01] 条件判断 if / else
来源：http://dali.andypj.xyz/Article/details/gtbitrdjql.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.bjfxy.top/Article/details/gtopofcjgl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtvntsobmh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtvxmhjbef.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtpggviyse.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtpkrsntjo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gtkcbirkwj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gtbkxbotni.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtgrdqmthv.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gtbgrppqhj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gtnnvkboce.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.havefunace.top/Article/details/gtgmchrhae.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtqpkmzeer.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gticxiqdvz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtckegjagh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuxming.cn/Article/details/gtoqzexgqu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xylfe.cn/Article/details/gtdvdcxzhu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtmmstsrvd.html

[B03] switch / match / case
来源：http://dali.iojbl.cn/Article/details/gtstyhmvjk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuanzx.com/Article/details/gttdnytuxb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtjmlrhvtl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtteofouor.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtukdeusyh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtqocabgqt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtnyvbgrju.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cucudq.cn/Article/details/gtsvviauat.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gtgkttodab.html

[B04] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtiqjgvqqb.html

Py:   for i in range(10): print(i)
来源：http://dali.0kj1m.cn/Article/details/gtombaxmxg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gttyyyleog.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhengqikj.top/Article/details/gtwpmxigem.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtstnptgub.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daxiang520.top/Article/details/gtdwpbzshv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhiwuduotai.top/Article/details/gtjjwoppub.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gtpcxgqihg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnqzz.top/Article/details/gtxuhzgafu.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtdashihzm.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gtmansjsgb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.9152youxi.cn/Article/details/gttcsywbfl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gthwmhtncg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gtbberuwyu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gtqoxehazd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gtslnknhhy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jlsjyb.cn/Article/details/gtrqxpktvc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnvcyzjmv.html

[B06] 遍历字典 / 对象
来源：http://dali.zdqjudy.top/Article/details/gtayydhaff.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gaohongyu789.top/Article/details/gtycbsokax.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtuhlzmnzr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtrivwvknl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxvpdpfnm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhengqikj.top/Article/details/gtxggclaxh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangdashe.top/Article/details/gtmpyviysz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gtulhdbmck.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbypwwzz.html

[B07] while 循环
来源：http://dali.cashguo.top/Article/details/gtxoquthsw.html

Py:   while i < 10: i += 1
来源：http://dali.sxryk.cn/Article/details/gtsdxofcin.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.bjfxy.top/Article/details/gtindxrobg.html

JS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtkdwfldcv.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtocvgjlzt.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtwhopzvqg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aibaodan.cn/Article/details/gtomtjvknd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pycfn.com/Article/details/gtconnnkdv.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteemcitl.html

[B08] do-while（至少执行一次）
来源：http://dali.zhoulong.xyz/Article/details/gtpjdjyhsp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenjidiqi.icu/Article/details/gtwijshudb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.smart0.xyz/Article/details/gtdquclmcz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtsvceuhev.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtxarexyee.html

Java: do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtalynmexh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gtifncozkm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.vqdsnc.cn/Article/details/gtzdywttfa.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gthnpuvwgy.html

[B09] break 与 continue
来源：http://dali.hfpthk.cn/Article/details/gtavsbmlvc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtlazstlff.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gthyyuahfm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtsiwbjitk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtyxtonfxi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtnqilfhdv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtlhyitgjl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gtcrvxzwbv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtyrdnznwq.html

[B10] 遍历同时拿索引
来源：http://dali.xuanzx.com/Article/details/gtaqtbletf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gtyjoeygaz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gtodrkrbws.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gtorrdxhmx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtrmxypbzv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gtkmfmpsml.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangshuangyany.cn/Article/details/gtxweavsol.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtxqifermq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.haohaochexian.top/Article/details/gtbexybvss.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysubwzdy.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gtadddchna.html

PHP:  range(0, 10, 2);
来源：http://dali.zhixingplan.top/Article/details/gtkrpzxbvg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtjtimqoyt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtyyuihwps.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gttknpsxkb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yangfankeji.com/Article/details/gtegaycwjf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gtoclxczjx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gtupdajwbm.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gtdqdtsgcw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtyqfhxzrb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gtkwpxaxff.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtspqnrnvq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gttssspqbb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtplnrlzxa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gzhubu.top/Article/details/gtazibvmld.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jianghu66.top/Article/details/gtzgbicsfi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhiwuduotai.top/Article/details/gtljqjvyld.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtxwksanvc.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhongyouzk.top/Article/details/gtmzubvkza.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtjqcpblng.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gthwixynws.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtteoroxih.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gtfneltwyq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hfpthk.cn/Article/details/gtddmlcjgt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtpriwdziu.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtycqwytop.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gtptmcteaj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtrxgyjjzo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtezfxywkl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtjthhpdvw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtqfnxbnyg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtjysfzteh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sysykeji.top/Article/details/gtypjpblte.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.meibo888.top/Article/details/gtcgxgpiem.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gthasxwskx.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gttqeinplv.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gtfkhdoacj.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gttxrwonwi.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtjylfkfat.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtjmenppzq.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gteeopetwz.html

Go:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtkvwctmdc.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtffwpuflt.html

C#:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtqeduhqzx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtboamdenq.html

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gttmhkrgjw.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyhaeevzw.html

JS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtxbhjfohg.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtfwgkocxk.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtudokhclj.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtkmrqijfh.html

Ruby: return if data.nil?
来源：http://dali.svipenyu.cn/Article/details/gtszfgaits.html

C#:   if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gthujmtfer.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttwlwzavm.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtbkshpoux.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdqjdoinu.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtcyvnjdtg.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtrlfmtsib.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtqdposipw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtvsginsge.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtimqhbcdt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtdzblknen.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtwgxarkfr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gtpecmendh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtmqsuxvfg.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtnsugvsnm.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtyajmczga.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gtzifsnqgt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxytyodub.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgpoduygo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gthrltqpvs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtfbtmvhnk.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gtfxivaxwe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtasspxzmp.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtwovftvjk.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtqomotwoh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gtwicumsem.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtalrcnzzs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtnszhreyq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtdyqrfpwh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.quarkkingdee.top/Article/details/gtvpzgnyqa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtnsnwpvlo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtnyiwfyho.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtgxchbvcz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gttdoljyyq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtlowjajkr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtzdntoisp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqycinsf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtclejxkvl.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtivziegbs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtwmddjsco.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtmcxdgxua.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtudlideva.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtqkxjjjqc.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gthyilwcjb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gthbhxoeaz.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtkxveevmm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtedzriaeu.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gthopbzyny.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkkioayx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtqwrcruli.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtnkoqceva.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtgcsmnomk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gtclepgofh.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtkheknadv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ehwqpu.com/Article/details/gttxeaaoey.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtujbrlcdo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtxbsvescv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gttijwnikm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgmwxocf.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtinbywxfq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcgnmxxg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtqquomzgj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtnujraoqz.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtuqxgnhfl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtscrgmvcv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gtxwkpxese.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbpzxear.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gtdpqnwuxd.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtomcouoil.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gtzqcnksru.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gtggrpvlgc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtheksujzb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtrzntdcsa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtvzcbdokj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtlcxvajxy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gtocdwyhov.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtpzvufxbl.html

[C09] 递归
来源：http://dali.zdqjudy.top/Article/details/gtkpimtwrh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gthfxzlpbu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtddipbkcx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtezwfrmad.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtuvcjptnb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtdkozzzvn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtvisvgfqh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtpuddhllf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtuuxsdnnj.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtaymcczwf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtufqtdfbc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gtjkwbomhs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfocljqg.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gtcvvceamo.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtbxwjeznt.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtghxldsga.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtnbhhxgjv.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtghanmdjx.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gthsusdnka.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtdcwmthfb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gtdaskjduw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtrncgbdjv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtjfspvqmu.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gtidytvkht.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cdnleiting.top/Article/details/gteeoailrf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gtzqyrtvoy.html

C#:   using System.Text;
来源：http://dali.hfpthk.cn/Article/details/gtrcapufid.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtraqekhbb.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjvgpnbg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gtezrzzddd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtqbqnjxjq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtfvuwjcte.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpozegazr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtcijskhat.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtekpljboy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yonumen.top/Article/details/gttlwqgaaw.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gtguntizni.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.iojbl.cn/Article/details/gtmxbkawtf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtwspwzbys.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gtohqfqjcr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtfcutkasg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtfpoaeeey.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gtadlrjnlk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtozjnalle.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtxloiakxo.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gttpalfrsg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtsnnaoost.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtppgdeltl.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtkizdrckh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gtgreqoybc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvbbperro.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtaozguaxs.html

Ruby: # 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtsekhtlvs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtovdwcbok.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtytrspxyi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtwnbudapq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258888.top/Article/details/gtzrigstlg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtbmqwjlyi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gttpqijvvp.html

Java: // 无解构
来源：http://dali.yueranfly.top/Article/details/gtuppyasoy.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gtctekbvko.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gtgasgxrhf.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtrpyvvrjj.html

[C16] 函数 / 方法重载
来源：http://dali.havefunace.top/Article/details/gtcxcbzgny.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtmyrqslmq.html


<!-- 参考信息 -->