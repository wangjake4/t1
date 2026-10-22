代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ybcxt.top/Article/details/gtrotstguf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yvedp.cn/Article/details/gtwueioqpv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtriracjty.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.0kj1m.cn/Article/details/gttktqssmx.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gtyzhtydpc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258.top/Article/details/gtkrlzazkr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.pengpengdd.cyou/Article/details/gthdkxaoox.html

[A25] 字符串比较
来源：http://dali.yj20258.top/Article/details/gttkqhqouq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxinkj.top/Article/details/gtdvqcyyhv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xziqi.cn/Article/details/gtvfddzvfw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtsesunqnv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gtdsjlgotz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guowangkeji.top/Article/details/gttzvsigdj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxinkj.top/Article/details/gtpkueykhh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gotoacloud.top/Article/details/gtopgmsjpu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gtvqlwlqvz.html

[A26] 类型转换总览
来源：http://dali.chenlongwang.top/Article/details/gthdwecelh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigufen.top/Article/details/gtobknxues.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gtshppkmxz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gzhubu.top/Article/details/gtgccczvex.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gtsekolvlk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkanmmpip.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ivvv.top/Article/details/gthvwiusvg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gotoacloud.top/Article/details/gtkmbrygru.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuxming.cn/Article/details/gtfzribpps.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpxjcuvyj.html

B. 流程控制
来源：http://dali.chenlongwang.top/Article/details/gtruvqxnsn.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdtjamvhz.html

[B01] 条件判断 if / else
来源：http://dali.meibo888.top/Article/details/gtckcirsyk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.bjfxy.top/Article/details/gtoqavdlcr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.guannengcc.top/Article/details/gtqvpjbuiy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtzlvjqrju.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtsjalkfqx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtewcfytpv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.wangdashe.top/Article/details/gtiegnxkwt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shzxlz.cn/Article/details/gtxoziawwg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtclbuxxxf.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gtmaucwanc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zdqjudy.top/Article/details/gtdrxykcsv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yangfankeji.com/Article/details/gtzwpfzjhd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtobuvshgh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gttglufkig.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtilittrtr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gtenzmubpw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gtnqexgvhv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtitydyoes.html

[B03] switch / match / case
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafvzzdkw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.kuanghao11.cn/Article/details/gthfgqserm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gttndgbfyq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtqjoymzvu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtfvkfeegf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtvonyuvnr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtzyplhuwx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gtnowguyme.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gttesebfcp.html

[B04] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtsrukhbbx.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gtogkagqvp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gtalvdnwnx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtmceoiqxw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gticslmchb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gtzyzhjgct.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gtrquikcnw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gtovtvampn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtdvslhxqb.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtmygmymot.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gtqbkgaxqc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.redwolf501.top/Article/details/gtbznbpqux.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtaohbatck.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtbkmrvchb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gtlaxgfyws.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zycfv.cn/Article/details/gtcyykhtbw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258888.top/Article/details/gtqofrtnrg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.iojbl.cn/Article/details/gtozvdjlft.html

[B06] 遍历字典 / 对象
来源：http://dali.wangdashe.top/Article/details/gtmhawvnpu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gtxqjactxu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gthlzkdfhl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gtsndzwcqs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shangyingyoupin.top/Article/details/gteovsycsq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gtbqpmggbs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuanzx.com/Article/details/gtcvbvnygj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgoemexxq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gtaiwbfrmm.html

[B07] while 循环
来源：http://dali.fengsongda.top/Article/details/gtgyfnvhew.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gthrybvptv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shuidangran.top/Article/details/gthygubasi.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtwilmzaun.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrysozhfg.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtvoqdotua.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.havefunace.top/Article/details/gtmjqdosnl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ybcxt.top/Article/details/gtyjmowxqi.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtclkpmttn.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gtcqbndbpp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gtmufolurr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtzxveqwbb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtdcvvyupn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtufiqnxlf.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtlbhfelvf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yongpay.top/Article/details/gtblsgjnuz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhixingplan.top/Article/details/gtjygzfphd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtpfsulddp.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gttotezcbc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnqzz.top/Article/details/gtogfgpcyp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtprqlbxcy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtnegprxwi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gteufnjaov.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtcpvazjsh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtfmtakzka.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gtqzdyhlsw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtrladsokd.html

