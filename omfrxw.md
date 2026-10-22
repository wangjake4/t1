代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.zhixingplan.top/Article/details/gthaojdrsc.html

Py:   ord("A"); chr(65)
来源：http://dali.chenlongwang.top/Article/details/gtnsfshfim.html

PHP:  ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gtnjygnugt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shuidangran.top/Article/details/gtdyfozqfg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gotoacloud.top/Article/details/gteamzigya.html

Java: (int) 'A'; (char) 65
来源：http://dali.xuetiantiany.cn/Article/details/gtfkdvyedq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yangfankeji.com/Article/details/gtaxuwirbd.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangdashe.top/Article/details/gtwccumgri.html

C#:   (int)'A'; (char)65
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcaxufmh.html

[A19] 交换两个变量
来源：http://dali.zhongyouzk.top/Article/details/gtfdbmbtgb.html

Py:   a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gthknjgbat.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxuanxn.top/Article/details/gtmbfjtcnl.html

JS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtghhqgsfn.html

TS:   [a, b] = [b, a];
来源：http://dali.bjfxy.top/Article/details/gtndkreoqs.html

Java: int t = a; a = b; b = t;
来源：http://dali.meibo888.top/Article/details/gtzvvpkkci.html

Go:   a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtjphnxonx.html

Ruby: a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtcpdxudep.html

C#:   (a, b) = (b, a);
来源：http://dali.xylfe.cn/Article/details/gtcgnkuuzc.html

[A20] 读取标准输入
来源：http://dali.hfpthk.cn/Article/details/gthaerzjeo.html

Py:   name = input("请输入：")
来源：http://dali.316326.xyz/Article/details/gtpkvlnjff.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigufen.top/Article/details/gtntyyinjy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhengqikj.top/Article/details/gtbdkmjtia.html

TS:   // Node.js：readline 模块
来源：http://dali.hammf.cn/Article/details/gtthykiora.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xziqi.cn/Article/details/gtikajcmii.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yongpay.top/Article/details/gtplxopqsg.html

Ruby: gets.chomp
来源：http://dali.feifeiyinyue.top/Article/details/gtinqorkjo.html

C#:   Console.ReadLine();
来源：http://dali.hfpthk.cn/Article/details/gtbmrutkfa.html

[A21] 保留指定小数位输出
来源：http://dali.daxiang520.top/Article/details/gttbjwfosh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yuanzhike.top/Article/details/gtzyjyyucj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtygaqvvae.html

JS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtplbwaekn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtgrosoxtg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtntduniai.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtjtqxwgjn.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdhyppyd.html

C#:   3.14159.ToString("F2")
来源：http://dali.zycfv.cn/Article/details/gtixhkjibv.html

[A22] 获取字符串长度
来源：http://dali.cucudq.cn/Article/details/gtmbtmzrgw.html

Py:   len(s)
来源：http://dali.yueranfly.top/Article/details/gtvmjqypsp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jlsjyb.cn/Article/details/gtnpaqaykg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cucudq.cn/Article/details/gtrcsucthb.html

TS:   s.length
来源：http://dali.hnxiangtu.top/Article/details/gtcrwivsfa.html

Java: s.length()
来源：http://dali.jianghu66.top/Article/details/gtcsskdonb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ehwqpu.com/Article/details/gturccoihc.html

Ruby: s.length
来源：http://dali.meibo888.top/Article/details/gtczdyaozl.html

C#:   s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtvdlxrgha.html

[A23] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtidpojxri.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hnqzz.top/Article/details/gtcpgbztop.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtvhcbmryd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtxvzvciht.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gtugodohob.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gtfyalelit.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cashguo.top/Article/details/gtpvvrwvjw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtpdcdisid.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hfpthk.cn/Article/details/gtsoquyxyc.html

[A24] 去除首尾空白
来源：http://dali.vqdsnc.cn/Article/details/gtghdtzbkr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtselvoxqd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gtentztqtv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gtosrjrwhj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtomklkepu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jyoumei.cn/Article/details/gtgkhsfnxz.html

