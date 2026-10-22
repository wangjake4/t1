代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xuanzx.com/Article/details/gt2vmmxvgwz.html

Ruby: "Hello, #{name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gt2udbrcdqh.html

C#:   $"Hello, {name}!"
来源：http://dali.pycfn.com/Article/details/gt2wphorpzx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dykmurqh.html

Py:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2uhbgcoxx.html

PHP:  "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2kqfgylrd.html

JS:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsvicgyn.html

TS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gt2gufhemnd.html

Java: "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2mrziskcj.html

Go:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gt2nzhnvyqd.html

Ruby: "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2fkiaknav.html

C#:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2wmvyklpq.html

[A14] 注释写法
来源：http://dali.tian-w.cn/Article/details/gt2myqrqxfw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cucudq.cn/Article/details/gt2itfvuele.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gt2ieeeidky.html

JS:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2miztssia.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2qjnhzxqn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhengqikj.top/Article/details/gt2rubtmvyl.html

Go:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gt2qyfkcwma.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gt2czagfjwt.html

C#:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gt2zudahsew.html

[A15] 空值判断与默认值
来源：http://dali.zycfv.cn/Article/details/gt2fqglkvcz.html

Py:   value = data or "默认值"
来源：http://dali.chenzaomai.com/Article/details/gt2qfnhabph.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gt2eonyytjh.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjcnpytf.html

TS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2sbjrckyd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.quarkkingdee.top/Article/details/gt2cdgeokma.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.c1oappe.top/Article/details/gt2addyntco.html

Ruby: value = data || "默认值"
来源：http://dali.fengsongda.top/Article/details/gt2frtakswx.html

C#:   var value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gt2udadprhn.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gt2mqoumaht.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sxryk.cn/Article/details/gt2meqmdhzh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cashguo.top/Article/details/gt2asmazhpb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.redwolf501.top/Article/details/gt2bdgfejug.html

TS:   if (!x) {}
来源：http://dali.c1oappe.top/Article/details/gt2xehrjtfs.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.9152youxi.cn/Article/details/gt2prqljryj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.vqdsnc.cn/Article/details/gt2stxuvwfx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sxryk.cn/Article/details/gt2hqjmrdte.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.guannengcc.top/Article/details/gt2yogfrbgg.html

[A17] 位运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bojktrdt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2qkvujdem.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2zudxbyaz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2zmzrlrcq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2vlowytgf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2slbguqqi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2mncujhdf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2tfyoiyyq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gt2gtirsnbr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sxryk.cn/Article/details/gt2uclestsu.html

Py:   ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gt2wbjnziug.html

PHP:  ord("A"); chr(65)
来源：http://dali.wangdashe.top/Article/details/gt2ubgkqtbc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gt2raiswcsk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gt2qpjrmmai.html

Java: (int) 'A'; (char) 65
来源：http://dali.guannengcc.top/Article/details/gt2txnizatd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258.top/Article/details/gt2lbaosjkj.html

Ruby: "A".ord; 65.chr
来源：http://dali.redwolf501.top/Article/details/gt2dgsqgadv.html

C#:   (int)'A'; (char)65
来源：http://dali.jinqigufen.top/Article/details/gt2yvypfiiq.html

[A19] 交换两个变量
来源：http://dali.zhongyouzk.top/Article/details/gt2ymjbyiqk.html

Py:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjmdcsgt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xziqi.cn/Article/details/gt2updprfiz.html

JS:   [a, b] = [b, a];
来源：http://dali.bjfxy.top/Article/details/gt2mkthiexi.html

TS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gt2pjcvsyao.html

Java: int t = a; a = b; b = t;
来源：http://dali.guannengcc.top/Article/details/gt2sudsncaa.html

Go:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gt2kyoqyutj.html

Ruby: a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gt2ufgsyrat.html

C#:   (a, b) = (b, a);
来源：http://dali.gotoacloud.top/Article/details/gt2gdutbwul.html

[A20] 读取标准输入
来源：http://dali.hfpthk.cn/Article/details/gt2jxamaeme.html

Py:   name = input("请输入：")
来源：http://dali.cucudq.cn/Article/details/gt2aiqhmvfy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhijiandao.cn/Article/details/gt2uivrhohm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqmdaxsa.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2igovjwro.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhongyouzk.top/Article/details/gt2zdabwmqm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgfzy.top/Article/details/gt2qzsftyat.html

