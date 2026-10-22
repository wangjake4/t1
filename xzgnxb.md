代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtyrwrlnbf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ppjwa.cn/Article/details/gteizccqsw.html

Go:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtnvkejpwh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.havefunace.top/Article/details/gtjfdaguuk.html

C#:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtuopdduoc.html

[A15] 空值判断与默认值
来源：http://dali.gzhubu.top/Article/details/gtwzchnkmi.html

Py:   value = data or "默认值"
来源：http://dali.zhiwuduotai.top/Article/details/gtpbidmrof.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtsqvtzjsd.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gtpjcitxob.html

TS:   const value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtifiafpyy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.kuanghao11.cn/Article/details/gtzrsnyrwa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.snrcjt.cn/Article/details/gtgfzznlxt.html

Ruby: value = data || "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrtbmmrc.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtcmnimjay.html

[A16] 真假值判断规则
来源：http://dali.tian-w.cn/Article/details/gtscqxwfse.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.havefunace.top/Article/details/gtgygyhxri.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.feifeiyinyue.top/Article/details/gtryqwmghx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gthegsyvvk.html

TS:   if (!x) {}
来源：http://dali.fzhhl.top/Article/details/gtwucbeksb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hammf.cn/Article/details/gthuqlsyrb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.wangdashe.top/Article/details/gtczepiejz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xylfe.cn/Article/details/gtumbatagb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtswikhooz.html

[A17] 位运算
来源：http://dali.shangyingyoupin.top/Article/details/gtqrxsooar.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhpquiya.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.iojbl.cn/Article/details/gtcraolgcs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtfmgqklnt.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtcdlvpfvb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtvxkqyjqp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtymcpcdpj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gttpqtsfoe.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtzrngkdty.html

[A18] 字符与 ASCII 码互转
来源：http://dali.redwolf501.top/Article/details/gtwijevnhu.html

Py:   ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gtczehdbkh.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gtukcuitwn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gogol.net.cn/Article/details/gtvpkhsprv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gthgzicugk.html

Java: (int) 'A'; (char) 65
来源：http://dali.sufxvd.cn/Article/details/gtwcvjxtoh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jianghu66.top/Article/details/gtjszzbxnw.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gtzzuatyuz.html

C#:   (int)'A'; (char)65
来源：http://dali.yj20258.top/Article/details/gtqkytfrde.html

[A19] 交换两个变量
来源：http://dali.yangfankeji.com/Article/details/gtwrulwwwd.html

Py:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gtwmbjbfvx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sufxvd.cn/Article/details/gtjtfngmqi.html

JS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtqwmvpaqc.html

TS:   [a, b] = [b, a];
来源：http://dali.yangfankeji.com/Article/details/gtfybcgitw.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj20258888.top/Article/details/gtyyyugjll.html

Go:   a, b = b, a
来源：http://dali.sufxvd.cn/Article/details/gtkzgfzndn.html

Ruby: a, b = b, a
来源：http://dali.tanke756.top/Article/details/gtormikbhk.html

C#:   (a, b) = (b, a);
来源：http://dali.andypj.xyz/Article/details/gtqosafljr.html

[A20] 读取标准输入
来源：http://dali.jianghu66.top/Article/details/gtwiwyzpud.html

Py:   name = input("请输入：")
来源：http://dali.gotoacloud.top/Article/details/gtwhnxgpeq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gogol.net.cn/Article/details/gtfzxsulos.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dashuyun.cn/Article/details/gtrbpbkaqk.html

TS:   // Node.js：readline 模块
来源：http://dali.yj202588.top/Article/details/gtmjezhthc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hywenlv.cn/Article/details/gtofjjbyee.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj202588.top/Article/details/gtofkkmxpa.html

Ruby: gets.chomp
来源：http://dali.jqgfzy.top/Article/details/gtyzcbfuzw.html

C#:   Console.ReadLine();
来源：http://dali.chenjidiqi.icu/Article/details/gtvakalfjy.html

[A21] 保留指定小数位输出
来源：http://dali.gotoacloud.top/Article/details/gtaswvldrt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jiagoushi.top/Article/details/gtedlerkts.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtfmqlsmlg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gtwhtsvxhh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtpkmkclbk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtlqurwsfk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gtabentygb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtojlukwgr.html

