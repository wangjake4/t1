代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenlongwang.top/Article/details/gtqgsltjbo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgufenzy.top/Article/details/gtclqjzgqi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangshuangyany.cn/Article/details/gtkntxftjf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtzlzsafhr.html

[A26] 类型转换总览
来源：http://dali.yvedp.cn/Article/details/gtubzfilur.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gtlwhqnlxo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.svipenyu.cn/Article/details/gtupamdsbh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gzhubu.top/Article/details/gttaprckfj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.haohaochexian.top/Article/details/gtxkxmkmlh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gtodgpgxho.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yongpay.top/Article/details/gttfyqxdqh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guowangkeji.top/Article/details/gttshtyrll.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gttxdvvpem.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlcditqjc.html

B. 流程控制
来源：http://dali.yj202588.top/Article/details/gtkbqrvfob.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtcbyekiwq.html

[B01] 条件判断 if / else
来源：http://dali.gogol.net.cn/Article/details/gtmtkwzzfw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daria6918.cn/Article/details/gttkblbfja.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dashuyun.cn/Article/details/gtomoedwma.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtwyzzogcr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtjkjucesr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtqhcenlyd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgufenzy.top/Article/details/gtdipjxwon.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.bjfxy.top/Article/details/gtweawsbmy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtkwawwmjl.html

[B02] 多分支 else if / elif
来源：http://dali.cashguo.top/Article/details/gtfooexoth.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sufxvd.cn/Article/details/gtuvvzcmbx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daria6918.cn/Article/details/gtzjkatjdu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtqkihmggg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtmbxapjcb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtucummveq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yanxiufei.cn/Article/details/gtknznvuyw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yanxiufei.cn/Article/details/gtuzgyekui.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtxnvadlgv.html

[B03] switch / match / case
来源：http://dali.zycfv.cn/Article/details/gtfqzayurh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gtdzdaoswm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtygwtlpfo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtayujldsn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtvypcntge.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtfqowwkui.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtcktjzqut.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jianghu66.top/Article/details/gtjgjwsvwt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtbbglcimn.html

[B04] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtveywtsqk.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gtirtqpscc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jiagoushi.top/Article/details/gtwzxjtskq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gtkgldgiuu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtpmwehulq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtnrorzunb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daxiang520.top/Article/details/gtalexvuyw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daxiang520.top/Article/details/gtfsvhducl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtxjiynbfi.html

[B05] 遍历数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtmbdbqwjt.html

Py:   for item in arr: print(item)
来源：http://dali.pycfn.com/Article/details/gtewtctood.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gaohongyu789.top/Article/details/gtthuvzann.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcxtegsx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gtbyhynzjh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zdqjudy.top/Article/details/gtvvfydpzw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gtbdqhonbm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hywenlv.cn/Article/details/gtvnetpnxk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gtwbmtvscs.html

[B06] 遍历字典 / 对象
来源：http://dali.hywenlv.cn/Article/details/gtevmxuxlv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gtcjurkdpk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gthevtujvr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtrgxzaxzy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gtmwhhjaio.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yongpay.top/Article/details/gtmcouliew.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shzxlz.cn/Article/details/gtzzpierov.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gtgljcmazy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhixingplan.top/Article/details/gteflkzpno.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gtvouvfjgv.html

Py:   while i < 10: i += 1
来源：http://dali.yangfankeji.com/Article/details/gtzvsyvajl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sxryk.cn/Article/details/gtgjiogxeb.html

JS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtqjsdmhxq.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtrjglyszy.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsgipvso.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuanzhike.top/Article/details/gtujimvzki.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhoulong.xyz/Article/details/gtqcuzaijg.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtafqoefno.html

[B08] do-while（至少执行一次）
来源：http://dali.zhengqikj.top/Article/details/gtebdwdbnd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtgqkkkfwk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtflmyilqe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtvpwzqzhe.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtvlfaebqi.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtzwqhkeqg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gtopvyjanq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gtftabbixe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtjkxtkqkf.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gtnhhcvdep.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtqydbghjo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdpigkgoc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtzagqwumo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtcwifdakt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtxcxvejyc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnqzz.top/Article/details/gthiveuzjm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gtczlkocco.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gttjremkil.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtmcgaryiz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gthwwovuvs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gtarffkbqd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtptnhuybl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtzxrlmakf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gtqsaedvic.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gtwguqarxt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gtwidzucle.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gtjhbexusb.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gtqgrgkpki.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gtkgveysot.html

