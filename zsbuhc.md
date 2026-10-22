代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtdviikhdz.html

[A15] 空值判断与默认值
来源：http://dali.hnqzz.top/Article/details/gtyyjtyvbf.html

Py:   value = data or "默认值"
来源：http://dali.cdnleiting.top/Article/details/gthhnstbax.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtdhfsvesg.html

JS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtbfzrrbpz.html

TS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gttawtotlm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenzaomai.com/Article/details/gtdymqgvkq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgufenzy.top/Article/details/gtepgcxxgz.html

Ruby: value = data || "默认值"
来源：http://dali.jqgufenzy.top/Article/details/gtpbejivao.html

C#:   var value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtninnnsfk.html

[A16] 真假值判断规则
来源：http://dali.gaohongyu789.top/Article/details/gtwzjruaiq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tian-w.cn/Article/details/gtpwzbicsw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinqigfzy.top/Article/details/gtsgduzzph.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.meibo888.top/Article/details/gtpnxejapd.html

TS:   if (!x) {}
来源：http://dali.yj20258888.top/Article/details/gtmzpbpgyo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.bjfxy.top/Article/details/gtvwsloioa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenzaomai.com/Article/details/gtfdqtplyw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jlsjyb.cn/Article/details/gtkjygkhjh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daxiang520.top/Article/details/gtmkbzhwnm.html

[A17] 位运算
来源：http://dali.haohaochexian.top/Article/details/gttobavxyk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtagtavyxc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtrfdcfuqj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtfjldhiig.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtzgsqzpqa.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtixzvrgdp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtoukbpiys.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtxlaflhwg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtflwpkcvb.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenzaomai.com/Article/details/gtiymavjoh.html

Py:   ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gtcistvyyu.html

PHP:  ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gtpwsjgqgs.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aibaodan.cn/Article/details/gtjjwjccmt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hysaishi.cn/Article/details/gtozwwmbqt.html

Java: (int) 'A'; (char) 65
来源：http://dali.feifeiyinyue.top/Article/details/gtycpjcuyo.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hongshengwenyu.top/Article/details/gtaoymeord.html

Ruby: "A".ord; 65.chr
来源：http://dali.aibaodan.cn/Article/details/gtsalbccqu.html

C#:   (int)'A'; (char)65
来源：http://dali.sysykeji.top/Article/details/gticfsckid.html

[A19] 交换两个变量
来源：http://dali.daxiang520.top/Article/details/gtxpthxrag.html

Py:   a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gtfrglckpn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tian-w.cn/Article/details/gtoowgwjzv.html

JS:   [a, b] = [b, a];
来源：http://dali.dashuyun.cn/Article/details/gtixfhayjg.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtmxptqwcc.html

Java: int t = a; a = b; b = t;
来源：http://dali.sysykeji.top/Article/details/gtxwoplido.html

Go:   a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtfsptnkkf.html

Ruby: a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtwzfbotcv.html

C#:   (a, b) = (b, a);
来源：http://dali.redwolf501.top/Article/details/gtvyfvarwd.html

[A20] 读取标准输入
来源：http://dali.aizwys.cn/Article/details/gttjhsaubz.html

Py:   name = input("请输入：")
来源：http://dali.shzxlz.cn/Article/details/gtahopacem.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.iojbl.cn/Article/details/gtmpfwerfs.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.quarkkingdee.top/Article/details/gtfzeaskmm.html

TS:   // Node.js：readline 模块
来源：http://dali.cqqwz.cn/Article/details/gtcmjcxzxn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhiwuduotai.top/Article/details/gtjbficmfa.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykynalzm.html

Ruby: gets.chomp
来源：http://dali.redwolf501.top/Article/details/gtsksodufx.html

C#:   Console.ReadLine();
来源：http://dali.shangyingyoupin.top/Article/details/gtdewxkjpl.html

[A21] 保留指定小数位输出
来源：http://dali.hnqzz.top/Article/details/gtrnmkwtuu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.9152youxi.cn/Article/details/gtkhmyetag.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gtkwdoyqax.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtgqumplzw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtyycnjynz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtybbbfekw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtalpjaiga.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtmvqgcccb.html

C#:   3.14159.ToString("F2")
来源：http://dali.vqdsnc.cn/Article/details/gtoevdewjn.html

[A22] 获取字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtpdamvddh.html

Py:   len(s)
来源：http://dali.yuxming.cn/Article/details/gtojzluvhf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhoulong.xyz/Article/details/gtbiqsmvmb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ehwqpu.com/Article/details/gtwamezcve.html

