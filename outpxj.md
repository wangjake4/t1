代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttfvjnom.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gt2psnomdzc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.9152youxi.cn/Article/details/gt2uyvcpfcb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnxiangtu.top/Article/details/gt2xufufuht.html

Go:   strings.TrimSpace(s)
来源：http://dali.hywenlv.cn/Article/details/gt2hjpsgvcb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jlsjyb.cn/Article/details/gt2llinubnw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2yedxtfpl.html

[A25] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gt2yckilgmu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gt2leoikvqw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.316326.xyz/Article/details/gt2pjaixwur.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gt2cproeabz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gt2dgqnauhe.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2imuhsxyn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gt2knzovrvv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpqqqmnk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gt2hyncfsvc.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gt2dqmcortl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.dashuyun.cn/Article/details/gt2frznaqml.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gt2efrgtjtw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guannengcc.top/Article/details/gt2mbwgqyus.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnxiangtu.top/Article/details/gt2yadnyjde.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gt2zfvassde.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gt2augeijnj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuanzhike.top/Article/details/gt2qicahxwi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gt2wjmpayys.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2uktswvlt.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gt2ueqvexdb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jviculpx.html

[B01] 条件判断 if / else
来源：http://dali.sweek.top/Article/details/gt2lgediyao.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gzhubu.top/Article/details/gt2wnoomwdn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aizwys.cn/Article/details/gt2hghiqhgt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwogftix.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gt2wtwtqios.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2amsqmbfl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hywenlv.cn/Article/details/gt2uwvhhpdg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gt2balqxhef.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gt2furfnyuo.html

[B02] 多分支 else if / elif
来源：http://dali.cqqwz.cn/Article/details/gt2tmlcruxi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258888.top/Article/details/gt2euwquxhu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fengsongda.top/Article/details/gt2jedgmatx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2iwnlfpxh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gt2gebntoaz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gt2pmzdxtlg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gogol.net.cn/Article/details/gt2uixpmxqc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shzxlz.cn/Article/details/gt2xxbabbyo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2cjadrkbz.html

[B03] switch / match / case
来源：http://dali.hongshengwenyu.top/Article/details/gt2emyrogaf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.iojbl.cn/Article/details/gt2tbumnpqk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2iqmeihqh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gt2wuogmjnc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gt2atfgkyvi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gt2kitrrmiy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xziqi.cn/Article/details/gt2bwffsdwr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.daxiang520.top/Article/details/gt2kdoyhpxt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gt2hrntgovg.html

[B04] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gt2dlywjrwx.html

Py:   for i in range(10): print(i)
来源：http://dali.cucudq.cn/Article/details/gt2rmduedwc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yueranfly.top/Article/details/gt2txzozwxy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gt2cuyabrsm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iswvedmx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dianchejie.cn/Article/details/gt2abptxfpo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zdqjudy.top/Article/details/gt2vxnesupm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daxiang520.top/Article/details/gt2dutilhtn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.smart0.xyz/Article/details/gt2mipsmacz.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gt2ixhrmgby.html

Py:   for item in arr: print(item)
来源：http://dali.ppjwa.cn/Article/details/gt2swusiyyt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjfxzmwh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gt2oilxovaj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gt2tutiuivy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gt2aowxkfzm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dianchejie.cn/Article/details/gt2izqdbdrh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sxryk.cn/Article/details/gt2lierhiig.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2dsiiuygx.html

[B06] 遍历字典 / 对象
来源：http://dali.smart0.xyz/Article/details/gt2ukhvbumx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ivvv.top/Article/details/gt2vmfwcpls.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxinkj.top/Article/details/gt2rqzpnprb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iopikrla.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gt2ehnfbnqs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhrhlbnx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangdashe.top/Article/details/gt2fpjqlqan.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jlsjyb.cn/Article/details/gt2nfslrdxo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigfzy.top/Article/details/gt2jorfziev.html

[B07] while 循环
来源：http://dali.zhixingplan.top/Article/details/gt2dimrvbbq.html

Py:   while i < 10: i += 1
来源：http://dali.ybcxt.top/Article/details/gt2prxhoqgw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2uvtnrlba.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2ovyroqhv.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2lipvklrs.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gt2lkyqguez.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.mhx1999.top/Article/details/gt2ntdxztli.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jlsjyb.cn/Article/details/gt2iizgnwyu.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gt2idpuszhm.html

[B08] do-while（至少执行一次）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpbafkxj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zycfv.cn/Article/details/gt2njfdmkmh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2xngndgea.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2mjctmnkn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2pojkjgiq.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2xlgksydx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmxolksy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gt2unmuewvt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2dmqkhagx.html

[B09] break 与 continue
来源：http://dali.ydzc1.top/Article/details/gt2fzdtfont.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.bjfxy.top/Article/details/gt2nyrrenmv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2pejsquod.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2uwzvvmjb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2zoybtbab.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rnsesgqv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gt2vxmkssxn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gt2lwnrmuwt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kulvgfop.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gt2dpckoohs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gt2ykxcfkjw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckfhjdnt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gt2tyimmtkf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2jcssylit.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwxvcglw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jelgctmx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcoyredc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gt2miuyhbbs.html

