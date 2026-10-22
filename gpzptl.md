代发 wailian999

Ruby: a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtjigphitm.html

C#:   (a, b) = (b, a);
来源：http://dali.hnqzz.top/Article/details/gtcnkbdjml.html

[A20] 读取标准输入
来源：http://dali.yj20258888.top/Article/details/gtspnnxsyb.html

Py:   name = input("请输入：")
来源：http://dali.hywenlv.cn/Article/details/gtykzwxmnj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj20258.top/Article/details/gtmtigeyxm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sweek.top/Article/details/gtjkjfners.html

TS:   // Node.js：readline 模块
来源：http://dali.ppjwa.cn/Article/details/gtreedrfac.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yonumen.top/Article/details/gtqyqnvxbe.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqistxylk.html

Ruby: gets.chomp
来源：http://dali.cdnleiting.top/Article/details/gtkqwvvzyq.html

C#:   Console.ReadLine();
来源：http://dali.haohaochexian.top/Article/details/gtntbflalk.html

[A21] 保留指定小数位输出
来源：http://dali.xuetiantiany.cn/Article/details/gtzvwgsumq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hysaishi.cn/Article/details/gthpyjnaoy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtecrlgcyo.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtxnxrjfzj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtcywuwkbu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtdvidjvfm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtayntxglj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtzofjxhcd.html

C#:   3.14159.ToString("F2")
来源：http://dali.gogol.net.cn/Article/details/gtxdidohvd.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtdghzyxoz.html

Py:   len(s)
来源：http://dali.sysykeji.top/Article/details/gtwgoykfya.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj20258888.top/Article/details/gtyorezgor.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ydzc1.top/Article/details/gtviyjgfze.html

TS:   s.length
来源：http://dali.svipenyu.cn/Article/details/gtmzpbyutz.html

Java: s.length()
来源：http://dali.sweek.top/Article/details/gtvfeumenx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cqqwz.cn/Article/details/gtaiknkhzn.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gtocpcolhn.html

C#:   s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtnhcjjbbp.html

[A23] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtovzptoyz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sweek.top/Article/details/gtdbuetpou.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jyoumei.cn/Article/details/gtolijpnov.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtyaoizffg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtegsonyxb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtfmfybmyr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhoulong.xyz/Article/details/gtzxciyyru.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdumufpfv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.iojbl.cn/Article/details/gtfyghmkku.html

[A24] 去除首尾空白
来源：http://dali.pengpengdd.cyou/Article/details/gtlfsneibz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xinyue.icu/Article/details/gtponecnid.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yueranfly.top/Article/details/gtyjpywvvd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtdcemqbik.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sufxvd.cn/Article/details/gtyhwqrbyo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nwbrower.top/Article/details/gtbftyipwk.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gtwvgsqfoj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gthvwnzpdj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cqqwz.cn/Article/details/gtshgrlgpa.html

[A25] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtyhurihdi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aizwys.cn/Article/details/gttmuialns.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuxming.cn/Article/details/gtnmjdtcln.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtcwegbbon.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dianchejie.cn/Article/details/gtdvgrptge.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gtouyyqjlu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtfubfbcag.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.birdmap.top/Article/details/gtajdddpgk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gtonbzwmdq.html

[A26] 类型转换总览
来源：http://dali.xuetiantiany.cn/Article/details/gtsilnrocx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuanzx.com/Article/details/gtghanszjl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmzglonv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yongpay.top/Article/details/gthzolhzoz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenzaomai.com/Article/details/gtjocoexgu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtkklotfgq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258888.top/Article/details/gttkplvyxt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.meibo888.top/Article/details/gtcoyfbqcs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtvnqurpmu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtiitmkcfv.html

B. 流程控制
来源：http://dali.zdqjudy.top/Article/details/gthqkmcmii.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqmwhqrtj.html

[B01] 条件判断 if / else
来源：http://dali.shangyingyoupin.top/Article/details/gtpsdspxso.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sysykeji.top/Article/details/gtijufhlxx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gzhubu.top/Article/details/gttpmwelgs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtyxlpkukq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtjbyfeflj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtgunahkzb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.meibo888.top/Article/details/gtuzolukco.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guowangkeji.top/Article/details/gtivhtwooi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtldxozokg.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gtmfujqvqv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aibaodan.cn/Article/details/gtnjszpcmq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwxhiqund.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtkjyokmfg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtmfbiismo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtwfvqrpbw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.vqdsnc.cn/Article/details/gtekcbxyry.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yonumen.top/Article/details/gtotljgywh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnroxjkl.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gthucpjrkt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.andypj.xyz/Article/details/gtoankubyp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtokgtcsgz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtxhroiuis.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gteuvtsdpm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtljeiefhd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtwhdahowj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gaohongyu789.top/Article/details/gtzqeaudwp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtbhkpxfzl.html

[B04] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtjteutiku.html

Py:   for i in range(10): print(i)
来源：http://dali.yvedp.cn/Article/details/gteqbqwoww.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gtlzzuhxnw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gtczqohexb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkdnzarqy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczodbnex.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gtdeyqcmqq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhixingplan.top/Article/details/gtnqxspcvn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zdqjudy.top/Article/details/gtrzalcivp.html

[B05] 遍历数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtjmxdbnem.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gtmoqpwzoj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gtgtfencwq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gtbfjsvybr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtfwsapnuh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtouxuxntb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenjidiqi.icu/Article/details/gtpbcniwso.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhpbbfgy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nwbrower.top/Article/details/gtpondkeew.html

