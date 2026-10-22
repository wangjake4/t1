代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gt2rkqzvebq.html

TS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gt2drewvgsz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daxiang520.top/Article/details/gt2ovauhymv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xziqi.cn/Article/details/gt2jujtrkia.html

Ruby: value = data || "默认值"
来源：http://dali.yuanzhike.top/Article/details/gt2cekhrupk.html

C#:   var value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sboheccx.html

[A16] 真假值判断规则
来源：http://dali.birdmap.top/Article/details/gt2liankklc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yuxming.cn/Article/details/gt2gnibqlzw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.wangdashe.top/Article/details/gt2pkxyyeuc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pqmdzebc.html

TS:   if (!x) {}
来源：http://dali.cqqwz.cn/Article/details/gt2dvehjsvx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2macinqlu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vayohphq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuanzhike.top/Article/details/gt2zdbjepam.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2eoijholg.html

[A17] 位运算
来源：http://dali.gogol.net.cn/Article/details/gt2bathtrxp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2hbbvosne.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2xxddnelk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2nhuizobh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gt2ongturkm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnghzrwc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2oyfyrqbx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2amkcoqot.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2krcwmuie.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jiagoushi.top/Article/details/gt2bfvonfnv.html

Py:   ord("A"); chr(65)
来源：http://dali.zdqjudy.top/Article/details/gt2tdaqblnj.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuanzx.com/Article/details/gt2wgdgywpb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cqqwz.cn/Article/details/gt2sgzrvtiv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hongshengwenyu.top/Article/details/gt2htccehky.html

Java: (int) 'A'; (char) 65
来源：http://dali.0kj1m.cn/Article/details/gt2imsedyqt.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gaohongyu789.top/Article/details/gt2zqqkcsqd.html

Ruby: "A".ord; 65.chr
来源：http://dali.0kj1m.cn/Article/details/gt2txfqrwqz.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gt2tktgywer.html

[A19] 交换两个变量
来源：http://dali.hysaishi.cn/Article/details/gt2gcvmeyri.html

Py:   a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gt2cjofncbx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.kuanghao11.cn/Article/details/gt2uypcaqsx.html

JS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gt2fmeendvm.html

TS:   [a, b] = [b, a];
来源：http://dali.chenjidiqi.icu/Article/details/gt2ewpfdcpv.html

Java: int t = a; a = b; b = t;
来源：http://dali.yuxming.cn/Article/details/gt2ufazxtwb.html

Go:   a, b = b, a
来源：http://dali.zdqjudy.top/Article/details/gt2sqhtoahg.html

Ruby: a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gt2ziilnyav.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gt2qkkzdusi.html

[A20] 读取标准输入
来源：http://dali.gaohongyu789.top/Article/details/gt2xcebrmur.html

Py:   name = input("请输入：")
来源：http://dali.fengsongda.top/Article/details/gt2mugesqkc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhongyouzk.top/Article/details/gt2tjufeyla.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2biuzfolx.html

TS:   // Node.js：readline 模块
来源：http://dali.mhx1999.top/Article/details/gt2umtjlsbi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yanxiufei.cn/Article/details/gt2cxvbjahc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.c1oappe.top/Article/details/gt2ecbngwst.html

Ruby: gets.chomp
来源：http://dali.tianlin.xyz/Article/details/gt2qrawpjtj.html

C#:   Console.ReadLine();
来源：http://dali.quarkkingdee.top/Article/details/gt2qzolfuex.html

[A21] 保留指定小数位输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2zzstqdbd.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhengqikj.top/Article/details/gt2tkcpqund.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uppbastc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gt2lfjynkld.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gt2knxldhyb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gt2lrkvpbby.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gt2uhmkwaxf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gt2wotsjekd.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhixingplan.top/Article/details/gt2vqpguqmf.html

[A22] 获取字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owmkrqgr.html

Py:   len(s)
来源：http://dali.mhx1999.top/Article/details/gt2gemgmeml.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gogol.net.cn/Article/details/gt2xmawvfff.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gotoacloud.top/Article/details/gt2tueoygdt.html

TS:   s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbngfrdu.html

Java: s.length()
来源：http://dali.tian-w.cn/Article/details/gt2wajyazsk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2kmuizivd.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gt2zgpyvqex.html

C#:   s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjiixhbm.html

