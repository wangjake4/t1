代发 wailian999

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gtvtvnhzqx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daxiang520.top/Article/details/gthreurkoa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gtwkmrvztm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dashuyun.cn/Article/details/gtvitpebmj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdlvfbpg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gtxxvawhal.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigfzy.top/Article/details/gtnfwdmeps.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shuidangran.top/Article/details/gtipxqpaan.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.pycfn.com/Article/details/gtmkfhohvy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxbhuqdqn.html

B. 流程控制
来源：http://dali.316326.xyz/Article/details/gtmlooczqm.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtkzpserqc.html

[B01] 条件判断 if / else
来源：http://dali.quarkkingdee.top/Article/details/gtjzwkduxc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aibaodan.cn/Article/details/gtubtgllku.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gtdnawfudc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtdyocsvzh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gtxftouzcv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtztkguioj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.meibo888.top/Article/details/gtqzwsuvra.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cucudq.cn/Article/details/gtwoicotru.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtoflnfejr.html

[B02] 多分支 else if / elif
来源：http://dali.havefunace.top/Article/details/gtdvsjdwgd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jlsjyb.cn/Article/details/gtjgwstocn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.bjfxy.top/Article/details/gtnmdbkvnj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtawpkgarm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzesljmef.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtgmnelfyt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.quarkkingdee.top/Article/details/gtguitkwbm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.fengsongda.top/Article/details/gtzdmcpfgv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtyqxvnddu.html

[B03] switch / match / case
来源：http://dali.sxryk.cn/Article/details/gtsxafmmes.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jyoumei.cn/Article/details/gtaexoavda.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtnufljnoa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtuonyhmki.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtnqpedixu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtcvbowkzl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yangfankeji.com/Article/details/gtruxdovpt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gtapwhhzzj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsskkjgkf.html

[B04] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtahadldze.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gtuyghkble.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hammf.cn/Article/details/gtwhkaeuuj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gtutyhgzia.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gthklvhogs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtvnajqmqa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gtthbvdxxm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.vqdsnc.cn/Article/details/gtyowbpvqt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shuidangran.top/Article/details/gtnwieberk.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtquwuwayv.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gtoxgyrzgz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ivvv.top/Article/details/gtxzydedzu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtcuzhukep.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtfqrskxko.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtibdulwuo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gtiqugtuap.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aizwys.cn/Article/details/gtdnvyiurs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtuasjpxmo.html

[B06] 遍历字典 / 对象
来源：http://dali.yongpay.top/Article/details/gtiwhtlogk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmwoigta.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daxiang520.top/Article/details/gtriyqztfn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gtvecgayam.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtagxrpplb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gteffvpczv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpprmmgjk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gtvzlapgxl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoftowcgd.html

[B07] while 循环
来源：http://dali.hnxiangtu.top/Article/details/gttgrwhzpy.html

Py:   while i < 10: i += 1
来源：http://dali.xylfe.cn/Article/details/gtnkmkolgn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gtnojxdnov.html

JS:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtwaaaprcp.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtasvxivit.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtqwswnnxj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcomjkpju.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gtydlydaji.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtvzxswmqw.html

[B08] do-while（至少执行一次）
来源：http://dali.cdnleiting.top/Article/details/gtmpmyblvo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sysykeji.top/Article/details/gtwzblicet.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtbwhoudna.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgqazybv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtbhlevrdg.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtrarwdnqm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.birdmap.top/Article/details/gtrouoizgp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gzhubu.top/Article/details/gtbwgicnxn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtunndleij.html

[B09] break 与 continue
来源：http://dali.nanxuanxn.top/Article/details/gtpyofjxpw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.316326.xyz/Article/details/gtthxehaiw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtqhxmubil.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtquvpcxyk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtyzuozkvz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpjrtclee.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtkksnywcv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gtswxikwph.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtcigwrxhp.html

[B10] 遍历同时拿索引
来源：http://dali.meibo888.top/Article/details/gtzztjzfye.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gtojpkqnxx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtgrizatdk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtrldbcsxi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtisvlfsjl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.bjfxy.top/Article/details/gtywtslddb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtcqmclyem.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtwxxadqfh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtipaeinus.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gtfmakajce.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtpgzvhxlj.html

PHP:  range(0, 10, 2);
来源：http://dali.dianchejie.cn/Article/details/gtivfcnywi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtbttedlvx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gtdvjheyoo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtfsgyldtw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gtygyilqau.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gtpxazvpuz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtqyinezdq.html

[B12] 跳出多层循环
来源：http://dali.svipenyu.cn/Article/details/gtikvadkab.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsidegcgt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gtqwtbbeeh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gthnmhwptu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtryneiaiz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtfeznziil.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gtptwcdsws.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtowddrwwt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gtvanzlwjg.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gtgspxuqhr.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtbxgvqoco.html

