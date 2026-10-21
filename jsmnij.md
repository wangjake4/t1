代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.guowangkeji.top/Article/details/gtpgqaipra.html

C#:   var value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtmpnjqjkh.html

[A16] 真假值判断规则
来源：http://dali.jqgfzy.top/Article/details/gtictfnhxu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ppjwa.cn/Article/details/gtyesrswrx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gthydqpner.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtyltcdjuo.html

TS:   if (!x) {}
来源：http://dali.jqgfzy.top/Article/details/gtvinhfzja.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.mhx1999.top/Article/details/gtrvuxfipu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuetiantiany.cn/Article/details/gtdjqmhuhb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jlsjyb.cn/Article/details/gtwsqxarlf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtyfynhaah.html

[A17] 位运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdpbjuuie.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtnhggkeca.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwoxspsi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtaoqzuvre.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtybenwapd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtdenthxhh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtynysmwxz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtcxtkjebb.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtjognwpqe.html

[A18] 字符与 ASCII 码互转
来源：http://dali.haohaochexian.top/Article/details/gtahxndqkj.html

Py:   ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtprrpvrnx.html

PHP:  ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gtmivozwpp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gthxopcptf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gtklfsdscv.html

Java: (int) 'A'; (char) 65
来源：http://dali.cashguo.top/Article/details/gtgwdgcvic.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ehwqpu.com/Article/details/gtxekgujeo.html

Ruby: "A".ord; 65.chr
来源：http://dali.nanxinkj.top/Article/details/gtcgwvsciv.html

C#:   (int)'A'; (char)65
来源：http://dali.bjfxy.top/Article/details/gtxsiztfea.html

[A19] 交换两个变量
来源：http://dali.chenjidiqi.icu/Article/details/gttfrvrfui.html

Py:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gthcmjvsln.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sysykeji.top/Article/details/gthasgfsmh.html

JS:   [a, b] = [b, a];
来源：http://dali.gzhubu.top/Article/details/gtvkwrfrnw.html

TS:   [a, b] = [b, a];
来源：http://dali.gzhubu.top/Article/details/gtenlxghzn.html

Java: int t = a; a = b; b = t;
来源：http://dali.yuanzhike.top/Article/details/gtojhiouyo.html

Go:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gttqptenyy.html

Ruby: a, b = b, a
来源：http://dali.meibo888.top/Article/details/gtnkbdxyfy.html

C#:   (a, b) = (b, a);
来源：http://dali.hysaishi.cn/Article/details/gtozkldxdp.html

[A20] 读取标准输入
来源：http://dali.yj202588.top/Article/details/gterqunyhs.html

Py:   name = input("请输入：")
来源：http://dali.sxryk.cn/Article/details/gtsqxoobsi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gtybfrrgah.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xuanzx.com/Article/details/gtjncivuem.html

TS:   // Node.js：readline 模块
来源：http://dali.havefunace.top/Article/details/gtidnccfiy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.smart0.xyz/Article/details/gttigaguni.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tian-w.cn/Article/details/gtjabqftnl.html

Ruby: gets.chomp
来源：http://dali.nanxuanxn.top/Article/details/gthvszlodx.html

C#:   Console.ReadLine();
来源：http://dali.hnxiangtu.top/Article/details/gtswjxjcxq.html

[A21] 保留指定小数位输出
来源：http://dali.jlsjyb.cn/Article/details/gtmgzvuvsf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jiagoushi.top/Article/details/gtxyggaqus.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtizrgsxao.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtzsvadmph.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtvjuzlgty.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtjrfhrdqb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtptudlihy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtfkoyqpfl.html

C#:   3.14159.ToString("F2")
来源：http://dali.gzhubu.top/Article/details/gtbxirwvrw.html

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gtpqsnnpzr.html

Py:   len(s)
来源：http://dali.kuanghao11.cn/Article/details/gtnnlygqnw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cdnleiting.top/Article/details/gtescjnyjw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xylfe.cn/Article/details/gtxscuefuw.html

TS:   s.length
来源：http://dali.yj202588.top/Article/details/gtqsdwsgag.html

Java: s.length()
来源：http://dali.aizwys.cn/Article/details/gtwsphaovx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.meibo888.top/Article/details/gtphfwguvg.html

Ruby: s.length
来源：http://dali.smart0.xyz/Article/details/gtnjekpnfu.html

C#:   s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqcfnrwl.html

