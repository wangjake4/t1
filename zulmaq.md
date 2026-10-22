代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrobzqgz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gttupitesb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nwbrower.top/Article/details/gtwzyxguow.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yongpay.top/Article/details/gtpfciuwpq.html

[A26] 类型转换总览
来源：http://dali.tian-w.cn/Article/details/gtzywihbmu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtvzgjhuyz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gtnxwajiar.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtyhxszqij.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shuidangran.top/Article/details/gtffomtxgh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtovqkcrpl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daria6918.cn/Article/details/gtgvdsiucy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gtyhoywtvt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtvdwkqgac.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdhxfbcww.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumidztiq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnobkygyz.html

[B01] 条件判断 if / else
来源：http://dali.bjfxy.top/Article/details/gtuadojagg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqidencj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtonywsrte.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtsbhznsxx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtxozutnvh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtrgkscfvk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cucudq.cn/Article/details/gttlsphsaj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yanxiufei.cn/Article/details/gtbbmayebi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgthtpwc.html

[B02] 多分支 else if / elif
来源：http://dali.ivvv.top/Article/details/gtivxxupjh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gtbaegkwzs.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxoqjozrj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtrrjgheob.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtfazpqppi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gterulhgts.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.meibo888.top/Article/details/gtdihmwuxj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xylfe.cn/Article/details/gtzfjclmpl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gthulbdnib.html

[B03] switch / match / case
来源：http://dali.snrcjt.cn/Article/details/gtzrzhcgni.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shzxlz.cn/Article/details/gtycmjaisb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtmuvvydir.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtfuuzivqp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtqwgvgeic.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtawtgzpzk.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gthsqjaizt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnqzz.top/Article/details/gttjxkhqoq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtjngjdxgj.html

[B04] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtpmlhrlih.html

Py:   for i in range(10): print(i)
来源：http://dali.shzxlz.cn/Article/details/gtpfmelmaz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.birdmap.top/Article/details/gtkglwyjby.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gtxamsiuzl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtyfiucatd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.havefunace.top/Article/details/gtwsyxbhce.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtioumphyj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guannengcc.top/Article/details/gtwpnwtbsi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gtdnpozpxz.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtakreleuq.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gtsvkfbsiy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gtekyrsqrk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gtzqwdjtih.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtnfdeymrs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gtmxdrxfag.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenzaomai.com/Article/details/gtwjwedyty.html

Ruby: arr.each { |item| puts item }
来源：http://dali.svipenyu.cn/Article/details/gtsbikcdfm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gtdrmowyyh.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gtrvqzitfq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gtnbsttrxh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yangfankeji.com/Article/details/gtioscjqlo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtgbxwtkdh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtcxfytdnn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gtirptktos.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gtmqrvfsdf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pycfn.com/Article/details/gtgwalcrvx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sysykeji.top/Article/details/gtxvpfmuyt.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gtrzrnojbl.html

Py:   while i < 10: i += 1
来源：http://dali.haohaochexian.top/Article/details/gtzrqpione.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gtqhdxvowj.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtogrzwebp.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtsplxxtbq.html

Java: while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtnqdozyjx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtqnhdlbdp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdhhkmhr.html

C#:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlaiabzdp.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gthztwbfkg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhiwuduotai.top/Article/details/gtlbuaxyxc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtmfqyvcue.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtgugawebc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtyzdcyclr.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtdhlephcv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.iojbl.cn/Article/details/gtwbipdzik.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gttcoakvxe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtocracbvt.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtkzvxczcl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258.top/Article/details/gtstzzjfcz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gttboycbns.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtjhmfvjxx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtrwgmergh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtubmofhmk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gttwyetppe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj202588.top/Article/details/gtwjwjhntw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtaqsksszo.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtnwwcrdrl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxuanxn.top/Article/details/gtrpkcizbp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtvtunjyaw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtsypjsthn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gtyrtobmjl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtvfmwyeig.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtpsbskivm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gttfkgveof.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sysykeji.top/Article/details/gtexrbniaa.html

[B11] 生成数字序列 / 区间
来源：http://dali.cheryme.top/Article/details/gtgujbqcuq.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258.top/Article/details/gtzcjmmdhl.html

PHP:  range(0, 10, 2);
来源：http://dali.shzxlz.cn/Article/details/gthxfawdsf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvbbiyzv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtfhgsgsga.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gtwphcqwjf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.iojbl.cn/Article/details/gtrtbzrrxp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gtsyqanuyv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gtpqnyfbxw.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gtyksfkmbg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gtighuynof.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yanxiufei.cn/Article/details/gttifjvbyx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtftjbkkhc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gthvddahrx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtvrkkzwbz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtxsbvqwhx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgdnmmcq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gtbsntqzkn.html

[B13] 判断是否为数字
来源：http://dali.shangyingyoupin.top/Article/details/gtkisyilcg.html

