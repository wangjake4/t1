代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hywenlv.cn/Article/details/gt2rnkjjluu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2qoluewwn.html

TS:   if (!x) {}
来源：http://dali.shzxlz.cn/Article/details/gt2myffcsgy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxbkypzy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxuanxn.top/Article/details/gt2vntbqodk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cdnleiting.top/Article/details/gt2zwnqvvdt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj202588.top/Article/details/gt2ctrxqkjp.html

[A17] 位运算
来源：http://dali.cqqwz.cn/Article/details/gt2uamwwcwh.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2zvsviobf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gt2oigxugea.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gt2trylrcap.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gt2pvujjwvn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2bvfwzqta.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2webtqzlv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2hqaydwix.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2lhpqyurp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hywenlv.cn/Article/details/gt2ufiehclo.html

Py:   ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gt2jbdmlocf.html

PHP:  ord("A"); chr(65)
来源：http://dali.tian-w.cn/Article/details/gt2usbwtghl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.9152youxi.cn/Article/details/gt2sklpbfko.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuanzx.com/Article/details/gt2mzsxznlt.html

Java: (int) 'A'; (char) 65
来源：http://dali.yvedp.cn/Article/details/gt2ygofgusr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258888.top/Article/details/gt2vrbwdlcu.html

Ruby: "A".ord; 65.chr
来源：http://dali.ehwqpu.com/Article/details/gt2ndsdvdxh.html

C#:   (int)'A'; (char)65
来源：http://dali.nanxinkj.top/Article/details/gt2wyelulot.html

[A19] 交换两个变量
来源：http://dali.shuidangran.top/Article/details/gt2zgyrdnic.html

Py:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gt2pkduhosq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sweek.top/Article/details/gt2hyeuvbmu.html

JS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gt2ddjzscoj.html

TS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gt2wtdxytgd.html

Java: int t = a; a = b; b = t;
来源：http://dali.hywenlv.cn/Article/details/gt2ridxwars.html

Go:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwjvruov.html

Ruby: a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gt2umtlueha.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gt2wlkerpds.html

[A20] 读取标准输入
来源：http://dali.zhongyouzk.top/Article/details/gt2xhbcrlwm.html

Py:   name = input("请输入：")
来源：http://dali.zhoulong.xyz/Article/details/gt2tzugwbjk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jyoumei.cn/Article/details/gt2adfxydme.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guannengcc.top/Article/details/gt2gbjloexd.html

TS:   // Node.js：readline 模块
来源：http://dali.gogol.net.cn/Article/details/gt2mvpkgxrl.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yanxiufei.cn/Article/details/gt2tdphqdhl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnqzz.top/Article/details/gt2sirwtfak.html

Ruby: gets.chomp
来源：http://dali.quarkkingdee.top/Article/details/gt2trcpbhbw.html

C#:   Console.ReadLine();
来源：http://dali.fengsongda.top/Article/details/gt2fqyokfsr.html

[A21] 保留指定小数位输出
来源：http://dali.fzhhl.top/Article/details/gt2ivgfwmpm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pycfn.com/Article/details/gt2meqlhjjw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gt2cfivfnqq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gt2xhbwnhge.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhuczadb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xakixmwm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2pktwxzxv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gt2oyrycyfk.html

C#:   3.14159.ToString("F2")
来源：http://dali.pycfn.com/Article/details/gt2vnhiecgj.html

[A22] 获取字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2yrfwelpb.html

