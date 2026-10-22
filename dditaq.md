代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gtaeykqpil.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmpghqki.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhiwuduotai.top/Article/details/gtfwbjfbax.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gtchumlgty.html

[A26] 类型转换总览
来源：http://dali.tianlin.xyz/Article/details/gtjcdxkhpg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsestqcni.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gaohongyu789.top/Article/details/gtcgfbfoly.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tanke756.top/Article/details/gtmuoavgta.html

TS:   Number() String() Boolean() x as number
来源：http://dali.meibo888.top/Article/details/gtezcsohwb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtyjpdwtss.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sweek.top/Article/details/gtrprfbnuw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gtqdqhsdaj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuxming.cn/Article/details/gtgenqtfyv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtkcsflahy.html

B. 流程控制
来源：http://dali.cucudq.cn/Article/details/gtpnjwraqk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfglllnns.html

[B01] 条件判断 if / else
来源：http://dali.ydzc1.top/Article/details/gtaouirdbr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gtivzaerok.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.9152youxi.cn/Article/details/gtftjsdlgp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtkaqchybl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtdphlabjx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtfywxxxba.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gtklxoriqb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigfzy.top/Article/details/gthylkrfjd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtpdqlbzwg.html

[B02] 多分支 else if / elif
来源：http://dali.guowangkeji.top/Article/details/gtnkfrwmph.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sweek.top/Article/details/gtewdecwph.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gtdflbbfol.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtgqruaiss.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtxlyvczjz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gttdgcobed.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shuidangran.top/Article/details/gtlffrcfug.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.svipenyu.cn/Article/details/gtlobhmsgo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtsrcbhnjl.html

[B03] switch / match / case
来源：http://dali.cqqwz.cn/Article/details/gtkwkbeeoe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhiwuduotai.top/Article/details/gtknnikhwo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtnofysxhg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtjklfkygo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtuikilcgu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtvmlkaqxs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenzaomai.com/Article/details/gtrjmbdavh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gtezkhamug.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtsbznowdp.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtjvrjolkj.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gtxidvilfd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hfpthk.cn/Article/details/gttkbgolej.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gtsuyknskg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtiuxavniz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gtwpwiqwnv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gtrseolgqd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gtttzbotkd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.mhx1999.top/Article/details/gtjlbommsm.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtwidqcnzg.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gtrwyjjodo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.fzhhl.top/Article/details/gtrnqusgfl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gtvrhtottz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtnscdzxbg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gtbvfvryly.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxinkj.top/Article/details/gtxottqfrp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxinkj.top/Article/details/gtnnhgtuxv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.smart0.xyz/Article/details/gtmitmkbes.html

[B06] 遍历字典 / 对象
来源：http://dali.316326.xyz/Article/details/gtyhutsylp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gtrizidexy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ydzc1.top/Article/details/gtkmlpkazj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gtlxtliyso.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtkwxixvgn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtvnxslwgv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtvhggnvtn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gtzffutwjn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yueranfly.top/Article/details/gtzeebxifc.html

[B07] while 循环
来源：http://dali.yanxiufei.cn/Article/details/gttsabskrx.html

Py:   while i < 10: i += 1
来源：http://dali.ybcxt.top/Article/details/gtwozowyjj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.bjfxy.top/Article/details/gtmukxvomw.html

JS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gthjbjncjj.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtitijyjwh.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtnyhmdy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gtbavtgval.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nwbrower.top/Article/details/gtljlitgfs.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtrdridtan.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gtlejjoxzs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tian-w.cn/Article/details/gtpwvgbhpl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.smart0.xyz/Article/details/gtqszqogkl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtiddpoanj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkqcuktu.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtdwmbjdas.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daxiang520.top/Article/details/gttzvxamcu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gtrrjhldgw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtsjcjfsdo.html

[B09] break 与 continue
来源：http://dali.iojbl.cn/Article/details/gteozylfof.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gtilhaeoqt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtotdtndzv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtdggvdtga.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtmtqamiqw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtsjbypkvq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gtpmavzxds.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gtplaoytan.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtjtgaxdhc.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtvrnwqfhz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuxming.cn/Article/details/gtkbaahxau.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvkwxtkl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtsgjbtomg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtasgufrlv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.havefunace.top/Article/details/gttjyyonjd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gtwgnzdslb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gtbcirgirn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtnbffwfkf.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gtedfckilw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gttpqcwutz.html

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gtbfzpxqfg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtlkhgkimz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gttqerrfbc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aibaodan.cn/Article/details/gtbqdwkced.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gtvaycperl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xylfe.cn/Article/details/gttkzrrpgz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvwmcgjf.html

