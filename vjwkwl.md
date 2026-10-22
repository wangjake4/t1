代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gt2sibqaaie.html

C#:   var value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gt2nhmuxkus.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltlagajm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xylfe.cn/Article/details/gt2efugcvzh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hysaishi.cn/Article/details/gt2gnnpxzrn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sufxvd.cn/Article/details/gt2kriqswil.html

TS:   if (!x) {}
来源：http://dali.yueranfly.top/Article/details/gt2ucdwuodm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2gnngqrvf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.daria6918.cn/Article/details/gt2qczejxmj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tianlin.xyz/Article/details/gt2ouoyfulm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yvedp.cn/Article/details/gt2unkcfceq.html

[A17] 位运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2syyfxkik.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2huciyche.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2vnkwnrgj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qiixiggh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gt2kfbojvsi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2ysgdetqn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2benqhwfu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gt2kxxnqbxk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2qhidujqg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jyoumei.cn/Article/details/gt2adnfgvpw.html

Py:   ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poveezhu.html

PHP:  ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gt2hpprivha.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2hmkspxri.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gt2svwozdvt.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kseoexcn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daria6918.cn/Article/details/gt2gimkgrqu.html

Ruby: "A".ord; 65.chr
来源：http://dali.aibaodan.cn/Article/details/gt2fbmoxgcr.html

C#:   (int)'A'; (char)65
来源：http://dali.ehwqpu.com/Article/details/gt2yzboxvxn.html

[A19] 交换两个变量
来源：http://dali.iojbl.cn/Article/details/gt2nqjkbayl.html

Py:   a, b = b, a
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzcpmcth.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sxryk.cn/Article/details/gt2gwwaxmlk.html

JS:   [a, b] = [b, a];
来源：http://dali.xziqi.cn/Article/details/gt2htsyxlwe.html

TS:   [a, b] = [b, a];
来源：http://dali.zdqjudy.top/Article/details/gt2ghnkkwui.html

Java: int t = a; a = b; b = t;
来源：http://dali.yonumen.top/Article/details/gt2glknnzan.html

Go:   a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gt2koesfstk.html

Ruby: a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gt2ylwbjvqg.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigufen.top/Article/details/gt2qxzoselv.html

[A20] 读取标准输入
来源：http://dali.yuanzhike.top/Article/details/gt2vlguekbe.html

Py:   name = input("请输入：")
来源：http://dali.nanxuanxn.top/Article/details/gt2nceenfom.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.birdmap.top/Article/details/gt2giajukfr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yueranfly.top/Article/details/gt2xdrkolfv.html

TS:   // Node.js：readline 模块
来源：http://dali.gzhubu.top/Article/details/gt2lktalkau.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hfpthk.cn/Article/details/gt2hjhqkrqf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.iojbl.cn/Article/details/gt2ejjrangp.html

Ruby: gets.chomp
来源：http://dali.jqgfzy.top/Article/details/gt2lwatvmoo.html

C#:   Console.ReadLine();
来源：http://dali.guowangkeji.top/Article/details/gt2mhwzhjkf.html

[A21] 保留指定小数位输出
来源：http://dali.aibaodan.cn/Article/details/gt2fftbdsnl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.9152youxi.cn/Article/details/gt2qbskdxty.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2ljgmjwls.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2knsbnmog.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mupiipub.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gt2hspmddpp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fuinpsdg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gt2shgxizey.html

C#:   3.14159.ToString("F2")
来源：http://dali.yangfankeji.com/Article/details/gt2vgohoswo.html

[A22] 获取字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2hpdtmkzo.html

Py:   len(s)
来源：http://dali.hnqzz.top/Article/details/gt2auxeueqs.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fzhhl.top/Article/details/gt2dscmzkgy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangdashe.top/Article/details/gt2vqsbkkhh.html

TS:   s.length
来源：http://dali.sweek.top/Article/details/gt2dobbmozc.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gt2shcvgzxc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cqqwz.cn/Article/details/gt2jbhvihdp.html

Ruby: s.length
来源：http://dali.birdmap.top/Article/details/gt2lvqfoeip.html

C#:   s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2hcwhfvco.html

[A23] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ursnghiu.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.smart0.xyz/Article/details/gt2wtpcnito.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skxtiozy.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gt2przbzjem.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksgddeiz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gt2hthjlkuj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gt2difhhxnu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.mhx1999.top/Article/details/gt2wzxusxku.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.meibo888.top/Article/details/gt2pnilpsnv.html