C#:   3.14159.ToString("F2")
来源：http://dali.guannengcc.top/Article/details/gtmmcpbfaq.html

[A22] 获取字符串长度
来源：http://dali.yj20258888.top/Article/details/gtwsiohcno.html

Py:   len(s)
来源：http://dali.zhengqikj.top/Article/details/gtumeiaebh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zycfv.cn/Article/details/gtslqarshh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.redwolf501.top/Article/details/gtfnpckfml.html

TS:   s.length
来源：http://dali.jyoumei.cn/Article/details/gtwrrziztx.html

Java: s.length()
来源：http://dali.zdqjudy.top/Article/details/gtooyilwtv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yangfankeji.com/Article/details/gtdpvaphns.html

Ruby: s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfouimjc.html

C#:   s.Length
来源：http://dali.hfpthk.cn/Article/details/gtsvehztgv.html

[A23] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtojapmyaj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtexfirvih.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ppjwa.cn/Article/details/gtomqxqqby.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjnzxagf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gtbuprgrpt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtxbghgdrl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cdnleiting.top/Article/details/gtidcdyago.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzeudlye.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xinyue.icu/Article/details/gtepeclumx.html

[A24] 去除首尾空白
来源：http://dali.zhoulong.xyz/Article/details/gtciwecfsw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ehwqpu.com/Article/details/gtjlkdrhpi.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aizwys.cn/Article/details/gtpudsatui.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gterwoofiw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtwtdlhmbl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.feifeiyinyue.top/Article/details/gtryjnyiat.html

Go:   strings.TrimSpace(s)
来源：http://dali.birdmap.top/Article/details/gtcitjiqkc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gzhubu.top/Article/details/gtwpwclpcv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gtiyxhyrzi.html

[A25] 字符串比较
来源：http://dali.meibo888.top/Article/details/gtnvrpqxvf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gthcxvhtug.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ivvv.top/Article/details/gtewoqjxkm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtkksvocxe.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cdnleiting.top/Article/details/gtbsreahqj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.c1oappe.top/Article/details/gtyyyqedil.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gtyzivccws.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.redwolf501.top/Article/details/gtqvacdukg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqufiopw.html

[A26] 类型转换总览
来源：http://dali.wangshuangyany.cn/Article/details/gtgrhjcttf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.c1oappe.top/Article/details/gtkswipjke.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gthvzchcmn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhengqikj.top/Article/details/gtnnbzyosa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenzaomai.com/Article/details/gtkubimhbx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gtdqqnuirt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gthyqinstu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenzaomai.com/Article/details/gtczdaehdb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtgzcciixq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrxmjmsz.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gtxcmpwphi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvstkvael.html

[B01] 条件判断 if / else
来源：http://dali.0kj1m.cn/Article/details/gtjgcezmhh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yangfankeji.com/Article/details/gtklqwivxm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhixingplan.top/Article/details/gtceqgokjv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtvgaddxcj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtkxsrxuqx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtsiememgc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cheryme.top/Article/details/gtwztjbymn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gtrxqevnwg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtqaiwzrde.html

[B02] 多分支 else if / elif
来源：http://dali.ehwqpu.com/Article/details/gtdmesyyda.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.birdmap.top/Article/details/gtknypaiqb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yongpay.top/Article/details/gtkorpykna.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtrfoitpja.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtegnrldwt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtklsnnnmm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtfmzqnnnx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigfzy.top/Article/details/gtgaxjhdnc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtpkaipzek.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gtsnqfcdwr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yangfankeji.com/Article/details/gtwblimmmc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtaywnxduq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtynwtvgtq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtcqthftxm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gtjuopkteq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sysykeji.top/Article/details/gtijanxqvk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zdqjudy.top/Article/details/gtesgitvfu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtzlszsvkj.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlfusxvu.html

Py:   for i in range(10): print(i)
来源：http://dali.hnqzz.top/Article/details/gthbbmenzh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxinkj.top/Article/details/gthzkjxjmq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtydfyyhab.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gtiufbwetw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtngpnbnge.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.snrcjt.cn/Article/details/gtzncclaqo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gtkankshbu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.snrcjt.cn/Article/details/gtqonzimxg.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtoatfbxak.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gtqymyxqdk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzuspxpzm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtwwirhxky.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtwiptudiu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.9152youxi.cn/Article/details/gtcktjrviq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhixingplan.top/Article/details/gtdoklyoqm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxevapxup.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjqqgzfb.html

