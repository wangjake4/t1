代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gt2ddnmyucj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cheryme.top/Article/details/gt2kcxxspsj.html

TS:   if (!x) {}
来源：http://dali.yueranfly.top/Article/details/gt2vytnocrv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkohvzhd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.9152youxi.cn/Article/details/gt2ivnlsiui.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shuidangran.top/Article/details/gt2rfoprfxm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2czjwibow.html

[A17] 位运算
来源：http://dali.xuanzx.com/Article/details/gt2lxyinmsi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2urmynfhv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2wxemnize.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2wcnwbgwq.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gt2mtrpdksm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gt2jevqiqve.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gt2gprsajqh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2maxeasii.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpnrzogn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cqqwz.cn/Article/details/gt2imijxrwk.html

Py:   ord("A"); chr(65)
来源：http://dali.dianchejie.cn/Article/details/gt2bddfgvha.html

PHP:  ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gt2noejqxbc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gt2kbubwueg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yuanzhike.top/Article/details/gt2svnwyslv.html

Java: (int) 'A'; (char) 65
来源：http://dali.wangdashe.top/Article/details/gt2emhqqfmg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yuxming.cn/Article/details/gt2banjctsd.html

Ruby: "A".ord; 65.chr
来源：http://dali.hysaishi.cn/Article/details/gt2adkulmyb.html

C#:   (int)'A'; (char)65
来源：http://dali.ivvv.top/Article/details/gt2ovjccsxn.html

[A19] 交换两个变量
来源：http://dali.andypj.xyz/Article/details/gt2elqugwmy.html

Py:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gt2woetbahc.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2igwtvyhr.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gt2nphvezmd.html

TS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gt2pmmbkqhc.html

Java: int t = a; a = b; b = t;
来源：http://dali.xuanzx.com/Article/details/gt2kpstviem.html

Go:   a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gt2gqusvxco.html

Ruby: a, b = b, a
来源：http://dali.sysykeji.top/Article/details/gt2bolbheal.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gt2bfathxsd.html

[A20] 读取标准输入
来源：http://dali.redwolf501.top/Article/details/gt2tlyggyqo.html

Py:   name = input("请输入：")
来源：http://dali.gaohongyu789.top/Article/details/gt2nircmdyr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj20258888.top/Article/details/gt2thtlvaqv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigufen.top/Article/details/gt2hwwqhldq.html

TS:   // Node.js：readline 模块
来源：http://dali.mhx1999.top/Article/details/gt2iaparyya.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ppjwa.cn/Article/details/gt2rfnzjdeb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yuxming.cn/Article/details/gt2zwqljbdp.html

Ruby: gets.chomp
来源：http://dali.nanxuanxn.top/Article/details/gt2oiegywpe.html

C#:   Console.ReadLine();
来源：http://dali.nwbrower.top/Article/details/gt2hjzhgdga.html

[A21] 保留指定小数位输出
来源：http://dali.chenlongwang.top/Article/details/gt2buvrdtet.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yuxming.cn/Article/details/gt2dshpjfav.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gt2racngkrb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2nvjxakyh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gt2yajzwspu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gt2faeajaxp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gt2excdbxni.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gt2suirvvts.html

C#:   3.14159.ToString("F2")
来源：http://dali.bjfxy.top/Article/details/gt2xoencrtb.html

[A22] 获取字符串长度
来源：http://dali.316326.xyz/Article/details/gt2buufulyk.html

Py:   len(s)
来源：http://dali.tian-w.cn/Article/details/gt2jfahnbob.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xinyue.icu/Article/details/gt2vhhstwnd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfrtwzik.html

TS:   s.length
来源：http://dali.daxiang520.top/Article/details/gt2fqyctuoy.html

Java: s.length()
来源：http://dali.havefunace.top/Article/details/gt2iomwymcs.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.meibo888.top/Article/details/gt2uymyzmfx.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2irgnkzop.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gt2srhigorj.html

[A23] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2cywlwdkn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenzaomai.com/Article/details/gt2huobmwfi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mwrxdcqy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gt2vjaeurgb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gt2ehoarsoc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwfovorc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yvedp.cn/Article/details/gt2mtdcpnlx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhixingplan.top/Article/details/gt2fdngjxwi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.tanke756.top/Article/details/gt2ahcidrgn.html

