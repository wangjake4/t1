代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gt2axqeihix.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hysaishi.cn/Article/details/gt2bawyktjm.html

Go:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2aqhuebsr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.daxiang520.top/Article/details/gt2hyftabyj.html

C#:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gt2gyktwasb.html

[A15] 空值判断与默认值
来源：http://dali.gzhubu.top/Article/details/gt2mshtsfjk.html

Py:   value = data or "默认值"
来源：http://dali.hfpthk.cn/Article/details/gt2bujbljhn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gt2srontmdu.html

JS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gt2ddzwypgs.html

TS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gt2ietkwskb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.316326.xyz/Article/details/gt2jmdmhqxg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ydzc1.top/Article/details/gt2qsymyzuu.html

Ruby: value = data || "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gt2uwbhgpix.html

C#:   var value = data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gt2whcmfuur.html

[A16] 真假值判断规则
来源：http://dali.meibo888.top/Article/details/gt2mttzadhz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhongyouzk.top/Article/details/gt2tcezuhcr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yongpay.top/Article/details/gt2jsyimouu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cheryme.top/Article/details/gt2zebleadu.html

TS:   if (!x) {}
来源：http://dali.ybcxt.top/Article/details/gt2cvxddpdy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhawgcmw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.aizwys.cn/Article/details/gt2ldijojjr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gotoacloud.top/Article/details/gt2amkbynda.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2jqqbemiy.html

[A17] 位运算
来源：http://dali.ppjwa.cn/Article/details/gt2iistofok.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2zozzzmwd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hnqzz.top/Article/details/gt2fyrblnwe.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gt2gdowcnbl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2ujbsgqnf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2tyfxbgma.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2bczcbblv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2euktizjg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2jopgfgum.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsxtpixe.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgufenzy.top/Article/details/gt2drppfuxd.html

PHP:  ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gt2absgikwc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigufen.top/Article/details/gt2mfaikgxm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gt2ozspguai.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenzaomai.com/Article/details/gt2ppcfxzck.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.andypj.xyz/Article/details/gt2ukbkzqpg.html

Ruby: "A".ord; 65.chr
来源：http://dali.dashuyun.cn/Article/details/gt2progzbxw.html

C#:   (int)'A'; (char)65
来源：http://dali.yvedp.cn/Article/details/gt2ebnukbwz.html

[A19] 交换两个变量
来源：http://dali.gzhubu.top/Article/details/gt2bwuelgcv.html

Py:   a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gt2gzmketcb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cheryme.top/Article/details/gt2jjhlxzws.html

JS:   [a, b] = [b, a];
来源：http://dali.cheryme.top/Article/details/gt2qhnqnfjz.html

TS:   [a, b] = [b, a];
来源：http://dali.pycfn.com/Article/details/gt2izinftlx.html

Java: int t = a; a = b; b = t;
来源：http://dali.nwbrower.top/Article/details/gt2dwjrbcpr.html

Go:   a, b = b, a
来源：http://dali.316326.xyz/Article/details/gt2bxmwjjsn.html

Ruby: a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2dhjsrbui.html

C#:   (a, b) = (b, a);
来源：http://dali.ybcxt.top/Article/details/gt2hpqwdatf.html

[A20] 读取标准输入
来源：http://dali.vqdsnc.cn/Article/details/gt2jbprbjxi.html

Py:   name = input("请输入：")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxxwchck.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ybcxt.top/Article/details/gt2ebmtkngs.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgfzy.top/Article/details/gt2ijfffhol.html

TS:   // Node.js：readline 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2bxvzolhv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jiagoushi.top/Article/details/gt2safjuxit.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gt2djjbqact.html

Ruby: gets.chomp
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktxjcwkk.html

C#:   Console.ReadLine();
来源：http://dali.jqgfzy.top/Article/details/gt2fnrhpmza.html

[A21] 保留指定小数位输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmwckzem.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxqcsehi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gt2uztsedkm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gt2yuqvzoit.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2ddzxtjom.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gt2mtxqpfof.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gt2zzwpwahz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gt2xcjchpco.html

C#:   3.14159.ToString("F2")
来源：http://dali.ybcxt.top/Article/details/gt2hojldyrm.html

[A22] 获取字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjvlmqep.html

Py:   len(s)
来源：http://dali.ybcxt.top/Article/details/gt2fyzhqxhq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.bjfxy.top/Article/details/gt2nlqfpard.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yueranfly.top/Article/details/gt2dbzdsgze.html

TS:   s.length
来源：http://dali.mhx1999.top/Article/details/gt2jmrdsdld.html

Java: s.length()
来源：http://dali.tanke756.top/Article/details/gt2usqyxsmd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dianchejie.cn/Article/details/gt2yynoewop.html

