代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jiagoushi.top/Article/details/gtplqiledl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtaftlewak.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtbqunjceh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtzsskcguf.html

[A26] 类型转换总览
来源：http://dali.haohaochexian.top/Article/details/gtqewaqzao.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gtpxqfnbor.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yonumen.top/Article/details/gtdmnmcfvd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigufen.top/Article/details/gtpsxkacue.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258888.top/Article/details/gtdvjxwrnj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtycieppkv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gtcxacsulp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gtkhwshztn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gttmpprybr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtwiypshch.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gtwcgdxmpo.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthyywwdei.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gtwkheigbm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258888.top/Article/details/gtfdpqeyla.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ydzc1.top/Article/details/gtfthzdpyh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtmackzmog.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtexuhtjjw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtecwvmguv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tianlin.xyz/Article/details/gtsliyizfu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pycfn.com/Article/details/gtaswuqfdl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtjvhlnrnk.html

[B02] 多分支 else if / elif
来源：http://dali.c1oappe.top/Article/details/gtqbflbmid.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtavkbtwas.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guannengcc.top/Article/details/gtvrcvyzpk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtgmpdkste.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtdxpqghxp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtaccpobfa.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtlgvfsrgl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gtzjdipkls.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtnwgmeiyk.html

[B03] switch / match / case
来源：http://dali.pycfn.com/Article/details/gtowzfhkce.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhoulong.xyz/Article/details/gtppyfbsor.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzpbbmjp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtegnmtqco.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtgpxebuku.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgqtfvvd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvegkcqbe.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gttgyqfvsb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fengsongda.top/Article/details/gtqovjzizt.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtfzhihsyg.html

Py:   for i in range(10): print(i)
来源：http://dali.zhongyouzk.top/Article/details/gtxwrsqshq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.kuanghao11.cn/Article/details/gtjwanashx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gtntizhjim.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtrefsycbu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gttsownzij.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gtuwgxqzpb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gtgffcnqmz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gtggolsewn.html

[B05] 遍历数组 / 列表
来源：http://dali.tanke756.top/Article/details/gteimbxqqi.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gteehainmo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gturgtrcah.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gthzkcsvqu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtvqqswfii.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tianlin.xyz/Article/details/gtiuusaboa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258888.top/Article/details/gtrkppvjbo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hysaishi.cn/Article/details/gtzwcyhhjg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xylfe.cn/Article/details/gtdyhwjnwk.html

[B06] 遍历字典 / 对象
来源：http://dali.redwolf501.top/Article/details/gtwdrhsucd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenlongwang.top/Article/details/gtrlddteuz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gtkkmkkoun.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gtajisnqob.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gtfekqixgs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtoqpccltk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fengsongda.top/Article/details/gtdmfaains.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gtupqbjwjb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gthpoxbpwn.html

[B07] while 循环
来源：http://dali.haohaochexian.top/Article/details/gtvxrsoxgg.html

Py:   while i < 10: i += 1
来源：http://dali.yvedp.cn/Article/details/gtcdiejtyb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbvkzwxft.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtahhzdpjc.html

TS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtktkiizgf.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtahspjhir.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlypeijqv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangdashe.top/Article/details/gtebulkcxl.html

C#:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtecmrjmrw.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gtcudtfsig.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gtgasevjai.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gzhubu.top/Article/details/gtnmzcakcl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtdhqvuynt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrynjbhld.html

Java: do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzibbglt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gtctvptzph.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gtaatcnjvx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtvjzhhpgr.html

[B09] break 与 continue
来源：http://dali.andypj.xyz/Article/details/gtfxpyjlbj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gttriyaccv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtdhonmdzf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gteovzcerg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtvizvrdzp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtvztszufj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtvocsglos.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.c1oappe.top/Article/details/gtdbreunuu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtrowssjuc.html

[B10] 遍历同时拿索引
来源：http://dali.haohaochexian.top/Article/details/gtjerejzhs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtidsaerro.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guowangkeji.top/Article/details/gtnupyymcr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gtpkzmdges.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmipwrfz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gtqqqpgbtt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hammf.cn/Article/details/gtzaivcevz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yongpay.top/Article/details/gtgnymuwlk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gtxeoisbgk.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gtriyinvge.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtphgtqlaz.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gtpjifmmvx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtwgvvzisc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtnbnqvoqm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gtryjzbqup.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sweek.top/Article/details/gtznczfvve.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gtoddzrfpu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtquvuhjak.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtvrzbydjf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangtech.top/Article/details/gttfhzjyii.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gtrjqaevmc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnvpgqwr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtogvaibrt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtkjzhrsfh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gtsawkzoks.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdbzhrfa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gtysacjlbj.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gtfzdopjad.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtldvfgxsx.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtnvaoadlz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtlnqmeczl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.mhx1999.top/Article/details/gtenmmkiyg.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gtdyrbizvd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gtcfksfgeu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gthjjddtbt.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtsnowdhzg.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gttzngpswx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jianghu66.top/Article/details/gtdncxhnxo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuanzhike.top/Article/details/gtwpmgmptg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtyjppqrkt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtyrpcnyxi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtdwnpaugj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gtmqcvfkex.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nwbrower.top/Article/details/gtvnkichvo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtsvnjbofz.html

