代发 wailian999

[A14] 注释写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbfpjlsg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhongyouzk.top/Article/details/gt2fthdbjas.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2ddgdjqws.html

JS:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gt2deiivnjb.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gt2vlhixtay.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.vqdsnc.cn/Article/details/gt2amnapbqe.html

Go:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2rqpuzvbp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yanxiufei.cn/Article/details/gt2rrfgxgyz.html

C#:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gt2noxlfukk.html

[A15] 空值判断与默认值
来源：http://dali.zhixingplan.top/Article/details/gt2jpeuzrjs.html

Py:   value = data or "默认值"
来源：http://dali.chenzaomai.com/Article/details/gt2ifzhjfic.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gt2peqmnzai.html

JS:   const value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gt2fasmuijb.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkosuzxb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.birdmap.top/Article/details/gt2vrhzsvyu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xinyue.icu/Article/details/gt2efgzoikk.html

Ruby: value = data || "默认值"
来源：http://dali.mhx1999.top/Article/details/gt2orrsaztt.html

C#:   var value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gt2sgtxcazx.html

[A16] 真假值判断规则
来源：http://dali.zhongyouzk.top/Article/details/gt2pabnitjt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.dashuyun.cn/Article/details/gt2djmmrxny.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkovryn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jiagoushi.top/Article/details/gt2arlijddv.html

TS:   if (!x) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2erugvezd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hnqzz.top/Article/details/gt2snhziacx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.vqdsnc.cn/Article/details/gt2jnfiaxoc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hfpthk.cn/Article/details/gt2wkurfkib.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yonumen.top/Article/details/gt2xogsnhvi.html

[A17] 位运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opwbebog.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gt2qjxmspqd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2dhsqboiv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2lgvpglrv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gt2jioqxvnx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gt2gpjlxxeq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gt2wotcybdi.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2ruoxmnnu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsnxvbnm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwpvkgtt.html

Py:   ord("A"); chr(65)
来源：http://dali.guowangkeji.top/Article/details/gt2lxmbrhdu.html

PHP:  ord("A"); chr(65)
来源：http://dali.dashuyun.cn/Article/details/gt2ecxqxdud.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.kuanghao11.cn/Article/details/gt2nbjuiqrc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gt2bplmepzk.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigufen.top/Article/details/gt2ucxcksln.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.pycfn.com/Article/details/gt2erlexbxr.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhixingplan.top/Article/details/gt2mshqejpp.html

C#:   (int)'A'; (char)65
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jabcphtk.html

[A19] 交换两个变量
来源：http://dali.jlsjyb.cn/Article/details/gt2bstytmgg.html

Py:   a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gt2uxiuiavn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.haohaochexian.top/Article/details/gt2usbficru.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gt2orglxupi.html

TS:   [a, b] = [b, a];
来源：http://dali.yvedp.cn/Article/details/gt2cccmzamm.html

Java: int t = a; a = b; b = t;
来源：http://dali.aizwys.cn/Article/details/gt2azizhryz.html

Go:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gt2vpaygarj.html

Ruby: a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gt2lnppnfdt.html

C#:   (a, b) = (b, a);
来源：http://dali.redwolf501.top/Article/details/gt2tavesame.html

[A20] 读取标准输入
来源：http://dali.yvedp.cn/Article/details/gt2mfxalqpb.html

Py:   name = input("请输入：")
来源：http://dali.hysaishi.cn/Article/details/gt2aydcbxti.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.daria6918.cn/Article/details/gt2tkxbwnrg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.smart0.xyz/Article/details/gt2ptpkqjfq.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aanukedp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jianghu66.top/Article/details/gt2mmblokdk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.iojbl.cn/Article/details/gt2hxauoezj.html

Ruby: gets.chomp
来源：http://dali.pycfn.com/Article/details/gt2pytjxrjk.html

C#:   Console.ReadLine();
来源：http://dali.jiagoushi.top/Article/details/gt2aoimfycj.html

[A21] 保留指定小数位输出
来源：http://dali.cqqwz.cn/Article/details/gt2kzmburgs.html

Py:   f"{3.14159:.2f}"
来源：http://dali.snrcjt.cn/Article/details/gt2phaypcnb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gt2tkjcfjle.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2kpekkuiy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gt2jltzmxvo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gt2bubjyxme.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gt2ghaqlhku.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gt2nlxszrhg.html

C#:   3.14159.ToString("F2")
来源：http://dali.guannengcc.top/Article/details/gt2grhczwjm.html