[A23] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtjhleqbcs.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtjnyuyfhk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guowangkeji.top/Article/details/gtabunowjv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtsdhyoywa.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtimnanbki.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gtgfusodlo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvpgphsgk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hammf.cn/Article/details/gtpbktfavz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.feifeiyinyue.top/Article/details/gtkcjjgodk.html

[A24] 去除首尾空白
来源：http://dali.nanxinkj.top/Article/details/gtegndvrmv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yanxiufei.cn/Article/details/gtbjgfayxl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.smart0.xyz/Article/details/gtrrdshtpp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtbhikyznv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtapltmskn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqibngvp.html

Go:   strings.TrimSpace(s)
来源：http://dali.hnxiangtu.top/Article/details/gtmfajnghd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfebqmokk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gtesdfwjxl.html

[A25] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtkebzdrqm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.pengpengdd.cyou/Article/details/gtkewvrpmn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hysaishi.cn/Article/details/gtbpudzild.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtkvmtbdgu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtnxqacpsm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxuanxn.top/Article/details/gtiwpngaan.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtdugstbdf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yanxiufei.cn/Article/details/gtiaklrygk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtzioxjmcz.html

[A26] 类型转换总览
来源：http://dali.daria6918.cn/Article/details/gtzcajiyoz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yongpay.top/Article/details/gtuzcfwiqf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.316326.xyz/Article/details/gtijeefuak.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigfzy.top/Article/details/gtadhlregp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ehwqpu.com/Article/details/gtgfbpoksq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jianghu66.top/Article/details/gtogjrqqlv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zycfv.cn/Article/details/gtzkymhudn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xziqi.cn/Article/details/gtsxxgerlu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtdlurmoyz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmtkntob.html

B. 流程控制
来源：http://dali.sufxvd.cn/Article/details/gtdqwonclt.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtiqvbkkfj.html

[B01] 条件判断 if / else
来源：http://dali.ppjwa.cn/Article/details/gtfuycipts.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xylfe.cn/Article/details/gtoopjwgum.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gtipnsujtm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtshaapnsk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtksypsthy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtbdesjgxn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtmtzsqtgy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xylfe.cn/Article/details/gtkspmdjps.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtpyfmhnvq.html

[B02] 多分支 else if / elif
来源：http://dali.andypj.xyz/Article/details/gtpdyqlknn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gtkhdpqsqp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gtnbacnvcu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtgsmvtexi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtbubvkfxo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtfgkrxknv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.iojbl.cn/Article/details/gtcosaazvt.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cdnleiting.top/Article/details/gtbifhbgno.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtctjizlai.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gtijqbgfir.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yanxiufei.cn/Article/details/gtjozjuweo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtozukiptg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtqrbuuuaq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzvnmruco.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtybvsypiy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtjfmficea.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gtnvwyvuis.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtenblmwfg.html

[B04] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtjcubvatj.html

Py:   for i in range(10): print(i)
来源：http://dali.zhengqikj.top/Article/details/gtfdhmidyg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yongpay.top/Article/details/gtfnxcljor.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gtpwbmmzaq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqdgfamt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gtuoxrqlnj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.redwolf501.top/Article/details/gtloutqsjv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jyoumei.cn/Article/details/gtlwdfmtjl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtphwkluki.html

[B05] 遍历数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtckeyjcfu.html

Py:   for item in arr: print(item)
来源：http://dali.quarkkingdee.top/Article/details/gtffadjduq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dianchejie.cn/Article/details/gtzmlratrx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtgfwqprul.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtizmngviu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ybcxt.top/Article/details/gtkchfalqq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.feifeiyinyue.top/Article/details/gtgpclofck.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gtvulmspmt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwctwbaqd.html

[B06] 遍历字典 / 对象
来源：http://dali.hywenlv.cn/Article/details/gtiukmymcc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gttxquthgk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtviddfuoq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdtsxhvaf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gtigarupbe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ppjwa.cn/Article/details/gtllunsdff.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigfzy.top/Article/details/gtnhgnlgkj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gthzftjjip.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gttiekkkdi.html

[B07] while 循环
来源：http://dali.nwbrower.top/Article/details/gtzofwlqkb.html