Ruby: s.length
来源：http://dali.tianlin.xyz/Article/details/gt2mkmreeqm.html

C#:   s.Length
来源：http://dali.cucudq.cn/Article/details/gt2bnwrycyf.html

[A23] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2xziiimnc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yongpay.top/Article/details/gt2ibhfiwdn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fzhhl.top/Article/details/gt2gryhsfeb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hammf.cn/Article/details/gt2ovdflniw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gt2mjaujoyl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gt2jkrljzps.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yongpay.top/Article/details/gt2vghwpidw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gt2ptweywpu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.0kj1m.cn/Article/details/gt2aghcttkh.html

[A24] 去除首尾空白
来源：http://dali.zdqjudy.top/Article/details/gt2cvxeqtul.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.mhx1999.top/Article/details/gt2mdqoqhyr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ppjwa.cn/Article/details/gt2gvsghatq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gt2sontjcic.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jianghu66.top/Article/details/gt2hsogbwnv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhixingplan.top/Article/details/gt2easemmzt.html

Go:   strings.TrimSpace(s)
来源：http://dali.hywenlv.cn/Article/details/gt2ocjihktv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.snrcjt.cn/Article/details/gt2jtefmjmd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hywenlv.cn/Article/details/gt2qpsnlsnp.html

[A25] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2xuszuccv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jlsjyb.cn/Article/details/gt2tklebjgt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhqyksla.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gogol.net.cn/Article/details/gt2blosofuz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svcmgdsc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dianchejie.cn/Article/details/gt2zrdyhxmk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2rujlleee.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.meibo888.top/Article/details/gt2rczkfsta.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gt2xrjfndys.html

[A26] 类型转换总览
来源：http://dali.yuxming.cn/Article/details/gt2onayjamz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pycfn.com/Article/details/gt2phpyvvgs.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.mhx1999.top/Article/details/gt2fbiolrgy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tian-w.cn/Article/details/gt2dwquonpx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hfpthk.cn/Article/details/gt2fxrjzgtg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gt2pdgodefi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dashuyun.cn/Article/details/gt2peouqhqg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yongpay.top/Article/details/gt2agjbdsxb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gt2dcngkdii.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2bdfcgrqz.html

B. 流程控制
来源：http://dali.shuidangran.top/Article/details/gt2jdsezial.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2zviyzjjg.html

[B01] 条件判断 if / else
来源：http://dali.pengpengdd.cyou/Article/details/gt2kcbmfsrp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinqigufen.top/Article/details/gt2yabpfcca.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxfldoly.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gt2wvanwxul.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2iygoamxc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gt2khthtbhr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yanxiufei.cn/Article/details/gt2bjmjxjhx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecmnfjgk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2rrqqvity.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gt2qbiokqid.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxinkj.top/Article/details/gt2shxlsftp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jianghu66.top/Article/details/gt2qckjhhsc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2mkxvzyiz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2jsbgjfae.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gt2zrezzobg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.quarkkingdee.top/Article/details/gt2swcvmomp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gt2hlbyyayo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldhuciea.html

[B03] switch / match / case
来源：http://dali.nanxuanxn.top/Article/details/gt2nrgpimxx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.haohaochexian.top/Article/details/gt2luknlqxl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2sxxkjygb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2qeukefyt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2akpznflq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gt2ohyzljml.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hywenlv.cn/Article/details/gt2lkwtnmcl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gotoacloud.top/Article/details/gt2btbhqljo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqfqyawx.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gt2nxxqzvbo.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gt2tenxtkmx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shzxlz.cn/Article/details/gt2xajszurn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.andypj.xyz/Article/details/gt2mnhtszpr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xklocyda.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gt2dzmdqkmf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.9152youxi.cn/Article/details/gt2foohebaa.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gt2nkkjyyds.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gt2nipipcrr.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2tbrxycoe.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gt2evdaqvye.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yueranfly.top/Article/details/gt2lwdpgeoi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gt2czbpligg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqjjoofm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gt2mkjjgvit.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ehwqpu.com/Article/details/gt2wdjvbudd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258.top/Article/details/gt2iwnqzobm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sysykeji.top/Article/details/gt2rbmmvakh.html

[B06] 遍历字典 / 对象
来源：http://dali.zdqjudy.top/Article/details/gt2zleublvj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gt2uynxtyjk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gt2rhonbxom.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gt2wpwbwcoy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gt2nyjyfmfi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.bjfxy.top/Article/details/gt2hzokwaax.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gt2sfjtwroy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gt2gdyjqnhq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gt2sqpyyhpq.html

