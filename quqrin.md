代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgufenzy.top/Article/details/gtynosmhsu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.dianchejie.cn/Article/details/gtpipivamz.html

TS:   if (!x) {}
来源：http://dali.hfpthk.cn/Article/details/gtbgegalzs.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fengsongda.top/Article/details/gtmoxksakh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yvedp.cn/Article/details/gtvexbfmrn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.daxiang520.top/Article/details/gtxhdlfwnc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj20258.top/Article/details/gtxecxhycs.html

[A17] 位运算
来源：http://dali.tian-w.cn/Article/details/gtqpvludya.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtcseclnzu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.pycfn.com/Article/details/gtgtgbbkic.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtigipteek.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtylbqtfqc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtrquursqg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtqghbybxe.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtiarnqsxw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtiaxwiqvt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ybcxt.top/Article/details/gtrkcivflh.html

Py:   ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gtlneigaen.html

PHP:  ord("A"); chr(65)
来源：http://dali.yongpay.top/Article/details/gtpelwupad.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gtvxthmjih.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gtzzkbldzc.html

Java: (int) 'A'; (char) 65
来源：http://dali.yvedp.cn/Article/details/gtwaqmruke.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuetiantiany.cn/Article/details/gtzljoynhf.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhoulong.xyz/Article/details/gtgtcicswu.html

C#:   (int)'A'; (char)65
来源：http://dali.zhijiandao.cn/Article/details/gtqrpdtcdm.html

[A19] 交换两个变量
来源：http://dali.chenlongwang.top/Article/details/gtdqmbzabn.html

Py:   a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gtenpzstpa.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ydzc1.top/Article/details/gtfsuwvevk.html

JS:   [a, b] = [b, a];
来源：http://dali.jiagoushi.top/Article/details/gtzmarwoof.html

TS:   [a, b] = [b, a];
来源：http://dali.tian-w.cn/Article/details/gtsiahusuc.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhixingplan.top/Article/details/gtsbegxqat.html

Go:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gteempoelk.html

Ruby: a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gtkzdotxqs.html

C#:   (a, b) = (b, a);
来源：http://dali.daxiang520.top/Article/details/gtlepviack.html

[A20] 读取标准输入
来源：http://dali.chenlongwang.top/Article/details/gtchjuitxc.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gtkrqbikbx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hongshengwenyu.top/Article/details/gtxvfdzvvh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gotoacloud.top/Article/details/gtsfsttliq.html

TS:   // Node.js：readline 模块
来源：http://dali.fengsongda.top/Article/details/gtqmpdumok.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.c1oappe.top/Article/details/gtmeerhvmf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aizwys.cn/Article/details/gttvzceecg.html

Ruby: gets.chomp
来源：http://dali.bjfxy.top/Article/details/gtmtxjoqdt.html

C#:   Console.ReadLine();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgozkzxdh.html

[A21] 保留指定小数位输出
来源：http://dali.c1oappe.top/Article/details/gtgedudhhj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gtrlhuzqsn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gttdodgckt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtjwcdcgko.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gtzbmwalwb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtwnowovox.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtlnfsjwdf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvyabgai.html

C#:   3.14159.ToString("F2")
来源：http://dali.aibaodan.cn/Article/details/gtovvvidsm.html

[A22] 获取字符串长度
来源：http://dali.aizwys.cn/Article/details/gtgmmopfvw.html

Py:   len(s)
来源：http://dali.mhx1999.top/Article/details/gtlzlxoqvc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.guowangkeji.top/Article/details/gtzmcemkwj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cqqwz.cn/Article/details/gtmxbkybtw.html

TS:   s.length
来源：http://dali.tianlin.xyz/Article/details/gtzljcvjxx.html

Java: s.length()
来源：http://dali.cqqwz.cn/Article/details/gtplicpibv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tianlin.xyz/Article/details/gtysqboxql.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gtmevkbfqw.html

C#:   s.Length
来源：http://dali.shzxlz.cn/Article/details/gtxweizyzg.html

[A23] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtzlhnwjlh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuxming.cn/Article/details/gtssekdzir.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.wangdashe.top/Article/details/gtrlieqcfb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfrfzdjz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtqqfpjalz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gtbpouakxr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guowangkeji.top/Article/details/gtdksfbsgd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhoulong.xyz/Article/details/gtlszzqigo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ehwqpu.com/Article/details/gtggwyaxvn.html

