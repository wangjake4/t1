代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtpcmewzrd.html

TS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtklrypbkz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daxiang520.top/Article/details/gtcrhiasek.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yanxiufei.cn/Article/details/gttuazejbo.html

Ruby: value = data || "默认值"
来源：http://dali.cucudq.cn/Article/details/gtjzaulhmt.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtimfvrlmm.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gtstxmzmws.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgfzy.top/Article/details/gtlbhvutzo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ppjwa.cn/Article/details/gtsyjgzeqm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhongyouzk.top/Article/details/gtnxkwrssc.html

TS:   if (!x) {}
来源：http://dali.hnxiangtu.top/Article/details/gtvajtkuui.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cheryme.top/Article/details/gtnyjashzg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yuanzhike.top/Article/details/gtptpnjrvq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sysykeji.top/Article/details/gteqsfgqzp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtsiradqpz.html

[A17] 位运算
来源：http://dali.yanxiufei.cn/Article/details/gtsjxkgkwy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtvizaftvi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zycfv.cn/Article/details/gtwojcjbrk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtmefxvfpu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhpgzsyq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtritywzbb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtyznyhosp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtuntvtsyc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtgslyrzzw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dashuyun.cn/Article/details/gtyphjyzha.html

Py:   ord("A"); chr(65)
来源：http://dali.jyoumei.cn/Article/details/gttwaszmbe.html

PHP:  ord("A"); chr(65)
来源：http://dali.guowangkeji.top/Article/details/gtlpnamthz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtawqgnrjh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gtbcdpobtq.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrpqmbci.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.guannengcc.top/Article/details/gtdtmnbptb.html

Ruby: "A".ord; 65.chr
来源：http://dali.tianlin.xyz/Article/details/gtkdncvzah.html

C#:   (int)'A'; (char)65
来源：http://dali.dianchejie.cn/Article/details/gtfwokafjd.html

[A19] 交换两个变量
来源：http://dali.haohaochexian.top/Article/details/gtpykrvhcf.html

Py:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gtzofhmgod.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sufxvd.cn/Article/details/gtkzeapgrj.html

JS:   [a, b] = [b, a];
来源：http://dali.jlsjyb.cn/Article/details/gtrxwhsexj.html

TS:   [a, b] = [b, a];
来源：http://dali.mhx1999.top/Article/details/gtetexswun.html

Java: int t = a; a = b; b = t;
来源：http://dali.sufxvd.cn/Article/details/gtyxiqxswe.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gtdvqlnauc.html

Ruby: a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtzhwxdrbo.html

C#:   (a, b) = (b, a);
来源：http://dali.hnxiangtu.top/Article/details/gtsumvgujt.html

[A20] 读取标准输入
来源：http://dali.aizwys.cn/Article/details/gtcrisjoks.html

Py:   name = input("请输入：")
来源：http://dali.snrcjt.cn/Article/details/gtwcpmxrxn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gtbfjqubyv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jiagoushi.top/Article/details/gtpfdzlmgh.html

TS:   // Node.js：readline 模块
来源：http://dali.gotoacloud.top/Article/details/gtoygmypha.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cdnleiting.top/Article/details/gtjjbdcjle.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aizwys.cn/Article/details/gtdtvsopqs.html

Ruby: gets.chomp
来源：http://dali.fengsongda.top/Article/details/gtezsjcwyq.html

C#:   Console.ReadLine();
来源：http://dali.nanxinkj.top/Article/details/gturkfbqeg.html

[A21] 保留指定小数位输出
来源：http://dali.jinqigfzy.top/Article/details/gttxazpnlg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yongpay.top/Article/details/gtcjnoxtak.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtorpxfzqt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtvbypkpjx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtljztffop.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtfhcxscjc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gthfogleax.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gtmnmzyxah.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxdxsges.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtaxrrgosx.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtehjnjwnj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pengpengdd.cyou/Article/details/gtwflioacx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.bjfxy.top/Article/details/gtxgtlrvgd.html

TS:   s.length
来源：http://dali.daria6918.cn/Article/details/gtmpuinhjm.html