[B12] 跳出多层循环
来源：http://dali.316326.xyz/Article/details/gtiqtnavwr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gotoacloud.top/Article/details/gtlcvpqveq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtkplmajgl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtndsfrqgt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gthlwkcpwf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtwizrbjph.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gttewovwsy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gtgeoibmmu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gthhwvhgwu.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gtikkxhijv.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gtlkbgqqpt.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gtcvhrjboq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtbpsslibu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarqqditv.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gtxatsfrrn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ivvv.top/Article/details/gthuayznjt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtqfpbilrs.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gtihhyihup.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gtjxzraxpn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gtojavcsls.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gtgsqnxzer.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtftiqdpap.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtgknohwei.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtquuxzmgj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhongyouzk.top/Article/details/gteyupgqjt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gtpnracfoh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tanke756.top/Article/details/gtnoltqjmp.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gtfwazoxil.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gtfaopimal.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzlslkui.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtllovcxjk.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtdqbemccl.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtwzitnfiz.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtjjfhaond.html

Ruby: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtcanrpmhk.html

C#:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtijqhnxfd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gtlfwyhjne.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gtyruahjtz.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gtfkvgrkhj.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtbcrodvhi.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtqabzjfoa.html

Java: if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpcsvviw.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtaizrmudo.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gtplwhppey.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomezuxzb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtknngvzsb.html

C. 函数与作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtcciagonn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtyyxyybkw.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtquntcskg.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtuijylugb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtweypbjzb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjexlldmz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtrhsvqaio.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtngcwzroh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gturfbjsbn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtiymtxwos.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtlnqldsdo.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtnuszfkqw.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gtoomeaxey.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj202588.top/Article/details/gttnnkvroo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gttmhlqkdm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtknrcjqpm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gteookplkv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtyrckvcui.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtnldongmn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtskzuayyd.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtwjgaxsrl.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gtvsvgvync.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gtxqjafhro.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtlztsnteo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtopaetcfo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gtambnwhei.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gtznzranue.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtimpikyah.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonwokhac.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gtyphrzujo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gtpzgerupq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtvrcwgldn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtitwvagfk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtacypcnvm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtusqocvio.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtgjladgzh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtowacgusp.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtksoszzup.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gtbkgtosok.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtwskqzeyz.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gtydeyigtf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtqvimgtcl.html

TS:   return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtvmtcsdiy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gtieqhdmro.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtlgzaifgo.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtuywthfao.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtkvjcuqxm.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gtmsqnoepr.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gtjpkunbuq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gtbnbckjdj.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtbfyesgdc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtotzggapu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gtfedlfbxq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturdrmibo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gtsfuhnmla.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtskhbclnu.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtveobdkuo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gtoekcaiuw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gtcqdgasjl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gtjyukzqec.html

TS:   arr.map(String)
来源：http://dali.fzhhl.top/Article/details/gtfffnqskn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtuogvqzme.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gttwkccaym.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtzaruriap.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gtycrutkhx.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtugcwefze.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhoulong.xyz/Article/details/gtqgnrfxaj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqdjmcxke.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtzakqrloo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtvobphxlx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtriqzuzvq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtnalmdwbc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtmcjqatdf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtvvecxfdq.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gtdrslkclt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtwcopaveb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtfshzhaoh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtjpekveue.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtmtideujw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtpxpagmzj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gtxedfhyvt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtsbvuregs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtwuojjvqf.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtivfejewq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gtqzjnycuq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtablirhps.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yangfankeji.com/Article/details/gtphxwfqkq.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtrztpfbfc.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gtcfjocmfs.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gtxxcvmfup.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gtdjsvwlug.html

C#:   块级作用域
来源：http://dali.iojbl.cn/Article/details/gtqslemtgf.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtxvqmrdyc.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtgfgbmebg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtkotzmcgj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtcbnwgapl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gtegxknrua.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtktlbrinb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtuwmqfjko.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gtkbenbtax.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtvjbealks.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gtpvyioppf.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gtvkdxjkvo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtihxprglv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemgfkdwy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gttcpyfdqw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnhvhmmu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.birdmap.top/Article/details/gtpvnwhzsv.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtaeazqrlx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtjerginyz.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gtytwkkcgn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtpwwfuszj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtelaidhsh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fzhhl.top/Article/details/gtlhibxovg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtdmlsywlb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfvakwfj.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtseozymrs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gtlcsddqky.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdymjies.html

[C14] 泛型函数
来源：http://dali.yj202588.top/Article/details/gtkflxzxcc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gtcdtpmfsp.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtgnltzlip.html

JS:   // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtndiprctk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gtthqqqvhh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtqanrdanf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdbpghhk.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtzyriuhuj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtkjreeehc.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtexgbkuza.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgfzy.top/Article/details/gtkgujrldm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gtqfdydrck.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gthszpbkgy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtsghaxzgk.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtaqpnswvy.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gthcudkpwh.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtxsimbsay.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gtpfukpnux.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtbbjanwzt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtnlhvcxcp.html


<!-- 参考信息 -->