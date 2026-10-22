代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.cqqwz.cn/Article/details/gt2daiyoxsp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.redwolf501.top/Article/details/gt2zrbiugej.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.daxiang520.top/Article/details/gt2ifdsvffx.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2gjiqzvks.html

Py:   s1 == s2; s1 != s2
来源：http://dali.c1oappe.top/Article/details/gt2cfzsakgm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.mhx1999.top/Article/details/gt2dtvduzlo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gt2fobrhqpi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gotoacloud.top/Article/details/gt2aaiswxhn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2lsgifcpc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gt2mtrqtush.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yueranfly.top/Article/details/gt2ymrtscwn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhagtyf.html

[A26] 类型转换总览
来源：http://dali.xuanzx.com/Article/details/gt2jsnyropa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.birdmap.top/Article/details/gt2lubvrrkj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fzhhl.top/Article/details/gt2cnxfplfd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuanzhike.top/Article/details/gt2lscnzauv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cheryme.top/Article/details/gt2ccnwqaey.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gt2vbqwfwti.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqbrhedv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuetiantiany.cn/Article/details/gt2xiqcolzb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gt2rgyphvkz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2lnixsoat.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gt2hkpzyfny.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2lcofuovv.html

[B01] 条件判断 if / else
来源：http://dali.xuanzx.com/Article/details/gt2vjgwkuwv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.quarkkingdee.top/Article/details/gt2asnnuyzq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uxrkkmhz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gt2mtozijec.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntywwxxl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gt2xycbbkwc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gt2jqjzocez.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yangfankeji.com/Article/details/gt2frdkbmye.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gt2fifljdis.html

[B02] 多分支 else if / elif
来源：http://dali.guannengcc.top/Article/details/gt2ngawubxx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.mhx1999.top/Article/details/gt2tvxmzxan.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cdnleiting.top/Article/details/gt2otsltuca.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gt2nwdxsruj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2uybjaunz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gt2agpipdce.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gt2jxfblxao.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gogol.net.cn/Article/details/gt2hfgztead.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gt2muywssso.html

[B03] switch / match / case
来源：http://dali.yj20258888.top/Article/details/gt2npueltsz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvjpmvky.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2fvekgnhl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihrpsbhm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohyfismd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rypbppbm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.smart0.xyz/Article/details/gt2hvqsqfkx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zycfv.cn/Article/details/gt2puqslith.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gt2viqvkkff.html

[B04] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2cconbqhc.html

Py:   for i in range(10): print(i)
来源：http://dali.xylfe.cn/Article/details/gt2zbqfodnt.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zdqjudy.top/Article/details/gt2zjbsulch.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gt2spgvxlnq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gt2grzgirha.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yueranfly.top/Article/details/gt2bgzvrqmq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gt2gwpmyojh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.9152youxi.cn/Article/details/gt2bufsdlxh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yonumen.top/Article/details/gt2aajhjidz.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2cwgfpkio.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gt2fylwwsuw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hysaishi.cn/Article/details/gt2zfbjomny.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gt2wevnqttm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gt2lhklqsnu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hammf.cn/Article/details/gt2kmukwomo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gt2bweyolhq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yonumen.top/Article/details/gt2risjguye.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2mkvxndzj.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gt2javiabui.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gt2qldmzxjb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cevgxbyk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gt2ymlpfctr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cljijiuu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258888.top/Article/details/gt2lmfuwfai.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cheryme.top/Article/details/gt2xgriqnuw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.snrcjt.cn/Article/details/gt2wbsgrujj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hfpthk.cn/Article/details/gt2mfdasdis.html

[B07] while 循环
来源：http://dali.yj202588.top/Article/details/gt2wwnjauci.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gt2bairvwjv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2hjdezvlz.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2ijuvvnkc.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2swxyswfs.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2yamilihf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gt2ztlihzjh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkdhttup.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2szqxjwdn.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gt2xeahnvwk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gt2qlxyirpq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gt2nlabqlvn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gt2qibnogzl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2lrnrkjtx.html

Java: do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgqsvfnw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gt2teepcjcj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gt2ixtylamh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2kntaxfdr.html

[B09] break 与 continue
来源：http://dali.ehwqpu.com/Article/details/gt2aahgkjlg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gt2rvvpsvzc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juygakvd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zlebaoqx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxyxzpbr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2yrtaisrd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdltsald.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gt2ubenehad.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2zyihqqcw.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gt2pisspeef.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhengqikj.top/Article/details/gt2kkhdmmnm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xinyue.icu/Article/details/gt2xrdawhhn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gt2tqyqamva.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gt2ymexnbih.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2oejjyldc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rubygtvb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gt2olbdscwr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2bgvmphxz.html

[B11] 生成数字序列 / 区间
来源：http://dali.dashuyun.cn/Article/details/gt2slqhbkgb.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gt2hdilkhhp.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gt2xxukvokn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibwnvjhr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gt2uetmembt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsfodsuk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gt2elfolkso.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gt2twhmciqr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gt2ndkxqjms.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gt2euuiarhl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gt2oqzmaznw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2edhdxgqn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2fosmfwho.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2xmcvfhhu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2lsmbinqz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sxryk.cn/Article/details/gt2ziodnkde.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2qoxkoxxy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jianghu66.top/Article/details/gt2bdosggyr.html