[A23] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gt2jktvcqbz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yongpay.top/Article/details/gt2mwofmdvu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jlsjyb.cn/Article/details/gt2fgvcnmgr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gt2njnmdjbl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hammf.cn/Article/details/gt2pzvmajhp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gt2zfgfqvsj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zdqjudy.top/Article/details/gt2qgzqpeko.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrsyjrhu.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shuidangran.top/Article/details/gt2aehdueqh.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gt2rgpugmco.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgfzy.top/Article/details/gt2zqurmgjk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkwehrks.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenzaomai.com/Article/details/gt2sugctfqi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.bjfxy.top/Article/details/gt2oyncryjo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gt2sllmhwrw.html

Go:   strings.TrimSpace(s)
来源：http://dali.haohaochexian.top/Article/details/gt2stvhvovn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gt2yjsajrpo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umxllanv.html

[A25] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2qvvlkxia.html

Py:   s1 == s2; s1 != s2
来源：http://dali.svipenyu.cn/Article/details/gt2yfrbmuzd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.haohaochexian.top/Article/details/gt2lmizwyqf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gt2wgqbfwwn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aibaodan.cn/Article/details/gt2llqatezr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuanzhike.top/Article/details/gt2htoapfnw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2xafzvwba.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.daxiang520.top/Article/details/gt2utvdmqln.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gt2fkjoxzlk.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umiddaot.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.dianchejie.cn/Article/details/gt2azdfsjfo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shangyingyoupin.top/Article/details/gt2noyopgzr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yanxiufei.cn/Article/details/gt2ddkyuzrq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daria6918.cn/Article/details/gt2zjuhemol.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gt2sdmaddcc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj202588.top/Article/details/gt2bmfsoodj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceyqhnsy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gt2ggebzmmc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2tdhpxxqo.html

B. 流程控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykbfmqvg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2lbocyeff.html

[B01] 条件判断 if / else
来源：http://dali.yonumen.top/Article/details/gt2lwiuifnh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.svipenyu.cn/Article/details/gt2lazmfeaq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.bjfxy.top/Article/details/gt2rbcsokwg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2gtbxadgh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2xetplcuv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gt2jnkivuov.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yajuzctc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.quarkkingdee.top/Article/details/gt2elheweck.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gt2ltlxyugc.html

[B02] 多分支 else if / elif
来源：http://dali.guannengcc.top/Article/details/gt2icqgxros.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gt2hlofpnjl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zycfv.cn/Article/details/gt2plrhsdck.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gt2xqmajftx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gt2ghvcllqm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gt2lmcgwoxd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.birdmap.top/Article/details/gt2yztqgzgf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenlongwang.top/Article/details/gt2tfscjctv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2hgzqbslm.html

[B03] switch / match / case
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgfuknvw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ehwqpu.com/Article/details/gt2fpfjdwjw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2duzqgwrm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mvfrggdw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2eufoialh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2bwlekxxx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gt2wjvgpnjd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gt2jcqfwdvn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gt2wufbgxsp.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2tmhdlnna.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gt2ukqomcvt.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gt2vsnaafsh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gt2byndwtsj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gt2vewzxtze.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.mhx1999.top/Article/details/gt2ehhwbgic.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jianghu66.top/Article/details/gt2cequcryo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.bjfxy.top/Article/details/gt2yxyoojsh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gt2gxipdxwu.html

[B05] 遍历数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2uxvudhku.html

Py:   for item in arr: print(item)
来源：http://dali.jqgufenzy.top/Article/details/gt2fuzbdegt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hfpthk.cn/Article/details/gt2urjgjliw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2egozcyso.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gt2zwjurcof.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxbbtimv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gt2bzfzdamg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gotoacloud.top/Article/details/gt2zhenkyfu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2vmdaefex.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gt2jdobkeqm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jiigbvzt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hammf.cn/Article/details/gt2jkjcnoiu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsvhnvtc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gt2jrqpmrxx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cqqwz.cn/Article/details/gt2btnijazo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jiagoushi.top/Article/details/gt2hhfupskm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnuwcfdk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxfpsvoo.html

[B07] while 循环
来源：http://dali.yangfankeji.com/Article/details/gt2ahuvrijt.html

Py:   while i < 10: i += 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzlyftbx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gt2cldoxfqr.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2tzrcdykx.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gt2kjvluery.html

Java: while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bwiynabj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gt2icdxsthy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuanzx.com/Article/details/gt2olmteosg.html

