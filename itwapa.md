代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yonumen.top/Article/details/gt2pzddyzlu.html

Ruby: gets.chomp
来源：http://dali.hongshengwenyu.top/Article/details/gt2wplycqkd.html

C#:   Console.ReadLine();
来源：http://dali.nanxuanxn.top/Article/details/gt2lticeheg.html

[A21] 保留指定小数位输出
来源：http://dali.sweek.top/Article/details/gt2jsjnmdpt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.redwolf501.top/Article/details/gt2rxotqpzz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2jajhnkox.html

JS:   (3.14159).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gt2ndbmmgmy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2xvbqjmuj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gt2sdoxjffu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gt2qulfliqs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gt2rwddpoza.html

C#:   3.14159.ToString("F2")
来源：http://dali.shuidangran.top/Article/details/gt2eztxvcwx.html

[A22] 获取字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2loiocvwz.html

Py:   len(s)
来源：http://dali.xinyue.icu/Article/details/gt2afvtglod.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jlsjyb.cn/Article/details/gt2bltpfjvl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zycfv.cn/Article/details/gt2hvlddggv.html

TS:   s.length
来源：http://dali.sweek.top/Article/details/gt2fvfaryho.html

Java: s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbzygreh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2xkbuvjep.html

Ruby: s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfcujrew.html

C#:   s.Length
来源：http://dali.xylfe.cn/Article/details/gt2qwchwocm.html

[A23] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2neyzrmyw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2jcwjzuwb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shuidangran.top/Article/details/gt2oafchlqr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gt2tdwxmdlg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gt2lauutyzo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gt2fkbyamal.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tanke756.top/Article/details/gt2qkdlsjqa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gt2onibwcyb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ppjwa.cn/Article/details/gt2bvykokam.html

[A24] 去除首尾空白
来源：http://dali.cheryme.top/Article/details/gt2nldjvkuq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jyoumei.cn/Article/details/gt2ghdnkadq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gogol.net.cn/Article/details/gt2ishkolnv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gt2zanmtica.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2mrlsicsf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2truoboni.html

Go:   strings.TrimSpace(s)
来源：http://dali.sweek.top/Article/details/gt2rlsgpbse.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guannengcc.top/Article/details/gt2rdhepqev.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gt2txlwzbvg.html

[A25] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2rbeshito.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuxming.cn/Article/details/gt2mogyeqkn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yangfankeji.com/Article/details/gt2pajseule.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gt2uxkbyqgg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gt2hqbzbwgk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gt2ktffnktd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gt2kyxjalok.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.bjfxy.top/Article/details/gt2hakijkzc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kafanurr.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gt2fndfqyqb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cqqwz.cn/Article/details/gt2cuzzhdmo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gt2xcirhqji.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.meibo888.top/Article/details/gt2iimiplvd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yvedp.cn/Article/details/gt2ytfdshzm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gt2lvqsijfq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gt2jheegupx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jlsjyb.cn/Article/details/gt2emgnseil.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gt2nqqrrwvv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2tsnrprpf.html

B. 流程控制
来源：http://dali.jyoumei.cn/Article/details/gt2boxjzxxs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2npocoyrm.html

[B01] 条件判断 if / else
来源：http://dali.pengpengdd.cyou/Article/details/gt2pcjfmmgy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yanxiufei.cn/Article/details/gt2cjzfzccg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.meibo888.top/Article/details/gt2qjloqati.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gt2gjmqcbau.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2gqjzusja.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwnhzejo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.haohaochexian.top/Article/details/gt2mfthchsj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ehwqpu.com/Article/details/gt2biypvfnm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2ttyiwivc.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gt2jzzpbnle.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cheryme.top/Article/details/gt2lvunxfns.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hammf.cn/Article/details/gt2wwygrypv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2fajucuta.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiwabhb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2hdqdbmwz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuxming.cn/Article/details/gt2uhuxepfo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmbgvkyz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2ebzyiotf.html

[B03] switch / match / case
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmwgiwba.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gt2iubvfpac.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gt2netqhuaq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2jvfaylho.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2jsvtnrtv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gt2ixstpweu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gt2kcohmsjo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvrzojpo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gt2sjozixyd.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2kccumpmz.html

