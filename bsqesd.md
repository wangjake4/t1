代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ybcxt.top/Article/details/gtxgtcnxze.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxuanxn.top/Article/details/gtnzovcvrz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tanke756.top/Article/details/gtolmzhwtu.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gtbvpvqcyf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtnwpfuqqb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xziqi.cn/Article/details/gtxbmjthkk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiusgeed.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtneahxnfq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtadixtglk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtowwamknh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtuaygrpwt.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtitpmqbhe.html

[A18] 字符与 ASCII 码互转
来源：http://dali.vqdsnc.cn/Article/details/gtqkvpfofx.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gtnmfvlkrb.html

PHP:  ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gtqpwudmba.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhoulong.xyz/Article/details/gtmjmmcilh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xinyue.icu/Article/details/gtacaapovo.html

Java: (int) 'A'; (char) 65
来源：http://dali.havefunace.top/Article/details/gtuxhtgfah.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.guowangkeji.top/Article/details/gtfvkeqwsw.html

Ruby: "A".ord; 65.chr
来源：http://dali.havefunace.top/Article/details/gtwmadxfxr.html

C#:   (int)'A'; (char)65
来源：http://dali.ehwqpu.com/Article/details/gtjnbptona.html

[A19] 交换两个变量
来源：http://dali.dianchejie.cn/Article/details/gtlfbjbasu.html

Py:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtqklwrdaj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ydzc1.top/Article/details/gtqyxhnquz.html

JS:   [a, b] = [b, a];
来源：http://dali.bjfxy.top/Article/details/gtruwgzcqa.html

TS:   [a, b] = [b, a];
来源：http://dali.sysykeji.top/Article/details/gteoewkxmt.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinqigfzy.top/Article/details/gtribnlcll.html

Go:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gttstjexll.html

Ruby: a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gtizlogtcv.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gtbyrdsfaw.html

[A20] 读取标准输入
来源：http://dali.hysaishi.cn/Article/details/gtztvlwsxx.html

Py:   name = input("请输入：")
来源：http://dali.yonumen.top/Article/details/gtcggaxunx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuanzhike.top/Article/details/gtgsqkmdfm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhongyouzk.top/Article/details/gtptsdtiub.html

TS:   // Node.js：readline 模块
来源：http://dali.aizwys.cn/Article/details/gtfbbyfjwc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yongpay.top/Article/details/gtixgijels.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nwbrower.top/Article/details/gttvvjeldb.html

Ruby: gets.chomp
来源：http://dali.bjfxy.top/Article/details/gtqlrgdpzu.html

C#:   Console.ReadLine();
来源：http://dali.shangyingyoupin.top/Article/details/gtgrzdkmay.html

[A21] 保留指定小数位输出
来源：http://dali.havefunace.top/Article/details/gtgygjlkkm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.redwolf501.top/Article/details/gtaqpzpnjc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtlmztxfob.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtrpmxkegb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtvuzwxcto.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadlntfaw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtkstlgjyl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtsofzryeb.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gtpbdxposd.html

[A22] 获取字符串长度
来源：http://dali.mhx1999.top/Article/details/gtctdpqigr.html

Py:   len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfdqhntc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gotoacloud.top/Article/details/gtprzqcitj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ivvv.top/Article/details/gtkkpeckom.html

TS:   s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtvrrmfudv.html

Java: s.length()
来源：http://dali.xuanzx.com/Article/details/gtcwiabunq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhengqikj.top/Article/details/gtonyqrghv.html

Ruby: s.length
来源：http://dali.sysykeji.top/Article/details/gtvbrxatti.html

C#:   s.Length
来源：http://dali.nwbrower.top/Article/details/gtnvgobgoj.html

