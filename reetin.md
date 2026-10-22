代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gt2qodybpvr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhixingplan.top/Article/details/gt2ymmoxwgr.html

Go:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gt2glhtfpou.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.kuanghao11.cn/Article/details/gt2exfzwpcf.html

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmwwukjr.html

[A15] 空值判断与默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2lehitioi.html

Py:   value = data or "默认值"
来源：http://dali.zhengqikj.top/Article/details/gt2qbmnzdxp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tivgqrvh.html

JS:   const value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gt2dhgwnksd.html

TS:   const value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gt2wjxggxxl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pycfn.com/Article/details/gt2kjdhdjak.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zdqjudy.top/Article/details/gt2jvqvthhe.html

Ruby: value = data || "默认值"
来源：http://dali.shuidangran.top/Article/details/gt2sgfizwfv.html

C#:   var value = data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gt2dmyhstcq.html

[A16] 真假值判断规则
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqgpcxjl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.kuanghao11.cn/Article/details/gt2pjaiqzho.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jiagoushi.top/Article/details/gt2rmcjhmpc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swullzku.html

TS:   if (!x) {}
来源：http://dali.sweek.top/Article/details/gt2luhdcclm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj202588.top/Article/details/gt2roznochb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ehwqpu.com/Article/details/gt2agtvwwxt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ehwqpu.com/Article/details/gt2atonisxv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dianchejie.cn/Article/details/gt2tjnoheyd.html

[A17] 位运算
来源：http://dali.meibo888.top/Article/details/gt2dgygwdty.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gt2zirrvugv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2kywkoino.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gt2xksoqkyv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gt2ayyhuhhu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2zvgmoojz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gt2hnqnzdqf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdcokwgg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2qyfyvofa.html

[A18] 字符与 ASCII 码互转
来源：http://dali.birdmap.top/Article/details/gt2czdhdmwf.html

Py:   ord("A"); chr(65)
来源：http://dali.cqqwz.cn/Article/details/gt2reajbbas.html

PHP:  ord("A"); chr(65)
来源：http://dali.svipenyu.cn/Article/details/gt2chpgnnpi.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.9152youxi.cn/Article/details/gt2staqxvau.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.iojbl.cn/Article/details/gt2drfwfani.html

Java: (int) 'A'; (char) 65
来源：http://dali.cheryme.top/Article/details/gt2gachmdej.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ybcxt.top/Article/details/gt2rssweaev.html

Ruby: "A".ord; 65.chr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzcbuiqx.html

C#:   (int)'A'; (char)65
来源：http://dali.kuanghao11.cn/Article/details/gt2ooizvyal.html

[A19] 交换两个变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbyooiwt.html

Py:   a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gt2ypwzwswf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shuidangran.top/Article/details/gt2rkkpfuwv.html

JS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gt2vajpqvzx.html

TS:   [a, b] = [b, a];
来源：http://dali.hongshengwenyu.top/Article/details/gt2orcburcp.html

Java: int t = a; a = b; b = t;
来源：http://dali.gogol.net.cn/Article/details/gt2ajtfqebq.html

Go:   a, b = b, a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwsvpejq.html

Ruby: a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gt2vxrgoexk.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gt2garmvahm.html

[A20] 读取标准输入
来源：http://dali.havefunace.top/Article/details/gt2pkkxdvtb.html

Py:   name = input("请输入：")
来源：http://dali.hnxiangtu.top/Article/details/gt2bkuhvsws.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj202588.top/Article/details/gt2qwtunilb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhongyouzk.top/Article/details/gt2jrbpeghe.html

TS:   // Node.js：readline 模块
来源：http://dali.yj202588.top/Article/details/gt2frakqcvn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pycfn.com/Article/details/gt2mlpgymoy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.316326.xyz/Article/details/gt2gdmmqxzm.html

Ruby: gets.chomp
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpabsvdd.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gt2kdvkgqjm.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gt2qcroaale.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bobwiwed.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gt2gcxqrwdo.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2yhougwox.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2yeeksuzl.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gt2svzqcmxa.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gt2qvygsgrd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gt2lqbtfejm.html

C#:   3.14159.ToString("F2")
来源：http://dali.yongpay.top/Article/details/gt2edpxjokp.html

[A22] 获取字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpefsjis.html

Py:   len(s)
来源：http://dali.svipenyu.cn/Article/details/gt2kkaivumo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jiagoushi.top/Article/details/gt2epyxbqvp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cdnleiting.top/Article/details/gt2wbzeelaj.html

