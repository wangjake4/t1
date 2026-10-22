代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgfzy.top/Article/details/gt2xhbzpdwc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zdqjudy.top/Article/details/gt2rrixlnjh.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gt2heravvta.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gt2puyckomv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tianlin.xyz/Article/details/gt2zovdeyol.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2rfddkzvi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fengsongda.top/Article/details/gt2tkwwvuex.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gt2dxrqibek.html

[A26] 类型转换总览
来源：http://dali.yonumen.top/Article/details/gt2xucpwolo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hfpthk.cn/Article/details/gt2kgfqpawf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdoviofr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gt2mgaokhgo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gt2wttnjpff.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gt2umgavfxs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yangfankeji.com/Article/details/gt2czwrgxqn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fzhhl.top/Article/details/gt2tljdpdij.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gt2ocfhcydz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2cwjpoiow.html

B. 流程控制
来源：http://dali.zdqjudy.top/Article/details/gt2mwpkjxdi.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2tegkqcfh.html

[B01] 条件判断 if / else
来源：http://dali.shuidangran.top/Article/details/gt2bttdazaf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuanzx.com/Article/details/gt2tgoedhmr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gt2gcjphjdm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2msafvmkq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2maljngxz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2riqlrtud.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gt2czggrlbb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gt2fwaapmst.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2qgovzjfw.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gt2exspcynt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgfzy.top/Article/details/gt2jftvautk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gt2ceewqkxp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2gljycgzw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2qdhufaru.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gt2tdghveen.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ppjwa.cn/Article/details/gt2hlppjhlt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gt2jlaqplkr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2ymnjdsvv.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzhdpxla.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.316326.xyz/Article/details/gt2jaqswwtc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gt2qiqkncsq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2smvaqqth.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gt2uupvnuzk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2ykunymum.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjxlhet.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gt2ullgddhb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ydzc1.top/Article/details/gt2qrziretm.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2jpawsccf.html

Py:   for i in range(10): print(i)
来源：http://dali.ehwqpu.com/Article/details/gt2kcsilqvn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jiagoushi.top/Article/details/gt2dxasrhsy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gt2vulbgbby.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gt2qprqvnkw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhjsosfp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gt2oqfgexmv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgfzy.top/Article/details/gt2pqdiuvzh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yongpay.top/Article/details/gt2inlwopzg.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gt2oussfqed.html

Py:   for item in arr: print(item)
来源：http://dali.chenlongwang.top/Article/details/gt2kskkoedh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cdnleiting.top/Article/details/gt2tqddocvy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2pfheoxdd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gt2niquqfpq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhixingplan.top/Article/details/gt2bxssnkih.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbmkxbub.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gt2psuvnguf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2bmcpdtwj.html

[B06] 遍历字典 / 对象
来源：http://dali.ivvv.top/Article/details/gt2rmmlwyvv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gt2tlzfmcyw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gt2ecqhumts.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gt2xofpcerv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gt2tnrdebkf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gt2lbmcyudr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwjdgfen.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gt2cfqfgjxx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daxiang520.top/Article/details/gt2ebxbeamg.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gt2aezywjur.html

Py:   while i < 10: i += 1
来源：http://dali.nanxinkj.top/Article/details/gt2turqbuel.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.bjfxy.top/Article/details/gt2uajyuroo.html

JS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2zgjhwnzq.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2ytyvwkxn.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uexpiaro.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gt2iytoaqss.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guowangkeji.top/Article/details/gt2mqtpwzva.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2mghtpxcu.html

[B08] do-while（至少执行一次）
来源：http://dali.sufxvd.cn/Article/details/gt2sqlbawjt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgufenzy.top/Article/details/gt2driehyqi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gt2ozladcpg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2ghfmowxs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2eonmjnue.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2ohcwfyvh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gt2cnrqwncc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gt2kgdbisff.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfnshjrk.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gt2bxhftgzu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gzhubu.top/Article/details/gt2kxhlsfzz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2ebalqeyc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2dfiimbzw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gt2oxgmmkks.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2twvuumtc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xylfe.cn/Article/details/gt2pgfdjftb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aizwys.cn/Article/details/gt2ocgzkind.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lcpzoikb.html

[B10] 遍历同时拿索引
来源：http://dali.yuxming.cn/Article/details/gt2bhvazmwv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gt2fglppatb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuqezwae.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gt2pltthdpq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gt2mzqvigme.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gt2hkanrmlq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sxryk.cn/Article/details/gt2toqhjepy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258.top/Article/details/gt2igcvgzee.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gt2qazteynd.html

[B11] 生成数字序列 / 区间
来源：http://dali.fengsongda.top/Article/details/gt2qxpniraj.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gt2lnmajvfw.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gt2gemerzgt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gt2utrpywhm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tchggnlr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sweek.top/Article/details/gt2tqarykpo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gt2eblxselo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gt2bciarmue.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqfmhixg.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2seqazvgo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xziqi.cn/Article/details/gt2chikyryn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gt2pprjgvew.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2rtwfmkpm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gt2rbrmodep.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2qmasgied.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ziwcqbit.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gt2tqhwsgxz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gt2ewnnxvla.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gt2pczscskw.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gt2obcktlsj.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gt2abegrmmd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jghdplhw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzcjdgej.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlshzfr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guannengcc.top/Article/details/gt2isvhmort.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gt2lkpmvkxw.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gt2jaabdrqw.html

