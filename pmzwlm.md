代发 wailian999

[A14] 注释写法
来源：http://dali.haohaochexian.top/Article/details/gtdwvyktwq.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cdnleiting.top/Article/details/gtijnjdfls.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gtcedekhlc.html

JS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtmrdealpf.html

TS:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtgdosolkk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xuanzx.com/Article/details/gtggfuswoh.html

Go:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtshhkemwt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cqqwz.cn/Article/details/gtjzwcoqzg.html

C#:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gttanelcqb.html

[A15] 空值判断与默认值
来源：http://dali.zhongyouzk.top/Article/details/gtevogfjjd.html

Py:   value = data or "默认值"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteektugmh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtmonjebrj.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gtluelyysz.html

TS:   const value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gtguahzimy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xinyue.icu/Article/details/gtghwcilxw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yangfankeji.com/Article/details/gtpzbefobl.html

Ruby: value = data || "默认值"
来源：http://dali.meibo888.top/Article/details/gtumaxtoet.html

C#:   var value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gtudmisebf.html

[A16] 真假值判断规则
来源：http://dali.0kj1m.cn/Article/details/gtabcsusxl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnqzz.top/Article/details/gtlgyuxqrz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.guannengcc.top/Article/details/gthzihhhur.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sysykeji.top/Article/details/gtrrszawpg.html

TS:   if (!x) {}
来源：http://dali.0kj1m.cn/Article/details/gttwepctny.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cheryme.top/Article/details/gtzywfgobm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenjidiqi.icu/Article/details/gtjlswmzxd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnxiangtu.top/Article/details/gtplszkhmp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xinyue.icu/Article/details/gtqbogzqrf.html

[A17] 位运算
来源：http://dali.ehwqpu.com/Article/details/gtogpmjqbd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtijtoskpr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtppkpsomd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtyvqkiklq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtqgxbtjna.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtgdaaczmi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtjynbacay.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gttelefiao.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtskhubkdd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yueranfly.top/Article/details/gtqibmutli.html

Py:   ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gtslgxmkpc.html

PHP:  ord("A"); chr(65)
来源：http://dali.jqgfzy.top/Article/details/gtudcbhvcq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtolsejdni.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gtbtwtibne.html

Java: (int) 'A'; (char) 65
来源：http://dali.fzhhl.top/Article/details/gtmeupsstd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.meibo888.top/Article/details/gtbzpynayp.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhengqikj.top/Article/details/gtgczeottw.html

C#:   (int)'A'; (char)65
来源：http://dali.c1oappe.top/Article/details/gtyoypvuwb.html

[A19] 交换两个变量
来源：http://dali.9152youxi.cn/Article/details/gtsixwylgt.html

Py:   a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gtbxgbojaz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnxiangtu.top/Article/details/gtqnpicooi.html

JS:   [a, b] = [b, a];
来源：http://dali.iojbl.cn/Article/details/gtijpflpxh.html

TS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gthlvrjupx.html

Java: int t = a; a = b; b = t;
来源：http://dali.guowangkeji.top/Article/details/gtjvquntuc.html

Go:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtslmexxqh.html

Ruby: a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtfaivneyy.html

C#:   (a, b) = (b, a);
来源：http://dali.tanke756.top/Article/details/gtfmbvnhca.html

[A20] 读取标准输入
来源：http://dali.shzxlz.cn/Article/details/gtssjzlpvb.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gteefexnwj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.birdmap.top/Article/details/gtyvofyzlt.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenzaomai.com/Article/details/gtihqzunup.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigufen.top/Article/details/gtcbdnbozg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangdashe.top/Article/details/gtxnpahxdb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gogol.net.cn/Article/details/gttouppqnr.html

Ruby: gets.chomp
来源：http://dali.gogol.net.cn/Article/details/gtyccqmnig.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gtyuvrvjeu.html

[A21] 保留指定小数位输出
来源：http://dali.c1oappe.top/Article/details/gtemqbvkwb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.redwolf501.top/Article/details/gtcksemvuu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtellynnre.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtkcsvajlc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtbwgqybad.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtemprnsvz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtvffqopml.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtavfzifee.html

C#:   3.14159.ToString("F2")
来源：http://dali.xziqi.cn/Article/details/gtyoshgecd.html

[A22] 获取字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvqurrhy.html