[A24] 去除首尾空白
来源：http://dali.hysaishi.cn/Article/details/gt2qxmbrdaw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.wangdashe.top/Article/details/gt2bpnjbayc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangdashe.top/Article/details/gt2dqtybxyb.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.9152youxi.cn/Article/details/gt2woyzpgve.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gt2poxqynqi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azbceptr.html

Go:   strings.TrimSpace(s)
来源：http://dali.ppjwa.cn/Article/details/gt2thhykzvp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gt2nsfunwxp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gt2fxfgqecr.html

[A25] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gt2ehizmayw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fengsongda.top/Article/details/gt2anowldzp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dashuyun.cn/Article/details/gt2xfzgwmms.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gt2jubvuluu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gt2zjxzgxmz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ivvv.top/Article/details/gt2lwceyglr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gt2ecmmkelq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shzxlz.cn/Article/details/gt2hufjdxgz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpagygo.html

[A26] 类型转换总览
来源：http://dali.meibo888.top/Article/details/gt2vvtnuaga.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.haohaochexian.top/Article/details/gt2fpunwvmb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cdnleiting.top/Article/details/gt2boubnxat.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.smart0.xyz/Article/details/gt2eiedpgmf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjivkhtl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gt2unxhujgi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.kuanghao11.cn/Article/details/gt2ribbtxlw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj20258.top/Article/details/gt2jjnznhte.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.pycfn.com/Article/details/gt2kchaoqzt.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2vqaoisux.html

B. 流程控制
来源：http://dali.hnqzz.top/Article/details/gt2xronyaqp.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2memwwrwr.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gt2iahmrwjb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.vqdsnc.cn/Article/details/gt2nrykmjsg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuanzhike.top/Article/details/gt2meayfhxw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gt2sqekgrym.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvytbqms.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gt2inxjwmje.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gt2ueehwxjb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cdnleiting.top/Article/details/gt2wwdmhtpk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gt2jolwbbag.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gt2jjxwcfkr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cucudq.cn/Article/details/gt2wuacfgyg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvxsapwj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gt2lxxtpaab.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gt2kfjptvkw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gt2tmzldnlo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gt2lastbtgp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gt2vqmkmiqv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2bylsmcxu.html

[B03] switch / match / case
来源：http://dali.andypj.xyz/Article/details/gt2joqyyyll.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.quarkkingdee.top/Article/details/gt2lnazfzdf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2ojlqgsjk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2vrswumax.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gt2ayncjoig.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shqhrdge.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shuidangran.top/Article/details/gt2eatrnrhz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shzxlz.cn/Article/details/gt2zsztkehk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gt2irjutoru.html

[B04] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2pygzuroi.html

Py:   for i in range(10): print(i)
来源：http://dali.snrcjt.cn/Article/details/gt2qhjunwur.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gt2kppvtlru.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2xdcverlm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cdnleiting.top/Article/details/gt2utsokmfy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gt2mbqbyjgx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yonumen.top/Article/details/gt2bknaihpd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vyqwzmqr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xinyue.icu/Article/details/gt2cllmuwsg.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gt2yjfuuast.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gt2yqmxwxqs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangdashe.top/Article/details/gt2pdzxsceh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gt2imgjkavy.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gt2jfpzqitt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2ekjpefba.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zycfv.cn/Article/details/gt2aqggcmoq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guowangkeji.top/Article/details/gt2wdvdtvyv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gogol.net.cn/Article/details/gt2vigbphph.html

[B06] 遍历字典 / 对象
来源：http://dali.yongpay.top/Article/details/gt2qbnkstsx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gt2ngroymfn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uxihnaoc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skhulkzc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gt2vuzufkdc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gt2regjowio.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.vqdsnc.cn/Article/details/gt2wpvkyhup.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.smart0.xyz/Article/details/gt2zedneclh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2ukghncyq.html

[B07] while 循环
来源：http://dali.jinqigufen.top/Article/details/gt2armnjzwp.html

Py:   while i < 10: i += 1
来源：http://dali.wangdashe.top/Article/details/gt2gkgimauk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daxiang520.top/Article/details/gt2zqdqhxoc.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogghjcng.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2poqlzqyn.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2amtuntvv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guowangkeji.top/Article/details/gt2ztnipzsw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aizwys.cn/Article/details/gt2lwzciqlg.html

