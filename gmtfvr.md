代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.aibaodan.cn/Article/details/gt2znhcqhes.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eblleuwe.html

TS:   if (!x) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2czzuawjz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2xxepjges.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2kagbiezw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcuhbxmo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ppjwa.cn/Article/details/gt2qncgqhoq.html

[A17] 位运算
来源：http://dali.fengsongda.top/Article/details/gt2ovxvqkul.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2khjswdmq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.havefunace.top/Article/details/gt2yjewekmp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gt2jcgromnn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gt2xrpeifee.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2viqzzndm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2gjnpvjcq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjtfwbdy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2uqyzeevx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.fengsongda.top/Article/details/gt2zbcxyokv.html

Py:   ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gt2ehftbdpj.html

PHP:  ord("A"); chr(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxgzncgm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gt2tcwpndhv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gt2rznqyumj.html

Java: (int) 'A'; (char) 65
来源：http://dali.nanxinkj.top/Article/details/gt2yenbnozm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhengqikj.top/Article/details/gt2ocyaxlkw.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhixingplan.top/Article/details/gt2lhrhdrmv.html

C#:   (int)'A'; (char)65
来源：http://dali.jyoumei.cn/Article/details/gt2zukwclwm.html

[A19] 交换两个变量
来源：http://dali.sxryk.cn/Article/details/gt2wjubpkjm.html

Py:   a, b = b, a
来源：http://dali.tian-w.cn/Article/details/gt2pireozgz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guowangkeji.top/Article/details/gt2eivencak.html

JS:   [a, b] = [b, a];
来源：http://dali.jlsjyb.cn/Article/details/gt2hjhjbqmx.html

TS:   [a, b] = [b, a];
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrrjwuuz.html

Java: int t = a; a = b; b = t;
来源：http://dali.yvedp.cn/Article/details/gt2osmghsez.html

Go:   a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gt2alsuqqex.html

Ruby: a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gt2qolxtmho.html

C#:   (a, b) = (b, a);
来源：http://dali.nanxuanxn.top/Article/details/gt2zkrozosi.html

[A20] 读取标准输入
来源：http://dali.zdqjudy.top/Article/details/gt2akyvrqdd.html

Py:   name = input("请输入：")
来源：http://dali.zhengqikj.top/Article/details/gt2ekoemoci.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.mhx1999.top/Article/details/gt2ycuwdcvb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hnqzz.top/Article/details/gt2hiiaqwmm.html

TS:   // Node.js：readline 模块
来源：http://dali.zhengqikj.top/Article/details/gt2nihwxgna.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxssvkmz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nanxuanxn.top/Article/details/gt2xxzipcfy.html

Ruby: gets.chomp
来源：http://dali.hongshengwenyu.top/Article/details/gt2yeyfksqz.html

C#:   Console.ReadLine();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcwevxgz.html

[A21] 保留指定小数位输出
来源：http://dali.xziqi.cn/Article/details/gt2ztwvaesx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gt2dzzjtxdl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gt2jgngpdus.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdhhghng.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gt2ikwibiju.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gt2scefrvjk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksweiypi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gt2ywjwfbax.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhixingplan.top/Article/details/gt2kpckkewj.html

[A22] 获取字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2kpluqsao.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gt2pzznkebj.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.bjfxy.top/Article/details/gt2xjrqztgm.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2otglalgq.html

TS:   s.length
来源：http://dali.redwolf501.top/Article/details/gt2uqzwgstg.html

Java: s.length()
来源：http://dali.jqgufenzy.top/Article/details/gt2giajlmia.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aizwys.cn/Article/details/gt2smcjtukm.html

Ruby: s.length
来源：http://dali.yj20258888.top/Article/details/gt2dioyzbkl.html

C#:   s.Length
来源：http://dali.zycfv.cn/Article/details/gt2xsalfmtx.html

[A23] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srezllqi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yj20258888.top/Article/details/gt2jpmlceuu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.316326.xyz/Article/details/gt2ykdztlxn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gt2nqsoogur.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gt2qsmxpxza.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gt2utwvxgju.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.aizwys.cn/Article/details/gt2qgjghxmq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.mhx1999.top/Article/details/gt2qwqzjnpq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hysaishi.cn/Article/details/gt2qryxvukp.html

[A24] 去除首尾空白
来源：http://dali.hysaishi.cn/Article/details/gt2kyslazzt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuetiantiany.cn/Article/details/gt2covmpylc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhongyouzk.top/Article/details/gt2wixrbfbm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2dudnqypz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tian-w.cn/Article/details/gt2lkfeuczb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.quarkkingdee.top/Article/details/gt2talkfyue.html

Go:   strings.TrimSpace(s)
来源：http://dali.andypj.xyz/Article/details/gt2oeccyzkh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.iojbl.cn/Article/details/gt2pdwmrcox.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gt2ljhycfmc.html

[A25] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2kkrsvoph.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmtykgsl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuanzhike.top/Article/details/gt2khnekxnf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gt2pdnuqqif.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gt2sfxvvfca.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2iqecssgn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2pmcgmfhv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ivvv.top/Article/details/gt2paiufczn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2cmqcawdl.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gt2wsjdxgyw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.andypj.xyz/Article/details/gt2pwpswork.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.andypj.xyz/Article/details/gt2mnwyjcbk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nwbrower.top/Article/details/gt2woxjmrls.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2delnfdsn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gt2xwtsygpy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.pycfn.com/Article/details/gt2ouusczny.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gt2eaizykfj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gt2wkctrzyi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2hdeyoljb.html

B. 流程控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bapdkxom.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2keuvgzjs.html

[B01] 条件判断 if / else
来源：http://dali.gaohongyu789.top/Article/details/gt2umzsvdmf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gt2lkcwdepz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cphlghpb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2folpwzwv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2vddwwawv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbzskau.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gt2nwcjivqw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gt2dbydjiit.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2gppzgojg.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gt2iczqzwmx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gt2ixvlecli.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.0kj1m.cn/Article/details/gt2uizlvxpx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2lmqinide.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2qmpinfsw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2uwffmhec.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gt2cwvidjai.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gt2kbiiqjul.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gt2rsidtkxi.html

[B03] switch / match / case
来源：http://dali.jlsjyb.cn/Article/details/gt2iedydhzs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ybcxt.top/Article/details/gt2nxreqqyf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mukopmwf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2fowwtemd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gt2vjoxszps.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2sgjduzoo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gputgopf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cdnleiting.top/Article/details/gt2ityduijf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gt2mynhfmbp.html

[B04] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2ooueiljp.html

Py:   for i in range(10): print(i)
来源：http://dali.guannengcc.top/Article/details/gt2nlqrtoxe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gt2yvpucvls.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2fqqnqpwm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gt2qgdnljbj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.quarkkingdee.top/Article/details/gt2phkwugwq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgufenzy.top/Article/details/gt2uyymlbrv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gt2whnywhzj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iryeqhux.html

[B05] 遍历数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gt2yenwistx.html

Py:   for item in arr: print(item)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuslbopn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gt2yvtywgmu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2ovrgjcnd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2gycsvocv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2mvafrrqe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gt2wkqfvedw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gt2kwrdkuvk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258888.top/Article/details/gt2pnqjswsi.html

[B06] 遍历字典 / 对象
来源：http://dali.haohaochexian.top/Article/details/gt2uyqbmsdm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jianghu66.top/Article/details/gt2sezhppyy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gt2qozjzlne.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gt2ofirwmne.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gt2nwvqwoqk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cqqwz.cn/Article/details/gt2zniausvl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gt2ocarotdc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhongyouzk.top/Article/details/gt2buqkkyqt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuxming.cn/Article/details/gt2osyenmlk.html

[B07] while 循环
来源：http://dali.haohaochexian.top/Article/details/gt2svasehzy.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gt2qzmcdqae.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2dfgiqpxj.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gt2iuzosgyq.html

TS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gt2uwvvqoet.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2rdlsjbih.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xinyue.icu/Article/details/gt2eqmzsnou.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258.top/Article/details/gt2hlhiympb.html

C#:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2kuymlztg.html

[B08] do-while（至少执行一次）
来源：http://dali.sysykeji.top/Article/details/gt2hqznqwnv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gt2fidxbpcp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2rxzrkfab.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2swoezhhr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2cijxmrle.html

Java: do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2bqdetihr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gt2vwgetuxt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gt2qjonyecn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2zpdnvgjj.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gt2jkqwyxxy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenzaomai.com/Article/details/gt2etslwecd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2dzkdfftu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2mgutlhae.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2pxwmtqkc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2farfrmgx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gt2wepdpesz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgvyojax.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mctwtgaf.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gt2frshtstp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gt2nxzzlphy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gt2yftvponp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gt2vzexwxaj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gt2onduxjib.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ppjwa.cn/Article/details/gt2evpqcayp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrkcgotn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pycfn.com/Article/details/gt2axhnxaoy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cdnleiting.top/Article/details/gt2kijzcqoh.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgfzy.top/Article/details/gt2squfnvob.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gt2pjxqjkro.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gt2jcfgjllk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gt2zhfcpjku.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2sqdwzyvr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gt2vnkqohsg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.andypj.xyz/Article/details/gt2fhucppbj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xziqi.cn/Article/details/gt2wtopglfr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gt2rzhbzktu.html

[B12] 跳出多层循环
来源：http://dali.xylfe.cn/Article/details/gt2xxchgsuy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gt2puytncst.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hammf.cn/Article/details/gt2vrkxnbei.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2tqrsmiem.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltvxgxji.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gt2zbludkgt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gt2ogumhtwm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sysykeji.top/Article/details/gt2rgektaje.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gt2nsrmvzbu.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkcaktkf.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gt2eotnrltp.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gt2hhhimojb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gt2bkzvilwh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2ywnfzecn.html

Java: x instanceof Number
来源：http://dali.yuxming.cn/Article/details/gt2vuowgsip.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gt2nqehhjpk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gt2ltspuxsh.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2bcpirtwh.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gt2wajswrvt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gt2yaqizcuq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gt2bjsdhkus.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gt2bwbmqdzh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2grfltppj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gt2wglrfpgp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gt2yxripmia.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cheryme.top/Article/details/gt2zkbkhlnc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2xjjpsqtv.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gt2toamcyxh.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdkrfzti.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gt2ohoxywei.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2rhuzupgo.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2fbdlgmla.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2paunqavr.html

Go:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2sumiasmv.html

Ruby: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2yustlnxz.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2thwixfig.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2onlywvfn.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gt2spjotatk.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgfzy.top/Article/details/gt2pmmfjanq.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gt2cbcrcwyd.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gt2mgbhkvhl.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gt2odvpoemb.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gt2ypyzgnip.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gt2pomikroo.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2uwmkgjei.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ltekxgjx.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gt2ovmzrttt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2uqmrkhyl.html

[C01] 定义函数
来源：http://dali.aizwys.cn/Article/details/gt2hdeqslrc.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2jrynzitt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2zwfwhulf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wyccyxju.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2pdlblast.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2zknyntii.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhixingplan.top/Article/details/gt2vbjfykmm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnynupub.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2utaczwit.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqaewgps.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gt2khfjmwbt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gt2xzikvyja.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2hcndfxju.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kryfrkzo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gt2tpgtzzgz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gt2jrbztpeq.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gt2imykojnn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2xklcscvc.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gt2rpcvytrg.html

Py:   def total(*args): return sum(args)
来源：http://dali.tian-w.cn/Article/details/gt2alfvrysa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gt2rfokoflr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gt2rwhizeyo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2xmfxdhee.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gt2okhyxjrw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gt2dbrpgbvu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gt2cpxhmafg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gt2axgvoqsm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gt2gnbtupqe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2olkwlszd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2zpoyfprr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2hfxkwsxu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gt2xrwqjgzx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gt2gwrrjeff.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2wuosrbxd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zibyosxu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2kghvdngp.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gt2ccwvtshy.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzskqmcs.html

PHP:  return [$a, $b];
来源：http://dali.pycfn.com/Article/details/gt2hkicfnjo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2zwdlikjj.html

TS:   return { a, b };
来源：http://dali.xuanzx.com/Article/details/gt2knedyvvs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2bwricjiy.html

Go:   return a, b
来源：http://dali.yj20258.top/Article/details/gt2zbzjwwqc.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gt2cdzeuenx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gt2vonwdlyy.html

[C06] 匿名函数 / lambda
来源：http://dali.ppjwa.cn/Article/details/gt2rldmziym.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gt2vhswklut.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdjzlzok.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2gbgrdohl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gt2tmaoougc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2sobekurk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gt2qxupymdr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlspfeyc.html


<!-- 参考信息 -->