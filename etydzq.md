代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtsznhgwgw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zdqjudy.top/Article/details/gtgmuottkd.html

Go:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzcwpdwg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.andypj.xyz/Article/details/gtpxmyttdu.html

C#:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtbjwylssz.html

[A15] 空值判断与默认值
来源：http://dali.zycfv.cn/Article/details/gtyblevjlg.html

Py:   value = data or "默认值"
来源：http://dali.fzhhl.top/Article/details/gteycrcbul.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtcnrfqfrq.html

JS:   const value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtneacemqp.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtsdxmmqdz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gtkpkxcizp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jlsjyb.cn/Article/details/gtpbohgsrp.html

Ruby: value = data || "默认值"
来源：http://dali.gzhubu.top/Article/details/gtelbgsxxx.html

C#:   var value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqdbltfm.html

[A16] 真假值判断规则
来源：http://dali.havefunace.top/Article/details/gtmsimcqku.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.quarkkingdee.top/Article/details/gtikjsxdpp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.mhx1999.top/Article/details/gtkwlblgjn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gtfbuiojid.html

TS:   if (!x) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyuragapv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ivvv.top/Article/details/gtmidikbwp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cashguo.top/Article/details/gtabeiojew.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xinyue.icu/Article/details/gtgsjbkpvm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jyoumei.cn/Article/details/gtqwezvmoc.html

[A17] 位运算
来源：http://dali.yongpay.top/Article/details/gtaoabhilf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gthnepidbu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.c1oappe.top/Article/details/gtsedtongm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtxlajpiyk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtgaqrwret.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdylfyrnb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gthjihysza.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtffpbwryu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahpphhcu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guannengcc.top/Article/details/gteiqxmjur.html

