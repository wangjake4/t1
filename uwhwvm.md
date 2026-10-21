代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ivvv.top/Article/details/gthesljaqn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtnscbkeii.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gtkiqqgkrf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gtchpvpdur.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gtmudaafpg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangtech.top/Article/details/gtueapjexb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xziqi.cn/Article/details/gtikrkwofh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sweek.top/Article/details/gtmihqgjkq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhiwuduotai.top/Article/details/gtavrrezsx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gtxiknctmv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtgufkmuga.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtaxnygeom.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gtkvyiyazo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtauzvgrek.html

B. 流程控制
来源：http://dali.316326.xyz/Article/details/gtgxvhpwix.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtyrxjtmkf.html

[B01] 条件判断 if / else
来源：http://dali.gaohongyu789.top/Article/details/gtokloqqgg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gtrccdndci.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnqzz.top/Article/details/gtkcqjhiof.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtohpetquk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtbtgjsktq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gthibinlpt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gtlzyhxrox.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jqgufenzy.top/Article/details/gtjeinpokj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtakvznbyd.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gtajjunnve.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aibaodan.cn/Article/details/gtnfqywcho.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nwbrower.top/Article/details/gtcutjltxl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtfhlnwchl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtgsdrlpxw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtlhjfvbyt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pengpengdd.cyou/Article/details/gtkvvwjxun.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.bjfxy.top/Article/details/gtdpwikwlf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtibazmvui.html

[B03] switch / match / case
来源：http://dali.xuetiantiany.cn/Article/details/gterhotyep.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gttdedyrgj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gthwdvfbli.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtcauudmxl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtxysetrmu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtzzdwugyu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jyoumei.cn/Article/details/gthbnssorw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccwxszse.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtkzikovbm.html

[B04] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gtidauzcht.html

Py:   for i in range(10): print(i)
来源：http://dali.aibaodan.cn/Article/details/gtkiyzftrm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gtkxaiqlls.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtqkrbenbe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fzhhl.top/Article/details/gtyyxcqcta.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gthnncdbcj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guowangkeji.top/Article/details/gtfngrqiam.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gtbyonkbbo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ydzc1.top/Article/details/gtocafuhlq.html

[B05] 遍历数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtiofbubjh.html

Py:   for item in arr: print(item)
来源：http://dali.ivvv.top/Article/details/gtocsooblf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gtgveywjwx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gtziwenscc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtavtbdczy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxobgfjfe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtdqiuxmwo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtsxbujxhs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gtongnqaui.html

[B06] 遍历字典 / 对象
来源：http://dali.pycfn.com/Article/details/gtanwzvata.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gthlndbwop.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduiuoyic.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gtncvykuul.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtadldqdai.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gtkmsdmtuc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtbxuijprz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtceonsugj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zycfv.cn/Article/details/gtivjqutna.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gthtgxllzx.html

Py:   while i < 10: i += 1
来源：http://dali.xylfe.cn/Article/details/gtpsgstijy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtkuohtdbh.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtpbxdviwn.html

TS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtpttjxgsi.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnwdrrdar.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gtpmpvtxic.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gtxxmynzcc.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybpyujqc.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtlzxshphw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuictvwid.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtalgfyprg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtqjmgvpoz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtyrlpfsaq.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtdvrrjwfk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtrarvnjpc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.birdmap.top/Article/details/gttswqywud.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtjztrwbvf.html

[B09] break 与 continue
来源：http://dali.zhiwuduotai.top/Article/details/gtlobnlyad.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ydzc1.top/Article/details/gtotizozhe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gthbdvipch.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtdohviojm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtggothvxc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtmvjjrant.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtktqaewgj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gtkjakqcfk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtpkmtxuae.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gttkgjavdi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gtggjfpmsn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gtibxsshzo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtoehpjxis.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtswsefhyt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgufenzy.top/Article/details/gtnusqnmcv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gtumaxdoey.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gtctsnfvfi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gtpgyqewka.html

[B11] 生成数字序列 / 区间
来源：http://dali.mhx1999.top/Article/details/gtamodijwq.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gtemzplorb.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gtsetkoscq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtvccmjvos.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gtnhljdilz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gtatssltaq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gtzixvhhrn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hywenlv.cn/Article/details/gtfrissezm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gtxoddajdk.html

[B12] 跳出多层循环
来源：http://dali.hnxiangtu.top/Article/details/gtnwdzrjjq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gtdlzoiruc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gthqkukurd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtmbuvychk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtmogpofwc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtponuhgjz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtvgmvcmqj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnqzz.top/Article/details/gtshjvkxzd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhixingplan.top/Article/details/gtfdkgwqdx.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gtjlimnjcq.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gtkahofqpu.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gthabvnklm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtjasdhtuk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtsuyksfxs.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gtiolwotoh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtrubwherw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzxdapwx.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gtdlavjsyn.html

[B14] 判断值是否在集合内
来源：http://dali.xylfe.cn/Article/details/gtrhelmwfs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gtpuwmjydx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtbeqzivvq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtrnixqedd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtnbfjulkn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtuxzyikui.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gtfkfxaqwe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gtgrekzuvz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtpejktwmc.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtefmcilhi.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtymazwqua.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gtfdgphaeq.html