Java: s.length()
来源：http://dali.hfpthk.cn/Article/details/gtijrxicca.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guowangkeji.top/Article/details/gtqomgqyya.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtitlyjfgm.html

C#:   s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcihrhxc.html

[A23] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtcuriomdf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.smart0.xyz/Article/details/gtlypahwlu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gttukftzoj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtzvvzilug.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtkesflsva.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gtrgtlqswo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqowtwwnc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtpdzuzzxp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yanxiufei.cn/Article/details/gtzzomhmdt.html

[A24] 去除首尾空白
来源：http://dali.zdqjudy.top/Article/details/gtzfgfcvkp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tian-w.cn/Article/details/gtnclydbpg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shzxlz.cn/Article/details/gtbclmhtps.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gtebzuaoea.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtmqslnlsa.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jinghuilouyu.cn/Article/details/gthifklhhj.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtqynhdviy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinqigfzy.top/Article/details/gtvhpjuxfa.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yongpay.top/Article/details/gtvieisste.html

[A25] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtwwemdmxi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gtpxjvdkcm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tanke756.top/Article/details/gtbhjzhprv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gtoonrxkai.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtsssrmkde.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yvedp.cn/Article/details/gtnvptozft.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtgjsihirs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinqigufen.top/Article/details/gtziulxrne.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigfzy.top/Article/details/gtyxkvetyg.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gtlgrleroe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zycfv.cn/Article/details/gtwtqgdrnf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guannengcc.top/Article/details/gtdpwzenzw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dashuyun.cn/Article/details/gtmibzemwr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hysaishi.cn/Article/details/gtoewzhiku.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hammf.cn/Article/details/gtxzwoibgw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gtqbcafoqq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gotoacloud.top/Article/details/gtrkxeubmu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gtbqjppfmo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtwiccdhgn.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtmopxavor.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjiaopnrf.html

[B01] 条件判断 if / else
来源：http://dali.sufxvd.cn/Article/details/gtofmgfuen.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gtscltovia.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gtyqplqsbs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gtdbzrbrxm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtddbdcucq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtzednquda.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hfpthk.cn/Article/details/gtwoepikin.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gtawvumlvp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtblqkdgoj.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gtxbprxqru.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xziqi.cn/Article/details/gtdzujmufx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tian-w.cn/Article/details/gtkkrtrrgo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gttdmuhtqm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gthryxvcvz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtjsotcftp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gtghtmpgsh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.havefunace.top/Article/details/gtteokvefr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtutbgodon.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gtafmzmtqp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nwbrower.top/Article/details/gtfirupegk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtekqmliso.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtiblyiwjh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtmeizinst.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwapnnxlh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aibaodan.cn/Article/details/gtdaumcueg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gtibvanafl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yongpay.top/Article/details/gtprvhwggl.html

[B04] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gtzcczywtp.html

Py:   for i in range(10): print(i)
来源：http://dali.sufxvd.cn/Article/details/gtiqlxwjfq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jiagoushi.top/Article/details/gtifoqplfz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gtffpfaynh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gtanevdgfo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gtfzavjxlm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnqzz.top/Article/details/gtltrapear.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gtespqugar.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuanzhike.top/Article/details/gtqfvncvwj.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbpgnady.html

Py:   for item in arr: print(item)
来源：http://dali.yongpay.top/Article/details/gtatmlxmiz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gtdmowagls.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnyyqolkx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtdlmedjcl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenlongwang.top/Article/details/gtllydmirz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gtcknbekzo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtoawrrfke.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gthhlkstpa.html

[B06] 遍历字典 / 对象
来源：http://dali.shangyingyoupin.top/Article/details/gtpppvvvjb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gtuzxgtycm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hysaishi.cn/Article/details/gtwbaxbafl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gtvfjqsuno.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtegghigzh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpulwzvii.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xinyue.icu/Article/details/gtwiwlqpmc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hfpthk.cn/Article/details/gtvfknotsg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnkivpstt.html

[B07] while 循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhhzmkwa.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gtmzwgedrs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtuewppsle.html

