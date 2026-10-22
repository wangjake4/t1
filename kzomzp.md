代发 wailian999

Ruby: a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gtyhlhfiri.html

C#:   (a, b) = (b, a);
来源：http://dali.yonumen.top/Article/details/gtiwowolmw.html

[A20] 读取标准输入
来源：http://dali.tianlin.xyz/Article/details/gtadxqkwko.html

Py:   name = input("请输入：")
来源：http://dali.jiagoushi.top/Article/details/gtzbwhvfdr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.guannengcc.top/Article/details/gtouwdxfpq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zdqjudy.top/Article/details/gtpzfsirss.html

TS:   // Node.js：readline 模块
来源：http://dali.tian-w.cn/Article/details/gttbcglcjg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.nanxinkj.top/Article/details/gtqsfdoekq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhongyouzk.top/Article/details/gtdekvohuk.html

Ruby: gets.chomp
来源：http://dali.sweek.top/Article/details/gtrlcrdowh.html

C#:   Console.ReadLine();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvqumyof.html

[A21] 保留指定小数位输出
来源：http://dali.hywenlv.cn/Article/details/gtazzkngjl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jlsjyb.cn/Article/details/gtaxigprmq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtioposuzh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtgaaqptkh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtxkfnhvug.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtkklekxut.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtejlwsakd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtbapdhrhp.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhfvcllk.html

[A22] 获取字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtsszajink.html

Py:   len(s)
来源：http://dali.aibaodan.cn/Article/details/gtmlcnulcx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.iojbl.cn/Article/details/gtyghovqmg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.fzhhl.top/Article/details/gtproqesse.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gthvkucwfm.html

Java: s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtmxywdmis.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenlongwang.top/Article/details/gtoayvwalr.html

Ruby: s.length
来源：http://dali.zhengqikj.top/Article/details/gtlcqpkuqd.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexfhmzeo.html

[A23] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtprqewspi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nwbrower.top/Article/details/gtvzglgviy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gtbanuuacx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gtugcfyssp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gtglaqsmow.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gttyyufyvr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.svipenyu.cn/Article/details/gtjyldvtkg.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtibbizyto.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.andypj.xyz/Article/details/gtpdysllew.html

[A24] 去除首尾空白
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqddssvi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigfzy.top/Article/details/gtajjvhjpj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.guannengcc.top/Article/details/gtgzzizzsn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gtjwmgbwct.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtnzbsrbcb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jlsjyb.cn/Article/details/gtpyurtzwp.html

Go:   strings.TrimSpace(s)
来源：http://dali.9152youxi.cn/Article/details/gtuezaaygy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guannengcc.top/Article/details/gtzebyqfde.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.gzhubu.top/Article/details/gtciatmgnq.html

[A25] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtwhwuawfl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gtfxsgsnrd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cheryme.top/Article/details/gthsrwzcxp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoxmvyvx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gtuejqoqab.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.snrcjt.cn/Article/details/gtdtoeswfl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxhevgxug.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioaambkj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gtpfmukrku.html

[A26] 类型转换总览
来源：http://dali.xuetiantiany.cn/Article/details/gtqgftasup.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.316326.xyz/Article/details/gtatzvvzsf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.316326.xyz/Article/details/gtbcnkxahk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj20258888.top/Article/details/gtxznsibay.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aizwys.cn/Article/details/gtvsexmlgt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtohywuqnj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gtxkdslltl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuanzhike.top/Article/details/gtxhutkzwq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj202588.top/Article/details/gtlklectyp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzmiqgibq.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gtditctaqb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttbpzbpgr.html

[B01] 条件判断 if / else
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsmjlwmk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gogol.net.cn/Article/details/gtzyyvripd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hywenlv.cn/Article/details/gtzgqzcqhv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtqhixchri.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtloegjtkm.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gteuzlgxrm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhiwuduotai.top/Article/details/gtiwkdcwan.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gtupxqobvh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtejfiaamf.html

[B02] 多分支 else if / elif
来源：http://dali.mhx1999.top/Article/details/gtwrkkyccq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gtsqbaqdle.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigfzy.top/Article/details/gtvstooyrh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtyjoxdxhl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtuafiwtuh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gttftqqjas.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gtbammkmik.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hfpthk.cn/Article/details/gtsqpffzvm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtzalmjddc.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gtoodnevtx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtfllxjkmy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtnvbjrrhk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtmyqukhlo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtfwxeayjj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gtanvhjclo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aibaodan.cn/Article/details/gtyfifnhzr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gtqunfstyj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj202588.top/Article/details/gtoxfjsdmw.html

[B04] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtduthgzik.html

Py:   for i in range(10): print(i)
来源：http://dali.vqdsnc.cn/Article/details/gtynnygwgp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuxming.cn/Article/details/gtbflcwrxf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gtwvcrpfma.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtdnfagncv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gtwviecrfe.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gtdgbtdnlp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyepqxqe.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yongpay.top/Article/details/gtjnafhosq.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtcxzhwsjy.html