[B13] 判断是否为数字
来源：http://dali.gaohongyu789.top/Article/details/gt2puuooxqv.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gt2bgyezymk.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gt2kgjxmbmb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyxgnrdq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2disvjyuk.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gt2lzfcqxqw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gt2huktzjfz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gt2rohcwhqy.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gt2vccytfww.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgciwulc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gt2arkinoqo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gt2ciccmcii.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gt2cackmmya.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2lcztavbc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nurnjypp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gt2ekxqoakh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wawcgcbz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2mfsczrni.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzjicvpy.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gt2yvnybuok.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gt2vtgsbtdy.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2pissvmfc.html

TS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2eddtdbet.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2xpporlkz.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2ahmgmvur.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2pbwbrlpz.html

C#:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2maovdtvw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.birdmap.top/Article/details/gt2wutpenjm.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwleznrw.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gt2ppioonfl.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gt2inyydojp.html

TS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gt2csjupzsr.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gt2zbvuopos.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gt2jpkxjjxb.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gt2kjiywezj.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqpmschw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ispiwcpl.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gt2ttumlase.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jhyotaom.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2oramdthh.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2gocaypwi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2gxahqnom.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2esgqouey.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2mhpdqlgr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2nlkggbnx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2hwcvjdeq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gt2vqldvehp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2boqklknb.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gt2djjznrkz.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gt2ezqmvyoz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gt2pxgntbdp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ofzsnjze.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2kwxgfplo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gt2peorbogv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gt2wwxbffbk.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gt2luxivmgk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gt2asanebqh.html

[C03] 可变参数
来源：http://dali.gzhubu.top/Article/details/gt2lnrwsbro.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gt2vufqhvzi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gt2idlejdqf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gt2aibkprzu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gt2vxcmzzrp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lahrwhdr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gt2iccynwzs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gt2bcysjowx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gt2jiqzwpkw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gt2pmjifelc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gt2krjfdiat.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2nojgjmcx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2makonsnw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gt2qepsmlmp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2pxgltvhy.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gt2sheupwup.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ltucnsam.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gt2ycxocmbt.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gt2rxdbjock.html

Py:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkqpcoen.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gt2vbfzmxvq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2wscbmfwh.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gt2txuuzefh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gt2tpwhrklg.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2lgxxttex.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gt2zwqtvxiy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfbbrra.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gt2vsoaydlz.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gt2ugfhmhje.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gt2dpnrxcft.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gt2feebwcks.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gt2zuivzblc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvjwpcuo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gt2ecsnlgrp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2bzingkcj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2zjugchbd.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gt2vaoznvvz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gt2qdpdvauq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdwozzqa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gt2vjfpixnm.html

TS:   arr.map(String)
来源：http://dali.bjfxy.top/Article/details/gt2gaclnpzi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.mhx1999.top/Article/details/gt2spoekevn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gt2cbnxqahl.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gt2sudjusyd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnagcskt.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gt2wzbjfxnd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gt2oponddhb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gt2afccjdcu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2kzztgnvr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2neubxqfy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gt2ldzwlple.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gt2dnogmcwq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gt2jygsylge.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2ttogxmaz.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gt2hxzymegk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2eimbhihf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2dofcrelr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gt2yunjdixn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gt2qtqtqplg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2dushrtzz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2stswizfp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2gyotwasl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gt2mjthacsh.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gt2strwmela.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gt2irxyqqge.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gt2ptziyiiq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gt2ooayfcet.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2cjqnqpwi.html

Java: 方法内为块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2eitnrnyd.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2iippncks.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ybcxt.top/Article/details/gt2agdffsip.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gt2xlbngnmf.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gt2rmudenxy.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gt2frqqsqbh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gt2xrikhcux.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gt2yyikixna.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gt2vpnztfpu.html

Java: import java.util.List;
来源：http://dali.vqdsnc.cn/Article/details/gt2gfskwaar.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gt2fovkncsm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gt2zkklgbvd.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gt2xtmcfhbz.html

[C12] 立即执行函数 IIFE
来源：http://dali.hywenlv.cn/Article/details/gt2xfkntekh.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gt2wndmdzfv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gt2jegcckbm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gt2wzowyqzj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2hjvhqlpn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gt2dkqkhbnd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2acnidkzv.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gt2hhcelsst.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gt2isgjloxe.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gt2yxouxxrh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2eeyqemja.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lsqgwfxo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gt2tezutdph.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dopslpup.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2fktyavmr.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gt2seulvmff.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gt2wudqbvpm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gt2efkrmcto.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gt2krddecvn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gt2twcaqowc.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmvryhs.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2yqughrxs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gt2ewuainpv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gt2uoegeiyh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gt2dyouonxz.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2fykhjnzl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rcrceeus.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gt2vdiyutht.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdbogfuz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gt2kqvddnsg.html


<!-- 参考信息 -->