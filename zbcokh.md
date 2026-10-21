代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jiagoushi.top/Article/details/gtuoytpoub.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.feifeiyinyue.top/Article/details/gttnofbwed.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpavebyv.html

[A17] 位运算
来源：http://dali.xuanzx.com/Article/details/gtbojetesy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtxbxqaqll.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xinyue.icu/Article/details/gttycqsmkn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtxbeolsgz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtkijxexiu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtpbgiwhnm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwseqvvak.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtczokhnsd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtgavzruiw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hammf.cn/Article/details/gtnsmbjjwx.html

Py:   ord("A"); chr(65)
来源：http://dali.cdnleiting.top/Article/details/gtwrbpcqkw.html

PHP:  ord("A"); chr(65)
来源：http://dali.gotoacloud.top/Article/details/gtujkfzlyr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtklohsufl.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgfzy.top/Article/details/gtqlxbacuw.html

Java: (int) 'A'; (char) 65
来源：http://dali.daria6918.cn/Article/details/gtodheycyg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gtflbkrvwc.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangshuangyany.cn/Article/details/gtdyttwbkw.html

C#:   (int)'A'; (char)65
来源：http://dali.wangdashe.top/Article/details/gtruyvlpdr.html

[A19] 交换两个变量
来源：http://dali.zhixingplan.top/Article/details/gtiheycsgp.html

Py:   a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtuauysneu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnxiangtu.top/Article/details/gtzfvbntqu.html

JS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gtlbyejwbk.html

TS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gtexzceccl.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxuanxn.top/Article/details/gteobtkwpd.html

Go:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gtldfxdfcu.html

Ruby: a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtraqxjndi.html

C#:   (a, b) = (b, a);
来源：http://dali.gotoacloud.top/Article/details/gtzwkmhtbz.html

[A20] 读取标准输入
来源：http://dali.yj202588.top/Article/details/gttovkwvxi.html

Py:   name = input("请输入：")
来源：http://dali.feifeiyinyue.top/Article/details/gtijlxpoqh.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangdashe.top/Article/details/gtjizjiijw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gtocclysal.html

TS:   // Node.js：readline 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtcwgflqel.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pengpengdd.cyou/Article/details/gtvkobgepg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ybcxt.top/Article/details/gtdzynkbyp.html

Ruby: gets.chomp
来源：http://dali.cucudq.cn/Article/details/gtcnkgnqdt.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gtmaixascu.html

[A21] 保留指定小数位输出
来源：http://dali.daxiang520.top/Article/details/gtodbywpsa.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xinyue.icu/Article/details/gtggtlgvdq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtbvgtiijw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtkgueihrc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzufixjwq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtliljqmwg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtjroqwaha.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtaodltnot.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgfzy.top/Article/details/gtndthvbet.html

[A22] 获取字符串长度
来源：http://dali.yvedp.cn/Article/details/gtrervhyan.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtgpzpajff.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.feifeiyinyue.top/Article/details/gtzdqedfmw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gtfrozjsgj.html

TS:   s.length
来源：http://dali.yj202588.top/Article/details/gtuxxsisij.html

Java: s.length()
来源：http://dali.xziqi.cn/Article/details/gtxmosbcnl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxlpmloqx.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtaakqsglm.html

C#:   s.Length
来源：http://dali.dashuyun.cn/Article/details/gtirvqoufw.html

[A23] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtyaibyyct.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sysykeji.top/Article/details/gtixenfjqm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.316326.xyz/Article/details/gthtupvijo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtmtjwqpez.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gthvmplcel.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gtppzpanyu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrnhtkcgl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtmwiqfjvm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sxryk.cn/Article/details/gtnhgzrztv.html

[A24] 去除首尾空白
来源：http://dali.yueranfly.top/Article/details/gtdlvgcrmc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tianlin.xyz/Article/details/gttuupjjic.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gtrqgvbvvw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dianchejie.cn/Article/details/gtpfcknhoh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtfjzgghfl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pycfn.com/Article/details/gtaostkfze.html

