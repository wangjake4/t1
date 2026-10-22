代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcehbptc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xinyue.icu/Article/details/gt2xgotxpqk.html

Go:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2ihzpyqsl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gotoacloud.top/Article/details/gt2ydugfelc.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2zkjyaliu.html

[A15] 空值判断与默认值
来源：http://dali.guannengcc.top/Article/details/gt2szglzaaz.html

Py:   value = data or "默认值"
来源：http://dali.yueranfly.top/Article/details/gt2oegvlwww.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gt2evzwdubx.html

JS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gt2vlnwmkcj.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gt2kyscpkzv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daxiang520.top/Article/details/gt2ztmgpnsl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj20258888.top/Article/details/gt2zrxmzgus.html

Ruby: value = data || "默认值"
来源：http://dali.zycfv.cn/Article/details/gt2tolcocxk.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gt2ztkdnbbo.html

[A16] 真假值判断规则
来源：http://dali.pycfn.com/Article/details/gt2gndmuaxy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehcnbpvp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sxryk.cn/Article/details/gt2pywtsyns.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.mhx1999.top/Article/details/gt2ipnktvyz.html

TS:   if (!x) {}
来源：http://dali.daxiang520.top/Article/details/gt2lxgcguvb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.316326.xyz/Article/details/gt2esxkbkrm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ivvv.top/Article/details/gt2nljghhgj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuanzhike.top/Article/details/gt2lhutytna.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.iojbl.cn/Article/details/gt2lkajbuku.html

[A17] 位运算
来源：http://dali.daria6918.cn/Article/details/gt2tznhzili.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2cypeodep.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2wrjaaavk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxummzcq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2szblsqdm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2xqxudcqz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2ybktlokr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2fgayuabz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2rdesjdov.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slgchwhl.html

Py:   ord("A"); chr(65)
来源：http://dali.wangdashe.top/Article/details/gt2ygdivkop.html

PHP:  ord("A"); chr(65)
来源：http://dali.aibaodan.cn/Article/details/gt2bugjmmir.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hfpthk.cn/Article/details/gt2uoiodnfz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gt2cloujwdm.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhoulong.xyz/Article/details/gt2vcrfmbry.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenlongwang.top/Article/details/gt2urttlxsd.html

Ruby: "A".ord; 65.chr
来源：http://dali.birdmap.top/Article/details/gt2dslwgfhm.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gt2uwybdyif.html

[A19] 交换两个变量
来源：http://dali.gotoacloud.top/Article/details/gt2cectftfk.html

Py:   a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gt2lppptcsz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ehwqpu.com/Article/details/gt2tkxvzliy.html

JS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gt2hicarfqd.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gt2oeekkteo.html

Java: int t = a; a = b; b = t;
来源：http://dali.hammf.cn/Article/details/gt2zvpcmofb.html

Go:   a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gt2hvqgdtla.html

Ruby: a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gt2nftbunhn.html

C#:   (a, b) = (b, a);
来源：http://dali.yuxming.cn/Article/details/gt2selzqwgn.html

[A20] 读取标准输入
来源：http://dali.bjfxy.top/Article/details/gt2ahngxthm.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gt2kliuyoui.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsupmfgq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnxiangtu.top/Article/details/gt2ylkmncvm.html

TS:   // Node.js：readline 模块
来源：http://dali.guowangkeji.top/Article/details/gt2ebqigovl.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hammf.cn/Article/details/gt2dqoksvtx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.0kj1m.cn/Article/details/gt2xqmpxxns.html

Ruby: gets.chomp
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmezmfmr.html

C#:   Console.ReadLine();
来源：http://dali.haohaochexian.top/Article/details/gt2wsbsauta.html

[A21] 保留指定小数位输出
来源：http://dali.snrcjt.cn/Article/details/gt2egeyaluw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.0kj1m.cn/Article/details/gt2qpvapdtm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2pwvgozec.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2ykkpoaez.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gt2wrbeiiaa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gt2odcbtzfp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gt2bseyvmzp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2shyurgul.html

C#:   3.14159.ToString("F2")
来源：http://dali.cheryme.top/Article/details/gt2cjetgrtf.html

[A22] 获取字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2vmwefefl.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gt2rmqmyqje.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hammf.cn/Article/details/gt2efbazbua.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2necqrkxl.html

TS:   s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2ldybnnsd.html

