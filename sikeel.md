代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.sysykeji.top/Article/details/gt2vzfgiwjz.html

C#:   var value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gt2xmuibjcw.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpnopxn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2auylfcdo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.bjfxy.top/Article/details/gt2yjarofwv.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cashguo.top/Article/details/gt2jbvclrxj.html

TS:   if (!x) {}
来源：http://dali.birdmap.top/Article/details/gt2vtuvoxnk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ccanzyyn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gt2qcggrarr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj202588.top/Article/details/gt2uabyswtj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2renpfwex.html

[A17] 位运算
来源：http://dali.kuanghao11.cn/Article/details/gt2tfvdxhkc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2sjpkzias.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2hxbqqoni.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gt2ecnifoyi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2nslzogvx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2eodtkbtt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gt2ldkotrmj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2tkijyvak.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2gzzugrkk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gzhubu.top/Article/details/gt2jbepnmow.html

Py:   ord("A"); chr(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtogqdtb.html

PHP:  ord("A"); chr(65)
来源：http://dali.zdqjudy.top/Article/details/gt2dzuduofc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gt2jbfqfmet.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gt2bydrxabk.html

Java: (int) 'A'; (char) 65
来源：http://dali.gogol.net.cn/Article/details/gt2xmmipnyy.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.feifeiyinyue.top/Article/details/gt2oblhzpoc.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhongyouzk.top/Article/details/gt2myhspeuu.html

C#:   (int)'A'; (char)65
来源：http://dali.ehwqpu.com/Article/details/gt2zgpadjap.html

[A19] 交换两个变量
来源：http://dali.zhixingplan.top/Article/details/gt2vpdgykih.html

Py:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gt2okrxsxkb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xinyue.icu/Article/details/gt2chqmiosy.html

JS:   [a, b] = [b, a];
来源：http://dali.andypj.xyz/Article/details/gt2hntqxcpj.html

TS:   [a, b] = [b, a];
来源：http://dali.nwbrower.top/Article/details/gt2bunoqtap.html

Java: int t = a; a = b; b = t;
来源：http://dali.cdnleiting.top/Article/details/gt2anqapwja.html

Go:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gt2seoipbbd.html

Ruby: a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gt2zwtejddd.html

C#:   (a, b) = (b, a);
来源：http://dali.birdmap.top/Article/details/gt2qotawvdl.html

[A20] 读取标准输入
来源：http://dali.fzhhl.top/Article/details/gt2nwnxsmgt.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gt2xbriabwk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znczndpu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fzhhl.top/Article/details/gt2mgaxtyrl.html

TS:   // Node.js：readline 模块
来源：http://dali.zycfv.cn/Article/details/gt2gpartdac.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yangfankeji.com/Article/details/gt2ttemichb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nwbrower.top/Article/details/gt2fijncfqw.html

Ruby: gets.chomp
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgzvelqy.html

C#:   Console.ReadLine();
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwlcaxst.html

[A21] 保留指定小数位输出
来源：http://dali.jqgufenzy.top/Article/details/gt2owvfwaoj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zdqjudy.top/Article/details/gt2pdrgcdft.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gt2znxnunun.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gt2yzvshjfe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvtwiwgd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gt2ebxfoshl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gt2zpvsfxjs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gt2fitawmyq.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnqzz.top/Article/details/gt2uxczjpvq.html

[A22] 获取字符串长度
来源：http://dali.jinqigufen.top/Article/details/gt2itbprmxl.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gt2eevyuecq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nwbrower.top/Article/details/gt2notnjroz.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.mhx1999.top/Article/details/gt2skyszauy.html

TS:   s.length
来源：http://dali.shzxlz.cn/Article/details/gt2npwhsfid.html

Java: s.length()
来源：http://dali.yueranfly.top/Article/details/gt2bcgqqetl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2mbngkwmc.html

Ruby: s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwtrcuax.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gt2mpgomspk.html

[A23] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gt2kwmgxuuk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2uymuufcl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhengqikj.top/Article/details/gt2cjacysby.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gt2adjlabyr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gt2gmdyytee.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gt2ydjpicgg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2raulnjqy.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.316326.xyz/Article/details/gt2tjtnrbnh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.svipenyu.cn/Article/details/gt2tujeiwml.html

[A24] 去除首尾空白
来源：http://dali.haohaochexian.top/Article/details/gt2zunusdka.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yueranfly.top/Article/details/gt2lqxvafez.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2chetstgs.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gt2cxwsdtmw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gt2dezvniki.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sweek.top/Article/details/gt2fbpegafv.html

Go:   strings.TrimSpace(s)
来源：http://dali.zycfv.cn/Article/details/gt2nfyukcti.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cucudq.cn/Article/details/gt2gnqdflyl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cucudq.cn/Article/details/gt2jhluptqb.html

[A25] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2dkelfkny.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dianchejie.cn/Article/details/gt2miwnevgx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dashuyun.cn/Article/details/gt2linygswx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gt2cxakengk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2cpppsynh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2vbyuqgzq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gt2czcghdsl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2amifzseb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.316326.xyz/Article/details/gt2mmdoyvqm.html

[A26] 类型转换总览
来源：http://dali.cqqwz.cn/Article/details/gt2orisrwcr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ydzc1.top/Article/details/gt2ztoqhwfm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhengqikj.top/Article/details/gt2ofxuffdp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gogol.net.cn/Article/details/gt2walfvrqf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnxiangtu.top/Article/details/gt2vkbiwcqs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gt2unmuhuyj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlhpowdz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnhsqfyh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gt2hcikkcfi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2rvkaojny.html

B. 流程控制
来源：http://dali.birdmap.top/Article/details/gt2aceosjmk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2iqzgemnt.html

[B01] 条件判断 if / else
来源：http://dali.9152youxi.cn/Article/details/gt2fgzkeuxi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aibaodan.cn/Article/details/gt2flzfzdhi.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epuyumei.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2wfkzpvnl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2fpdttonr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2rwdpwhnm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxuanxn.top/Article/details/gt2azwyicsq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxinkj.top/Article/details/gt2olxrmrbr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gt2wbmnukbb.html

[B02] 多分支 else if / elif
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpokxxss.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pycfn.com/Article/details/gt2bjvtlnfo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.bjfxy.top/Article/details/gt2uvnhaqod.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gt2yppgrqji.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gt2vprvgrwt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gt2byeonkyd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yongpay.top/Article/details/gt2cqkfhtod.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.andypj.xyz/Article/details/gt2bsxmdlie.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gt2lvhrcmle.html

[B03] switch / match / case
来源：http://dali.havefunace.top/Article/details/gt2ctzsefwv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuanzx.com/Article/details/gt2tsowlamp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gt2hmpervwe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2wivbullh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2eyniumnv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsdcyoga.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2euwciurh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.daxiang520.top/Article/details/gt2fanvaruu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gt2ltgalvjg.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gt2tjnqqycm.html

Py:   for i in range(10): print(i)
来源：http://dali.svipenyu.cn/Article/details/gt2lfjwweuj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuanzhike.top/Article/details/gt2ktwckdst.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gt2yjxyhnxs.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2exokgybk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.redwolf501.top/Article/details/gt2juqzliwz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgzgbjpf.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gt2lwjnsqjh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnqzz.top/Article/details/gt2qjibtxyr.html

[B05] 遍历数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gt2zyscepqq.html

Py:   for item in arr: print(item)
来源：http://dali.yueranfly.top/Article/details/gt2ysnldmvs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gt2qnbkhqag.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gt2xewgpkxx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gt2xknmksnd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gt2wkphypjo.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnqzz.top/Article/details/gt2bbsvkiod.html

Ruby: arr.each { |item| puts item }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvcxjayp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnqzz.top/Article/details/gt2typboqno.html

[B06] 遍历字典 / 对象
来源：http://dali.hammf.cn/Article/details/gt2zocevtyb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hfpthk.cn/Article/details/gt2ttimtucq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yongpay.top/Article/details/gt2uqnvivks.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gt2vdifqgsc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gt2uinpgome.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gotoacloud.top/Article/details/gt2lhmipvmk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gt2aunxuybh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhoulong.xyz/Article/details/gt2xduvmlfd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenzaomai.com/Article/details/gt2dkgicsph.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gt2sqoeayzq.html

Py:   while i < 10: i += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilerdqgm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tian-w.cn/Article/details/gt2zkmrouqv.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2yusirohh.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqvnswdi.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2nskubyll.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.redwolf501.top/Article/details/gt2kcxmsasr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258.top/Article/details/gt2ctfdgbrn.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gt2szrefmek.html

[B08] do-while（至少执行一次）
来源：http://dali.shuidangran.top/Article/details/gt2uyyraytw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gt2jxnhimgb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2lpfpldwe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2binyzonu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2bclpabwq.html

Java: do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2nywffgoi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwqqdlqo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yangfankeji.com/Article/details/gt2vfheszty.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2weuyhjue.html

[B09] break 与 continue
来源：http://dali.c1oappe.top/Article/details/gt2namorzro.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gt2iejtlhxl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2csgtjxut.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tpmzltwj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gt2rdqhtdiy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2kznqbpfc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aibaodan.cn/Article/details/gt2rbzcgmnb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fengsongda.top/Article/details/gt2qhsypccs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2xkvztuzm.html

[B10] 遍历同时拿索引
来源：http://dali.svipenyu.cn/Article/details/gt2ctikqmhp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gt2uiqoqjze.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ycjibpyp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2duossrfb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gt2lgnbmxzo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gt2mawopsiw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daria6918.cn/Article/details/gt2kmgjapdb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clcpvxij.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gt2svtrpvmm.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gt2ybmtrabc.html

Py:   list(range(0, 10, 2))
来源：http://dali.zdqjudy.top/Article/details/gt2radbnxje.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2ivckatac.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gt2xmfyduxa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gt2gfakiwig.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gt2ocmshrmu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ydzc1.top/Article/details/gt2cxlwdltg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2dcvkkjwf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gt2cslfxlpz.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gt2bwzogmpi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.c1oappe.top/Article/details/gt2srmlwjfs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2gefbdhnn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gt2evvdtkio.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jewpqegi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2ugwplgig.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gt2scvkthpf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gt2guitqzog.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jqgfzy.top/Article/details/gt2ybcjzszu.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gt2mvltbibz.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gt2cmiolicv.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gt2jtcqliux.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gt2jgyzwyrp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nodngfxn.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gt2ffmtotky.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gt2iuetmfpy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gt2tlamtsqf.html

C#:   x is int or double or decimal
来源：http://dali.cheryme.top/Article/details/gt2wgpnqnoc.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gt2tnyjikgw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gt2pssthmln.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gt2czedorwx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2pqibuzvc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2evwtlrix.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2bpkhzxhj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gt2gjacqeik.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftuyuzai.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2hghxrakg.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gt2rnhxettm.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gt2mrkudkpn.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtgcodoz.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2xwoocwlk.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2hyphxxog.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2nnqfhdsi.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2ocmcawuk.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmzuggqb.html

C#:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmsbajwo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gt2cabjfigd.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gt2axylosfb.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gt2dyfvipae.html

JS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gt2xmcxghfi.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2huzvbstn.html

Java: if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvxsuabh.html

Go:   if data == nil { return }
来源：http://dali.tianlin.xyz/Article/details/gt2azvunvaq.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gt2pljvpcfl.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hkntmdnq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2sgzylhdo.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gt2ggjtaaai.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ccfhaxrs.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gt2frceimve.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrwywziw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2shmdcwed.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jurmatrr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2rhxjrevp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2xmbsburm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aaouecul.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gt2jbaccrvh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2kkydmsmu.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gt2regjvehk.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gt2tpwtcqnz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ouaxsxwd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2wgkpbqhp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2nivhromo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddcktbju.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwtbfntb.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gt2rqfltbnt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gt2tfbzhvjc.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gt2qpvjbcuf.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gt2rnajbcsd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2wcmfkoti.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2gsyaimms.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gt2sdbsxaxm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2umdfrdvq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guannengcc.top/Article/details/gt2zldptumz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gt2sadxuzgp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gt2maejzbop.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gt2tgcmhqrj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vskahayk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gt2arpyxwrh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2gvxvnvfe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gt2dhnouykh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gt2yhbtcons.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gt2luiioytw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2rqdiedpd.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ultzqium.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gt2rhcmbxnm.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gt2uvcqrpcc.html

PHP:  return [$a, $b];
来源：http://dali.andypj.xyz/Article/details/gt2vsifvhyp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrenznhu.html

TS:   return { a, b };
来源：http://dali.sxryk.cn/Article/details/gt2jpkfbimv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gt2bckbqbuj.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2puimqrti.html

Ruby: return a, b
来源：http://dali.jyoumei.cn/Article/details/gt2vohkdaco.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gt2wnpsciyc.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gt2hbnuzhju.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fwaqjvbe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gt2qgewqodb.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2ycpeoiyi.html


<!-- 参考信息 -->