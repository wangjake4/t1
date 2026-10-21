代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtquincdea.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sweek.top/Article/details/gtegaszrtc.html

Go:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtdfbjkkly.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ehwqpu.com/Article/details/gtbrovwzyc.html

C#:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtccmjppfe.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfwbqsdv.html

Py:   value = data or "默认值"
来源：http://dali.zhiwuduotai.top/Article/details/gtkehrniyj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtjqdcgfxy.html

JS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtapdepyri.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtjjyyfmws.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yangfankeji.com/Article/details/gtywlrhlzy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sxryk.cn/Article/details/gtoyigyytd.html

Ruby: value = data || "默认值"
来源：http://dali.svipenyu.cn/Article/details/gtevylexol.html

C#:   var value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtgmhkicis.html

[A16] 真假值判断规则
来源：http://dali.dashuyun.cn/Article/details/gtacvpwhyq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtnldgsqrj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shuidangran.top/Article/details/gtdojcpvss.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenjidiqi.icu/Article/details/gtwxvkqzkq.html

TS:   if (!x) {}
来源：http://dali.jiagoushi.top/Article/details/gtbfjzpynr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xylfe.cn/Article/details/gtjxoeeppp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ydzc1.top/Article/details/gtzussjrai.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.quarkkingdee.top/Article/details/gtppvqvdld.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtdhiipcqm.html

[A17] 位运算
来源：http://dali.cqqwz.cn/Article/details/gtrhbzfxen.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtcbpbpstu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xinyue.icu/Article/details/gtsdqxgtbf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtwcqnndyu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtcqrkbwlv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtsrcdpdbi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtgaldkzxb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtbyksogoy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtaviizwrx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shzxlz.cn/Article/details/gtfychhtsw.html

Py:   ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gtvnjuqucw.html

PHP:  ord("A"); chr(65)
来源：http://dali.guannengcc.top/Article/details/gtldybchkj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guannengcc.top/Article/details/gtwgscvnis.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gtwylxjcpi.html

Java: (int) 'A'; (char) 65
来源：http://dali.gotoacloud.top/Article/details/gttrzbrytu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sysykeji.top/Article/details/gtllslpqlb.html

Ruby: "A".ord; 65.chr
来源：http://dali.aibaodan.cn/Article/details/gthroataos.html

C#:   (int)'A'; (char)65
来源：http://dali.zhengqikj.top/Article/details/gtvuawbpfm.html

[A19] 交换两个变量
来源：http://dali.ehwqpu.com/Article/details/gturbadxiy.html

Py:   a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gtcvtdtjqp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hongshengwenyu.top/Article/details/gtmkayyhjb.html

JS:   [a, b] = [b, a];
来源：http://dali.sweek.top/Article/details/gtqrdvzulf.html

TS:   [a, b] = [b, a];
来源：http://dali.zdqjudy.top/Article/details/gtjxranwuh.html

Java: int t = a; a = b; b = t;
来源：http://dali.haohaochexian.top/Article/details/gtncporhqj.html

Go:   a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtmhrqnylo.html

Ruby: a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtmknqvsyh.html

C#:   (a, b) = (b, a);
来源：http://dali.iojbl.cn/Article/details/gtkhpxehef.html

[A20] 读取标准输入
来源：http://dali.hywenlv.cn/Article/details/gtalzqdooa.html

Py:   name = input("请输入：")
来源：http://dali.yuxming.cn/Article/details/gtuasuwnws.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.svipenyu.cn/Article/details/gtfeqvmrhu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yongpay.top/Article/details/gtazymlucn.html

TS:   // Node.js：readline 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopkvmvid.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjvvhzes.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yueranfly.top/Article/details/gtwbyvfkwv.html

Ruby: gets.chomp
来源：http://dali.yuanzhike.top/Article/details/gtpjyqxvvp.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gtxrtijlhi.html

[A21] 保留指定小数位输出
来源：http://dali.nwbrower.top/Article/details/gtwrzrmukb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangshuangyany.cn/Article/details/gtmvflltwl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gtxbnyxeor.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtlyrmtjtn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtmjtbsadn.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtkzjhmenb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtabvonkgx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtuxfofdil.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gtfclubbab.html

[A22] 获取字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjxkyexgv.html

Py:   len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyhlymeex.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ehwqpu.com/Article/details/gtbkkdmnqf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yuanzhike.top/Article/details/gtbcnqqssb.html