Ruby: gets.chomp
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssvqelms.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gt2gekwwwyp.html

[A21] 保留指定小数位输出
来源：http://dali.ppjwa.cn/Article/details/gt2tfwjwsjt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jianghu66.top/Article/details/gt2sgsbqvbu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.meibo888.top/Article/details/gt2srpmhjjz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gt2chfrlbwz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssvzhcdf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gt2mzcfmacb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gt2nsmvzvbt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gt2tozvurbc.html

C#:   3.14159.ToString("F2")
来源：http://dali.nanxinkj.top/Article/details/gt2cngjblnt.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2apzoywfx.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gt2minxsbuv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yangfankeji.com/Article/details/gt2rpkolslj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cucudq.cn/Article/details/gt2qkejyqym.html

TS:   s.length
来源：http://dali.cdnleiting.top/Article/details/gt2xqzpcxmn.html

Java: s.length()
来源：http://dali.iojbl.cn/Article/details/gt2zvopefvh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2jjukaipc.html

Ruby: s.length
来源：http://dali.zhengqikj.top/Article/details/gt2stullpym.html

C#:   s.Length
来源：http://dali.havefunace.top/Article/details/gt2nfdrqhnn.html

[A23] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2lfhvweak.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cheryme.top/Article/details/gt2kshzjmty.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gt2phiegmch.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gt2gqsdvgiz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gt2jpyvosmc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gt2vdljoinr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gt2xiicnvkl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gt2kqrumoor.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqnnwyje.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gt2tdlydrhn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj202588.top/Article/details/gt2wksybirl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgufenzy.top/Article/details/gt2xqcrnvmr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gt2haaxrhnn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abvcwwsk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhixingplan.top/Article/details/gt2fvmaywqe.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2xcbcrwdv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bggrlooz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xinyue.icu/Article/details/gt2czkwfcne.html

[A25] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gt2ceyyndgc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dianchejie.cn/Article/details/gt2rchsyzcb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2yenlemyq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2spvkyqkk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gt2htpaimsk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sysykeji.top/Article/details/gt2bagcvxcc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gt2nltwmhjq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cdnleiting.top/Article/details/gt2sqaraxno.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eopemirc.html

[A26] 类型转换总览
来源：http://dali.xuetiantiany.cn/Article/details/gt2txlsbfgb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sweek.top/Article/details/gt2lsxpbwje.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.kuanghao11.cn/Article/details/gt2igsexdls.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuetiantiany.cn/Article/details/gt2blqaitzz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj202588.top/Article/details/gt2cjoxnpkl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gt2uzfeaoyz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.svipenyu.cn/Article/details/gt2rbqewwoc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.andypj.xyz/Article/details/gt2nrjvewhd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.meibo888.top/Article/details/gt2mhsoyzfn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ngosmqzc.html

B. 流程控制
来源：http://dali.quarkkingdee.top/Article/details/gt2zgirnwba.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2ottzzbcm.html

[B01] 条件判断 if / else
来源：http://dali.yj20258.top/Article/details/gt2egfhbpje.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cqqwz.cn/Article/details/gt2tysnbccq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkkokkmj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gt2keczjcfm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gt2ztkfbfrp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2feyvtrat.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nwbrower.top/Article/details/gt2gvhvcajs.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgnxqkag.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2oddunffn.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gt2mwyzlvpq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sxryk.cn/Article/details/gt2dwwgbijb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.andypj.xyz/Article/details/gt2jhyvdore.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2btzuxvnx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2toztbcfn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gt2ichbqhfs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.pycfn.com/Article/details/gt2gvoztdpi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hammf.cn/Article/details/gt2nnebsfab.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2lcxeyrbo.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzjjkrqq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihnvzcef.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dashuyun.cn/Article/details/gt2pdogikbi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gt2vrbmatlo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xzoducmi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2fhjicizb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gt2ppbmfjde.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gt2gkawvkky.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ivvv.top/Article/details/gt2dhxjgacl.html

[B04] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gt2dvopkxvh.html

Py:   for i in range(10): print(i)
来源：http://dali.svipenyu.cn/Article/details/gt2rjappdfi.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vymjmhhb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gt2lfjkhecp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gt2ryapjsxj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gt2jgrhnpkj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fzhhl.top/Article/details/gt2bofkivou.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gt2svxruaei.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cheryme.top/Article/details/gt2wdsgejmc.html