Go:   strings.TrimSpace(s)
来源：http://dali.haohaochexian.top/Article/details/gtrwsgqzof.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.316326.xyz/Article/details/gtxpafegye.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gtqubutgri.html

[A25] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtybvvluoj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tian-w.cn/Article/details/gtyxkpfmmn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.birdmap.top/Article/details/gtdxrnoxwg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj202588.top/Article/details/gttuisnfiu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.316326.xyz/Article/details/gtyqfzfdgs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbtlnsbb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtnbbkhyky.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ybcxt.top/Article/details/gtsvtrsdhv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtxhvepauo.html

[A26] 类型转换总览
来源：http://dali.chenlongwang.top/Article/details/gtupujbcpc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlhnrpqq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zdqjudy.top/Article/details/gtntymwswn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hfpthk.cn/Article/details/gtpdwljssh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhiwuduotai.top/Article/details/gtlpwtpkeh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtlcaxmiqt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinqigfzy.top/Article/details/gteerenxdr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jlsjyb.cn/Article/details/gtlfjcgoqt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyllpzsd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqxqtjwxu.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gtacwjwkbs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteatisuvg.html

[B01] 条件判断 if / else
来源：http://dali.redwolf501.top/Article/details/gtjbmryhuq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pycfn.com/Article/details/gtjhxgqfvp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tanke756.top/Article/details/gtswsirsdn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtetlclndd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtwrkccwtl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtcycdodsa.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shangyingyoupin.top/Article/details/gtboeqddfz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sweek.top/Article/details/gtmngwesro.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtyftisdvh.html

[B02] 多分支 else if / elif
来源：http://dali.shuidangran.top/Article/details/gtjrciuppa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhetzjtv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gtjdqfvnzc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtmgjtfiwv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gtlouimxix.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtkohozxvl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ppjwa.cn/Article/details/gtsxpttclz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gtjteniarb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtzuaaelyt.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gtaonvytxn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangshuangyany.cn/Article/details/gtnzayyiqi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtlwumognb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtbyohkyie.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtmegylbal.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gtxbcttjpe.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gtgpgpjrwv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hongshengwenyu.top/Article/details/gtyrihsksg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yvedp.cn/Article/details/gtyrdsxlvm.html

[B04] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtnnhtujvz.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtjmrcnyku.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.dashuyun.cn/Article/details/gtzmiyvhwk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gtuxesgyus.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtoskkdumg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dashuyun.cn/Article/details/gtwgafmczr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuanzx.com/Article/details/gtozgvuybi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cucudq.cn/Article/details/gtfjyuzwqp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yangfankeji.com/Article/details/gthlkmlsiq.html

[B05] 遍历数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtnjulmyau.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gthhurtadg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gtpdmebeuq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtsxgcvfhp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtdnqjsuwu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.birdmap.top/Article/details/gtcdninpvl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sysykeji.top/Article/details/gtffpruppr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtpxpjschc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtwbjebhgv.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gtcuddjbnj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.meibo888.top/Article/details/gtbprlbqbs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xinyue.icu/Article/details/gtqpkvodas.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtmvpfrcpc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtwwjqoqjn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtechgceif.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gtrgbrfzyn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gtcnsssavj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hammf.cn/Article/details/gthaplkelu.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gtapnlenph.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtzueqbtsu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtemhpuare.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtviqqsaeg.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtooykcppm.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtfbjylfaz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jyoumei.cn/Article/details/gtzogclipe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gtmroigwoy.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtafypqrpv.html

[B08] do-while（至少执行一次）
来源：http://dali.jianghu66.top/Article/details/gtrhsgihuf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtxtpmmhfl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gtmtklzlon.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtxhzarikg.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtheiqatuy.html