TS:   s.length
来源：http://dali.nanxinkj.top/Article/details/gtwjmpprwo.html

Java: s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtxeogfslz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.pycfn.com/Article/details/gtvzrzkvrv.html

Ruby: s.length
来源：http://dali.smart0.xyz/Article/details/gtqgmcidrk.html

C#:   s.Length
来源：http://dali.meibo888.top/Article/details/gtpjvacrqb.html

[A23] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gthiajwasv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yangfankeji.com/Article/details/gtcgzpxgqv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cucudq.cn/Article/details/gtwggqvlpp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gtiwurpttd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdxuocqa.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gthrilseia.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidyzusfo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtsifzpzzb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guowangkeji.top/Article/details/gtmhlzalkh.html

[A24] 去除首尾空白
来源：http://dali.jinqigfzy.top/Article/details/gtowtytvzl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtzihgzpsu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.quarkkingdee.top/Article/details/gtyfpzszro.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtocxspxcp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gtxjefdphd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cdnleiting.top/Article/details/gtqhunxxpi.html

Go:   strings.TrimSpace(s)
来源：http://dali.cheryme.top/Article/details/gtupfwcomr.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gtpzimosow.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.daria6918.cn/Article/details/gtnrsfxcmh.html

[A25] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtmwndrkno.html

Py:   s1 == s2; s1 != s2
来源：http://dali.iojbl.cn/Article/details/gthxcinbhj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhongyouzk.top/Article/details/gtfmgxqdqe.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtuhcctiot.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtwipjdlts.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gttphtcobi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbepkiemm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenlongwang.top/Article/details/gtjweoigrp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtuxiubkpz.html

[A26] 类型转换总览
来源：http://dali.xuanzx.com/Article/details/gttdqkdwfm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hywenlv.cn/Article/details/gttygkwmac.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yonumen.top/Article/details/gtubzgutri.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zdqjudy.top/Article/details/gtpkixkqcd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cdnleiting.top/Article/details/gtzgakgrbz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtmchjrjee.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxuanxn.top/Article/details/gtvkotrsdb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gotoacloud.top/Article/details/gtiaogxjxs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtcmrpndmv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtegpkenzg.html

B. 流程控制
来源：http://dali.guannengcc.top/Article/details/gtujaymeas.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjgwealek.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gtjkxgiimo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtrazeqhzf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gtsbkuzbwo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gtmcazsvcu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtawagaymj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtpdqcnoam.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fengsongda.top/Article/details/gthtlmzzxi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fengsongda.top/Article/details/gtwbylynhv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtgkcgqoxq.html

[B02] 多分支 else if / elif
来源：http://dali.dianchejie.cn/Article/details/gtfceecwqz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shuidangran.top/Article/details/gtjushlfoq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.0kj1m.cn/Article/details/gtfhijdbal.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtfoxvoryj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtepofiwst.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gturyzwujo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxuanxn.top/Article/details/gtzaezihht.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dianchejie.cn/Article/details/gtplarxbkr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtcggvytmm.html

[B03] switch / match / case
来源：http://dali.fzhhl.top/Article/details/gtknrtwzoq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtpevqlisa.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyixwxdgy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtzhtxhagq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtmcmlvxxe.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtierywaiq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.iojbl.cn/Article/details/gtcvngeeae.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangshuangyany.cn/Article/details/gtjyoztscm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtzdqvdsfb.html

[B04] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtadpspwhf.html

Py:   for i in range(10): print(i)
来源：http://dali.yanxiufei.cn/Article/details/gtallujkvl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gtpixsnztc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtgfuxjzda.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gtakpwgpfl.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zycfv.cn/Article/details/gthbnxvqpc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.meibo888.top/Article/details/gtlrqumkoi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gtdfihfyku.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuxming.cn/Article/details/gtoxariirk.html

[B05] 遍历数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtbredswds.html

Py:   for item in arr: print(item)
来源：http://dali.gogol.net.cn/Article/details/gtxoacgphm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnxiangtu.top/Article/details/gtrtqgeadg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdizzzrbr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gtevltcfvv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbeowwrew.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yongpay.top/Article/details/gtfgaqhmso.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gtwifjbthz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gtcxiaqkui.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzakajepm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hysaishi.cn/Article/details/gtzkxhmmtf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gotoacloud.top/Article/details/gtlmavcovt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gtduuidgqs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtlvglfdkt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.meibo888.top/Article/details/gtbrsvzxmo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gtcdjivkue.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cqqwz.cn/Article/details/gttbaalkyz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gttcfnjguf.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gtgtskqcui.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gtdeaxjzki.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hfpthk.cn/Article/details/gtnmzupgnx.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtznxoetjb.html