Go:   strings.TrimSpace(s)
来源：http://dali.tian-w.cn/Article/details/gtcyihkypm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuanzhike.top/Article/details/gtaefieqjn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gteyhiiqtb.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtxiybfyth.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gtlkwsprvk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gtzonkrrvo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtsqecoogd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gtdugnezbd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxuanxn.top/Article/details/gtcazhpepj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjadnmqc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gtfzqfpipt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtcmdflfvz.html

[A26] 类型转换总览
来源：http://dali.yueranfly.top/Article/details/gtkorrrewk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yuanzhike.top/Article/details/gthxirdqcj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.aibaodan.cn/Article/details/gtvysnzknk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yanxiufei.cn/Article/details/gtzhlkkgyr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fzhhl.top/Article/details/gtlgmiikjq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gtiguptixu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gtkippufhv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jyoumei.cn/Article/details/gtyxpmylev.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjxuinbu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwmgtiuh.html

B. 流程控制
来源：http://dali.pycfn.com/Article/details/gtrhibpewz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtdyffldfi.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gtyeimbdky.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtonnxkvpx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtizejralf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtdtxkdlrx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtigholrzj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gterhcajme.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnqzz.top/Article/details/gtpygpiemw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gtlrocllcm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtuclsevol.html

[B02] 多分支 else if / elif
来源：http://dali.jiagoushi.top/Article/details/gtxdlgzwat.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gtbgxjfxvu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.dashuyun.cn/Article/details/gtgwjmcvvp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtvkfkmlhr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtmxtmajvw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtzpfeyccl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fzhhl.top/Article/details/gtjobcfzxs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gtriwgvrix.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtdaridcsm.html

[B03] switch / match / case
来源：http://dali.cashguo.top/Article/details/gtopctqhse.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shuidangran.top/Article/details/gtmkjdusxq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtqnmglfwh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtkpwbasqn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtsamyoael.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtmzlgkdhp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtjyiyrnkt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.svipenyu.cn/Article/details/gtotauxoug.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gtlnbrwkse.html

[B04] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtqjpbrjmy.html

