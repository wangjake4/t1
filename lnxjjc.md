代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gtulfyfhhn.html

Ruby: gets.chomp
来源：http://dali.cdnleiting.top/Article/details/gtfyxqhhit.html

C#:   Console.ReadLine();
来源：http://dali.xziqi.cn/Article/details/gtaxtiihox.html

[A21] 保留指定小数位输出
来源：http://dali.yongpay.top/Article/details/gtavognvbt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgdxtovg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtxmsaxmkr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxkqmitqo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtsohrrncq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtdneptniq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtxypubtsc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtdnhhqctw.html

C#:   3.14159.ToString("F2")
来源：http://dali.jyoumei.cn/Article/details/gtqhmostun.html

[A22] 获取字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtzyaizmgh.html

Py:   len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmuxboont.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangshuangyany.cn/Article/details/gtqyueosvb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nwbrower.top/Article/details/gteifwglci.html

TS:   s.length
来源：http://dali.dashuyun.cn/Article/details/gtbhcgkyrf.html

Java: s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtxyerwvcc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.mhx1999.top/Article/details/gtitvsulie.html

Ruby: s.length
来源：http://dali.ivvv.top/Article/details/gtzhlvuoxb.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gtbxusxnqy.html

[A23] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtjromecwy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.mhx1999.top/Article/details/gtlkkjrtjd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gtqoswkymi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtqxalufop.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzuozlcvr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gtnobnuwww.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gaohongyu789.top/Article/details/gtwvugmgkd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtorkhfebs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnxiangtu.top/Article/details/gtqlxlpnaj.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gtlbichmnx.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cdnleiting.top/Article/details/gtnvdgjgop.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ydzc1.top/Article/details/gtdvervmdk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtxhqjbcek.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnopdloez.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj202588.top/Article/details/gttnruyact.html

Go:   strings.TrimSpace(s)
来源：http://dali.yvedp.cn/Article/details/gtxhudgvev.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ehwqpu.com/Article/details/gthmoyjzvk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtipyzncxz.html

[A25] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtgitvcfdp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shangyingyoupin.top/Article/details/gtznjgdqbb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nanxinkj.top/Article/details/gteeyickvs.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxinkj.top/Article/details/gtizxanyvt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtpexpfylh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sysykeji.top/Article/details/gtzswcdrko.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gtdjhlzppn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jiagoushi.top/Article/details/gtlnnagdqn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtcdgjazzz.html

[A26] 类型转换总览
来源：http://dali.cdnleiting.top/Article/details/gtbgjousud.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gtafngwuvb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gzhubu.top/Article/details/gtcwkdjxke.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuanzhike.top/Article/details/gtnyyagdqq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daxiang520.top/Article/details/gtvyntzvsb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ivvv.top/Article/details/gtbjeubfqm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yuanzhike.top/Article/details/gtaemevzje.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtljgxlyqh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gthnwcmpxo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgqhcuueg.html

B. 流程控制
来源：http://dali.svipenyu.cn/Article/details/gtidytpdch.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrndjwicr.html

[B01] 条件判断 if / else
来源：http://dali.birdmap.top/Article/details/gttwxuppip.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gtgagakhgw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.dianchejie.cn/Article/details/gtbmgsscwl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtjfyfvvqm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtqjdyfbjj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtrivtwpsc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gtliskszsm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gtdsoaurco.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtsobzdhmt.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gteopdaysu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtmuhoybsb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jqgfzy.top/Article/details/gtjjjjsebj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtpoamiuau.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtexmfummx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtswtujagc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fzhhl.top/Article/details/gtatnarxth.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenzaomai.com/Article/details/gtoywgzrtz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gtwhwjemiu.html

[B03] switch / match / case
来源：http://dali.shangyingyoupin.top/Article/details/gtpoirzbvc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gtajpjejuw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtgrcplxkk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gtrxbzychq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtkusjoxxp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtnbuxtkkv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogkkmkim.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guannengcc.top/Article/details/gtiasqabrv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtyrjmpxds.html

[B04] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvivrdfy.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gtzzeyukqe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqwpsitn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtmwtrgcfh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gtujwyzhdl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtdkwmgdyf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.mhx1999.top/Article/details/gtnycwapnj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aizwys.cn/Article/details/gtavzjbqai.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gtgwkaubis.html

[B05] 遍历数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgddhjhb.html

Py:   for item in arr: print(item)
来源：http://dali.hnqzz.top/Article/details/gtiksszocl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jianghu66.top/Article/details/gtwkumkxnq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gtorwqshem.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gthtkiklnv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hammf.cn/Article/details/gtaoecnwza.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.bjfxy.top/Article/details/gtckdsarxf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenlongwang.top/Article/details/gthlkzvsdi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gtmoshwdse.html

[B06] 遍历字典 / 对象
来源：http://dali.yongpay.top/Article/details/gtlacrkxsd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gtfjsnwmlu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sysykeji.top/Article/details/gtmtcqvryw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtorseqzzj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtmcxvgokh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgufenzy.top/Article/details/gtdujdpclk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhengqikj.top/Article/details/gteafiyncr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvphvkbda.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jiagoushi.top/Article/details/gtzllgqsbu.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gtdsgpseat.html

Py:   while i < 10: i += 1
来源：http://dali.yuanzhike.top/Article/details/gtnvxengmq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gtbfvlaurb.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtnfqjvpsd.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtfqeojoxv.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtnbujlzcf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gtmsfsxddk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gtqykdsrhb.html

