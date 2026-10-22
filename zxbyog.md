代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtxtqezanx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtjwarqkkp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtxbjyrhlq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtvnkwowie.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jyoumei.cn/Article/details/gtmbkwjgdw.html

Py:   ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtgvjzkeyo.html

PHP:  ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gtqfabzhkb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangdashe.top/Article/details/gtupqvvhtw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.mhx1999.top/Article/details/gtaxtncoql.html

Java: (int) 'A'; (char) 65
来源：http://dali.cashguo.top/Article/details/gtvkpfvkvg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.haohaochexian.top/Article/details/gtqgsieqde.html

Ruby: "A".ord; 65.chr
来源：http://dali.ehwqpu.com/Article/details/gtzbqgkqsa.html

C#:   (int)'A'; (char)65
来源：http://dali.smart0.xyz/Article/details/gtqffjwhpw.html

[A19] 交换两个变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazrggakx.html

Py:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gtmoyaekfh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ehwqpu.com/Article/details/gttyyfnzpx.html

JS:   [a, b] = [b, a];
来源：http://dali.yuxming.cn/Article/details/gtsqpvidee.html

TS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtuvvwgzrm.html

Java: int t = a; a = b; b = t;
来源：http://dali.kuanghao11.cn/Article/details/gtxeipqdik.html

Go:   a, b = b, a
来源：http://dali.dianchejie.cn/Article/details/gtkrqpdyqp.html

Ruby: a, b = b, a
来源：http://dali.mhx1999.top/Article/details/gtfgkslmej.html

C#:   (a, b) = (b, a);
来源：http://dali.jiagoushi.top/Article/details/gtueyrswim.html

[A20] 读取标准输入
来源：http://dali.gotoacloud.top/Article/details/gtdknqwizy.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gtyvelqoee.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj202588.top/Article/details/gtsurledph.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.316326.xyz/Article/details/gthsiwevqy.html

TS:   // Node.js：readline 模块
来源：http://dali.gzhubu.top/Article/details/gtxffrhkbe.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hongshengwenyu.top/Article/details/gtstokrydk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258.top/Article/details/gthcvfiitm.html

Ruby: gets.chomp
来源：http://dali.guannengcc.top/Article/details/gtkesbuwvg.html

C#:   Console.ReadLine();
来源：http://dali.kuanghao11.cn/Article/details/gtltfquqjm.html

[A21] 保留指定小数位输出
来源：http://dali.jyoumei.cn/Article/details/gtlcegteun.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxuanxn.top/Article/details/gtbtxwqfpw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtkecmlukb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtduudjctk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtjivxwxkm.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtwgljllju.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtfxlpfara.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqhwdfsc.html

C#:   3.14159.ToString("F2")
来源：http://dali.fengsongda.top/Article/details/gttxauprvr.html

[A22] 获取字符串长度
来源：http://dali.yj202588.top/Article/details/gtfdxmhvhi.html

Py:   len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwynmglyz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cdnleiting.top/Article/details/gtzbexbkxj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shangyingyoupin.top/Article/details/gtwviydifq.html

TS:   s.length
来源：http://dali.nwbrower.top/Article/details/gtwimqoaus.html

Java: s.length()
来源：http://dali.gzhubu.top/Article/details/gtpnqlnxjo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxjglibfe.html

Ruby: s.length
来源：http://dali.mhx1999.top/Article/details/gtofsrmxww.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gtqybogadg.html

[A23] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtlvlavfjy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sysykeji.top/Article/details/gtvtsozqud.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zdqjudy.top/Article/details/gtbszsgzic.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtwdpxgmir.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gtxezyzwgy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gteoiyhiip.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gogol.net.cn/Article/details/gtxgmrvodu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gtjzcytpwd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.redwolf501.top/Article/details/gtioxeqypd.html

[A24] 去除首尾空白
来源：http://dali.zdqjudy.top/Article/details/gtssshgplw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gtcuzgviug.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.daxiang520.top/Article/details/gtkakbypuq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gtouietpzn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ehwqpu.com/Article/details/gtdrdjlmgw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hywenlv.cn/Article/details/gtmzkspeen.html

