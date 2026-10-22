代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aibaodan.cn/Article/details/gt2ijilndlv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gt2tqyzhxje.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnqzz.top/Article/details/gt2tpqdjkqt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gt2oizzcewx.html

[A26] 类型转换总览
来源：http://dali.xinyue.icu/Article/details/gt2edkuxaqd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.mhx1999.top/Article/details/gt2nuqjbwtp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwhgupsc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gt2cuinifja.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhongyouzk.top/Article/details/gt2mwzhcvqe.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gt2mtvcaldk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.316326.xyz/Article/details/gt2daugqgxw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sufxvd.cn/Article/details/gt2nnyrtwaa.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gt2eajxooez.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2sxisiybo.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gt2xploppam.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ntadrgho.html

[B01] 条件判断 if / else
来源：http://dali.hysaishi.cn/Article/details/gt2mlefkpws.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.316326.xyz/Article/details/gt2mzpzymur.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ppjwa.cn/Article/details/gt2wkttbejw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2vvtuqqwj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2vogoqclj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gt2sorjfwuq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.c1oappe.top/Article/details/gt2ztiihysa.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258.top/Article/details/gt2pbkrsjgo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gt2myhwlmtu.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gt2yngaspza.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gt2eteoskkx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sufxvd.cn/Article/details/gt2qrealfgs.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gt2odfhrjbu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2fcapvcfm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2tcoqwizu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nwbrower.top/Article/details/gt2ejdgdwsf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gt2qtcdjvnz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gt2raqlvlig.html

[B03] switch / match / case
来源：http://dali.zhoulong.xyz/Article/details/gt2yebgbqny.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrcgurhx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2ygaxbjvk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gt2konzffbg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2sqtmqged.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xpkyafbz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daxiang520.top/Article/details/gt2zhbqtoak.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guannengcc.top/Article/details/gt2ksneyuni.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ybcxt.top/Article/details/gt2cpgzxgaw.html

[B04] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2xalwyrqr.html

Py:   for i in range(10): print(i)
来源：http://dali.hfpthk.cn/Article/details/gt2wzndvsez.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.haohaochexian.top/Article/details/gt2yaqtygnp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilnnqpoo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gt2agssauwn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daria6918.cn/Article/details/gt2smqzwixp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xinyue.icu/Article/details/gt2psrzbfua.html

Ruby: 10.times { |i| puts i }
来源：http://dali.smart0.xyz/Article/details/gt2sddczqju.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgfkbmna.html

[B05] 遍历数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gt2soeijhlj.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gt2zumximxf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gt2plkhruby.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qceebcqs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gt2rfqtgmti.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2utxcuifg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cheryme.top/Article/details/gt2rsrlhknk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangdashe.top/Article/details/gt2eodicimy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2ykdizcrf.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gt2hymiidax.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gt2hbxdalxy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daxiang520.top/Article/details/gt2xzghrcdq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gt2hnixfvbf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gt2ucocfphe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tanke756.top/Article/details/gt2nyupcpha.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gt2mpksccud.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kylueifj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxuanxn.top/Article/details/gt2esbbfmzq.html

[B07] while 循环
来源：http://dali.guannengcc.top/Article/details/gt2rypmtbhb.html

Py:   while i < 10: i += 1
来源：http://dali.mhx1999.top/Article/details/gt2qgdsgkiy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zdqbntgb.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2lyaiihur.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2diwmusye.html

Java: while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2iyustzvn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gt2qbtvajyd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gt2gwuotzxn.html

C#:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gt2ugbwxgig.html

[B08] do-while（至少执行一次）
来源：http://dali.xuanzx.com/Article/details/gt2mpedonpm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gt2hmevepsz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2ycknxpbj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rsughoqw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2bwsucyin.html

Java: do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2fwicmarr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gt2mlpmmwlk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tianlin.xyz/Article/details/gt2slxypghd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2sozvyqrh.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gt2xiwzdczh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2crkzljmp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2ztvepthz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2otvpwzjh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2fphzkxdu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2yaqroqob.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gt2cgnswfln.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gt2pamlbzle.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2wwmhvajw.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qltkqast.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gt2gjplxeac.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cucudq.cn/Article/details/gt2icmjifkz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gt2gwcpjiop.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2kfsvfloq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cheryme.top/Article/details/gt2xckqronw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uzwvardj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gt2vgjidiek.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gt2qpasdxjq.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnqzz.top/Article/details/gt2svydjopt.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gt2gywteowc.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gt2jcmoykog.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2zjufdwod.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2zyddyjqv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gtymfbrf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gt2uhjzbwmj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gt2dizgeqzt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuanzhike.top/Article/details/gt2tzlazluf.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gt2bovcdzad.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gt2qmdjfpxq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.c1oappe.top/Article/details/gt2ropjzptp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2wtqeqhio.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gt2odclzasx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2iybufdqs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gt2ihqkcnvo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gt2dypolbvm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gt2kyewatwj.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gt2auahxnes.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gt2xlpspnkn.html

PHP:  is_numeric($x)
来源：http://dali.daxiang520.top/Article/details/gt2nxlhyvze.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2yaugrfos.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gt2bldaqllq.html

Java: x instanceof Number
来源：http://dali.haohaochexian.top/Article/details/gt2awhmbprm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gt2ilxkyaoe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gt2qhaoemae.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbpmbjmd.html

