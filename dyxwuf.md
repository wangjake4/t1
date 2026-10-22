代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.redwolf501.top/Article/details/gt2swztoqbh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.haohaochexian.top/Article/details/gt2eekfafti.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gt2nzjpqgrs.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gotoacloud.top/Article/details/gt2ufzlgmqx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gt2djbwhely.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gt2kwyafluj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxznjuht.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gt2myhwssgw.html

[A26] 类型转换总览
来源：http://dali.ppjwa.cn/Article/details/gt2tflmcauc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jiagoushi.top/Article/details/gt2nxxfplnr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gaohongyu789.top/Article/details/gt2glvadqvr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.bjfxy.top/Article/details/gt2xtypjuzj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gt2emiiwtlr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gt2ohjnamdq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.meibo888.top/Article/details/gt2lffkraat.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.bjfxy.top/Article/details/gt2cohyruku.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gt2rjmrevjs.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2wpjvxyba.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gt2vsmqhmgp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2xxycfizr.html

[B01] 条件判断 if / else
来源：http://dali.yueranfly.top/Article/details/gt2bfcrlpwp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhongyouzk.top/Article/details/gt2egcbogwv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gogol.net.cn/Article/details/gt2penpcorm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gt2fsxjtkhy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gt2eygbplzw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2zqslnkev.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cashguo.top/Article/details/gt2zfaleoys.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenlongwang.top/Article/details/gt2xzpuilxi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gt2injbvypm.html

[B02] 多分支 else if / elif
来源：http://dali.cheryme.top/Article/details/gt2lnyyduqa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nwbrower.top/Article/details/gt2lcktmfcl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaezwopc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2jcsrgceg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gt2txtcqeot.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gt2lixevhlj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gt2wknfiuix.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hywenlv.cn/Article/details/gt2kenixajw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2yazbtnpo.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gt2jvbkkfpg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xylfe.cn/Article/details/gt2baqpswdh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2vmthicsv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2onoclqgh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2oirgttyx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2rpofbbgz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gt2inrttoyo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258888.top/Article/details/gt2rpqrusqh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gt2szxastsx.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2xhcyytko.html

Py:   for i in range(10): print(i)
来源：http://dali.xinyue.icu/Article/details/gt2whqkeqof.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxuanxn.top/Article/details/gt2neeltcnl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gt2lnaftvpu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gepeuiyg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shuidangran.top/Article/details/gt2svarwzol.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fengsongda.top/Article/details/gt2jfovxrqc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shuidangran.top/Article/details/gt2mjertrny.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yueranfly.top/Article/details/gt2kmfmikep.html

[B05] 遍历数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivhbpurx.html

Py:   for item in arr: print(item)
来源：http://dali.cheryme.top/Article/details/gt2vnqzzsmx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zdqjudy.top/Article/details/gt2pezabgyt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gt2ryioxmwr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2fgmxrief.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2rxiiqstp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gt2vkfrzyww.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gt2fjuztguq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gt2sxtcitfd.html

[B06] 遍历字典 / 对象
来源：http://dali.tian-w.cn/Article/details/gt2puwuenqe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cucudq.cn/Article/details/gt2prqxkghz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2onpofjxl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gt2zqnmakxb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gt2morlfabv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cashguo.top/Article/details/gt2sfttjkth.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gt2jnxygnup.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gt2pcnbyyyj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gt2qcltkwgd.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gt2kvttqfuk.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gt2nrhklocq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gt2mpycjxvm.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2notkmlxt.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gt2knotoscy.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2lkcbemuf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gt2ndtiawvp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ziqarjrm.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2dfbnpwdm.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gt2oxpuroxo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gt2tcneydkh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2sfxnhxzj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2jwpntsrb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggtlhgnu.html

Java: do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2uakefjti.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.0kj1m.cn/Article/details/gt2sujvdwqy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gt2djhmmtww.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucwbdxcv.html

[B09] break 与 continue
来源：http://dali.aibaodan.cn/Article/details/gt2kkotfrgy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yueranfly.top/Article/details/gt2jnnwdffj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ydrykhmt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2kekkzvan.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2hciuwewp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2xohadlzx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj202588.top/Article/details/gt2viuenmnj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gt2tafesstk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2mpkltanw.html

[B10] 遍历同时拿索引
来源：http://dali.dashuyun.cn/Article/details/gt2mfgsxrsw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gt2mcooimzo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gt2yooiiuyh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gt2gldaqaiq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gt2htyxulbo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gt2lxmtlrxh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gt2hdyegxue.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guowangkeji.top/Article/details/gt2pcicdmew.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gt2uvzmyfeb.html

[B11] 生成数字序列 / 区间
来源：http://dali.cashguo.top/Article/details/gt2cgeajyam.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lgrmodnu.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gt2kryqxien.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gt2uhzjtglb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2wlzpgeur.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gt2gwusxpzi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gt2pqpttqyt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.andypj.xyz/Article/details/gt2osruyxee.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gt2nzfsdyah.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gt2xouxkanc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gt2kkydyatv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2fwnuryip.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2hsbgnmmv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2xhnysqyg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylsoywps.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gt2vznsvtwd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gt2wgobyuqr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gogol.net.cn/Article/details/gt2vymxzppb.html

