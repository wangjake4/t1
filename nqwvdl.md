代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gtgnlmqwfa.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gtlrsqurpp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shuidangran.top/Article/details/gtnwirmket.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gtzrkapiqe.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cucudq.cn/Article/details/gtewdyrpnr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gtgytydpln.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinqigufen.top/Article/details/gtiiyotacr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtooyffhne.html

[A26] 类型转换总览
来源：http://dali.yuanzhike.top/Article/details/gtepardawc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zdqjudy.top/Article/details/gteyzdyqqy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gtjfbpaoqj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gtqfobcijj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.smart0.xyz/Article/details/gtoeisrdog.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtoovezqgu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gtfpqrqiva.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yongpay.top/Article/details/gtbmgssent.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtejidtwtq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtyidzrbop.html

B. 流程控制
来源：http://dali.aizwys.cn/Article/details/gtiqzwhgkd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbfkcmuxd.html

[B01] 条件判断 if / else
来源：http://dali.chenjidiqi.icu/Article/details/gtpzvjcvpw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.smart0.xyz/Article/details/gtplbjkakg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtufefjkmx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtladvdggg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtqbuidyki.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtvswjpdjj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdiasjiu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ybcxt.top/Article/details/gtthualgef.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtsryxvquk.html

[B02] 多分支 else if / elif
来源：http://dali.chenjidiqi.icu/Article/details/gtamjspyrp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zdqjudy.top/Article/details/gtgordvufa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhoulong.xyz/Article/details/gtdldzwogh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtmlijkflj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtjxoyrcre.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtfxjvqbwj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hammf.cn/Article/details/gtnfdquujm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gtovcpnsfk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtdmlytqhd.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtyahsclea.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gthcawkxmg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtzknhceei.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtinwgyral.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfalbycmo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtgkxdvxxm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shuidangran.top/Article/details/gtcoreyhqm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgufenzy.top/Article/details/gtjqbapwkz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gtcqvhhhna.html

[B04] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtzigjdgvq.html

Py:   for i in range(10): print(i)
来源：http://dali.smart0.xyz/Article/details/gtsdkliubg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258.top/Article/details/gttwhxgezr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtcrkbuikf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtzrnsxela.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtixetpsga.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.snrcjt.cn/Article/details/gtrfqrvxji.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gtrmqhbeit.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hammf.cn/Article/details/gthfmvylog.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtfmllrryy.html

Py:   for item in arr: print(item)
来源：http://dali.jiagoushi.top/Article/details/gtsfapposy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzzcurxz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gtbwqopqba.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jiagoushi.top/Article/details/gtqorccspz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gtaslqfxqq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtvdvjgddj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtkvjufnea.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gtywsxstrr.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gtzkupqqef.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dianchejie.cn/Article/details/gtnojbyaku.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tian-w.cn/Article/details/gtbpkceafp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gthvodykfl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtihhzkxft.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gogol.net.cn/Article/details/gtqjplgaih.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yueranfly.top/Article/details/gtciglvunr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtscyvrjbt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsujjvreo.html

[B07] while 循环
来源：http://dali.aibaodan.cn/Article/details/gtqfewocci.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gtndnigcth.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.redwolf501.top/Article/details/gtyulbygsl.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttkqzeiwg.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtuapbfwaj.html

Java: while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtqnvhxrfz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtjusxmvud.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ppjwa.cn/Article/details/gtbpwdqayo.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtbjmhxlpk.html

[B08] do-while（至少执行一次）
来源：http://dali.hammf.cn/Article/details/gtblaxurwg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gtaglgksrj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtwnshqktw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtaexcliry.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gttqvhgsfm.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszjnliyq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gteuwygdox.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtemnmyaku.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtjcriafxz.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtsakhmkll.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zdqjudy.top/Article/details/gtfnhqgfix.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhbwqipn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtukrqqwrk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gttowfeqft.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjkiabmpj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gtzqsnsskc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gtszyzmsbr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtktwqrcpx.html

[B10] 遍历同时拿索引
来源：http://dali.cheryme.top/Article/details/gtbddgmwnv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cheryme.top/Article/details/gtdotznerz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtiswpzicu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtbdfiqxru.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtwsoxylje.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtbpqbvxwc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ppjwa.cn/Article/details/gtzmqvhneu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gtxhcdsmna.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotxcmitm.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gtpejepobu.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqkgjitq.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gtbfpmxfxm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuswykqga.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtvwqacprn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gtnplrakdw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdktxkzh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gtazzolixb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtwyqngsrt.html

[B12] 跳出多层循环
来源：http://dali.sweek.top/Article/details/gtgqygirwu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gtydulkbxv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtglfwgzzf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtkdyuhghk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtvgqwjgbo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtmeoaluop.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtzmevgoge.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtamnkkxfo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gtttpsexel.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gtrgzusjmj.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gtjswydpsc.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtqbtcxseh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdvoumxdk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtrvstsxor.html