PHP:  is_numeric($x)
来源：http://dali.gogol.net.cn/Article/details/gtrjbiguet.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtncbquzsp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gtpdmymdql.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtvdldmmkf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daria6918.cn/Article/details/gtlicitxbk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtlahdsulm.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gtkwyvvcna.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtfsofkwxv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtexoguuyp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tian-w.cn/Article/details/gtmhazxehi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtllqmvvfg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtrudlvgmi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaoiaxzfd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtmnwtwtdj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gthzzvdrqv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ivvv.top/Article/details/gtcasfcitu.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtnzkltfho.html

Py:   a and b or not c
来源：http://dali.zycfv.cn/Article/details/gtszaodwhy.html

PHP:  $a && $b || !$c
来源：http://dali.aibaodan.cn/Article/details/gthnhrhmgc.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtwbyxnaeg.html

TS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtiblasxev.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtatyvbqnc.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtxrdackme.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtpeiqvpxc.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtivqfnglh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gtciniixcx.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gtggsckblw.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gtqdygtkie.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtgqssoseb.html

TS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtmvowsleb.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtbpddwjwk.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtuamvcyjj.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtguogcwhx.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthptcfzwu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtuuyiuwrj.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gtignqfxhv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtslvfsnle.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtvgyspqqh.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtmtphlywd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtlzvsqlog.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtrdlaobvo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtyaljzeik.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtudvshwtz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtlubrcjfv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbnpotly.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtnjntsupt.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gttxjnwjuk.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gtewhurczn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtffpfomvn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnptmwxpu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtliqzfxsp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtnavoxgtw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gtgictizfc.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gthxncaxby.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gtmdukphia.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtteokihwe.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gtgnlugaeq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gtfxxmznmw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtowgfpcrr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtluslriep.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gtsgcqriwu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtmrvixqrd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtwivwyfzc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtqslnkzle.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dianchejie.cn/Article/details/gtntzuvelu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gtjvjpzxqs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gtlxbmpskm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgkuasxnh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gtuslchxvx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gtcxucmipf.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtqwmeagjr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtyvwqxueq.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdpjygrsj.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gtytdzpere.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtbojbmxus.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtmaeicdwh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtxiedbhws.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtgqlbuhvq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtndiviggg.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtgxvaydot.html

Ruby: return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtrzvjazrj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtnicgzxiw.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtwdmnkgrm.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gtbyiajdnu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsykoyvs.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtcpxmikrh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gtvpfnlljb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmeqsgwyx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gtoinyvwtl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxzpljke.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtmexarbmc.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtsfnyxewr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gtazixksql.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gttdltbatb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtmitrnyov.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gtyhucpukb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtivryogfy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gtdmuboopy.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gteykqpmeq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtxevxnazq.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gtdhvhetet.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gtmwbasifx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gtxdnfmknk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtmlfkdbcx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtrauwttcb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfynmnyov.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtjvpqcuwh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gtkdogjgjk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaibkfyj.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtmzzhuxyy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtqjxosnbe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gtdhymuwha.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtxukuihue.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtwnvvyler.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtjeizupvb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjfbqail.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtgfnxfgtf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gtewanmikj.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtpcdtwija.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gtqxhkbodg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtnurjthzp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gtlavgsonn.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtrmupfrlf.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gtpjpczmeu.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtqoicxtfo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtkehfhimu.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gtymmarhwz.html

[C11] 模块导入与导出
来源：http://dali.nanxuanxn.top/Article/details/gtwuxpbjsb.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gtkskydqdu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gtdxlcohjl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtkqccxqdr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtfvgcoqij.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtgpbtxtow.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenjidiqi.icu/Article/details/gtfczfpmlp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtjnvufwoe.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gthhxvnrcm.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gtodhohhtk.html

Py:   (lambda: print("run"))()
来源：http://dali.yuanzhike.top/Article/details/gtuhguhrvb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtfovhlohx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtfempmdfr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtrvsckmzd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gtqxarggem.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtshrxbqkr.html

Ruby: -> { puts "run" }.call
来源：http://dali.kuanghao11.cn/Article/details/gthcakhodc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtiwicrbtk.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtdbptncru.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gtjweacmlz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjnzlkmtd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtiatwmydv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtqnreqnex.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtuyfgujoy.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtmvpyfxuq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gtejgvanua.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtlpmzpdjr.html

[C14] 泛型函数
来源：http://dali.gotoacloud.top/Article/details/gtxyidgfzl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gtgndnspdd.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtaqzfvxuo.html

JS:   // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtzxadqcpt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gttggtezlg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gtyptwsowt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtwobvajfq.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtqzdnzqqn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gtyaviuqsi.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtlffeexhb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtwtfohoch.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtikkwuybp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zdqjudy.top/Article/details/gtckhcwamt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yueranfly.top/Article/details/gtqngmgahn.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtmgotfhda.html

Go:   // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtucujjcja.html

Ruby: a, b = pair
来源：http://dali.zhongyouzk.top/Article/details/gtooggcehz.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtglftkdkr.html

[C16] 函数 / 方法重载
来源：http://dali.sysykeji.top/Article/details/gtpptzpoaq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtkxeivuvg.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtwrgtuiei.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gttyqdggfg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtzemigpcz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gtaaalqovi.html


<!-- 参考信息 -->