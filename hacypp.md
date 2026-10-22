代发 wailian999

[A26] 类型转换总览
来源：http://dali.nwbrower.top/Article/details/gtlvnhzaun.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xinyue.icu/Article/details/gtiqczcqyu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.kuanghao11.cn/Article/details/gtvnngrsed.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dashuyun.cn/Article/details/gtflhyfwex.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jlsjyb.cn/Article/details/gtedilorca.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtothxlmjs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cqqwz.cn/Article/details/gtwliqjugk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tanke756.top/Article/details/gtaxvjmaif.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gtqpnbegjs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtswaaxhif.html

B. 流程控制
来源：http://dali.yvedp.cn/Article/details/gtthevdtqs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtszxjsfwc.html

[B01] 条件判断 if / else
来源：http://dali.zdqjudy.top/Article/details/gtzmboxbxp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtvcqmfjzr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoycaqbpd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtieaodalv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtdniokocx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtxappamma.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnxiangtu.top/Article/details/gtvqbvuwma.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhongyouzk.top/Article/details/gtxioviqyz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbknuamv.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gtojfzakyl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtnneunsqo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gtmttnazmk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtmhfielqs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtwyngjxzk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyalinzb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.chenlongwang.top/Article/details/gtuuoajpdk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.meibo888.top/Article/details/gtpuqxzdac.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtzdhgnvwj.html

[B03] switch / match / case
来源：http://dali.xinyue.icu/Article/details/gtowoxzqhc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gtqageusgj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtsnacipmu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtrdoslbhj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtzxdyuezc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtefgjehwr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.havefunace.top/Article/details/gtkoqqolrs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gtagduhrzs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gttrngeiri.html

[B04] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtyvhseekq.html

Py:   for i in range(10): print(i)
来源：http://dali.9152youxi.cn/Article/details/gtvliqgtyr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gtjxmwrbeo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gteiaabcul.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtxznujjae.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.svipenyu.cn/Article/details/gtddkfwhul.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gtsnyrfgkg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.meibo888.top/Article/details/gtskedmguo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cashguo.top/Article/details/gtjcidazwx.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtruoermrc.html

Py:   for item in arr: print(item)
来源：http://dali.hywenlv.cn/Article/details/gtujptqyuk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.fengsongda.top/Article/details/gtldsaitgi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtmnatjymk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtjgdmwmfa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtwpjfzkft.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlaktgbp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yonumen.top/Article/details/gtvbviztdt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gttmcgdyri.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gttzavwqhl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.haohaochexian.top/Article/details/gtteignpwd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yangfankeji.com/Article/details/gtijyyghfg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gtndztfofd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gtntyjuxjb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxexdryb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.bjfxy.top/Article/details/gtitpwbxkk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gtzdfzxyir.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.meibo888.top/Article/details/gtklypfqas.html

[B07] while 循环
来源：http://dali.chenlongwang.top/Article/details/gttyqkhufy.html

Py:   while i < 10: i += 1
来源：http://dali.daria6918.cn/Article/details/gtqpdzqoko.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gtbkedchxi.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtmcenrnrj.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtulzmaqfd.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtxssorxti.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gaohongyu789.top/Article/details/gtiolwhweo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gtekftdhuk.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtztzydffn.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gtavaeaped.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gtoifzonpm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtblxjrrqm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtweasyvym.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gthmwpokpo.html

Java: do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gttnyheyii.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtmfdbngfv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gtpbfjphyc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkjeuttw.html

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrujjikda.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zdqjudy.top/Article/details/gtsrlpilwk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtlzglvgql.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtbtwxiapp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtgqjiorbn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gthgnbmjrp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gtepylmybs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hfpthk.cn/Article/details/gtqlwfxbpm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumcppdry.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gtjndxyaru.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsmspbkh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.vqdsnc.cn/Article/details/gtemjzmqjq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtlwaicupm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gthfvmebca.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtlpktvobn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlvklorv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigufen.top/Article/details/gtocgdpwqd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gttroaagwt.html

[B11] 生成数字序列 / 区间
来源：http://dali.bjfxy.top/Article/details/gttbveiodw.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gtfzyxhhti.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtnqgewfjb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtssrfwbtd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtnqvhotvu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gttjhxiauv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gtuzhbasbx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.quarkkingdee.top/Article/details/gtyuinjxoa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gthuhpzvcq.html

[B12] 跳出多层循环
来源：http://dali.jiagoushi.top/Article/details/gtucqtdvcd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gtkylvkmrq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnxiangtu.top/Article/details/gtfggizxez.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtkuwsoolp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtuvkebydy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtxwuqimap.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtngbjgzjx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gtwhbzyopy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtwgnzmujv.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtjcgjwkel.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtsfpmvwno.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtibbyfmiw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtmcvqokvb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtdsysxpuc.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtjvrkihdo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtxtngpged.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtnrsdakrm.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gtjzrxtjtv.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gtjswesxsp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gtqqybixcv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gtgfnjrsoe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtszzcjgbc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgaizrvdx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtymjvwasj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gteoccxrpg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtrlhvfzci.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtgfzrwdzf.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtpiwfapru.html

