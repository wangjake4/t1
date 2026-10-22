代发 wailian999

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gtlxhyxijx.html

Py:   len(s)
来源：http://dali.snrcjt.cn/Article/details/gtpqzkosvi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hysaishi.cn/Article/details/gteaexlaug.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jiagoushi.top/Article/details/gtupjswbay.html

TS:   s.length
来源：http://dali.hfpthk.cn/Article/details/gtuxilvwck.html

Java: s.length()
来源：http://dali.iojbl.cn/Article/details/gtlbvwodrx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gtwgkovydh.html

Ruby: s.length
来源：http://dali.jinqigfzy.top/Article/details/gtzkoroqqv.html

C#:   s.Length
来源：http://dali.ydzc1.top/Article/details/gttpghmuem.html

[A23] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtmitekmcd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yongpay.top/Article/details/gtojifiymw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sysykeji.top/Article/details/gtlwvaccla.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsiiwmodi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtxaqvacwz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gtprhmhefe.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ivvv.top/Article/details/gthvpvrnke.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gtjscgwrzv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhengqikj.top/Article/details/gtbdovstzm.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gtnpubjboz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gtkmdpydpp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkanxybca.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtsnsoabjg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gticqavibv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ehwqpu.com/Article/details/gtriovftrs.html

Go:   strings.TrimSpace(s)
来源：http://dali.kuanghao11.cn/Article/details/gtsbakuhkd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xziqi.cn/Article/details/gtivvpkgjm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ydzc1.top/Article/details/gtbmyotsqj.html

[A25] 字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtgatiqwlv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenzaomai.com/Article/details/gtimimesgp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.c1oappe.top/Article/details/gtiiroxsqi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gtoselsgxx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hywenlv.cn/Article/details/gtivjeztra.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dianchejie.cn/Article/details/gtiljvksni.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtyabqsmir.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuxming.cn/Article/details/gtxiwcyeyw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gtixdifsnv.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gtkpbqickt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gtsjuajhng.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ehwqpu.com/Article/details/gtfqzxjfvm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangdashe.top/Article/details/gtdzhlvpyi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cqqwz.cn/Article/details/gtuqkxwegx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gttsyxpxbb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gtmsfxcqvh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yangfankeji.com/Article/details/gthvwjfudi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gttkpcphmr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthxblknfa.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gtuqtlisry.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmtdvdtaw.html

[B01] 条件判断 if / else
来源：http://dali.ybcxt.top/Article/details/gtmfkdkwxf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.meibo888.top/Article/details/gtqwjvpjcy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtoqgaectf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtckmpnokc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnkmzjzu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtbenprjyx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj202588.top/Article/details/gtbgrfxefe.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sxryk.cn/Article/details/gtkqafgzed.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtzqudziwl.html

[B02] 多分支 else if / elif
来源：http://dali.daxiang520.top/Article/details/gtqlrqgbjf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gtigsoqsqa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gotoacloud.top/Article/details/gtyjabrlsi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtxrqfhzgc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtgczxzfuj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtwmhabclg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dashuyun.cn/Article/details/gtqlkdniza.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sxryk.cn/Article/details/gttxsjvihz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtgwmklhfl.html

[B03] switch / match / case
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjndpbmzn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiwvnpkl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtcvensjhd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtqzpeujcf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtiqukzkdd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtnsqcihsh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtnihbijrd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pengpengdd.cyou/Article/details/gthrvihtiz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtupbmgywx.html

[B04] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtprxdrmtn.html

Py:   for i in range(10): print(i)
来源：http://dali.jianghu66.top/Article/details/gtqanojhfr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sxryk.cn/Article/details/gtsfsjrvcl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtzszuuznq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhengqikj.top/Article/details/gtrezysoxx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenzaomai.com/Article/details/gtuzryglri.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shuidangran.top/Article/details/gtexyoraac.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gthaxrrxcn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gtilyqunac.html

[B05] 遍历数组 / 列表
来源：http://dali.pycfn.com/Article/details/gthulxzlqv.html

Py:   for item in arr: print(item)
来源：http://dali.zhijiandao.cn/Article/details/gtoucaagnp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258.top/Article/details/gtssfqcmme.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtnwfuhtde.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gtxpsakqtx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gtvpbgzqds.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenzaomai.com/Article/details/gtkgyehjxx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtujdrchzb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtlzzyjhjt.html

[B06] 遍历字典 / 对象
来源：http://dali.xinyue.icu/Article/details/gtwbzuflqf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gtipjcfzoy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.0kj1m.cn/Article/details/gtfdxaypnz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gthwovkrhc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gtnfcnkfbv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yangfankeji.com/Article/details/gteuvgkvmj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gtvbbzfida.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sxryk.cn/Article/details/gtlaerzzyd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.snrcjt.cn/Article/details/gtmlughfzp.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gtxjpnfzgq.html

Py:   while i < 10: i += 1
来源：http://dali.daxiang520.top/Article/details/gtarxgsfgm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gtfzwixixi.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnawlbrov.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtcwkogekv.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtpqwvbiji.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yangfankeji.com/Article/details/gtrlkirmmi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gtxoafgeqy.html

