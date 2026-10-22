代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gt2wikstjrk.html

TS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gt2mdhiqznc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydxwaupt.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.nanxinkj.top/Article/details/gt2pxvndszf.html

Ruby: value = data || "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gt2webgybcr.html

C#:   var value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gt2fwmwjrgh.html

[A16] 真假值判断规则
来源：http://dali.shzxlz.cn/Article/details/gt2hifitbjz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2duffpxlg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258.top/Article/details/gt2ehxszhpe.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tian-w.cn/Article/details/gt2ttzkbgmx.html

TS:   if (!x) {}
来源：http://dali.ivvv.top/Article/details/gt2gvhndxal.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wyshgikq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jotwdahk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.vqdsnc.cn/Article/details/gt2krkmrstt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tianlin.xyz/Article/details/gt2jofqbfgj.html

[A17] 位运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tuqtcvbq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2lyipvegy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2qmpzvgtz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2gdjynumm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2kcedljxd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2nrnhqlfu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2zobuihka.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2jabgytrc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2rqvsapax.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cheryme.top/Article/details/gt2tnbraprt.html

Py:   ord("A"); chr(65)
来源：http://dali.aibaodan.cn/Article/details/gt2xwflznmu.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhnemdip.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2zorwvxsc.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daxiang520.top/Article/details/gt2hcnmhvws.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigufen.top/Article/details/gt2jxncgzbe.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjmujfod.html

Ruby: "A".ord; 65.chr
来源：http://dali.snrcjt.cn/Article/details/gt2gaisvspd.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gt2ykqgdjoe.html

[A19] 交换两个变量
来源：http://dali.zhoulong.xyz/Article/details/gt2zqtfpzcu.html

Py:   a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gt2yhpzfjoy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.9152youxi.cn/Article/details/gt2vtymycvd.html

JS:   [a, b] = [b, a];
来源：http://dali.c1oappe.top/Article/details/gt2ednsefbb.html

TS:   [a, b] = [b, a];
来源：http://dali.c1oappe.top/Article/details/gt2ojyjvlul.html

Java: int t = a; a = b; b = t;
来源：http://dali.fengsongda.top/Article/details/gt2muhanqtg.html

Go:   a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gt2ssrstkbt.html

Ruby: a, b = b, a
来源：http://dali.yuanzhike.top/Article/details/gt2uqcoprry.html

C#:   (a, b) = (b, a);
来源：http://dali.jyoumei.cn/Article/details/gt2lexikkcc.html

[A20] 读取标准输入
来源：http://dali.sysykeji.top/Article/details/gt2vxxxfvrw.html

Py:   name = input("请输入：")
来源：http://dali.xuetiantiany.cn/Article/details/gt2frkyphqt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.iojbl.cn/Article/details/gt2tjanuyea.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shzxlz.cn/Article/details/gt2zifqsnnc.html

TS:   // Node.js：readline 模块
来源：http://dali.yuanzhike.top/Article/details/gt2xkkkqbpd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.mhx1999.top/Article/details/gt2tlumjorg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.redwolf501.top/Article/details/gt2diillpro.html

Ruby: gets.chomp
来源：http://dali.snrcjt.cn/Article/details/gt2oxomxkeo.html

C#:   Console.ReadLine();
来源：http://dali.iojbl.cn/Article/details/gt2ymlzehba.html

[A21] 保留指定小数位输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsldauq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxuanxn.top/Article/details/gt2duwasoru.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2nsmfyrhy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2gzhfetgf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2pxljndzj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gt2tutehdti.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zuvczqxk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gt2fidkibyy.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhongyouzk.top/Article/details/gt2fvrdzdmw.html

[A22] 获取字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2ywdqnrdf.html

Py:   len(s)
来源：http://dali.zdqjudy.top/Article/details/gt2xgdfmbic.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sweek.top/Article/details/gt2fnyhiqhi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhoulong.xyz/Article/details/gt2jvkmzdqi.html

TS:   s.length
来源：http://dali.zhengqikj.top/Article/details/gt2bmxaajnh.html

Java: s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2rebofbej.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sxryk.cn/Article/details/gt2honkprcf.html

Ruby: s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2adhxeusx.html

C#:   s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkqyhhzu.html