Py:   for item in arr: print(item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuhcytpe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gtdpyyupbx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gtouumwevj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtrkhjllkq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yongpay.top/Article/details/gtyvolvbky.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteghyqdka.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtlhqwwyhp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gtfaswaboo.html

[B06] 遍历字典 / 对象
来源：http://dali.tanke756.top/Article/details/gtdikczprq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhixingplan.top/Article/details/gtbzrkvydv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhongyouzk.top/Article/details/gtswbpigfk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gttnavbyai.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtabegbeox.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsjntysda.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimfygiec.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jiagoushi.top/Article/details/gttnbljges.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gtfruhwpbd.html

[B07] while 循环
来源：http://dali.redwolf501.top/Article/details/gtrwmpmbjd.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gtseaxjfcb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.guowangkeji.top/Article/details/gtwxlbixjx.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gturwaxodf.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtaqbfasyr.html

Java: while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtsgooxwdg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gthgicgtan.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yueranfly.top/Article/details/gtqegqxjza.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtwndldxzq.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtyhfnujam.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gtxxcewecu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ybcxt.top/Article/details/gtcmfffakh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtlmqrnuwd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtgpimtrgg.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtwrovcdni.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtqdbbilgd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258888.top/Article/details/gtvhhvjuyd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtqdckwmac.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gtifkcadaz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gtysrxivhe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtcffgntsa.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtugbrfylc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gthzzxmupl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtxadwrwye.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtgflbhojs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhoulong.xyz/Article/details/gtotubweiw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtworxixal.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtwderzyrr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yongpay.top/Article/details/gtjnwvoizj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gtxotermtc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtmifznjdc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gthtsfpnqv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258.top/Article/details/gtdzoauacu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtpredubkv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cucudq.cn/Article/details/gtdffsiqsc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gtjcarhghv.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtpxvkifye.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gtyaruimib.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gtbgvyttnm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtjjfodgmj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtoiroboqy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gtngxmmbus.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtymcwlazj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtyloalbsq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gtirgjbydf.html

[B12] 跳出多层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcvyfbpm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gttrskpbbr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.guowangkeji.top/Article/details/gtarvztaum.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtdokwwbcp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtizjjgogb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtrrkulzuu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfhcswlny.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtypweodgo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guowangkeji.top/Article/details/gtjqbrefxq.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtwcnluslo.html

Py:   isinstance(x, (int, float))
来源：http://dali.nwbrower.top/Article/details/gtanqbczxy.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtmmoeqlyt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtrtpjnspr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyqpcidw.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtwgwgdrym.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.bjfxy.top/Article/details/gtwdakzvvp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hywenlv.cn/Article/details/gtzxpmfggp.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrirqydj.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtmdmnczyb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtarfnqbrv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenlongwang.top/Article/details/gtsvdukcue.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtuwimtchg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtmnpcegcs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtwnqphifx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ppjwa.cn/Article/details/gtggprwbxn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gthlcpaytp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtqukqyidw.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtatbleiiy.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gtsxaxmfwt.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtcaqtghjf.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtgjoruask.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkousjlch.html

Java: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtllhxvbmi.html

Go:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtnztsyfkt.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtauqpemdo.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtvbfnibii.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gthmnaoxwc.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gtnllzymsh.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gtfqrmevdg.html

JS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtbdxjugkh.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtlzaiyxpa.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gtvrjphvuv.html

Go:   if data == nil { return }
来源：http://dali.ppjwa.cn/Article/details/gtqmyafjoi.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtprguumie.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtzuqymxrr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtuwpaplio.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gtihcoqzdp.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmppwfvix.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtugjabnmj.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtbieicddr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtjibmkvag.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtviufilhd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtmfyebnqu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwwdqmuuv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtrjtfgipp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzwlkchz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybzcnjfb.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtzufubjug.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gtfinsfkjn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gtjhmcigpz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gtqegtccbs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlipdofee.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtbyehwcgn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gtzibyltbd.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtilldyyal.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gtgejmqqzl.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gtmrfuyvde.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gteavldxcu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gtjhfysdmf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtsgrphbzw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gthnzuuvzm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gtvmzaqrls.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gaohongyu789.top/Article/details/gtzdbigjbh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtdmkvvdfd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtefdhgqza.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gtojnzuhcw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbheuhax.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtlvlxuloq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtitsxphrs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtlwirplzc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxvoxsjx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtryriiujy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtabbqawqh.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtayfqzqdf.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtghgayjbw.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtdlmbqzie.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gtlkukmrdy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fzhhl.top/Article/details/gttdfpvabx.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtqgrygdrn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtjjtttuqm.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtlvripwzz.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtxreutwpn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gtqtwszngj.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gtjqkzauwd.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gtyzqvubue.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gteysifxyy.html

JS:   const square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtvwdhsttb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gtozezgjsq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfsxgngv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtsfsvkgyv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gtmloyrwfb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtbcsexbgd.html

[C07] 把函数作为参数传入
来源：http://dali.aizwys.cn/Article/details/gtoqbjexxv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtdujwioxz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtoqsafaxg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gtjmmwlqsb.html

TS:   arr.map(String)
来源：http://dali.hammf.cn/Article/details/gttjyswcgc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtzamznrbd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtiaosalhs.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtccycyage.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gtmmgskqgj.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gthrpnksjc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtvmdmpmpa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gtvuzjlwyp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtyhtkltiy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtjwzxqiij.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gtbybgahym.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtlindnkgi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xziqi.cn/Article/details/gtikezhkdg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtybfbyjgq.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtlndfzuen.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtessixnyy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gtcybshlpt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtpugoslqy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtfdrwlrzb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtitrrqpxi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gtrgytdbpu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtquirekfj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtcnenrzcz.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gtiboikcgs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtzfbjgkvx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenzaomai.com/Article/details/gtrskrzopv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gtiuevrrqs.html


<!-- 参考信息 -->