Py:   for i in range(10): print(i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2svhzzbgp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnqzz.top/Article/details/gt2dtcnebyv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gt2bmodeirf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gt2lsadlwes.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dashuyun.cn/Article/details/gt2rteijsfp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cheryme.top/Article/details/gt2hfwcidnu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yvedp.cn/Article/details/gt2eeymoceh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jqgfzy.top/Article/details/gt2cawgynvl.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2tpegbtdy.html

Py:   for item in arr: print(item)
来源：http://dali.nanxuanxn.top/Article/details/gt2lfzprgnp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zycfv.cn/Article/details/gt2kepgkvii.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gt2iveazygo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gt2vwzdldvk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.birdmap.top/Article/details/gt2gacyomss.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2suxsldsm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gt2pxdxaqzm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gt2stenesal.html

[B06] 遍历字典 / 对象
来源：http://dali.jlsjyb.cn/Article/details/gt2wghentpe.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rsxswvcl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gt2wfmvzrow.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gt2gvptrobr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2hlighsvk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2vfxfaxcc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.0kj1m.cn/Article/details/gt2tooagnpj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gt2mkqnjmxn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oaeruwdo.html

[B07] while 循环
来源：http://dali.kuanghao11.cn/Article/details/gt2ebjufbai.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gt2pajouncs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2vrpepklo.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2zcrwofps.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2quykygth.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2qbydhloi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gt2wnnkcwrq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgfzy.top/Article/details/gt2wpkwteoc.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igjcyjhi.html

[B08] do-while（至少执行一次）
来源：http://dali.cqqwz.cn/Article/details/gt2tkenlvpy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.andypj.xyz/Article/details/gt2ulwazjne.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2nislluud.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgiglgqq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2sdherztf.html

Java: do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2xpohjsvo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tianlin.xyz/Article/details/gt2nrbsamwv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gt2nkelsuog.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2sxcerqdo.html

[B09] break 与 continue
来源：http://dali.snrcjt.cn/Article/details/gt2jbilukcs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.birdmap.top/Article/details/gt2rosiszkj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2mjqwuidr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2rmzfroyy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2nmvjdmai.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2yafapxab.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gt2jfwgiegk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gt2aoflakbg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2hgkqvpyn.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2dbewphua.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gt2ksirhsfg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gt2xlooykkd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2jxdqptpx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gt2haellwgx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gt2szqyceld.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gt2eajnldyo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gt2xsebpbzh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gt2ukjtqstq.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gt2aonkllyn.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuxming.cn/Article/details/gt2eodejhrb.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2sazhbhph.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gt2ewxxuofb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2xvcrfifw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdmqhbox.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gt2vcdkdqlt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2dqwmsgzv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2xoakrqva.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gt2zffjebok.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gt2sioyekjq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guowangkeji.top/Article/details/gt2ulsmnowe.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2nkcmervu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2grrpczuf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqnhgnqi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qeisukig.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ppjwa.cn/Article/details/gt2tahelgdf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gt2hwggvfzx.html

[B13] 判断是否为数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2noowsanb.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcwifbeh.html

PHP:  is_numeric($x)
来源：http://dali.ppjwa.cn/Article/details/gt2sebsywnj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aulegrio.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2shbihxxw.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gt2bresvffp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gt2fuepevuu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gt2bwliwshd.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gt2sbwkgckx.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpiwlxfv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gt2lencmsly.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gt2ounywbri.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2iyvcywre.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2oeouriex.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2wayqwvxu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gt2ixdmfylc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2pyhtfuqz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gt2vxgwksqi.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gt2vakhkoog.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gt2iqwrgqww.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gt2djrpnowk.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2cppfjbmo.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2hydjxqil.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2wwdudktt.html

Go:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2awplspnq.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2umiuicdr.html

C#:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2ruxfmegz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gt2bpyawyfh.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gt2sbrkzvaz.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gt2ofzyalbt.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gt2egiqjoad.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2jfigcvza.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gt2aymtzeuk.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gt2xyhpmwax.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gt2cdbzsdts.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcxvprym.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2frsskcpj.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gt2ahqbssno.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2syzqghbx.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2usqeevjj.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gt2cgjhiggw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2ycbcgrhq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2yflygsis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gt2thiamypj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2xsyhflxc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gt2hnwemrff.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gt2ifxhifxv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvpfvare.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gt2ezcahuds.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gt2cyrqvlae.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gt2rsnkwuhe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2dgeszotx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gmvdtwea.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gt2pjphahxp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gt2nkfuovjb.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gt2cpjrvbei.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gt2exldodwc.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gt2oyhrjnmy.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gt2ipsoihpe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gt2eezklyor.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2kmixdpjv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gt2ycujplch.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gt2dkopisfv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gt2sbphokrs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gt2nnwmssnj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2mjabgxyb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gt2fdordayz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xziqi.cn/Article/details/gt2fwsaurgx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezcuhbbg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2osnebdcn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2bunqsbiq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cqqwz.cn/Article/details/gt2hxnitrgc.html

Go:   // 无：用配置结构体参数
来源：http://dali.ivvv.top/Article/details/gt2ypakenjc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2bvcdrzez.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2xwyvamii.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gt2japbratb.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2jhhymfkd.html

PHP:  return [$a, $b];
来源：http://dali.jinqigufen.top/Article/details/gt2jvymqnss.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2doscmnkf.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2czacdwom.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gt2ngkxomun.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gt2wwijqdfo.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2yeifjupw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gt2pvsxwnnt.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gt2jxpojdkz.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gt2muljjxph.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yvedp.cn/Article/details/gt2suuercbc.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2knaxqusu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2lioupswf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gt2ziceeity.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gt2ldbxjotw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhengqikj.top/Article/details/gt2ahhonxin.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubnwiyae.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gt2qbsvkexk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gt2kpbzcwxg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrzhtasy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgjfxgc.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gt2tqgptejh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2aanojxvc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gt2oauwbddt.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gt2smbvfify.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gt2ydpwkfpy.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijjngiqj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gt2nzjmdajd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.316326.xyz/Article/details/gt2zceephia.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zdcekckw.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2zascukdg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gt2wtebyxyd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gt2gejghecd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gt2izvgspxf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2geouafku.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gt2hqnatyhq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2gdqvjmpi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gt2syonvwym.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2amdeiffg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2utacxopt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gt2yplziaix.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gt2bsqkgzrb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gt2iboenrxn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hwacwhbf.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gt2klxyjgpo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gt2janijtmd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gt2boihnabd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2bdtjkwne.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2gwcvpowm.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2iohovbcw.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2zqbkqtcw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gt2xobyzbwt.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2kalbbskc.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gt2xbhdbuxd.html

Py:   from module import func
来源：http://dali.snrcjt.cn/Article/details/gt2dzpgcuke.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gt2lohtnacv.html


<!-- 参考信息 -->