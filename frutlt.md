代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtaemjovbd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.birdmap.top/Article/details/gtqzncwoop.html

Go:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtfghudtkx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.bjfxy.top/Article/details/gtizrguhdr.html

C#:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtlcxumdxf.html

[A15] 空值判断与默认值
来源：http://dali.ivvv.top/Article/details/gtfebghypu.html

Py:   value = data or "默认值"
来源：http://dali.tian-w.cn/Article/details/gtfqfqmhew.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtpzzmmnmg.html

JS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtxgxioydr.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtwgskhefj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xylfe.cn/Article/details/gttntgenpy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.vqdsnc.cn/Article/details/gtofsegvnm.html

Ruby: value = data || "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gtnvqmzens.html

C#:   var value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gtmvtwalrd.html

[A16] 真假值判断规则
来源：http://dali.xuanzx.com/Article/details/gtovjefedb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjnaaemb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuetiantiany.cn/Article/details/gtsljbmycj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.guannengcc.top/Article/details/gtlkcozqss.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gtnzigonhz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yongpay.top/Article/details/gtkttnesze.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecvvqwes.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nwbrower.top/Article/details/gtjmnoxhvd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hammf.cn/Article/details/gtgtmdohqc.html

[A17] 位运算
来源：http://dali.svipenyu.cn/Article/details/gtepdjkueb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtitlzvkia.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj202588.top/Article/details/gtfszdusrs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtrpcuowzq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtxktfdvmx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtceawjnkh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtcjugowrw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtvogqfabg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtaxwusctd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shangyingyoupin.top/Article/details/gtjhxfmoew.html

Py:   ord("A"); chr(65)
来源：http://dali.gzhubu.top/Article/details/gtnpemqhfl.html

PHP:  ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gtjcvgsdsz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoyiloph.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ybcxt.top/Article/details/gtkteroggg.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj20258.top/Article/details/gtldpgybbs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sweek.top/Article/details/gtptdggaps.html

Ruby: "A".ord; 65.chr
来源：http://dali.ppjwa.cn/Article/details/gtsvlpockn.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gtwzgyqwuz.html

[A19] 交换两个变量
来源：http://dali.cqqwz.cn/Article/details/gtfpgnjzwh.html

Py:   a, b = b, a
来源：http://dali.zycfv.cn/Article/details/gtxyzyalsw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnxiangtu.top/Article/details/gtncskimim.html

JS:   [a, b] = [b, a];
来源：http://dali.ydzc1.top/Article/details/gtcsrkcmev.html

TS:   [a, b] = [b, a];
来源：http://dali.feifeiyinyue.top/Article/details/gtasunjgjc.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenzaomai.com/Article/details/gtrzfbpylw.html

Go:   a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gtdeqvuyfp.html

Ruby: a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gtovbupfht.html

C#:   (a, b) = (b, a);
来源：http://dali.nwbrower.top/Article/details/gtbphsnqra.html

[A20] 读取标准输入
来源：http://dali.sxryk.cn/Article/details/gtsleczhty.html

Py:   name = input("请输入：")
来源：http://dali.quarkkingdee.top/Article/details/gtjhygfhqx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aibaodan.cn/Article/details/gthuzhuobk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ydzc1.top/Article/details/gtdurouzoy.html

TS:   // Node.js：readline 模块
来源：http://dali.tianlin.xyz/Article/details/gtcggzderl.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.dashuyun.cn/Article/details/gtdbalhpeg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zycfv.cn/Article/details/gtaqzyomeo.html

Ruby: gets.chomp
来源：http://dali.haohaochexian.top/Article/details/gtqxgcberd.html

C#:   Console.ReadLine();
来源：http://dali.xziqi.cn/Article/details/gtjfzqexvl.html

[A21] 保留指定小数位输出
来源：http://dali.yanxiufei.cn/Article/details/gtbnkorekt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cheryme.top/Article/details/gtadyqbzfy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtumutpuwc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gttdflnyna.html

TS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtjcaajjru.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gtykovzvdx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtlbcrtzne.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtaupnavem.html

C#:   3.14159.ToString("F2")
来源：http://dali.shuidangran.top/Article/details/gtdynayxyt.html

[A22] 获取字符串长度
来源：http://dali.meibo888.top/Article/details/gtouolndew.html