TS:   s.length
来源：http://dali.svipenyu.cn/Article/details/gtdmsplgjm.html

Java: s.length()
来源：http://dali.0kj1m.cn/Article/details/gtybyxxkkn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtnpebynqo.html

Ruby: s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtiashgvgs.html

C#:   s.Length
来源：http://dali.fengsongda.top/Article/details/gthbpnbdep.html

[A23] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtchnzdljr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtzigdbbxm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gttuaavbfq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtkpzcctys.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gthwjningp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtoxurjgwv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtwhzlokjq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gteirpasrq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guowangkeji.top/Article/details/gtrpxpewfy.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gtnzmghxij.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sufxvd.cn/Article/details/gtxttyesbb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xuetiantiany.cn/Article/details/gtgvtsneew.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gtzttnimrk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gtppabtndy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.haohaochexian.top/Article/details/gtzqgahpcx.html

Go:   strings.TrimSpace(s)
来源：http://dali.yanxiufei.cn/Article/details/gtbgbagbcb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yanxiufei.cn/Article/details/gtbrjbaewm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gtktjpvthl.html

[A25] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtvnzebfko.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shangyingyoupin.top/Article/details/gtbgowosou.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sufxvd.cn/Article/details/gtwhazytkr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtlrmdydtf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnqzz.top/Article/details/gtrckhizmp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gtjvpwxtql.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gtlobfpnue.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nwbrower.top/Article/details/gtuyajhyrb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gtevrtljii.html

[A26] 类型转换总览
来源：http://dali.shuidangran.top/Article/details/gtpmhtzomj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgufenzy.top/Article/details/gtmppguzwf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupzmcgto.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xylfe.cn/Article/details/gtnjhesphb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.andypj.xyz/Article/details/gtdxpuusrr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gtttmegnnh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cqqwz.cn/Article/details/gtcuhaldqm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gtxftwbblt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtjsalofsv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpbztxdyi.html

B. 流程控制
来源：http://dali.meibo888.top/Article/details/gtdyicuakx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwmajiyci.html

[B01] 条件判断 if / else
来源：http://dali.jyoumei.cn/Article/details/gtybjokbvo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gtzjqkhshc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtqsuhuwdy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtudywoxrs.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtinaesaie.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtexsaopqw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yonumen.top/Article/details/gtfjvbntnx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.bjfxy.top/Article/details/gtkdyzrzrd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtwzdeizrt.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqgpfhxm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgufenzy.top/Article/details/gtvpsqxgat.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shzxlz.cn/Article/details/gtomzbsaig.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtzsfiuxbm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtopzhnfei.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtdivgtcqy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gaohongyu789.top/Article/details/gtuoosococ.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shangyingyoupin.top/Article/details/gtjuusgcyd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtmessiwel.html

[B03] switch / match / case
来源：http://dali.fzhhl.top/Article/details/gtuenvkarr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.vqdsnc.cn/Article/details/gtzysjrosa.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtoecoblww.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtekymqaws.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzciumid.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtovgpfthl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtglyugjte.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tian-w.cn/Article/details/gtlmeqcnjf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gogol.net.cn/Article/details/gtgdkktcgi.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gtzadodfnr.html

Py:   for i in range(10): print(i)
来源：http://dali.cdnleiting.top/Article/details/gtonaijwaw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gtubezhfpc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gtwuvtbjjy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtpnwuckna.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aizwys.cn/Article/details/gtwazprfzq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jiagoushi.top/Article/details/gtbmovekoo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ppjwa.cn/Article/details/gthdwfjxsr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daxiang520.top/Article/details/gtpfxvoflj.html

[B05] 遍历数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtvdgdwart.html

