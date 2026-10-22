代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gt2zyztzyea.html

TS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gt2ktcnpafs.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.vqdsnc.cn/Article/details/gt2zxjwysbe.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sysykeji.top/Article/details/gt2hhvngltn.html

Ruby: value = data || "默认值"
来源：http://dali.shuidangran.top/Article/details/gt2etzbjdig.html

C#:   var value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gt2fsmalnps.html

[A16] 真假值判断规则
来源：http://dali.yj20258888.top/Article/details/gt2bkikjufj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2smmmnsfs.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.iojbl.cn/Article/details/gt2isuidkun.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hywenlv.cn/Article/details/gt2wchfzmtm.html

TS:   if (!x) {}
来源：http://dali.gzhubu.top/Article/details/gt2jabeirxn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmfuhloe.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj20258.top/Article/details/gt2rhbvxvje.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ybcxt.top/Article/details/gt2umcqnrrb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2uabzkogg.html

[A17] 位运算
来源：http://dali.jqgufenzy.top/Article/details/gt2rowednoe.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2fdciazwe.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2zyhnjerk.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gt2zahbsuft.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2pjrxtxfb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2eanthaft.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2tfriyiii.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2ozplwlma.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2tjoicpwr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hysaishi.cn/Article/details/gt2fkldowyk.html

Py:   ord("A"); chr(65)
来源：http://dali.jianghu66.top/Article/details/gt2thjdaooe.html

PHP:  ord("A"); chr(65)
来源：http://dali.fzhhl.top/Article/details/gt2hoebmudg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gt2usqhtnro.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gt2ksdeibnt.html

Java: (int) 'A'; (char) 65
来源：http://dali.ehwqpu.com/Article/details/gt2wtzttiuc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.redwolf501.top/Article/details/gt2zmbnagvm.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangdashe.top/Article/details/gt2tikslryn.html

C#:   (int)'A'; (char)65
来源：http://dali.shzxlz.cn/Article/details/gt2sfvbvpfz.html

[A19] 交换两个变量
来源：http://dali.gaohongyu789.top/Article/details/gt2huxysqbm.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gt2quuxhlov.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycvevkqu.html

JS:   [a, b] = [b, a];
来源：http://dali.yangfankeji.com/Article/details/gt2eiuzucxd.html

TS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gt2vakwirbj.html

Java: int t = a; a = b; b = t;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osjugxil.html

Go:   a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gt2brgoqrbn.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2nusbajtm.html

C#:   (a, b) = (b, a);
来源：http://dali.iojbl.cn/Article/details/gt2vrxwsywg.html

[A20] 读取标准输入
来源：http://dali.hnxiangtu.top/Article/details/gt2ydmakxcw.html

Py:   name = input("请输入：")
来源：http://dali.jianghu66.top/Article/details/gt2rejceoyv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenzaomai.com/Article/details/gt2sbmafuwe.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.9152youxi.cn/Article/details/gt2aiptshgb.html

TS:   // Node.js：readline 模块
来源：http://dali.0kj1m.cn/Article/details/gt2zjnbbnoy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.snrcjt.cn/Article/details/gt2gdujbuyb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jiagoushi.top/Article/details/gt2arkhmitv.html

Ruby: gets.chomp
来源：http://dali.hnxiangtu.top/Article/details/gt2lozzvpxa.html

C#:   Console.ReadLine();
来源：http://dali.xziqi.cn/Article/details/gt2saarbsvm.html

[A21] 保留指定小数位输出
来源：http://dali.cashguo.top/Article/details/gt2znkshfjb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yuxming.cn/Article/details/gt2ibipukzs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gt2xrraxzyi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2miiwvkkg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gt2quqzfuyd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gt2pvqmugwm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gt2alhpfoqx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdbidrjd.html

C#:   3.14159.ToString("F2")
来源：http://dali.yueranfly.top/Article/details/gt2qzaoitrp.html

[A22] 获取字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2knifwutw.html

