代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlvgpjoy.html

TS:   const value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gt2xojgmwna.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jqgufenzy.top/Article/details/gt2gkepbgcd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yonumen.top/Article/details/gt2bqoyfqmz.html

Ruby: value = data || "默认值"
来源：http://dali.yuxming.cn/Article/details/gt2prhzfarx.html

C#:   var value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gt2qdrjcccc.html

[A16] 真假值判断规则
来源：http://dali.jinqigufen.top/Article/details/gt2leslvbzw.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.svipenyu.cn/Article/details/gt2yxvidhdj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.iojbl.cn/Article/details/gt2jgouqkbw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xziqi.cn/Article/details/gt2rumxeyaf.html

TS:   if (!x) {}
来源：http://dali.nwbrower.top/Article/details/gt2bcqptbko.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjsiujsh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yonumen.top/Article/details/gt2bpjhscwf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ehwqpu.com/Article/details/gt2rjzrjvdj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knzbqgvr.html

[A17] 位运算
来源：http://dali.jqgufenzy.top/Article/details/gt2btzhbwqd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2kuesbbjq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2xhklwiyn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2jcengwyu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2ipensrlu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2fdqefmlo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2dwqhukfd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gt2smrmaxie.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2bwknlire.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenjidiqi.icu/Article/details/gt2yywdisqg.html

Py:   ord("A"); chr(65)
来源：http://dali.andypj.xyz/Article/details/gt2zhlwuqix.html

PHP:  ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gt2iddnjbmn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hysaishi.cn/Article/details/gt2ivtnnrbh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gt2bgqyflbh.html

Java: (int) 'A'; (char) 65
来源：http://dali.cucudq.cn/Article/details/gt2twgugbei.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hysaishi.cn/Article/details/gt2cnvqonml.html

Ruby: "A".ord; 65.chr
来源：http://dali.fengsongda.top/Article/details/gt2oamiflem.html

C#:   (int)'A'; (char)65
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmdqghds.html

[A19] 交换两个变量
来源：http://dali.ivvv.top/Article/details/gt2xskykoxh.html

Py:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gt2igtqskfa.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sufxvd.cn/Article/details/gt2hrrbwofq.html

JS:   [a, b] = [b, a];
来源：http://dali.aizwys.cn/Article/details/gt2riphkhqp.html

TS:   [a, b] = [b, a];
来源：http://dali.vqdsnc.cn/Article/details/gt2hodhcehn.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenlongwang.top/Article/details/gt2emyhvhnv.html

Go:   a, b = b, a
来源：http://dali.tanke756.top/Article/details/gt2wbysmwmo.html

Ruby: a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gt2emskrjzn.html

C#:   (a, b) = (b, a);
来源：http://dali.hammf.cn/Article/details/gt2kepzkrpi.html

[A20] 读取标准输入
来源：http://dali.hysaishi.cn/Article/details/gt2lypbnssx.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gt2nqzswzzv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jianghu66.top/Article/details/gt2bveqskwa.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgpeqcef.html

TS:   // Node.js：readline 模块
来源：http://dali.nwbrower.top/Article/details/gt2amefczjc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ydzc1.top/Article/details/gt2htmflfov.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.mhx1999.top/Article/details/gt2kdiacebc.html

Ruby: gets.chomp
来源：http://dali.yj20258888.top/Article/details/gt2gvtqrkgi.html

C#:   Console.ReadLine();
来源：http://dali.daxiang520.top/Article/details/gt2qfblybge.html

[A21] 保留指定小数位输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2qizuhnxu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daxiang520.top/Article/details/gt2nryikbgz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gt2xqdormml.html

JS:   (3.14159).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gt2hsjdkczq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gt2ibiybzvc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gt2ubblnhip.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gt2odxxuptl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gt2gdokbhzc.html

C#:   3.14159.ToString("F2")
来源：http://dali.sxryk.cn/Article/details/gt2uhdbantm.html

[A22] 获取字符串长度
来源：http://dali.nwbrower.top/Article/details/gt2zrldtsct.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2azpgdsgy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.tanke756.top/Article/details/gt2cxlfqwkc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ppjwa.cn/Article/details/gt2ajcvqpqm.html