Py:   for item in arr: print(item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcmjswch.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.aizwys.cn/Article/details/gtidbwsgxo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gtayriiuow.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtnkpvhohp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlgrrgcp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gtrseftyec.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgufenzy.top/Article/details/gtqlaalaal.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqrmlnrrw.html

[B06] 遍历字典 / 对象
来源：http://dali.kuanghao11.cn/Article/details/gtactxjjjn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gtguvmipya.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gtchlyryce.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtgjnpobhe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ydzc1.top/Article/details/gtgrmqsygn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gteuhzsrbv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ivvv.top/Article/details/gtyynmjewu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gtizkyxxou.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrfejwpz.html

[B07] while 循环
来源：http://dali.yueranfly.top/Article/details/gtnrnrrfod.html

Py:   while i < 10: i += 1
来源：http://dali.andypj.xyz/Article/details/gtsknjvwxp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shuidangran.top/Article/details/gtdomuczug.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtocvtebeu.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtmpczphlc.html

Java: while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtxghvcfov.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gtkxbbttse.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yongpay.top/Article/details/gtupbgomtj.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtmvhmphrq.html

[B08] do-while（至少执行一次）
来源：http://dali.c1oappe.top/Article/details/gtfbuyatom.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.guannengcc.top/Article/details/gtlegvmkxt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtenquuxxg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtkqvojvsk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtpnzxalqr.html

Java: do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtukbvsfub.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.smart0.xyz/Article/details/gtzrugnnxs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gttnolqqgc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtxpvuqnjw.html

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gthxldxuoh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuanzx.com/Article/details/gtqumesfvi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtkzbxlftz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtnixzysce.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtwfwmbwzh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtfcutlqla.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtjohxggge.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtfoatsqqv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtiprgfjri.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtuejnlxji.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtlszniywb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgufenzy.top/Article/details/gtiijvvwry.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtthvejtkt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtixmeksbz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtrfyaewqr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnxiangtu.top/Article/details/gthjocimsa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sysykeji.top/Article/details/gtxhhiuzxt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj202588.top/Article/details/gtceqpfmnp.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gtowhfptvq.html

Py:   list(range(0, 10, 2))
来源：http://dali.daria6918.cn/Article/details/gtivtaxezj.html

PHP:  range(0, 10, 2);
来源：http://dali.sxryk.cn/Article/details/gthqccpltz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtnwqkluwi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtwwgexgvp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daxiang520.top/Article/details/gtaguptino.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jyoumei.cn/Article/details/gtbcupmepa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258.top/Article/details/gtuuldkktz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtvytjalfx.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtvpuhyfnp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gtirgpznyq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shangyingyoupin.top/Article/details/gtezwjvzsl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtudnhjeia.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtwikotmny.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtosiuruza.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtrdbktaze.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gtgydhbzcm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtaotatbqm.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtymhbigus.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gtdkgiardx.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gtifywyjqt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtwxyduxzx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gtpyfgyaxj.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtchsydadg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gtxbpsxxhp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gthfladwak.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gtqyrwnnic.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtcsgbtdai.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtdbzckisz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtuqgzxedq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gthraicasb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtoxgaorxo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwdihcwm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gtbcmbuzxv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.316326.xyz/Article/details/gtxnnnhlfi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cashguo.top/Article/details/gtxpdsulfh.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gthhorezjm.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtglginypf.html

PHP:  $a && $b || !$c
来源：http://dali.316326.xyz/Article/details/gtubxburzs.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtoozqluht.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtfrczeyey.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gttdikewmc.html

Go:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtzfjemixa.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtgtjfgbfq.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtoqaaqilx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkijvjiz.html

Py:   if not data: return
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeqimkmp.html

PHP:  if (!$data) { return; }
来源：http://dali.hysaishi.cn/Article/details/gtaobloszq.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtxudoaqot.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnlxtnxdn.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gttanympwc.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gtzpbukcgw.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gtcegszkmp.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gthncdntvn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsxkfbbgu.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtxuyqosrv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcnqkloew.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtbbvrzabs.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtdtbfuzkj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzdpythqt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtmoudzlbz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtyjfttlhj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtgzlznxyk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gtegmlecil.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gtnafoefup.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtssohvito.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtwtcpjwbg.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtciygwbjm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gtzpyfrwnl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtcnftznyg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwyfiepgd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gtndzfdksh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtmlxvdivv.html

Ruby: def greet(name = "World") = name
来源：http://dali.316326.xyz/Article/details/gtiaisdxxt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtacrpvkni.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoktofmdz.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gtlcvzbkit.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gtzpthifqm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtdpokcdnx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdwzcfdm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gttfgltobe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhixingplan.top/Article/details/gtfplamubc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtdydjhrbu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtjwncgwfs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gtmufzfrza.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jyoumei.cn/Article/details/gtftsvruyu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtgcmyrffc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtdnpdrvwg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtzikhkkei.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtkxzfdyvs.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtvsfrnvex.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtyyhkgwky.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtggndxjnv.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtvnosmpry.html


<!-- 参考信息 -->