[B13] 判断是否为数字
来源：http://dali.yuxming.cn/Article/details/gt2ydoujhgf.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gt2akomiknu.html

PHP:  is_numeric($x)
来源：http://dali.guowangkeji.top/Article/details/gt2lrvhdynu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2iwsrkmyh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gt2zfjqgtsq.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gt2peftcono.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gt2zsmcadsu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gt2uzrpcden.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gt2leenrmwf.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gt2mchfsqkl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gt2mlxclygq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gt2ghjoyvjg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2xbkosvtg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mjgptxcu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gt2mwahblmb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gt2cjtobwkl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gt2rshslncv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2fckcgbkk.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gt2vxynftwa.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gt2bzrwjppo.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gt2freslkkh.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2kbpuchpk.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2bopyharh.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2gvxagycb.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2sfelchaf.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2htupxpev.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2xbydurfg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqoxiamo.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gt2ctrxlckc.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gt2qfgylxdd.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2gzyqmsee.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gt2uqczeurw.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gt2bfpanefh.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gt2ixwhekfn.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2dhvnbith.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdfeqqbm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2iuhaldut.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gt2pmyinhhk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fxcuwtzr.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2kelosoan.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2iqsalvvn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2pqbidoam.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oofoftap.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2pfhdwinn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2zrmpsood.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gt2llusfewb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gt2lmxzoohu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2xeegydcr.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gt2djpvfusl.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gt2qjltmpms.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dianchejie.cn/Article/details/gt2qtjmgqog.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2pmfcqktt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2wqukbaja.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gt2bpbzrlyg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gt2xcufxzrj.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gt2pyjebpvb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gt2lubvtoop.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gt2ogpmgema.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gt2ybkxgoyr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gt2mzhnnvhf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2slupqpin.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gt2whydoyqk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gt2recokvqu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gt2zjsxhqsd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2jytcxtuo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gt2gnksaxid.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndmgjacu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gt2jlvvyzlb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gt2pheuyynx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gt2tmkfotlr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gt2ysjjxwvo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gt2wpfvejtj.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2cieguaxj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gt2fmaehkct.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2rbkwtlfr.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gt2fbpeykpv.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2mrpbmimy.html

PHP:  return [$a, $b];
来源：http://dali.andypj.xyz/Article/details/gt2dhnvudyv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2grlutroq.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gt2fchugyhh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gt2yruketqa.html

Go:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gt2fumxkvhs.html

Ruby: return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2yvgviber.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gt2etlvbnfz.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gt2curfqjur.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gt2quaeseds.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gt2cygmjrse.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysynsrqz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2cvlfjkfn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2xxwwrtvz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gt2jtiopxuu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gt2uhomyazr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2xiwwgiek.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gt2tnuffbxg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xziqi.cn/Article/details/gt2ilogdqzu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2urqvsicv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gt2idbyxqdt.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gt2mddpvptu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bralfxfe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gt2meyactoj.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gt2bhomawpg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gt2gtuyjibg.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gt2bgiqnxth.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gt2yjwsokry.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gt2ecllbbzp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2vvdbeyni.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2cuiumpgb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wowrtcqa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gt2bzwcedsi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gt2uvwgxqbd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tzgmxoto.html

[C09] 递归
来源：http://dali.xziqi.cn/Article/details/gt2xbawvtne.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2vvputhmq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gt2bpsvvucc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2ggcfvzjo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2psrkhckj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2ibbjgwdf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gt2tfrbhwqk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2eetsgjau.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tian-w.cn/Article/details/gt2qvlbbrjh.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2nzikprpu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gt2wtajwttt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.c1oappe.top/Article/details/gt2ddmmzgag.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2kjtubuya.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gt2ursokopx.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2rddpqnvz.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2carfyjsl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gt2omngkaii.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2nkxlznxw.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gt2ikdvtycy.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gt2zuxxvrhc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gt2gjyfqgjb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cheryme.top/Article/details/gt2crzgiani.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gt2vgomvyyu.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omcbytix.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gt2ejdrlebi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gt2jpzapuil.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcktztfv.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gt2vtdixgmh.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gt2jnhhdpwh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gt2dvndigwr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2rsvrezkj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gt2utzajfuw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ppjwa.cn/Article/details/gt2ldmuwhaf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gt2zcmlvwim.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gt2mptxvlxi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gt2yrgjlvhl.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gt2ddsgtjrj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2nazhkfle.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2xqthooon.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gt2uvtstjlv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2nzvafmmt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2ltssuomo.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gt2pdmgzsoo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gt2ykolmlwp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyioethe.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gt2tddthddy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gt2yuvoyaat.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2jkhxapde.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2knhvlqda.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gt2yzvngbhz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gt2trehgzbh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfxkiubu.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2uxvbcdzu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.chenjidiqi.icu/Article/details/gt2xuvtwumg.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gt2ixjxjtly.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gt2atcieduq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gt2lszcxsar.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2mgdomdqs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2jtypdybz.html

Java: // 无解构
来源：http://dali.svipenyu.cn/Article/details/gt2cueyfshv.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gt2mkrtaedf.html


<!-- 参考信息 -->