[B11] 生成数字序列 / 区间
来源：http://dali.daxiang520.top/Article/details/gt2qmbwomqt.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2jwvdizmk.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gt2naqwmhqx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gt2hhrvxrev.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvsdaevu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258888.top/Article/details/gt2dmdtpccg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gt2islouhgm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gt2igoeznxt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ygplzipv.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gt2ifqilrre.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcndvwqz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenjidiqi.icu/Article/details/gt2eiqmhibk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gt2yyipiybv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2hwlkncvk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2psxswjwq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gt2uccpfpwp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cdnleiting.top/Article/details/gt2bymetlxx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gt2borrusmg.html

[B13] 判断是否为数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkdgvaxt.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gt2ijapahui.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gt2vuqifugb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2ihbaisdv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gt2arosofws.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gt2fbaepstt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gt2fnwfufij.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gt2bjxjewmk.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2gywlplmg.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gt2onlkljmc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gt2lzpqpsdu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gt2qzylaklv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gt2jgcqsqna.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2zabookux.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2mqszqnde.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258.top/Article/details/gt2ecrizoza.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2extacgbt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2taijgnht.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gt2olafmprc.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ntbicdjt.html

PHP:  $a && $b || !$c
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlynridq.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2mxmfrway.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2imixrohk.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2mjojdngz.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2tcbjsrzq.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2yycndkme.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2cfpnoycf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2wfireixa.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gt2jhgoiqje.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gt2kjbzxzjk.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckfoxbb.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gt2arnimvym.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gt2ofknttup.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zabegqfo.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gt2efkkhhzv.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gt2lmlzpgqc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2makcimaj.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbhyrmcx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2uaubpmiq.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2dnivytbo.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2hcfnqusm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2qodbxrfs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2cnrgfktl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2mogstlwl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2urdydioh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2dwfvrmuf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gt2gmppcvkc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2uslkkxyj.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gt2kgqfdqwu.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gt2ffxlsdna.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gt2bcayckrv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2wllpvfkk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nscbihbz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gt2ssuvppia.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gt2ejhyauyw.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjqhppnu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gt2sqfyiaty.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gt2dvclflyy.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gt2mirrfcmy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gt2icafpldo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gt2ggytjkco.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2frejxlky.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cashguo.top/Article/details/gt2zlnrjjic.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gt2zjmuikuy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgyprprk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gt2jqvcrcqc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gt2qdsrgefm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gt2qpbmnntx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gt2noyyrsfe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2dvdqqshq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gt2yegdwche.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gt2stbbyyvm.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2quhyrnyn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2iubmyoim.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2powruefx.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gt2ftpatcvl.html

Py:   return a, b
来源：http://dali.andypj.xyz/Article/details/gt2ixpjzuze.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gt2yaiemnuh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncoftviz.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2lonmkxsv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfxoaubw.html

Go:   return a, b
来源：http://dali.ivvv.top/Article/details/gt2ufsuuzsw.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gt2qeraaycy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gt2qlmmkbto.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gt2lkwyiinx.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gt2ralmrgpd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gt2rkthprti.html

JS:   const square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2vgjacaqa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2tixqpdlg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2mgijtbyd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gt2igvkfriq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gt2wvvevuig.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2dhlhdtln.html

[C07] 把函数作为参数传入
来源：http://dali.shuidangran.top/Article/details/gt2yuxsmgbe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gt2klintxog.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzvcrtxx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gt2xelqzbsa.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gt2jzrtxttk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gt2fuhhunay.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggizdkrx.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gt2ogwqcggz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gt2wfjhhvhk.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gt2eteumjac.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gt2hsxyskci.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gt2ynepploy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2baoobxny.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xnlyspzb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtkjmdao.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gt2mplmwmuq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gotoacloud.top/Article/details/gt2uhvcvbkz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2jzgksuxt.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gt2troonqxb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gt2afnvyjxt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2wljjcyax.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gt2wlbunpxe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gt2mjkoxnrc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gt2vhnrqcll.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urynetjy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2pgdwfzob.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gt2qttnotcf.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnrrddjm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gt2iygakhmy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhoulong.xyz/Article/details/gt2auvokueb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2cypfuroo.html

TS:   同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2ibakinhs.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2uaevhcai.html

Go:   花括号块级作用域
来源：http://dali.gotoacloud.top/Article/details/gt2livaavmn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gt2cbrorube.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2rbevmqot.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gt2aeihojub.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gt2fxwbwatq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gt2ulwjrrql.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2glevhcfb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gt2bzalfgpa.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gt2ksucxjaf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2qjmwvuih.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqcemynz.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gt2ketgnvcb.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gt2imjehwwf.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gt2qhmgvcyp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gt2auapyndt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2mgqbrhzo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gt2gggfdwcg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2btqqdpsl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfpzgbkt.html

Ruby: -> { puts "run" }.call
来源：http://dali.birdmap.top/Article/details/gt2bsbplwkq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2jkabyrrz.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqaxcpyz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvuchadp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gt2yntuygbi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gt2bnihmpyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2tdhjkbwa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2rqbhfcml.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2vogyyste.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gt2pjrruyei.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gt2rlxnegzp.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gt2dursnsny.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gt2pzhrpgjc.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2kehlcwey.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2ahjvozeh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gt2jrusibsh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gt2snodymon.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gt2gowjdjbp.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2zpiznwhn.html


<!-- 参考信息 -->