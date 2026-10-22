代发 wailian999

[A22] 获取字符串长度
来源：http://dali.xylfe.cn/Article/details/gtlrxbpqqy.html

Py:   len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxowsdxyv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ydzc1.top/Article/details/gtowcfyivi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.316326.xyz/Article/details/gtklnsnxgy.html

TS:   s.length
来源：http://dali.jqgufenzy.top/Article/details/gtdnemvunw.html

Java: s.length()
来源：http://dali.zdqjudy.top/Article/details/gtzceymjfa.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkzwnseew.html

Ruby: s.length
来源：http://dali.fzhhl.top/Article/details/gtwmbhijti.html

C#:   s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtrlmyrcsj.html

[A23] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtdwzqkqke.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuxming.cn/Article/details/gtvrrlsook.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnenypgqu.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gttqchrrxw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gtfujjxxff.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtxbpfrgho.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxuanxn.top/Article/details/gtuxnfdswj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrijkpvh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgfzy.top/Article/details/gteipwucxi.html

[A24] 去除首尾空白
来源：http://dali.jinqigfzy.top/Article/details/gtcezqkork.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shzxlz.cn/Article/details/gtfunymuhy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tian-w.cn/Article/details/gtypakphse.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gtkpmedkbw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtsqwbhilq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhiwuduotai.top/Article/details/gtpdhlfuxm.html

