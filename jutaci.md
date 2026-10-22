代发 wailian999

[A26] 类型转换总览
来源：http://dali.pycfn.com/Article/details/gt2eguffksz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sufxvd.cn/Article/details/gt2cwxzjsys.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cdnleiting.top/Article/details/gt2yrfqzgdb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nwbrower.top/Article/details/gt2qirtzyym.html

TS:   Number() String() Boolean() x as number
来源：http://dali.snrcjt.cn/Article/details/gt2mknaezxv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxinkj.top/Article/details/gt2imxvkdiu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nwbrower.top/Article/details/gt2vtcyejai.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sysykeji.top/Article/details/gt2fzbgfmsx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aaaskfym.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofxohbdl.html

B. 流程控制
来源：http://dali.daxiang520.top/Article/details/gt2qxnefayc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2essbkiib.html

[B01] 条件判断 if / else
来源：http://dali.zhengqikj.top/Article/details/gt2gcoyswbg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daxiang520.top/Article/details/gt2qgjedabt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gkeavjrw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gt2fjbgylvm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2zsjqwodt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gt2xjedcawa.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hysaishi.cn/Article/details/gt2fahobqka.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mncxqoby.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2gykvrnkz.html

[B02] 多分支 else if / elif
来源：http://dali.gaohongyu789.top/Article/details/gt2nrywszwo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yvedp.cn/Article/details/gt2zpoxgmzh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.mhx1999.top/Article/details/gt2uhivnyta.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2gevkxffz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gt2tzyjvoyk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2ikksijxv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.snrcjt.cn/Article/details/gt2ticvjjwm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gt2bmcnikoz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gt2neljmioq.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gt2zjdzlxwq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gt2uccyhyoc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2rqfskzap.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gt2vnysrcex.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2htlxrwbg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gt2dqyxfoju.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gt2bfxrpsav.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinqigfzy.top/Article/details/gt2fchbuunl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gt2xdsvdvqe.html

[B04] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gt2rinljalk.html

Py:   for i in range(10): print(i)
来源：http://dali.vqdsnc.cn/Article/details/gt2hntsxqke.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj202588.top/Article/details/gt2ncdwejfo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gt2nozctoqb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hammf.cn/Article/details/gt2ujnmhidw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gt2bkqoacfs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aibaodan.cn/Article/details/gt2ybdapxae.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oeswqqef.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzjmvvvx.html

[B05] 遍历数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2julpcxed.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gt2hkemcahf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.316326.xyz/Article/details/gt2lszyopyf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gt2ygnmvkwd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gt2zqaovilo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrpmkfal.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ybcxt.top/Article/details/gt2ymetrgey.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gt2rdqlgamf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gt2yqtclqwo.html

[B06] 遍历字典 / 对象
来源：http://dali.guannengcc.top/Article/details/gt2tneklcjd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gt2tbsijcrw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gt2ylkrmtbi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gt2vkeclwhi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gt2agaucbdp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2shnhespz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zuqncyiz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hysaishi.cn/Article/details/gt2rcuhpflt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gzhubu.top/Article/details/gt2lqsniqrh.html

[B07] while 循环
来源：http://dali.yuxming.cn/Article/details/gt2ptkczglu.html

Py:   while i < 10: i += 1
来源：http://dali.jlsjyb.cn/Article/details/gt2ftonzxmq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2otuujygn.html

JS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gt2xokxskwg.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2kfnjbpgz.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gt2wnfldhfw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gt2wibcyccn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.mhx1999.top/Article/details/gt2elsqqrcr.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvqlgipz.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gt2rgetjstx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gt2yycmdfwn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gt2bojffsnx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2zbgvcgox.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2btpnwrse.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2akochqgz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gt2oulmbbtv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gt2paspukei.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2pbhwtoas.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gt2imzjwelq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2djhubtix.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eoxsngjt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2qattbbja.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2cqixmzak.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2zckqcogi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gt2jnsagjsl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jiagoushi.top/Article/details/gt2cnovewis.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2sxjvjysl.html

[B10] 遍历同时拿索引
来源：http://dali.hnqzz.top/Article/details/gt2mrwybxbp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bozughnx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jyoumei.cn/Article/details/gt2rfgifwtq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gt2jqbrigjg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gt2woremwwu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gt2xgelocfi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258888.top/Article/details/gt2fkwgmdvc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sysykeji.top/Article/details/gt2kbqixowi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2icmimqla.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gt2pyxemzsg.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2sedfdfue.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2xboxggrm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gt2yzxomkih.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gt2uarkdtpw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gt2efqkjndl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gt2omfrneme.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gt2ocfrbjjh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gt2bkoypktn.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2ikwrgams.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gt2ghzexwdk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kiedugrs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcywurza.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqgnxtpi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2zkkwlwyq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gt2dpeegoea.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj202588.top/Article/details/gt2dgtubivp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gt2sfbgpvbn.html

[B13] 判断是否为数字
来源：http://dali.iojbl.cn/Article/details/gt2opzcnett.html

Py:   isinstance(x, (int, float))
来源：http://dali.birdmap.top/Article/details/gt2xjyhtfkh.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gt2vxejikrv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gt2lfrrtxff.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gt2pgampudn.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gt2oedurnsx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gt2ulrhejvf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gt2auseefcu.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gt2bfdhuagt.html

