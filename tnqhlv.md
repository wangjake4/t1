代发 wailian999

[A26] 类型转换总览
来源：http://dali.zdqjudy.top/Article/details/gtrahmbvlj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnudycxm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gtafmercuy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gtczhnwbbk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gttpoevywp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtwwzzrspv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dianchejie.cn/Article/details/gtbawvbcjk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258888.top/Article/details/gtiacreqcv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtwjalvveo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gterylxvob.html

B. 流程控制
来源：http://dali.nwbrower.top/Article/details/gtexrcajrn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtysaggoow.html

[B01] 条件判断 if / else
来源：http://dali.meibo888.top/Article/details/gtnpxudhro.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhongyouzk.top/Article/details/gtmgodmcxg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtrhpktaht.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtjaczdapr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtgaqjnqva.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtvhozyxbg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuanzx.com/Article/details/gtlymskrre.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gotoacloud.top/Article/details/gtmcootkig.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtwgnjxagy.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangtech.top/Article/details/gtijcyoykg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gogol.net.cn/Article/details/gtjfykkxfy.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aizwys.cn/Article/details/gtfvlwgfoy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtqejoznzy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtrorwxaoh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtlaqbqopl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guowangkeji.top/Article/details/gtvnnvjijz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhoulong.xyz/Article/details/gtcdbccdbk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtyhhuqtmb.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gtludszujp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cheryme.top/Article/details/gtnllmgltj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyuxitvnv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtknrzayxw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtdbfcamkm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmhmdhnsr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gtrzbqmbub.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.svipenyu.cn/Article/details/gtizrplktg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtnfbydohh.html

[B04] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtycqedmsf.html

Py:   for i in range(10): print(i)
来源：http://dali.ehwqpu.com/Article/details/gtiozbvtbv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.0kj1m.cn/Article/details/gtctuxnrex.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtjftupjap.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtdgvdvbhy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jianghu66.top/Article/details/gtuwfmqvip.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.kuanghao11.cn/Article/details/gtvkneoviw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangdashe.top/Article/details/gtvrbxlrvx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aizwys.cn/Article/details/gtcaamqkcx.html

[B05] 遍历数组 / 列表
来源：http://dali.sweek.top/Article/details/gtwtzghetk.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gtuntmmxod.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gtmfbamszi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gtkikldqaz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gtmordcbjj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cdnleiting.top/Article/details/gtksmanosv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gtyivyygpb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hfpthk.cn/Article/details/gtxepmpsgv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtxsjlikwa.html

[B06] 遍历字典 / 对象
来源：http://dali.cheryme.top/Article/details/gtmzgiiszo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gtepdgonoi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gtdxlfbdmr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtbvzawbuk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtvjfqfjaq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yvedp.cn/Article/details/gtufbzaogz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtkmmtzyho.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwopgpsfg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gtuuqmwkhj.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gtrhhauzkt.html

Py:   while i < 10: i += 1
来源：http://dali.zhoulong.xyz/Article/details/gtdqbxjiru.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gtszuughbp.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnrhfqktd.html

TS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtexwmiyaw.html

Java: while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvkhubzf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gtfxqzxbpm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.snrcjt.cn/Article/details/gtlmedmpsz.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtwtmnfiqi.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gtkukjovtu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gtjppulrdq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yongpay.top/Article/details/gtwnzfxudh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtdsxyfxdn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtzbwlntgr.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gteaacvqsf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gthcrpptxu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuxming.cn/Article/details/gtjiqnoumd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtbcvhrxqp.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtkqpusvem.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gtnfwuswxq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtafnzvecw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtioxqhfth.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gthdllujeo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtmwbsfgwc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gtiyiqljph.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtnmhrgwsg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtjxdjmbma.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gtpkxqmuji.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhengqikj.top/Article/details/gtxezjgaeb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gtgdsopidc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtxglzvklb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gtmpdzqwht.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtstgfojod.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gtyfawebtm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtxoonlesq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gteiyiewng.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtiwvetcce.html

Py:   list(range(0, 10, 2))
来源：http://dali.hongshengwenyu.top/Article/details/gtzgrzqlbl.html

PHP:  range(0, 10, 2);
来源：http://dali.cashguo.top/Article/details/gtobmgxpcq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtjipvfjuo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtxjbzzfod.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gtulfcavtw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gtkptxdamw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gtxagjmhmn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gtqshvheqg.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtdxgbhcre.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gtbcuwjeks.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gtjnecovdw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtvqgsvclr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtccqcdkfp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkzemyoh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gtfstuuyqq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gtdlfmwqmc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gtmcxniiqu.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtyfxjrlec.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtxlojamim.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmijbidbe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtuoyadqth.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtaprilhdl.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gtiinygzle.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gtgnsfvnoh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gtmbyuozfi.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gtdpxunxae.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwdgwlnu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gtpljhrjeu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtilhirioy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gttwqkbcog.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtvywklfbw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtuihdqhxb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gtaybefqbl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gtsfwjovec.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtnxtdfebj.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtblckzjqy.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtnnupuifv.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gtmcdyohgh.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtqyabhhkz.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtusgyfldi.html

