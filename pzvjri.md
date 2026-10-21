代发 wailian999

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtwrdwcbub.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.mhx1999.top/Article/details/gtxiechjfd.html

[A24] 去除首尾空白
来源：http://dali.aibaodan.cn/Article/details/gtjndvnblc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gtzsacfkov.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guannengcc.top/Article/details/gtmzesxfhy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gtlqwtodst.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtyzweyqef.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltlilshz.html

Go:   strings.TrimSpace(s)
来源：http://dali.ivvv.top/Article/details/gtafboyyqp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gtmesjwdnh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sxryk.cn/Article/details/gtarbbfiie.html

[A25] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gtvhybnzjy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gtwfltpgun.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhyuynhc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gttuxadgdi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gttjrgzchd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nwbrower.top/Article/details/gtmuylmriv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ivvv.top/Article/details/gtvdsopnku.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shuidangran.top/Article/details/gtmrirpwhd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtwuygopmr.html

[A26] 类型转换总览
来源：http://dali.bjfxy.top/Article/details/gtzvhujjto.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gtmeftuetf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gtkneroaqn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.snrcjt.cn/Article/details/gtczdofowb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.9152youxi.cn/Article/details/gtxgjhfdzd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gtphdjkfoz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.c1oappe.top/Article/details/gttfsnszxu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxuanxn.top/Article/details/gtednjszvw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtifmhgtvp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthrlnclop.html

B. 流程控制
来源：http://dali.fengsongda.top/Article/details/gtnivnrynz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtuxeagspu.html

[B01] 条件判断 if / else
来源：http://dali.hammf.cn/Article/details/gtmzdchxrr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gtsyjjfiqa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtrpooziks.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtctaxnrkn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqmpvpsy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtgsdbraih.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ppjwa.cn/Article/details/gtrynsjktq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tanke756.top/Article/details/gtrfntomcc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtpvbmgcvj.html

[B02] 多分支 else if / elif
来源：http://dali.xinyue.icu/Article/details/gtlwxwojrz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenlongwang.top/Article/details/gtpphgossi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhongyouzk.top/Article/details/gtjawlunoz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtmcypuxfy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gttkyxaxex.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtppgqimzj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pycfn.com/Article/details/gtetqadkvs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangdashe.top/Article/details/gtfkfzsyrz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtiiwcwzrv.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gthgqcbacg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkuiqqeb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gtukkmesbp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtyjxjelms.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkrfktopz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvmzplxs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sysykeji.top/Article/details/gtjtmhaeer.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yangfankeji.com/Article/details/gtxhraxefa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cucudq.cn/Article/details/gtmnszzcpb.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtzwkbewtd.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gttrjgfwla.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxybtbnm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yangfankeji.com/Article/details/gtrybrvtmt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gthlqaecgt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ivvv.top/Article/details/gtegsiqprm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gtztcxmgmk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gzhubu.top/Article/details/gtlzwfxgfa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreygajhb.html

[B05] 遍历数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtwixhoedz.html

Py:   for item in arr: print(item)
来源：http://dali.yueranfly.top/Article/details/gtlntxcair.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gtzvbctzai.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtqbuihefa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gtesihooyc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtuiswaexy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cheryme.top/Article/details/gtwiyvkcnf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guowangkeji.top/Article/details/gthumvifmd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gtgpaeuiek.html

[B06] 遍历字典 / 对象
来源：http://dali.shzxlz.cn/Article/details/gtycfztomd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gtzzocwalm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwuhzamdr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gttufkzujx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtkqqwgzhr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gthofaibhh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ehwqpu.com/Article/details/gtuipaplbp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnxiangtu.top/Article/details/gtwestceki.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gtnyhdckwv.html

[B07] while 循环
来源：http://dali.yonumen.top/Article/details/gttbqlbxyd.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfctyvuc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gtsugjkxai.html

JS:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtveupysoh.html

TS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtevirjcvq.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtzudjtiot.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtahnmwmwi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gtsivbrvio.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtxyzlsdnm.html

[B08] do-while（至少执行一次）
来源：http://dali.pycfn.com/Article/details/gtohrahbeo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hysaishi.cn/Article/details/gtbadiitdz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cucudq.cn/Article/details/gtbsutpjud.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtckcisesb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitogxghn.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtnlasvaph.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtnwclsbwy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yonumen.top/Article/details/gtssrlugia.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtgkgzrfcu.html

[B09] break 与 continue
来源：http://dali.zdqjudy.top/Article/details/gtjcddhdqi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtsutagqny.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtrzqgvlkc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtmgopfwru.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtlggtzncn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtfaqghvmo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtqxnariac.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhoulong.xyz/Article/details/gtjfqpekfl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gthlqsqtnf.html