[A22] 获取字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2esmtoyrv.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gt2yhatgulx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cdnleiting.top/Article/details/gt2wyhfbxmq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ppjwa.cn/Article/details/gt2cpcgnntt.html

TS:   s.length
来源：http://dali.tian-w.cn/Article/details/gt2rurkewzr.html

Java: s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2pglpvmqx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2egrrdpcf.html

Ruby: s.length
来源：http://dali.zhixingplan.top/Article/details/gt2cbgewxhz.html

C#:   s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2luuekdrh.html

[A23] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gt2bulnpvyu.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuofliay.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.smart0.xyz/Article/details/gt2kwrwxzce.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gt2xzizlwce.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gt2vxzgygop.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbovuppp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2zajhhdtk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2ixqbqufa.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shangyingyoupin.top/Article/details/gt2aqpiiedc.html

[A24] 去除首尾空白
来源：http://dali.ydzc1.top/Article/details/gt2tnybayux.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258.top/Article/details/gt2xnfarsmi.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yongpay.top/Article/details/gt2rcgrleqe.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hammf.cn/Article/details/gt2qysvhxhr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gt2sakzxfcc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gt2yltybgdr.html

Go:   strings.TrimSpace(s)
来源：http://dali.cucudq.cn/Article/details/gt2qylujmfj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinqigfzy.top/Article/details/gt2umzzkdlc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfhuabay.html

[A25] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2pyukgoon.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ehwqpu.com/Article/details/gt2pfoqqlil.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.pycfn.com/Article/details/gt2wkznadwk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gt2jyubyfrf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gt2gtdcgrqr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.mhx1999.top/Article/details/gt2ohixpiju.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gt2hufxhypq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.c1oappe.top/Article/details/gt2wmsvipbu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zdqjudy.top/Article/details/gt2tgrjiruo.html

[A26] 类型转换总览
来源：http://dali.shangyingyoupin.top/Article/details/gt2eslkajxd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xylfe.cn/Article/details/gt2ywxjjtfg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yongpay.top/Article/details/gt2msoxeecq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.havefunace.top/Article/details/gt2xwjwkpnd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhongyouzk.top/Article/details/gt2xrftiwgo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gt2hweqohjk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gt2hsgaezux.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zdqjudy.top/Article/details/gt2dpytwvdb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gijvogky.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2tethmtpd.html

B. 流程控制
来源：http://dali.jqgfzy.top/Article/details/gt2mibvikny.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rnwdjeaw.html

[B01] 条件判断 if / else
来源：http://dali.kuanghao11.cn/Article/details/gt2fqppmpwr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gt2aaezdcey.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2irpwgphg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhvdpnta.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gt2yilvvulz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gt2svquqpqy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zycfv.cn/Article/details/gt2ykdzokyl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258.top/Article/details/gt2tfmnjtkm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gt2znrervrd.html

[B02] 多分支 else if / elif
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sleycufu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xylfe.cn/Article/details/gt2zqjvmkgv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xziqi.cn/Article/details/gt2rvspbaff.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gt2sqkpxofk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2vwloofpe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gt2fvlgebjq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhongyouzk.top/Article/details/gt2umtxeqrh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gt2keneikdx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2aruksywk.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gt2vnjcwtqw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hammf.cn/Article/details/gt2narihjdh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gt2yyupsjgc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gt2focuhrpe.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cjkdnlwn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ryhpzese.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ivvv.top/Article/details/gt2nzlhurfm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dashuyun.cn/Article/details/gt2jyhztcrx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gt2kjndarsd.html

[B04] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gt2eadckdwx.html

Py:   for i in range(10): print(i)
来源：http://dali.zhengqikj.top/Article/details/gt2hiwhjpwb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sysykeji.top/Article/details/gt2axlhbhuj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yangfankeji.com/Article/details/gt2bbkaeuij.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gt2qyilebho.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yangfankeji.com/Article/details/gt2tcbxnced.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gt2oqjrcpwb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.svipenyu.cn/Article/details/gt2jufzqvyw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clgxdapc.html

[B05] 遍历数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gt2yrojqend.html

Py:   for item in arr: print(item)
来源：http://dali.snrcjt.cn/Article/details/gt2rthgtvlq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daria6918.cn/Article/details/gt2xrdtdppc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gt2djsiuava.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gt2mxbnqpku.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.iojbl.cn/Article/details/gt2hepqwryq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gt2fifhewuz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.smart0.xyz/Article/details/gt2zvthmxdb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gt2qleuhwup.html

