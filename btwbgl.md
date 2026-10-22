代发 wailian999

[A26] 类型转换总览
来源：http://dali.hywenlv.cn/Article/details/gt2olfmimdx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.andypj.xyz/Article/details/gt2qjarszoy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xinyue.icu/Article/details/gt2raydqkgj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xziqi.cn/Article/details/gt2udxmppum.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jlsjyb.cn/Article/details/gt2npbvpjmc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gt2pmledbyx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gt2vtixhopi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.snrcjt.cn/Article/details/gt2jxndxioy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gt2begipnrc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2socwpxtu.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfpozqdm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dmvfafrf.html

[B01] 条件判断 if / else
来源：http://dali.bjfxy.top/Article/details/gt2eokdxmfw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gt2mwdqxvxq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj202588.top/Article/details/gt2soikryke.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2cittdhov.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2odawgqjm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gt2woqydiul.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2njhxsfgm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.quarkkingdee.top/Article/details/gt2fkdbgggs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2xhsidvyi.html

[B02] 多分支 else if / elif
来源：http://dali.birdmap.top/Article/details/gt2nmaapfqo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnqzz.top/Article/details/gt2vnbfjsqq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pycfn.com/Article/details/gt2osqtxqcf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2dptpadjd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2ylqfrehc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gt2izqhlbzw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jlsjyb.cn/Article/details/gt2nswlipqo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xziqi.cn/Article/details/gt2yjcfnoie.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lirrqpwd.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gt2aqlciywc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mazowtpa.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2ndbojkcq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gt2ulepscnv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2iuttwfiv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2jfiqkgbi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.9152youxi.cn/Article/details/gt2srdtbsru.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gt2rruxmueb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgjzmtaj.html

[B04] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2xkauoaiz.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gt2evbcsadb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dashuyun.cn/Article/details/gt2uhqhujff.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gt2xrflpkti.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2drvfgfev.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gt2pauuvzxp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.0kj1m.cn/Article/details/gt2keoolgnv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jyoumei.cn/Article/details/gt2esjrlrih.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gt2jyhlhncr.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258.top/Article/details/gt2kmygkndo.html

Py:   for item in arr: print(item)
来源：http://dali.jqgufenzy.top/Article/details/gt2qxtqbavw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gt2aouovpwk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2qufgypgt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gt2ahowjfuu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gt2dxmeqywp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ehwqpu.com/Article/details/gt2uliuddmp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yonumen.top/Article/details/gt2urydodle.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2zzujeokt.html

[B06] 遍历字典 / 对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2zkwsxkkj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gt2czarswss.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gt2erjhbupb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnxiangtu.top/Article/details/gt2zenmnyml.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gt2cbkbleyf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gt2soxjyavt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gaohongyu789.top/Article/details/gt2zjwrnwek.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guowangkeji.top/Article/details/gt2ixddyvna.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuanzx.com/Article/details/gt2yxvoikry.html

[B07] while 循环
来源：http://dali.yuxming.cn/Article/details/gt2faisvfsa.html

Py:   while i < 10: i += 1
来源：http://dali.zhengqikj.top/Article/details/gt2zgppootc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gt2mrfckwoe.html

JS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2nsanilku.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kszonmns.html

Java: while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2yxbvdpai.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gt2ebzmgjhm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmrecfgc.html

C#:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2iyemhdea.html

[B08] do-while（至少执行一次）
来源：http://dali.0kj1m.cn/Article/details/gt2fehpcfxy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gt2vephgenm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2finjfynb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2zdjyrpci.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2bqcxxdjx.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqqmuflj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuanzhike.top/Article/details/gt2qxjqfebm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gt2nkziwhdh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2rcebrvds.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gt2gyswixln.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.smart0.xyz/Article/details/gt2nybfydfh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2fpalzjgb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2riyzqovq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2moslmjll.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hoplhmeh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gt2dlroinor.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gt2mnxamapf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gfwxbzhm.html

[B10] 遍历同时拿索引
来源：http://dali.daria6918.cn/Article/details/gt2hrtbrxur.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipufkwgw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gt2gtduixxn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gt2fczqiqwu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2kzbkhvuu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jlsjyb.cn/Article/details/gt2jjunzhmc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gt2xjdkxfdi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gt2xeynspqt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfulrliq.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhongyouzk.top/Article/details/gt2jgohgzzi.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gt2zsmhukcs.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gt2xkwlsash.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2aijzhmag.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2ghlcwhxo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gt2jkguomku.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gt2orvsboea.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shzxlz.cn/Article/details/gt2eeitrwyl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2kewontru.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2ifovofrc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gt2xsfbkdlj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.9152youxi.cn/Article/details/gt2ymegnbfv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gt2xztzfvek.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2euwanbth.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2jgtwsqpg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gt2ghghpncx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cashguo.top/Article/details/gt2cfgghvtu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xinyue.icu/Article/details/gt2uwyqmtjx.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gt2pttgaydo.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gt2psrgdfby.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gt2sxdhymjl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2emuerbuo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2inanajts.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gt2jwjfsiuj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gt2wmkfpwje.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gt2qbhwqyoa.html

C#:   x is int or double or decimal
来源：http://dali.cheryme.top/Article/details/gt2nukkeusg.html

