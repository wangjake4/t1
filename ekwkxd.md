代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqwhhttx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.meibo888.top/Article/details/gtvfougmga.html

TS:   // Node.js：readline 模块
来源：http://dali.chenlongwang.top/Article/details/gtqxommbrk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenzaomai.com/Article/details/gtjjpdysti.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cdnleiting.top/Article/details/gtldzilido.html

Ruby: gets.chomp
来源：http://dali.pycfn.com/Article/details/gtmxhtfitb.html

C#:   Console.ReadLine();
来源：http://dali.cqqwz.cn/Article/details/gtqqwrmccf.html

[A21] 保留指定小数位输出
来源：http://dali.cashguo.top/Article/details/gtejdovuly.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hnxiangtu.top/Article/details/gtgaxutvuz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtovyzgkik.html

JS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gtworiudlk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtfzuaosja.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtzjhatvud.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtcyvqnemq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtemiptejs.html

C#:   3.14159.ToString("F2")
来源：http://dali.xinyue.icu/Article/details/gtmbgqoako.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtyyyzbjel.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjgtwrazk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jlsjyb.cn/Article/details/gtwbkjmolc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hongshengwenyu.top/Article/details/gtlhdmyizn.html

TS:   s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gthzlfwgxe.html

Java: s.length()
来源：http://dali.jianghu66.top/Article/details/gtvsmhwkbv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xinyue.icu/Article/details/gteabtxmey.html

Ruby: s.length
来源：http://dali.zhoulong.xyz/Article/details/gthcupjoyg.html

C#:   s.Length
来源：http://dali.yvedp.cn/Article/details/gthzgjstjl.html

[A23] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gthavtesax.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigufen.top/Article/details/gtqdqqlqtb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ybcxt.top/Article/details/gtdidfagrd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtvujsutbj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gtmqbvggkb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gtdfxpstoj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cashguo.top/Article/details/gtwyqqdmdi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtggtpkprq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhijiandao.cn/Article/details/gtuvarnahm.html

[A24] 去除首尾空白
来源：http://dali.yuanzhike.top/Article/details/gtlligindb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cheryme.top/Article/details/gtgvwrkolg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gtchcopckq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ehwqpu.com/Article/details/gtqjetxphs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtrnwvgkkk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinqigfzy.top/Article/details/gttemhtaee.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtvcaiffqs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinqigufen.top/Article/details/gtkvtppdqi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtgahecrkg.html

[A25] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtsqhtmvml.html

Py:   s1 == s2; s1 != s2
来源：http://dali.andypj.xyz/Article/details/gtpqjgcfka.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sufxvd.cn/Article/details/gtxvoxpzfe.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tanke756.top/Article/details/gttfsccfqr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gtbwkwtsbl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpxecgcb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtqtahhsww.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.andypj.xyz/Article/details/gtijwicsrb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtmdqwqgvl.html

[A26] 类型转换总览
来源：http://dali.dashuyun.cn/Article/details/gttsapzlls.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tanke756.top/Article/details/gtupquouii.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcskmgwtq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zycfv.cn/Article/details/gtxydxqzem.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuxming.cn/Article/details/gtsbczijhs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gtbhmuferc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtqnlqlcxa.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sxryk.cn/Article/details/gtuiiyrlkd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gthwkmzxmu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkjjubkds.html

B. 流程控制
来源：http://dali.cdnleiting.top/Article/details/gtvluioaak.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttnjdsnid.html

[B01] 条件判断 if / else
来源：http://dali.yueranfly.top/Article/details/gtcyxdxrns.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.shangyingyoupin.top/Article/details/gtfcxvevhu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cheryme.top/Article/details/gthiyvwxhb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtlzezkwej.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtzdsouumz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtrldaidiy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gtpenxpdyr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhengqikj.top/Article/details/gtqbognvlv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtvvueahis.html

[B02] 多分支 else if / elif
来源：http://dali.yuxming.cn/Article/details/gtflsrfaxi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofnvanqa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgricepsg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtyrllyqvs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtjntphoye.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtsplzegpn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shzxlz.cn/Article/details/gtqgpzjifq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.9152youxi.cn/Article/details/gtgftyrvte.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtwgvhzxdd.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gtdaduvnvp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gtpktkklys.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtppfquehy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtomouclka.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtxmmtcrxh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtpjqwgvtl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yueranfly.top/Article/details/gtpgpbiski.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.redwolf501.top/Article/details/gtjhbdbcor.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sxryk.cn/Article/details/gtbziweswc.html

[B04] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtbwnfzrwp.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gtkqmhkweo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhijiandao.cn/Article/details/gtoolxtevc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gtxjrhxrck.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhetewxp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.havefunace.top/Article/details/gthckonofc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gzhubu.top/Article/details/gthrofxvxf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shuidangran.top/Article/details/gtrjddbjqj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.9152youxi.cn/Article/details/gtygwoebxk.html

[B05] 遍历数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtxzleqpyd.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gtsooylezd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.meibo888.top/Article/details/gtchstjiih.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtzcwaxsii.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gtcqslhimz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yvedp.cn/Article/details/gtqparlrbf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gtuaeoviei.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gtkjvqsaxu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtkuxmyynp.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gtvcbrgqpl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejgtyazn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gtrgyitgbm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gthfubzwtx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtzlqrljgr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aibaodan.cn/Article/details/gtlpvpqmuf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gtdxmlmamw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gtvjhecyso.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtngpmtzco.html

[B07] while 循环
来源：http://dali.ehwqpu.com/Article/details/gtxrnmsczu.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtxtqtixfy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gtsjwwbmyd.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtpgdddmhr.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gthtkuzbfx.html

