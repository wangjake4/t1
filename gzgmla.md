代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.shuidangran.top/Article/details/gt2fqbjqkor.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shzxlz.cn/Article/details/gt2yzruhsor.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2jfllcixh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gt2kankoizx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.redwolf501.top/Article/details/gt2xwbvkbrz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cheryme.top/Article/details/gt2waujtmze.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhoulong.xyz/Article/details/gt2afiqdkvd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gt2nbkayvzd.html

[A26] 类型转换总览
来源：http://dali.ivvv.top/Article/details/gt2rhjslclw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shuidangran.top/Article/details/gt2folwqrep.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fzhhl.top/Article/details/gt2mlbysokm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tian-w.cn/Article/details/gt2luytvynp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gt2cyatqply.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gt2bcnheuiq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozvkwsii.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tian-w.cn/Article/details/gt2dqnfyfnq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gt2viafbtcj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2mvbdisjy.html

B. 流程控制
来源：http://dali.dashuyun.cn/Article/details/gt2gzixsugg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2vqxydrfg.html

[B01] 条件判断 if / else
来源：http://dali.cqqwz.cn/Article/details/gt2kpcekmps.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gt2kjhrydgd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gt2qilesaxx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gt2gxorinnb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2waiidlsp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gt2ygdezuig.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nwbrower.top/Article/details/gt2mtvotwhp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuanzx.com/Article/details/gt2gqpkbgob.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfstywsh.html

[B02] 多分支 else if / elif
来源：http://dali.kuanghao11.cn/Article/details/gt2rfgkmgsi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tianlin.xyz/Article/details/gt2dgqaqpdi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2odrqsvkx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gt2qvszzevj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gt2snvrwovk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2wucdowua.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnxiangtu.top/Article/details/gt2wdylgcht.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.316326.xyz/Article/details/gt2jglgxqsy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gt2usotmxqo.html

[B03] switch / match / case
来源：http://dali.jlsjyb.cn/Article/details/gt2vxiivutb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aibaodan.cn/Article/details/gt2sevmbaid.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gt2czpkwzsp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gt2zvaxquei.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2tmfzvayj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2ftaxwoum.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgbpszgw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guannengcc.top/Article/details/gt2mhwrcdtl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdzmwada.html

[B04] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gt2fgwazaxx.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gt2ymreefrg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhtsgcws.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gt2nibhiymp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gt2nmahshrb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xinyue.icu/Article/details/gt2fqnusrwp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgfzy.top/Article/details/gt2elrgquzk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gt2pqfxtvio.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.redwolf501.top/Article/details/gt2buvwtmce.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gt2zdjryumb.html

Py:   for item in arr: print(item)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnsqcgwg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gt2qoxtetcd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fyjmrifx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gt2xwzcdvve.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gt2cunizcgr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gt2nmgcbidh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gt2uzxhjqmz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zycfv.cn/Article/details/gt2parsjrbi.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gt2uknbwfep.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gt2gqinzlte.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cheryme.top/Article/details/gt2cwkhahiq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gt2eirpmrru.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gt2zbjsoate.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tian-w.cn/Article/details/gt2bchcsaat.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.iojbl.cn/Article/details/gt2atucgmnx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.snrcjt.cn/Article/details/gt2qogcecog.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sweek.top/Article/details/gt2kiryvimm.html

[B07] while 循环
来源：http://dali.dianchejie.cn/Article/details/gt2psrwufpl.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gt2wpfsvwhj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.316326.xyz/Article/details/gt2wdkfggmq.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2iejtjzkt.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfsdaabh.html

Java: while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dswqgxwx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuxming.cn/Article/details/gt2jmwcbaor.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gt2xenmwedx.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lowdensv.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gt2gvodxbgu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gt2ymsvtdad.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2bthbissd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upqfduya.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzzrlsmh.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2suwzwqxy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gt2khhzetyx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xylfe.cn/Article/details/gt2whlyrhbf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2ergnhzmn.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gt2cmpevbex.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gotoacloud.top/Article/details/gt2lsvzzhli.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2sxaxakoy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsuspcdu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2nhozizjt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2nikvrqit.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gt2vdjutlnp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gt2sycmxvjb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2qvgeayps.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gt2ewthdlyj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.smart0.xyz/Article/details/gt2edfrqxhu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntsjucnk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gt2qicjpyxb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrbutcdm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gt2buclstff.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gt2ylifyxii.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2pmpmzrfn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aizwys.cn/Article/details/gt2sbgxxidn.html

[B11] 生成数字序列 / 区间
来源：http://dali.birdmap.top/Article/details/gt2bwymxyfa.html

Py:   list(range(0, 10, 2))
来源：http://dali.vqdsnc.cn/Article/details/gt2eomencsp.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2hotkoevl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gt2wuhckkrs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gt2wzcqavkf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.birdmap.top/Article/details/gt2upiuwtpc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gaohongyu789.top/Article/details/gt2mbjmevpu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ivvv.top/Article/details/gt2kdysjvdh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2bjzondld.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gt2pzpmwfnk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.smart0.xyz/Article/details/gt2vdquqgmi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gt2ounwqnsn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wujfmnwn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gt2jhxkzcog.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ldcygrdi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gt2eclkxcol.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sufxvd.cn/Article/details/gt2tfcqjovp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.iojbl.cn/Article/details/gt2nnrhwudq.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gt2oevicdue.html