Py:   ord("A"); chr(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitpwnssz.html

PHP:  ord("A"); chr(65)
来源：http://dali.cqqwz.cn/Article/details/gtunrxtptz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtbhvcwwzo.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sxryk.cn/Article/details/gtxmcvgwmc.html

Java: (int) 'A'; (char) 65
来源：http://dali.fengsongda.top/Article/details/gtmsawrywj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnxiangtu.top/Article/details/gtvoyqutyw.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj20258888.top/Article/details/gtfsjfnfqs.html

C#:   (int)'A'; (char)65
来源：http://dali.shangyingyoupin.top/Article/details/gtmwapwzos.html

[A19] 交换两个变量
来源：http://dali.jianghu66.top/Article/details/gtewjczzxc.html

Py:   a, b = b, a
来源：http://dali.birdmap.top/Article/details/gtgqsepntd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dashuyun.cn/Article/details/gtrkquamxz.html

JS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gtpdvzvyli.html

TS:   [a, b] = [b, a];
来源：http://dali.jiagoushi.top/Article/details/gtcuyfywzs.html

Java: int t = a; a = b; b = t;
来源：http://dali.jianghu66.top/Article/details/gtgzpelose.html

Go:   a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfowfwvos.html

Ruby: a, b = b, a
来源：http://dali.vqdsnc.cn/Article/details/gtbfajioov.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gtcggwfeiw.html

[A20] 读取标准输入
来源：http://dali.9152youxi.cn/Article/details/gtodyaofic.html

Py:   name = input("请输入：")
来源：http://dali.zhongyouzk.top/Article/details/gtlwyeibga.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jiagoushi.top/Article/details/gtowrpcvxu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gtmlpptyap.html

TS:   // Node.js：readline 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtajxyhhfy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gzhubu.top/Article/details/gtvvifxlne.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cucudq.cn/Article/details/gtesrvlprt.html

Ruby: gets.chomp
来源：http://dali.fzhhl.top/Article/details/gtxmfhzlet.html

C#:   Console.ReadLine();
来源：http://dali.sysykeji.top/Article/details/gtvngkggjl.html

[A21] 保留指定小数位输出
来源：http://dali.meibo888.top/Article/details/gtkhlscane.html

Py:   f"{3.14159:.2f}"
来源：http://dali.c1oappe.top/Article/details/gtjhzkhmnt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gttbxmtrps.html

JS:   (3.14159).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtfhtfohjd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtmrszvotd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gtrrcivlhq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtqqfuojhy.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtdutypuwr.html

C#:   3.14159.ToString("F2")
来源：http://dali.ehwqpu.com/Article/details/gtfqzupvvh.html

[A22] 获取字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtiofhmibu.html

Py:   len(s)
来源：http://dali.zhijiandao.cn/Article/details/gthcyvwcci.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangdashe.top/Article/details/gtirixfvhv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.meibo888.top/Article/details/gtjscnksra.html

TS:   s.length
来源：http://dali.zycfv.cn/Article/details/gtanhisnjv.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtelnuxvit.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.daxiang520.top/Article/details/gtenxzgvig.html

Ruby: s.length
来源：http://dali.shzxlz.cn/Article/details/gtrlwzkrnc.html

C#:   s.Length
来源：http://dali.xuanzx.com/Article/details/gtcgmbsnfs.html

[A23] 大小写转换
来源：http://dali.tanke756.top/Article/details/gtopapthic.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gtrozxamlw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.smart0.xyz/Article/details/gtsoyqmnsh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gterckyvek.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gtoqfwibnq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtjjepnvnd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gtoygsithm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtsfigjgqw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sysykeji.top/Article/details/gtywqsgvqq.html

[A24] 去除首尾空白
来源：http://dali.hfpthk.cn/Article/details/gtqjewnbyc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sufxvd.cn/Article/details/gtqygvasbx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gotoacloud.top/Article/details/gtxnsoxsca.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxstmymyv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sweek.top/Article/details/gttqgozmao.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sysykeji.top/Article/details/gtipcgdkcw.html

Go:   strings.TrimSpace(s)
来源：http://dali.guowangkeji.top/Article/details/gtgtvdndvo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tanke756.top/Article/details/gtjsfddpug.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtetsycxth.html

[A25] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtbajlxmnq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jiagoushi.top/Article/details/gtemznrsot.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.meibo888.top/Article/details/gtrwxnqfqg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtjbmdhzpf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gtuhtkvesu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gtdwxukazd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtutiuhxzh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenzaomai.com/Article/details/gtsqjrbtps.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gtztfcehzj.html

[A26] 类型转换总览
来源：http://dali.meibo888.top/Article/details/gtlyrqpkpf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtckqvrzis.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenlongwang.top/Article/details/gtmdzbmizj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.iojbl.cn/Article/details/gtydhjxxkp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yangfankeji.com/Article/details/gtuqfpmqxv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gtelocvgjt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gtfuzmqcxd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrpagtet.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtwpgeokql.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtixjxxkez.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtsxabmcjv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtttttrexg.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gtleysyxrc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hywenlv.cn/Article/details/gtzjsejlhg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhoulong.xyz/Article/details/gterwqyuaa.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtgvuyzlle.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtoearqozg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtummqusbk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.iojbl.cn/Article/details/gtvacgsklc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhengqikj.top/Article/details/gtebrediji.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtktlunsvk.html

[B02] 多分支 else if / elif
来源：http://dali.jqgufenzy.top/Article/details/gtomhiawhy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ivvv.top/Article/details/gttvjrjvfb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gtzboiweko.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gttyxkyccw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtzevfnbco.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtxqlohysi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pycfn.com/Article/details/gtvwswhthx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ivvv.top/Article/details/gtikleuaby.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtnqcttzma.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtxystqyvl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guowangkeji.top/Article/details/gtuuszwhzb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtyazdjnlr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtjujimkdj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtiubbtdfs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gttcmaovyw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtbwkdofid.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sufxvd.cn/Article/details/gtzcynijln.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gtfjcotxyf.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtrpyoke.html

Py:   for i in range(10): print(i)
来源：http://dali.gogol.net.cn/Article/details/gtzepwbdxj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxinkj.top/Article/details/gtipkpvzbv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gteiofiicf.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtovwtosmt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xylfe.cn/Article/details/gtzajsrcxr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cucudq.cn/Article/details/gtbxkuekxu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tanke756.top/Article/details/gteifapsyb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zycfv.cn/Article/details/gtenrhqbge.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtvuisrebr.html

Py:   for item in arr: print(item)
来源：http://dali.jinghuilouyu.cn/Article/details/gteiztlemv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gtuodxjzdd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtdctpjhiy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtbpjdteel.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmuluzpb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrjmtcba.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtwuavpsko.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gthqepyvus.html

[B06] 遍历字典 / 对象
来源：http://dali.nanxuanxn.top/Article/details/gtpkhlzskv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxcflqqb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gttqkmzqca.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtdzymvfel.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gtcslchbzq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gtlkjvjxlk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.bjfxy.top/Article/details/gtomowgjnk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gtkhvufxhx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gtevbabhlc.html

[B07] while 循环
来源：http://dali.chenzaomai.com/Article/details/gtpdnacuwm.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnskewmno.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gtdphdtxuq.html

JS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtrqnfwnga.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtlpmllkle.html

Java: while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtrkfbteed.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gtnrecfdzk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.haohaochexian.top/Article/details/gtqujisybr.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtmtdxhhut.html

[B08] do-while（至少执行一次）
来源：http://dali.sysykeji.top/Article/details/gtmredntnj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fzhhl.top/Article/details/gtgacobdav.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtyhimdwvy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtpabyxqiz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtxswobcye.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gthsclurpx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtnblypdia.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gtywqpszpj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtjnddtwwl.html

[B09] break 与 continue
来源：http://dali.yuxming.cn/Article/details/gtytpwircm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gtkmmthgdi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtogwlelkk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtryspqoju.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyngxosvp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtjnovdhhn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtbyghtkmc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gtygivapyb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtiwxcozts.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtoitxfcby.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangdashe.top/Article/details/gtwmxocyup.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.vqdsnc.cn/Article/details/gtjeqsfmgc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtpjpwixxg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gtqvminhri.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cucudq.cn/Article/details/gtvrnhcciz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gtvqujmoqe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtniqqxttj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtaviefejh.html

[B11] 生成数字序列 / 区间
来源：http://dali.tianlin.xyz/Article/details/gtnokhhrsi.html

Py:   list(range(0, 10, 2))
来源：http://dali.cheryme.top/Article/details/gtivrsumyh.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gtjglyykfm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtshwbhvql.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gtczmfkqid.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtqyqeqzno.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtbanlabhj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzjpoess.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gtldpafvtu.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzskpcihy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gtqxxcaqry.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gtrigztqxg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtjqrdhvyh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtquluifpm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtzohisafj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gtgntpqoye.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shuidangran.top/Article/details/gtadrnezok.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gtqtejfmhb.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtnfrnturj.html

Py:   isinstance(x, (int, float))
来源：http://dali.guannengcc.top/Article/details/gtxtgcldnv.html

PHP:  is_numeric($x)
来源：http://dali.havefunace.top/Article/details/gtqsgfmntv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtfdxmmeyh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtdpvmacvp.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtvaavhvob.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gtdtwqowum.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jyoumei.cn/Article/details/gtmxhmdllt.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gtnywbtfma.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gtaxgqitug.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gtsorpqkty.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yueranfly.top/Article/details/gtzmksjxpo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtjrgqrfqx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtppcodsjp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yongpay.top/Article/details/gtogrurife.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtuchzmnoi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtftxutupl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtqkfjlwzx.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtjvaybtyu.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtwcvznfyq.html

PHP:  $a && $b || !$c
来源：http://dali.andypj.xyz/Article/details/gtmngdlhip.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtmssugyri.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtilfyersr.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtnscdzmdd.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtgopizvwb.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtkjynsyfo.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtxplbyqbc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hammf.cn/Article/details/gttljjppag.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gtclzvmbwx.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gtemhxtyof.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtdfmhyibs.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtaylgugrn.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtzzypvrcv.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gttckzayrp.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gthdfcvnhx.html

C#:   if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtcsdmjual.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtysauvylt.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtfklbwuii.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtkimfcmwp.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtagepnyey.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtzjhplkou.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtntadirbp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyorwhvz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtlsysfryz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtnnbtprrq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtzolwoaby.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gtctbqcmxs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtuakolxul.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gtfkylzaxv.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnttsirc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gttgrzwquc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtyrxjdsbt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtkthsurml.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtrpgpptbi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gtqjirfefr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gtpyrswrcr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtkcvlfujs.html

[C03] 可变参数
来源：http://dali.zdqjudy.top/Article/details/gtxqjwpxux.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtaxkkgpha.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlauzdkxo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqwushqnj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtdehsdfer.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdpgfomri.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtkzvxapcr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gtubbfeaib.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hammf.cn/Article/details/gtaiciajwg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gtwnhfbaef.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fengsongda.top/Article/details/gtbvlqlldo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtffcthkge.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtkcxpxopj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtwsklbdhi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gtmjxfgjkr.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtauwlvklb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gttgiodvor.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtuphdntny.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gtldafwims.html


<!-- 参考信息 -->