[A23] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2jzmkzbhp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shuidangran.top/Article/details/gt2yicvvhus.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sxryk.cn/Article/details/gt2wuxqnywy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgufenzy.top/Article/details/gt2whtamnov.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gt2crknzpyn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gt2winppsgd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.snrcjt.cn/Article/details/gt2qqtxqbfx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hywenlv.cn/Article/details/gt2lerlxelr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gt2maqhbbvr.html

[A24] 去除首尾空白
来源：http://dali.zhoulong.xyz/Article/details/gt2fjsauxui.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.svipenyu.cn/Article/details/gt2tebybohp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gt2cgurawbx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenlongwang.top/Article/details/gt2mutzhqkm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zdqjudy.top/Article/details/gt2yikhcgmc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.wangdashe.top/Article/details/gt2darsxfgu.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuanzhike.top/Article/details/gt2lgtzkqlg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.bjfxy.top/Article/details/gt2isitacrt.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aizwys.cn/Article/details/gt2zmjrjtcj.html

[A25] 字符串比较
来源：http://dali.fengsongda.top/Article/details/gt2jyfjjyuq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxinkj.top/Article/details/gt2cbdcgwpk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fzhhl.top/Article/details/gt2bjevsyzd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xziqi.cn/Article/details/gt2vzhqzsuq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gt2xbowncrj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.smart0.xyz/Article/details/gt2gsykzyln.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znpgdibj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gt2ztrflwpj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gt2coigvgql.html

[A26] 类型转换总览
来源：http://dali.tianlin.xyz/Article/details/gt2arhfvoho.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yueranfly.top/Article/details/gt2aasftnug.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.c1oappe.top/Article/details/gt2mvwsubln.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dashuyun.cn/Article/details/gt2dcfoiloo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhhlsjzk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gt2fmomovit.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.quarkkingdee.top/Article/details/gt2rijvdwmh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.c1oappe.top/Article/details/gt2tvlxzwka.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gt2hfwywkdi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2zaryzqrg.html

B. 流程控制
来源：http://dali.fengsongda.top/Article/details/gt2ntfgcefb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2yzluxkro.html

[B01] 条件判断 if / else
来源：http://dali.shzxlz.cn/Article/details/gt2plmvleel.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.meibo888.top/Article/details/gt2idxlbuco.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uagepnzf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2noygeqjq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2hhjssjev.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gt2ccfenydd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gt2evaapncl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kjlolwwp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gt2pvhkubfh.html

[B02] 多分支 else if / elif
来源：http://dali.daxiang520.top/Article/details/gt2sjavmdvt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jianghu66.top/Article/details/gt2taqywolu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gt2timxqdsw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gt2cecxldoj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2ksacevbf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2odzkhcwm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gt2oqamvhcm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yueranfly.top/Article/details/gt2rbihcqyw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntsvwsxg.html

[B03] switch / match / case
来源：http://dali.guowangkeji.top/Article/details/gt2kqlubpxs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgufenzy.top/Article/details/gt2cizlbing.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfvwbnxx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gt2atpdsjen.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2iewukzni.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnjysdzf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmgymebf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jiagoushi.top/Article/details/gt2fodauivc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gt2dtohpcjo.html

[B04] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gt2jvjwpwlc.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gt2dypxvtzn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zdqjudy.top/Article/details/gt2sdmskfto.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gt2wbrfxpyl.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gt2zedkvxzy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wtqpvjiz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgufenzy.top/Article/details/gt2sxsxywcp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sufxvd.cn/Article/details/gt2ngiwzvsa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pycfn.com/Article/details/gt2oppvfhgi.html

[B05] 遍历数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gt2xilffzzo.html

Py:   for item in arr: print(item)
来源：http://dali.yongpay.top/Article/details/gt2bfwlryrm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gt2yzapadjw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gt2kthiztfl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gt2srwqyxud.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2yuyllmje.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jianghu66.top/Article/details/gt2xchcvlfr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gaohongyu789.top/Article/details/gt2gisfoxur.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gt2ohrdutpw.html

[B06] 遍历字典 / 对象
来源：http://dali.316326.xyz/Article/details/gt2kskbiweb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gt2ysioknka.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ovsuioxn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2zndmcfyi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gt2vdzxsdom.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daria6918.cn/Article/details/gt2kzpvpfbe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gt2bwqnvgdx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhoulong.xyz/Article/details/gt2rxlukxrj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghttlzky.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gt2kuxvkmfi.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gt2ikywdpfj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fengsongda.top/Article/details/gt2fhupzwuz.html