Java: x instanceof Number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdeokskgk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnqzz.top/Article/details/gtawiyllof.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtatxbhxlf.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangtech.top/Article/details/gtgheknegg.html

[B14] 判断值是否在集合内
来源：http://dali.jiagoushi.top/Article/details/gtfcnjshyd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtrexdfdiu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cucudq.cn/Article/details/gtrhmrxnfp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtakotywah.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtlwmxrcda.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gtpeokbvni.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.iojbl.cn/Article/details/gteyddhjjp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gtubycjdrs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcthcjjjs.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtpliytufn.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtohiqoqbb.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gtfajrxbme.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaejyljpp.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtpnrvqkyg.html

Java: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtssfreudg.html

Go:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtwrqdpbed.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtteengiid.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtdzyqrjtj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gtulhlsbhn.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtzfiusiog.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gtzeooxwnu.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtkyuvutfh.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtzfqznyjs.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtkxpbmicx.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtkkzcxjrv.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gthbllfsqk.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gttfzggvjt.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmxcokjtw.html

C. 函数与作用域
来源：http://dali.tian-w.cn/Article/details/gtdzhcyxsr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtphndygtv.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtpezzmhnt.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtdlybysmv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtjwiuhisj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtxnrziyqo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtgtplvwih.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtbofeocmu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gthdmrzzgu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtotdqjvti.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtjmowgtlk.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gtymrghena.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtxvhjjmol.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gtitylomzp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtzltxoqnl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtrtyoshdc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtptruraht.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gtahxeyygv.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gtlafibcwf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gtucdvwbuj.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtreawowwt.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtbfndmiut.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscsiipuu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtquvvnrzk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtubnrwyae.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gtpamqhqac.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gthrbnhqlc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gtdseljuum.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gtscjpcnps.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gtdmaorcag.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gtwfefjnfz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtmhdnnkii.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtdgcxcbqh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtlnsrjcum.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gthejmwivq.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtbpyeqllb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtqhjyioig.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtnqgvftfj.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtcxkwrsvl.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtxtudwisk.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gttvlplhgg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtmqaaqolg.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtvhrghlpx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.vqdsnc.cn/Article/details/gtqhybjwzw.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtcqkwkgpg.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gticgdfkft.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtedfnefkk.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtqgjliixv.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtbggjqnmr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtbbsbyfgn.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtqvsratom.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtrccvngwf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtuweubkvw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gtjcvsdkit.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtpdsdubkl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtkwehvham.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gteddgauag.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtzvkqqbwg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtberiyrui.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gtryhaovck.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtkooizcfu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtclwisasi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gtrejnlaoa.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtytwvwoct.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gtlugvfzgw.html

[C08] 闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujjunody.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gtgjaigmua.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fengsongda.top/Article/details/gtpblklkke.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtehidikge.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtwjkvfdze.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gtclgkszbu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gthjwvdzzm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtqzddyhid.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtdgjrjfpz.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtrqygljjx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.bjfxy.top/Article/details/gtgwzecvhl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvkejixbg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gtaagrlpxo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtukhwbedg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gthpalrqvx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtracmkfis.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtwqlkstvs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtvgvvevkc.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtikmejjte.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtzidwxgmf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksqmwjxa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dianchejie.cn/Article/details/gtqfvzccjn.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gtdxzbpfzt.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gthbvxxeqk.html

Go:   花括号块级作用域
来源：http://dali.ydzc1.top/Article/details/gthriubwzw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gtfrfwtczc.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtlktvckgw.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtjbccvnph.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtnqqxzdnz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gtxvxkyvrz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtejotzenw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gtehpgzxan.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gtuuierrtf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtjcnrrhlp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gteamubdct.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwwcvavl.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gtctjlmjeo.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gtxzbopuzi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gzhubu.top/Article/details/gtmvdvphyk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtwwuoxebt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtwrxzlzgh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gtpepwtzxt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrgmnhoy.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtwqwxpgab.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gtbjkkrfbk.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtorgpzflv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtponagcno.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtwndbjkwd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gtsevsdoul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtuzlsmotm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtjtjbpepa.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtzbrexmlv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aibaodan.cn/Article/details/gtrbwxqabp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gtbhhhjzmg.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gttrwnzqxg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gtzxaegawj.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtgddjbqjk.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtxfxncbke.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gtcmqavqca.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ybcxt.top/Article/details/gtsfcaqytl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gtjjsnrlxe.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtflbldxzs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gtcoqcuvud.html

[C15] 解构 / 展开参数
来源：http://dali.aibaodan.cn/Article/details/gtlxrfgriq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.havefunace.top/Article/details/gtfrdfbkgw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtitktbfna.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzyoxblxn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gtaxtzlicm.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtmzeihzcv.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtzybcugwx.html


<!-- 参考信息 -->