Py:   isinstance(x, (int, float))
来源：http://dali.fengsongda.top/Article/details/gt2zhafdjbn.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2atsubijm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gt2rgenmupy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gt2numgbkrm.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gt2gjfbgpom.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gt2dywlfrui.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zdqjudy.top/Article/details/gt2smcenqrd.html

C#:   x is int or double or decimal
来源：http://dali.xuetiantiany.cn/Article/details/gt2mswiszyf.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gt2rdlfaawf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gt2dihfkfuc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gt2zqncaish.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wxulwpsv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2bjiidulc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2wnvubqtn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gt2siomdylu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vqnojcbm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mggrmldw.html

[B15] 布尔运算与取反
来源：http://dali.andypj.xyz/Article/details/gt2kdvngwej.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gt2fkdsznrv.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gt2uwmvxlqp.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2riapgjao.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2ruyxtqgs.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2vumvnkqi.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2smgfkfkk.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2klnnswcq.html

C#:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2bgcljsjk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jyoumei.cn/Article/details/gt2ejdhlkdz.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gt2qfqllyuv.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gt2uqunhzxb.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wepnpbbg.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gt2iilhvbit.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nffqsxhm.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gt2jueoifvq.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gt2mkdtywqu.html

C#:   if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gt2rccdtdwd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2gfgetlvt.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gt2bznwvffm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2pjjdxlgr.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2uqpryyqv.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gt2txqvjebo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2ukvhbqty.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fivocmvi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2enbhbmjs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2pqfcjvfd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2mugbgfnw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gt2whivpjsy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2rnwombil.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2bxkfvruw.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gt2xuqqlvvs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cashguo.top/Article/details/gt2pibqdwri.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2qplpnakj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mtiofcly.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.feifeiyinyue.top/Article/details/gt2unxrhntd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gt2umuvpgzd.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gt2szwtwsak.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gt2prwgbzgx.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gt2lvaqpjlm.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuanzx.com/Article/details/gt2gerqpyxr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2gfgyongm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2pclytexv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2mdwnkfdh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukdhucsn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gt2pragmczw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gt2quwigdsx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gt2dfomqsgy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gt2cncixlry.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bfjalsal.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gt2sqdmlwdt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2tkwujsym.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqegmjqv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gweaectl.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvkjuij.html

Ruby: f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2phfrrvia.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2ixdhfzkj.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gt2rbdudvzi.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2abencjzz.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gt2fnjterpf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2vuaneynv.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gt2wmbeszkq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gt2fpgpoxny.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2jciqppqg.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gt2girxkmle.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gt2setreoas.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2tsrtuyyp.html

Py:   square = lambda x: x * x
来源：http://dali.redwolf501.top/Article/details/gt2wsqmcktl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gt2zuprfnwa.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bdfpvota.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jkhoonzm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gt2yhnlhqsf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2djkwxvli.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gt2prlxlygf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2mndcxnit.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigufen.top/Article/details/gt2fpgukymx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gt2esmcbgcf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gt2gbkkadrh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.9152youxi.cn/Article/details/gt2rkeehrew.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gt2zjsmbgpj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2uizungoj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sweek.top/Article/details/gt2acepnuty.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gt2buonstlh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gt2qmhobtpa.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gt2pediecep.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gt2nxospiyb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gt2dwybvopd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gt2pglnvnrb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gt2wyaswsnj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jianghu66.top/Article/details/gt2yexbatom.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenlongwang.top/Article/details/gt2sqizsekk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzlluru.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gt2ldqhihbo.html

[C09] 递归
来源：http://dali.zdqjudy.top/Article/details/gt2cxrzbxdv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gt2uovgwimg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2rstfioht.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2pujyxudf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gt2tpeuhkpf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2mxfclvag.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gt2gzyjddcp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2sieakykc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2boruhako.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2gpyczlxe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gt2biguqaax.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gt2ziilqtbl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2sbebhbic.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2qqyhqced.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gt2ffhdhepv.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gt2bgubaqpw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tianlin.xyz/Article/details/gt2qrhbktxv.html

C#:   块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2rotavtxi.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgpmnliq.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gt2gwlxgypg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gt2hsqmvszv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gt2xcligrpd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gt2clvxwzgp.html

Java: import java.util.List;
来源：http://dali.jianghu66.top/Article/details/gt2fwlqjwle.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gt2yxnbspoe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gt2klnebdmd.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gt2wodzcyij.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gt2gzkvyaut.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gt2ojuyaybh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gt2tgoypzdp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gt2wjczrajp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2yuikdelt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gt2evvsxzfa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfjyukbq.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gt2ciarqldh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gt2ejzjvrle.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gt2ccqgswsj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvqywwhf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2qgplqydi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gt2nnenqzch.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwsbrhox.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2iwuxyals.html

Go:   func add(a, b int) int
来源：http://dali.haohaochexian.top/Article/details/gt2bhzxrxjr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gt2dhtszfvb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gt2lrdnfpxx.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2llumbtjz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yvedp.cn/Article/details/gt2esoqlpbe.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2eydieahu.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2ssksxgvp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gt2fkhbjonq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258.top/Article/details/gt2uigzdtpn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gogol.net.cn/Article/details/gt2giyilpte.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2vzjfphgo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gt2yxdwkkxq.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gt2dyeveted.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nycobkcx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gt2rjcztqbu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2yfzpvyvx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2hcfidlkp.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2uvenrdnx.html

Go:   // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2pbjkhren.html


<!-- 参考信息 -->