Py:   a and b or not c
来源：http://dali.yangfankeji.com/Article/details/gtqbawfcav.html

PHP:  $a && $b || !$c
来源：http://dali.havefunace.top/Article/details/gtgzuisehu.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtlfdkyghc.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtawecrjny.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtvnxhrnem.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtzjgnnzki.html

Ruby: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtoakrqxwy.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqllndpz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gtnjcttldx.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gtnjimvhvt.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gthqoxquwe.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtfwvpnwrm.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gthqrnxlph.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtugvqxgjs.html

Go:   if data == nil { return }
来源：http://dali.redwolf501.top/Article/details/gtmtmlagam.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtirwwjeso.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtvuhbipci.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmibcodlr.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gtltskpkwg.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtlopwgfwn.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtqeoavwvy.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gtbbiikhiv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtqocmdisz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtkcczvyqq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsuopesde.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtsdetivnw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtzccbztnk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gteghkogmn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtollndimt.html

[C02] 默认参数
来源：http://dali.ppjwa.cn/Article/details/gtyknbfybe.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gtntntfkap.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gtcwvkmurl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtfkmoqgdj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gthtzqqtsx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gteuymsyqj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtpwtmuiee.html

Ruby: def greet(name = "World") = name
来源：http://dali.cashguo.top/Article/details/gtpjkrnozs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gtafybitoq.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gtqzqpbrxh.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gthaefpevl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gtqimnhijb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtjylrcfrd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtwhetjtmb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gtlqjximqw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtiqubvdeq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtkzygsarl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gticaouzhp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gtbxuozxmz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtoikuiosn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gtkvshywib.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtuqqcizrr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gtwnprvldr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xinyue.icu/Article/details/gtrptnqqtc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gtxljgwwed.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtnygwffhw.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtoqsvduia.html

[C05] 返回多个值
来源：http://dali.ppjwa.cn/Article/details/gtnjwqqevg.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtpxjmaxfn.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gtspykfxej.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtzfvbuhug.html

TS:   return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtmsooeynz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gtrmvidezm.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtbvhemzni.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gtoynvkqwk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtoqlctnlc.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqntofqo.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtssuitkwq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gthyfzupbb.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtkhhigkmc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gtqzzistkp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtuntkuwfg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtynttjdln.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtadwmmuqr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtjsykrdtt.html

[C07] 把函数作为参数传入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblzgzskc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gtgfkxykfh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtgibxcbrz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjkcjpbw.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gtlnafgpaj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtqybycczl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gtlrfwmtnb.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtrzauqmlo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.birdmap.top/Article/details/gtualhtoup.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtiymeatwc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gtkalpvtsp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtivablfdx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtqozpeekc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtxzukvmhj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jianghu66.top/Article/details/gtwolytsjn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjgqtook.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gtfbfmdfym.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtevjuoxqe.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gtlelblczx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylffsrnf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtntcnuwsu.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gtsswuedch.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gtvcxdxdvu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yonumen.top/Article/details/gtgpjfqoys.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtmspuwslf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtedjzgzla.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtrpwmrvit.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gtinhmidyp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtpbqeaefa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtefgelbaq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtbwluiizk.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtapztrjct.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtxohldwca.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gtbufyfcbn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ppjwa.cn/Article/details/gtzigbrbjg.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gtbvcwxrmo.html

[C11] 模块导入与导出
来源：http://dali.jinghuilouyu.cn/Article/details/gtotgonhpx.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtnojjgeaz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gtspaujsmm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nwbrower.top/Article/details/gtlaiolxsy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yvedp.cn/Article/details/gtsraumtpg.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gttguazsvh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gterrwqayz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.birdmap.top/Article/details/gtqrexmbfz.html

C#:   using System.Text;
来源：http://dali.yj20258.top/Article/details/gtxmtsfvwu.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtwmoormta.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoofkchda.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtdtpcaski.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtrrphbzar.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gteqnwdulc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuanzhike.top/Article/details/gtuehlnggn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gtagibnwuc.html

Ruby: -> { puts "run" }.call
来源：http://dali.xziqi.cn/Article/details/gtnsimderv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gtprcczbsu.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gtnikhgwha.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtigdwvntx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtgwzouaat.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gtnrrkfmvs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtakekxfos.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtkdbwwlji.html

Go:   func add(a, b int) int
来源：http://dali.wangshuangyany.cn/Article/details/gtoabjhfpr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuxming.cn/Article/details/gterppeyfj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gtjsdqufjm.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gtnytjhavr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gtrkalhpoh.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtkguzwgcc.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtxyqklbox.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtazjmhiui.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gttfeqdaie.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtjeuwwvxi.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtkkyltlbv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gtyuzopwmc.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthldltgyy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258.top/Article/details/gthjvcpsrr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gthhsbkxyu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtngbjkwts.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cheryme.top/Article/details/gtcbtyvqmv.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtuvuccrnh.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtzoeimomt.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gttjtmahoi.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtzmmgdhvk.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gtvomkjdif.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtvgvcthpl.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gtriucleei.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtxrpgnzrf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtnjdpxbob.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtkrcdcgbl.html


<!-- 参考信息 -->