[B05] 遍历数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gt2ichbxzmq.html

Py:   for item in arr: print(item)
来源：http://dali.jqgufenzy.top/Article/details/gt2tgujuxbk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xmnzocpf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gt2pantldtb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gt2tomktady.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2eoaymcrv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tianlin.xyz/Article/details/gt2zwsbjogf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gt2nawucrko.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gt2oohejfwu.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gt2wmsdkqhr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.quarkkingdee.top/Article/details/gt2ioplvwsi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.redwolf501.top/Article/details/gt2tclyxxkw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gt2lnumfyuc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gt2mvshrzim.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gt2wunbddml.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenlongwang.top/Article/details/gt2mgpvayrt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gt2kjymqspt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qywvmgfu.html

[B07] while 循环
来源：http://dali.sufxvd.cn/Article/details/gt2oukfpdxg.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gt2iyfgttin.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.andypj.xyz/Article/details/gt2srseebff.html

JS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gt2whcaaubu.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2egqkxtab.html

Java: while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2vylynyvl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxinkj.top/Article/details/gt2qaoeqivs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgpfbpfu.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dxhklgsd.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gt2herorsyy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aarifiwr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2wuxfgssj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2heaiieyl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2pbskfpsi.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gt2onmriiuu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyveeioa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gt2fjnhlsvz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gt2zhpdrtvu.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gt2cznkkbpm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gt2ljqguclh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2bujedgpu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnylffxl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2guazvdvj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2jngqquaw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gt2zspcnsub.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gt2vdffgtmt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2rdswujcf.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gt2pvevskgg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gt2vxvxdluu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.redwolf501.top/Article/details/gt2egbhfwaf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gt2maxfxhst.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2rcobcizu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ujgczach.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kccelnea.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gt2lsgfskkm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yongpay.top/Article/details/gt2yqxvqqsd.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gt2motmfpaa.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gt2derlslhr.html

PHP:  range(0, 10, 2);
来源：http://dali.fzhhl.top/Article/details/gt2weeyyzpl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gt2eywanqlw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gt2gdiffyze.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gt2wkdsgqeq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gt2zvlqtjrh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgcbasxk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gt2ffhjxryg.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gt2ivwxwxet.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gt2ewweangn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2efufmhxp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2auskwfzt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eujssoci.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2tugohttn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gt2jkcrtwrh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gt2oxluiqmi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.kuanghao11.cn/Article/details/gt2ybkrzden.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gt2rlgsnyaf.html

Py:   isinstance(x, (int, float))
来源：http://dali.ydzc1.top/Article/details/gt2ihucwhzm.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gt2wzivkscr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gt2tmwapkxl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpiujeks.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gt2fgojntpc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gt2ddltriwe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yffllgsj.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gt2fnexupyq.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gt2ibzkdred.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gt2cbwmmlxt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gt2vzbtrxsy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gt2kiqjiiqn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2ukpgnpaq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gt2cippbihd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gt2hifuxvoz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gt2ujrjiggm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2btvthlbq.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gt2kfvpbzhf.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gt2vidxmysp.html

PHP:  $a && $b || !$c
来源：http://dali.mhx1999.top/Article/details/gt2qxwfrire.html

JS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eykjorie.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2grihherd.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2wrhvtecw.html

Go:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2lfymmdga.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2nrpvjavs.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2buczrezk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwnceubn.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gt2klkawspl.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gt2zpysvdbe.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ppwvhfms.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2qvrzlbju.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gt2wnldjlaz.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gt2lxidiqga.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gt2oioltytc.html

C#:   if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gt2hmdypbik.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2nbfhogur.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gt2waidrapz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2kcdlpsql.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2fihxdkqz.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gt2rzsztnqh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2horrqorq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2fpidgwmn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2rhctynxv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2inuvevfa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2hkxmbfsb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gt2nuvkfiar.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nwfvkodm.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gt2gvqzaulp.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gt2toprsthy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gt2srpouhwp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rzfqrdhe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2rulhyipt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gt2wavahrvi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gt2ovyzalph.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gt2amaphjzi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gt2khxnalfx.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gt2lwltddal.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qmvuwmic.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqxokwvx.html


<!-- 参考信息 -->