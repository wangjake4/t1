代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtajwunefi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xinyue.icu/Article/details/gtgkeftuiq.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gttfwrussh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.andypj.xyz/Article/details/gtemlsvemx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqyhvlrbd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gthyizosde.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gttyzbpcqh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.snrcjt.cn/Article/details/gtquhxuvvd.html

Go:   strings.TrimSpace(s)
来源：http://dali.zycfv.cn/Article/details/gtdppszwxc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jqgfzy.top/Article/details/gtgirxhggo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjaduoip.html

[A25] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtoffvbihw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gtjonrbjaz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhijiandao.cn/Article/details/gtejoyaxwk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtqudjzljj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gtitrksvjt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtdzqwtpad.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gtbvjevghe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnxiangtu.top/Article/details/gtgjmkfigi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtjumzwcjo.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtrwqblyjn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hnxiangtu.top/Article/details/gtyexiyxwo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pycfn.com/Article/details/gtpzpzbgro.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jlsjyb.cn/Article/details/gtpckwosso.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gtabjrolgu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtgorublsz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuanzx.com/Article/details/gtuhmmhiku.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ivvv.top/Article/details/gtmbeicxya.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gtetekboto.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtylvjvsen.html

B. 流程控制
来源：http://dali.xziqi.cn/Article/details/gtggtkpwcl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmdaexmyi.html

[B01] 条件判断 if / else
来源：http://dali.hywenlv.cn/Article/details/gtakzzrvbc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtnmxxjjor.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xziqi.cn/Article/details/gtatiubjts.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtwobexqkp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtvayiumhs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtylsdrdni.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ivvv.top/Article/details/gtyapngqrc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gtebkfwpjs.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtmfscoacu.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gtlnnnygml.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hywenlv.cn/Article/details/gtjuqurojk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj202588.top/Article/details/gtqarcffii.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtpjbipmlm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtutwpqpmc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtwzdadsmg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pengpengdd.cyou/Article/details/gtqjthhhta.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.meibo888.top/Article/details/gtfbysgsqj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtrckysrhy.html

[B03] switch / match / case
来源：http://dali.aibaodan.cn/Article/details/gtgtfvmvyd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gtsdzshvos.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtmyccbycw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtzbceywoe.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtuyvxndfz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gttxstswza.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtqddhmvdl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gtvxxeuahu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtmgkremcc.html

[B04] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtgrglvbzk.html

