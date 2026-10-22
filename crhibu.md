代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumwhkipp.html

C#:   var value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtlkpbydpt.html

[A16] 真假值判断规则
来源：http://dali.gaohongyu789.top/Article/details/gtamutptsm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.redwolf501.top/Article/details/gtlnsgpbys.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnqzz.top/Article/details/gtanlxuufb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xuanzx.com/Article/details/gtwgayuikm.html

TS:   if (!x) {}
来源：http://dali.ivvv.top/Article/details/gtxbkvoehz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ydzc1.top/Article/details/gtbijatwxk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhengqikj.top/Article/details/gtqmqtsjbr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj202588.top/Article/details/gtcbxqltcd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gtwavgoxya.html

[A17] 位运算
来源：http://dali.cdnleiting.top/Article/details/gtzvwilnpl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtxjxntsrw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtqvpeogjg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtwwedchmb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtnhummhwu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbujnhmo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxyyglzc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtzsobhsuc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtuehmivax.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dashuyun.cn/Article/details/gtoxcnevju.html

Py:   ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gttddodjhf.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjernyckz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gtpchiywkj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dianchejie.cn/Article/details/gtfeffvtfa.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258.top/Article/details/gtdigfzewb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.9152youxi.cn/Article/details/gtznfifmvx.html

Ruby: "A".ord; 65.chr
来源：http://dali.cqqwz.cn/Article/details/gtgungqdjz.html

C#:   (int)'A'; (char)65
来源：http://dali.hongshengwenyu.top/Article/details/gtectlcmdf.html

[A19] 交换两个变量
来源：http://dali.sxryk.cn/Article/details/gtpwblslqs.html

Py:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtlmqxuqlu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ppjwa.cn/Article/details/gtmskelreb.html

JS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctbmrbwg.html

TS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gtmohrspwu.html

Java: int t = a; a = b; b = t;
来源：http://dali.cashguo.top/Article/details/gtcerznvlu.html

Go:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtoabyzhtx.html

Ruby: a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gtzmdspvoc.html

C#:   (a, b) = (b, a);
来源：http://dali.mhx1999.top/Article/details/gtnygsiaju.html

[A20] 读取标准输入
来源：http://dali.yuxming.cn/Article/details/gtgthzrvwo.html

Py:   name = input("请输入：")
来源：http://dali.andypj.xyz/Article/details/gtejuobirq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gzhubu.top/Article/details/gtqoidihog.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nwbrower.top/Article/details/gtzjlcgyki.html

TS:   // Node.js：readline 模块
来源：http://dali.dianchejie.cn/Article/details/gtivxvdwdx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zdqjudy.top/Article/details/gtnzgasyji.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.vqdsnc.cn/Article/details/gtjopkqhtw.html

Ruby: gets.chomp
来源：http://dali.tanke756.top/Article/details/gtrbhvrgaa.html

C#:   Console.ReadLine();
来源：http://dali.xuanzx.com/Article/details/gtddmxfkld.html

[A21] 保留指定小数位输出
来源：http://dali.hfpthk.cn/Article/details/gtbilnkmex.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygldfljf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtlbbucdpr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtehflhbya.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gtdwifpaoy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtfbbiljxx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtobttjthj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtssygebhw.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258888.top/Article/details/gtrihbtauv.html

[A22] 获取字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtjyjkhyfr.html

Py:   len(s)
来源：http://dali.gogol.net.cn/Article/details/gtetugeahp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.haohaochexian.top/Article/details/gtroaefruu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenlongwang.top/Article/details/gtacfsxzet.html

TS:   s.length
来源：http://dali.zycfv.cn/Article/details/gtlinixsoq.html

Java: s.length()
来源：http://dali.zhengqikj.top/Article/details/gtwfpumcuk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jiagoushi.top/Article/details/gtlyvtgorn.html

Ruby: s.length
来源：http://dali.0kj1m.cn/Article/details/gtrmuhzldz.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gtmziizays.html

[A23] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gttozpvdmi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtocgxrxci.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gtosnkhvsv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gtdxnweoxe.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hammf.cn/Article/details/gtzcjzdynr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gtdqtelyjl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnetcnbj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtgbmxdrnt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gthbzgfdgk.html