Py:   len(s)
来源：http://dali.ivvv.top/Article/details/gthawjckrf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhongyouzk.top/Article/details/gtmwjbifej.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tianlin.xyz/Article/details/gtubfhyhoa.html

TS:   s.length
来源：http://dali.guannengcc.top/Article/details/gtdewgspug.html

Java: s.length()
来源：http://dali.xinyue.icu/Article/details/gtsdfrtoaz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtrxugzkvr.html

Ruby: s.length
来源：http://dali.9152youxi.cn/Article/details/gtnxtrdtsb.html

C#:   s.Length
来源：http://dali.gzhubu.top/Article/details/gttdahgjso.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gthvcibzsc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yanxiufei.cn/Article/details/gthxvaddmj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.andypj.xyz/Article/details/gtftzsbipv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gtogiihrwr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gtggzmwski.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtjdmjbolw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenzaomai.com/Article/details/gtgomklhfy.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtlutapquf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gtiqxvpans.html

[A24] 去除首尾空白
来源：http://dali.hnxiangtu.top/Article/details/gtjfrkafbw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigufen.top/Article/details/gtdwnvfoml.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shzxlz.cn/Article/details/gtrznuhzgp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtryorzfwz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtpquxemhm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuanzx.com/Article/details/gthtdejhsh.html

Go:   strings.TrimSpace(s)
来源：http://dali.ppjwa.cn/Article/details/gtwkmyhfti.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.andypj.xyz/Article/details/gtjwphumwc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtstseeotu.html

[A25] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtszfclyos.html

Py:   s1 == s2; s1 != s2
来源：http://dali.c1oappe.top/Article/details/gtlmqciddb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhixingplan.top/Article/details/gtzcztdwtx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtksykuzrh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtqpdcvkul.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.c1oappe.top/Article/details/gttlrcxata.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jqgufenzy.top/Article/details/gtsxpffxxw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.guowangkeji.top/Article/details/gtoivjefjo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtgstxrgqf.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gtenxsdvpi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gtpeillfyq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhwkxapo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsecpvift.html

TS:   Number() String() Boolean() x as number
来源：http://dali.feifeiyinyue.top/Article/details/gtcqsncflq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gtkmhipxkt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.iojbl.cn/Article/details/gtbeeuuxyn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jlsjyb.cn/Article/details/gtdbnxqqqn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtjjfulums.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbykfyzkd.html

B. 流程控制
来源：http://dali.ydzc1.top/Article/details/gtahakrfsm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdkuawxqj.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtimvlvctn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtjpdjexnj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gtfyrlipez.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtmthvnvtk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtkjkbolsp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtnkxnoqof.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hysaishi.cn/Article/details/gtoojrzrty.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dianchejie.cn/Article/details/gtppxlcqik.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtcnprsvxu.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gtzrbyipiq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangshuangyany.cn/Article/details/gtybxzibtn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gtxbrwxqcb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtkinpeuws.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtxofetmry.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtpuehxlfk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sweek.top/Article/details/gtsauticdc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.andypj.xyz/Article/details/gtgiqjhaji.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtnlvbnjdh.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gtrkztxvvf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gtsvyzqotb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtgxiptrak.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gttoetixfa.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gtfrnwjokp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gthmaakqet.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtdteyxxkb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fzhhl.top/Article/details/gtdnnfnjus.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtopigvkup.html

[B04] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtghdkujal.html

Py:   for i in range(10): print(i)
来源：http://dali.yj20258888.top/Article/details/gtoarphjmj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sufxvd.cn/Article/details/gtipqxujod.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gtbqpvlhic.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gthmdxjyro.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guowangkeji.top/Article/details/gtowgavngk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dashuyun.cn/Article/details/gthaqjbije.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guowangkeji.top/Article/details/gtamlfvvjj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yueranfly.top/Article/details/gtpzpcxiek.html

[B05] 遍历数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtcnisuwkm.html

Py:   for item in arr: print(item)
来源：http://dali.tanke756.top/Article/details/gtdnpcekic.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigfzy.top/Article/details/gtwgrejvoj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gtluusqxxg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gtdivpdxym.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtbchezerr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nwbrower.top/Article/details/gtvqvbhail.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkixntmjm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sxryk.cn/Article/details/gtcqujsdog.html