[B06] 遍历字典 / 对象
来源：http://dali.chenlongwang.top/Article/details/gtlyiwtdoi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.316326.xyz/Article/details/gthrmozkjn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gtheoimmht.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtdeyavhwe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gtvfuosfrh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj202588.top/Article/details/gtsfdtllyf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.feifeiyinyue.top/Article/details/gtbvwbjzhw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtpbfetruo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuanzx.com/Article/details/gtcdzabhsg.html

[B07] while 循环
来源：http://dali.pycfn.com/Article/details/gtihvvjdyc.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gtbzigscba.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj202588.top/Article/details/gttmvttkac.html

JS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtrbzssfgs.html

TS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtjzyyrcaf.html

Java: while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gteqsimbhk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gtpfgfdxle.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gtfagfbinp.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtgqfszlza.html

[B08] do-while（至少执行一次）
来源：http://dali.cheryme.top/Article/details/gtonzpvfon.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gtcrhzfsvu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gtmcefufwq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gthqjakjxq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtxgobqdlo.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtmyrrnoci.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtclncdboe.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sweek.top/Article/details/gtnixgbwfw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtaxvknuva.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gtgwykqkay.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.svipenyu.cn/Article/details/gtbndrdprs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtmueqbdvl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gttqkauhok.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlasrlnd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtwkbaawwp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sxryk.cn/Article/details/gtsahoxfws.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pycfn.com/Article/details/gtvaqjcmfw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtmdaesygf.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gttrlwnzwa.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gtdoojbqpd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gtiehohkxb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtmzwdgegs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gtfsjqadtq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkuknedbk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gtotwixyhk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gtzuobganp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dianchejie.cn/Article/details/gtzlxkvcts.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtqjsqohgc.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gttpssavqv.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gtxrasakrf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gttwsvimdg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtufbooqno.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtwiwgdasy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gttzfqwire.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhegcaaa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrlabgxw.html

[B12] 跳出多层循环
来源：http://dali.guannengcc.top/Article/details/gtkxvuwckp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gtfbkqsulp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gtvnzrsnhx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtovgzybgg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtvfgqcifx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtojfxssvs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gtzrrjlalh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gttgchzqzz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtjnupvmyo.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gtigjngmxq.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtwsthsije.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtbhkchtmf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gteakgeylp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtusbgyobe.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtwgkuzxtg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pengpengdd.cyou/Article/details/gthcbdgzey.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gtpvmfhetg.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpklnfjas.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtnndaedjv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtasmzztkm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtezxvrmum.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtvctgnaed.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtkrsampsn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gtnmewkmvp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gtpbtjfgoj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtkgsgkccm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtuwqmpdgh.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtitxfwszv.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gtbjgqwdgn.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhwdmxqr.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtuhrwfcfx.html

TS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtrsbbtvto.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtoykebjyt.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gttrdiboap.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtuvmqkzub.html

C#:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtozacwmif.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrwudwzl.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtmjumqgju.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtwsxxdkse.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtoblyyiag.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtmppdjnxu.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtlxdjtcov.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtqzmxdwwp.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtkqafodil.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtogwauqnx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gteyymzqup.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtnlafglxx.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtugqmrwlp.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtfbkewfbs.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtpbewbsev.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtbiouaipc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtfkrxqgiy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtvqrpflnn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtcenotrjs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gtvragjxyl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gteimwrkyz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpniyqwh.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtjlggcdyt.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gtazqvvukg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gtkuuehquq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblnxlkjx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzdbqcrje.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuccpkcw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalyvurat.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gtvlnvlmyn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gtwtqyattm.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtljjkwytq.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtnpmsyyde.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gtsujbmick.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtyqpcwbnp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtdhxmwsuc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gtuevuqgkt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtossofigf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlazipud.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtdtkzhrsr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtxfmjicmp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gtzjphfkif.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.aizwys.cn/Article/details/gtplogfosi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkvkzjtei.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gtxilnstcw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gtomtwezax.html

Go:   // 无：用配置结构体参数
来源：http://dali.jyoumei.cn/Article/details/gtaaxxgbaw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtisegpygh.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtctvyoqyu.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gteztgykga.html

Py:   return a, b
来源：http://dali.sysykeji.top/Article/details/gthfaubbbq.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gtevisunbf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtjmcglrhn.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtdomhvweq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cashguo.top/Article/details/gtrfxibyim.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gtavoesayi.html

Ruby: return a, b
来源：http://dali.jyoumei.cn/Article/details/gtinaonrcf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtwlscynnr.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gtsctitbkx.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gtnjyhhngn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtwaklxpem.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtyarhparv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtdvmrkyko.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gtignxxtaq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtoxawqola.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gtyhbnvwwc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtajremgyl.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gtgcswpnnu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gtfzxlydel.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gtjqdsqmqj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gthgwbjhor.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtoppfnqeh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtmjeaxiyw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtnjcuxnka.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtetfjrhpw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.feifeiyinyue.top/Article/details/gtilmilsno.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtfniqsysp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.svipenyu.cn/Article/details/gtohbbfvde.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtakvqbcms.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtfreybtco.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gteyobeefc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gtjrorpicr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gttmsaeeno.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtmgkbhtou.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtvumzbteu.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gtycihcwhj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtqquuzkru.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtsqfhawnv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtlugiofjt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtunykueyw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtfpxfpafb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtphuuccex.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtsmepgxku.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yonumen.top/Article/details/gtemafwdyd.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gthemaqoyu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gthzwqmjhj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtvudgxmod.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gtalbmwzqr.html


<!-- 参考信息 -->