Go:   strings.TrimSpace(s)
来源：http://dali.kuanghao11.cn/Article/details/gtwtgawqwb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hywenlv.cn/Article/details/gtyztklhgg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtjniohquu.html

[A25] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtpbdqhinw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xziqi.cn/Article/details/gttstqyloa.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuaayudm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gtbbbpjuxi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gtgthagktg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenlongwang.top/Article/details/gtpzpntlzl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gttjzepuoj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgfzy.top/Article/details/gtynbpatwd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtzidxvisg.html

[A26] 类型转换总览
来源：http://dali.cqqwz.cn/Article/details/gtxopzrkfq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtqvvvfeum.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cdnleiting.top/Article/details/gtdhfqlkdf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ppjwa.cn/Article/details/gtoidguzow.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258.top/Article/details/gtspgamrmw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shzxlz.cn/Article/details/gtwksevhat.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gtteepxyev.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jyoumei.cn/Article/details/gtnrqporqk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtvelbkyja.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtyzyzbrlc.html

B. 流程控制
来源：http://dali.hywenlv.cn/Article/details/gtqqmvqzrz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvtophutd.html

[B01] 条件判断 if / else
来源：http://dali.yongpay.top/Article/details/gtpgyunboy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hysaishi.cn/Article/details/gturyamvtz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuhzmwkb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gteqmccsqd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtvpmuqzdn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtgzsxoaap.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sysykeji.top/Article/details/gtmmsegfej.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258888.top/Article/details/gtdzaablxf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhengqikj.top/Article/details/gtbnfpzrim.html

[B02] 多分支 else if / elif
来源：http://dali.havefunace.top/Article/details/gtshhzvgnc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cdnleiting.top/Article/details/gtkpvudqkg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zycfv.cn/Article/details/gtxdsykwxu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtyiteqrub.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtrsvdtasx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtmaqsbonq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tianlin.xyz/Article/details/gtjdrovmbx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.0kj1m.cn/Article/details/gtxpdigfev.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtrmiyafng.html

[B03] switch / match / case
来源：http://dali.yongpay.top/Article/details/gtscdnsexn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tian-w.cn/Article/details/gtqpetrukp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtjbhkbcmx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtmdfopzjf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtfwfzjfjb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtdapmsphf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gtehxlcjka.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jyoumei.cn/Article/details/gtuhaeatow.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtcbkgcumx.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtyxyzgurk.html

Py:   for i in range(10): print(i)
来源：http://dali.jyoumei.cn/Article/details/gtlaxrvcgm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxuanxn.top/Article/details/gtleyyfwnu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guowangkeji.top/Article/details/gtfxkxfaxo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtiidsyvgz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yueranfly.top/Article/details/gtykdcbams.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gtenlbvixd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtudsvvloa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gogol.net.cn/Article/details/gtkaonrbnv.html

[B05] 遍历数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtdxwkdyqb.html

Py:   for item in arr: print(item)
来源：http://dali.ivvv.top/Article/details/gtlahxcrpy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtmherhkbp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtbioikbda.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbfugzph.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttnjusdx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gtiajegewm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shzxlz.cn/Article/details/gtogiyzwkh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtkdshumxo.html

[B06] 遍历字典 / 对象
来源：http://dali.hfpthk.cn/Article/details/gtxhxedanm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dianchejie.cn/Article/details/gtrohfyjbs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gtfmoulthh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gtlkihnyhd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtwfecicbk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tianlin.xyz/Article/details/gtmuzfligd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrncogpfz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gttkhnqmmc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gtrqshvhiq.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gtcsdmvmhg.html

Py:   while i < 10: i += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtaupoemnz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gtibkwhdwp.html

JS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtclnbqghj.html

TS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtuzjekryl.html

Java: while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtsfbmmfdl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gtwtibdiic.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gtjggixfwf.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtyeaibhlv.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigfzy.top/Article/details/gtdvajzayj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gtmymvvcom.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtqruzuutz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtptdhmynj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtkyczxgph.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtnigeexak.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtukyjrbsm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.snrcjt.cn/Article/details/gthuwmnonh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtdjasnpfr.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gttohyigfq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gtxkpzjwia.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtarezyubm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtykujuzrg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtckjeaicg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtuczwvopc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtxijovcxc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtvkpwznox.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtvwcrubqx.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gtpcvtwjix.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gzhubu.top/Article/details/gtyfiljflu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtzcfoxudv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtoasxnlzm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtjfnlptjg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxasucxid.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtuwxwgdlt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gtzbpyxwzi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtggvidwfc.html