[B10] 遍历同时拿索引
来源：http://dali.yonumen.top/Article/details/gthzrdmtis.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gtxnmrxsdp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xylfe.cn/Article/details/gtqpanqsru.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtckdmonrv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtymojglnu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtowfewgnt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sweek.top/Article/details/gtwyibodsx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtqfwcovvb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gtsztwwycj.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gtupbftbqz.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gtebuktben.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gttdebjloj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtfwtxkupr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtvyqguseb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gthbqypnyw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtcyyfdsfs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jyoumei.cn/Article/details/gtxxpehiuw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtjgzlzymp.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gtyvwoasjr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuanzhike.top/Article/details/gtbylmzskf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtyyzbtfuh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtcykosjxe.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtgpbbraka.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtktadoezg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dianchejie.cn/Article/details/gtoipxaqkg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gtyszvladk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gtllhlhxcw.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gtvvnpbgdi.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztwylurn.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gthkmrqppl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtijctgfex.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtntwapmvf.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gteqgolmro.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gtuvwviqwk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgatshqt.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gtsgkytkfs.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gtiwkvovig.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtrgwqqdab.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gtxvygyowg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gttilgloqg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtzyblrfpf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtvvhhdgsu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.iojbl.cn/Article/details/gtqmikdckm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjcarkchj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtaqflomik.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtwneaktyk.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauqywybi.html

PHP:  $a && $b || !$c
来源：http://dali.chenjidiqi.icu/Article/details/gtyvlosjsg.html

JS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtwopdzjrh.html

TS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtfasnntal.html

Java: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtjqgyyylk.html

Go:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gttptpcaus.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtinvgubxb.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtsqjvvtln.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtboynquij.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtumoyhgmb.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtqhrilqqd.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtroddudvf.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtiymltduh.html

Java: if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gthjlwcyrw.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtkhekfwrd.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gtjpuumbev.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtibjtaizd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyfubgwcw.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtdsgkbjbo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbttidhxq.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtjnddszmn.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtugsvppya.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtcskagbpy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpuzxgtu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtubzrbhsa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtqfduyfel.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxinkj.top/Article/details/gtmqspecvb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtbgyviyay.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtmhxcqyfa.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gtvdouejmc.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gtuvzsbzfo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gtwdkqgayk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjkqavxal.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtgfippjpd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtmeejanbv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtkvmsilmq.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtpablhqwr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gtupifvyuj.html

[C03] 可变参数
来源：http://dali.hnxiangtu.top/Article/details/gtdrrzbnxw.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtujbngzrx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gthinsqdei.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtanfieuax.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtyfgvfiwk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gtibylafmp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pengpengdd.cyou/Article/details/gtoaxixsfs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gtnotaqdvb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtpgvpvyob.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtfqwthncw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtbxzrkyns.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtrvyqiqnw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtlzlnqmoi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtkbagfgsg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gtdwslcqhx.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gtkqsvvytk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtwjzljilc.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtwlgjwnkr.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtxjipnevi.html

Py:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtxclpavkk.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gtmrofrxso.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtxjhogjvi.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndyeibtw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gtqwoxjffy.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtcphkuxiz.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtmxeulzxi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gtqkqhwopi.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtoobnfffq.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gtrvyxvcdn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtoasjqnza.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtpzusjmft.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtldgfdxjz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtoxjipjwu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtzsdavcfm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegqtwftk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gthsqcerbx.html

[C07] 把函数作为参数传入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeahchfp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtvabmgchh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtxnodpcsj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gtvzonaprg.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtejzfbmqt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gtjwchmcmx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtkmvhumku.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gtwgziniwn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gtncklwavl.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gtabwpchrn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtucothkhi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtveshgghx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtdmpzurbv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtxlraqkhj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtyifwdfib.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtylhabqvu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gthweuenor.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gthjarqhhh.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtbyhkhxtj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gthnamlupm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkukgynns.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gthkczxeis.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gtsypvwyxv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtwrctugzs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gtalqcgepe.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtepihmjmj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtsinamunw.html

[C10] 变量作用域
来源：http://dali.iojbl.cn/Article/details/gtuagxkgor.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtevryzezf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ybcxt.top/Article/details/gtgldgvphj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gtuiwckhck.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtnzqkuftw.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gtctyffjjl.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtgoyfzhtq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtervqnwid.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtuqrkqfat.html

[C11] 模块导入与导出
来源：http://dali.quarkkingdee.top/Article/details/gtxyppparj.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gtdietwcvu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.9152youxi.cn/Article/details/gtlpntfjbc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cheryme.top/Article/details/gtvpvnkymq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzoazmcem.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtsevdhugf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hywenlv.cn/Article/details/gtojtopsba.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtedsnseer.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gtylexnpiq.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gthhygxzey.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gttujenpne.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtpsrpxjww.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtdqzeysez.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtnrbtudxp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gtikdyaxvl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gtvendlxig.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtytdmkspz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtbtzadqru.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtkancnyse.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtzvicclex.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtieeyorsr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtzeiiorwv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtgpihrdxc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtecrckehr.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtjqvlofzl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtrargybxi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtpyzvigqd.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtarygycuq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shzxlz.cn/Article/details/gtqyyfbctg.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubvbfeue.html

JS:   // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtwzcmypby.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtegkvalps.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gtncxverge.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gtmahrceat.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gtxnyotmfi.html


<!-- 参考信息 -->