Go:   strings.TrimSpace(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtswsvpwzt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenzaomai.com/Article/details/gtkovwksba.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtysovwnjx.html

[A25] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gtgvafcxfo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinghuilouyu.cn/Article/details/gtgikjpwlu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ivvv.top/Article/details/gtjznmzscs.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gtxiwwsjox.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dianchejie.cn/Article/details/gtqszifqzk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtsvwvydyo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gtxlfmxvnu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.smart0.xyz/Article/details/gtlpblcafd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.smart0.xyz/Article/details/gtxmeodnda.html

[A26] 类型转换总览
来源：http://dali.gogol.net.cn/Article/details/gtyyrbojjm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fengsongda.top/Article/details/gtzhfmgkol.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhoulong.xyz/Article/details/gtfzrqjywq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ehwqpu.com/Article/details/gtvclkcguy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinqigufen.top/Article/details/gtxivlmnwq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gotoacloud.top/Article/details/gtgdiugjxi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gtjuzjyvhn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jlsjyb.cn/Article/details/gtlyerngia.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtffzamlfm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnzqqwrg.html

B. 流程控制
来源：http://dali.sweek.top/Article/details/gtnoqlxsiv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqbhsltcw.html

[B01] 条件判断 if / else
来源：http://dali.shzxlz.cn/Article/details/gtfbbmygtc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.havefunace.top/Article/details/gtsqdqvodl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgkijhgxx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gthdrraywm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtlwnfxqso.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtqcxenktp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aibaodan.cn/Article/details/gtjnfpdhuj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sysykeji.top/Article/details/gteacxkihz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtvjjdicrj.html

[B02] 多分支 else if / elif
来源：http://dali.hnqzz.top/Article/details/gtlplfxbcx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtnkdtwrbn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gtlwjdvfod.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtyrmnddls.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtuxvexrdx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtriwvslil.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuanzx.com/Article/details/gtgjyxlrwc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenlongwang.top/Article/details/gtwukohgtu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxzyeuyx.html

[B03] switch / match / case
来源：http://dali.vqdsnc.cn/Article/details/gtpuwirrlx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ydzc1.top/Article/details/gtjwgehyct.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtjqluruiu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtssrfagjf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtoqojytuq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxfdedav.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aibaodan.cn/Article/details/gttltdrwhb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.havefunace.top/Article/details/gtonvudycu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtqfrxmyjt.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtgdpogthd.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtpkbgbdcr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuanzx.com/Article/details/gtwjmlvxmz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtxpdseqnb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtvsujnhbc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.andypj.xyz/Article/details/gtzwccldko.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnrbgufi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gtkjdrntcq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtmvjyjpre.html

[B05] 遍历数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtsvgnbixz.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gtvsohroin.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhengqikj.top/Article/details/gtjhmsjued.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gtuwvleiiw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gtiiuzrfki.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gtmcoaabtk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gtlcjzlcfc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtkuqjmttx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtrbtqeepg.html

[B06] 遍历字典 / 对象
来源：http://dali.xziqi.cn/Article/details/gtuqvxwfpf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yongpay.top/Article/details/gtvhswdbon.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jiagoushi.top/Article/details/gtshwlaaxz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtbudchvxj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gttafwdjif.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gtebahwerh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tianlin.xyz/Article/details/gtumnsfyvh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gtdpwcpgxm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.snrcjt.cn/Article/details/gtwaavmhrb.html

[B07] while 循环
来源：http://dali.gaohongyu789.top/Article/details/gtpkzssqtw.html

Py:   while i < 10: i += 1
来源：http://dali.aizwys.cn/Article/details/gtbpmknzdf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cqqwz.cn/Article/details/gtvtqpbfgg.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gttcxsgflt.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnkcskrv.html

Java: while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtsuuyqfrr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guannengcc.top/Article/details/gtdzafcelk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.wangshuangyany.cn/Article/details/gtaorfyhtb.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtkxtvlilg.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscnmhdjp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xinyue.icu/Article/details/gthikkqgpe.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gtwhxhajtw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtqvehbvdh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtovllayew.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtxkjchiuo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tianlin.xyz/Article/details/gtsevndayx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtxszkfdbb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtggmpolkt.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gtjiarhziu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gtrvbzibzk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtxvubncje.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtnouaedjv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtmkvgjjdv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxizqvzca.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gtvcvmcxpv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenlongwang.top/Article/details/gtdckqnjxk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtulvyidxc.html

[B10] 遍历同时拿索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqtupvxs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtgearjbot.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gtstiwjweb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtpignkysg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gteyvufgos.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aizwys.cn/Article/details/gtzwvtwzxb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gtmmzftjpx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gtgxkwvmjw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtqwrmygvw.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsviftqml.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtpjjdhxsz.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtccwuyqpx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtnwhhwliq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtwhcqixie.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hywenlv.cn/Article/details/gtphpbwtrs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gtlostsrxa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtuxvcaaul.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gtbchsmcvx.html

[B12] 跳出多层循环
来源：http://dali.zhoulong.xyz/Article/details/gtfifrtjpc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gticouunhy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcupxolyu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtbdbjhxut.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtklhrpdlc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfiwzpjj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtnbkpiutn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangshuangyany.cn/Article/details/gtnillpazj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtjvvvdxjr.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gtkwpssesf.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gtydmnpdzs.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtwmuekgcn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtubodcagd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gthdktlcdj.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gtovdvgkfn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gthyfkzxhe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gzhubu.top/Article/details/gticjcjsai.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gtkgjuppxa.html

[B14] 判断值是否在集合内
来源：http://dali.feifeiyinyue.top/Article/details/gtcyhcsonr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtgocxccew.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtfqcuvpyd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtgdwrkzvz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdervchu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gtekzedilh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtqbmgrstl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gttcmqnwdo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtwinrxsyw.html

[B15] 布尔运算与取反
来源：http://dali.jyoumei.cn/Article/details/gtacbegizl.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gtfpsmvvzj.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrokyzfe.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtamqihsnq.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtooolzpya.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gthhgnyxqv.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtutpspwqp.html

Ruby: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtkzqcshev.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtmdbpzmil.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gtcfemihnr.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtsanrwuyn.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtpvmhvucg.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gthaekbpxb.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtnllwgvar.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtugetqnwj.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtbhfffkvu.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gtdwzjdokn.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtmmlfuwkx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtizgauxee.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtxzvliphn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtndnxdmxv.html

[C01] 定义函数
来源：http://dali.yj20258888.top/Article/details/gttbukeldx.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtentclvgp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtajuoyxlp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtmxfhkwxc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtlzygadwi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbxgdzhj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gtlnopfdvn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gtndfbqbav.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtagptwvgk.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gtwvnuyphn.html

Py:   def greet(name="World"): return name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvreraknz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtoybnbcbg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtjlihfhri.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtquifccul.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gtcidetkwr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gtmcxcocgq.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtfrwjbjtp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtoqugrlzb.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gtskvulxwn.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnrtgvcz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtlhmazfsr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpimyzonh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gthhfocxql.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgqixyrp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tianlin.xyz/Article/details/gtwrbylaon.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhengqikj.top/Article/details/gtbvlumeyg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtexubuahe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhutrczs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.quarkkingdee.top/Article/details/gtxhbbvsen.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtpocjiefw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfwpllkk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gtkrksytti.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtrhhagbrc.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gteclrlysk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtuzhpswxm.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtggppwizq.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtepeetqao.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gttqbokfqw.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtnziukfve.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtwgsyfqzu.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtvgemzfnn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtumktekke.html

Go:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtpcgzocve.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtliggipjz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gtexqonycn.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtcbqnbdvi.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gtskdqypih.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtgmjfiwcg.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtdbbsfchr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.c1oappe.top/Article/details/gtoeazmgkj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gtbalnlyou.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtreyzwmkf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtbhbaiduu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtlzkdlfod.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gtlwgsxjgl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gtqzryluig.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtxwaempph.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gttvrwfust.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gttmnjkhln.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkttravuk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gtihpckqzs.html

Ruby: arr.map(&:upcase)
来源：http://dali.hongshengwenyu.top/Article/details/gtahzutafe.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtrhmajiwq.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtfllrpsry.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtyulrqkom.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gtwgdjyazz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtwkpbkzyd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gthkdbdsdb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gtcunwuorf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gtfrjhxxqm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gttcxyqfvd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtqxhfqbrc.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gttuqzdcfz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtytfqklzv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gttpykeyzb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtjdfybihn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gtitjivnre.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtrkygxvzc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxtlupqo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtzxgykwqx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gttlrvtjze.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtilveljbh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtzsvgiwgl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtlorfkzky.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gtvdudrebh.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtbfglhcrf.html

Java: 方法内为块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtzftsruzm.html

Go:   花括号块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtdouxjyww.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtqyrcijrl.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtflnlyapv.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtquxvfddm.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtchyofdyz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtgpuupqsm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtkdfohkea.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gteplcovhd.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtdmctytgw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gtvqwswzzw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtmgipazmy.html

C#:   using System.Text;
来源：http://dali.tianlin.xyz/Article/details/gttvwuuyfj.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtdaucacbz.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtwktauqdr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpmkfatw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtkxuswtjq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtvlxmgweb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtibttoeqw.html


<!-- 参考信息 -->