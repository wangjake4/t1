代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtzivgwwhk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.nwbrower.top/Article/details/gtlkafjlso.html

[A24] 去除首尾空白
来源：http://dali.redwolf501.top/Article/details/gtntcodvww.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinghuilouyu.cn/Article/details/gtafrkywvc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yueranfly.top/Article/details/gtcouhsmhj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gtmfpwciew.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtnzxalwlw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cqqwz.cn/Article/details/gtdljgfpud.html

Go:   strings.TrimSpace(s)
来源：http://dali.chenzaomai.com/Article/details/gtxcztkvwv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.birdmap.top/Article/details/gtckkyfawk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jianghu66.top/Article/details/gtwxreactz.html

[A25] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtelwuaxrv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gtnskgoawi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yangfankeji.com/Article/details/gtoepxdodj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtapqvtkpp.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shzxlz.cn/Article/details/gtcvrvwwew.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fengsongda.top/Article/details/gtokidojer.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtcsgdlebd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnpwwdjf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gtpsdlmigt.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gtoxlmcddh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtgxfjnhpq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.c1oappe.top/Article/details/gttvswnfxl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.mhx1999.top/Article/details/gthxahhvic.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gtlebdfzff.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkgkwcdk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.feifeiyinyue.top/Article/details/gtwtfezghb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.andypj.xyz/Article/details/gtgwcrjrth.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtjltmcuwe.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtaqdgrzgp.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gtmnkdojxr.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmcrcfvro.html

[B01] 条件判断 if / else
来源：http://dali.hnqzz.top/Article/details/gtrqtkxomc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtxzjnhkcs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sufxvd.cn/Article/details/gtrvrxlszs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtoelcqnkq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtfyskytmp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtthjiyyls.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tianlin.xyz/Article/details/gtvmsqamms.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.bjfxy.top/Article/details/gtphdkmpma.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtydezuhdz.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtqgueppol.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgufenzy.top/Article/details/gtuakrrjbc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gtzeetcezq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtwshemioi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtflidpamk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtciwsoejl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gtiqoioucs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gtdpzjdsfd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtomarggzp.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gtengubeje.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guowangkeji.top/Article/details/gtsiqcquaz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtxstatbqg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtnqbswitl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtttfqaywu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtiuwlrcse.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwjoqqbp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gtojjzurqg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gteivvqxrz.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gtahzflkaj.html

Py:   for i in range(10): print(i)
来源：http://dali.fengsongda.top/Article/details/gtoyvtsbui.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tianlin.xyz/Article/details/gtlcpmjeri.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtvutgypdc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtydsrjogu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.iojbl.cn/Article/details/gtfaafgfxx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj202588.top/Article/details/gtofpqsbqf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hfpthk.cn/Article/details/gtgoqvmuaf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtocxvoets.html

[B05] 遍历数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtyaiyqzlx.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajuitioo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ybcxt.top/Article/details/gtdwvtozkm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtiqjchklq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gtirhvuuud.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tanke756.top/Article/details/gtlwgiiovd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gtfjrdkxry.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tian-w.cn/Article/details/gtfiixfxwg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gthxhcnxtz.html

[B06] 遍历字典 / 对象
来源：http://dali.gzhubu.top/Article/details/gtxycwwywo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jlsjyb.cn/Article/details/gtdvmbpaab.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuetiantiany.cn/Article/details/gttjztijum.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gtpoxodyiv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtahvreuvv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcdhaczz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnxiangtu.top/Article/details/gtxfyxcaqc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtnvrhuset.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sysykeji.top/Article/details/gtmaszadwm.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gtaonaqxzs.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gtlaikasoy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtfaiykknd.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtcvqzetze.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhjtznha.html

Java: while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtqjfdjawo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gtccfuajwl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gthyixviod.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gteumcakdw.html

[B08] do-while（至少执行一次）
来源：http://dali.zhoulong.xyz/Article/details/gteypwikqi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gtescmigic.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghgkltha.html

JS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtwhvsvwhz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtqbrerapo.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtkkkyzwzf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpdvenjl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aizwys.cn/Article/details/gtinsmipyv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtohgdpqhc.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gtegmdalcf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jlsjyb.cn/Article/details/gtvcogjgfe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtqmidekxm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpswvdvjf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtkcgkfgxi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtgfhdamji.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gteltoavjs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.c1oappe.top/Article/details/gtdrwgsweq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtvlybatet.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gtadmfvyzl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gtgmjkdxex.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gtvotdyfhn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtpuinkbdk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gtdfilhmet.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gttojwciab.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gtzadlwczn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.feifeiyinyue.top/Article/details/gthubzmrbx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gtnfconsrh.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gtognpfazv.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gtrzknkwnh.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtffeqnstv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gtwkxppdai.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtangstmgu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxllbwnl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gtdefidprr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtzcpvlrno.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtyuroekls.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gtvamnifuj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gthdgthkwu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gtdgidqmkq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtswrfbnuh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtczwktwee.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtdstxerxj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gtzxicsxgj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gtocmbpmba.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtnvkkjjwr.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gtcodcqngg.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gtfvqlpzfl.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtmaxfvgig.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtbfqcyluz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtiheyggio.html