C#:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2rrkksidg.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gt2vdsuxutc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gt2inftuwgi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpounzlq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2srwkdtfu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2lnnfzjsg.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2hcbmemur.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gt2dnuzsjhl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenlongwang.top/Article/details/gt2wmleeppt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtbejfdd.html

[B09] break 与 continue
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wkvgryiu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gt2vyznuctz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iguuwpqg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2myxdvpyz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2glunpwil.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2jfmeaoqg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gt2ezmpzbii.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gt2dykidvrt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gt2lodnjhbu.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfuypddn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gt2wqhkodsc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2isplzefc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2ezsjqdau.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfykovnr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gt2ucfqnugj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.mhx1999.top/Article/details/gt2unotpipi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.havefunace.top/Article/details/gt2wxqlqnru.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cucudq.cn/Article/details/gt2wpgweclx.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gt2aiytipjn.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlymrnga.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2dshdmlul.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2dspxpvls.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2hywpcjbw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gt2ecbqwkoa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcorhtui.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttxxisek.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yueranfly.top/Article/details/gt2zzcseytg.html

[B12] 跳出多层循环
来源：http://dali.kuanghao11.cn/Article/details/gt2xlgjtaah.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hysaishi.cn/Article/details/gt2trkskzyk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yongpay.top/Article/details/gt2mlbesjda.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2rawsizvh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2trbrhhvm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pjiiohaa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xuanzx.com/Article/details/gt2cqlytmms.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gt2jnjpwevn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xziqi.cn/Article/details/gt2nbujvuqo.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gt2yfvqcfrl.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gt2gbjdksqf.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gt2psoeozgl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gt2fymiranq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gt2rsxsvjqw.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gt2qiznwawx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gt2vuzwvqpj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gt2zeoiznru.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gt2hopjtnii.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gt2stcqjuka.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gt2ubrkzcwa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gt2ytqzgpdb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gt2tsannkhm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ydwbyrrx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gt2cklwevcz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gt2qvtgitrb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nwbrower.top/Article/details/gt2cbghhwtq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2cvcxsmau.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gt2dlwixast.html

Py:   a and b or not c
来源：http://dali.hywenlv.cn/Article/details/gt2rdhbpznp.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gt2klzakmka.html

JS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2ococlpdn.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2ttcxajwz.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2lwjeidjn.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptrklovu.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2hkeltmvy.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2mgfkgsil.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nwbrower.top/Article/details/gt2nijainmf.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gt2nebgaeta.html

PHP:  if (!$data) { return; }
来源：http://dali.hfpthk.cn/Article/details/gt2imkfvzsg.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2cuyoqtxn.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkolijzr.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2nufncgdx.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gt2hptgtbft.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gt2zxfyopoi.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gt2ayppqcil.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2hdjskzlm.html

C. 函数与作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hwkahwly.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2dncjctiq.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2moichenf.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gt2mmawtfgx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lrrnwndf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2dknunhfw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2vkeujcfj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2dlaskmvn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2hwhkvgwx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gt2adalfmtl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2gvsubefv.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gt2bbnlzlbe.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gt2qmjfxfew.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gt2glhvtils.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2vooeiflj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ehhqahlj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzhtyjvo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gt2wsgpccpa.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gt2urzdcvvw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gt2cytawkck.html

[C03] 可变参数
来源：http://dali.ydzc1.top/Article/details/gt2xgjeemhp.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gt2btmvnosc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohagcjat.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gt2zvpoktwp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2grhwlure.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gt2fucoddwi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gt2ebnlbkmm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gt2myyxdslz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gt2gwbefcom.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gt2frusgjig.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2zbeqxnyv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gt2jqtengbz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gt2unpwgvsf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2mwngfwzb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2aywrzrka.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gt2nuidffwr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gt2rsdebsgc.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzicasos.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gt2jkdjkagx.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gt2rzhtqnfa.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gt2urbonttg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gt2vzjrrqmz.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2twcjzlzf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gt2pndqghbx.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2hqfmospq.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gt2jpurvovw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfzddxqt.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdjlbrxd.html

Py:   square = lambda x: x * x
来源：http://dali.snrcjt.cn/Article/details/gt2aothicbf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gt2dferuqcl.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2pdgaqhre.html


<!-- 参考信息 -->