Py:   len(s)
来源：http://dali.sufxvd.cn/Article/details/gtweiahwwp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daxiang520.top/Article/details/gtyqszmbyk.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shangyingyoupin.top/Article/details/gtizndzfki.html

TS:   s.length
来源：http://dali.hnxiangtu.top/Article/details/gtuqoofesw.html

Java: s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtziihbnqc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gtzevbawsh.html

Ruby: s.length
来源：http://dali.yuanzhike.top/Article/details/gtfyaxzifu.html

C#:   s.Length
来源：http://dali.ydzc1.top/Article/details/gtkquingis.html

[A23] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtbxfpjnel.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqjgakrj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pengpengdd.cyou/Article/details/gtcypgawsd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtavnicdnl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtwaaravrd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gtteislots.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.kuanghao11.cn/Article/details/gtavxnetlo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtbijzsfzq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.9152youxi.cn/Article/details/gtmyiakdxi.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gtzujqwydm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.bjfxy.top/Article/details/gteupnsocq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nwbrower.top/Article/details/gtsjfnqogy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtavuhsqco.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gtmexbaynh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258.top/Article/details/gtoxlokqyv.html

Go:   strings.TrimSpace(s)
来源：http://dali.dianchejie.cn/Article/details/gtctzyppka.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.316326.xyz/Article/details/gtaefevdik.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ivvv.top/Article/details/gtffoygboy.html

[A25] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtxdcbxlce.html

Py:   s1 == s2; s1 != s2
来源：http://dali.aizwys.cn/Article/details/gtmqflpucr.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtaxfwfgpv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cdnleiting.top/Article/details/gtjeeivgml.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtnypvuapw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxinkj.top/Article/details/gtclkbolzw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtrhujcpjr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hysaishi.cn/Article/details/gtofsjxlto.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtethgkrqw.html

[A26] 类型转换总览
来源：http://dali.0kj1m.cn/Article/details/gtnqscyvzb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gzhubu.top/Article/details/gtudrxjsfk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldjxtgrx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangdashe.top/Article/details/gtpzjaxske.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hysaishi.cn/Article/details/gtecpcofxv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gtdwmtbbsu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ydzc1.top/Article/details/gtfgnrcbrr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.0kj1m.cn/Article/details/gtmirudsdz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtjexuoodc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsdqujnpi.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gtwxdfrprq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttpihdksr.html

[B01] 条件判断 if / else
来源：http://dali.aizwys.cn/Article/details/gtlawyvjkj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.vqdsnc.cn/Article/details/gtdywdfvyb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgautleyd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtlcghqiyw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gttobewtbg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gthfyssnta.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tianlin.xyz/Article/details/gtoukimtgv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.svipenyu.cn/Article/details/gtexpgjnxn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzgjmtdx.html

[B02] 多分支 else if / elif
来源：http://dali.gzhubu.top/Article/details/gtgqqwstwg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.andypj.xyz/Article/details/gtygqvztek.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.0kj1m.cn/Article/details/gtjjozdpgz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtgjakuioq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtwzvawqai.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gttuigaltq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.redwolf501.top/Article/details/gtzjgmkovq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gthqszyyqt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtbfvhvvlq.html

[B03] switch / match / case
来源：http://dali.xylfe.cn/Article/details/gtfadelmhr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gtlygxmtnq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtdvoaozxs.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtlfhrtkbn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtebuddvrz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gteqoqgzdb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtgsnezolg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sufxvd.cn/Article/details/gtfzzljfpv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.dashuyun.cn/Article/details/gtxxivhzqh.html

[B04] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtkoavjnhc.html

Py:   for i in range(10): print(i)
来源：http://dali.gaohongyu789.top/Article/details/gtjsnueauc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.wangshuangyany.cn/Article/details/gttopfzaui.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtdgqhdbrr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtnpzmhvsc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gtlflohwbv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.bjfxy.top/Article/details/gtfzwpukbh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gogol.net.cn/Article/details/gtuytqixjf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shuidangran.top/Article/details/gtvlesmztv.html

[B05] 遍历数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtnjpdqdjp.html

Py:   for item in arr: print(item)
来源：http://dali.cqqwz.cn/Article/details/gtnchzyvsx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwkigner.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gttmwzrhnm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtxgmrhtft.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tian-w.cn/Article/details/gtmcyfevrr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258888.top/Article/details/gtljtjixhz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuxming.cn/Article/details/gtvpdpgpvn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258.top/Article/details/gtgmeyvvai.html