[A23] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gttteyktqh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtvrjlovru.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gotoacloud.top/Article/details/gtikrwfniz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtjrmfngtg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtcttejcvu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cheryme.top/Article/details/gtdkfuavbp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxuanxn.top/Article/details/gtudqkubxh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtwhoquigj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aibaodan.cn/Article/details/gtujwefltq.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtaadnuult.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hfpthk.cn/Article/details/gtcyronzhw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangdashe.top/Article/details/gtmdklfpnd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrxjuskp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtgxbozhcl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.guannengcc.top/Article/details/gtnfsxkskm.html

Go:   strings.TrimSpace(s)
来源：http://dali.yueranfly.top/Article/details/gtpurjvzbx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jlsjyb.cn/Article/details/gtjjajkhco.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnqzz.top/Article/details/gtasclndth.html

[A25] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtyybrjmou.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gtefdwcklg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jlsjyb.cn/Article/details/gtzjpitjeu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guannengcc.top/Article/details/gtgvwrutui.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shzxlz.cn/Article/details/gtvvvqfdbe.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.andypj.xyz/Article/details/gtiyfmjxyo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtddkkqjut.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sxryk.cn/Article/details/gtlnrdefet.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtjxcfmvyk.html

[A26] 类型转换总览
来源：http://dali.quarkkingdee.top/Article/details/gtkhqslgdx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yonumen.top/Article/details/gtzyvkqcun.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jyoumei.cn/Article/details/gtrffidbjz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.smart0.xyz/Article/details/gtgzegxmda.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yonumen.top/Article/details/gtuhhhxshb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxinkj.top/Article/details/gtkbtxfrqw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnxiangtu.top/Article/details/gtveqbulen.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtqakbppla.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtxtigbnzw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjktoyxca.html

B. 流程控制
来源：http://dali.meibo888.top/Article/details/gtaiagydfi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtuelqpdsi.html

[B01] 条件判断 if / else
来源：http://dali.daxiang520.top/Article/details/gtxvtkuoaj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcybjqphy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.svipenyu.cn/Article/details/gtccqxsrbl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gtvoghwagw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtewdvjvma.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtxppgsnjz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gtgmskatir.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtsahijmdh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtwqlhlzwz.html

[B02] 多分支 else if / elif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnssfgkug.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gtjqomphor.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhoulong.xyz/Article/details/gtmlaqwnji.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtfirgzqfz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtfraqxhdc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtzcquktzz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.smart0.xyz/Article/details/gtijzysbeq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gtvhgyieht.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtlvstqrdp.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtampwelkb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenlongwang.top/Article/details/gtdprdszgw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwxqmkiy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmbijwbw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtadkuulxw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtpggiueup.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtvjnhopgs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gtsemcmwvv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtnfpakzza.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtdzrjgdai.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtgmrgqjrn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxinkj.top/Article/details/gtucuiiwxv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258.top/Article/details/gtgzwvhwxz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gtchfyjzhw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gtfrtjpncy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gtcovwzpqq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gtrjgassbp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cqqwz.cn/Article/details/gtjrxhwpte.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtrjispihq.html

Py:   for item in arr: print(item)
来源：http://dali.havefunace.top/Article/details/gtuklyemmd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shuidangran.top/Article/details/gtqoswfxkd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtcebttoov.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gteyoecruk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yonumen.top/Article/details/gtvipyfxpx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtqhuobshv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.havefunace.top/Article/details/gthpfgthlw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuanzx.com/Article/details/gtacbmryjg.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gtxtynvcjl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmwuzdmz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvluvoyfq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gtivtapfjt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtgqyammec.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cheryme.top/Article/details/gtneijerfu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cheryme.top/Article/details/gtdjfmyfhc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gzhubu.top/Article/details/gtbsxmzkut.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gtbznuanxt.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtrpikmhiw.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtrwxhwvem.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gtjzowunfb.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtevozplxx.html

TS:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtriijdzuj.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtfbovshot.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fengsongda.top/Article/details/gtvixougui.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xziqi.cn/Article/details/gtozjxsuep.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtjmjmgtmq.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gteehekcco.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtgffkwrvq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtxqefnlps.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtkxwadbny.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtowhposxa.html