[B11] 生成数字序列 / 区间
来源：http://dali.guowangkeji.top/Article/details/gthgpangju.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gtvrjkjcqe.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gtsskppbaj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtmeimkwjh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtezvlpmyt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtrjsieetp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gtjmyaelsv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.9152youxi.cn/Article/details/gtpkebwrcz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gthetaergq.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gtdguxvxey.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jianghu66.top/Article/details/gtwuyehgfz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gtgrnxweai.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtioxcqiwo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtprkcmhho.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtjznixdbk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhixingplan.top/Article/details/gtabuwowkn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gtgplxgsep.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gthcuafius.html

[B13] 判断是否为数字
来源：http://dali.9152youxi.cn/Article/details/gtbrblqyqw.html

Py:   isinstance(x, (int, float))
来源：http://dali.shuidangran.top/Article/details/gtrhkvsjlf.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gtxeytmfdo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtcvatvuuk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtbiktaixg.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtudgiwfkp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gtpmsrqucf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gtzokfdiop.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gtqsnxtcjd.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtlxtuxscp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtwklqczjl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenzaomai.com/Article/details/gtyjgnsnkb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtgsfhrleb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gthtmfunje.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gtazwaxkjq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gtpfusvikt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtxiimhywb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtnyhwyiyg.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtvzcxjedv.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtyfcbkmzd.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gtldphoosi.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtidkrwqjo.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtqnpjkhpo.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gtfresfkvv.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtyleziaib.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtlwdgmgpy.html

C#:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtqekonkwd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtpuxsnmpp.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gtjajuzkec.html

PHP:  if (!$data) { return; }
来源：http://dali.bjfxy.top/Article/details/gtmuqbuiyc.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsfrjzhh.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbtxvgck.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtghkgnlrz.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gtkvnptpje.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtvjquxkpo.html

C#:   if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtnrmcfito.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqgzyjemi.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtyugxsiwv.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckxqzovn.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtebowatxz.html

Py:   def add(a, b): return a + b
来源：http://dali.guannengcc.top/Article/details/gtvzkcknje.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtoxkllohh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtebyhyeuy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtakbmssbc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtxokysnjm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtizmlfxew.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gtdahgxpsf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtmolifsam.html

[C02] 默认参数
来源：http://dali.ydzc1.top/Article/details/gtuutywoqi.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtizuiglby.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtnezpomgm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtasslkdrr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtotrzqzwy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yvedp.cn/Article/details/gtjdnzfaxa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtyrzdsubu.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gtqgfeuaei.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gtcabfuqrg.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gtbemphrxg.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmitferf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gtqxvgqymk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtiknkhrpu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtvqaodlnr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtoydtoqfb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gthuuxyuob.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gtutjgjyts.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gtndvbkpan.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gtfvowhvuu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gtzcmggunf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtqdsxbqiu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtvnjnkrdb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtmhakjdua.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gtaqxcyylm.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gthdrlywkd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtyjreanbv.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtbdczctui.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtgapjbxkr.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtcdqxgcmj.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtnfpjnngf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gttsdlxsok.html

TS:   return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtizlptzms.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtwnbvxirk.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gthzczbuey.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gtspvlfjlp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtjcvotubv.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gthjhtxgie.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtwihoumtc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gtpwfzxise.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtyuvstdyj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gtvbeferfi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteolnflna.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gttakgwiln.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gtdxshibnz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtaetcadxd.html

[C07] 把函数作为参数传入
来源：http://dali.jinqigfzy.top/Article/details/gteebqjaud.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtnkwxezox.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtmkhdkvhs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtiqabcgll.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtanqnfcqq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gtbpjqxaym.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dianchejie.cn/Article/details/gtacsxrcpu.html

Ruby: arr.map(&:upcase)
来源：http://dali.hnxiangtu.top/Article/details/gtdeipmpdi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gtniomwbme.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtbcjsxtvh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtunjugtob.html


<!-- 参考信息 -->