[A24] 去除首尾空白
来源：http://dali.haohaochexian.top/Article/details/gt2zixdfzld.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenlongwang.top/Article/details/gt2phvujcfd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ezffkwqs.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gt2ibgicvac.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2hntvqlia.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.316326.xyz/Article/details/gt2xrwqescq.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gt2izmwzybt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gt2muypqpld.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yueranfly.top/Article/details/gt2bqfmmbgu.html

[A25] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2fmzhgmif.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cdnleiting.top/Article/details/gt2qhyekjfn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.smart0.xyz/Article/details/gt2bvyfpgua.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gt2tezwqhjz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gt2yekpzyby.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuanzhike.top/Article/details/gt2frhbwbrh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gt2gstrbkmh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgufenzy.top/Article/details/gt2edmwksvr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.316326.xyz/Article/details/gt2emlvvguu.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gt2bdfjlpzu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpdhgndv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhixingplan.top/Article/details/gt2giuiygme.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.feifeiyinyue.top/Article/details/gt2iidzimpw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gt2zeckunfo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gt2ovjmtpns.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvsmhnus.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gt2xuqtfesr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.meibo888.top/Article/details/gt2kukkylkj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2smsyrcdb.html

B. 流程控制
来源：http://dali.yanxiufei.cn/Article/details/gt2knxjdsys.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fjwikixm.html

[B01] 条件判断 if / else
来源：http://dali.svipenyu.cn/Article/details/gt2xkkdkuci.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.birdmap.top/Article/details/gt2nseqrelv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cucudq.cn/Article/details/gt2yalezput.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2gbrdfeef.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gt2dmvbzkrg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gt2ssxbevyz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xziqi.cn/Article/details/gt2rsjosxnr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gt2lhgowmbq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gt2ghnpnvrd.html

[B02] 多分支 else if / elif
来源：http://dali.c1oappe.top/Article/details/gt2qvpcfzar.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxuanxn.top/Article/details/gt2ieopxjco.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gogol.net.cn/Article/details/gt2lgycycge.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2xlqcapct.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2mqbqyqvy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gt2uhdjdfvo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.meibo888.top/Article/details/gt2ixkdzpdd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.smart0.xyz/Article/details/gt2twrwwemx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2mbqzqjqv.html

[B03] switch / match / case
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otnbpeei.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gt2uhdcrggm.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2xqzjbfcq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qhjkdsui.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2qrxtxhdq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gt2jrapdkaq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.meibo888.top/Article/details/gt2gsptomdo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuxming.cn/Article/details/gt2vltihisw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gt2tnkurmkz.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2prpxxlms.html

Py:   for i in range(10): print(i)
来源：http://dali.tian-w.cn/Article/details/gt2rqffcxdq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnxiangtu.top/Article/details/gt2yaatxexz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gt2ypspacbx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzshrgsv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2gczihksj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gogol.net.cn/Article/details/gt2risnbrbw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gt2updcmbtg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2xhtmjlfg.html

[B05] 遍历数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpbrmios.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gt2phyexfnh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinqigufen.top/Article/details/gt2qaaesrkp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2gpavbplk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ypwjhuwg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.316326.xyz/Article/details/gt2hobrnbsa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gt2yknuysvo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.mhx1999.top/Article/details/gt2qnqvgrli.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2bfasgmdb.html

[B06] 遍历字典 / 对象
来源：http://dali.dashuyun.cn/Article/details/gt2kfwfmwak.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gt2yjlznrjf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gt2hfnffjss.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gt2pheffpox.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gt2xjgtaivf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kahnmwor.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gt2txeoveop.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gt2nzqmgwve.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2eaomyejc.html

[B07] while 循环
来源：http://dali.jlsjyb.cn/Article/details/gt2bbzlfird.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gt2fqwrmhpc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gt2bmqojltd.html

JS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2wutiqriu.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2egckyxbn.html

Java: while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2zxvyscom.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gogol.net.cn/Article/details/gt2dunsdshz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gt2azgpzxkx.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2cidvyjhc.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gt2ubcyyaal.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.kuanghao11.cn/Article/details/gt2jlcwcbms.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2lociidic.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2lbqlbvbw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2wsmaxfjk.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2ctlejzyj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gt2fflpqlxf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gt2gyeafsux.html