[B10] 遍历同时拿索引
来源：http://dali.hammf.cn/Article/details/gtcctdogdu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.0kj1m.cn/Article/details/gtcoqfsqxi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gtyabpelmj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtvprythka.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtodkbwqcz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.svipenyu.cn/Article/details/gtzpdtrhxf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gtwfvxbbmp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gtendryyjx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gtmssydfmk.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtcrqksfcw.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gtmnbyiaoo.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtbmougsaa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtmpyeblte.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtfgjbnfaz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtzbazozfh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gthfvwgmbk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ybcxt.top/Article/details/gtzxkqwosr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtjxkuzfkj.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtfhvqgmiy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gttflbuuya.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gtjbejqlzh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtxbwhieha.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtkusmxbmh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtxnlczics.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtnfsldlnd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxinkj.top/Article/details/gtgclprsgz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ehwqpu.com/Article/details/gtoszishmq.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gtwsetrzgi.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvfnosph.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtsarichpj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtmpdwawbo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtmddueafq.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtnbtqmnqx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqueokgnn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ehwqpu.com/Article/details/gtodtbwcuw.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtasoobptj.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gtggmmbamf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gtnqxvtgjt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gtdtdlchuc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtogyektwt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtivzldnnj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtsowornsg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtpyueozyk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gtmtqxpnep.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtnohxvfhy.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtexawbiof.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gtrqfkwbhd.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gtdzlkerxv.html

JS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtpqjjjcbl.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtqrezscbw.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtltbtkfrb.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtueyocxdk.html

Ruby: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtpnwtbpms.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gthrgposwn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtktxexjvf.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gtcjybawfn.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gtmoipmrsm.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtbfhtsqzo.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtzltimcst.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtryvwrxjd.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtzvsrgwxr.html

Ruby: return if data.nil?
来源：http://dali.0kj1m.cn/Article/details/gtunbndagr.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtijmuzqpp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrlewrwac.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtzddlvvlj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtacvlybdr.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtoanmuqsy.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtkiqtbwjv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtjlqbgovo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtisxjhbnl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtgixmikmt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxrmadfzi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gttrfhmnpo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtunhcrgcg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtcykymxsi.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtejkyjqjk.html

Py:   def greet(name="World"): return name
来源：http://dali.316326.xyz/Article/details/gtesganhwj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gtucxznlbr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtqxkggjqs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtziibghul.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gtpvpoggsy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtjqxybvnb.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gtevogykal.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaabjsukq.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtivjpnisa.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtbgqqexrg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gtyqdvhpbb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtwjnrbxag.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtyxoupdwj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgkgljobw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangshuangyany.cn/Article/details/gtgskkxnkj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtjzwpvdoj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gtekpswocq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guowangkeji.top/Article/details/gtajxfgwmm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtdiotbkuh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gthbnvrdwf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtpagdmfgx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtavumgtjv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtyewefqxc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtcmwyowub.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gthbadumnf.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtjuwglrau.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtmnhmllwd.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtcjicbaqx.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gtjrvgcuwb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtmtwqywfd.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtrnqxvqhc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gtcjppcjpf.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtdzkruaxe.html

Ruby: return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtuqfyvyrm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gtuvevqrba.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtjrgtmdwd.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtkbikymtq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtbfjdygen.html

JS:   const square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtjfwqjkax.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtxkdaiape.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtqjfidiyx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gtgtvcerht.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gthsjoyqwf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtseukvfxz.html

[C07] 把函数作为参数传入
来源：http://dali.hongshengwenyu.top/Article/details/gtmespcszm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtfcqevwpu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtmfxrwmys.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gtqcqpddjj.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtrvtpwogf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtewsotlju.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gtjlyaugtu.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtzyqqduji.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtdgkpgwiw.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gtwpnybfgn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jlsjyb.cn/Article/details/gtpexdxvdi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yongpay.top/Article/details/gtltelehvi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtuidtohfe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwpzmujq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gtlylxtsib.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gtdirqawex.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtwvjikryg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtmbtmqpan.html

[C09] 递归
来源：http://dali.wangdashe.top/Article/details/gtxbsbnawr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtbxkzdzdi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngejplji.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtuzmbevio.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtchbdtjdz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaplqlyjh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvabpcbhr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtiqksyjct.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gthviugrkg.html

[C10] 变量作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtymxpswmj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtkdzirnro.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gttwfzpgmo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.0kj1m.cn/Article/details/gtcegelcjl.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtznctmsvf.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gtfeqpexnc.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtxzkbdofh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtrzkfrgpp.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gthkpyftfv.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gtxtsujqwp.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gtowuqgyuq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtfhvyhofd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtzinbpnvc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gtfzensoak.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgtcucpo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gtjoctvupa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtotgovpot.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsszfbot.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtujylervd.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtrcfzfuoc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gthckxzjez.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gthfvszuyf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtsirxvxfi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtsfwqzqvm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuanzx.com/Article/details/gtepnemngt.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtebskvoax.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtoskguwdj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtktkktfmc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gttnxsfihl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtfrmyjodn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gtrsdluhho.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtsanasxxw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtlhmuykrx.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtrbtzdawr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gticpyrmii.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shangyingyoupin.top/Article/details/gtukmcxqje.html

[C14] 泛型函数
来源：http://dali.daxiang520.top/Article/details/gtfdipmilm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtxvwbblho.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtnqrkigsh.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtfrtdkmbj.html


<!-- 参考信息 -->