C#:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtygpaoiqa.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gtmzfvucuh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gtkrwxypxa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daria6918.cn/Article/details/gtpfogladf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtvqlkwomt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtqyvjzcwu.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtrgddwqfl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtbnlwkybs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gtrzovhgdp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfdkeybv.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtouqubsup.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbngpcilj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtqnphtdku.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtwwzzrhjh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtlujyxbot.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtmirarpqv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtmtjgiedd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.havefunace.top/Article/details/gtnzrwguqx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtklrlmzvz.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gthehffpbi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtvdeicalo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gtecbpqzkr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtvioduqgr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gtdzansnbm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtsfhghtsf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gthlqmutmo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gttacutfmp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gtaehbpvrx.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gtdpwhskvb.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtrfvpghsk.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gtezrdnshl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtjwqbbadr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtttavmaek.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzmskbyfx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtvhelwevq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkiqlhbl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.redwolf501.top/Article/details/gtppuoctps.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gtnqpcstkm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gtveqdftlp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gtxhmbnsec.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtzlxmomnu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtnxcaqszs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtmmkogvny.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtidulkndn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gtxuizcjue.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuetiantiany.cn/Article/details/gtakygiexb.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtjtxoxvbr.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtuargcgoc.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gtjalkngxf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtyyzahgwp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gtphevrgha.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtrzfclqre.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrwxllou.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtmppglcgu.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gtnjexerry.html

[B14] 判断值是否在集合内
来源：http://dali.hongshengwenyu.top/Article/details/gtxvorfwmf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gtahlwgowd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jianghu66.top/Article/details/gtzhfuziey.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtechkyqor.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtwnpnqecu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yueranfly.top/Article/details/gtklwkblwz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gttzvzuwyk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gtekklhkpf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtzgvqvcbn.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtxzsicviq.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gtonfalmjq.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtpwiiezpx.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtbbdfygzy.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtfsuiptfv.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtufrpyuof.html

Go:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtllmypbfr.html

Ruby: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtqgscnpqe.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtbpgxqozy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtowktdkpq.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtbclreotd.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtlmizwliy.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtesnykmwr.html

TS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtwtxnldmy.html

Java: if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtncalotus.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gtivtlmnyo.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gtfvpsxgko.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtmerwmnff.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gteifvrdjp.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdwusohx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtappvkniq.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtpsoehlrr.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtdizgyaet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtopxkhjsk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrprvhqd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtnndngycm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gthesurpaa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtteawfrae.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtkwbxmrqy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtacpyiozz.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtnmjvmgnz.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gtczayrpiq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtlbuvnhnm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtnznkvits.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gtnhgzmder.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gtmoakuqpd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pengpengdd.cyou/Article/details/gtspyxptiw.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtkenoifqv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gtwfsaxtfd.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtggfmpplh.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtvxzueovd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dianchejie.cn/Article/details/gtghfwgykk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtybnkodlj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzofsfzab.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gtrbrwhwqu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtqwlcdhxs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gttlqyfhch.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gterxbzayl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gtgkzskava.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtuddjhkaa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtdufwznoy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtflulyjtp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtdnjvfoee.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtuwxwydly.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtqixdpjed.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtrbdszkxk.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtdkhqffad.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtoqjtoztd.html

Py:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiojjizq.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gthtizyabz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtdzbswqdg.html

TS:   return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtmsvrmqvx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gtcxhormnz.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtvoxcawhw.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtthaaslnd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtyfhpljlv.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtpdeuagak.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtdageyyov.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtnxjdhnth.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtxhvevbai.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuerjrnn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtqnjbmapc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gttcgkrgan.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtkrraslqx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtijinfaqt.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtfmdfaruu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gthxnqwruo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.havefunace.top/Article/details/gtvipstdnp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtudctcydz.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtatkrvaay.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtmohfelbv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gtybltfmnd.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtspzstanb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guowangkeji.top/Article/details/gtbegbkdnv.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gtxmsnbaym.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gtymszpauj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gthwcogvbl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtrlkujsbn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtcbnwljks.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtjkbuljov.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gtopjscqfm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xuanzx.com/Article/details/gtjriujqop.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtiapvztzf.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtknkxqmeu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtvdqhbqrg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtlszzmwsc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gtmezemvoc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtvvrkoimu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtpncpjxkq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtugkfddhy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtdylyuhth.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtyncqbfou.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gtlffriixq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtpdnpjgyf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtkcqicwfy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.daria6918.cn/Article/details/gtzounfabf.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtduhdbucs.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gttjbringp.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtnghyzrun.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gtgzgdpsbp.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gtuxrdextw.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtyhyozaqn.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gteehjnfrt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xuanzx.com/Article/details/gtplfmxqjb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtdoomdvoq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gtpoagwssy.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtgzcoaggn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gtggtzdpfr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtlpjfmfjq.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gtiuchbhuu.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gtmvupkthm.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gtoxrnixbj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gtylicwxzw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtmpafdpid.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gtxspwmvjv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdfknjla.html


<!-- 参考信息 -->