[B07] while 循环
来源：http://dali.hnqzz.top/Article/details/gt2bfwgsdhs.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2zxptajrl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yueranfly.top/Article/details/gt2qdvjpgue.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2krpthyho.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gt2lyutwozh.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gt2uxauohyx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ehwqpu.com/Article/details/gt2hxmudegj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gt2tbrtfsqq.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isdzuskp.html

[B08] do-while（至少执行一次）
来源：http://dali.redwolf501.top/Article/details/gt2kdlbtolr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gt2bufptkjk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gt2wfxdgewi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2eysnjynr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2zyyhftnu.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2lznlucns.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gt2vkjwngvv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gt2vvmqdbke.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2xotcatra.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gt2spkimwxl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfiykcob.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2vlvsjhrs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2mcsyordz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtpqahrs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckuwfawl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gt2aqjsnxrd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daria6918.cn/Article/details/gt2xrhhzrgv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2fkkevhbz.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gt2ekvahuby.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gt2xfcnsdze.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gt2tezfjzaq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2acfezwxz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gt2tebgeucg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nwbrower.top/Article/details/gt2lbvtuudr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gt2zfopvfle.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gt2exyatetu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gt2raqxnhjs.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gt2iulgigta.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gt2zumuynbh.html

PHP:  range(0, 10, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2syibdcce.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gt2pffdooum.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2euepbvht.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2tectofvk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jyoumei.cn/Article/details/gt2wwtdelso.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gt2glructrz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.redwolf501.top/Article/details/gt2jwrjsvxb.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gt2wrkkslhq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gt2xxiwplzk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxuanxn.top/Article/details/gt2driwvaoc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2itakvkqg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2jtvwbsgw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2vslkruuc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gt2eetnrtbl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zdqjudy.top/Article/details/gt2gfothmpc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nwbrower.top/Article/details/gt2oxvxsptr.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gt2vxsvneva.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gt2qrjkcqzt.html

PHP:  is_numeric($x)
来源：http://dali.gogol.net.cn/Article/details/gt2ncqvtyfk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gt2zjwlwrms.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gt2gukkqjid.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gt2kcbnqxsm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frchhuwe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gt2iejnpvip.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gt2bfvlksef.html

[B14] 判断值是否在集合内
来源：http://dali.xziqi.cn/Article/details/gt2yrxbnopx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2cbjrqcnp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gt2czijdttk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2kjauilmx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2yczzgwmc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2ogvdgzsw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zycfv.cn/Article/details/gt2vpoztjxc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gt2dsswisqq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gt2ymugxxmd.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gt2ztbgmuaj.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gt2fpdlhtlh.html

PHP:  $a && $b || !$c
来源：http://dali.dianchejie.cn/Article/details/gt2vamespju.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2nicbxefu.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2bisgqhci.html

Java: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2xcvtbvsr.html

Go:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2jgskrqmg.html

Ruby: a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2lzgvopot.html

C#:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2myrbtpox.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xinyue.icu/Article/details/gt2tdvimvvy.html

Py:   if not data: return
来源：http://dali.hongshengwenyu.top/Article/details/gt2odvopncj.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gt2tntsxdze.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gt2kpsqddyx.html

TS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gt2jylhoqim.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2srmgsocr.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gt2hcwnupsz.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gt2uhfsyyqb.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gt2zbodgzbf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2yhwvqovj.html

C. 函数与作用域
来源：http://dali.meibo888.top/Article/details/gt2fqrbmmpu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2omuvbgfj.html

[C01] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gt2gvfefbiw.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gt2qesdahhv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gt2pdzbqowq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2hvfcfriy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kolcwpef.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2qgdssizh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gt2fhxxzoht.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxinkj.top/Article/details/gt2hrkusjbj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tmwmemqd.html

[C02] 默认参数
来源：http://dali.jinqigufen.top/Article/details/gt2kotxoofp.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gt2ibubjjeb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gt2ouhkhije.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2ulldztcr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2lplpaduv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gt2rnsjrtgy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gt2sguzfxhd.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gt2sckkysln.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gt2txjhxoxv.html

[C03] 可变参数
来源：http://dali.9152youxi.cn/Article/details/gt2soybbubk.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gt2kfccnipx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gt2gtluvduu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2ccsjcyoq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2apbbequz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gt2uqbwsolr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gt2cyoyjbvj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gt2negigaih.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hodzdvcv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gt2mvliiwbx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gt2snzgzouu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gt2ixgnjidy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2kulmerea.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gt2xwviciao.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gt2svemicli.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gt2nnypggeo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2spossvgj.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gt2gwbfylvp.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gt2lpkqaxkj.html


<!-- 参考信息 -->