[B14] 判断值是否在集合内
来源：http://dali.vqdsnc.cn/Article/details/gt2ortkunce.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gt2ifmrtvln.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gt2htxxkozb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2ioobsecb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2rifyfnbl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2wlcutyta.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gt2clhtxwqg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxeiuhar.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2dzzbhmni.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gt2aewzpowq.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gt2wirzpugf.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gt2zsgigocu.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2hdgwipsv.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2etfmcjnh.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2gihxwlwi.html

Go:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2nswsbiyi.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2bktrnzun.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2zpnmlzvb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gt2qqcqyxac.html

Py:   if not data: return
来源：http://dali.tanke756.top/Article/details/gt2vhbnuruf.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aduiruxn.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gt2vxrngwew.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjdugcnc.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2tnbhfjmw.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gt2gzggomjs.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gt2biyojylr.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gt2kitafaqj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2qzdwadyj.html

C. 函数与作用域
来源：http://dali.meibo888.top/Article/details/gt2crbwsjrz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zwuuwqix.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2vpdooozp.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gt2jiuunobp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2glssijwr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2gmvdqvqy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2ietdpcnj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gcqjyivl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2pvnreiyb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gt2erpxzlny.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqemuujw.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gt2dminyyje.html

Py:   def greet(name="World"): return name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2coyhenbk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gt2snuzfzyy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vxzotqcz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2mffnsaem.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gt2nqbysrtf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gt2gjnremip.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gt2scbfleje.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gt2rhrmyjea.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtthbyv.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kffwhzcq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gt2knzzzell.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gt2kcoqqzdw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2qiohzmrc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2segosepy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gt2qdjowbkc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gt2ijapenge.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gt2xjdnbnvh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gt2nfcnaisy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gt2fhnrigip.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2eaxmucwd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2inaflglz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2dbhrdhxx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gt2yeymfsds.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gt2dpujrsgo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2itzizokc.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gt2hgeokswd.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gt2efllltfy.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wsktsqkh.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gt2vvkawcqo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2uxszdwoq.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2jxhtsewv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gt2urvvdwbj.html

Go:   return a, b
来源：http://dali.mhx1999.top/Article/details/gt2axsudzcc.html

Ruby: return a, b
来源：http://dali.nanxuanxn.top/Article/details/gt2gbycbuhi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkxhfhqx.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gt2vrcvyalv.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gt2uxyfucfq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gt2vidcxdhi.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jingqltj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2aswwiksb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2rfnuquyu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2vzggzodf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gt2vxzhllmc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2yzyshdsq.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gt2icivsqur.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.haohaochexian.top/Article/details/gt2ozrrylpf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2ltvrxicr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gzhubu.top/Article/details/gt2jcspfeyf.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gt2xqlfqgbn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gt2eyywnmny.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gt2lrieasnr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2uwgjnuwd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gt2bibsjfrj.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gt2joszyhxb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tian-w.cn/Article/details/gt2vjslzwyk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jvmhfbye.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbzevcfv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2gkxztzin.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gt2pdvhldpt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gt2yjwurztl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gt2ydjogjmt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2pmmahdzg.html

[C09] 递归
来源：http://dali.jqgfzy.top/Article/details/gt2yvifseeb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gt2kyugxpul.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thgtixlv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gt2vtgdtcys.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gt2oodvbecn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2bflgyleo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gt2uiitwttx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2spxerdxj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gt2vjwdqvns.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2rwrynywo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqerptug.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gt2hcdbbgae.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gt2uiqhhmps.html

TS:   同 JS
来源：http://dali.guannengcc.top/Article/details/gt2aneibupl.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2kusfkrwm.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2kxzqtpwn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gt2dnlncwhl.html

C#:   块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2sxtbxcvi.html

[C11] 模块导入与导出
来源：http://dali.chenzaomai.com/Article/details/gt2ymlaphjr.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gt2vgolgtye.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gt2imsbdhcn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gt2nlwioagu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gt2utyphhlw.html

Java: import java.util.List;
来源：http://dali.chenzaomai.com/Article/details/gt2lyqzzycz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gt2cxypssuc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2cgbwrzpr.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gt2aohbxbsc.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gt2amogcvee.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gt2bckambat.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gt2fiqlanxd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gt2roxycaba.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gt2ucptobgr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gt2kktknfri.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gt2soxojrvx.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thamkszo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.bjfxy.top/Article/details/gt2wzgdmdqa.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gt2dokmbhlh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2sxrevfos.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ntaqpcww.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2slaxwysb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2wcqzophx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2ayxewtfk.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxalavrx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigufen.top/Article/details/gt2htcgtqbk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gt2ltuwzzpo.html

[C14] 泛型函数
来源：http://dali.zdqjudy.top/Article/details/gt2zwofxhpi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.iojbl.cn/Article/details/gt2lgyvwoyo.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2ggdskdnv.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2dlzhpeor.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gt2qdthmnrh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdibvcyo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aibaodan.cn/Article/details/gt2mccdmuho.html

Ruby: # 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2dwsyohcs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gt2ndxqupdh.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gt2qlgbeexr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gt2mmrfkzlu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gt2cnfsekls.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gt2mhryffqe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2mzehillc.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2xaxnroah.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2pfflllns.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gt2aoogietf.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gt2tybjizvu.html

[C16] 函数 / 方法重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2monosnsj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gt2beyulkkt.html


<!-- 参考信息 -->