[B06] 遍历字典 / 对象
来源：http://dali.ehwqpu.com/Article/details/gt2ywvtswni.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccistdgg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gt2pjhafazw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gt2tznqyhzc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gt2bvaqdisn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gt2qozjppvt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyiafmk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cashguo.top/Article/details/gt2cgkhscoo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzmlynau.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gt2peltwraq.html

Py:   while i < 10: i += 1
来源：http://dali.zdqjudy.top/Article/details/gt2urkbipmx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gt2etyoibrr.html

JS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2bjnttdsu.html

TS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2zhebrjxv.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2leilysdm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gt2nrpsxnpy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzrrksv.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gt2oagroocc.html

[B08] do-while（至少执行一次）
来源：http://dali.zhixingplan.top/Article/details/gt2acfcqlwf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gt2inhunvdj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2zketbetx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2ynpwuecr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2gvndczxb.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2smyjkcjg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fzhhl.top/Article/details/gt2xgsmwalp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekjvdoui.html

C#:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2emcukhia.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdmfqbsc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gt2whufbxer.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2aezsilap.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2agtpqkgx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2ruhydylf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2tbwjmbls.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kqrktihk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gt2rqgncgwg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2mwumerzf.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gt2rkoeqtni.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gt2vlyxgalx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gt2yetmixvt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gt2vfowlqhg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gt2fpmssfau.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzainaen.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gt2boixyahx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gt2ytrccthe.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.vqdsnc.cn/Article/details/gt2veimxigj.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gt2hvsscbtq.html

Py:   list(range(0, 10, 2))
来源：http://dali.daxiang520.top/Article/details/gt2qlcavxod.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vvqofdpu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2mpxnudup.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gt2llidkgzs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daria6918.cn/Article/details/gt2infcelft.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gt2rnqjcfwr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gt2ccmmnwjn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gt2nggaadtz.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2srgliint.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gt2ugsmdgek.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gt2zoohiydw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2ekoeubpk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2xnqpjxcn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2jyjvfxao.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gt2tsofbwxx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqmdwwrc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gt2thqlqkaw.html

[B13] 判断是否为数字
来源：http://dali.nanxinkj.top/Article/details/gt2lderkdwi.html

Py:   isinstance(x, (int, float))
来源：http://dali.jiagoushi.top/Article/details/gt2yiktapmj.html

PHP:  is_numeric($x)
来源：http://dali.ydzc1.top/Article/details/gt2desmqron.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gt2rggvosdi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gt2abmdjaxv.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gt2xyzhphpn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgufenzy.top/Article/details/gt2yztpaaws.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gt2tgjlqjrl.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plxqfpnn.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gt2aotsrqcj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqhkncfl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxqnmtxe.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gt2lcjntrvk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2fkcxzvwi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gt2ibrjisqt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2zjvkdvqy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gt2pbfzxioh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2euxjbfow.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gt2erdouekh.html

Py:   a and b or not c
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzjztvli.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gt2npesyqkh.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2vjjuzptq.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2xppvgjvd.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2wtbhkhve.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtfsgopk.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2gmnffxrh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2omvkofdg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gt2fqrgrpoz.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gt2cmmcjgvs.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gt2qewyqjks.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2vltnuduc.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gt2sljlzjtq.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gt2exwygpso.html

Go:   if data == nil { return }
来源：http://dali.jlsjyb.cn/Article/details/gt2bgrdyazx.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohisxscw.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gt2nwnbxzvk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2tzbstjsf.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gt2pqtxgbrf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvkfbhqr.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gt2gqrztssg.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gt2cuasprbj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2blgckfjo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2ghmxpjdi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2fohhtlis.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2gtnrrjlm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2hofmysxq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gt2swblwefv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwxuzblu.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gt2msxbzssc.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kwwkfvqm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gt2tvaxyjcr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2yybkgyqw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2jxanztum.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gt2zdtjpmvq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gt2myopocjz.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2vdftozht.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gt2ihdmygfg.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gt2ubjsikon.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gt2viaubfup.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gt2fhbrjyxy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2dwmwtuae.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gt2lcukjhoo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gt2qmykjsva.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yanxiufei.cn/Article/details/gt2wjfyjfly.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.smart0.xyz/Article/details/gt2fhvnylhb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gt2efnetojs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gt2aalfwiqd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gt2yobdmscy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gt2sjgesomh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2bvxradju.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gt2ezqiiqty.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gt2jnousngl.html


<!-- 参考信息 -->