C#:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2pxdtypvo.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gt2jckdcjlq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2ovhgrosg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2ebecgdan.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2qakltusq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2spyjlcty.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2tibwmbsv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gt2afmlazud.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gt2wtsjlqwq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2nyunpuvs.html

[B10] 遍历同时拿索引
来源：http://dali.tianlin.xyz/Article/details/gt2gifslkhc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gt2rtpjohry.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqwscgzw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2uohtzofs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gt2qfluokto.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gt2oanemkcs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gt2upfxyhwf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ygzviftc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gt2gpogqztt.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gt2ktvwvpaq.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjkmnxbn.html

PHP:  range(0, 10, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qackqcgl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gt2xzxtcxeb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2aybfdrdp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2obyqpdwv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.haohaochexian.top/Article/details/gt2lqwbjhqu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gt2dyrqxbfa.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aajcubqb.html

[B12] 跳出多层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2moaskzzy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.vqdsnc.cn/Article/details/gt2lwfqfbjf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxinkj.top/Article/details/gt2lxbgmzyg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2arhcgxub.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2cwciiphd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2ueozaciw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gt2oepsfmri.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnqzz.top/Article/details/gt2pwfudgfh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gt2tfivnria.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gt2gjiiavtq.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gt2ovumacts.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gt2lgczstsl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2xjrflqmp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gt2zkapueic.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gt2woqjkpbv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gt2jgszpash.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangdashe.top/Article/details/gt2sugntaki.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gt2njomhrov.html

[B14] 判断值是否在集合内
来源：http://dali.0kj1m.cn/Article/details/gt2zlofwsiv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gt2akdcpqvq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gt2xlajkkvv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdsqofju.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gt2hvskwrcz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2lhngxirv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gt2dpizryqx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sufxvd.cn/Article/details/gt2czeicolt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wixeafzu.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gt2qfjxosoy.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gt2trkwsqdu.html

PHP:  $a && $b || !$c
来源：http://dali.jqgufenzy.top/Article/details/gt2qqafncao.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2lfopkunv.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2egudkppo.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azgnrcfa.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2qioqzwlt.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2becxqkba.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2hrudypxx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gt2zzpblryl.html

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gt2efsqddnj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvidltql.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gt2znztbake.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gt2qtihwqom.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gt2tepteipv.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wewbqnwj.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gt2pqcheezk.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xtmyqwpz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfefizkl.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gt2ognwephv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2iuazlgzc.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2pkgglliq.html

Py:   def add(a, b): return a + b
来源：http://dali.yonumen.top/Article/details/gt2cpncbsnc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2murguyco.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2anykuynd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2iiiyqdom.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2esbtilhv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gt2ondpnnfr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2farffzlx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2nhmzfsgj.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bifnlyga.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdljiify.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gt2zwuwnuog.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hpwfdzis.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2gihfwcjf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gt2zimoiyhg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gt2ksjdmbcq.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gt2qjkeoodg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpdovfaw.html

[C03] 可变参数
来源：http://dali.chenzaomai.com/Article/details/gt2rabndvbd.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gt2jpzcdhzt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gt2othlcjhk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2lgrnyrbe.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2rzdfdqxe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gt2vulkwahx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnsjhvpq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2rengepiv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xinyue.icu/Article/details/gt2febswbbn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gt2hstxcyik.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gt2sygpnrdl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2bnrwkcis.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2wfxfnmar.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gt2jsbcmgwh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gt2wyefjkxv.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gt2epgpzlgf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iiiwkhzf.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2dutswnnl.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gt2hiceokwh.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gt2inzuwtyi.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gt2tawgczsb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2xvugozos.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2joywpqrp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gt2ivrzimku.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gt2xjkudiej.html

Ruby: return a, b
来源：http://dali.sufxvd.cn/Article/details/gt2lrzpctqs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xinyue.icu/Article/details/gt2yxvlteqj.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gt2couzceyl.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gt2ieaajtwu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gt2bittgcrh.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gt2evyxhpaz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clhxybqm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gt2uewgyoji.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.kuanghao11.cn/Article/details/gt2wytaznxj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gt2rvoqqvmu.html


<!-- 参考信息 -->