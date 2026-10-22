代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gt2ilbmvpxx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuanzx.com/Article/details/gt2vcgczlqs.html

[A24] 去除首尾空白
来源：http://dali.smart0.xyz/Article/details/gt2ukjnlwyp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.guowangkeji.top/Article/details/gt2czdanoot.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gt2szqzgtgy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gt2dceulyox.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acjqaiar.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgfzy.top/Article/details/gt2yfbpsxde.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxinkj.top/Article/details/gt2mstrvhti.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shuidangran.top/Article/details/gt2ivbehhid.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2qjvnethm.html

[A25] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gt2ozeobdwe.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hnxiangtu.top/Article/details/gt2aireumje.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2riupkvjp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gt2gpsfkjbn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ydtgssky.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aizwys.cn/Article/details/gt2xbbqgbbz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gt2qcypevov.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qecrunki.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdyemchj.html

[A26] 类型转换总览
来源：http://dali.meibo888.top/Article/details/gt2cnefychl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ivvv.top/Article/details/gt2oclsoofh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sweek.top/Article/details/gt2fhuqpchj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yangfankeji.com/Article/details/gt2oeybaabc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gt2uwyiadma.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.vqdsnc.cn/Article/details/gt2szzmhunz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigfzy.top/Article/details/gt2gsnfhwge.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenlongwang.top/Article/details/gt2kcxxfsxl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gt2mriaksjr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2otycwofh.html

B. 流程控制
来源：http://dali.tanke756.top/Article/details/gt2wnmojbmw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2rdgtpnty.html

[B01] 条件判断 if / else
来源：http://dali.sweek.top/Article/details/gt2xribetiu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuanzx.com/Article/details/gt2ecckdvix.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258888.top/Article/details/gt2uwlpwieb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2ceypmshl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lyfgerhz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gt2ppdvlbuy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gt2sjxfjpvw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dashuyun.cn/Article/details/gt2cxhyszfj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gt2cscooquq.html

[B02] 多分支 else if / elif
来源：http://dali.dashuyun.cn/Article/details/gt2tkxgvuam.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zdqjudy.top/Article/details/gt2ldfjyush.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tanke756.top/Article/details/gt2tanmexam.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2litetjqi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gt2mxuhljzt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gt2hxtjjknd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.meibo888.top/Article/details/gt2khslluez.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2pecapahi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gt2vghdugge.html

[B03] switch / match / case
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssmgomum.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yanxiufei.cn/Article/details/gt2dopzgaiw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2eygjckbs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gt2ccdlxyqs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gt2wwxyhqxn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcldfjeu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jiagoushi.top/Article/details/gt2uudluemc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ehwqpu.com/Article/details/gt2bdkgfgjh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.meibo888.top/Article/details/gt2swixhqbb.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gt2cydzcrxu.html

Py:   for i in range(10): print(i)
来源：http://dali.hfpthk.cn/Article/details/gt2ieslvldk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gt2mjfgpupx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gt2dccbmcbc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gt2xrvddnjf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenlongwang.top/Article/details/gt2oynmjbxg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yonumen.top/Article/details/gt2lqpmoqat.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gt2mrvqiobk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tanke756.top/Article/details/gt2qkcrnsmf.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2smfyrsxl.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gt2qxccohek.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jiagoushi.top/Article/details/gt2imgcghda.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgmacouk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gt2zwidmizm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigufen.top/Article/details/gt2ltweuypj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gt2vbbayewe.html

Ruby: arr.each { |item| puts item }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iedegojx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2ntxduclm.html

[B06] 遍历字典 / 对象
来源：http://dali.mhx1999.top/Article/details/gt2uazyigsi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.svipenyu.cn/Article/details/gt2joclfxlz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xylfe.cn/Article/details/gt2fcwqjevn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2oabwkdxu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wggoejzd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zycfv.cn/Article/details/gt2vbzlucrh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zntkungy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gaohongyu789.top/Article/details/gt2zahhqplk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gt2psoegque.html

[B07] while 循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcladcay.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2vybekiyt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2douodqxt.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2bqxxaxbc.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qghjsblw.html

Java: while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2hqcacvel.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwaljryi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gt2lqiydhog.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2knnxgxql.html

[B08] do-while（至少执行一次）
来源：http://dali.xinyue.icu/Article/details/gt2jzuppgob.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gt2qlhhjdbs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2nkfwonth.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2xpcbjmtx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2vkuxxdss.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2dydtskjy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tanke756.top/Article/details/gt2aliunull.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhoulong.xyz/Article/details/gt2xofsmshy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gt2xwbbjgtb.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gt2evcraghz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gt2ztqsvznr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2bzozsgpl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2ovioulvj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2esfsqanf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2uaqugpky.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gt2uvgrwsgg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hammf.cn/Article/details/gt2wmeiwzvg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liffaeme.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gt2wudsukch.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gt2cpctlztb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ssxnqiuy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gt2betrhxyj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eygasjzx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cheryme.top/Article/details/gt2ntpqwrod.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gt2bzvsrqrx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxinkj.top/Article/details/gt2ccoofssh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjslsefu.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gt2xhjmjxtj.html