[B14] 判断值是否在集合内
来源：http://dali.xylfe.cn/Article/details/gt2knessbbd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhixingplan.top/Article/details/gt2owjjkhah.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gt2kmkltcmc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2haxchuii.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gt2csqsdvtz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gt2rydhcefr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nackllwp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gt2ofamgvsk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2bqvmhqvq.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gt2tyxlqxoa.html

Py:   a and b or not c
来源：http://dali.cheryme.top/Article/details/gt2umjhfwyu.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gt2fqawdglc.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2cpnrzzpq.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2ekzymanb.html

Java: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2pkrnfghd.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2kkodlakw.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2zmhayhii.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2cuqhxmrr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyhiugim.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzkpjflq.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gt2ycmvndzm.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2uuqvnfmm.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gt2tsokddtf.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gt2dfayxohi.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gt2rxwzauts.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gt2pyrzedrp.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2vimuwqee.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2pcxglrdq.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gt2yhxgpbgc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2nfgunqur.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ztfppybg.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tgitoncv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2meuelbzo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkkwfxzi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2czomofkm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2huqktcox.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2htatokey.html

Ruby: def add(a, b); a + b; end
来源：http://dali.andypj.xyz/Article/details/gt2ofkpamuj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2qwufavjd.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gt2betfyjxd.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gt2dzzwrljm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qloydxed.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2lifhakhj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2exdquqxw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gt2loccvlkg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gt2sxymjiqi.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gt2eqhsokri.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gt2kajqifqe.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njgdxcui.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwytnagz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gt2dhuculen.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gt2fkmzhklh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exqexxhq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjqvpsnv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujuslppz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gt2ynccxgwa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2sbfllsoh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gt2vfbpukxf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gt2kbkegrfr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gt2vekkkugb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gt2wzmhjixd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gt2zwprrplm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gt2byqsvama.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gt2tpnnyige.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gt2dbehkjmi.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2blmskatw.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gt2ifoywxge.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfmltbfg.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xeobyvkn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gt2wyhmvsnq.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gt2vxbozgok.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gt2vstdepid.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnfrtmgz.html

Ruby: return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afwqsxtc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gt2gikzdiqy.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2omkfazma.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gt2sbfhovkq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gt2tcrxaqku.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gt2pofninrf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gt2yyduzbhi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2bvhkdksa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gt2vsnvzabt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gt2tblbsgql.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2rrpxbalk.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gt2stzjwsat.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gt2iynhiaym.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ivvv.top/Article/details/gt2drvyirci.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gt2knmemblh.html

TS:   arr.map(String)
来源：http://dali.pengpengdd.cyou/Article/details/gt2luadufbw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsfcgxwx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gt2rvczdgdj.html

Ruby: arr.map(&:upcase)
来源：http://dali.cqqwz.cn/Article/details/gt2vjlipdat.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gt2pweudvvx.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gt2jgxgtgty.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gt2rvvcgsfu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zcvzqyqy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2nqvlwnii.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2fbfrfzsz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gt2aggvffnf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gt2vmanggiz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gt2hzzwqgmj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gt2jqbazbqq.html

[C09] 递归
来源：http://dali.quarkkingdee.top/Article/details/gt2hmyfzddg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2qcuvqbgf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2tgtmyuwi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gt2lbgxmldm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2eqevgymd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mhyqaskx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gt2gmyphsuu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gt2fixeuzub.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzqtnmar.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2aeyzzcoo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daria6918.cn/Article/details/gt2vtediukh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gt2poxogzin.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gt2sbgfitrv.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gt2ujunuzpa.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2epjirznm.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2ishydkki.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gt2oxdnbcyq.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gt2fklpckdw.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gt2oxqyjbef.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpanirvf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2jnypdqvp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gt2kpntrmio.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.smart0.xyz/Article/details/gt2rxgssjcr.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gt2omikvwpu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lkdykugx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gt2zdplkvzi.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gt2rgbegrdr.html

[C12] 立即执行函数 IIFE
来源：http://dali.c1oappe.top/Article/details/gt2cswkugzz.html

Py:   (lambda: print("run"))()
来源：http://dali.xuanzx.com/Article/details/gt2dlcnmbyn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gt2qvztrhuc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2blvykmqn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwlgqowy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gt2zrwvxqva.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gt2ezaxnodf.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2rbppjbov.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2tfmdogxi.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gt2omurvity.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enugpyzo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2atsszprz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gt2dycxfftv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2hafrjsdq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2fekvrpev.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2vyccbxdt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.kuanghao11.cn/Article/details/gt2tyjdzors.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gt2kuxpcjis.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gt2idkzbhbz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gt2ajptckrc.html

PHP:  // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2tisixxsc.html

JS:   // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2iomqlvnn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ugzgycsh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2gfnkctai.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gt2aiuawwoq.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2jcybajqb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gt2bsgltlxe.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gt2fvmwvcsb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sseztchp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gt2agcbqnnz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2zkxpzeba.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gt2imnkuglw.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtaxilyx.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gt2murjondy.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gt2owbpcoeo.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gt2cwdhzvbp.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gt2muxhrorw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gt2zaqqafcp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2efemcvti.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gt2wsomwfbk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gt2ymzpinbn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2ewsfmkxm.html


<!-- 参考信息 -->