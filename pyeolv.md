代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.mhx1999.top/Article/details/gtfyeblmow.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenzaomai.com/Article/details/gtxdmzmrcm.html

TS:   if (!x) {}
来源：http://dali.sweek.top/Article/details/gtpnymxicn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtslrcyoyt.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.wangdashe.top/Article/details/gtlxauufqc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.feifeiyinyue.top/Article/details/gtgkcmazzl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfyzefotq.html

[A17] 位运算
来源：http://dali.pycfn.com/Article/details/gtvkuwqvwm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtyjiojpxr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gzhubu.top/Article/details/gtebstcxvx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtbcjpjokn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtcpgewvqw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtkdvezdwc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtfqomyluz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gttbjsguyk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtxmlfndlk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ppjwa.cn/Article/details/gtobxjodbz.html

Py:   ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gtmsitqaba.html

PHP:  ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gtjknxqiwa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gogol.net.cn/Article/details/gtzgsnftin.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xziqi.cn/Article/details/gtupbrvikn.html

Java: (int) 'A'; (char) 65
来源：http://dali.daria6918.cn/Article/details/gtycpouikn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tian-w.cn/Article/details/gtdqazuhrd.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangdashe.top/Article/details/gtoicmlyaq.html

C#:   (int)'A'; (char)65
来源：http://dali.sufxvd.cn/Article/details/gtdjcludxp.html

[A19] 交换两个变量
来源：http://dali.tanke756.top/Article/details/gtnjxrohdt.html

Py:   a, b = b, a
来源：http://dali.zhongyouzk.top/Article/details/gtlklegnvj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxinkj.top/Article/details/gtjlfuvpqy.html

JS:   [a, b] = [b, a];
来源：http://dali.pengpengdd.cyou/Article/details/gtrmkcelgh.html

TS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gtqfqiahqh.html

Java: int t = a; a = b; b = t;
来源：http://dali.cdnleiting.top/Article/details/gttbzthitx.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gtuqrwswtu.html

Ruby: a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gteylqpczz.html

C#:   (a, b) = (b, a);
来源：http://dali.chenjidiqi.icu/Article/details/gtixwkivkv.html

[A20] 读取标准输入
来源：http://dali.meibo888.top/Article/details/gtqizhouml.html

Py:   name = input("请输入：")
来源：http://dali.smart0.xyz/Article/details/gtgqfvvcmw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ivvv.top/Article/details/gtxgwmcxbq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shangyingyoupin.top/Article/details/gtmyseoydc.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtsclnpybp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yuxming.cn/Article/details/gtkahgfliv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.daria6918.cn/Article/details/gtgxvtaxqp.html

Ruby: gets.chomp
来源：http://dali.cheryme.top/Article/details/gtjdqdkflj.html

C#:   Console.ReadLine();
来源：http://dali.tanke756.top/Article/details/gticdxfutp.html

[A21] 保留指定小数位输出
来源：http://dali.jiagoushi.top/Article/details/gtccottigp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenlongwang.top/Article/details/gtvfwyqlfl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtizgfajzp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gttomatoux.html

TS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtqblndmxi.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtkrmquxnz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtemmnmxgl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtvmukchsa.html

C#:   3.14159.ToString("F2")
来源：http://dali.yongpay.top/Article/details/gtuwtmymso.html

[A22] 获取字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaddixdxt.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtsbojawbz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hnqzz.top/Article/details/gtgphxjkal.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ehwqpu.com/Article/details/gtbxzodaji.html

TS:   s.length
来源：http://dali.fzhhl.top/Article/details/gtxqbjjgma.html

Java: s.length()
来源：http://dali.ivvv.top/Article/details/gtwgwvmoxp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gthzpjfonv.html

Ruby: s.length
来源：http://dali.dashuyun.cn/Article/details/gtvvukucqb.html

C#:   s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxlutcbe.html