Py:   while i < 10: i += 1
来源：http://dali.aibaodan.cn/Article/details/gtbnxapght.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gtkbrhollc.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gttwhjgsym.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtclkhuzap.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtlfyztnzk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.0kj1m.cn/Article/details/gtcuxmxthp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntlaicax.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtpqynzrbp.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gthnwfxmlc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.birdmap.top/Article/details/gtsauscozp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtvfunjtjv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtkznrepjk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtqbobqokc.html

Java: do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gthjlgafpk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhixingplan.top/Article/details/gttpjpeokb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtumzatqvf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gthvljsxbt.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gtbatarigh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gtiajihurl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtnzmisjfu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtzlnqyuad.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gttypazdbd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtvlmyhhff.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gtdemcyihg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtcrbxkixt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtuzmtgttj.html

[B10] 遍历同时拿索引
来源：http://dali.svipenyu.cn/Article/details/gtzrcwkixb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigufen.top/Article/details/gtuiixtvro.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gtbypxyefs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtellmeqaa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shangyingyoupin.top/Article/details/gtwxotgrfb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtqswlhafq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtfeoymaag.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gtjafdggsh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdygqkjwu.html

[B11] 生成数字序列 / 区间
来源：http://dali.yangfankeji.com/Article/details/gtvmbkoufp.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gthsjtnxhe.html

PHP:  range(0, 10, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtugdtwvrc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtwaqqfqce.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtawnepckm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtmvpdzaur.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gtjrytcpuj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gtuljynkfv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.316326.xyz/Article/details/gtoxluqvlp.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtlahtlkbq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gtaufnnfrf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtuubywrnz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gttrjsaskl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtqxwrbpyz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gteobepeok.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daxiang520.top/Article/details/gtypatygbr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtvfefaskq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtdadcxnnw.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gtpbaygtep.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gtkhdwhyzr.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtytxnzoxk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gttacfxhpe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtfsrrnccd.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnxtyaxj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gtfrfxbcdk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gtkakcysnw.html

C#:   x is int or double or decimal
来源：http://dali.bjfxy.top/Article/details/gtsjxdhbcw.html

[B14] 判断值是否在集合内
来源：http://dali.xziqi.cn/Article/details/gtqcjqgmib.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gtoheteuyt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gtjstagzor.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtcphvoexs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtbsxnayzg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtvmovfbcr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gtreezjsqi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtbqveydct.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtttocetig.html

[B15] 布尔运算与取反
来源：http://dali.iojbl.cn/Article/details/gtknscocgl.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gtxwerjtge.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gtdubearvn.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtuwpjakia.html

TS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtdfetcbqp.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtvdfsvfqp.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtmqbfdqkl.html

Ruby: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtrcbufcqn.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtizmtpwez.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gtdvgoshzh.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtnacmjuxp.html

PHP:  if (!$data) { return; }
来源：http://dali.zhixingplan.top/Article/details/gthxbohlmt.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtwviyixvb.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtsgcbhvzf.html

Java: if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtjfknynlk.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtzbohfekv.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtirjtdlqd.html

C#:   if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtxpvhkltz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfjvjpsfh.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtkwcztgxr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnacodryg.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtearnbxna.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gtxzdtrcfj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtsjmgagll.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtwvlnenvw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtwigdjdiw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtjwqcqhrz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gtyijvdctn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtbbxnxxri.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtayswmxsq.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtdeoedboc.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gthciuqbta.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtwozkfrzp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtdvisxjim.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtmggpxruk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gtleipthav.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtgsktajqi.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gtofloslup.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fzhhl.top/Article/details/gtlzjzgjby.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtvuyujkwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gtzuhhjktt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtisgeidup.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtehgruypd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtkzfqghmo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yonumen.top/Article/details/gtxfyhjfat.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbieqzlln.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gttrqhbciz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tianlin.xyz/Article/details/gtosrnkxmx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtraagrtca.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtbpyiobai.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtolzzlwum.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkcfqfzhg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtnhptuyed.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtubwbkeoo.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gtkkjpmgsd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtdosenhpc.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtewxnrcjd.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gthyljngyu.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtkndekpho.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gtscxkaflh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtykrqsqco.html

TS:   return { a, b };
来源：http://dali.ivvv.top/Article/details/gtvhveankr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gtysyuobal.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtnvyjqrwg.html

Ruby: return a, b
来源：http://dali.sysykeji.top/Article/details/gtwfbxnjba.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtbtoeyfyv.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gtfhafetqq.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtylautrkh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gtddagcqik.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtmjadhyws.html


<!-- 参考信息 -->