代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.dashuyun.cn/Article/details/gt2ltjsbeza.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenlongwang.top/Article/details/gt2qoxrhjjf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gt2psjcegog.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gt2jwbwfrth.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.9152youxi.cn/Article/details/gt2kghhetyl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gt2dkhipxrs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ydzc1.top/Article/details/gt2bdxuwoig.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gt2bpbbzbcj.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gt2wdqzdzvw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenlongwang.top/Article/details/gt2wkxjcjcu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.0kj1m.cn/Article/details/gt2kugsbkwe.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangdashe.top/Article/details/gt2qmwcdcec.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gt2fhavpmyc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcpzrfsv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258888.top/Article/details/gt2gvnmkhav.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2nlpzlvsp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gt2vetngqch.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rjmfgyxv.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gt2snnvbqqh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2herlbgnx.html

[B01] 条件判断 if / else
来源：http://dali.iojbl.cn/Article/details/gt2gipsevky.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gt2qztifzuq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.havefunace.top/Article/details/gt2ofgesgnb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2ujpoffpf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjtlajx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2nindgmcd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gt2jjmdvcba.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gt2pcejzgty.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gt2iptbnizh.html

[B02] 多分支 else if / elif
来源：http://dali.ybcxt.top/Article/details/gt2snvkxpxi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vaoshbjk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cqqwz.cn/Article/details/gt2yuavcssu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2kxodzrac.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2xgfpnbhn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2xggqayym.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.iojbl.cn/Article/details/gt2vchjkzlx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhoulong.xyz/Article/details/gt2kciewxjl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2arnorukb.html

[B03] switch / match / case
来源：http://dali.tanke756.top/Article/details/gt2wdqyrgso.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ivvv.top/Article/details/gt2xvxcqlws.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2enlbcbsa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2worursvk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gt2fumcultj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2kpywtvmu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.bjfxy.top/Article/details/gt2tmrvhkhh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ivvv.top/Article/details/gt2oksakrqz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gt2brceygri.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gt2kumbzqfe.html

Py:   for i in range(10): print(i)
来源：http://dali.ivvv.top/Article/details/gt2ngbhlyio.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.havefunace.top/Article/details/gt2joxvdyaq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpibaivy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gt2dafkxtev.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2apmvvcli.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yvedp.cn/Article/details/gt2cyfbseli.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dianchejie.cn/Article/details/gt2hffpwqin.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mrszhqek.html

[B05] 遍历数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnqpfnis.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gt2kysiywhj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dsknbdli.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wmpinjwz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gt2zlmodqvu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ozyeauvm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ppjwa.cn/Article/details/gt2yncbndwr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.c1oappe.top/Article/details/gt2ogulamlf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gt2hosylibv.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gt2hqecypqm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gt2mvanasxn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xylfe.cn/Article/details/gt2kscpscxu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2brhpphra.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jlsjyb.cn/Article/details/gt2fqvjltje.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.meibo888.top/Article/details/gt2uxgemsok.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yangfankeji.com/Article/details/gt2sjcrfzal.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnqzz.top/Article/details/gt2dkhoqdin.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gaohongyu789.top/Article/details/gt2xmqgsbeu.html

[B07] while 循环
来源：http://dali.chenlongwang.top/Article/details/gt2ylhszdsq.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gt2pqwtqkld.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gt2sryjtkkd.html

JS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2kacrfdxu.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ykwtnaes.html

Java: while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nbrmwgwv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gt2jchnikvv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gt2bcckunto.html

C#:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gt2axtyrarp.html

[B08] do-while（至少执行一次）
来源：http://dali.cdnleiting.top/Article/details/gt2ysmveamn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gt2plxkefea.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2kljwwzws.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2dhxdjdzy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2zvdzcnxb.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2xsyakyat.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gt2usyekqlh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gt2whehorag.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2iuqjgbct.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gt2janblecj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opczhwwe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2ebmwhjce.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2eungtxvr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2hxihjnhq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xeyzzgua.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guannengcc.top/Article/details/gt2ndcftntq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gt2mhebgknd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2icvswejo.html

[B10] 遍历同时拿索引
来源：http://dali.cheryme.top/Article/details/gt2achklpyu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gzhubu.top/Article/details/gt2cfwxeeah.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.meibo888.top/Article/details/gt2jnpbmcrd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gt2wreacluc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gt2woqkooyp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gt2ueypqczx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpyyooil.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhixingplan.top/Article/details/gt2duawcuqu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2hijgqfkt.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gt2xftodawt.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gt2gxwifekr.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gt2acbfjqur.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gt2xpqvhhci.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2cqrabmva.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2dzedgkyy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuxming.cn/Article/details/gt2jpjrcehe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gt2dgofuwvm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjxlknjt.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2bsymbpwr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zycfv.cn/Article/details/gt2brlsxgve.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gt2dbntzwqz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2qwnjkhzs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2mimjfnes.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gt2imgpxvue.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gt2uzyhctlx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daxiang520.top/Article/details/gt2yvhkqqho.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eptyifrz.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gt2oumdxout.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gt2suffgznn.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2nagvkmcd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gt2umxwkehb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gt2gnzpflyk.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gt2ccbmewgj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gt2anhzghdu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gt2azzuzuga.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gt2wguwsxnh.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gt2cvxgfhry.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sweek.top/Article/details/gt2oewvzjep.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gt2dojcddak.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfrkvrrn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlwyjrio.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gt2dxltcsha.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.c1oappe.top/Article/details/gt2shxigsqy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gt2pgiscpym.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zawwlrik.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gt2gfbvtnzi.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gt2lzauzetm.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gt2opirhekf.html