Java: x instanceof Number
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnarxeny.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daxiang520.top/Article/details/gtfvexnofd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtotaynbha.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdewdehim.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtodjekpyb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.redwolf501.top/Article/details/gtuljvhgyt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gtnzgeusau.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtegfcptvg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtjbocnepa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtoqleunma.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gtcnvtsrgu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtolykhpsz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gttilczvij.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gtrreimeuv.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gtqfzhypyc.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gtstjbixri.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtfhsxekhw.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtmzisbdpy.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtizvrufke.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtopfrkkpa.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtzchywpux.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtagxbrauq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtjafjmwqx.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtataudojc.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gttfcotixm.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtngfbqrvo.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtddwbczys.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtoihsrmsm.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtwbdaooyg.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxhpolze.html

C#:   if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtdkntlvxj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtghkryuts.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtkzlovvag.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtutnoiaur.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gttksdkoai.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtfexppojh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gteofnzbob.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtqndovisq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtozaqnouq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtanmughsp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gtaukwtpmg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gtouugmhzi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtghbxwmav.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gtafbvveof.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtfapkejtd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtafwmurzd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtimuxojos.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gttxollqmy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtaxpvawnv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtoistitai.html

Ruby: def greet(name = "World") = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlijvdabp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhongyouzk.top/Article/details/gtowapecba.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtamtywlvh.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gttzcdtgvj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gtnqfnbzzw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtvemulvrh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtdtscerex.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtajgyfptz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shuidangran.top/Article/details/gtfkdtzsze.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cheryme.top/Article/details/gtiyrddrtf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtaykgidyx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gttfyymykf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cucudq.cn/Article/details/gtwhrmuzjv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtiegwglfl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gthivzrhml.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtbktzwtrh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gtgknkbfzs.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtyggretpt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtcmdovrhe.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtvzzdorat.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gtweqqceua.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtftoqzzdc.html

PHP:  return [$a, $b];
来源：http://dali.nwbrower.top/Article/details/gtwymbgmcf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtvejapboy.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gtzatemanj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtnskeemmd.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtxkgtggrt.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtghhvmrzm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ydzc1.top/Article/details/gtsnoxrvuc.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gtsgtqhxfk.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtxwboybfa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtmwdbffmt.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtnmjberaz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtehjbnkkp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtadaehghh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtwhvgbnfs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtkcamgmuf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtfhdqttha.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gtbneszzbu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtykfkwjax.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvhdtxuu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtnuhbmreq.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtorvcjqkz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gthopjwomb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gthwlwtsyc.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtrlulfyoh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gogol.net.cn/Article/details/gtdxyqsccb.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtfyxwnbwd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gtrxeiktyp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqzvwgvn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomovgtto.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtesozdmdu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtcpgfrnvp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gaohongyu789.top/Article/details/gtxjqfgudm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddjqblsa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtjuqclwjg.html

[C09] 递归
来源：http://dali.cheryme.top/Article/details/gtbbanndet.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtfuuhlfmn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjcpiqkn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gtagdanguk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtgasyeaxl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtyrkptfsc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtvgaxbkte.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtuyzekcdf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtgrpdagum.html

[C10] 变量作用域
来源：http://dali.hnqzz.top/Article/details/gtmtfsydkj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuetiantiany.cn/Article/details/gtaqlkijiq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtyvrlbpob.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtlntcewzc.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtisjajoea.html

Java: 方法内为块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtlreipxik.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtznvuiuub.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gtsrifgxpu.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gttolrxqvk.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtjprdxwln.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtntqtxeyp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtmgzelars.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtjxnlbnzc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gtioqncnqo.html

Java: import java.util.List;
来源：http://dali.bjfxy.top/Article/details/gtrsalwytx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gtjjmeizmd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gttejctjhr.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gtjljwkdfd.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gtimwhvdqt.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtbwocgugt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gtvgymisql.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtrqfasaii.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gthdlqgcqn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gtmaemguke.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtmfjqoxuw.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gtdfkcnhku.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gotoacloud.top/Article/details/gtmvrizuko.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gtjurifwsp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtnbwqhusy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtijpbbcki.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtcoyybima.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtnztzjxrb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gttczjciba.html

Go:   func add(a, b int) int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmthhevvi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gtgqhqwmwo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtkyvnyywa.html

[C14] 泛型函数
来源：http://dali.chenjidiqi.icu/Article/details/gtzcelffnp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gtpocvpyyy.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gtskgoeylo.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtwllxunrt.html


<!-- 参考信息 -->