[A24] 去除首尾空白
来源：http://dali.hammf.cn/Article/details/gtkrqxytub.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxtxmwki.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hnxiangtu.top/Article/details/gttuegbnek.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtweqizljo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtqquvkkvv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangtech.top/Article/details/gthvzhgafp.html

Go:   strings.TrimSpace(s)
来源：http://dali.hnxiangtu.top/Article/details/gtugnclaav.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinqigfzy.top/Article/details/gtnsfwdplg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shzxlz.cn/Article/details/gtbiryidpk.html

[A25] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtgpkdaxri.html

Py:   s1 == s2; s1 != s2
来源：http://dali.c1oappe.top/Article/details/gtvulswlyl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258.top/Article/details/gtdtrxptyz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gtgcxrvjzz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaquhxohh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tian-w.cn/Article/details/gtzghtcxev.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtozowclss.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.bjfxy.top/Article/details/gtpopopiop.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtsnwywggk.html

[A26] 类型转换总览
来源：http://dali.316326.xyz/Article/details/gtuoxumogf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.snrcjt.cn/Article/details/gtmkbwlvuz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dianchejie.cn/Article/details/gtkfwvcynm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnxiangtu.top/Article/details/gtwsieyxum.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gthcwnyjna.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtcrkfpppj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhiwuduotai.top/Article/details/gtdxxcitnn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gtwqnzcyav.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.chenlongwang.top/Article/details/gtyvawsixc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdaqcbduz.html

B. 流程控制
来源：http://dali.aizwys.cn/Article/details/gtiiyekrcg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmltiwctp.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gtrhterogo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.mhx1999.top/Article/details/gtcpricuyh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenlongwang.top/Article/details/gtcqgpsyek.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtlbwaivyb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtwswsabhn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtntjdildo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gtidkgkgcg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhongyouzk.top/Article/details/gtgnxzznys.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiajowgl.html

[B02] 多分支 else if / elif
来源：http://dali.xuanzx.com/Article/details/gtihdqmhuh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.aizwys.cn/Article/details/gttxznljee.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gtmbmntifr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtwztdjohz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtwbxnhlsw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtzqprqoja.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ehwqpu.com/Article/details/gtlfffueeh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryqpjinx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtryovwwfr.html

[B03] switch / match / case
来源：http://dali.mhx1999.top/Article/details/gtevkkdyje.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuetiantiany.cn/Article/details/gtwuobzxek.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtmpcsaxxt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtrksahamx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtgbgjpayc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gthlwhxuks.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shuidangran.top/Article/details/gtclwnmthb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangshuangyany.cn/Article/details/gttfeeghco.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cheryme.top/Article/details/gtixbujqmm.html

[B04] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtqtyegiza.html

Py:   for i in range(10): print(i)
来源：http://dali.hywenlv.cn/Article/details/gtexxpxzah.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sufxvd.cn/Article/details/gtiybmkejv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcapnmkub.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gtjpqfvtyh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfxriykv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gtlzwhpoox.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gotoacloud.top/Article/details/gtlgwklnbm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtimnmscpb.html

[B05] 遍历数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gtvxdecyyu.html

Py:   for item in arr: print(item)
来源：http://dali.daria6918.cn/Article/details/gtarbxwabd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlqopydk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtznfduvvg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gtbwlbmwtj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gtfycfviur.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpajacbwm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sxryk.cn/Article/details/gthsedtrpn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtzykuwhnk.html

[B06] 遍历字典 / 对象
来源：http://dali.chenzaomai.com/Article/details/gttucjbcnx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfnxorvv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gtiayzihcn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtcdjvwmna.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gtgdzuwejy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xylfe.cn/Article/details/gtgrehsvwb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvxrvpny.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gtcffmnpjj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ppjwa.cn/Article/details/gtvmokiypv.html

[B07] while 循环
来源：http://dali.iojbl.cn/Article/details/gtsxjxwxsi.html

Py:   while i < 10: i += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbceggaf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhixingplan.top/Article/details/gtgderkthj.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtnkehelxy.html