Py:   len(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ztaxozgi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2odahvtsd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aibaodan.cn/Article/details/gt2zhwondwn.html

TS:   s.length
来源：http://dali.yangfankeji.com/Article/details/gt2bhszlacq.html

Java: s.length()
来源：http://dali.yuxming.cn/Article/details/gt2jeiqnhrk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenlongwang.top/Article/details/gt2seinxbod.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gt2hjpatzkr.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gt2jjbbbavn.html

[A23] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gt2oaaejprp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yvedp.cn/Article/details/gt2rxnrtrgo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yueranfly.top/Article/details/gt2rswuqshr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxtvelqw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gt2zaymamui.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.0kj1m.cn/Article/details/gt2pbplpsyh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxinkj.top/Article/details/gt2hwqeswcy.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nwbrower.top/Article/details/gt2cxgiqpxb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxxdjbbv.html

[A24] 去除首尾空白
来源：http://dali.birdmap.top/Article/details/gt2uzyldytc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gt2zrrqhsll.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gt2wkagjags.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2elnggzbk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuanzx.com/Article/details/gt2uvlyydcp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gt2gcoqrwxc.html

Go:   strings.TrimSpace(s)
来源：http://dali.ydzc1.top/Article/details/gt2djefpqrw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.c1oappe.top/Article/details/gt2yfhrlokn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyjdheb.html

[A25] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2bmudlegd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuanzx.com/Article/details/gt2meiuhwif.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shzxlz.cn/Article/details/gt2maujjnye.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gt2rsojgnsg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xinyue.icu/Article/details/gt2vjcqzrhm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2prkjulgk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gotoacloud.top/Article/details/gt2leqnfxgj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangdashe.top/Article/details/gt2ixhjpzvz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gt2tvjaspdd.html

[A26] 类型转换总览
来源：http://dali.jyoumei.cn/Article/details/gt2techsrat.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ppfyevzv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhiwuduotai.top/Article/details/gt2japmsuin.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shzxlz.cn/Article/details/gt2qpmnkslj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yueranfly.top/Article/details/gt2hvaynvwj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj202588.top/Article/details/gt2tymokbgo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.birdmap.top/Article/details/gt2wamrbocj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.dashuyun.cn/Article/details/gt2tiihripd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tanke756.top/Article/details/gt2mjginpod.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrbmsoca.html

B. 流程控制
来源：http://dali.guannengcc.top/Article/details/gt2hoddvgcd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ldlclqbe.html

[B01] 条件判断 if / else
来源：http://dali.nwbrower.top/Article/details/gt2deuvshkd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrsylrpx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hfpthk.cn/Article/details/gt2ntfoyjmq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gt2lzrjnkps.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2quojzoqg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gt2oystcrjl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258.top/Article/details/gt2nzxuxzka.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yongpay.top/Article/details/gt2jrncdvvy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2guxmokux.html

[B02] 多分支 else if / elif
来源：http://dali.tianlin.xyz/Article/details/gt2hchmhjga.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gt2namwveme.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tbhotdft.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gt2gqwffbpb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gt2uyocdzvy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2chztbbbi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.vqdsnc.cn/Article/details/gt2mcalpcwc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj202588.top/Article/details/gt2ujmhhkwy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2gupixdyu.html

[B03] switch / match / case
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryqbudyl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuanzx.com/Article/details/gt2qgdiybof.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2llrnveeb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2smbkaetz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gt2wlzlkacn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gt2ekhpodbu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gt2zszmqxti.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.iojbl.cn/Article/details/gt2bmdzeuyg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gt2mbmpsgau.html

[B04] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gt2vokctrdv.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gt2mzohicsq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuanzhike.top/Article/details/gt2wiapxwxq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcimhijv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gt2mfnihjkd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2csuarlon.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.smart0.xyz/Article/details/gt2szlggrrj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shzxlz.cn/Article/details/gt2apsttvtz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.redwolf501.top/Article/details/gt2ldsorxlk.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2baneabkg.html

Py:   for item in arr: print(item)
来源：http://dali.guannengcc.top/Article/details/gt2pxcvvffh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gt2wqeibgsk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.svipenyu.cn/Article/details/gt2prmuzblj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2awgmjphs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fkyklobw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jianghu66.top/Article/details/gt2vimhfdaj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xziqi.cn/Article/details/gt2ccdohbkv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hysaishi.cn/Article/details/gt2uveivmgq.html

[B06] 遍历字典 / 对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2imkccckc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2htsunmfa.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gt2wfqwopce.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daxiang520.top/Article/details/gt2jidihddc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gt2nombuycv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sysykeji.top/Article/details/gt2yrxznjrb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gt2ktxjqirs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuanzx.com/Article/details/gt2dsyykxio.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmizwjlx.html

[B07] while 循环
来源：http://dali.sufxvd.cn/Article/details/gt2ovvhuegp.html

Py:   while i < 10: i += 1
来源：http://dali.0kj1m.cn/Article/details/gt2vfnbsion.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.c1oappe.top/Article/details/gt2lvpbqexy.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iuapatbl.html

TS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2uplrdbbp.html

Java: while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2cycwslmz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gt2jmbukadf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvkxsbm.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2ebovtcux.html

[B08] do-while（至少执行一次）
来源：http://dali.jlsjyb.cn/Article/details/gt2rpjzuagc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.fzhhl.top/Article/details/gt2upuhgqer.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gt2afnghzti.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2eladckzn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2okmfzfls.html

Java: do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2srvqwzyz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xziqi.cn/Article/details/gt2zdivabfs.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258.top/Article/details/gt2tfqfwnds.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gt2dvhrypoy.html

[B09] break 与 continue
来源：http://dali.yj20258.top/Article/details/gt2gckhhnst.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gt2tzezubnr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gt2wlvioygb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2hcglbiut.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wtucnzys.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dudykwjs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gaofgaol.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgufenzy.top/Article/details/gt2akquvgub.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2uffojylk.html

[B10] 遍历同时拿索引
来源：http://dali.ybcxt.top/Article/details/gt2itoapenn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gt2efumjcnc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gt2xhnqclyr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2nslxabkj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gt2rwamgytz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjwcwwre.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gt2tsdfzqqr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinqigufen.top/Article/details/gt2wdcxwkwu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2oycbeqch.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gt2zomqzalh.html

Py:   list(range(0, 10, 2))
来源：http://dali.cheryme.top/Article/details/gt2wzsuuroc.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gt2rktlfqem.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gt2bihmyjtd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2micikxjb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ydzc1.top/Article/details/gt2pmxulxaa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gt2kbqjhird.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gt2weimkslj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.mhx1999.top/Article/details/gt2suytlflh.html

[B12] 跳出多层循环
来源：http://dali.xylfe.cn/Article/details/gt2njodevgw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gt2bcphdpda.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zpumlprp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ygnpqvjn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2rmaatqtj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gt2gymnqtew.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqfympve.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myhiuqul.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gt2ahretrsy.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gt2heslvoom.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gt2oqjxmhoo.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gt2fivylgpp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvewpifd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gt2dmefaigc.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gt2kkvruhhx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxdmditj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cucudq.cn/Article/details/gt2tzxoalju.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2qqquctuu.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gt2vuoykubw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gt2oxhwdlsf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gt2umfzcszg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gt2wzpajexl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2qjsdoqwi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nkbijdhe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gt2bsgpjsuu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gt2qwrhtujl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2cqgyvohp.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gt2mgedyyyf.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gt2hdptkkgf.html

PHP:  $a && $b || !$c
来源：http://dali.yuxming.cn/Article/details/gt2qdhtiqnm.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gt2nxnqcron.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2mibzrmfn.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2fprhlqul.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gt2esoutniu.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2mihngtoy.html

C#:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2klcfnfnm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2hrrejgwq.html

Py:   if not data: return
来源：http://dali.aizwys.cn/Article/details/gt2granbhwi.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gt2rjmlkglu.html

JS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gt2funepjir.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cpskfgac.html

Java: if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gt2cqmwjunm.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gt2jdlfwquu.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gt2loabxytn.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2gwbvvnmz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hzfemuut.html

C. 函数与作用域
来源：http://dali.bjfxy.top/Article/details/gt2qemlsmnu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2qkupklti.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gt2sfwokdjf.html

Py:   def add(a, b): return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2uieozdxf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fngdgimc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2jbzeedam.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2zhbpuglu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2hcrxeabd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2rcqkmexe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gt2cqihycpi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mghwrxlu.html

[C02] 默认参数
来源：http://dali.yongpay.top/Article/details/gt2akdrlyxm.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gt2xrstbaph.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwdtchp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2sgxsxyfn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2okjbsbza.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gt2xbhlajcy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gt2prlrxngc.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gt2tzjmxnat.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gt2nkqmewdo.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ckvqgtco.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gt2bbgwaiim.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gt2fthxwdfb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gt2hhlikgfn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2acpbvlcb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gt2hokhcadu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gt2ixjgdilv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gt2qpdtjrgv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnxiangtu.top/Article/details/gt2lntkrfjs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gt2tufgytmg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gt2hdexqaxr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gt2minlnpgq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2qvzjeege.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gt2zzpfzaaw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gt2tdiwntsz.html

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gt2khavmrtt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2xrihqpcf.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gt2krwbhzao.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gt2pzgdlnjt.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gt2jodldoat.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gt2ywuagmwy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gt2qwncpzoq.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gt2pnppxslz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gt2snjjewhq.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gt2ohvxlipp.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gt2aapfpocd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.havefunace.top/Article/details/gt2amnzvndg.html


<!-- 参考信息 -->