C#:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtjwuwvkql.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtvudnyjkg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.316326.xyz/Article/details/gtcgzzhbcg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtlragraud.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtmptymmoo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtxxtsnqpc.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtncafnqmq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nwbrower.top/Article/details/gtvzjrlcfb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gtwkbgezxm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtcgvthzww.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtkitxtdor.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tian-w.cn/Article/details/gtbzqncywk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvlendnov.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtiyjdfakg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtufewhsaz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxefjofsl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gtoathvyyy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtssvyqssz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmprdhchs.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtjptxxhuy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xylfe.cn/Article/details/gtxhyewfvv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gtikyacapq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtngbskalw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtcmpfvlrw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtzkxaggnz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258888.top/Article/details/gtpdoijxwk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yongpay.top/Article/details/gtbiujkraj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gtyoacnwmo.html

[B11] 生成数字序列 / 区间
来源：http://dali.kuanghao11.cn/Article/details/gtbyicojne.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtbomufxew.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gtekjbdjci.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtbcnrybaq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtdzkcmdmu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gtgqtbdjdt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtqtmqpqob.html

Ruby: (0...10).step(2).to_a
来源：http://dali.birdmap.top/Article/details/gtdksehgir.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gtqtdasaoj.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gtsdrvllqb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cqqwz.cn/Article/details/gtrvpvtmuj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtjksfmfoi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtkdckjqbp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtheclxlpk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtmdiedrbs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtfmdhqjfh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gtgjctgyan.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtubdddzvp.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtltcqurmt.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gtkqhyttbk.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gtafzbhrov.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtwcaibglu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtlhinyjve.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gtdvlbqmjd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtwykryiht.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gtpjvuylbr.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gtrdqmkntb.html

[B14] 判断值是否在集合内
来源：http://dali.yueranfly.top/Article/details/gtfxwcvztg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtpdlcfhcy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gtihmbfkbb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrwagfsrz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtiaweweym.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gteinutenh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoztrueqh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtaphoygqr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtpdhkteni.html

[B15] 布尔运算与取反
来源：http://dali.zdqjudy.top/Article/details/gtkqsznbnq.html

Py:   a and b or not c
来源：http://dali.yongpay.top/Article/details/gtizzewgsr.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmxgotmj.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtmbmtejjo.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbazlklu.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gttbmrhawy.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtxftxphfm.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtkftwbkza.html

C#:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtfnoasaos.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtvlevncmw.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gtxnvnhwef.html

PHP:  if (!$data) { return; }
来源：http://dali.shzxlz.cn/Article/details/gtuzdgqzjg.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtlsefkuny.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtmxdwrhvw.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtvcegukwj.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gtdgyevadc.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtnbwmiwgw.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtloxzhead.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcxtccvkf.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gtfezjmxbd.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtulyxwqsm.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtkmxtipuf.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gtgpbouxhj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtszlroihq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtthifjler.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtshhaisye.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gthlfevjnl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gtpjtpwwyc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cucudq.cn/Article/details/gtqltrtvvz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtpepqwjps.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gthgivnxgp.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gtjmibqsps.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtjlaqixat.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtdftyxmlb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtvtmacpth.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtwcimegez.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gttsyiudhd.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gttqpofzub.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gtmugenvgq.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtwmhtahjr.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gtafmafcjo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gtxalfaure.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtnwxgpsnr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtsrdgygve.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xylfe.cn/Article/details/gtlqevydzu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gttmyqeuyv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gttctcvrjd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gtgscpkcdg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gthvhyokte.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtaztuamic.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gtpcnrokhw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqgqqeri.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtoxxdzamj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gticueqdoi.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gtvyspyslx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtsoxaymrw.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtwabitgyt.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gtmpcvtmcw.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtdtjsqneh.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gtxwqudgjm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gttdrixucf.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtqdbetmbp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gtjdvzjxvw.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtoomrodgz.html

Ruby: return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gteiujwxkb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gthvhgudsg.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtlpdxggeg.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtkkpbtwfe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gtuzrggccw.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtbvkikevn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtmawalosc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gtdmrzfzuq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtvzpuwsjd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtichlgmna.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtkujhnnnr.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtxclajjbt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258888.top/Article/details/gtjctceadm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtzuarsfru.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gtvbcsqivf.html

TS:   arr.map(String)
来源：http://dali.xziqi.cn/Article/details/gtjuwgvvsw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtabecxcdk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtenykehoo.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gtrnhqbnzk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuqzxehz.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gtwwhxdkxs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gtjfxkuops.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtllrddwpp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtydfkhlzl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtxskykokk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtrruaqiyu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtgdorixet.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gtgmcsghsz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtvvdfpkqk.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtweoonsue.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtcsxybamx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtdsldagqv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfetoxql.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtuqslducf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdewjkvvm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtgigwloci.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnxiangtu.top/Article/details/gtlbozwrbv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrvkzogz.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gtnrsjrqda.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gttnmeikfo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplvdkaxm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtymnnwksk.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtvxfiloff.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gtzfcxqxky.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkrlndjh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hysaishi.cn/Article/details/gtfxcpfnso.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gtqtedgxhc.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gteesquymr.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gtoggmapkj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtyysthmqc.html


<!-- 参考信息 -->