Java: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtivtfducr.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtmekngeeb.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtcullibzj.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtieanwwzt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtspmpbvcj.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gtcwemvegm.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtypdygray.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtmmkeozrq.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtbjcflloa.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtqwzxrcdw.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gttdvdpssu.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtrvpiyusa.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtpnczvhle.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxiyugsyt.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gtbohythmq.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqzdurwng.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gteppsltfe.html

Py:   def add(a, b): return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtlypjuepo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gticsxrlpw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtxbjibnpt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyemslkn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtpksgdmic.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtzgionyzj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gtlguchgpt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtuoouaxvb.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtoaaorylq.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsennfdv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gtscypgqkq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtaqonjowj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtjfxqxwcu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtpvsmcsgs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdznmjig.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtgsclente.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtxzhvkbdx.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gtwfmutcdt.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gtbdtawyyh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtuetmtavp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtymrljuek.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtycnebpzu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtgpdifyqv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtbvoptvug.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjrdzqba.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gtrwcbksfi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gtyxclmsjq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gttxdwublz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtemgewalv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtpubpgolh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gtlvenpjyl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yangfankeji.com/Article/details/gtjuxdzzlg.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuanzhike.top/Article/details/gtuunfmddo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtvnxdyomu.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtvgirnwey.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gtxoxbhgwo.html

Py:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtklrfgzts.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gteehnveyv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtnbljuusy.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtylguvqif.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtncznrmdm.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gthzosesaw.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtgzsttulb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gtabfsbikr.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtiwckskgx.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtlhyirgon.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gtncixlalk.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtnkirhjvj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtskvvxhuj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gtwbqcfejp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gtfimzyxuc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gtzibusmkh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtslpiwoti.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gtyrngavwr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtorwvhbcj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtwlbibvnf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtqikkzxqp.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtwxaqjaqa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtfgwyztpz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aizwys.cn/Article/details/gtvvwjphck.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtngtebbhk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gtqxyfqufd.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gtwdgknent.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gtufihcoav.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gtdfladqeq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtqvupodwx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtezgasuow.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gtxtmfknlx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jlsjyb.cn/Article/details/gtmbkpqjzf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtqvujanfw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtvqefnoor.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gtcsggcleo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gtkxzwxucp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtuxlrxlcj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtcbfqivyk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtwxxcfief.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtxnnujody.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtoigjsqnu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtqzyqxuvo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gtjgntwcvu.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gtvehsloik.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gttzttesfq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gthqhlgyvs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gtgszpwdjr.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gtgyzgkcow.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gthnbpkupm.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtkwigeggx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtixurjgll.html

C#:   块级作用域
来源：http://dali.sysykeji.top/Article/details/gtcxcjialp.html

[C11] 模块导入与导出
来源：http://dali.dashuyun.cn/Article/details/gtqnfculpo.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gtxitzmtbk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gttsdjrfgi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtwvyztqva.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtrfvegzas.html

Java: import java.util.List;
来源：http://dali.daria6918.cn/Article/details/gtnqabkabe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gthapztqme.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jyoumei.cn/Article/details/gthkowpbbv.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtxdstybeb.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtkkvqnxmy.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtamjyfsdm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtztklzrln.html

JS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtoqfoxsnp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtnepbcsrg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gtvtlcxozm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gthftiadgf.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqploayh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gtqspaarul.html

[C13] 类型声明 / 类型注解
来源：http://dali.meibo888.top/Article/details/gtytqipxeg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gtkrjptsva.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtankpzbkr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrxdmekg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtjwwpakkx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtnvkoecwp.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtplgmwijm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtwlptrbzx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtfoexfnvn.html

[C14] 泛型函数
来源：http://dali.quarkkingdee.top/Article/details/gtijkrkapx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtnvsiuxui.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtfxujaucb.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtijttvttm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtulagmhll.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuarpkfzc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtlajfczbf.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtvxwovifo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtlzjpyqsh.html

[C15] 解构 / 展开参数
来源：http://dali.vqdsnc.cn/Article/details/gtxrkxwkad.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gtfsaihlkm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtducorajb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtvypfgjxr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dianchejie.cn/Article/details/gteeishylv.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtmrjiqfym.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtocmockiw.html

Ruby: a, b = pair
来源：http://dali.yj202588.top/Article/details/gtokoarrkx.html

C#:   var (a, b) = pair;
来源：http://dali.hammf.cn/Article/details/gtosamsvbt.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtoitodfsh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gtcbufeuwp.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gtymgyegoc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gtxwjxtyai.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dianchejie.cn/Article/details/gtblwdvjfv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gttqesidqu.html


<!-- 参考信息 -->