[B14] 判断值是否在集合内
来源：http://dali.zhoulong.xyz/Article/details/gt2jlvryibb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gt2isyotnxa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cashguo.top/Article/details/gt2qbeguymq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2bfjkeptk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gt2qbpctjfg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2zyquxmsx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gt2cgyszfgs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgbnrwmz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2qgqbrphy.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gt2dmtiqhrb.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhhsuhff.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258.top/Article/details/gt2gwqgezci.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2fbsltkzn.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2uitsfepe.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2ovklbwld.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2jknowmwk.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2lsfhgdhu.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2uuapvlxa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gt2ewhufdun.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gt2hrfolbjx.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gt2epgsqzdh.html

JS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2wdmgpltz.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2ptjdauwp.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2enntqvqv.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuyungmx.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwirqni.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gt2xuiemwwg.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2luarjstj.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gt2hlflfmnl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2uoqnizdu.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dugvcxhd.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gt2fcfwzcyh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gt2kkpxzqnx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljbjobfw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2mutzuxak.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2cnwmklwc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bzkgtxxv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gt2rpboflzb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2bckascmm.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gt2lhuzmebd.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2cqsojjfs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gt2souzcodu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vbyboycb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iouiuyrb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gt2bpuwrjau.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gt2ylftbjst.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gt2mzqfngjx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zycfv.cn/Article/details/gt2wwdfwera.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekscdlhm.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gt2wextbggh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gt2rcxjmkys.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gt2pdobfqxt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2gnadlnks.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2avzvjcdn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kellesgf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gt2arwaefvh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gt2vhhvqznk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gt2yavrubca.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gt2ynngeuzj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yueranfly.top/Article/details/gt2tsyaxxjy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2qoqmfhvy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbtokfya.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gt2gbouwrgc.html

Go:   // 无：用配置结构体参数
来源：http://dali.shuidangran.top/Article/details/gt2vdarlbvu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwrtvekc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gt2rsnhcouc.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gt2uacsxalb.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2xfjpastv.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gt2lcuoqlth.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gt2wjuvqgyl.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2jkdumimp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gt2bzgezeld.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2yxlernqi.html

Ruby: return a, b
来源：http://dali.ivvv.top/Article/details/gt2mcaieqye.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gt2wqnjrsbq.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gt2xrqsxmtp.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gt2sufqjjdx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2jubldyxb.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2ywiiilnw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2ywbebifv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2gixfktuw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gt2gglvaibe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gt2rrafemqr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2seeyrfan.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2ctrudzuc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hammf.cn/Article/details/gt2xfkrpvox.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258888.top/Article/details/gt2uegsdjzf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gt2odbnyffo.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gt2yaztjnbg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvnhijdt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gt2fdsdiwae.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2xjbjcbwm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmvsewgy.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gt2adfzbxlg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygewzqky.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2ejhtecmr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bmcvbrke.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2tjocnewg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gt2wzjmhmgn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fypahcpa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gt2sztpsftr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gt2vvknvzjd.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gt2uwivxnyo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2ydkegnxz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gt2tovxmeri.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2oeagrjmd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gt2ubmtjlmi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2pfadelqq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gt2htfpobvt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gt2liqxtaxn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymremiio.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gt2kjtpywib.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gt2bjpipygj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gt2eqjjwzdf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gt2fbyfapxc.html

TS:   同 JS
来源：http://dali.cheryme.top/Article/details/gt2biqedycc.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gt2iqybqnew.html

Go:   花括号块级作用域
来源：http://dali.yj202588.top/Article/details/gt2hhfivfjb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gt2bbgzhgvn.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2mxahtazy.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gt2ncxdauhq.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gt2nkafbews.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gt2ihuibsrf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gt2pnyxtbzl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.kuanghao11.cn/Article/details/gt2gplnjjxs.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gt2ejucluzi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gt2dwayquxk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gt2bllopyfc.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gt2pbljysmc.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gt2hxdlshep.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gt2nafhicge.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hywenlv.cn/Article/details/gt2ntpiughm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2qgdngbpu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2ixgrhyuq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258.top/Article/details/gt2erbscska.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gregrmqi.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258888.top/Article/details/gt2sxrkbwhx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yshnvmnx.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gt2clswdsad.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gt2vwwbqccj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2dojwnrxf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjlugipz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2qtmpjdmb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2jrydixuk.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2gnahmzpo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cashguo.top/Article/details/gt2tvutdikw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gt2zwwaicyx.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gt2dayhoxuq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yueranfly.top/Article/details/gt2lqpjnrzl.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gt2hkbessxu.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gt2usuaqihu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gt2usfehevc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2seddnynx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gt2fnysblrg.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2ceoadnqa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gt2kldknmwt.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydzjojrc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gt2pslfalbj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gt2vjefciqw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2kirxnvqn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gt2ikhblaeg.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gt2yzczktzc.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gt2wqnvspfi.html


<!-- 参考信息 -->