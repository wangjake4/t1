代发 wailian999

[A14] 注释写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbtiqxzf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xuanzx.com/Article/details/gtghbyncik.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtnbspiyjr.html

JS:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtppcwnrzn.html

TS:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtzykzpkgp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.birdmap.top/Article/details/gtovnhnffl.html

Go:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtxdpxgkto.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jlsjyb.cn/Article/details/gtgwejigos.html

C#:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gtaqnsclui.html

[A15] 空值判断与默认值
来源：http://dali.dianchejie.cn/Article/details/gtlajabtcx.html

Py:   value = data or "默认值"
来源：http://dali.yj20258888.top/Article/details/gtrzzzeisf.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtnvhpshpl.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gtggfxjquj.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtqtcynsmk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sufxvd.cn/Article/details/gtzkymwpyu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangdashe.top/Article/details/gtywaxxyoa.html

Ruby: value = data || "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gtlbozehxb.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtmqpiqmgx.html

[A16] 真假值判断规则
来源：http://dali.haohaochexian.top/Article/details/gtijoncsmx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xziqi.cn/Article/details/gtyqttuhxu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jyoumei.cn/Article/details/gthrsprynj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangdashe.top/Article/details/gtorerxvch.html

TS:   if (!x) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlzudxtg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.tian-w.cn/Article/details/gtwikzkuhh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj202588.top/Article/details/gtkoljggnv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tanke756.top/Article/details/gtnvljcsep.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtoxglapms.html

[A17] 位运算
来源：http://dali.zhixingplan.top/Article/details/gtmeuzkohm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtggulywss.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.birdmap.top/Article/details/gtxmbrdlcn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtrmjhegak.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtjekqzfgw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtwfrobctz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtzncrctlt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtzmfzotct.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtncfpteyg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gotoacloud.top/Article/details/gtmmhqnyfo.html

Py:   ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gtqfuukqpb.html

PHP:  ord("A"); chr(65)
来源：http://dali.shuidangran.top/Article/details/gttivksnmz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gtufrvliui.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gtfcrvemfa.html

Java: (int) 'A'; (char) 65
来源：http://dali.pengpengdd.cyou/Article/details/gtmtulrtig.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ydzc1.top/Article/details/gtnmismmnv.html

Ruby: "A".ord; 65.chr
来源：http://dali.tianlin.xyz/Article/details/gtscplljsi.html

C#:   (int)'A'; (char)65
来源：http://dali.wangshuangyany.cn/Article/details/gtnnucmnyk.html

[A19] 交换两个变量
来源：http://dali.yuxming.cn/Article/details/gtihtihesr.html

Py:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtgaaqsubn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.snrcjt.cn/Article/details/gtbeholqiv.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gtufefoqfs.html

TS:   [a, b] = [b, a];
来源：http://dali.dashuyun.cn/Article/details/gtrodijvjp.html

Java: int t = a; a = b; b = t;
来源：http://dali.hysaishi.cn/Article/details/gtugpttrse.html

Go:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtkbyiykbe.html

Ruby: a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtnigvgqkd.html

C#:   (a, b) = (b, a);
来源：http://dali.zhoulong.xyz/Article/details/gtytsllaxt.html

[A20] 读取标准输入
来源：http://dali.hywenlv.cn/Article/details/gtcgbeqzpi.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gtytrizhld.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhixingplan.top/Article/details/gtjcpddpav.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.meibo888.top/Article/details/gtvwanreld.html

TS:   // Node.js：readline 模块
来源：http://dali.jianghu66.top/Article/details/gtgsabpjvc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hysaishi.cn/Article/details/gtizgvqbfp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnxiangtu.top/Article/details/gtrdepfexj.html

Ruby: gets.chomp
来源：http://dali.jiagoushi.top/Article/details/gtvnjyinvx.html

C#:   Console.ReadLine();
来源：http://dali.shangyingyoupin.top/Article/details/gtnqkxxiuk.html

[A21] 保留指定小数位输出
来源：http://dali.dianchejie.cn/Article/details/gtpasqtvtx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yongpay.top/Article/details/gtqvycbsqy.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtacycwwdv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtgljhsgxt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtgejsdvcm.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtquykmvpv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.wangshuangyany.cn/Article/details/gtuhtftpfx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtpuranrii.html