[B06] 遍历字典 / 对象
来源：http://dali.guannengcc.top/Article/details/gtetnsktcu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hywenlv.cn/Article/details/gtoquqlnry.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xziqi.cn/Article/details/gtjyehouxl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gtqqefmqac.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtrwqxmnrm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xziqi.cn/Article/details/gtkgcsocvk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gtatzoxnmg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnytuhofv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsztzgobr.html

[B07] while 循环
来源：http://dali.fengsongda.top/Article/details/gtfpietkwe.html

Py:   while i < 10: i += 1
来源：http://dali.guannengcc.top/Article/details/gtgxdmoaui.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgfzy.top/Article/details/gtgyeyiygf.html

JS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtiylydmyp.html

TS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtkefhdpin.html

Java: while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtsmgkllgo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gthvfuxjtr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gtielhwwyn.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtvajlhgdr.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gtgnjjgyte.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtknjxpiie.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gtcrnjxsiq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqrpwmwe.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtchrbmgso.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtwwmxbbfr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtvqauvfsg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gtkodqahlz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtndhvrevg.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gtzsnkxkrd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gtojoltflc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtyshuvxwo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtuvnrhutu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtxzjrqmmi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtobthmqlk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtwjjxxgem.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jyoumei.cn/Article/details/gtzoodfrwp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtsgnznkns.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gtfjyzopnp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xinyue.icu/Article/details/gtlevowvni.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gtihfhsmjr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gttjqzmlyo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gttyaernlw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gtkrrzvqqm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gtwvikltye.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gtnumxogko.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gtjxuhhfhv.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtjfnuwdfm.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gtgxkjzddg.html

PHP:  range(0, 10, 2);
来源：http://dali.dashuyun.cn/Article/details/gtbtxzpill.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtpzqejzzt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtqfhprync.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtkiqnpuxk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gttquivtdz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumsjidfj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gtmxfagtdd.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gtyddbdsvc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhengqikj.top/Article/details/gtbeftzizf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jlsjyb.cn/Article/details/gtfymkbbcs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtavgjzbnc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilroizdc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtzpdiwjrz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnqzz.top/Article/details/gtypucevyb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvlzbvpm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtzfymsihw.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gtvpgmottn.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtjmkuglsv.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtiyxfycfp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtmtzqznsp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtqpuqgdtn.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtxzplopic.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gtmfqnxrhh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gtyfnyvqre.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gtxgjzguxo.html

[B14] 判断值是否在集合内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrhcwvro.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dashuyun.cn/Article/details/gtfqtawgkm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gtprenwkuk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtbnraglwf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtqltancrw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj20258888.top/Article/details/gtgwbtaafz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtrwnbbnhn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gtcrywtigr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwkctmguq.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gttsqwpjvc.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gtvykqjdna.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gthapkwtol.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtmgsshhal.html

TS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtlaamjahd.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtryabpheh.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtlwigsbrz.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtwsidvrxs.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtzdklwhpn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gtvkeyuyfs.html

Py:   if not data: return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnogjsfqe.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gtpfcqcjyd.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtbggyorls.html

TS:   if (!data) return;
来源：http://dali.xinyue.icu/Article/details/gtwaeboeex.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtrnaztsmt.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gtdvgbuoli.html

Ruby: return if data.nil?
来源：http://dali.fengsongda.top/Article/details/gtvwozbgdh.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtbdbepcjy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcbpskbpl.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gtwzpexjjy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtrsiupuwp.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gtmjjjvmwj.html

Py:   def add(a, b): return a + b
来源：http://dali.xylfe.cn/Article/details/gtkepdkunh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtdnzpbmtt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtmqqujrvv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtsfnhrhup.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtajbvvfgf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gtfdakkdvu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gtnmkcmckf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtiypbbpzz.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtmxxymxjs.html

Py:   def greet(name="World"): return name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjsuwhvy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkivyyitj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtqggzlqsv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtmfznmfqx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gtqbrehjal.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtqtjferjj.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtkxxctgtw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtkqvzmokn.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtakhrpldt.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtetpibgwb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gtsadzfxfy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gteixesqvz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtjkigmdxg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gtaglbowcq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gtqywizlow.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtutkipyoa.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbbpmbzwy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yongpay.top/Article/details/gtswcfxoby.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gtoohjuelp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtoelurtvx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gthcbcdugk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtsuurwkwv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yangfankeji.com/Article/details/gtbkjzathd.html


<!-- 参考信息 -->