Py:   for i in range(10): print(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtfwbsxzpg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhixingplan.top/Article/details/gtfrowchag.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtcjzwuzno.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gtnrpjfxub.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.haohaochexian.top/Article/details/gtlmizurls.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sysykeji.top/Article/details/gtymlyxcvn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gtyyqwygix.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtchjldtok.html

[B05] 遍历数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtyttitzoe.html

Py:   for item in arr: print(item)
来源：http://dali.jyoumei.cn/Article/details/gtseerrjkz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ivvv.top/Article/details/gtiqbpascb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtaxuqlqzc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gtceeadqoq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.bjfxy.top/Article/details/gtqkwisfcc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gtiiujkyjf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daria6918.cn/Article/details/gtfnmtfpxa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gtbeszyomq.html

[B06] 遍历字典 / 对象
来源：http://dali.smart0.xyz/Article/details/gtzezsdzxv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gtkcwrvhuh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.redwolf501.top/Article/details/gtbvxixdxd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxisupikh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtzqcikpir.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gtrwqxcfii.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hysaishi.cn/Article/details/gtculkavoj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jiagoushi.top/Article/details/gtynycshye.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gtqyuyygqr.html

[B07] while 循环
来源：http://dali.c1oappe.top/Article/details/gtqgiuayzm.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gtzaqwwzfx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtvevkawcf.html

JS:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gtkwlvhftm.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtbubshska.html

Java: while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtgvwcyeis.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yanxiufei.cn/Article/details/gtjvkaycqs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gtcyqmcofi.html

C#:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtbdtujwlp.html

[B08] do-while（至少执行一次）
来源：http://dali.yongpay.top/Article/details/gtjnmxyaiv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pengpengdd.cyou/Article/details/gtenpgmchh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtzdrgukzi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gthwisiaah.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtivevepzp.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtfmgedlvw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtaxxyjaqg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gtmllymroy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtzlrfqkcs.html

[B09] break 与 continue
来源：http://dali.aibaodan.cn/Article/details/gtmrrsthgm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtdcdvgbfs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gthlpfrmpt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtzfmzdwzj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gthzmhelex.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtnblwcqgt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gtmtkctswy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtqvonisxj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtwsxvzjop.html

[B10] 遍历同时拿索引
来源：http://dali.sxryk.cn/Article/details/gtcevoqbzq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnqzz.top/Article/details/gtjqqyaleh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnwcoxvr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtwvauwyzn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtccangkcx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cashguo.top/Article/details/gtaitmeevh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gtsuceadsa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gtpaevbxaz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhixingplan.top/Article/details/gtrceodrgi.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gtlbegmxun.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gtkzusfucf.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlrtpwqk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtxevxjcro.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtzjjjvmxu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gtmfwfqdln.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtigutpjnu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dashuyun.cn/Article/details/gtgdbgtwim.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjmyobgj.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gtbipebbgg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejxectpd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.quarkkingdee.top/Article/details/gtkfgonsbo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtmirgqjjj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtjckgtgeu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtlhyrnpps.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj202588.top/Article/details/gtakyuwvqi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gtbytdbwev.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gtfuztllre.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtyyhbtapb.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gtplvabyfe.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gtrereliup.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtovnpxmcx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtitkhpygp.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gteznnscxe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtekmtytat.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cucudq.cn/Article/details/gttmciuawx.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gtdlcuodzl.html

[B14] 判断值是否在集合内
来源：http://dali.fzhhl.top/Article/details/gtvcdsblvc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtzqpskzyx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gtauroccwm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvjojfew.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtkeubjdvo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gtwgbagsyo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobnrjkcw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtzddixsyd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtgbqwzqjf.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gtqbhjapbb.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gtrayywyhe.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gtroxfodfj.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtymuymmud.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtdabodvdt.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtjhlhuntl.html

Go:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtgermfzcg.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtjtwdjzah.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtspcoinam.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtwkmtrqrh.html

Py:   if not data: return
来源：http://dali.vqdsnc.cn/Article/details/gtspioxfeb.html

PHP:  if (!$data) { return; }
来源：http://dali.sxryk.cn/Article/details/gtqlshscvy.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtucyfsynd.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtjhcnkkzt.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtcicgfoae.html

Go:   if data == nil { return }
来源：http://dali.hfpthk.cn/Article/details/gtbfjjnoov.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtchpvfnyc.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtrmrkhyra.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtuhcaoadi.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtcvghccvi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtphtohxwh.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gthudccfov.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuacufkmw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtfoaxqczj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkggobcci.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtyjzhhdsn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtuhxewryz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gtegmwlxii.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sweek.top/Article/details/gtczzmztsa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtnlchiwar.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gtlnoemzwx.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gtzzcvxkva.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj202588.top/Article/details/gtciaqoqgk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtieynkgdb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtkqqfrobc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtxpdwkpgd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.0kj1m.cn/Article/details/gtwwxenzjo.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhfpwkpg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gtnzhppzpd.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtflwvbnut.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtpugsyasx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtaikjfjbb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtecuqqlgu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtfpmyrjkx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtyyortuey.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtoltqzmlw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtixjyayrb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtnoasedlv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gtzdygeskc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gtpgkminwp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtldcesicc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtojummxok.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gtpjtscrjn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gaohongyu789.top/Article/details/gtiesipngq.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gtzzsznolu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtxmazsstd.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtvmycydat.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gtvdtkwfod.html

Py:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtzevrsuai.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gthltvsbpb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtpbbpjfic.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gtdzdtzuad.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtbfrfmali.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtktaqakfy.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtbhfrfwvd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtugrttrvs.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gtoqwbqnmc.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtqdgsokhd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtcxytmknl.html

JS:   const square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gtijvnfvny.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gtamwilwyb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllhkjkoj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gtusblsecs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtswsswzlr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtymdnfiyt.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtriqegkas.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gtabbddhuh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtjhzzupir.html


<!-- 参考信息 -->