PHP:  range(0, 10, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdkbvqnz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gtxomnaohb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtupxwfaui.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnbbdorfe.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtdainebkh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gtwbsuxspz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtexsukqmm.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gtnsppfqal.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gtxpneeqaa.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxinkj.top/Article/details/gtbeqepnkj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtoqnfghgb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtyuzffdud.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtxwiivsmv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gttvmfxxfk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtptgwuziw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtgvyvpkbt.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtpluabovs.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtyumdjkob.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtxwsiqrnb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtzqdelrqy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtpqvbvhvt.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtomwjublt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daria6918.cn/Article/details/gtwortfvis.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtizreoxwd.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gtqvfuaaen.html

[B14] 判断值是否在集合内
来源：http://dali.gzhubu.top/Article/details/gtgpxnuufd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gtkskswtfh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ehwqpu.com/Article/details/gtejwywttk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtcipkshzc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtrqvmqdcj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtuhwwkgox.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gtpsgnvtmj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gtsgqlfwef.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.andypj.xyz/Article/details/gtrevjrbgq.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtekkppohy.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtolmhvsws.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtlltxvnjh.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtmyhxzldd.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgisqrip.html

Java: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtyllhtikk.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtvpxcfgyb.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtduljkrkg.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtigkrteru.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gtaqhjshsm.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtraexdfdq.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtekfkdezp.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtavdjolcm.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtjhdsrqhp.html

Java: if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtpaldfynr.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtbfupdjmd.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gtspfiknhp.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtjdgpzmhj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlsqkqzbv.html

C. 函数与作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtkuuqwmao.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtktbieqto.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtkxalgcye.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtlraugptz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtyteolqrq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtqppgdtwd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtyjghhxlm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtwyvenast.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj202588.top/Article/details/gthvoumhys.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gtauvffzpw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtpezxrfny.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtkxsnykuc.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtajwaqcku.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhutwjnz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtkrxnjbrl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfxdpfjey.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gtfpllwpwu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gteqhnljvb.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gtgmthlopx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtncbfqvxg.html

[C03] 可变参数
来源：http://dali.ybcxt.top/Article/details/gtorpeokrz.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtkrmhnlsf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gtrxaaiozs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfxbsoase.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtrpselkzg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gtzwelnvrm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gtozdcpkil.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gtthpkbldu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtszlgblqr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gttalemwif.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gtchlnotvg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gttwwucbts.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtlwdnowfq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gtvlqbtubz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gtdtgutjhu.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvkwyhhs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtiyvafrio.html

C#:   f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtobesgvmi.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gtynwwerbw.html

Py:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtsrattqko.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtvbitafxu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtsbmddshs.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtwymyoclc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtzmasqdmq.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtlfqytbzs.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gtypoxbddr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gtwmvtzdcs.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtdlmwhdtq.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gttkjddjbu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtfeizsquf.html

JS:   const square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtljbebjek.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtzyssukvv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gteueqgdxy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtqpruypxf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gttjmzxlfg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtlnqcxqzd.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtlcbymfnp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtjbriwuxr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yonumen.top/Article/details/gtfmcnggyw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gtvagyzcmd.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtjddemszx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gtpcgdvuet.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtbnfljanf.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtgwfldaua.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgufenzy.top/Article/details/gtiutcmsys.html

[C08] 闭包
来源：http://dali.tanke756.top/Article/details/gtljefhjve.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtqkrturue.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbxhzmffc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtgjdsfrgv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtommxbely.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.smart0.xyz/Article/details/gtzehixhzv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgfzy.top/Article/details/gtfijjsxrc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtfdcswfav.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtsokfhxwv.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtnpefahpd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gthinooawa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtoqemfxhj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtcjercpjz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtdjojpooy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtvtfmzdae.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gtdhuwhnye.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtbrbzhhba.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gtrqcrlvcy.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gtgruxdxrx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gtulfmzmdo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtbetifyzr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtdganjyki.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gttmgwselg.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtvpouoxrv.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gtdghrnjjl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yongpay.top/Article/details/gtoiujdkyg.html

C#:   块级作用域
来源：http://dali.tian-w.cn/Article/details/gtvyszwoca.html

[C11] 模块导入与导出
来源：http://dali.cucudq.cn/Article/details/gtxfzhlera.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtexlgjwiw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gtoahzqetq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtxqkybeaf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gtfouuuvyj.html

Java: import java.util.List;
来源：http://dali.nanxuanxn.top/Article/details/gtrdtmvrxs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gtrczixfql.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtvjaavcup.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gtlczetmgy.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtuqabjgow.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtsdiuoter.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtliyqjuqs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtvpaajhhg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gttwmrdcts.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtvnsoaisi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtjrlqlomr.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gtxweeuxaz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtyfxdjuhq.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gtluqkxdyc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gtjxlmwoiy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtvjgmqnku.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtyhewbzaa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtiavfjwnn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtgltzjhrs.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtlnesevcd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtuffmlfwb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gthsdmxfnl.html

[C14] 泛型函数
来源：http://dali.fengsongda.top/Article/details/gtlfplebri.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtvnzfmrfm.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gttdbvuzlm.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtqgnjxoqn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gtpthwsqji.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gtofswykqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gtbnxexzol.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtdpwvfjro.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhengqikj.top/Article/details/gtrtjsaegt.html

[C15] 解构 / 展开参数
来源：http://dali.yangfankeji.com/Article/details/gtdetihgis.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtlbcqgkjr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtqbqruzgb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtndcgredp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzpttiulq.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtxubhvjfc.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtpwdmuwjx.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtptmqbsvm.html

C#:   var (a, b) = pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraoowznp.html

[C16] 函数 / 方法重载
来源：http://dali.guannengcc.top/Article/details/gtnjfbnedi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtddxisnpk.html


<!-- 参考信息 -->