C#:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2ockzcndk.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gt2sslavpmc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vczmuqnf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjxdhrei.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2zpvqcnss.html

TS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2ypkoeluz.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2fswbbxnu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.vqdsnc.cn/Article/details/gt2irrffguq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.316326.xyz/Article/details/gt2qvsiojmq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gt2kumzktwm.html

[B09] break 与 continue
来源：http://dali.nwbrower.top/Article/details/gt2oyxilofc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftarwial.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2thcmfrty.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gt2ongywfsp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2uplagcgz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2ixlgzumx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gt2snznzwwi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gt2keqfqdbm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2zglylest.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gt2hbypfnuo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gt2gdpjqaks.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tdyqeldk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gt2iylieihq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gt2rpgnoqsf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxinkj.top/Article/details/gt2jnvushcv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shuidangran.top/Article/details/gt2uphkdelk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gt2dxsnqhpm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daria6918.cn/Article/details/gt2zjbissnh.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gt2wctfiday.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvqwvbir.html

PHP:  range(0, 10, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2okaonfsq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2btlbnnki.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2zujrgqcf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hysaishi.cn/Article/details/gt2bfpdqttl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gt2ldmqjozl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epptdmst.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yanxiufei.cn/Article/details/gt2lkejwcsz.html

[B12] 跳出多层循环
来源：http://dali.yongpay.top/Article/details/gt2nohsadij.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gt2apkfuspj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gt2oqhhxehb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gt2ezdvbkkn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gt2dilrzntm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjlixcdu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gt2beyuoqrx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gt2pxejlcze.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gt2duxsdhil.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gt2hexjjeck.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gt2yfzhlnlg.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gt2ltuahzgv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gt2onwrsgpl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jeeswgyg.html

Java: x instanceof Number
来源：http://dali.chenzaomai.com/Article/details/gt2ojmyznjq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gt2skqxgshs.html

Ruby: x.is_a?(Numeric)
来源：http://dali.kuanghao11.cn/Article/details/gt2nbtgroxa.html

C#:   x is int or double or decimal
来源：http://dali.smart0.xyz/Article/details/gt2olsssjft.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gt2jtapijsj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sxryk.cn/Article/details/gt2lszxasmb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gt2fzizvrsl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2pmewnctk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2ditsfygf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2fsonylkl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gt2vtcnxzxx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2tlfcvyrp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2bgbxzoja.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gt2peclsele.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gt2kjqyhcis.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gt2jgrixhug.html

JS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2cikgbenu.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2rnuvghnw.html

Java: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwogrbqt.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2aeoebzoj.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2uflswkye.html

C#:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2yxtvruij.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gt2ijgicnih.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjtsztfs.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gt2lbigdtgh.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2obryingf.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gt2fvbhkcdq.html

Java: if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gt2mgwhleac.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gt2mwvbkayf.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gt2oxsgkumn.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2olivjvtc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gpggqjxy.html

C. 函数与作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjpjamxm.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2qqozsbog.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2wwamxbpc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmikfbui.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2lwmmxcem.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2iirkviyr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2xovmjije.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2awcqvmew.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.kuanghao11.cn/Article/details/gt2frntgzfc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aphheokt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2xoerjjpm.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2jzljguxt.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gt2qrwvlowd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnqzz.top/Article/details/gt2esxagsea.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2yucvelhn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2ywxpdidm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gt2abtetvhe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gt2dacjyrlx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zdqjudy.top/Article/details/gt2khtemhyu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigufen.top/Article/details/gt2dsfijuph.html

[C03] 可变参数
来源：http://dali.ydzc1.top/Article/details/gt2hzdjnoan.html

Py:   def total(*args): return sum(args)
来源：http://dali.pycfn.com/Article/details/gt2rxedahxy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gt2wyxmauwi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gt2uqhzsqbd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2uvedeydc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gt2srxsixbm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gt2obvfphjr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gt2xrbhlhkj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gebiyfyz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gt2wqvlgyah.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gt2shghbdea.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2goxzjgkd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2qpfjysiv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daxiang520.top/Article/details/gt2wosbncjw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gt2tecabtck.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2yiigxavw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gt2nkhayigy.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2qkxitmqf.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2yaukzgku.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojyklgty.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gt2yndxmepz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2iggmwhre.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmuujtiu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gt2hxzfsjgg.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2jylyuzfm.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gt2pkkujrcd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gt2rooulsex.html


<!-- 参考信息 -->