代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlmporzb.html

[A15] 空值判断与默认值
来源：http://dali.sysykeji.top/Article/details/gt2utkbazej.html

Py:   value = data or "默认值"
来源：http://dali.xylfe.cn/Article/details/gt2ccwvibkp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqwmqpbh.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gt2dstxuazc.html

TS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gt2hayrpblo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.meibo888.top/Article/details/gt2tujckutc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.iojbl.cn/Article/details/gt2uhcwcqnn.html

Ruby: value = data || "默认值"
来源：http://dali.sysykeji.top/Article/details/gt2uphtjoso.html

C#:   var value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gt2qefalsjk.html

[A16] 真假值判断规则
来源：http://dali.gotoacloud.top/Article/details/gt2piwxrgza.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pycfn.com/Article/details/gt2owmfqeif.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jyoumei.cn/Article/details/gt2mtgncnha.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sufxvd.cn/Article/details/gt2vtgvyecj.html

TS:   if (!x) {}
来源：http://dali.hywenlv.cn/Article/details/gt2keupoyxy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xinyue.icu/Article/details/gt2tsytlmrl.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.gotoacloud.top/Article/details/gt2efxfjdml.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ehwqpu.com/Article/details/gt2zcbzzoie.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xziqi.cn/Article/details/gt2qoypdpcj.html

[A17] 位运算
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzcopmlo.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2dvpokqlk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2jfthcjdr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2tmfaguzo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gt2zfsrrjwk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gt2gbundwvn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2yeskqjcy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gt2vyjbebwd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gt2vrxkedoc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cashguo.top/Article/details/gt2ynzmnzuk.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgfzy.top/Article/details/gt2jpsrbzqg.html

PHP:  ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gt2eaotqxrs.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shangyingyoupin.top/Article/details/gt2obvxfsob.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tian-w.cn/Article/details/gt2kqgsgqsn.html

Java: (int) 'A'; (char) 65
来源：http://dali.hysaishi.cn/Article/details/gt2rhwezgpd.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.guannengcc.top/Article/details/gt2zvpkonpc.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhengqikj.top/Article/details/gt2qvksreiz.html

C#:   (int)'A'; (char)65
来源：http://dali.tian-w.cn/Article/details/gt2ylyddfpe.html

[A19] 交换两个变量
来源：http://dali.9152youxi.cn/Article/details/gt2yzqxjrzo.html

Py:   a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gt2rgcgrvfn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.daxiang520.top/Article/details/gt2qilxenam.html

JS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gt2gudvpitv.html

TS:   [a, b] = [b, a];
来源：http://dali.shangyingyoupin.top/Article/details/gt2jseaodre.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhixingplan.top/Article/details/gt2vvtcpkbe.html

Go:   a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gt2rcfikisd.html

Ruby: a, b = b, a
来源：http://dali.birdmap.top/Article/details/gt2xvyffhec.html

C#:   (a, b) = (b, a);
来源：http://dali.0kj1m.cn/Article/details/gt2iefwfaao.html

[A20] 读取标准输入
来源：http://dali.hnxiangtu.top/Article/details/gt2nbdthtmo.html

Py:   name = input("请输入：")
来源：http://dali.gotoacloud.top/Article/details/gt2ftuhbssb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ehwqpu.com/Article/details/gt2dytgmwsu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shuidangran.top/Article/details/gt2uikhoijc.html

TS:   // Node.js：readline 模块
来源：http://dali.hfpthk.cn/Article/details/gt2fktkweun.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhrlkbcu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhixingplan.top/Article/details/gt2syjuujeu.html

Ruby: gets.chomp
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyjszade.html

C#:   Console.ReadLine();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwfoxpgi.html

[A21] 保留指定小数位输出
来源：http://dali.ybcxt.top/Article/details/gt2exckdegy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hymyaxrk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2fcebcrkq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gt2nibimbvo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2dklnnkfa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gt2vdntvjqq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqkxhdt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gt2bzlmawto.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpbhjmvu.html

[A22] 获取字符串长度
来源：http://dali.ivvv.top/Article/details/gt2yxufsyts.html