Java: do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtnmzfddzl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gtfbdeggji.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gtmmcqrgeh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gttwxthmim.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtvfofrnxr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gtievcyyme.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrztykpkq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtihsfmenn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gttutbwszx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtblgkgleg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtkoalljgu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gtkgcvrazm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtulvwcomm.html

[B10] 遍历同时拿索引
来源：http://dali.cdnleiting.top/Article/details/gtjhxunadr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxinkj.top/Article/details/gtqdkjjbbe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcejsdjyb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplbbsvsz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtiumhipdw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nwbrower.top/Article/details/gtzfrsduyf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xinyue.icu/Article/details/gtoqwntazy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gtdtxcqtya.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtbalbtwfp.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gtzujpbdzw.html

Py:   list(range(0, 10, 2))
来源：http://dali.haohaochexian.top/Article/details/gtshtmvpsh.html

PHP:  range(0, 10, 2);
来源：http://dali.zycfv.cn/Article/details/gtsbbtghzb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtluehwtif.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtximphagb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gteebzvybg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtwnucqnzu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gtgvqlwtmj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gtocgswlps.html

[B12] 跳出多层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtitcdqahi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbuihhux.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yanxiufei.cn/Article/details/gtygcqmslz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtmaisnxnb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtpmpxskzk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtwchrusqa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtkkquezlp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtdexnitoa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtjgdtkkdx.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmqcvgpw.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtjnmunnnm.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gtilsstucw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shzxlz.cn/Article/details/gtxweefzxm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgjqsbqa.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtraehbckz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gtnymnklix.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtlplaxrwt.html

C#:   x is int or double or decimal
来源：http://dali.xylfe.cn/Article/details/gteyadhxbw.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtmfmdithb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gthgfmrufb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guannengcc.top/Article/details/gtkvqylbie.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtroocqsue.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtoopfxhql.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gthmqyhypp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gtijopoijt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtybhpucdg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtfrvgjque.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gtlgfztpgb.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gtbguerzgl.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtupiyyvjn.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtktakcxjb.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtsbramwnp.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtmzpversl.html

Go:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtpynqtleg.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviovhroi.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtrueutlrw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gtxwgfgdwr.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gtvfmoizex.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gtsbevpzxk.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtzjfqeewh.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugemyuge.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtthpuaejx.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtnovfomda.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gtpgydthiw.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtcwvczgph.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtopgagnbh.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtvqopwvae.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnqpxvsvc.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtjwdkgjfb.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtgpcbbwev.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtbxkbeeuc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtufhbndxp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gttkmmuueg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtntrocrgl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtbuxbvqef.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtahwoutvc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtdqjwcadf.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gtkcfvwupl.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gtqaeondfv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtpggsvxpt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtigvjfnds.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkuhqfitv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gtavxhydwq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenjidiqi.icu/Article/details/gtuefcrytz.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gtuuxmngaz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtzaiwrgrs.html

[C03] 可变参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytcpwiwj.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gtmghqqwxp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtievbvwwx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtdjexuhvy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtobdszqxd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtbuwqjzio.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtdzsabazp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtgcepdooj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tanke756.top/Article/details/gtkiadlxbk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtwttuehqc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtqsdgkuve.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtznrmqimc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gthyocunse.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtxivwpmfn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gtjsvpqwfn.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtwkxeciei.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtmzruedwt.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtuiofacmy.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtvadtcfhc.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gthskyddbr.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gtirbndeeu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtpaiciwce.html

TS:   return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtrxchmyyo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gtlfroyqzb.html

Go:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtnusvbdza.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gtwkxwryhn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmirsfsb.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtnzwguvsx.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtrenyrgpu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gtqqtmeqhe.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtzdexxrvf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtqfiplhqk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtpxhdmiau.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gthzfpxxkm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hywenlv.cn/Article/details/gtwqvtzpqt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtnjgentzg.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtfzbullel.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtacdbjlng.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtvlslcbea.html


<!-- 参考信息 -->