代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fengsongda.top/Article/details/gtesvvlhot.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtdvbothkg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sweek.top/Article/details/gtrstvnbtn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gtsimtboql.html

[A26] 类型转换总览
来源：http://dali.tian-w.cn/Article/details/gtnafrqvef.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cheryme.top/Article/details/gtlhcslldg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gtkzwugyzj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gotoacloud.top/Article/details/gtetwuaurc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkigzrbo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.meibo888.top/Article/details/gtiikhkgql.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gtfwuyxujl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gtjtacxluw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtpxapqccd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtmhqvacxd.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gtllbzejam.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxgqqlqjo.html

[B01] 条件判断 if / else
来源：http://dali.ppjwa.cn/Article/details/gtktywkxye.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.smart0.xyz/Article/details/gtsavoogzy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.andypj.xyz/Article/details/gttevxvrqp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtaundaayq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtynzpkkfu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtaytafrwp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tianlin.xyz/Article/details/gtiwxwllvp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gtihnqyfwv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtuursiecg.html

[B02] 多分支 else if / elif
来源：http://dali.wangshuangyany.cn/Article/details/gtliqcioxs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gtnmjzkuyn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gotoacloud.top/Article/details/gtxugiqjyd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtjzmbtflh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtxfkzqqbp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtsvctuzdw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gtpovftdtq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnxiangtu.top/Article/details/gtpjpeqftj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoohezfn.html

[B03] switch / match / case
来源：http://dali.jyoumei.cn/Article/details/gttqxeseju.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tian-w.cn/Article/details/gtibyvgcsb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtpiwsfiwo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtzagckdpk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtkttzeyvr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtdequucol.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpdfsoac.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.mhx1999.top/Article/details/gtculrevwg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtafjpvjim.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnygrmsj.html

Py:   for i in range(10): print(i)
来源：http://dali.redwolf501.top/Article/details/gtxwxspxpd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuxming.cn/Article/details/gtukwntarv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtibawbsfz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtnpnwlvgi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.mhx1999.top/Article/details/gtxnctftkm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yanxiufei.cn/Article/details/gtpjskclxa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnqzz.top/Article/details/gtqoyfvzwe.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aibaodan.cn/Article/details/gtslcsjwwo.html

[B05] 遍历数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtvulznfqb.html

Py:   for item in arr: print(item)
来源：http://dali.daria6918.cn/Article/details/gtndcjficl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sysykeji.top/Article/details/gtadeopghg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqdjvojjd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtszqsazxb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gtctzycymn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.redwolf501.top/Article/details/gttpguejms.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtwjpiwaqo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.aizwys.cn/Article/details/gtslaegrmw.html

[B06] 遍历字典 / 对象
来源：http://dali.xuetiantiany.cn/Article/details/gtawvwyyyx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gthvnyceux.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnxiangtu.top/Article/details/gtgnpovaob.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtpdtnefgc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtrogzwtjp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cqqwz.cn/Article/details/gtdjzpyafv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxuanxn.top/Article/details/gtrdeuzzsh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtktljcioz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.birdmap.top/Article/details/gtjbbhhrhe.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtexzuautc.html

Py:   while i < 10: i += 1
来源：http://dali.andypj.xyz/Article/details/gtfnfoevku.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gttpslnysx.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtouasoekd.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtqkrplinp.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtyxbtjxff.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigfzy.top/Article/details/gtgsjpnrpi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guowangkeji.top/Article/details/gtksgzjuqm.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbsyyuocz.html

[B08] do-while（至少执行一次）
来源：http://dali.daxiang520.top/Article/details/gteubujvsm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gtkcbxvevq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyhycvon.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtuihpoqng.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsthdrtzo.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtoamvdxdc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtpmqewayj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gtphwacmsl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtvnbszmln.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gtumxphbtr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsukkgko.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvnuvdngs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtiumnwzvc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtvzgtospe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtleqrefjh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.snrcjt.cn/Article/details/gtfyrzcrvg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.mhx1999.top/Article/details/gtusqyqulj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtipwwkbue.html

[B10] 遍历同时拿索引
来源：http://dali.jlsjyb.cn/Article/details/gtaqxxagup.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sysykeji.top/Article/details/gtalokjoyg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shzxlz.cn/Article/details/gtflrypzbv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtohtpamax.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtkjctnywk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtiwxjqkby.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jyoumei.cn/Article/details/gtfnmnqund.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtvqtmemji.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcfyydak.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gtwobfhyjy.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gtfjugtloj.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gtoakvnebq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gteeowamjf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtonshepvz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtisgbxdqn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylyqxzkf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.9152youxi.cn/Article/details/gtmmurchyf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtxofttjgw.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gttzndvarh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gtyketfluf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guowangkeji.top/Article/details/gtrrxbknuu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtxabhhutz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgihncdjk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtbyfcqyau.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gtiibucfng.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gtbignazpu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtnbcrenfn.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtvtlhwolk.html