Py:   len(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2bzbnnwiy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yangfankeji.com/Article/details/gt2kuvzfqat.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gt2ustwhyrv.html

TS:   s.length
来源：http://dali.jianghu66.top/Article/details/gt2zifiuiuc.html

Java: s.length()
来源：http://dali.redwolf501.top/Article/details/gt2nifwjxst.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2dkszxqec.html

Ruby: s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dijzrsde.html

C#:   s.Length
来源：http://dali.gogol.net.cn/Article/details/gt2izbupwfi.html

[A23] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2vjjijzwa.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.316326.xyz/Article/details/gt2nypssacc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wrtpncoa.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gt2pswhvatr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gt2kcbpxcxn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gt2zwmwzibj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cheryme.top/Article/details/gt2mviiltmn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezgxnmjm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigfzy.top/Article/details/gt2cfylaglm.html

[A24] 去除首尾空白
来源：http://dali.jqgfzy.top/Article/details/gt2tgsotflt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqfnsrxa.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gt2hzfenwrl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gt2zcvobrzo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gt2lcgqduuo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zycfv.cn/Article/details/gt2hqbwqgeu.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangdashe.top/Article/details/gt2jzfnyvzo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jlsjyb.cn/Article/details/gt2zrxkgijf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shzxlz.cn/Article/details/gt2gsgwojcc.html

[A25] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2uwwenabq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daria6918.cn/Article/details/gt2czbvivak.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.dashuyun.cn/Article/details/gt2vgubikab.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gt2trdekoam.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gt2iqpphzix.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gt2pmqprsuk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gt2orfcrwyx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tanke756.top/Article/details/gt2sesfkeib.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gt2jnbsoasd.html

[A26] 类型转换总览
来源：http://dali.guowangkeji.top/Article/details/gt2jgepftwa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cdnleiting.top/Article/details/gt2xlwahjvk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gt2lhnsszpl.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yonumen.top/Article/details/gt2jmqrtnpy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guowangkeji.top/Article/details/gt2dcipwvek.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gt2ozujckeu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gt2cqvdteqf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxinkj.top/Article/details/gt2plisghtu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gt2tdootyzk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2leydjovk.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gt2zxhzxrdp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2nwxxvtmk.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oeuqakzd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gt2hugqoksl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigufen.top/Article/details/gt2gumrpgyp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gt2ylbizeiq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2mspluwrn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2gawbuxfv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gt2xcktttzz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.316326.xyz/Article/details/gt2bofizulm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2qkdnnjsx.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gt2hgrtwblk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zdqjudy.top/Article/details/gt2qkbzeyej.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuanzhike.top/Article/details/gt2dmvttedd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gt2gmztpzxl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2fxewwqxd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sragutqn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigufen.top/Article/details/gt2vijgvqyn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nwbrower.top/Article/details/gt2fweuknqq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2zvhvzbdb.html

[B03] switch / match / case
来源：http://dali.nwbrower.top/Article/details/gt2zosxzahk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.redwolf501.top/Article/details/gt2lfblxxyu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2bbsqtloe.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xmxnibag.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gt2njlciwrn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gt2dxnfqvyu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dashuyun.cn/Article/details/gt2skumhvdz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gt2igkmidrq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj202588.top/Article/details/gt2wcouyqks.html

[B04] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gt2aclnzpxl.html

Py:   for i in range(10): print(i)
来源：http://dali.aibaodan.cn/Article/details/gt2czdsqltn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwvwlvsr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gt2yghfcvgm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gt2niygxgjp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejrjeegp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gihwfdai.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yangfankeji.com/Article/details/gt2mheoeiqy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.316326.xyz/Article/details/gt2lgendiur.html

[B05] 遍历数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gt2ykgpnvce.html

Py:   for item in arr: print(item)
来源：http://dali.9152youxi.cn/Article/details/gt2eaeladhj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dianchejie.cn/Article/details/gt2jotpqrji.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigfzy.top/Article/details/gt2divzcmed.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gt2fcxfoppw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gotoacloud.top/Article/details/gt2depqumly.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhoulong.xyz/Article/details/gt2iuzcyxtm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jianghu66.top/Article/details/gt2ylmunwyv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gt2uwpeqtsi.html

[B06] 遍历字典 / 对象
来源：http://dali.wangdashe.top/Article/details/gt2hfrxfats.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258888.top/Article/details/gt2muaugmqw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmmwcyzo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xksfmapw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gt2roxmoqij.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jepusskh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgtwejub.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcdikaae.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gt2skzzivze.html

[B07] while 循环
来源：http://dali.zdqjudy.top/Article/details/gt2oqjhyvbd.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gt2dpyxiiak.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gt2aftkzoyg.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2byeayeur.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2jovhwlgn.html

Java: while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gt2ooqdnubf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tueulqhz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gt2hldtuzhv.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcunxydj.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gt2wzpwvqqm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigufen.top/Article/details/gt2emmkirjt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2lbjdmheu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2dslctkud.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2bcuztgri.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbdodxzt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cdnleiting.top/Article/details/gt2yccauyls.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gt2yqwxvcvg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzhheizm.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gt2ekcwzxrf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tianlin.xyz/Article/details/gt2nagiiyik.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2lxubxuvg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2xznzemdn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2kivdajqc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2dlosjfbx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gt2biwmxzfw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gt2wvgzqmmh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2rkgcbati.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gt2abfoeggl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zycfv.cn/Article/details/gt2hydclduy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxafxwrh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gt2vyrzyymu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amklgcwj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhixingplan.top/Article/details/gt2fmhvdzap.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzmjfmtn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gt2sioaalqk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258.top/Article/details/gt2mhiikrqq.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gt2xchdmvyu.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gt2aqcqkwfk.html

PHP:  range(0, 10, 2);
来源：http://dali.fzhhl.top/Article/details/gt2cjbeviyw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gt2tsvphylg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gt2ehksbizo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fengsongda.top/Article/details/gt2bfdksyaa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daxiang520.top/Article/details/gt2vefoopcx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2ktlmjptx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.redwolf501.top/Article/details/gt2gnpxlrwn.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gt2qrrlkutp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuerrlyk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gt2graondjt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyghuopc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2kfbwchuw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2jfcprlui.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gt2swmcwvbt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gt2jxukhzyf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gt2pdghqily.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jctnxumq.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gt2hzclydws.html

PHP:  is_numeric($x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2swgnytxu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gt2tycatnil.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2lrawncua.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gt2vtqydfwe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpqvkqi.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gt2fcfbeymh.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gt2hvsajbyo.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gt2kshltegr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gt2jxvtrvym.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yppzjnhj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2azlcjadi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2ykhdpuja.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2opthcgqd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gt2pabsiltd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2uhofkfwr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2syqsmbbr.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gt2ynsfbpki.html

Py:   a and b or not c
来源：http://dali.havefunace.top/Article/details/gt2nezwrezk.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnajyonr.html

JS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2rzmcylos.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhibsxzp.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2svsqnxxo.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2sasxwuyd.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2fucbbwfi.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2hyzdtdeb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gt2lwhtrdhi.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gt2looqondl.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gt2akmttjcc.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2biheivsq.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gt2ymvizrme.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2lwdkjspz.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mjfkvtew.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gt2achghmmi.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2nsfqnify.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2xqicizlr.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2xkatslqd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2akpnrajz.html

[C01] 定义函数
来源：http://dali.mhx1999.top/Article/details/gt2gqtxpejl.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gt2utnrokcj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2pxqetxnx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2seltlaus.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2ftqwsxkz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2tsxxfbdw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuxming.cn/Article/details/gt2qiysuvpj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gt2nicjfrla.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uqgisebq.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwfnzsws.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gt2tejmmepq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gt2ucfbefti.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2gfqozynx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2bvpklhot.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gt2tgczfzyv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.mhx1999.top/Article/details/gt2ezvrexgb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zycfv.cn/Article/details/gt2irzylwkf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qckbjqwn.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gt2xoxxsqwy.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gt2cvpaolbm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gt2swyioojs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2tpynakxg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gt2thyureno.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gt2qygpixrq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gt2ebnnrdtf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gt2tuqcmhkf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xinyue.icu/Article/details/gt2arcrdlpf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gt2hgpwikds.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2pntdtjtn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gt2iasmjbdn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlezboyu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gt2ydjthqof.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2kkkekayj.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gt2ezaryrnc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gt2pxbtrpzk.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2kgqryruu.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gt2plaxlxcm.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gt2rjdaeecj.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gt2zlbpugyt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2mrjvazoy.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gt2hzfmzuxl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gt2odhwjtaj.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gt2yudjuybg.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2twttgexy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkmroruk.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2lglltwcj.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gt2banjzhjv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gt2cstosfmg.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2vjyiqznl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2kclckulq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2tpnptnsj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gt2onskmfrs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gt2ayumcpws.html


<!-- 参考信息 -->