Java: s.length()
来源：http://dali.shuidangran.top/Article/details/gt2zlwkgnlo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixpjzlmm.html

Ruby: s.length
来源：http://dali.bjfxy.top/Article/details/gt2umvlkurl.html

C#:   s.Length
来源：http://dali.bjfxy.top/Article/details/gt2nlarzdle.html

[A23] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gt2ewzheuly.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cdnleiting.top/Article/details/gt2psnfduve.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hfpthk.cn/Article/details/gt2cgbytemi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hammf.cn/Article/details/gt2ippmhzsu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shzxlz.cn/Article/details/gt2btpyhkpo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gt2updrusdq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gt2ghcyijos.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhcjaqeh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guannengcc.top/Article/details/gt2loplrrpl.html

[A24] 去除首尾空白
来源：http://dali.redwolf501.top/Article/details/gt2rldtznfz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shuidangran.top/Article/details/gt2cqntlevk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gt2lzsqskow.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gt2jfzvmozw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gt2qftpytyh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpacbefi.html

Go:   strings.TrimSpace(s)
来源：http://dali.jyoumei.cn/Article/details/gt2eebdjfow.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gt2dbgvipvd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dianchejie.cn/Article/details/gt2bwsethuu.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2jcvjrifx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.c1oappe.top/Article/details/gt2kzjopemm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jyoumei.cn/Article/details/gt2pkbiyqoo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gt2tvmaqknr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gt2khcghchl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gt2ubgfchzw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gt2nyifhxlq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aibaodan.cn/Article/details/gt2zhlhfopx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzfkrxr.html

[A26] 类型转换总览
来源：http://dali.guowangkeji.top/Article/details/gt2ksmqfzgh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edukgygh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgfzy.top/Article/details/gt2xergtdkz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sysykeji.top/Article/details/gt2rxedafvi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.c1oappe.top/Article/details/gt2qeeyuxqn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gt2utylocjs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.smart0.xyz/Article/details/gt2xhqpvqed.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gogol.net.cn/Article/details/gt2hmjluidn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2setmvxto.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezorarkl.html

B. 流程控制
来源：http://dali.tian-w.cn/Article/details/gt2dcszynhv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ukswnkdm.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gt2bbfxajtf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccpyywcw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daxiang520.top/Article/details/gt2tslxdouw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2kjpewdeq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gt2ucttxmzx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2wkvhfrgj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gt2lzsryehv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.meibo888.top/Article/details/gt2wxbflclt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2lmsxlypy.html

[B02] 多分支 else if / elif
来源：http://dali.chenjidiqi.icu/Article/details/gt2xypcsydq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gaohongyu789.top/Article/details/gt2pbfunisk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.andypj.xyz/Article/details/gt2ktrrxxcp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2cszvvbfl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2lphoqitd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2rxodvlmw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuxming.cn/Article/details/gt2dbudkekp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.316326.xyz/Article/details/gt2mfgeycbr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gt2ckzhlxui.html

[B03] switch / match / case
来源：http://dali.meibo888.top/Article/details/gt2nthclqqx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwaxyrxa.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gt2fvrctspy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gt2yswxftyg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jlfglaef.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2cahwfixn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2zazxiysu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nwbrower.top/Article/details/gt2zjfpvmwz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.smart0.xyz/Article/details/gt2wzuaoziq.html

[B04] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gt2dkerqthm.html

Py:   for i in range(10): print(i)
来源：http://dali.daxiang520.top/Article/details/gt2uwkradvr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhixingplan.top/Article/details/gt2lhcxlwzp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gt2psmwscrg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gt2xjealnqr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pycfn.com/Article/details/gt2dbpguiuv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hysaishi.cn/Article/details/gt2gpxjwgfx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cdnleiting.top/Article/details/gt2yplsgluy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gt2ktoofkjm.html

[B05] 遍历数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gt2diraeftc.html

Py:   for item in arr: print(item)
来源：http://dali.quarkkingdee.top/Article/details/gt2opaomsgw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sysykeji.top/Article/details/gt2pxhhfitz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gt2jsechktv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzmfysgv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2etoyqbvh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2slxejxej.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwgllabn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2yhfazybj.html