[B14] 判断值是否在集合内
来源：http://dali.sysykeji.top/Article/details/gt2ihuktyoc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj202588.top/Article/details/gt2eqrypnxk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gt2psyptudk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2dokpfqna.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2kwlxlvip.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2zotdnmwx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gt2ghiabxve.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gt2nnccxsjx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2lxftyees.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gt2cgmrlqkn.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gt2qrixxitz.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmwbtbya.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2uvfjebvg.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2rtasjluw.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2lhicyijc.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2svyebxic.html

Ruby: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2yyuwlxdo.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2vligcbqc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ehwqpu.com/Article/details/gt2usxnrmps.html

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzigoxpw.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gt2rjizkxfz.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gt2mvcxmyip.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbqrfvtb.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2yscypyst.html

Go:   if data == nil { return }
来源：http://dali.yuxming.cn/Article/details/gt2krkptixi.html

Ruby: return if data.nil?
来源：http://dali.aizwys.cn/Article/details/gt2pnfxiokx.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2amdjlegi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2plhkgeag.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gt2dugyyyuj.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzviljkt.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdsmtcrg.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gt2ctnicqih.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2zjkbmubo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2xerxsbfi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2rqkiuaqy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2mjkglagy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gt2qcsncpvq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gt2gqaeicqt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2wcbtztza.html

[C02] 默认参数
来源：http://dali.0kj1m.cn/Article/details/gt2qyjmlegi.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gt2exlzmjeo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tshsbkva.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxbinqmp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nhqwcedk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxafpzts.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ivvv.top/Article/details/gt2tgmlsdqb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gt2qxvuniox.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gt2akcinuwr.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gt2ujcfrjrg.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gt2zbyjdkhp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gt2pnzsiqxx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2koknxsex.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gt2qxsxlmcx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gt2rjtbbeqg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gt2bfbozvwp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gt2yayxksyb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2guydyoxk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuxming.cn/Article/details/gt2wlgdksod.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gt2fyswrdgv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdiueepd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gt2wrfvwxvb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2swuuqhld.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jgemgwte.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gt2pafwzxux.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gt2ygnrbahk.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2znufsajt.html

[C05] 返回多个值
来源：http://dali.hnxiangtu.top/Article/details/gt2tatvzjph.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2blcmjfxy.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gt2aangdgvy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gt2ycerypfq.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gt2wyfuvykm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gt2jubtbtjo.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2eiwmmasf.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gt2rjhgbgba.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnxiangtu.top/Article/details/gt2mrbnbapy.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gt2tatlwuix.html

Py:   square = lambda x: x * x
来源：http://dali.jlsjyb.cn/Article/details/gt2tcbdmrqu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gt2vmfeqmeo.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gt2elwkdrkw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2kuwudnuz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2xjydpgpa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gt2nmhrakql.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gt2xlijnmfx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhbpmexr.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gt2shjwkzaa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gt2ttscqftn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2uygqrpfe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gt2zyvpvvko.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2dydicvkv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2dltwmsjc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gt2hzhqihmd.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gt2ifghrbyp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2bkanspdk.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gt2jjvttkys.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gt2rztamzjw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rvgxabnm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2keiabiju.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2lmwmtbjh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gt2lxqbqfnv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gt2lsebobwe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gt2iuresldc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2wisgssol.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gt2ryfbinhm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2hdhvtdch.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gt2ftvglbdj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2omorywcq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2onhqkrwj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cdnleiting.top/Article/details/gt2dagoaoxz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gt2plkgyzbb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2ltqsuzql.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gt2rboasyyq.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gt2ovezcnug.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gt2vjijwqfx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gt2ppkrkups.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gt2qiwmxihm.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2antzyuff.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2opqhlfxu.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gt2tosklgdp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gt2agtiunlo.html

C#:   块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2hqabtwwy.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gt2clidybfv.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvitgayc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gt2vgpiijzu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2mjyxmwgh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gt2ubyzjfhw.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gt2ecmkwphr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gt2jtqujhca.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gt2qieblyrl.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gt2rrsyadpv.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gt2gpxtriuo.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gt2etwquclo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdqzhosa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gt2zsbqwcuu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2uovtgwqq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gt2nlhcbnte.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gt2zqiltbhb.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2iropnmif.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.redwolf501.top/Article/details/gt2fqkbwxyc.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gt2npqvsqtf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gt2fkmzatsm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2fkhbbjnl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xylfe.cn/Article/details/gt2lphadkyo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2aktupipz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bpcdjujy.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gt2anveqsld.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.iojbl.cn/Article/details/gt2wziafdmg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gt2vabrdmep.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdghjanz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gt2bwmoxazt.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2temrfjqw.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gt2tntypnuo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gt2paxyzyry.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xylfe.cn/Article/details/gt2wvjqrjzj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gt2amzkxxwz.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2hvvmzsbb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gt2fcawebiv.html

[C15] 解构 / 展开参数
来源：http://dali.fengsongda.top/Article/details/gt2sdbvaloh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2puwdxvtc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gzhubu.top/Article/details/gt2rbbrjuhd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2qqqjvnph.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tian-w.cn/Article/details/gt2bxgjybys.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2egunspaf.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2wkpeyvdl.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gt2svprbvpn.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gt2iwujoeug.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fowswelk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gt2szxhkdyf.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gt2dcpepcvm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gt2gwjujxqt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cucudq.cn/Article/details/gt2aigoolgq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2myupofpt.html


<!-- 参考信息 -->