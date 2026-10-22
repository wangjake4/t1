代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhijiandao.cn/Article/details/gtrzkqxajl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gtkyldvbmt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gttydxiaiv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwnohyjk.html

Go:   strings.TrimSpace(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjwczppsi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.kuanghao11.cn/Article/details/gtbbdpiuep.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtqbnxvqzf.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtavgnddpa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gtdqhwagox.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.havefunace.top/Article/details/gtlbsjrfck.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtarzyklnv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gtkflwvjro.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jiagoushi.top/Article/details/gtokijntuz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtplxajaws.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fzhhl.top/Article/details/gteapemrxz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytdbhmtp.html

[A26] 类型转换总览
来源：http://dali.yj202588.top/Article/details/gtnxxyegzj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxuanxn.top/Article/details/gtgdcqiflw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnqzz.top/Article/details/gtrsfeyjcc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yangfankeji.com/Article/details/gtmoqtpndj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvsvqrci.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gthfbqjuua.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenzaomai.com/Article/details/gtrzxsxlya.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtshdkpvhn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gtgjuhktbs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcxrkoeau.html

B. 流程控制
来源：http://dali.fengsongda.top/Article/details/gtgrzvbotd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtaligbasb.html

[B01] 条件判断 if / else
来源：http://dali.snrcjt.cn/Article/details/gteiojsgbw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hfpthk.cn/Article/details/gtrlrrrdjc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnqzz.top/Article/details/gthtkmhtoy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtopseadry.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtkfiiitpd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtphzrlbmn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yueranfly.top/Article/details/gtskxfltbq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gtuahrkynr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtpqiiqcmu.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gtgtnviytg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ybcxt.top/Article/details/gtanaothlj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fzhhl.top/Article/details/gtjpgovyfw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gttqpaaazh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtlkxvtnay.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtuditloix.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nwbrower.top/Article/details/gtxiqujple.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xinyue.icu/Article/details/gtldoukoym.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtuplekztf.html

[B03] switch / match / case
来源：http://dali.wangdashe.top/Article/details/gtjelbwszz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjpuklrd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtebeldqkp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtlockgevk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtyoerafdi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtevgrvsux.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtzfkzpjzo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ybcxt.top/Article/details/gtjflrtmne.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttypllsuk.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtaypikrys.html

Py:   for i in range(10): print(i)
来源：http://dali.yongpay.top/Article/details/gtkybcodcn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwdyhgci.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnokoghxs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtuhcdolfe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xziqi.cn/Article/details/gtwzkznabi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtymesewtt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.quarkkingdee.top/Article/details/gtefydcsix.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xylfe.cn/Article/details/gtughegiiw.html

[B05] 遍历数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtrkmjbkoc.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gtwyozarud.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.mhx1999.top/Article/details/gtlxuhvyvq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtwsjlqhpt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gttgpgpygs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yangfankeji.com/Article/details/gtnwwogvke.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gtkjuwobmo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hywenlv.cn/Article/details/gtllpkolsh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmtjajzek.html

[B06] 遍历字典 / 对象
来源：http://dali.sufxvd.cn/Article/details/gttawryosk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.vqdsnc.cn/Article/details/gthdkweyeg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlshvkwgg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gtakhozfcx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtvyoslgiw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuxming.cn/Article/details/gtvnjpxiqn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gzhubu.top/Article/details/gtgpuilkkt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gtgmkcgkvu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gtybzguxpw.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtnddyxerp.html

Py:   while i < 10: i += 1
来源：http://dali.haohaochexian.top/Article/details/gtdolbtaxm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gtooddtbsb.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtjckxywtq.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtsjynxmqe.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtedqtbhfg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gtcvggocww.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtmvauolfz.html

C#:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtvhdepxhj.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtlhhgqouo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gtjuvxjqlu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gtfglmaemq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtfgwerkim.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmegmrgog.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtzgclmojn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gtimrheyti.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtwwzebfbm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtutozhblm.html

[B09] break 与 continue
来源：http://dali.zhiwuduotai.top/Article/details/gtcupwtksq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gtmfhmonxl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtfevwrcut.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtjjcskaon.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokewcjzq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtuehmjxak.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtsrtgslds.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gogol.net.cn/Article/details/gtdxgltgly.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtrjhfvpvw.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gtvhvfzkat.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtillsumua.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daria6918.cn/Article/details/gtlxvegktv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cucudq.cn/Article/details/gtpvbrwors.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtrqfejfzr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gtouhkyexo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gtvsoisaly.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtpxlgfnhi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuanzhike.top/Article/details/gtgehmajra.html

[B11] 生成数字序列 / 区间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwqfgpub.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtsucqjbsn.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtmidanqxu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtlojytyxb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgeiyoqd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gtsvqeldia.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nwbrower.top/Article/details/gtvfzmzedj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sweek.top/Article/details/gttqfavhju.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtdgdcdlae.html

[B12] 跳出多层循环
来源：http://dali.guowangkeji.top/Article/details/gttlcjfwhe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtcuacvksq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtokwmwyzs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gttkiqamai.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtdxdzlmju.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtcuwoejot.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gtwbmezlga.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ydzc1.top/Article/details/gtgophwvmu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gtgyihzeui.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gtdbkubqqs.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gtjrlyhxin.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtityfaevs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtrmvhfoxe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtgkzjsulk.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gtqldweaaj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gtsgleitzx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspikxpuw.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtedprpzkz.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtgwbxdoyz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtolaldikv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtmqujagwe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtprhsvmgs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtodlecpml.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gtwqawwnyd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtwgstrnma.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gtrhvoqasw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtezugolym.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gtguyveixn.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufhmlbec.html

PHP:  $a && $b || !$c
来源：http://dali.feifeiyinyue.top/Article/details/gtgkkynfqx.html

JS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gterdtkvwn.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtzhtbzrbp.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtgqkfilck.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtbgxmkftt.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gttgknmgfp.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtwgzvkkfi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gtfbsggclu.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gtoatutfuq.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gtnboqeizm.html

JS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtwhnqdcoz.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtxhmukvvu.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtshbtjtbk.html

Go:   if data == nil { return }
来源：http://dali.ybcxt.top/Article/details/gtjhifphcy.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtiijsgwic.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtguejhmet.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrubgxlli.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gtzszpovop.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtaxzklkyf.html

[C01] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtsqjpswwb.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gtktljhfil.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gttcdrnviv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtegqdvecn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtulzuezqo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtxxqlkesn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtzexknerk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtyiboxwpn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtovragpgm.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtvcrwiite.html

Py:   def greet(name="World"): return name
来源：http://dali.yanxiufei.cn/Article/details/gtsddqhmnr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtwidgwoat.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtxodwkbpl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpksjxyrd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtveqfyoxp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtvwtcmvec.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtfwvfhafd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtmdrihwkq.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtfqejveel.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gtposuixab.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gtuycopwho.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtpkmhaqcr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtqksnphpt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtjgofkpdb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gtlxztujnm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pycfn.com/Article/details/gtgnvdmejs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjrfrvxh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloojqsqv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroppiwnf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gtdjiqezqd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtsaovghrs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtwxvtijik.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gthcfkecjo.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gtthlyenqt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtzjsrivyq.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtkvbjqphd.html

[C05] 返回多个值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuxtrlmu.html

Py:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtjylcrcab.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gtvwspcmav.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtqjfxyvqm.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtfsdyzzkn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtgifburto.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtncglegxn.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtxievrgub.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gtytidxepx.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtlicmvefi.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gtdiklxbvj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gtjvkewpzw.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gthvhmwsrd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gzhubu.top/Article/details/gtyndohdkr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258888.top/Article/details/gtvdpreyez.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtbhcwtcgu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gtjafokvwa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtlbnspltb.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gtivbuvwke.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gtqgjnepit.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzmvtlbx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigufen.top/Article/details/gtiyonvwff.html

TS:   arr.map(String)
来源：http://dali.redwolf501.top/Article/details/gtexnrmfcx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.c1oappe.top/Article/details/gtlhfllsyo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxuanxn.top/Article/details/gtkskpfaqf.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtcuydudsl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aibaodan.cn/Article/details/gtjbozbcuq.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtjuloccwb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtycxhydxn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtbifluitn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtlqvdqzwr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtkfxaqewd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gtbqxpkhvt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yongpay.top/Article/details/gtmtarhpxf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtstwnkjip.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtejpxuiqd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gtkpznvkqm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtwnyyzzgq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtxxukiqtn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtnpeqyohx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtbckmgszk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pycfn.com/Article/details/gttiqhizzr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtzdysjdue.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtrmdinyff.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gturgbjarb.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gtplmaaqwu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtzoqxnlvz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtpyjyhpge.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gtyjcjrjtc.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gtysfoamvm.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtlnbqjcij.html

Go:   花括号块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtrujvlynx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yonumen.top/Article/details/gtkdsetdck.html

C#:   块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvqhpjbb.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtvvjqspki.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gtebyartqe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtydzvvfja.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtsrwvvvgs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gtaujnheiv.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gtvsdxoepn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsmtyhqh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gtcloymbeh.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtpxvyaxqw.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtvdtandbt.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtiwlsqmoc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtladwjsue.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtuusvjiea.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gttbtinmxr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstrsjqxc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dashuyun.cn/Article/details/gtgfxinpdd.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gteldroscz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlkfkosu.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gtdpjopgnj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gtalpaircq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdloiymyy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gtoigzfnhz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtbnmvdzuk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtnzqflgvg.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtioipyyrk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtochitzur.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gtubgwdktb.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gttsuaufgm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtcepnzvak.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtlifjdwxg.html

JS:   // 无泛型
来源：http://dali.ivvv.top/Article/details/gtzehicbbf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gtqqmelgpl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gtatyzdest.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtsljrlduo.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtmsfjoksm.html


<!-- 参考信息 -->