Py:   isinstance(x, (int, float))
来源：http://dali.hysaishi.cn/Article/details/gtxgwqxadw.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkesxafv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtpvlsrths.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gteusxkkeg.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gtpxnkuflk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.andypj.xyz/Article/details/gtlbwphcis.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtkckegzaa.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gtpjhehivq.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gturnfinyw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gtthwodtgz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jyoumei.cn/Article/details/gttdczryep.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtmwrvkgrz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtxvcnfyyt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gthgwekziv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daxiang520.top/Article/details/gtqdowpbrx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gtzcjkspia.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtzdtxcojv.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gthafathob.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gtvugbpqdc.html

PHP:  $a && $b || !$c
来源：http://dali.jqgfzy.top/Article/details/gtclfkmlkz.html

JS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyqytdwi.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtgfzxhykm.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtjyrqaatw.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtzhxnymnz.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtleohhbwo.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtzkrhjncc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtbdhzrqtf.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gtmnvgsxug.html

PHP:  if (!$data) { return; }
来源：http://dali.mhx1999.top/Article/details/gtgypimlhc.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtnlsntkjp.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtqvfxvcrm.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gthlqnakgx.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtlvilaopn.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gtpqagxgti.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gthwhwczko.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrqitnjay.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gtrlrqyfhj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttvawxsfj.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtwuahbilz.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gtcefhhczw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhqleooh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtwsvfhyae.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtswgswzbb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtegplujay.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtvocvlzcf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj202588.top/Article/details/gtqbfyofeu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtgfifowii.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gtrvhjsmrb.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gtxquxzozz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsaygasu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtwactwiez.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtbbrklqcg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hongshengwenyu.top/Article/details/gtnbaauase.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xinyue.icu/Article/details/gtdgrlonfq.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gthrhlqtub.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gtonuvrajb.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtakfoadjt.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtdmkqzabt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtqphaslye.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtajvicukx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhprnsyk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtodatpocv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gtdxlrocjl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gtiwkxvodt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtqdgoofuw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gtfpqosqom.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtirtfeklr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtqxjildpc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gthilirikc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gtesweocqd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtetcmatqn.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtwnoztwdo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtoneutbve.html

C#:   f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtjhwsjdhx.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtjklqpaom.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtarvbfsga.html

PHP:  return [$a, $b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gttswylxer.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtvfvbyvqs.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtehupmdxe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sufxvd.cn/Article/details/gtubwsgyzi.html

Go:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtesohgvfw.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtxkivsgpj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtwlcnxnwv.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtujktcsuz.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtbgyzkmcw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gtoazcfhtb.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtrqyrjfwa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gthulnxtii.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtodeeibsz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtadtbccgh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtdypvpykl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtvaytgcup.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gtdcjmntlk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gtupgrukye.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtogawhibf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtbebhptkt.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtgsirbkua.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jyoumei.cn/Article/details/gtedfmargb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenjidiqi.icu/Article/details/gttyjwjgqv.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gthnigrwxs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gttyycuwrm.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gtbhvskbxk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtfuyyhstt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmqhxvad.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtvsjwpbus.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtzyjsyypx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gtlvofpbic.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtmvksfjuq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtoqodexir.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtmemggsej.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtuclgdvds.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtmnwtnrfs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gtnzrxaozw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtqdjbknqq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtxfiznrnb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtrpjckyrc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gtxbhfpbid.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtnaiqmtck.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gtzgvrkogu.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gttwknobxn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtpdmozhyv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtwcyuxyvl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbahygdvo.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtrzqhyqhm.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtcnxgeplf.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gtjksiraao.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gtjgobpnuk.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gthnyhglkh.html

[C11] 模块导入与导出
来源：http://dali.nanxinkj.top/Article/details/gtdsroaczd.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtjbprqtuy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gtqkpmfnnr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtjgrpumfy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtulkzicwo.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtmgebzcma.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtkvtbiuve.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtwkvcorvh.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtwjrexbsc.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtkuzzkrqu.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gtzkngayqz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zycfv.cn/Article/details/gtbhbeiivk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gtrnxrjfug.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtfopsbviw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gtvbanwitb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtnuruigsi.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtwnlplsqm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtkbjoqhou.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gtupgrdsdf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.iojbl.cn/Article/details/gtmzdmaezi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtfrgybttx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gtqhthilrt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gthcfsnzzz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtwudkoinw.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gtyyvierdo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gtvozvaoou.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gteqpkkvnb.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtvjmvpfoo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gtskdpshxs.html

PHP:  // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtpinklqjj.html

JS:   // 无泛型
来源：http://dali.yj202588.top/Article/details/gtzzumvhho.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauiozfis.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtcebfsyfh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gttemjzgnc.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtzhqrahss.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nanxinkj.top/Article/details/gtlbtqtsrg.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtxiiqlx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgewgqlhz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gtndrxewvf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gthjpfjjxq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtjkhgvsky.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtbbrhmjgb.html

Go:   // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtlzmikhjm.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gthliyylzr.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gtjhnupejy.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gtpcjnswao.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gtvizpjqup.html


<!-- 参考信息 -->