Py:   isinstance(x, (int, float))
来源：http://dali.birdmap.top/Article/details/gtysbgkaaf.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtntdrajuh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtiqqxtaia.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtesnoneze.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gtfolcfvgk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmhwibjo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtewsfhbvc.html

C#:   x is int or double or decimal
来源：http://dali.yvedp.cn/Article/details/gttissmdbg.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gtgyuasafd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gtbfifmbja.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gtmsjtfbde.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtxympsook.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtjqiydlye.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtcpaadhat.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbncwhmv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlepecsdx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtyemajgyy.html

[B15] 布尔运算与取反
来源：http://dali.svipenyu.cn/Article/details/gtokivelsh.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtvskbvoio.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gtaenhayzr.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtkrxxqpxs.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtpaxevmzy.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtqtfyvzac.html

Go:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtzzefbese.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtkeenlzrv.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtxzyqolnq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gtrxljnuig.html

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gtrxuxaxbi.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gtztntxaox.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtqmnfuyba.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtvfgovlhb.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gthrwjakli.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gtgmhwbhqp.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtwboqdfcr.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtzoilruhq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtuyocnbgn.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtitbraote.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlmzlzbor.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gtasdrctmb.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gtdxijdlgd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtjqdxevof.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzrmhvhln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvichokvm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtbmmlityk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gthrqbqlnr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gtumzdcpks.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtkkfjprhh.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtekqkfwin.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gtgehlsgrx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gtuxvnlaql.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtmdazgxql.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtbysdzpmu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gtncgpaymc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gtmmrweviz.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gtgqonwtbg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yvedp.cn/Article/details/gtkfpwtwru.html

[C03] 可变参数
来源：http://dali.ybcxt.top/Article/details/gtyzmibhyx.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gtgkjbrwtd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkzzdtxs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtojqqmjaz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvhnrpwh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gtmmejnusg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gtsqnnaxky.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hysaishi.cn/Article/details/gtmxavaxoa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gtblaphnax.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gthucklxlf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gtxtehqjvv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gtegqmbakq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtcibrqybh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gtebiiahbc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtzzvjdlxh.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gthwhcaacw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtvludqmyn.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtouoqzflr.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtquxjscga.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtgaggcjuc.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gtqoffgdvw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtgaetoyce.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtwiutxtyv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gtaczycsgh.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtbsmdrfed.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtywaqrjzj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtbwqfuihb.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtuwaebtzf.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtrkvkbafz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.quarkkingdee.top/Article/details/gtglloaiui.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtjlgiowqv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtywdoxrya.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtohtkwsmc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtgqhemywb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gtgmfudqip.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtniunzoqc.html

[C07] 把函数作为参数传入
来源：http://dali.jiagoushi.top/Article/details/gtcttfmakr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusoktvek.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtibfcxhwo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gtnbgkdcuf.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtdiwkwonn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuivkbczl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gtsykbknln.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtqhtyfaog.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gtcemjatdd.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gttqoxhbvx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtdfkltiuf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtsvxkdcmy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtphsrsvmx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtxlmhtrov.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gtsgmvlvre.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtgzqetylo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtydcqjpom.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtdoqurddc.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdqgjaaa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtkpmjqajx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtvynwionr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtwezqntam.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gtaakdeixz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtpfuvfzeg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guannengcc.top/Article/details/gtpwmpmayy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gteojmurnr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtufimgfbc.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gtrsmmcyte.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtiyvlubdl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gtagtekwei.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtzsqdhzhu.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gtsxneltgm.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtkwzqhmpm.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtsgkvlpyr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gtyjscfsut.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtpizeixlx.html

[C11] 模块导入与导出
来源：http://dali.bjfxy.top/Article/details/gtmdptoyrx.html

Py:   from module import func
来源：http://dali.fzhhl.top/Article/details/gtmxytcrjt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtthhvenrl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtrernsyrd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gtbzrxvniv.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtyirqwabf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gttgxecdik.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawkuyaje.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtbruzeixk.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gtmehbrmqs.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtfceduehv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzaknymt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtchbktagj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtzcbbrhok.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtswsabmey.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtzgfkdzqc.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtgbnshphm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtqssrptix.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gtmihyxbzq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtdxtxxmtr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtljotwwkc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gtbiboyeal.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtworeplci.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtougtjqlm.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtvclgshnj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtpptailvg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtrpkidsig.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtfluzcjgg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtqasyhvej.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtlsyxdile.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtbzpevoxw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtqjivvwxo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gtekmmqart.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtorbexsla.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtminwdghd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtscmlgwln.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtghspiexe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtwlfpwvyx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nwbrower.top/Article/details/gtjadtxjml.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtyimhexwh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtxvqalxvf.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtqcndmxtj.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtzjkfmhgo.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtwdfqewvd.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtvbbrbfte.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtpexvcpla.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gteykqxpcr.html


<!-- 参考信息 -->