[A23] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtskwvxiqs.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gtpleqdblr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonlwvkxd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtwlbrggjd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gtrxxzhrvm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gtrtvbqzxl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtxszfnchn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtyfdychwb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gzhubu.top/Article/details/gtjmxhaubj.html

[A24] 去除首尾空白
来源：http://dali.cqqwz.cn/Article/details/gtuemaasjv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yvedp.cn/Article/details/gtzvqztkik.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.smart0.xyz/Article/details/gthmjegahx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gtnonkvfit.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtwrxcghad.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.snrcjt.cn/Article/details/gtnhpwibxr.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhijiandao.cn/Article/details/gtcfcjmfsp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shuidangran.top/Article/details/gttzqjrkvh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yueranfly.top/Article/details/gthzvpytjd.html

[A25] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtpzbwxbet.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigfzy.top/Article/details/gtagefcodr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yangfankeji.com/Article/details/gtpsuxmrvr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gthlwfwsdv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtoyqijgnl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gtczyhsdop.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtsvdybldr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.iojbl.cn/Article/details/gtyhmqutmj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gtadehwqwg.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gtcaolnlzi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.fengsongda.top/Article/details/gtngbnhdtk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hongshengwenyu.top/Article/details/gtjqgzzgav.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.guannengcc.top/Article/details/gthpdadxsb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tian-w.cn/Article/details/gtcewsvgqq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gtqluwtpzl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gtfisgqqzo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.svipenyu.cn/Article/details/gtexbrzmub.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtzuxordgx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxwaumops.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gtkchtfyab.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlmbajepb.html

[B01] 条件判断 if / else
来源：http://dali.zhongyouzk.top/Article/details/gtclzkesnd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnqzz.top/Article/details/gtsglcxofw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jianghu66.top/Article/details/gtwnfstctz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtkohmyney.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtfgryjqzg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtuqquyknb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gtvtwlwuzk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.birdmap.top/Article/details/gtczcmrjpu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtnnbnbdjj.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gtmfbuqrgu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fzhhl.top/Article/details/gtavecmyir.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gtspvrrrer.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gttlqavwhc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtbbzozber.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gttmsosguy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yongpay.top/Article/details/gtiaobufts.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daria6918.cn/Article/details/gtuexcycka.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtpswqabld.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gtydkvpgkd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hnqzz.top/Article/details/gtqygsotcq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sweek.top/Article/details/gthbvlgkmq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtbkqilaob.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtrxmzralh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtdbqvxlgq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtulwfjwhl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gtbiisbjej.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hfpthk.cn/Article/details/gtcscafjna.html

[B04] for 计数循环
来源：http://dali.pengpengdd.cyou/Article/details/gtkjpqlddv.html

Py:   for i in range(10): print(i)
来源：http://dali.dashuyun.cn/Article/details/gtodupwdtn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.birdmap.top/Article/details/gtuvmyfepg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtcjlplidq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtnzuxajtj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenlongwang.top/Article/details/gttlhoqnjt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xinyue.icu/Article/details/gtbymvffon.html

Ruby: 10.times { |i| puts i }
来源：http://dali.meibo888.top/Article/details/gtwpiheetr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gtbeguckfe.html

[B05] 遍历数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtxnaogjgy.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gtdxvucwey.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gtjhmlqpqi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gtsytnqskx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gtnqtpuqva.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenzaomai.com/Article/details/gtpoohjpsx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jyoumei.cn/Article/details/gtvdhfuswn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gtdgqkbwmg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuanzx.com/Article/details/gtmdtntarf.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gturojnxhu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhengqikj.top/Article/details/gtpoglrrkg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tanke756.top/Article/details/gtrqqpkdiq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtjicvjaeh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtitzievzu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxuanxn.top/Article/details/gtbxxtlxvp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtmugvxlzy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gtqjhkufwc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gtontrkgle.html