TS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtzmrrawoi.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtqrwtvklr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtdfwzkwtn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gtzgwhcmvm.html

C#:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtsnjnnksk.html

[B08] do-while（至少执行一次）
来源：http://dali.xziqi.cn/Article/details/gtjxacvtam.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guannengcc.top/Article/details/gtfdqbrynm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gtbtnwjtyc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtqcsfsuey.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtuimirmih.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtqdkfkbnq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.smart0.xyz/Article/details/gtpkwcnicp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuanzx.com/Article/details/gtxwzynser.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtkovypzlo.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gtaqktpfrq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gtgbdrcyob.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtiaaxmrqg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtldzhivsi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtfockbasv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtnrgcrjmf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.kuanghao11.cn/Article/details/gteizshvlr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dashuyun.cn/Article/details/gteurlvuyy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtxevzxhwx.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtmowzkrmv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nwbrower.top/Article/details/gtwohiapjc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.c1oappe.top/Article/details/gtllagqlpv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtfxooawmk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gtiotlxupb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gtkcpxgzun.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nwbrower.top/Article/details/gtjldldctm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sufxvd.cn/Article/details/gtgkdnwmyc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hywenlv.cn/Article/details/gthvitnyit.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhongyouzk.top/Article/details/gtdxhduayt.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtsbwqhzje.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtuxdsdgzu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gtobhqmxnq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtqdlngfbz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtzrfcpeoo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gaohongyu789.top/Article/details/gtxmrwdkyy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gtbfympbcz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gtzfueqfyx.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gtchynknfa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkhsvlyy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gtwnbegmmj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtbpimckns.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumasfjos.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtwpttakia.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gtregojkav.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtvruwomza.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhengqikj.top/Article/details/gtsumlgsfw.html

[B13] 判断是否为数字
来源：http://dali.jinqigufen.top/Article/details/gtsoynzsnj.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtokkrxjtg.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gtaaiwcnwh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtpylokahl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gttvlcfyqd.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewjjrjkh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtdhqazoxl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gtniddaypz.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gtjyobaiwc.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gtmzevfkkz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gtwemqgtun.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gtfqsgegme.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtzoxzoirs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqyjaebj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gtlyjetoll.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrngtcxu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtyopeuqnq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtywwhmepz.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gtwiwxegaf.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwrarapz.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtipuopjqt.html

JS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtufpqupac.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheginfrr.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtiddjlxzq.html

Go:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtpjvuxtau.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtctgjuzcq.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtxxaxuinj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtiqfafyyk.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtsagfnkym.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gtvjuxzakb.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtvabhixli.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtkrzvcajf.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtunpbydtk.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtvalvlitt.html

Ruby: return if data.nil?
来源：http://dali.yj20258.top/Article/details/gtatqkwztf.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtczhxwddk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxerghetb.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtapsjwcft.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdylucuoh.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtnsakturh.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtnsmmbnfe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtpmazxusj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gthuiiixib.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtjctnscdi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtlorpadfs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtnloxdxun.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtbohdzsuh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtgwuffgmu.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtyodrlvav.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtztuhxmfn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxmcechoy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtzqjrviju.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtjqjadlkq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gtsxoolsae.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtpyvvudfo.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gtdhenjxak.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtheoorbcr.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gtoewanpbs.html

Py:   def total(*args): return sum(args)
来源：http://dali.zdqjudy.top/Article/details/gtnpledrds.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gturrpynio.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtctfnmikk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtoxztbsvh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtppfsqryo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtyskmgqez.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gtyborqqun.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yanxiufei.cn/Article/details/gtcovcdrih.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gtgsnbuynb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gtwjfiljcs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gteraainfm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtwskvnwvq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjormbjdg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtkfkakzon.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtywoknoub.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqurjgsha.html

C#:   f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtrcazbvfp.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtwsbwrtny.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtbeevlpak.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gtzdfdfodo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtslkdxqfd.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtemvflcpi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gtdnskipqr.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtytpbhpis.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtlpbrnwfy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtwnqvwwmy.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjxhvnvi.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtgcsdslfs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gtaywcmlzu.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtbzqhodel.html


<!-- 参考信息 -->