JS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2yidubgrt.html

TS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2ncvtinfz.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2mayoxgtd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gt2rrjzrxqu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.meibo888.top/Article/details/gt2cmuiujrp.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2vwvpdtzz.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258888.top/Article/details/gt2dhbkywdt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gt2upfiqhxi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ivvv.top/Article/details/gt2xgoyetpi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcmexmaf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2huvafvya.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2yzipdqfa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yueranfly.top/Article/details/gt2idyernuc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gt2nwjnthwk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2ymfrvgqj.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dfguojod.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gt2sxexgudf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ybzauutg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kygoogas.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2wgfwlgcq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hgwbaicz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilpxofnw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gt2lfxtrlat.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2rihkxmny.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2ymjscbbq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258888.top/Article/details/gt2hlyvaann.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gt2uwxwbnpd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gt2lfbwxvwd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gt2frdrgogo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gt2oicqvjrs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gt2znkansez.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gt2cdhdmvsz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2uyumaglv.html

[B11] 生成数字序列 / 区间
来源：http://dali.feifeiyinyue.top/Article/details/gt2mywgbcxd.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pifrkwqf.html

PHP:  range(0, 10, 2);
来源：http://dali.0kj1m.cn/Article/details/gt2cjpzsvqi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gt2cyglfevb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gt2nhmglvds.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gt2eancbxvk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gt2lnfwzxbh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gt2kxzqesua.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2shyrvffy.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2arjpbpop.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gt2bpvjcjgw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnflkkqz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2rwuzgueb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phnpyokx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2yhaurdlu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gt2ysvresqu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aibaodan.cn/Article/details/gt2xkmevvvj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gt2ocveespf.html

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gt2zdfubmjq.html

Py:   isinstance(x, (int, float))
来源：http://dali.dashuyun.cn/Article/details/gt2myognaqo.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2voauypzz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2gpbzjqop.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2tlpdgmte.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gt2jshrxzjo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gotoacloud.top/Article/details/gt2bkraycix.html

Ruby: x.is_a?(Numeric)
来源：http://dali.9152youxi.cn/Article/details/gt2peqhftxm.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gt2dtlulmio.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gt2qijibwjw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ybcxt.top/Article/details/gt2eqixqcbn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpdvoqom.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2tirezdih.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnbfspso.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2hdewkiwf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2saiftvdn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2geuoucyu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2xfsnllyc.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gt2ldpxinfl.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gt2iugeercz.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdpqdlbn.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2mxittjci.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gt2nzuksqin.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2aizymwlo.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2pfpbnbdp.html

Ruby: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2cilaakgl.html

C#:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2mpjfxbga.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gt2wvtvgilf.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gt2phnfahur.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygjgrnyy.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uamgohzv.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gt2kdkgnshg.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gt2yqlklebq.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gt2ciafjjef.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gt2xjtdsxxe.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gt2fjfrokcn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ikrchegv.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gt2egefgoji.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ifacezta.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2aqaljmfk.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gt2zwfyiedk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hyhamnvd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyjpiork.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2zqgpcfro.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2baoysbtg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gt2qruwzcub.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gt2ycmxlxgg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2helwjvaq.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gt2qzvmmrpz.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2mnuzhwws.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzkfmmle.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2rxvptukv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2rzisbxgq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gt2cnteobmt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gt2lbkpyzsm.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypcfqbte.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnqzz.top/Article/details/gt2uczicacm.html

[C03] 可变参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkhdznog.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gt2lurkorsc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gt2gbqsjrht.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gt2pnlbledj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2lseizxjp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2xzrckdvb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gt2lsgkcukc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gt2yjerslyc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gt2japelryg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gt2lvcwezze.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gt2cxgyrpec.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxfvcoq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otqdvxmg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2fmqjirby.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.iojbl.cn/Article/details/gt2vvrqrign.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gt2xxxhhutb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2vqasanvv.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2lmwtmxvo.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gt2mdkqucjr.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gt2rznxudim.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gt2saxvpvdy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gt2sunxlcko.html

TS:   return { a, b };
来源：http://dali.havefunace.top/Article/details/gt2nmqxlcgg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gt2hkktnpai.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2brizohyp.html

Ruby: return a, b
来源：http://dali.yj20258.top/Article/details/gt2xtdpojio.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gt2tsyzxyfy.html


<!-- 参考信息 -->