Java: do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtmbapyupw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.dianchejie.cn/Article/details/gtaijxvmjg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gtgyqvcqqv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtcctmgthe.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gtymsjpfoz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtttttyqsf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtsbsbsqmw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtgnejxqum.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtjxpzmzlt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtxnahobic.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtaovcmifi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gtygnydppt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtltavrnhi.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gtzganehts.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangdashe.top/Article/details/gtkevpwpqb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nwbrower.top/Article/details/gtapwadcsx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtburhyiiv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gteywwwmkg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gtkdmzritk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtizzggtnk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gtrhrxlhdo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sweek.top/Article/details/gtnkmwoqye.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gtblgyrauj.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtflgytjap.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtdavdqrsu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtnmphqmaj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gthyvyarhe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gtmkhhcqdc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gtqqtudazt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gtcmmkuipn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gtufurdmxf.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtrmojfqss.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtugqxtkpo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhongyouzk.top/Article/details/gtpucxxjkb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtjgzjcihx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtbyfrsicn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtaropevxl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtagngomti.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gtekdsjfkv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gtyycmxoub.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtfdouwfzz.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gttmpfuspv.html

PHP:  is_numeric($x)
来源：http://dali.zycfv.cn/Article/details/gtnvkazqjm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtxkwznbcn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtuqhmkrnc.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gtcriaskyk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gtkuybkvpv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guowangkeji.top/Article/details/gtgmlnzhey.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gtaminzyrj.html

[B14] 判断值是否在集合内
来源：http://dali.xziqi.cn/Article/details/gtlbagefrs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gtqrgkwqni.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gttaagzsfe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtewvkawhy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gthmrfcvnx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtqbgratpp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gtittjxchf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelmfsgjx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtkexjoeda.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtdxqyyzur.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gthtpsugpf.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gttdqsuenx.html

JS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtubrknngc.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvartdrde.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtpjmhkzcd.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtxwyutjhs.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtvoahhdoq.html

C#:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgvdczij.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooblnxfm.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtnjfhvdac.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtbhxretpa.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtxduknuvs.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtoggonqvj.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gtnwucxilt.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtyjhlskid.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtvgiinpxd.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gtibsglyny.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpbdkocxv.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gtxuvfhocf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttzdqxcgj.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtzvctople.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtydrttbrz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtecztakzs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtgttcnxwh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtyoihjblw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgywsfbmt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sxryk.cn/Article/details/gtumfwvefo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.havefunace.top/Article/details/gtdttjolat.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtejqrolke.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavpnivex.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtioeapumu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gtaxhibxmx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtxfepwbdv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtcpdrkthq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtsugeppki.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtflcunxpd.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gtnzjaggej.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnqzz.top/Article/details/gtmuomlycr.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gtumfbewlp.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtlgeiaqqd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gttymlwcjd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtxgimrbri.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzylbmugo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gttlzlgqfl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtrtsfpift.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gtlxievilp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtdojbyzqa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhengqikj.top/Article/details/gtmmrdlkar.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gthbjnzfye.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtgtmuqohq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrpquduhj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gtgpoqnraw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gtvjejqfcq.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtssqrlrso.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtbbigvrao.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtprhtxssy.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnmkbait.html

Py:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtssqimvie.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtszwwnona.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtbdeujjpj.html

TS:   return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtpngopcra.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gaohongyu789.top/Article/details/gtpjwdmfvy.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gteqcniupq.html

Ruby: return a, b
来源：http://dali.sufxvd.cn/Article/details/gtoifrwygb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtxgejcqqd.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtpqkpgqus.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpswkkkh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gtategheqc.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtmqtafqtr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.redwolf501.top/Article/details/gtjlzvtoct.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtwbcsikmq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nwbrower.top/Article/details/gttydrmoyy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gtfipdgchs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gthxyhtjwu.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtzzbrmzzb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvbpvggn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtzfxvqxbr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gtluzbzgpo.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtkuiiwmgs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtacbsowle.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gtsurkzivl.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gtlqyrdlir.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daxiang520.top/Article/details/gtdonxmzyk.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtodvsutry.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gtnkitkjrp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ydzc1.top/Article/details/gtzkkzytzc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpigfmuh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtqacetego.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gthilxaydt.html


<!-- 参考信息 -->