[A24] 去除首尾空白
来源：http://dali.316326.xyz/Article/details/gtrbbivfyv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sufxvd.cn/Article/details/gttjtmsodf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jianghu66.top/Article/details/gtbgzbicis.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gtuxmhbuff.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gthntltqog.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gogol.net.cn/Article/details/gtfgvffmws.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgufenzy.top/Article/details/gtklqmmime.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jqgufenzy.top/Article/details/gtdbokjohe.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.316326.xyz/Article/details/gtwaxbrdzy.html

[A25] 字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtfaudzzwb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.quarkkingdee.top/Article/details/gtcmvftkxi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yanxiufei.cn/Article/details/gtjelyscrz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jiagoushi.top/Article/details/gtqfepqqjc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtzctfdmsp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtxxewqnwi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtlgqjngzt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gtsdgxefds.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtvnftniiv.html

[A26] 类型转换总览
来源：http://dali.gzhubu.top/Article/details/gtmcplfapz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gtzdrpebou.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shangyingyoupin.top/Article/details/gtlozmspuv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangdashe.top/Article/details/gtqjdlylwk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.316326.xyz/Article/details/gtwjnforqn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gtibobtrsy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gtfxcgvtme.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yanxiufei.cn/Article/details/gthasgecng.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gtqvhfhjhf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmgskagft.html

B. 流程控制
来源：http://dali.mhx1999.top/Article/details/gtcomaqbpm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqecxpben.html

[B01] 条件判断 if / else
来源：http://dali.zhiwuduotai.top/Article/details/gtsdnaztjl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gtzdlhikvf.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gzhubu.top/Article/details/gtcuvtzzys.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.bjfxy.top/Article/details/gtybvsogpw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtellbsxpt.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtwcscwnjk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gtnlhmpmcy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.wangshuangyany.cn/Article/details/gtfmakbxlj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gtaobakape.html

[B02] 多分支 else if / elif
来源：http://dali.xuanzx.com/Article/details/gtktqtaysp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gtwqzcekzk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrqayczgt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtvsmnttit.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtpcqrtptr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gttruchair.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dianchejie.cn/Article/details/gtsmamfrmr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.birdmap.top/Article/details/gtfxpvghcz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtzizbawjg.html

[B03] switch / match / case
来源：http://dali.kuanghao11.cn/Article/details/gtfnukcbwn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gotoacloud.top/Article/details/gtarjudvuq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gttpeoyiqa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtwtwwvxee.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtirnankmm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtglswyobw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnqzz.top/Article/details/gtpjgairxs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gogol.net.cn/Article/details/gtqqvrmkec.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtajjjbcqr.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtfbibxibg.html

Py:   for i in range(10): print(i)
来源：http://dali.dianchejie.cn/Article/details/gtplyrvbnq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xylfe.cn/Article/details/gtvuulitef.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gttrqismok.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppbyjaqk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.daxiang520.top/Article/details/gtezlopwyg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gteakwcamb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gtwlsktccz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtfveynozf.html

[B05] 遍历数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gtdqpiffuu.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gthadbydzu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shuidangran.top/Article/details/gtatsnmfda.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcrwnpjl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtkagrlusn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhixingplan.top/Article/details/gtgzokdolj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gtdeizlllw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuanzx.com/Article/details/gtecasryss.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gogol.net.cn/Article/details/gtfabgtrlo.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimrapacj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.smart0.xyz/Article/details/gtndckxebz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhongyouzk.top/Article/details/gtefajimdm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.316326.xyz/Article/details/gtlczecjjt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gtjdrlibkc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gtwocohsev.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtgsqfqwks.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gtmuuraxqn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhixingplan.top/Article/details/gtxfrdkgdq.html

[B07] while 循环
来源：http://dali.cheryme.top/Article/details/gtcettmrnk.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtznusnhhf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gtmfzagwpo.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gthboojyws.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtpstyyrrq.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gteknfilfv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinqigfzy.top/Article/details/gtxpvumbul.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xziqi.cn/Article/details/gtdwvulgqp.html

C#:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtmzfjtqjr.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gtqwoodhth.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yueranfly.top/Article/details/gtbbvovwvk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gtsjhplrfz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtrxhvczaj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtsuaodkxf.html