Py:   len(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ypghxiwr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhixingplan.top/Article/details/gt2tzoawcbg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.svipenyu.cn/Article/details/gt2jojbsrhz.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gt2gufrwqgk.html

Java: s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2utqpezix.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.haohaochexian.top/Article/details/gt2hbrrkrpt.html

Ruby: s.length
来源：http://dali.guannengcc.top/Article/details/gt2tmuldpnf.html

C#:   s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2ktzappyt.html

[A23] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2uempcsmc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gt2esxqaish.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jianghu66.top/Article/details/gt2uabdrfee.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gt2ucberugq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gt2odftggcs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gt2xusivtvx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2abgxrgkv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenlongwang.top/Article/details/gt2ywfvmlac.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgfgrslr.html

[A24] 去除首尾空白
来源：http://dali.shzxlz.cn/Article/details/gt2gnzvyhcc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yzthcrqn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gt2azifclwh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gt2pcvtwhgu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gt2ewfshxfg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cucudq.cn/Article/details/gt2tourcbid.html

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gt2dkaitlvo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.dianchejie.cn/Article/details/gt2zskpxioz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ehwqpu.com/Article/details/gt2hcagvyma.html

[A25] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gt2kjjuwoqr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gt2boonsyew.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbcmjyzx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2ppabvlmz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2rcslzpmf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yueranfly.top/Article/details/gt2ruecytqr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2pmlflvcs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gt2ybeoxfcz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gt2bdfovciz.html

[A26] 类型转换总览
来源：http://dali.sufxvd.cn/Article/details/gt2zcvufjpv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.kuanghao11.cn/Article/details/gt2gkhykpmc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hfpthk.cn/Article/details/gt2weyenuxk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.redwolf501.top/Article/details/gt2copyzjjj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jyoumei.cn/Article/details/gt2bhdbjfjg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj202588.top/Article/details/gt2wznkbuqy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gt2hayqzjua.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cashguo.top/Article/details/gt2tvxsfucm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gt2xlsrguhu.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2utkvvncu.html

B. 流程控制
来源：http://dali.hnqzz.top/Article/details/gt2qmwypywy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tsfaewpd.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gt2eniwgqer.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gt2ntkuhsbr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2olxvcdbv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2nwrkgddq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2ofdtyamn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2pmpsysyu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgufenzy.top/Article/details/gt2arrdhgji.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2usltlhkg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gt2airecyjd.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258888.top/Article/details/gt2buwotsxk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daria6918.cn/Article/details/gt2uqftbbxc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.birdmap.top/Article/details/gt2xnegyyji.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gt2qiszvhye.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzfuowyv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdzspijc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ehwqpu.com/Article/details/gt2baubxbxw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jianghu66.top/Article/details/gt2jdexljfa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gt2prjaomul.html

[B03] switch / match / case
来源：http://dali.yj202588.top/Article/details/gt2umcfubew.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.c1oappe.top/Article/details/gt2rnljkpsq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2mqhenldd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gt2axgltcxz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gt2wemiisfe.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ukjtflca.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ppjwa.cn/Article/details/gt2ahxzyxeg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ehwqpu.com/Article/details/gt2xqqvdtmc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gt2yuuzyqub.html

[B04] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gt2wnslsocm.html

Py:   for i in range(10): print(i)
来源：http://dali.aizwys.cn/Article/details/gt2brxwiqin.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gt2srsvsjsn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gt2mbstaesl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gt2rzhtgkpq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj202588.top/Article/details/gt2dtuqchsp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tanke756.top/Article/details/gt2uuddombr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gt2opzdzbse.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.svipenyu.cn/Article/details/gt2lrpyferi.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gdvnrmxj.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gt2jwhqeumq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gt2cgpiexns.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gt2ltwzadib.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2anbicdmp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2isohyfyy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gt2mgviuogy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gt2ifitovik.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2msxdsoss.html

[B06] 遍历字典 / 对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqsorqca.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhongyouzk.top/Article/details/gt2kjnyenjb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yczpqfju.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ajuwaljc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gt2rrpshnel.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tianlin.xyz/Article/details/gt2kpsraphh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gt2jtrkkswk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvsklwjy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gt2mlqbbusz.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gt2ddhlqgsv.html

Py:   while i < 10: i += 1
来源：http://dali.tian-w.cn/Article/details/gt2dlkhxunp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fowapugr.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2igolefrg.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ypgixquw.html

Java: while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2havwmwrz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gt2kkzirmqq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhixingplan.top/Article/details/gt2cywggxow.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2zweaikuo.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gt2nshpukfp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgfzy.top/Article/details/gt2dqdjgyrv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2slwqohjg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2wicantnq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2qwitlxci.html

Java: do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gt2nvymarjw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gt2bqledcwb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jianghu66.top/Article/details/gt2mgmliudy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2zijdvayk.html

[B09] break 与 continue
来源：http://dali.iojbl.cn/Article/details/gt2hvlbdvdm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gt2psejrjqx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2uvfjlmbb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2divburoz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2zclcczvn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blrufbfo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.iojbl.cn/Article/details/gt2vkwrwhoj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gt2txfwnohd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2zkjofqit.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuxxlltv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gt2chvlzuqg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gt2sblxmezq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gt2huuzdrlv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gt2wxnytews.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gt2zqffgflf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yvedp.cn/Article/details/gt2dsnrtspc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sysykeji.top/Article/details/gt2jkvfeuiy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqtztqba.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gt2scehffxy.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npqfdolt.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gt2yzaurqnq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gt2iljpyiif.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gt2ovixnkiv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gt2kzctjses.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gt2cnehrbtd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gt2ptvlwsst.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptmmidqa.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xjwdvgwb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gt2kukugrvw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gt2webixzlg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcaqitlj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2nenrcshe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gt2zsalrsie.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gt2heethyxj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hfpthk.cn/Article/details/gt2emhephyg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gt2xedrkhje.html

[B13] 判断是否为数字
来源：http://dali.fengsongda.top/Article/details/gt2wuqygagn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gt2tnbaxfdt.html

PHP:  is_numeric($x)
来源：http://dali.hnqzz.top/Article/details/gt2kxalpyem.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gt2uhrwjhdh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gt2svoxsdik.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gt2yewcuwua.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gt2nlyuwiup.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fzhhl.top/Article/details/gt2sywycotb.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gt2jxeqwgvi.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gt2jtbaleci.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gt2wxdclshl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gaohongyu789.top/Article/details/gt2gkahodxg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2qrjzyjkx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gt2lqbpvdqo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2gvfdzbvp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gt2sfpbrkhu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gt2glekziti.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2vimzzgfg.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gt2lrjedwie.html

Py:   a and b or not c
来源：http://dali.yangfankeji.com/Article/details/gt2enecwajg.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gt2bytcmpte.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2ckruzpmo.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnlmkfdt.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2vlgqqvjb.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dqflbgbs.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2rltecezs.html

C#:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2kzllxblq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sysykeji.top/Article/details/gt2hlupznww.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gt2wanarecv.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gt2rfumfeva.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2bphdjjsa.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gt2codleygd.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gt2jefyacfc.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gt2rtwiyzez.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gt2urwrhvlh.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2grnsxzuy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2unwbsvec.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gt2utkrrbco.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2rkbvcrkt.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gt2pkvejbno.html

Py:   def add(a, b): return a + b
来源：http://dali.ydzc1.top/Article/details/gt2zphdxysb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2hvuobwof.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxjpzxzq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2vbqfaplw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2sdgkmjsy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2mwzwoyjj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gt2khaesowi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2ujnxxind.html

[C02] 默认参数
来源：http://dali.jlsjyb.cn/Article/details/gt2trrexety.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gt2shrrqjkn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xbcsnffu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gt2mpkdqcfr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2sgpiwcxs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gt2gqbydong.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gt2vjxfgwan.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gt2zyozbxwm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gt2sfvgwyvm.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gt2jxifjwhv.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lustbcdx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrcibhhd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2mdoorqwm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2cfgflqfe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtkwcmnf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gt2ntlpbbdl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gt2hhqgibol.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjuuhgfl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gt2lawfwfae.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gt2rcqlvjss.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gt2mxsfxppb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gt2yppgltnj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gt2lozopnmr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gt2gfbknzet.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2viecxwgz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2nhpdnkvq.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2jyrlmgmy.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gt2zkijwhwo.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gt2mqdyjguv.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgfopblh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2ppitxrjp.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2byfsomef.html


<!-- 参考信息 -->