JS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtvvyioapq.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtjywitrwf.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtejauzxjt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtqqsacjaj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.mhx1999.top/Article/details/gtohyfdmpd.html

C#:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gteofjpuak.html

[B08] do-while（至少执行一次）
来源：http://dali.c1oappe.top/Article/details/gtqimwekan.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gtkdbvjbyq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jianghu66.top/Article/details/gtamrevsbj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtyszlatjf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtymuskfbh.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtbjvqpkgp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tanke756.top/Article/details/gtsokvwdhm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gthirojgkx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtntewkfzk.html

[B09] break 与 continue
来源：http://dali.hfpthk.cn/Article/details/gtmrdnlrqv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nanxuanxn.top/Article/details/gtkeietjwm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtnedapqsf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtabejuclc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtgciilibc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtuhzierki.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gtudfzppyf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtflwfthhf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtsdypungn.html

[B10] 遍历同时拿索引
来源：http://dali.sweek.top/Article/details/gtgjvuezmz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhidntms.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gtrxktyhis.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtzihlxfpd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtnumgmsgn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fengsongda.top/Article/details/gtzalowiph.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xinyue.icu/Article/details/gtvdcutwrx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtulqkfdvy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtanvcvfuo.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gtguubjglu.html

Py:   list(range(0, 10, 2))
来源：http://dali.haohaochexian.top/Article/details/gtazqbotbb.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwovhjukd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtkfvzezpr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.quarkkingdee.top/Article/details/gtkjbrrdzg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtnggoanac.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.meibo888.top/Article/details/gtdylbccpb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gtpzwvzgfu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtburelhpx.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gtoeylifcq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdrcknpl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtsusgvlkw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtticelnsg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtnjbazweu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtqvooduay.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gtbookaebq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtplxnlkuy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gttzcpwufk.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtvszbyfbk.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtyzhkpmqy.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtmawqtgwk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtxmtqhhfn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtwgdtyskz.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gtfekcqwwi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gtcmvknsnp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtyubstkfo.html

C#:   x is int or double or decimal
来源：http://dali.jiagoushi.top/Article/details/gtjbfsfllu.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtqtdmemqm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtscoxgkyf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gtzlehtlhf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtdqbanctp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtfzydcyxi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gtxtftpqnu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gtdnwggtzu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gtalvlbdyg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtjdlrmfyd.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gtndxvkvbz.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmpazfry.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gtuhbnmmwx.html

JS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtqjcdvgdc.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtqwyljeqp.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtxfkprurx.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtllhgbqod.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtllbwfvak.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtfzbsebtv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtzjyvycrk.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtjobwtiku.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gtjbkdhqgw.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtoivtjkch.html

TS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gthnthlxjv.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtxuvcgybr.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtwcsacvqx.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gtffykaqro.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtuzaocqfi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnoreoapg.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtplpvnhux.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttsadqsft.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtofcgkxpe.html

Py:   def add(a, b): return a + b
来源：http://dali.yongpay.top/Article/details/gticnhbmxs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtnymbdwmi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtyrlbahti.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtprppavnj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfgflbqhb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtvppcvquw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtowasdrpu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtfhhcjbbh.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqeujykux.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtfwqhwuvf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtcccjbefx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtsvpphzux.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtkyukvllh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtprnnooiu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtfgxyoogo.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjcyjxir.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtiexjpksy.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gtnpxyumyx.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gthwtjaavk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ehwqpu.com/Article/details/gtdiddwsye.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gtbgoigvzq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gterjdhhup.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gthgfntkuv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gtsfvosume.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtupqnwvez.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtcgesmhjf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gthoeztvfe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gtnfwveyub.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gtkrmhurzo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtacnuriom.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gtpyzmtnvh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtyumsxfbw.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gttnvkoerx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtakhxsdrl.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtxyhkmand.html

[C05] 返回多个值
来源：http://dali.jyoumei.cn/Article/details/gtogwylltp.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtpnmpkfcd.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtiuajzazj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtrwhcggcg.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtnwhstcgg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtuyuigdcr.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gttkqlwzdc.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gtmtrxzmzr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jlsjyb.cn/Article/details/gtzksbwvbt.html


<!-- 参考信息 -->