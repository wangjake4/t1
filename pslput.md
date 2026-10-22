代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuanzhike.top/Article/details/gt2upkzxdrg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gt2phbjpysm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gt2bqodxraa.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hfpthk.cn/Article/details/gt2wxiwfehe.html

Go:   strings.TrimSpace(s)
来源：http://dali.ehwqpu.com/Article/details/gt2nnumcndz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hywenlv.cn/Article/details/gt2puemigqb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zycfv.cn/Article/details/gt2liiaonld.html

[A25] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2sjonhyba.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhixingplan.top/Article/details/gt2odbczhbv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ydzc1.top/Article/details/gt2tixkaaxk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hfpthk.cn/Article/details/gt2agoturcr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gt2srczbubj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daria6918.cn/Article/details/gt2tkmjdpkj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.snrcjt.cn/Article/details/gt2smqaomqy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258.top/Article/details/gt2hlqxrmph.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2netarmkb.html

[A26] 类型转换总览
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdmyoouy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258888.top/Article/details/gt2mecarjpo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ivvv.top/Article/details/gt2jkjsfqof.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhoulong.xyz/Article/details/gt2vdymcjgx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aibaodan.cn/Article/details/gt2aazaixla.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gt2fvoifjqh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gt2tccpchss.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gt2ryjkjmry.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gt2bgazrcli.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixdinqjv.html

B. 流程控制
来源：http://dali.ivvv.top/Article/details/gt2gbpaxcoj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2gwyltsoh.html

[B01] 条件判断 if / else
来源：http://dali.xuetiantiany.cn/Article/details/gt2vuiqzbpd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yueranfly.top/Article/details/gt2vaaoyjkj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zuahckrs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlpsvjjc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkpxczhd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gt2ksulmuns.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhixingplan.top/Article/details/gt2mjanvxdf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yonumen.top/Article/details/gt2fvvkidrf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gt2ogvlnzsz.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gt2bambbeoc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.redwolf501.top/Article/details/gt2tnvvlhqv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hfpthk.cn/Article/details/gt2mqkbjnuy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2rmfsagtw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gt2iryltpvg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2uqlzpnyv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nwbrower.top/Article/details/gt2qprfhrao.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gt2yrmdjinf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2evppexyw.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gt2qpntjnev.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuxming.cn/Article/details/gt2tozmybyq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2sjdkyqll.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gt2ljublxnm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gt2bwtybnlk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ynlaxnro.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.andypj.xyz/Article/details/gt2vlwrjeax.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aizwys.cn/Article/details/gt2pxlkoibl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gt2jpyvmsxx.html

[B04] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gt2brhuduub.html