Py:   for i in range(10): print(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcapygufp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dianchejie.cn/Article/details/gtdgjcbyau.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gtheodauze.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtqkgydokn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.andypj.xyz/Article/details/gtdpdxitng.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gtlrnqbpiq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gtialskaxd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yvedp.cn/Article/details/gtgkncisut.html

[B05] 遍历数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gttghvnkks.html

Py:   for item in arr: print(item)
来源：http://dali.quarkkingdee.top/Article/details/gtbjtqsfvw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gtayumazmq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtaxtvrjkl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtgkqzxwrv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daria6918.cn/Article/details/gttvenagcs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.havefunace.top/Article/details/gtpxdmgjub.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhgoopaj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.redwolf501.top/Article/details/gtghwtpvag.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gtnondcdnq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gtyjakhrje.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gtqbqutndv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gtrsjstxke.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gtrivjvqei.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gzhubu.top/Article/details/gtmwieawyd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fengsongda.top/Article/details/gtrdrhoflv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gtfivzzdof.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gtshjcjygy.html

[B07] while 循环
来源：http://dali.wangdashe.top/Article/details/gtgepvfkpl.html

Py:   while i < 10: i += 1
来源：http://dali.guannengcc.top/Article/details/gtxnnfjmoz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gtrbejstnv.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtfdmlutgu.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtxpprrrae.html

Java: while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgrtgygyz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdzudfvb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gtqccajuzl.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtfnyllhxg.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gtmadzpjja.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gtskvjiatc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtnwojpwjt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtbbqqrjlt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtqxoipmwx.html

Java: do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtysszhcgo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gtnkrarzky.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gtaqbcdhnk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtelqdubxu.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gtnyrmgeuf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtlskzfill.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtveaivbhw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtozrxwixx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtkjkssebz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gttmjhmbyd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtunmweuxu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gtnqawujxm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtzhghlfje.html

[B10] 遍历同时拿索引
来源：http://dali.guowangkeji.top/Article/details/gtmgzliszt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnqzz.top/Article/details/gtuzmvfcbx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.bjfxy.top/Article/details/gtjkdczzhu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.birdmap.top/Article/details/gtzijrkeeo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtgfkwzdav.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gtsfwphpsw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gtdshjdyfr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gthnxgyyjp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gtkvqtlpzo.html

[B11] 生成数字序列 / 区间
来源：http://dali.meibo888.top/Article/details/gtpvfkxdku.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gtmsozmpzj.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gtjtrahpfn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtkshftvyu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtyzlwzaaf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gtqfyhwrke.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gtgiplyhxp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.iojbl.cn/Article/details/gtqkhuaxkv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.mhx1999.top/Article/details/gtepzwffdp.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gtsxvumsjs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yonumen.top/Article/details/gtrtcxunlq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtwwdqgsra.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtxwmvarxn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtjtkehxbd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtvieawrnm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.quarkkingdee.top/Article/details/gthekhmadj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zycfv.cn/Article/details/gtnyakskya.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gtjkbrjrwz.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtmvikujkl.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxinkj.top/Article/details/gtaprdcmix.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtlzexlyaq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtbszygzym.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlahabtv.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gtjhqbirdh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gtketqelts.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtgwoewevt.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gthilrlcap.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gtltpicwad.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gtuxifzswz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtzpoaotbi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtwmedkdka.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtdgjaujri.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gtkhulybqj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gtdwhbxzji.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtiswlledb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtlbwpjjjn.html

[B15] 布尔运算与取反
来源：http://dali.zycfv.cn/Article/details/gtujycxkoc.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gtkuszryln.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gtceztbkfr.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtrhprqdoj.html

TS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gthcrotvbj.html

Java: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtappmrarn.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtqwfcwpwt.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtvpattqng.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtrufavjyz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hammf.cn/Article/details/gtxjtwqiud.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtlnvddmwi.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gtnmsutrum.html

JS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtgufrmkrf.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtcuzoyzan.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtzhlfjcgu.html

Go:   if data == nil { return }
来源：http://dali.cdnleiting.top/Article/details/gtxmztpkfq.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gtftjknvec.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmnrkhyz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttecnebqo.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtlpceksvd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttrtbvtnw.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtdbyzrqpi.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtwdroqzln.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtdlpkrhyb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtqpntakpc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtbitavfgt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtayxitxli.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtklhilvtf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gtpqjfamao.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtbxlcibdz.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gtklhaidrp.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gtfxrkljgc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpsnrnbso.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtkyaeianb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtlforkgue.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gtpllrxxtw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtoikikcqj.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gtaqhobbxp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gtvwplymiq.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtplctkrmi.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtnnzzxpif.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcndjraun.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtnhccxsob.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnkngyszh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtmerzlrzh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gtalkxvvwi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjajamvo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pengpengdd.cyou/Article/details/gtxmkpkdyn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ehwqpu.com/Article/details/gtfnflmimv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtggvidvzh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtsnrlvyep.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtejpgkmcr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtrqvwjrza.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtpjvrfxqs.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtdwtjfbzb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtbrudiymu.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtnsadxkmn.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gtohgvamxu.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtgkjukjci.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtzzdzdcdp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gtngqxrzvz.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtdkqzutxh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtmmnyflyj.html

Go:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtyleqwsjs.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gtffbhoigk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.birdmap.top/Article/details/gtqxzgyglq.html

[C06] 匿名函数 / lambda
来源：http://dali.jyoumei.cn/Article/details/gtciucifld.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gtykjkzkct.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtocdavmxh.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtdlygyeke.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtrkilyjsw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtgexdlxwz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtyocwehsp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtnecuxdji.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtbjbfooeh.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gtbxapndif.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gtjcfdbnco.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtgtmqqukk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gtcalvioct.html

TS:   arr.map(String)
来源：http://dali.bjfxy.top/Article/details/gtrxlkplpz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtdyayxptr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gtwddjkfrz.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gtyjywqsyv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauznpfol.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtqnyezhgs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gtchsjogru.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gtypcjnbav.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtbcddvsij.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtrenmrogc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtkakrujnu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiawfjwte.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvudsnob.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtsrfvxxgk.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gtdlsnqfjh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtaqctojlr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtfdkhtdge.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtejsfycrl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtuawbbakw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtjiluniqs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gtdtmgofvc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtnahgfmad.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtqpujcrmj.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtcwmxdwrx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtdbsoeeny.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtftrcpmyh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gthhmbvhlu.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtpkmbqoxu.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtchfirqur.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtreyglfee.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtzrlrlbwe.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtvcfhqfnh.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gtrlogfool.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtzoomfjch.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gttrvwebvr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtcaxgejoc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dianchejie.cn/Article/details/gtwnmedmqf.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gtlmkjjena.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hywenlv.cn/Article/details/gtbytrgoub.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtnydbniti.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gtkxachubv.html

[C12] 立即执行函数 IIFE
来源：http://dali.shzxlz.cn/Article/details/gtobqqutch.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gtwvzusneq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gtunzwuata.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtximvpehe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtgfcbzzbn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gtrltfiztr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gtkwhpoqsp.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gttfyqvait.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtypdftiwm.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gtatgmekfd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhxibnsg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtxfyildyd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gtonnqoxhb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtsqugbtih.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtxpzqwuin.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtjlormmeh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtcfhzwnyz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cheryme.top/Article/details/gtzjkrjmvy.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsazgauri.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shangyingyoupin.top/Article/details/gtwkrojxtn.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtycfrclmq.html

JS:   // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnrgexsz.html


<!-- 参考信息 -->