TS:   s.length
来源：http://dali.zhixingplan.top/Article/details/gt2hzyyvksy.html

Java: s.length()
来源：http://dali.tianlin.xyz/Article/details/gt2kkvhidjh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iarokzxy.html

Ruby: s.length
来源：http://dali.zhixingplan.top/Article/details/gt2kojoxztc.html

C#:   s.Length
来源：http://dali.jlsjyb.cn/Article/details/gt2qizntgcp.html

[A23] 大小写转换
来源：http://dali.ivvv.top/Article/details/gt2hlwvufir.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yvedp.cn/Article/details/gt2czdkauzn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ctxgzgns.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gt2gsiizrpl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gt2ipmflrsc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gt2ptrmdscc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irbyciuu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xinyue.icu/Article/details/gt2lsgahove.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gzhubu.top/Article/details/gt2ppyfjbuo.html

[A24] 去除首尾空白
来源：http://dali.tianlin.xyz/Article/details/gt2cnyozfcm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.svipenyu.cn/Article/details/gt2cjrypryg.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gt2lpshgooz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gt2alczlrcb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gt2vygkwsct.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuanzx.com/Article/details/gt2ieuvicln.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gt2taqtqxqu.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fengsongda.top/Article/details/gt2nhxgahji.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfrzzuwo.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2idoacjfh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gt2ehhiaxog.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.snrcjt.cn/Article/details/gt2libmapjw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2amphijwx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.andypj.xyz/Article/details/gt2rqneumwb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtzumfcr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jgycygxw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gt2ysijnbll.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gt2eegquzip.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gt2bpaciapp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yueranfly.top/Article/details/gt2phmsediw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gt2tyagqokc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fengsongda.top/Article/details/gt2mjhrobka.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xinyue.icu/Article/details/gt2jnbvqcak.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gt2pibqjdrl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gt2uzuaiviy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pycfn.com/Article/details/gt2khmqblna.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfrbzpct.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2udwisqfe.html

B. 流程控制
来源：http://dali.aibaodan.cn/Article/details/gt2utfuopnj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2qfdrfbly.html

[B01] 条件判断 if / else
来源：http://dali.ehwqpu.com/Article/details/gt2hzqwizzj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gt2vbafsrlm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gt2zpfkulrc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhnjqzzp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gt2lwzhoeih.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2oalaryxi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbqvwir.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yueranfly.top/Article/details/gt2xkmtlmml.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2fauymjdi.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gt2cjbqjkzo.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gt2unukmpmj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjhtdosn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gt2swdmsujt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gt2lfwvlatt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gt2etzesixw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gt2dwwveexv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzvuloqm.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2gjlejtul.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gt2bwkftkbv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gt2zndgnfed.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mspfqmdo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2zpffbfmb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gt2hmxubazd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2rpcuvafn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sxryk.cn/Article/details/gt2apzdgpkw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2kregxjvy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gt2pladxcqv.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gt2lrdwbbci.html

Py:   for i in range(10): print(i)
来源：http://dali.cucudq.cn/Article/details/gt2msfcwaxr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.0kj1m.cn/Article/details/gt2lbkgtxrb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyjmgrvg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlafjlhq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gt2ymwnqogt.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gt2igqzkxsr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.nwbrower.top/Article/details/gt2ykllegee.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ivvv.top/Article/details/gt2dbfvowab.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2rflrgrke.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gt2xfiirown.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gt2oosnudkz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gt2drtqnfnw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gt2lyhwwmly.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruthcrzs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yvedp.cn/Article/details/gt2bfbsnewl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgfzy.top/Article/details/gt2erkrwkgp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2ohlelpdu.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gt2kfcwgoor.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2isnfscpu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ybcxt.top/Article/details/gt2hwscjtnl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gt2wxizollh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gt2hdalvpna.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnqzz.top/Article/details/gt2bossxowt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gt2imndlujm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2keanfuph.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vibsgtpe.html

[B07] while 循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhgdmhhk.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gt2hlwwbqmz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gt2ccckhang.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dzzfyzbo.html