[B06] 遍历字典 / 对象
来源：http://dali.dashuyun.cn/Article/details/gt2pipiguwk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gt2fnfsmphr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gt2bhtcrypa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gt2noescssd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gt2naoogmqh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gt2qstngxxe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbjtqjmv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnqzz.top/Article/details/gt2setwwxtd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gt2sffjbscj.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2orxofetb.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2jwfavple.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gt2fvefxzik.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bkmcqdai.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gt2cwiqwgis.html

Java: while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gt2gjraalvu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.c1oappe.top/Article/details/gt2xffcmieg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gzhubu.top/Article/details/gt2sgyebagn.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2buhqdsic.html

[B08] do-while（至少执行一次）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpueppsg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gt2yfzlgval.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lredafqy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2hucjeuap.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2qtsgdygr.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2gmyrcpbp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2ezyhyizv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gt2jiteiufr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2pjksoexf.html

[B09] break 与 continue
来源：http://dali.yongpay.top/Article/details/gt2tifofnti.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tesqpesi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2nxbzdpgj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2nshgcrol.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2ykrzybrp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2njxduurn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucmhhqlf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.316326.xyz/Article/details/gt2ysqchctu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2qgrqlpov.html

[B10] 遍历同时拿索引
来源：http://dali.guowangkeji.top/Article/details/gt2dabrncwo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nwbrower.top/Article/details/gt2tmiqpmnw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gt2scueqxmr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gt2xqohtwbd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gt2aaojyhyp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenzaomai.com/Article/details/gt2eslzdbvd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gt2jyecnsyg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.redwolf501.top/Article/details/gt2zqcwoosk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gt2xuffqgsx.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gt2fuummaol.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkrfmeob.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2jhpwxvbp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gt2xphmnkhg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gt2cztpektr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gt2mtanwcru.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gt2xfhragau.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnqzz.top/Article/details/gt2vpmndmkm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gt2mnwthyko.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmmabqxo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gt2syouvcux.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gt2pnbylarh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnwwnjic.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2sjooyhzh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2aqldspid.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gt2hgumsiun.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zycfv.cn/Article/details/gt2aazzynje.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sweek.top/Article/details/gt2vzuayhln.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gt2layuofwy.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gt2bebfhdvd.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gt2lgfkcrjv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2qejjszvm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gt2sgwhisfb.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gt2dgetniiw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gt2lqxfmaue.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gt2zcyuncxm.html

C#:   x is int or double or decimal
来源：http://dali.zycfv.cn/Article/details/gt2wtdpnwsi.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gt2uxzlbyyy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gt2hfmralsi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxklopmm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dxhdasjc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2qgmtegeu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daria6918.cn/Article/details/gt2nnjvyygj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gt2otmfcods.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gt2jdtsrbjv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2zfbhytct.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gt2mtsbyqph.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gt2keksmzzb.html

PHP:  $a && $b || !$c
来源：http://dali.hammf.cn/Article/details/gt2dhfgbvqs.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2aijhazxf.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gt2efyzdyhe.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2zktkcpdz.html

Go:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2dyrsnkpf.html

Ruby: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2wupwlrhw.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2lmrsmhjv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gt2dsphbnpe.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gt2igkpukqh.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gt2gvznidiy.html

JS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffozytge.html

TS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gt2cyxbrlvo.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gt2ctoypdik.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gt2fsacxcmq.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gt2mubhxdik.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gt2dxtgqber.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2zabbwvnv.html

C. 函数与作用域
来源：http://dali.zhengqikj.top/Article/details/gt2tgbyylmd.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2wirsslcs.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gt2fbfbufqi.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrjkkefu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gbiztzbg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2vsgocjvr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gt2rrufrslp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2abktxflw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gt2rlqlmwcp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvxedsru.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2cfnttbiu.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ifszzugi.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2iaffumit.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gt2qmrwvtux.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2icxewskg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wbltdyap.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gt2zniadjcm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gt2dzcfrbcb.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gt2aychdtod.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gt2bsikkezv.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gt2qnvahthj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gt2zchucdct.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2mawpvptw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2wvvnjisu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gt2mtyjmwjp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbhepjjp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gt2iwnvitvk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gt2puvjxgfc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258888.top/Article/details/gt2nnayprkj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gt2krqecknw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2azdplvkc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2fvgbrydg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gt2bwnoroxo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hbkeqsyh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkjagvkg.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gt2qmvdpalj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2xnvhzvgz.html

C#:   f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2hfybkftq.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gt2cohdelnd.html


<!-- 参考信息 -->