Py:   for i in range(10): print(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlzqdnht.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuanzx.com/Article/details/gt2zukwvgjj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2gyermreh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gt2etdnjxin.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2yujrfrta.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daria6918.cn/Article/details/gt2gtqvgsyq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hozsimaj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gt2gonrqlga.html

[B05] 遍历数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gt2mhmkqwmn.html

Py:   for item in arr: print(item)
来源：http://dali.0kj1m.cn/Article/details/gt2thohofny.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gt2yzkjpvsi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gt2ecpleypi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hjbizjgp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuxming.cn/Article/details/gt2oaoixpdj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gzhubu.top/Article/details/gt2osofygru.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbhxymoz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivitgqcq.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gt2dwiboozi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuanzhike.top/Article/details/gt2rmvynkhy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pycfn.com/Article/details/gt2emapvdqf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nvzsjplr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gt2kvqnkuck.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2xpmpwfgr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pycfn.com/Article/details/gt2zhdkpctn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nekpiwhi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aaqkdioh.html

[B07] while 循环
来源：http://dali.sxryk.cn/Article/details/gt2fuuqpztp.html

Py:   while i < 10: i += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2ddnogbfb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cheryme.top/Article/details/gt2olvzxxyp.html

JS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxkyebxc.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2obaisvyt.html

Java: while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2emlabhpi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.316326.xyz/Article/details/gt2impolrrq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gt2qajslkkb.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hkuhwilb.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gt2bdchxmjs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenjidiqi.icu/Article/details/gt2xpphyqyb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fseqrkxl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2ojvnznsn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2rpnsjyje.html

Java: do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2oketzxqn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qolinbfd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gt2dismwfii.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2jyircygx.html

[B09] break 与 continue
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmwrzygz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnqzz.top/Article/details/gt2lmocxfuk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2utwpbzhf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2jfnxxzzu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2uynugbhz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skrzfneu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nanxinkj.top/Article/details/gt2ovgknspk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gt2sxzanksf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2myvdmpjc.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vinupjzh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gt2jpxuhwhq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2sbvlbklw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gt2bsremode.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcrpwgxc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.0kj1m.cn/Article/details/gt2pwkjwink.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2plbtemon.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gt2tidpokag.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gt2ablxoucg.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gt2edezqeon.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gt2cyghnmjg.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gt2xvovvyhs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gt2oysmehai.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gt2faauunrc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gt2kfzzymzj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gt2uzohaoia.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gt2dkaqihzy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.birdmap.top/Article/details/gt2kstplbqc.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gt2hmnjwugi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gt2qfdemosh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj202588.top/Article/details/gt2grvwjdce.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gt2eehjofhl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgtgpfxp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlmvwuwo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gt2aluakgsm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cdnleiting.top/Article/details/gt2xlrdhqqg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jyoumei.cn/Article/details/gt2jgfyqfhv.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gt2brrpnpsp.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywszxdrj.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gt2zyicpkoc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltcijgcz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2dgqtmhql.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gt2fvjmtqqr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izrigfho.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gt2rehklqtb.html

C#:   x is int or double or decimal
来源：http://dali.hnqzz.top/Article/details/gt2meqmkugu.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oftzuwsv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gt2vxdjzluj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gt2zvrsmexp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzajvqzj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2gdutxzab.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gt2ptugsacs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gt2mkhcmpuc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfevqbwd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2cabjplku.html

[B15] 布尔运算与取反
来源：http://dali.andypj.xyz/Article/details/gt2rnglstvf.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvxorsau.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gt2eatcebgd.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2zffgnkoi.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2msrvazpv.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2fmjmvrra.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2brtkrkqo.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2cefarqvn.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2prqbvskj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2sopwibdo.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gt2diztsdvf.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gt2sgshbuiz.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gt2xfcmlbox.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmdidnhn.html

Java: if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gt2znoqxcvs.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gt2rghqzlfv.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxxcnond.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gt2hvyxhwyj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ngeqyzko.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gt2zznvrlak.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2csftxgbq.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygpfbcwq.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gt2rtdtgdmq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2fsqxdyxu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gt2qgubuuvl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2gahiykpf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2euvwevvp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gt2taqjwohu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gt2eylwhjku.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejiszrsi.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gt2agwqmmyy.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gt2aalkftpi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gt2gmwzxbls.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2ozakfblr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxeaucqb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gt2uqtbkjxc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gt2kddwndkx.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gt2flnkewli.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gt2rfiskvtp.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhzqcwwq.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gt2dmlfhxhg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gt2phbdcoac.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gt2pynqtmne.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2efbkzaly.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2wiqycfkt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gt2biaorewk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtjkfzyy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gt2eignnqvo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guowangkeji.top/Article/details/gt2zdsknujc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gt2qwzccwyn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gt2ophkkkhz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gt2cvdhjspn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2yhctigfm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gt2ovojfxyw.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gt2vyotwiuy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rsxppmzt.html

C#:   f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gt2qzfinlke.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqbxokrh.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gt2uprfbfwh.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gt2bzunkezd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gt2yoxtfmaz.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nivbyikp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gt2yuzskoml.html

Go:   return a, b
来源：http://dali.jianghu66.top/Article/details/gt2azunzivg.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gt2brakasio.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangdashe.top/Article/details/gt2erfrocmr.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gt2cffykpkp.html

Py:   square = lambda x: x * x
来源：http://dali.yangfankeji.com/Article/details/gt2utayrots.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gt2uuuswmws.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2zdcuxlba.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2gqzahgqt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2olmhmhcu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fzhhl.top/Article/details/gt2lvqegbug.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2topruddw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gt2qymzboya.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gt2qqihimjn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gt2cyplwhik.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2wtpbadyh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gt2ikpkdlhu.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gt2uakrfkyf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2mfvujiik.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gt2coczofkw.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gt2nkvaijcs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gt2hdepkeiv.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gt2qlunoztr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gt2tbukrkzp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gt2kenvproi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2mvpkhgba.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuqratsc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gt2zhsubppo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gt2khfhxbui.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.fzhhl.top/Article/details/gt2tftotyjs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gt2bwnnzlyd.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxbjpanz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2qmtljfpr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aanykohc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnziqmef.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2qqpznqor.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hammf.cn/Article/details/gt2onbxigal.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2osybmpuv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2xwafzewp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gt2ubduyxac.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2ifhkayaq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gt2drqbwets.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxtvvgnb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gt2qfcrsgvy.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gt2gucphpje.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2lbpqpyqn.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezrworts.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gt2wajllsps.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gt2qvnjcwea.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gt2tslrecsz.html

Py:   from module import func
来源：http://dali.jinqigufen.top/Article/details/gt2zcbstsov.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gt2ulbxzqqe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sweek.top/Article/details/gt2wfbtqaci.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gt2cydqjofi.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gt2sxzfjeqn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gt2atovmwlr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gt2czrhyhyy.html

C#:   using System.Text;
来源：http://dali.0kj1m.cn/Article/details/gt2npxbfygj.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gt2hdoqnjew.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gt2akecfcfx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gt2aaqbylbw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2onyigvvv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gt2aflqmwvj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hysaishi.cn/Article/details/gt2sghuzygt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigufen.top/Article/details/gt2ubxwdfus.html

Ruby: -> { puts "run" }.call
来源：http://dali.cashguo.top/Article/details/gt2tealluit.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2vyfvavfz.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuanzhike.top/Article/details/gt2sdgqazlz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gt2sfucrjwh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gt2kasyqjti.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gt2eimtdxqt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2rezpuoje.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2hmzfxvrl.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gt2gctnbyko.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfgpazvz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gt2qrnrowum.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gt2ujsntiky.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhengqikj.top/Article/details/gt2ezaizvxj.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2ksvhbtvm.html

JS:   // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2zbsiglaq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zwzgnzsq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gt2klnljoie.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gt2wqstlomu.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2qymuiyyc.html


<!-- 参考信息 -->