代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fengsongda.top/Article/details/gt2obtcukej.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubqckxkn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gt2apmjzfgb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dashuyun.cn/Article/details/gt2mfxvgyeg.html

Go:   strings.TrimSpace(s)
来源：http://dali.jiagoushi.top/Article/details/gt2srbmvryj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fzhhl.top/Article/details/gt2apcegpex.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hysaishi.cn/Article/details/gt2fparktcy.html

[A25] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2frsrmyuw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tian-w.cn/Article/details/gt2ahfxqvxj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258.top/Article/details/gt2jrtsapel.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkdipuiq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hywenlv.cn/Article/details/gt2xktmnbtx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yongpay.top/Article/details/gt2iburvhlw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gt2croykqen.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gt2pdaiimht.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2drpksltl.html

[A26] 类型转换总览
来源：http://dali.hammf.cn/Article/details/gt2mpptvblb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gt2tosbyywt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigufen.top/Article/details/gt2dovrqatk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sysykeji.top/Article/details/gt2ppkdnbpr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.andypj.xyz/Article/details/gt2narmqaqa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gt2ymmeywld.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gotoacloud.top/Article/details/gt2xdhmdwca.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yueranfly.top/Article/details/gt2vuqshhto.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gt2tunewvvj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ivyoyrry.html

B. 流程控制
来源：http://dali.shzxlz.cn/Article/details/gt2gghljbrh.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wlbtyfho.html

[B01] 条件判断 if / else
来源：http://dali.yangfankeji.com/Article/details/gt2vwahrjtf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ppjwa.cn/Article/details/gt2fvoqbggw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxinkj.top/Article/details/gt2wveuhimc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gt2ykszetvm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gt2bkbypzcf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gt2tfixiogz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuanzhike.top/Article/details/gt2fpgbrljo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gt2godlkxfz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2bobcrmbv.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gt2zclakebl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ivvv.top/Article/details/gt2ninztago.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jianghu66.top/Article/details/gt2pnzdhbqm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2pikrsmnw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2tyzdbvtp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gt2jujkbiuz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigufen.top/Article/details/gt2hjwqvbem.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gt2kxtynnrk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gt2vscymmum.html

[B03] switch / match / case
来源：http://dali.jiagoushi.top/Article/details/gt2cplwjvnb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aizwys.cn/Article/details/gt2czzyhzou.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gt2ntatpuqd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fjzuvwlx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2brmzudod.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2rbukypsa.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gt2zrklvwmh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.mhx1999.top/Article/details/gt2vxfkddef.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuanzx.com/Article/details/gt2ewbupctb.html

[B04] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gt2hinmzqsj.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2qktvtwlb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.svipenyu.cn/Article/details/gt2nuectkkk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymbcxkjh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2ibzofegl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2lwyddtrc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gt2znbhlgcy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gt2tzhigypa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2kvucydqm.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gt2vofvygrn.html

Py:   for item in arr: print(item)
来源：http://dali.hfpthk.cn/Article/details/gt2pbgdibcw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gt2vshwdkqm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gt2ilknujrq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gt2hffclsdx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tanke756.top/Article/details/gt2ucunkazr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gt2nevbwkxc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gt2jsunfnag.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj202588.top/Article/details/gt2lrdoukpl.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gt2gemsdpqy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pveqpriq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yueranfly.top/Article/details/gt2xdcahide.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gt2voyzckwk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2tkjlwybl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gt2rnkekplt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.redwolf501.top/Article/details/gt2vcxbmdic.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuanzx.com/Article/details/gt2etydvqjy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gt2hjstvhhf.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujjurcrk.html

Py:   while i < 10: i += 1
来源：http://dali.ydzc1.top/Article/details/gt2jrlafvok.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2buidzpem.html

JS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gt2pilcwkgx.html

TS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2nerbawzc.html

Java: while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2xynntyed.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftpqykfg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gt2pldrfuxy.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2kgdppyza.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhkjhof.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gt2jqqyscnt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhdtlfcq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2vnkwospi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2ysgolqkk.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2jkzfvujo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2jncvowpi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxnhqxuw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2ggxzvwhn.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gt2sdahzipt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gt2fcyyvkwy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2dvnukgkc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2athhhxps.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2fxdtaqiu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2rbmqewxe.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gt2irmetblj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xaojinhq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2akpgotpg.html

[B10] 遍历同时拿索引
来源：http://dali.andypj.xyz/Article/details/gt2alkgmdrj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gt2wcyvatxl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gt2dstcpilg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2zzdpbxif.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gt2bkbxetlw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lfsmqflw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gt2zcwdoaax.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfeltlwd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ydzc1.top/Article/details/gt2edgehkkb.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gt2nwjoicra.html