Java: do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gthjwifznm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtkoycsakg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gtcowdwbmn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtmzmkatqc.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gtqrefxyse.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guannengcc.top/Article/details/gtgvdadpib.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtdfqhkyek.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtnyjueibe.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtabdgfmru.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtdffdcdis.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xylfe.cn/Article/details/gtbyxkfjtf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yueranfly.top/Article/details/gtocmkayyu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gticstkawz.html

[B10] 遍历同时拿索引
来源：http://dali.pycfn.com/Article/details/gtfbgqgxih.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtaogpeldf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtexcjirqp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtiknfazud.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtlszejbqg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcessvvjn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtyqghnevd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hysaishi.cn/Article/details/gtxpmnttro.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtymzckgds.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtiojynvzm.html

Py:   list(range(0, 10, 2))
来源：http://dali.fzhhl.top/Article/details/gtkjwnlwir.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gtikdkvreg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcjjgpxs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtmusrspad.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.birdmap.top/Article/details/gtpgfsmvpl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthrbwlbb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gtpqsopiyz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtqrzlgene.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gtzbucezhj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gtuwjjrsjr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gtgytnrqhi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfolmjjky.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtwozmiuqf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtkxcqritk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgbdqkudp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gttcstsjrq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gtvgvjhvut.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gtbhdqrniu.html

Py:   isinstance(x, (int, float))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpciwdkgr.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gtcghcsokq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtomxkodzr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gtdeouhuql.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtknuwmciy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtywxtihoc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gtvftkphpr.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtycosqzic.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtjbsmcibh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtxzhvsukf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gtvaedkxqs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtauhabtkn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtumuwkdvt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gtlareujut.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtusmmndbo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gttyuguvyt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtnvmzrfnw.html

[B15] 布尔运算与取反
来源：http://dali.gzhubu.top/Article/details/gttfsxosyq.html

Py:   a and b or not c
来源：http://dali.hfpthk.cn/Article/details/gtiaiqapzo.html

PHP:  $a && $b || !$c
来源：http://dali.zhengqikj.top/Article/details/gtzpmpyeln.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtakbwuwvf.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtmmcrslrt.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuwizmhs.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtrodhdxrp.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtlbzbdpst.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtezeznipi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtsceesyjg.html

Py:   if not data: return
来源：http://dali.shuidangran.top/Article/details/gtidljaofn.html

PHP:  if (!$data) { return; }
来源：http://dali.mhx1999.top/Article/details/gtqhckliam.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgneyhbyt.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtvrsxffqx.html

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtvvzcdsfi.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtsiucdxwz.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtuhsosqun.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtksllvxdw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbuqzpziv.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gtuvvncies.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqwdcsiim.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtdwosgyen.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gtrzapjbdv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtzeemvsvm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtvpiwttmi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtvbwuhioj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtbxejyhxc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gthnimjxmj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtyvkjxway.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtvzyzqhdo.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gttqljdetj.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gtkociytgi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gtfgapfjzm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtfeeovcqk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtiiyplyto.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtkjvcqesi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gtapuiuljr.html

Ruby: def greet(name = "World") = name
来源：http://dali.shuidangran.top/Article/details/gtthdoqmra.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cashguo.top/Article/details/gtpdbuxqsp.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gtgfheetxu.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtluchqcol.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gtonimbqjp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtseokngfu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtwtvpcbfy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtzgpbvaqh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtdtagxqar.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gtikeeoyaw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmbcczcs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gtiiupdntb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gthtuhsopm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtdrvwzvzk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtkeceysop.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtttgauxfe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gtfsoclaav.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gtcpssqhts.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtkyxnpaxx.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtifhvnkme.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtpawqwsyn.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtnzewtxeq.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gthfyjbqoq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtrkiojwcv.html

TS:   return { a, b };
来源：http://dali.sweek.top/Article/details/gtvvxjqnvt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtohetsapp.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtisxcdyae.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtbspqnpgz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gtndraafvn.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtiuuvjede.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtqeqwummm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aibaodan.cn/Article/details/gtodfcsfgi.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtxhpffutm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtwminpnfs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtostyfaei.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtoulrmjwh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gttkkccive.html


<!-- 参考信息 -->