C#:   3.14159.ToString("F2")
来源：http://dali.xziqi.cn/Article/details/gtbyvorjcw.html

[A22] 获取字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtzpghhvwp.html

Py:   len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgrkibfok.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aizwys.cn/Article/details/gtfyejadix.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gthaniddnn.html

TS:   s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwasglojh.html

Java: s.length()
来源：http://dali.smart0.xyz/Article/details/gtjzzafruo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jianghu66.top/Article/details/gtgjxgcydt.html

Ruby: s.length
来源：http://dali.nanxuanxn.top/Article/details/gtfwncaxuo.html

C#:   s.Length
来源：http://dali.ybcxt.top/Article/details/gtgcomjgcg.html

[A23] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gthvivhwvb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.haohaochexian.top/Article/details/gtcqjvsfud.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aibaodan.cn/Article/details/gtzhzcccaj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtmfdzkyim.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tanke756.top/Article/details/gtndkuyohc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtuxspjati.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hfpthk.cn/Article/details/gtyaqhjjsm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtvrtoeljb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangdashe.top/Article/details/gtvoudrlmt.html

[A24] 去除首尾空白
来源：http://dali.smart0.xyz/Article/details/gtknmqagck.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.andypj.xyz/Article/details/gtkquoddai.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tanke756.top/Article/details/gtxbtlkqdx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtkzuhebot.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtpdyavfyw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gtbewcvcnf.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthefgagkg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.redwolf501.top/Article/details/gtwtcvtljy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.havefunace.top/Article/details/gtrxkscnqx.html

[A25] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtcbqazeyj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sufxvd.cn/Article/details/gtpnycqemo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.nwbrower.top/Article/details/gtixgtekxv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtteowsjqc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fzhhl.top/Article/details/gtcfjgkpmq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtzetmwipo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gtkchnhiet.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hongshengwenyu.top/Article/details/gtsywxokkd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtbzqzafjt.html

[A26] 类型转换总览
来源：http://dali.shzxlz.cn/Article/details/gtepugzuhe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258888.top/Article/details/gtlgsycgua.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjhpabip.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.feifeiyinyue.top/Article/details/gtnwdxnsdz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnxiangtu.top/Article/details/gtivtingxx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gtcblmrxap.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yangfankeji.com/Article/details/gtmkhqfgmz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrtgllyx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtpxqujtxt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtitfxtans.html

B. 流程控制
来源：http://dali.pycfn.com/Article/details/gtolaitlff.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpqjokiog.html

[B01] 条件判断 if / else
来源：http://dali.ehwqpu.com/Article/details/gtvmkncsyv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cheryme.top/Article/details/gtsiygxkev.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cheryme.top/Article/details/gtcaqzguvg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtcjdedlze.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gtrlrmtfwt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gtfxrlqokp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gtxvhacuoo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gtisaktfyj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtffdmsxvy.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gtlrxhnahb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgfzy.top/Article/details/gtvdsciovi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shzxlz.cn/Article/details/gttnhqwove.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtymsqsemx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtflejpkpt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gttvadnfat.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fengsongda.top/Article/details/gtkrqetize.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.birdmap.top/Article/details/gtelvmyedt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtpgxamtrg.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gtibwjigwk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jyoumei.cn/Article/details/gtnnsnttdl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtxzkhjptu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtidvofayg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtqtqdpayh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtrcpmbcix.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gzhubu.top/Article/details/gtgsxxqydr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gtzqwntfhx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtpzgcexzc.html

[B04] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtepyexlam.html

Py:   for i in range(10): print(i)
来源：http://dali.chenzaomai.com/Article/details/gtjryvgcld.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gtxtfptqpx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwdaaejh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtjehutklr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgukylqeb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtdeldtqdo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gogol.net.cn/Article/details/gtuqycgzpy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoryfhngc.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtqjkvkzqe.html

Py:   for item in arr: print(item)
来源：http://dali.ppjwa.cn/Article/details/gtxslxknjd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xylfe.cn/Article/details/gtqngbunxi.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtrzfpmmiy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gthsagnjhm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xylfe.cn/Article/details/gttgxbamoc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxuanxn.top/Article/details/gtrptozubz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenlongwang.top/Article/details/gtyuwmlajk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnqzz.top/Article/details/gtdxbpjzgy.html