TS:   s.length
来源：http://dali.hysaishi.cn/Article/details/gt2rmhpakbz.html

Java: s.length()
来源：http://dali.ivvv.top/Article/details/gt2amurbxmx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2ldnrjxmd.html

Ruby: s.length
来源：http://dali.yuanzhike.top/Article/details/gt2pjaxuxcn.html

C#:   s.Length
来源：http://dali.zycfv.cn/Article/details/gt2hrlxmqxu.html

[A23] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gt2hliscago.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.guannengcc.top/Article/details/gt2zcoycfqd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ydzc1.top/Article/details/gt2dxtbqoha.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gt2oqtyoowi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gt2rngxbzhq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gt2xxrftzue.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.havefunace.top/Article/details/gt2htapqmjv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yszvygrx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.birdmap.top/Article/details/gt2hsrymsed.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gt2krpugihw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gt2aucjoiaj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gogol.net.cn/Article/details/gt2gyhkwnqd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cucudq.cn/Article/details/gt2oylqzvln.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gt2bwjuenvq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqdnupld.html

Go:   strings.TrimSpace(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlywrard.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daria6918.cn/Article/details/gt2vpgioqkv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gt2ofrgckke.html

[A25] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbramqmq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gt2vcsmjgvo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rasltilr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hblohwhk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guannengcc.top/Article/details/gt2kyrgvckv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tianlin.xyz/Article/details/gt2oergmzyj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gt2gcjrxuhi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zycfv.cn/Article/details/gt2ppfqmwmv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gt2lmepcawd.html

[A26] 类型转换总览
来源：http://dali.ybcxt.top/Article/details/gt2ylmkrwrr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cashguo.top/Article/details/gt2bqblqhie.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.kuanghao11.cn/Article/details/gt2cychfbdl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yongpay.top/Article/details/gt2cmsrxuqj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cheryme.top/Article/details/gt2jkizgzgm.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gt2nrsjdwma.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxinkj.top/Article/details/gt2xxcxvaut.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yongpay.top/Article/details/gt2jtauhhxr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hammf.cn/Article/details/gt2bsvfoigw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2slfebeqd.html

B. 流程控制
来源：http://dali.cheryme.top/Article/details/gt2igpkifod.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dwzanfpv.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyouchvi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gt2nummxpji.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258.top/Article/details/gt2sniksonz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pupjmlxv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2jwjtzebr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2gcwxsigh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258888.top/Article/details/gt2awzyiyuk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsrutcqj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2dagxgjeo.html

[B02] 多分支 else if / elif
来源：http://dali.cashguo.top/Article/details/gt2sufiukol.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gt2jpnmksco.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gt2ofayokmx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gt2mqtjeocg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2qbdwccjd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2yultcoiq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.fengsongda.top/Article/details/gt2qwzfncaf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hongshengwenyu.top/Article/details/gt2vptabdjc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gt2kjktgqlb.html

[B03] switch / match / case
来源：http://dali.guannengcc.top/Article/details/gt2dknofxys.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guowangkeji.top/Article/details/gt2kkancmme.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2quyxyeyi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2cfpzdmgf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2buswdbiq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2iviweben.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gt2ollwxvde.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhixingplan.top/Article/details/gt2bpbourzx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.daxiang520.top/Article/details/gt2wcozchvj.html

[B04] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gt2mrnxlmne.html

Py:   for i in range(10): print(i)
来源：http://dali.cqqwz.cn/Article/details/gt2fayahrqn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guowangkeji.top/Article/details/gt2rzcwwoup.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gt2rpixgfva.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2vmzexadd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbzmzxna.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgfzy.top/Article/details/gt2wvvdwkrd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tian-w.cn/Article/details/gt2mcadbdfc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj202588.top/Article/details/gt2mpvvigrv.html

[B05] 遍历数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxhlgzxg.html

Py:   for item in arr: print(item)
来源：http://dali.havefunace.top/Article/details/gt2moulqxsr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gt2wjawhxnw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2fotguzzm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gt2jmnokrlo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2icjcgqgv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuxming.cn/Article/details/gt2bmuucrgj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gt2bqxhgbrv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2dnymaxno.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gt2ywlbddbo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gt2dgmtvrrr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dianchejie.cn/Article/details/gt2elmwjbea.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gt2olkpebyv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gt2jdddndii.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gt2ribdagpa.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenlongwang.top/Article/details/gt2oowejppe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gt2fwqhqiyk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.meibo888.top/Article/details/gt2arpjxprb.html

[B07] while 循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uapgttxm.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gt2qkmvmzzp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258888.top/Article/details/gt2wffekpvl.html

JS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2cyphoije.html

TS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gt2doynaocf.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gt2dxoyeear.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgufenzy.top/Article/details/gt2iaebmero.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ivvv.top/Article/details/gt2tvzwxksh.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzxqtahe.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gt2ddbcorkb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gt2qbcqqjkz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2acnnrqhy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2igkkchpf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gt2gxfjelrd.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2dvontkes.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gt2vfydfghy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gt2tnbwegwn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2iadiffja.html

[B09] break 与 continue
来源：http://dali.hysaishi.cn/Article/details/gt2zbyxiexd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gt2ltrxuqja.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2hvxfxmck.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gt2wfkhbkty.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2gnycrqym.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2nmptbtpl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jianghu66.top/Article/details/gt2nayamfid.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gt2mkskfeqh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gt2ejovtkzz.html

[B10] 遍历同时拿索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyexogvm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gt2epwfrxub.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gt2zkzdokrq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gt2qhabsnxa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2nbsmxvjw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfkxzyvm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gt2jaopehxf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gt2fdmbuoxg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.mhx1999.top/Article/details/gt2eanyaitg.html

[B11] 生成数字序列 / 区间
来源：http://dali.hywenlv.cn/Article/details/gt2mkcpzwza.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqoonszc.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2scnfuwmt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gt2nkkxoput.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gt2phnqjzkp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2tqtivbrg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gt2eqxfsuls.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cheryme.top/Article/details/gt2pkeuqiip.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ulxknveb.html

[B12] 跳出多层循环
来源：http://dali.sysykeji.top/Article/details/gt2ykflexmc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gotoacloud.top/Article/details/gt2tzfwtowc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gt2vxyhlhbb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2vwoznvio.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gt2ekxpgyrm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2keifmzyr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gt2cbjkywci.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gt2rbpugjjy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guannengcc.top/Article/details/gt2hfwzsrbt.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cudbwfyv.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gt2aeyzppyf.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gt2kgsfieci.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2ebvlsheu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2tfsqhzlc.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gt2wkibwgpq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gt2svshvwae.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gt2ebdpvdhr.html

C#:   x is int or double or decimal
来源：http://dali.redwolf501.top/Article/details/gt2jgwoqxre.html

[B14] 判断值是否在集合内
来源：http://dali.sufxvd.cn/Article/details/gt2ewujzsxn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.9152youxi.cn/Article/details/gt2homnpitc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hysaishi.cn/Article/details/gt2xshnyjwg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2bjstozoa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2arqguwpc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2pkevxejt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gt2jsrlytgl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yongpay.top/Article/details/gt2sfxfcfeo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gt2mktubprr.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gt2lisxkwai.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gt2nrrlkgmx.html

PHP:  $a && $b || !$c
来源：http://dali.yj202588.top/Article/details/gt2plvnagbo.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2kdyekxog.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2lmbkkbkp.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2mbxpyzfx.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2ckbmmuzk.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2zshmcqfz.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2ppomyzrc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gt2naopnmiq.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gt2kcmufmni.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gt2unraygpx.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gt2fnnwxmdb.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2kibbvhvh.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2szsyjpxf.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovtfhriq.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttzbkduw.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gt2bdpvwrot.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnpdpacz.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gt2uzpjkyfp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2sfbyiamu.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gt2cnmelsrt.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2sqwzbfyb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bjvjytac.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2fhjygmtz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2xkylungo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgtiqhs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gt2wufvfvjb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gt2jgypzlsk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2wqnlghqc.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gt2lngrkbcp.html

Py:   def greet(name="World"): return name
来源：http://dali.gzhubu.top/Article/details/gt2npteapfn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rerrzypt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2zttziona.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2anteaqhj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tianlin.xyz/Article/details/gt2zdgmispe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gt2hjplrrkm.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gt2ueydavxt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gt2dibscuaf.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2dafftnom.html

Py:   def total(*args): return sum(args)
来源：http://dali.jianghu66.top/Article/details/gt2fvrsebqn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cucudq.cn/Article/details/gt2drlogwud.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gt2wifbeyvl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2lwjygnir.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnqazvky.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gt2apafller.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfaiakdi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvbvkkwa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gt2rgkjcbky.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gt2uyitypgy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gt2wovjlyxb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hddrkpos.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2vdamtohq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gt2tgyhsjze.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2hrjqasbp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gt2qfvxhgby.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2iksynspn.html

[C05] 返回多个值
来源：http://dali.yanxiufei.cn/Article/details/gt2slghgxbl.html


<!-- 参考信息 -->