Py:   list(range(0, 10, 2))
来源：http://dali.iojbl.cn/Article/details/gt2rgmsvqrp.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2ynfbdjmz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2aiwwuczy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gt2cuogcnub.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdostrie.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gt2yxqnbotq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ppjwa.cn/Article/details/gt2ltcwosia.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2zzrmyszw.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gt2bsdlsvwb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gwtinxmb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjezscpe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2sjuxlhdb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2ujpcboig.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ponugund.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jiagoushi.top/Article/details/gt2uxhafhnz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gt2gtvwkjbs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gt2hjpurbxo.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gt2tbweqwxl.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gt2brewwwwm.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gt2jpnnertz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gt2josvznxh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2kxxqivii.html

Java: x instanceof Number
来源：http://dali.ivvv.top/Article/details/gt2fchomcay.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gt2zwitcarm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gt2qjalviro.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeaoukwk.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnltcbhs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenlongwang.top/Article/details/gt2drsgbllb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvpcqyek.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2jvgjejec.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gt2lxxjkfym.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2fiwkyldz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gt2oxsdxxxj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gt2soksabsj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2cjhjamyt.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gt2wbzdzqew.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gt2ukoiizow.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gt2ogevgera.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2zovuucde.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrsczxdr.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2zofdqugv.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2qulyilhm.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2nrfryvmj.html

C#:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2ffjqpnhm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gt2cpdrvjuf.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbufyzyw.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxuanxn.top/Article/details/gt2xiqratsl.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2khwhbmtt.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gt2cybqhucn.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gt2ayqfwdom.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2avqgsgmp.html

Ruby: return if data.nil?
来源：http://dali.c1oappe.top/Article/details/gt2gcinraqn.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duprkyca.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2vxyruxgw.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gt2iemoovad.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ytivwfpj.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2umqvkgaf.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gt2zboryntb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gt2eeahftjj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2qyeixlot.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2kncfpyvr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2zjodxdae.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2pytymxfj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gt2spenajse.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhwkcsmv.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gt2vdiddkuy.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gt2pfxpwamn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gt2yleoupde.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gt2kitnfdzs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2ajbfikqz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gt2jzzozlnx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gt2bqfpqqhv.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gt2rxdibqem.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gt2cwioyrij.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gt2pwlfmfyj.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gt2ctmxnnji.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gt2zxcwgjji.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2blxsorqq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uiffwowk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gt2ydiiuage.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gt2rjsiirxv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gt2hgoqihel.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhoulong.xyz/Article/details/gt2snkwiexb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gt2crksench.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gt2ziezknte.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhengqikj.top/Article/details/gt2kackgvdp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbviynuh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gt2orrvhqrd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gt2fkjfbfuc.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gt2vgdzdkiw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hfzarymj.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2uwpkrkzy.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gt2jrlmwnis.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2gaiaorzg.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gt2epixjuqx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gt2evsniteu.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gt2xveqpjct.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gt2hhmkgyml.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2wyowrpjc.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2gbnctief.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gt2iqlkwtoc.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gt2zckrfusl.html

Py:   square = lambda x: x * x
来源：http://dali.xuetiantiany.cn/Article/details/gt2nztlcdxd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gt2orfecoym.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2bessjcln.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2caqbmxnt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqlpufur.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gt2hjppiffj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gt2bxcuthkw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2hjawretm.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gt2galhdybb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2ouqdegii.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2pfbebrme.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsujtmem.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gt2ggwmagrc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2estslvbu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gt2iqnpwmzp.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bouthqii.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gt2ievkluei.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gt2pwebutun.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gt2wpsmrfio.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gt2depkgtsx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2hfrxblmx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2zmumptdf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gt2rceowfqc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.smart0.xyz/Article/details/gt2aghwkpbt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gt2nakfjczy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2xjzictgx.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tihpjkzk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gt2vofpicsb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtvyofxq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2zmxixkyn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gt2xnsqzfyj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzgtizjo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gt2jorbhuqb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2ibqgxrfz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tian-w.cn/Article/details/gt2bvxxvlzs.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gt2emsgvwrl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gt2zpvjfsnl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gt2lzvwhxax.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2vmoocdmb.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gt2anbtqkma.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqpkimjl.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2flrripfk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gt2vxakawbb.html

C#:   块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2fsqycpys.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2dyyqpunb.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gt2qtyzhejo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gt2zsqycbtk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gt2fhimwrrd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhongyouzk.top/Article/details/gt2vwsslbre.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gt2jlutqqbo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gt2audtjnxg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gt2uothxvet.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gt2truumiym.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gt2ywtfbakc.html

Py:   (lambda: print("run"))()
来源：http://dali.wangdashe.top/Article/details/gt2atppspuo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gt2gnrmbhuv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2exfvjvjm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gt2oxzrpocx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnmmwrzj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gt2tgiwgaca.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvjdbunj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvspsrlc.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gt2yjpfqfma.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdbfukzq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wigrqinr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj202588.top/Article/details/gt2tovwimei.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2musliilb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2whpztyhu.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gt2kjwatnzg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gt2ravgwljj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gt2ghjzgwdj.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gt2hplclyoy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zggtwpbr.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2katwfrtf.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gt2owxqxfey.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gt2jedjwues.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tcdsnnvm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gt2ujixzuij.html

Ruby: # 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2navumdjj.html


<!-- 参考信息 -->