[B06] 遍历字典 / 对象
来源：http://dali.pycfn.com/Article/details/gthuygcihr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jianghu66.top/Article/details/gtotmqszuo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gtyrxajyeq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpgbdojw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gtaskgtwia.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gticeoocaw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gtuedxtclp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtpxwpbmpr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtmmmcgaqy.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gtwqsyyxfz.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gtqgpvrqhj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtglzpbugr.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtqgwyifez.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtkwrvvsuv.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtncnbporn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.redwolf501.top/Article/details/gtvzasvgsy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gtrxejlwth.html

C#:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtfuljxzms.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gtfgfqhnoy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hywenlv.cn/Article/details/gtgqngvtou.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxizvtgt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtxavjlevm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtjfmmpgpc.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gthxxhnumd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nwbrower.top/Article/details/gtxmyrhswf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.kuanghao11.cn/Article/details/gtcncyzgfz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtficnxloz.html

[B09] break 与 continue
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtwaudpu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gtittbrdus.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtbvtbgopp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtclxxhnyb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtkzhjawse.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtbgormlrf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gthrmxwbww.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gtwxnvkvdk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtetmrnjrw.html

[B10] 遍历同时拿索引
来源：http://dali.sysykeji.top/Article/details/gtxovgmodf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjowljjpv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvncyskbm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtmcpurxtf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtlyzlckln.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shzxlz.cn/Article/details/gtmaldmvvu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gtholjfpgv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtawkbfezt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ybcxt.top/Article/details/gtgoiuujrn.html

[B11] 生成数字序列 / 区间
来源：http://dali.bjfxy.top/Article/details/gtxpobtiqz.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gtqzhavzsf.html

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gtzubasbop.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtezxxlenx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gtiyzcjizl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.snrcjt.cn/Article/details/gtgrvqkekt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuxming.cn/Article/details/gtgpvbsqoo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.havefunace.top/Article/details/gtmibpuiqi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gtlefoxtaw.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtevkyluhi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gtoxrlrqgu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tian-w.cn/Article/details/gtvhvuduzy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtbkxmizhi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtapwtqthw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtwwldlfqc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gtfjjkbein.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtscabregu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhengqikj.top/Article/details/gtochajptp.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtakjkdytg.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gtcyodpwhj.html

PHP:  is_numeric($x)
来源：http://dali.birdmap.top/Article/details/gtnswqnmjl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gteeqfipkp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtnbnpsxqk.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gtrfhxvcng.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fengsongda.top/Article/details/gtstdzyfge.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gtxeqooeaq.html

C#:   x is int or double or decimal
来源：http://dali.chenjidiqi.icu/Article/details/gtqfnwbfpz.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gtafyckseo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gtbmmebqfx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cheryme.top/Article/details/gtubthalut.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtbakbapeh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtuivmkohy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gtcxclpond.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gtogiezcom.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtatdhqcyl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtlhrmhlje.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtznoudptw.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtogqohhoy.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtzjsmnsts.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtyrjxonwo.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtrpfxcrid.html

Java: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gteupmbnvu.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtccrprkgh.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtcbeyzxer.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtvfmihsss.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtoouvandi.html

Py:   if not data: return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcccdcupj.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtidzyxwxm.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphwlfjac.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gttyoseddq.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtfmzvbzif.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gtjyefgvgi.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtlpdbrswk.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gttvlccblk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnfizuddc.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtxlpkzcgj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtilmqzvpe.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtlttkyvio.html

Py:   def add(a, b): return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtheciqsmd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gteaizrcku.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtvsyouzwc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtxjtleeay.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtrzznhzys.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gtdqcstibg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gttiwxfnnp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtdaghhwlu.html

[C02] 默认参数
来源：http://dali.pycfn.com/Article/details/gthgqfvshr.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtwnpfcwdh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gthxqpjakn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtdorhahva.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtzyrgcvks.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gtalrlhxia.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gtsmyymbtf.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttpsfliq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gtaaxjqpyo.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtaubkolqz.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gterfizmuf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtaensnyrf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtjpclqcyp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtiiuqkeog.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gtlcexkicu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtavptzbyl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtrbdsxpqo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gttixtttui.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gtvcotcnzq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtuqgbzupg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gttjnejuag.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtwwmdvcyt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gtmoulnuuy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtjxbamyyq.html


<!-- 参考信息 -->