[B06] 遍历字典 / 对象
来源：http://dali.zdqjudy.top/Article/details/gtwurtnoas.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigufen.top/Article/details/gttxbfgwik.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sweek.top/Article/details/gtydupmbwx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtlpvmxzwl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtmbpvnnnz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gtwpiuiple.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fzhhl.top/Article/details/gtbaaibpfl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gtexbeclmh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jianghu66.top/Article/details/gtbdmqkbdi.html

[B07] while 循环
来源：http://dali.meibo888.top/Article/details/gtufsfbpjv.html

Py:   while i < 10: i += 1
来源：http://dali.chenzaomai.com/Article/details/gtbqncmnzt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenzaomai.com/Article/details/gtmqopgckb.html

JS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtmwbvkptb.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtfnximexj.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtxedxzikr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtvtkxcfko.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhoulong.xyz/Article/details/gtiaiqfmqh.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtwwytwnbc.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamwiesln.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gtdnazhpof.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tian-w.cn/Article/details/gtjbfwxajn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtgrvqvluc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtbjrbbwla.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtrwvoagwp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cheryme.top/Article/details/gtzmqcpoyi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gtybotzmka.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtiiyppyyo.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gtebzmhobb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jyoumei.cn/Article/details/gtidlecrtw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtdxsmrliz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtkmgeuwtm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtrhrryruu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtkylmijxv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258888.top/Article/details/gtqkuzwksz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtucuyaqza.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvhuyrqx.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwjiiytt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gtagtgxtvq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gtighlgohh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtyjuwmgyz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtswnfzxcv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gtmwnyirjk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hysaishi.cn/Article/details/gthlxsjbvw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gthmiuwdqf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gtlgdmitmh.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gtrjblvucf.html

Py:   list(range(0, 10, 2))
来源：http://dali.tian-w.cn/Article/details/gtmbykcbke.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtdfbbojfd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtoozvewqa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtqlklrrdu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gtviftkptv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gtbxsmezxx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtfevclfkb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtuvapechc.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gtqwfqpzss.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtzhnrmwmy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtyxxxkant.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtmhkkvtzj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtiorhsgdk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtzzyhxkic.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsvganfc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtchetimqj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtddodcdyq.html

[B13] 判断是否为数字
来源：http://dali.birdmap.top/Article/details/gtlhhwukqi.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtwomxivzs.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtgtueaspd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tian-w.cn/Article/details/gtcaocblfr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtwyhemyol.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtjjlgkucr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtkqfnsxmd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigufen.top/Article/details/gtreybrcsl.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtjlybwgei.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofxzfsbt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gthofigeyx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gtobemneyx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gthgoolgzz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtvodclags.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtvqplexre.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gtkqmaahix.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gtpfuvekmg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtzglthuxr.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gtnzriflgo.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gtsnchjpjk.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gtpqbrnkuf.html

JS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtixbtewyg.html

TS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtsanjoevu.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtstghdqdf.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtaqglvlsl.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtwhhzczds.html

C#:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtctuxuojs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtbfqfkccu.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbejwnbn.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gtekhldyvq.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtxudviikk.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtvxhwtqlh.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtcwuddekj.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gtrzhjfobb.html

Ruby: return if data.nil?
来源：http://dali.jianghu66.top/Article/details/gtnulclowq.html

C#:   if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpzvikgz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttvxwuhih.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gtmjwuntnc.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnptphewn.html

[C01] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjdzojqi.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtjsqgvmlj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitfdxzvz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtvgujaejh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtihxiwjop.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtvbeydjjl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtxcjenvtj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gtbblzjipg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtzcakazab.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gtvuddfwti.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gtlxqggnkg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gtsdgmooto.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtpjpmifds.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtacbwrrbj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gtdjxyfzei.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtnxpmyper.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gtxkaeueab.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gtapwhmpjo.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtywqlfuqw.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gtqpeiaefj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gtpdmfkajq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gteqgxzwnb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpytoulx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtfiikqpve.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gthotolkzm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gtjebbsjyn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gtbfpvndhv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtpwytlazz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gtcdwzkwbe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gthuefyzho.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtddgtutdv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtcpvdfkrx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtgnygusrw.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gtmecnvwfl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtdonnqctl.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhynazbl.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gtbxojivmk.html


<!-- 参考信息 -->