[B07] while 循环
来源：http://dali.yuanzhike.top/Article/details/gtqoioolfb.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gtsulshhpd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tian-w.cn/Article/details/gtbbdqufly.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gttipwwahk.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtqeawmoaz.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gticyzpfuw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258888.top/Article/details/gtblgbqcjf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ivvv.top/Article/details/gtdrudbijv.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtardwosti.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gtorhejmrk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhixingplan.top/Article/details/gtkdldzphg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtqfdcyfuu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gthfzkhawy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtqizbcbuh.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtaitviant.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gtaohzcpaz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gtphboiqwz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtqbxwxcjg.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gtgkyygsjf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuanzhike.top/Article/details/gtdjqoipvv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtnvutxvsy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmaturor.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtomkwxxlw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtwboxxtwr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gtquwtbzrv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.snrcjt.cn/Article/details/gtkpzkhdhe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtbcdtmtxe.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtesyvqthy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpkcmhxu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gtiowtjorr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtmbarsiem.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gttslottcy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtjlublphu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ydzc1.top/Article/details/gtorolzjge.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.havefunace.top/Article/details/gtdtdcrxfh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtotoirglj.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangshuangyany.cn/Article/details/gtrfxoowut.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtpwnrrwmx.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gtjiqagybg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtdbopzmkw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjvsxywl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gtsbelojiq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtywrrdldh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtypwdhnvz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtnpmuufcy.html

[B12] 跳出多层循环
来源：http://dali.gotoacloud.top/Article/details/gtuuuiuqnc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gtkjwflbgb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhnzjnjb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtmrswlyoa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtigxmtwjn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaowumfol.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtuacoioso.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.havefunace.top/Article/details/gtsejddveq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pycfn.com/Article/details/gtyeaetdei.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtpxxmwqix.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtuzjvjlmi.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gtgotmtsna.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtelrehcwo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtkqshllyp.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokvmbjts.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jiagoushi.top/Article/details/gtvkismaxu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gtdjqnpduf.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gthcmpdmpq.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtsjlihhqp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtayxnvwvs.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtrutcrflz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtenpmstdo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtudjjledq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtayowujsc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gtzbsputax.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jianghu66.top/Article/details/gtoptiujja.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gthmoqljis.html

[B15] 布尔运算与取反
来源：http://dali.yj20258.top/Article/details/gtgbtszzrk.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtpgitpaaj.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gteguivsie.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtswmylbsu.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtlriiiqap.html

Java: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsscwcgwb.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtyusmjwck.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtwmlkwgpa.html

C#:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtmapmesbb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gtwywulryp.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gtzxfropkx.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtmiusnqag.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtcefilpup.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtsellitdc.html

Java: if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtpfhohtpl.html

Go:   if data == nil { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtxczqnxuo.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gtlbcjtjyn.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtmfainrue.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqvyvabwc.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gttamtwonl.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtsppijhhn.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtgrszisei.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gtvudhesgm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtokeokqqt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gthesgzire.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtebpsvjgo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtijvezwbm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtscxjxrmz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtlijizoob.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtxazefmca.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gtjzvhkjbm.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtvncmctej.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgutqouho.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gthjaxpgxu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcfmxhig.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gteftokayk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtzmfjznmn.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gtxnpjkzvk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gtnfgfvxyj.html

[C03] 可变参数
来源：http://dali.yj20258888.top/Article/details/gtsfbjkpcr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gtvlrjoprx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtstdcmdgo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtrdhrnxbc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtrrxnuyow.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtajyfwnrp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtmnewgzys.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtxsffhnse.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gtjdzbcwiz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtvinzocsc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtgcbeyarc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gtmpchtsao.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtlglosids.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtqpzzaxda.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gtmlhrinxa.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gtndgalddt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gttxjdmmlf.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtwbvlotkh.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gttnfxdrlo.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtlifdvxnk.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gtkuexobnx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtveecbrkl.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gteeyujgah.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gthtnmjrro.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtrpbwdegb.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gtdwqakvbn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gtmitybxac.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gttfupbfuq.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gtynkvnrch.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtwapgkcag.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdicdrugr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtfryrpnrb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtjespsgau.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gtbocrdogp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctldecdb.html


<!-- 参考信息 -->