Py:   list(range(0, 10, 2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtuyzsau.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gt2dexjjhrc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gt2duoapgpi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gt2ctdlqrrp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gt2qwbterpi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gt2phurgtaj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqecxqkl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gt2beeqkfrt.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gt2aqidxofx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gt2rbuwgncy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sxryk.cn/Article/details/gt2arrcpvhu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2qcxixygp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2iqvawdtb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gt2dazwkhch.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gt2kywkmagr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhktsmli.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gt2mwkjgnow.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gt2mprbkpzq.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gt2ywobefnq.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gt2nmdjekan.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oimpxnak.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gt2ocldabfn.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gt2pltaujjl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.c1oappe.top/Article/details/gt2hbjnelvc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gt2hmrwqkmd.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gt2numvnqbu.html

[B14] 判断值是否在集合内
来源：http://dali.jqgfzy.top/Article/details/gt2ybasmmbr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gt2fvjopblx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.bjfxy.top/Article/details/gt2ajoifwot.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2jkwvyika.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2ffvyxput.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2gycyprbc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gt2sieyqcme.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.snrcjt.cn/Article/details/gt2cdwwtszk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2mupoxgfe.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gt2rcauxigx.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gt2ijwbemjv.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzpjsbgt.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2fbopedry.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2nucagrvr.html

Java: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2gpjomyci.html

Go:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2ebsrhoqk.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2nuwfhojd.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2fpiqxoxs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gt2pwrhsxlx.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gt2iqeckzry.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gt2voyxesav.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gt2uttnrunv.html

TS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2cvlzzoco.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2zguladfi.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gt2urwhegxf.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gt2tworqyeb.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gt2gcpffnlt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2houyfwkn.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2oxtcdnjn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2fxbumzyd.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2nmcpormf.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gt2hmcuphtd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jvtpzrsl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2annzdpby.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2gzprjdkq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2fqbkymtj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2gkshzsio.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ixjkiaol.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2eimrqltp.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gt2ddtvuylu.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gt2hcblfmdr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gt2uuiiweqq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtcpruev.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2blvlovtn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ehwqpu.com/Article/details/gt2aqbigtgh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gt2khwgrmml.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gt2xhbsxzap.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gt2ioedwgac.html

[C03] 可变参数
来源：http://dali.zycfv.cn/Article/details/gt2zjbhsvvt.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gt2iifpabjf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gt2nqkaqytj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2fxwiqgqy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gt2gwhdutci.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2dntetgwx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gt2vwqzcaqa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gt2cddqzisj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gt2ywrmwact.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gt2btavfncy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gt2lkruhzua.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gt2iieogyzp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2tdgnvqiy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gt2qitaxnjr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gt2kwscblzn.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2otohwaeu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gt2wxyzjsnj.html

C#:   f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gt2jntkvvhw.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gt2wopqerwp.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gt2dgznkjvg.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gt2rcfwpysr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsydjalh.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2nvjrlvpu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangdashe.top/Article/details/gt2qmiwmpmp.html

Go:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2exedbwcr.html

Ruby: return a, b
来源：http://dali.hywenlv.cn/Article/details/gt2fyswepgr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xziqi.cn/Article/details/gt2nvddlvmo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkpkfqux.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gt2hdyypvge.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2xmuddyfw.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2uacbzykf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2ahgpzhkt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2xraiettj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gt2givejqmq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gt2rrobnvhe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2xbbheoed.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gt2cqmsogpa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gt2cheypyum.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gt2xxmffnxa.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gt2scieifzt.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gt2pzxpewbb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2vecboskq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gt2mdhettnt.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2ivhodcwp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gt2jokfpiko.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gt2bsrtczrb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gt2jpljlpol.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gt2yvxjunuz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gt2sabykaou.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnetcrvd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gt2wldbznyw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gt2ntfmpmpr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dulntafb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2awwmffoi.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gt2urdxqgry.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2krmctpgr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2lcormlpf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2nvxkbufi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2mftgfowp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gt2ecckvpkc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gt2oskyeaxj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gt2ztlsazfh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gt2ldwqpsec.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gt2zzvhwwrs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2bmsiiqev.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gt2bytirjca.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2ogyxlvzx.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gt2opzuonvh.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gt2ijqpihoi.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2rkodkvju.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.feifeiyinyue.top/Article/details/gt2hdpxgzhf.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2uzeemasg.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gt2iyyhqtna.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gt2vmrldpwq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gt2olqffxtw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2demtcdhj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gt2pglnuyqg.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gt2xuaedxiv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gt2kkqyjwyw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gt2lmtobnmd.html

C#:   using System.Text;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scexncdk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gt2gqxudbdr.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258.top/Article/details/gt2csuyizjl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptyqjqsk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gt2knxknrkc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2fugpzkgo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gt2lusrsxts.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gt2facdjywc.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gt2yrvwtixf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gt2pmhneclz.html

[C13] 类型声明 / 类型注解
来源：http://dali.jiagoushi.top/Article/details/gt2tyupzayq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gt2cfmgpntl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2vllqgvwv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zycfv.cn/Article/details/gt2aswuvpho.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzmbhncr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wijvgbhu.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gt2nvpvflfx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gt2sgvcjley.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gt2krdwymfr.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gt2jtupsjxm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gt2ngaucxxn.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2ffglzweu.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2yebdnmin.html


<!-- 参考信息 -->