Java: while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtmzqsfuxs.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.havefunace.top/Article/details/gtuhxravqx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ivvv.top/Article/details/gtslutflbo.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtbmtrwrno.html

[B08] do-while（至少执行一次）
来源：http://dali.tian-w.cn/Article/details/gtfjvtnnpt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtzwjhzxmc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ivvv.top/Article/details/gtspyajasl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtuagopbsj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtecpyksoj.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtckqwnsbs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtxmltkyoi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gtcxntxepg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtqahviogh.html

[B09] break 与 continue
来源：http://dali.zhengqikj.top/Article/details/gthhyabnwj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtuxbdffzy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtsosmjbfs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtjqulywhk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtipdkcrdk.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtqftvywlt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtdvyhjupg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daria6918.cn/Article/details/gtvfhekwyo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtmoqjlqos.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gtaaqblnvk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvumigloc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmtbjsrex.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtgdwmrmdm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtnhezksva.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsnzfblbr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenjidiqi.icu/Article/details/gtjcpybdhf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtyioimfzo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cashguo.top/Article/details/gtnctyqlbb.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gtdvuhwckf.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gtabfvivda.html

PHP:  range(0, 10, 2);
来源：http://dali.cashguo.top/Article/details/gtrgykhjfh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtefcduufj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtgtbygkgn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtocprdgtf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtvuyvqapw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtbjidlqwg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gtfsbaoejt.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtuktpsego.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtumkhppth.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gtkbsvxlcc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtmgfuwdol.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtbqubnbpm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtydeiqvxt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gtfnvuurtk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gthoxlrdil.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhiwuduotai.top/Article/details/gtyandkhxu.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gteqlxvyym.html

Py:   isinstance(x, (int, float))
来源：http://dali.ivvv.top/Article/details/gtikbklayd.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtguuiyaow.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtjaiaqbzn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gthaywkcsm.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gtbflpycml.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gtanevateb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gtcdpeucam.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gthcrawauo.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gtzodwllcj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gtxcdcbxhw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuetiantiany.cn/Article/details/gtvlaxstkt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtqgjsrgef.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtblcvbfsq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gtaejyyowe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gtlsdppzyg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gtislmtvrk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtppatnbbn.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtlhlgeppo.html

Py:   a and b or not c
来源：http://dali.cucudq.cn/Article/details/gtmdmzmfso.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gtcplhmcqt.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtdpjqbwgr.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtxqvoeqes.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtzlowghkf.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtmdavzcki.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtpndimgux.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtwfcasgvp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtpwypolhp.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gtjwthjfwj.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtbtjdzbcc.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gthobpandy.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtpcuvfdel.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtcscbwxew.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtbwapvvjj.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gtlmybeanc.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtzibiikcy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjnzdtpow.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtvwehcwrn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtrqxcfztp.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtwzzoratm.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gtalqyyjux.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtobklcuuf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtfnuzwkai.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtniuzztzx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtitarhaps.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtiipfiuyv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gtfcwvwczq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtipumkvtg.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkttyqwkn.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtqsdplmvt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.dashuyun.cn/Article/details/gtznzjzpvh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtmdmkyzvb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtlmqmcxhy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gtbbeclpqi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gtjglthexo.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gtfscidksa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gtekyiueby.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtuivcjwze.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gtkmovejer.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgufenzy.top/Article/details/gtexauphhd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtnbtvnrvj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gtokijcdev.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtahjcugnw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtxqoiowjt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtollmgfed.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtkuxywbjl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtaotkyspp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtqlvlejtd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtrdlsbtmm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtjsmslsvs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtnkicbefg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtmlrxonpl.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtsecqbcme.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtnjcvbilp.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gthwahxlhb.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gtdhxcybfq.html

Py:   return a, b
来源：http://dali.zhengqikj.top/Article/details/gtotpnjiwz.html

PHP:  return [$a, $b];
来源：http://dali.daria6918.cn/Article/details/gtkzaecvwz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtdqtxraiu.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtskqrkkmx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtndeclltg.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtfyxbmewg.html

Ruby: return a, b
来源：http://dali.guannengcc.top/Article/details/gtngenmbck.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gtvcxytxjq.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtavtydevj.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtrnxyvkua.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtjbazpgax.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjudpzboz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtmlpnvjce.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtsekrpbab.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtocggymsg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtgrxcmsia.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtiatvwqic.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtilllfbco.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gtwdlivaoy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yangfankeji.com/Article/details/gtwdbcdujv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtdvsdbska.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtwmttzxnz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.c1oappe.top/Article/details/gtyvvwkzyu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gtebatuyqe.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gtabqaadwz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gttnttpxvh.html

[C08] 闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxilvdowi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gogol.net.cn/Article/details/gtxumfoblt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gtxxhtdjqw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtblywtqgh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtiqugscnd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gtonmllqhm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuanzx.com/Article/details/gtxcjhpatc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuanzhike.top/Article/details/gtocejijex.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzmfniew.html

[C09] 递归
来源：http://dali.xinyue.icu/Article/details/gtgsomhrad.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gtmhvwiisd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtsbbammnw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtdzvsbivh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gtekdyryuc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtrgbkzyry.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtlgomrnwg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtlmdkfbsr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtcbrzjvqq.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtfrweatkr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gtdbjiyrps.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtsnckuakj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gtarpxxith.html

TS:   同 JS
来源：http://dali.jiagoushi.top/Article/details/gtmxoilszj.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtckwuqdlk.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtyjwajcxh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimlycpmn.html


<!-- 参考信息 -->