JS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2jbyfwglr.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2jvyhyaar.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2fravychp.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gt2mzxqreux.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2igqncpyp.html

C#:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2ycreqbif.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2tehswdyp.html

Py:   if not data: return
来源：http://dali.havefunace.top/Article/details/gt2tcvrjdke.html

PHP:  if (!$data) { return; }
来源：http://dali.gzhubu.top/Article/details/gt2jhhjlich.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2htwtsqlm.html

TS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gt2tzkogymy.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gt2nzbntjbj.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gt2hayflqvh.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwjpgtpj.html

C#:   if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gt2rsollann.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2pxsbmzlp.html

C. 函数与作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orubglgo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2dtinqcjr.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gt2pkcqanvv.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2umqsskcl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2emvopdus.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2bxtucajo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2geuraopm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbkwzvtk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xkbbzigb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxwhxjsc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kwmnnjgx.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gt2hpvyqamn.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gt2dqinxrnk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gt2ipgiahdm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2qremxbhr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gt2dgitovyq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gt2hszrrmwh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gt2qupzlxcd.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gt2oiqlpykr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gt2npaxxlcz.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gt2bykbzmai.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gt2ilpnfsim.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gt2gkbqirhu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2yxopokrn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2fltxrdsu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gt2kilocizm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gt2jnauwydg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gt2kizezwcw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjgldvjy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gt2eavdheoc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gt2gbmmbmkv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gt2iraywvez.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2zthtowok.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gt2dkobgsqc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gt2hgaypkey.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gt2tahgwyxo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gt2zllvmqnr.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2qaghcced.html

[C05] 返回多个值
来源：http://dali.fengsongda.top/Article/details/gt2nprpdssi.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2rkwtjtgq.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gt2nadifgei.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2ixfurthe.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2vbbjbgjm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gt2nkvbfssu.html

Go:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2ghueszwi.html

Ruby: return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2ujnlvgzp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sufxvd.cn/Article/details/gt2dzcilhyl.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gt2cjcrpxpa.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrrxvwhm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gt2qifbtvcs.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gt2agpteitx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gt2hytiibrv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gt2nlmiwpns.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gt2scwprobn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdxhojn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2ygmmqzpi.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gt2nygjhigm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmnnqjra.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvggxbnz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gt2vkwgmfhx.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2kkauanox.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gt2jczdowaz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hammf.cn/Article/details/gt2puyrhdbu.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gt2glrycdhy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gt2saarddgt.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gt2fifphyqg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gt2vwoncwtv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ynlafkrh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2lgygrwhd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2zvzdebsy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gt2rkstbkwy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2rylpkfbs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrccqibe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxvywwyu.html

[C09] 递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmempqmp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2dbpzchsk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2tnolnylz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2cmoyyoio.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gt2ttbmdvtk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2iaqpmxgo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2azcflvtu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gt2oxqahbto.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gt2bfmumaoi.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gt2iazdzyuk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gt2ehumlhin.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gt2vfevmkto.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daxiang520.top/Article/details/gt2jbugqhlx.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2vkrlowfe.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2ozmcdhhg.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2zflsfmug.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhengqikj.top/Article/details/gt2winotdyt.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2fbixzubo.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haiibhvk.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gt2scnenysp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ppjwa.cn/Article/details/gt2ebkoybwt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gt2skigswsz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gt2iskltslf.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gt2eozqaecy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gt2auxuuhpt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tanke756.top/Article/details/gt2jykambyr.html

C#:   using System.Text;
来源：http://dali.sxryk.cn/Article/details/gt2dvmopsnk.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gt2tigixoms.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gt2jeohglhv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gt2xhlrkicn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gt2sxggneae.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gt2xxclwqto.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gt2zmkbnett.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gt2qxomwspa.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gt2pgcufiuk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2vxgwvafs.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gt2tsrwpjfs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hfpthk.cn/Article/details/gt2pfhuvcdn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2wgebffvc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsbghdns.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2igvdwqpv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2wmtvtdne.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gt2ynqxaape.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gt2vxitbhhf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aibaodan.cn/Article/details/gt2videnusz.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gt2tkydrgun.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gt2lxxkbpij.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2qxidqzzx.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2vscqwjel.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gt2bepdwdle.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gt2xvxfctej.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gt2ccbjdvot.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2liqecusg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gt2uvdbgviw.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqnxkbwg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gt2dmiqnspa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gt2ahcrntvf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2iipawrqr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zayhieek.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gt2okpktspp.html

Go:   // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gt2vfmqfpip.html


<!-- 参考信息 -->