JS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtibbmukmi.html

TS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtvtnpbcpy.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtaekxpmis.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtxhjneoxf.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtgbmeptiq.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtggqqwyhc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtlnzteypk.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtecaitpzt.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gtwmeijwmo.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtaevkohvv.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtshkjmkhd.html

Java: if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtxafsyaso.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gtafbxdmls.html

Ruby: return if data.nil?
来源：http://dali.pycfn.com/Article/details/gtvbdtytlz.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtyvdwllbv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtehsmaqww.html

C. 函数与作用域
来源：http://dali.bjfxy.top/Article/details/gtofascvyr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttpoisjef.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtigcnyzbe.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gtpwggdsjn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtvfrnvzam.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtfcunkgha.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtlbjssbgn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtnsxdqprc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gthsqiwezp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gtspchncmy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtiigzlcju.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gtuasmpley.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtmxsxxeth.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gtpunfovek.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gtpemzrfhu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtpzpogslm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhpzveaa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gtaarkivii.html

Ruby: def greet(name = "World") = name
来源：http://dali.guannengcc.top/Article/details/gtvuhocvft.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnqzz.top/Article/details/gtxiiyyzpf.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gtgetklonn.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtatlrewke.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yvedp.cn/Article/details/gtlfilgkrg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtcmaybapc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtoobtcicv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmmkofkvz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtboaqsqrj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gtxtmtfxfk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gtwgrqrxis.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtoskejrhg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gtwexaexmh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gtliyigmgv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtwmqkzacr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gtnutcosiz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtxomhycrn.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtylibwboo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtazuvojtm.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjgkhign.html

[C05] 返回多个值
来源：http://dali.yonumen.top/Article/details/gtwfvzbdqf.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtewdliyfu.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtmaswqwqt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtsqxrusyh.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtcbijhlkx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gtglwvhggg.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtocseblhm.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtztujpimf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtcxlvduxg.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gttwcmrgnm.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258.top/Article/details/gtoqegbkxv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtmabpuwyl.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtpwivemfh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtrigmctxd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtidsrxrrq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gtluqwegcf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtlliqwwze.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtznwyljht.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtaawidszv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtmfewjmor.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtjxbvzwcw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gtzwjmixss.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gttwsejhjp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioigghph.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtxhzxnddw.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gtnangasyz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gthrglwsln.html

[C08] 闭包
来源：http://dali.c1oappe.top/Article/details/gtjnjktpyt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gtobmjyqbv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtwsybybap.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtejyqlyyh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtifvpxyhv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gtctyfhjkp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gtdmlbonqr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtorrofcrx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtdrmnqabz.html

[C09] 递归
来源：http://dali.yuxming.cn/Article/details/gtwanuhblk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtxpaztgca.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgintdej.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gteysviraj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtxxkcgybs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtvrobzqds.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gttojowwxn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtqxqzaevp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhongyouzk.top/Article/details/gthextqqko.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gtpsggbszc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxuanxn.top/Article/details/gtamjpwyhs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gtcxomdamd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtipzzhfok.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtonyqdksr.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtknnubnfm.html

Go:   花括号块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtuhsoakhp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gtegrodbsz.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtmidugckt.html

[C11] 模块导入与导出
来源：http://dali.wangshuangyany.cn/Article/details/gtscjvqvjs.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gthkimithi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gtxleddgnk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtjiwkilvo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtqqqgzizz.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtjitgofbi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtkouaaaaf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtbgelrngm.html

C#:   using System.Text;
来源：http://dali.birdmap.top/Article/details/gtkisvabwk.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtjfrtbrnm.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtyfloghbo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtmzlhburw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtpsnmbgwp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtgjjzfcrg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shuidangran.top/Article/details/gtannlhcku.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.9152youxi.cn/Article/details/gtktlyawfa.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtmuvemwav.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwknkbaow.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gtbsmdppyi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtkgixqsjk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtjocpezwm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.iojbl.cn/Article/details/gtqpslagim.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtwvfstpyn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gteldnqgzs.html

Go:   func add(a, b int) int
来源：http://dali.ydzc1.top/Article/details/gtafybqxtz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tian-w.cn/Article/details/gtefnvqatr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.birdmap.top/Article/details/gtkvvolphm.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtsxejkblx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gtibwzsvvd.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtjhuwxswq.html

JS:   // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtumbndpol.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gthexlzdke.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gtyqgzwwmy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gtuoamcjdg.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtawbhulir.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtdifxclhc.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gtltavhidz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtnifiahsc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtvkfcvzhu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtnkabjkdt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtlxtmegwe.html

Java: // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtzsgkdsll.html

Go:   // 无解构
来源：http://dali.svipenyu.cn/Article/details/gtlousipge.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtkhpcfoei.html

C#:   var (a, b) = pair;
来源：http://dali.sufxvd.cn/Article/details/gtapcibueo.html

[C16] 函数 / 方法重载
来源：http://dali.pycfn.com/Article/details/gtkbfurexg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.birdmap.top/Article/details/gtzqawbzoj.html


<!-- 参考信息 -->