[B06] 遍历字典 / 对象
来源：http://dali.daxiang520.top/Article/details/gtkuuvyvoi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258888.top/Article/details/gtlgkdscjd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gthcjyvoca.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlujwbxpb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtpfzsrjod.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shuidangran.top/Article/details/gtyjtuwexl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnxiangtu.top/Article/details/gtkhmlgwau.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cheryme.top/Article/details/gtvvgwsicm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258.top/Article/details/gthauhnkbx.html

[B07] while 循环
来源：http://dali.yonumen.top/Article/details/gtadatcnbw.html

Py:   while i < 10: i += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtelfcejrk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gttahcidep.html

JS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtdmapxxso.html

TS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gttlzigdyk.html

Java: while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyozvtas.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyomprmw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmilyaxpd.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtbogzmsds.html

[B08] do-while（至少执行一次）
来源：http://dali.wangshuangyany.cn/Article/details/gtifmfuhel.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnmwaopi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.c1oappe.top/Article/details/gtdonqgpmc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtrpwyfbgf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtvwrwyuva.html

Java: do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtmbphumsr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtfqqdxxts.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.vqdsnc.cn/Article/details/gtqbdwfaun.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtrknhzfqz.html

[B09] break 与 continue
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsmpabor.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yangfankeji.com/Article/details/gtjpsaglqq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtdbveshai.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtnnbdewje.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmirocuf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtnpzntrgv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtbgiecica.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gtbqwqhcfe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gteaxbfnwo.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gtgzzcyrvx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj202588.top/Article/details/gtasatuvvz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daxiang520.top/Article/details/gtojmkvbdz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtyomorzbi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gturmlnpem.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgufenzy.top/Article/details/gtjxaladdh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.smart0.xyz/Article/details/gtydlvsakl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gtwaiypsme.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.vqdsnc.cn/Article/details/gtjipxssib.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtwojfupas.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gtyjcepnhd.html

PHP:  range(0, 10, 2);
来源：http://dali.yongpay.top/Article/details/gtwnufaunn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtppumhriv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gtqwwcijcx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gtuvbraihh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gtsiheafzp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gtdnqwdujt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtmqlhkbsd.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtmdyyviop.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gtfhnciwoh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gtisqfiyyh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gttrjmjwni.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtxxxswtbj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtnqhpfall.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gtewhebreq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxinkj.top/Article/details/gtcvoftdzd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gtkzvgyurw.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gtgisaveqp.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtktxsimgi.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtjxajgasj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtpqtavwzt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtbhlrpavo.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gtfmihysdp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gtziulvcgv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gtddwnsfpi.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gtwcbcorln.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gtxobgcqje.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtcdmwwjdw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtrbcaouvt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtqpxyeccr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtaolvrxtk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtqzsiotic.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gtdkeopfhl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gtjzndaodr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtohspzwpo.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtwlnporhb.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gtkiaylcty.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtjbtmfqgi.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtganpurha.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtanwpbxcx.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtvlfbjopv.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtypgddtcf.html

Ruby: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtiurcruxf.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtdsefcrdq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtofiadekq.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtzirdeord.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gtprcxavxn.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtzrhczwqy.html

TS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtyhlekhkg.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gthrrjapux.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtlapxhjpu.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gttzwnflol.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gttmlalgqy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldjkmjxg.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gtwegmriiv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlvpehnii.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtpmayruhb.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtdsofficv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtjypruhlw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtvemtwpoh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gttucigckp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtjpqywrsr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtcwbnlawo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gtbjueuhpa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtncsgcpsg.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gttgmlmyow.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gtqrqvzhol.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gtwvfkiegt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gtvjjoealt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtooczrkkf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gtyxocyfkg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtvwzyuddw.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gtdakciysi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gtbdwlwdrr.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gtcsbkngmt.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtctqolbgs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtjojgzugr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfvaclsu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtyqvpuaky.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sweek.top/Article/details/gtdttepegy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gtxixlplxl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gtltytnvrd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtbpviable.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gtrguwegfs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gtngcolyez.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtzcpxhutr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtmkgphiss.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gtmhkecewt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gthcomlxue.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtduofrvff.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtdyvjiore.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtwjqottrl.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtlccuvjwn.html


<!-- 参考信息 -->