TS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtdtvkvnjc.html

Java: while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtmnctcvtr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gttlbaumdt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daria6918.cn/Article/details/gthjtlvcnh.html

C#:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtxbntiphd.html

[B08] do-while（至少执行一次）
来源：http://dali.ydzc1.top/Article/details/gtjpgsmuci.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdagzhsm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtpojnjydt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtxnufrvph.html

TS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtbyusgvdv.html

Java: do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtaayfgawz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yueranfly.top/Article/details/gtdchqedkz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gtnkhcmnhe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtrirguviz.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtslmqmrcj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gtfjqpeugb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtwipzzwoy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtzljqkkqo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtasenwalh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtetivbsrd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gthqeqkdza.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gtkxhiwkvc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtmewfxrzo.html

[B10] 遍历同时拿索引
来源：http://dali.cashguo.top/Article/details/gtsqcxtoeh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gtdguixfst.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xylfe.cn/Article/details/gtpmaebzuw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gthobzwyqi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwscascl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yanxiufei.cn/Article/details/gthozceyyk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gtmxkgmahy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.vqdsnc.cn/Article/details/gtoudawuic.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtlgsraobv.html

[B11] 生成数字序列 / 区间
来源：http://dali.yanxiufei.cn/Article/details/gtecjakjlv.html

Py:   list(range(0, 10, 2))
来源：http://dali.xuanzx.com/Article/details/gtwrxoohfo.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtlicvmubp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtyilllbjs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtqfsjazmw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gtnlirkkdb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gtywgbccdp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtipwthgbz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuanzhike.top/Article/details/gtaqzvcroo.html

[B12] 跳出多层循环
来源：http://dali.c1oappe.top/Article/details/gtlcwyeyyz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zycfv.cn/Article/details/gtedkdouch.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gtawjjssoz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtwzoauptz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtulahgviz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigwnblpm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ybcxt.top/Article/details/gtmtwfgqxk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cashguo.top/Article/details/gtunyokzny.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gtyjljvfje.html

[B13] 判断是否为数字
来源：http://dali.jqgufenzy.top/Article/details/gtxvgkkudj.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gtqxfxcwpi.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gtrinkmbix.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtqgdkcojv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtgiqwgyfl.html

Java: x instanceof Number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywjutccc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gtpozcylsp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yongpay.top/Article/details/gtubbjrnmq.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gtqwbgopsq.html

[B14] 判断值是否在集合内
来源：http://dali.snrcjt.cn/Article/details/gtyizmqbvi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtnytlxncl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtdrapmbkq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtbvlucyse.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtaaontfcl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtkwsadfym.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtriycdwsl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gthphrskqh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtmchfuctt.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtiwjddmhh.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtqgxaqftd.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gtjhigancx.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtwpaaondd.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gthevlczmi.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtkequqmzg.html

Go:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtoaoyvgwe.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtrthhqtkk.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtgnbydpvc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dashuyun.cn/Article/details/gtzkxavunh.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtkmpwbvgj.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtlkjhpzsi.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gthzwgcrfl.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtvkqepizr.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtgqmbtyiu.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtyumpqooe.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtbelexqfv.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtqpxaxicl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzxxczedo.html

C. 函数与作用域
来源：http://dali.yuxming.cn/Article/details/gtnntivvmu.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtpuggpvcm.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtuyhumrot.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtlvflibkm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtazqtxfjc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtqncqonmy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtadjgvfch.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtewqjaacy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtxlnxijkz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtghriycio.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtorvybcmz.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gtjprgrmbq.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtzbmybweu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtudbruqyt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtiukgdqhf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtkrytcpqc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtkgicggbd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtmkckeopv.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gtpdwxrivb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gtacyggoxt.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gttiggjrmq.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gtfzvdqdxk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jianghu66.top/Article/details/gtficygwis.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtwkttoljj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtbwhgzubo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gtccopfnyz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gtwmbeighj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtsarqnvwp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gtexkskjus.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gtsgsdgddq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtfmkjsnuq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gtaufnfysb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gticljtifh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtczrjcjde.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtsijgmgxt.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gtnsbxsfcl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiluydfb.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtmrneqssf.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gtwjhrtpvz.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtidxhkvdj.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtrkjzjxoq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtahgfuenb.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtuamrbveu.html


<!-- 参考信息 -->