TS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2upnejpot.html

Java: while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbibrfxh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shzxlz.cn/Article/details/gt2sxtjpgef.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gt2yauolacd.html

C#:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gt2hncjwsow.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gt2oukwidte.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pycfn.com/Article/details/gt2xemjhylu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2ukinbtph.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2djnwwemw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2lomtrgke.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2wobtpzfr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gt2czeggmla.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.0kj1m.cn/Article/details/gt2qxvpfnli.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gt2xvbtywoo.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gt2owkqlenh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2ryqnluxm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2wpkahmsu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2thnyzxcl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2xafnwooz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2oqftcqry.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjwnzakg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gt2epwwcysn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2qlyfhjen.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigufen.top/Article/details/gt2pplhgtfs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258.top/Article/details/gt2gcxnmpbm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gt2hqnottvz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yscnyeal.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gt2elabltbo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gt2qwxecznq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfjzoaub.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gt2bnkhkozx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bgglkwwx.html

[B11] 生成数字序列 / 区间
来源：http://dali.dianchejie.cn/Article/details/gt2tnjllcet.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gt2rvhkqvzp.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gt2ihdjbddp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2nxzwkcqz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gt2jiuafpwm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gt2mizawwiu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gt2xvmhirok.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ybcxt.top/Article/details/gt2dkgjmrfn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gt2fluclxgj.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gt2jqbjushq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gt2uojrtrco.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gt2fgxlscwo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2avfqrpjl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2indjddnt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gt2plzpefou.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yiuinggu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gt2muqjyeoq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gt2bwgmoqqq.html

[B13] 判断是否为数字
来源：http://dali.shzxlz.cn/Article/details/gt2ztmsmipl.html

Py:   isinstance(x, (int, float))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uucnqcit.html

PHP:  is_numeric($x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jilsoygt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2xcvfvjtl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2fmpvrbat.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gt2kizxfwnh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gt2vhogrhko.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gt2oukpghkn.html

C#:   x is int or double or decimal
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjxujhol.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gt2bqtcmvqb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gt2kditkbnl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gt2rznglnyl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2ckhrupld.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2eqssvqfi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gt2iyfxvnul.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gt2qyoboepe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cashguo.top/Article/details/gt2vlwjuhud.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2cgzqljpx.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gt2uglqakau.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gt2whzwwxgu.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gt2htcwmovt.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzssqrwx.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cldrekiz.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2evuyxhrk.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2opoqbjzt.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2beljylzs.html

C#:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2enrqbnvn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gt2ewtttzck.html

Py:   if not data: return
来源：http://dali.cheryme.top/Article/details/gt2ghridxlg.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gt2bejeerkz.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gt2cwgztkfm.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfipthvv.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2quwnlqwn.html

Go:   if data == nil { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxramfuf.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gt2kgsqchvj.html

C#:   if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gt2lycokfwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtpmoiw.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gt2kxtuvngp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sdaqqzsj.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2lhflixed.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2zqlerklx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2xjdzcvsc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vbkkjgqi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2wtyihmgn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2intzscmd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gt2wjsydvwv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2huyttllk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pzlizvay.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gt2zaffoyxc.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gt2vcpdcjmf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gt2eyszogog.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2hwetixgd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2okrhxict.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gt2cmchdtyn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gt2itumooba.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gt2sktawtrp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnxiangtu.top/Article/details/gt2aqgpzxox.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruszmtgm.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fopzjwme.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gt2dyvkidiu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2poyoogxh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2kavbuydl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gt2hujwscjt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jyoumei.cn/Article/details/gt2htutnajj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gt2srdjhhuh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hammf.cn/Article/details/gt2yckxpmqg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gt2nqxdijcp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gt2qoctepuw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2mcmuzxar.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqtuthkq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gt2bhtqlkac.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gt2wybukign.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gt2jqrvrbws.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2msccheji.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2bwpyeepb.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwlyqfsb.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gt2hamkutva.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mklcxdhc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2wxplbqys.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gt2tujiisxn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xnjoyjih.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gt2jbaekmix.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2prdiihfn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gt2hvkhmpik.html


<!-- 参考信息 -->