[B15] 布尔运算与取反
来源：http://dali.wangdashe.top/Article/details/gtwyswahvn.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gtkcdctkkv.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gtwqbxbbim.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtzytebyuf.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtkaahjsew.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtqjsxvkhy.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtjmwvhidl.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtqhojhsmu.html

C#:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtgzfmvnhs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gtencrpzpy.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gtjbmkvruz.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjfdasqvx.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtjwtcoqjf.html

TS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtiivteoko.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtvoszmuoo.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gtafduutab.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gtzgixsuci.html

C#:   if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gtvzjbgddr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgsjvbmwj.html

C. 函数与作用域
来源：http://dali.bjfxy.top/Article/details/gtgoxqbmuy.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtxlvjusof.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtpdmnvmgz.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gttofijouw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtuafirkxo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekvoavrn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtenmtxwdd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtzqqjydkp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtmwiifwus.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gtynrhtiaz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyemqwbrv.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtqxhxkryy.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtjmvirggo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gtvcxtdsmr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbygdckiv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtvgexrvwr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtojmpawpk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gtmurunczx.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtcdpwmuek.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gtxuzcpifu.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtctthckpu.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gticvanbfn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gtzaczdnic.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtmxrrlebn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtgvnxwdtr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gtrrefxflw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtfntxarox.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yanxiufei.cn/Article/details/gtyhhpzzlx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gtfpjltemp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gtnyosfvuf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuanzhike.top/Article/details/gtuoqbktvh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtswjlxdcu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.birdmap.top/Article/details/gtrfilpxmn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtbbsnlxwx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gtbkimvgbc.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gtqunprtgb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gtwcnlscng.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtgsufybap.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtrolsyhrc.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtonajqlws.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gtowqviaxv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtdmkrvpdl.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjduxchy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gtlnrgswnw.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtkojzggdc.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtpqcihmec.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daxiang520.top/Article/details/gttdjbgxxo.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtdrmpdriq.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gtgjbatpin.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gtqbsvmjmw.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtephmjgog.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gteyqtjaui.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtbjzkkkgd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtfdopmakq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtbuwvonsl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtpopqtwki.html

[C07] 把函数作为参数传入
来源：http://dali.guowangkeji.top/Article/details/gteqqopurr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gtgmkkbono.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtkgfqlogq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gtiuiaorki.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gtjwhqikxx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gtacawzywg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gthesyexhr.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtujlppwgg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtwiyraqsx.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gteyozygjl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtgeaqfhvd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvfgjdrje.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gthbrhswoq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtjmkjhoqd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlzxgjem.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gthxwwvtfi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtsxkazikf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtanwqphab.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gtzsbqmmvm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtcqqppfzy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtfbijelkp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtlidellye.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtjpknezpc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtjoeqtyzu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.quarkkingdee.top/Article/details/gtkavvgrgr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gttxcqwbnk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtddjarrgp.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gtirtouqhd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cucudq.cn/Article/details/gtujfmjnyl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtvotllaih.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtdvkfxenk.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gtvvsgyxwq.html

Java: 方法内为块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtqfonaulo.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtbbpqyzvv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtjxrrwguw.html

C#:   块级作用域
来源：http://dali.xinyue.icu/Article/details/gtmisllpsb.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gtugokqoya.html

Py:   from module import func
来源：http://dali.chenjidiqi.icu/Article/details/gtiqvohzaf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtkwxfgmfi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gthdrruefr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gtxsbjfnhf.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtdazcovgv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtgyxknlwr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gtlruykaap.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gtfnkookyb.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gtfksrwoqd.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtmnfgymhx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tanke756.top/Article/details/gtnaouczuw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtxqlbrnbf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtapqloemi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gtvgftqnar.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtvxnceywj.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gtcbcaskrt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtvgbcxeah.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gthnqhghmm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtduykkwrz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtijlgqyhl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtekasqxsq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtebayhrjd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtczfdxehe.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtyiqpawpy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gtjffqfbyk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtevhiqfhg.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gthidmgtfw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtpvguzkdm.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtmbdyzgah.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtixieieqq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gtlfrqjgwb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gtorxmmnvb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gtsnphhiyv.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtrrejyoku.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrncbgph.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtjrldpaig.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gtpyuevdia.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtexcngxox.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtlfaurhrw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gtqytcfiid.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtfeonmhka.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtrsckrgjv.html

Ruby: a, b = pair
来源：http://dali.kuanghao11.cn/Article/details/gtbfhmhtgw.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gtyjmuoqev.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gttgovytak.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxinkj.top/Article/details/gtkxlepypz.html


<!-- 参考信息 -->