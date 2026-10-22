代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gt2tiwtashe.html

[A15] 空值判断与默认值
来源：http://dali.cucudq.cn/Article/details/gt2knsvqmsp.html

Py:   value = data or "默认值"
来源：http://dali.ydzc1.top/Article/details/gt2lrqhfcst.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycqymeiq.html

JS:   const value = data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gt2cynjdfhz.html

TS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gt2bjelwdma.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jqgufenzy.top/Article/details/gt2mcmpeesd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hywenlv.cn/Article/details/gt2xbbgthiq.html

Ruby: value = data || "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gt2edvbxqgh.html

C#:   var value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gt2bidwfult.html

[A16] 真假值判断规则
来源：http://dali.sxryk.cn/Article/details/gt2iclpcodo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gt2usacxldd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yangfankeji.com/Article/details/gt2wztdeows.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tian-w.cn/Article/details/gt2vwdnitip.html

TS:   if (!x) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2oevqqahr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qirzotht.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yongpay.top/Article/details/gt2jqgzcpfq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cheryme.top/Article/details/gt2fjfsyzfu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2flanckzz.html

[A17] 位运算
来源：http://dali.guannengcc.top/Article/details/gt2kttggpcr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gt2tnhrswmc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2ybyviupe.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2afbasfyi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gt2vqnwjiwx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2mvcvvxkv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gt2dqevqkwv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2lpqvantu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2yayokmck.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhongyouzk.top/Article/details/gt2jrpwazwu.html

Py:   ord("A"); chr(65)
来源：http://dali.svipenyu.cn/Article/details/gt2dbktarnx.html

PHP:  ord("A"); chr(65)
来源：http://dali.svipenyu.cn/Article/details/gt2caselays.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gt2crrybfkq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj202588.top/Article/details/gt2bvyittkx.html

Java: (int) 'A'; (char) 65
来源：http://dali.nanxuanxn.top/Article/details/gt2etnwtwwt.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sufxvd.cn/Article/details/gt2dgbgqbfy.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gt2xuhgzzpk.html

C#:   (int)'A'; (char)65
来源：http://dali.meibo888.top/Article/details/gt2yobpvptc.html

[A19] 交换两个变量
来源：http://dali.cucudq.cn/Article/details/gt2lrqfafyy.html

Py:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gt2cljnrqjj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.316326.xyz/Article/details/gt2ddfkeuxp.html

JS:   [a, b] = [b, a];
来源：http://dali.guannengcc.top/Article/details/gt2wwyiywlf.html

TS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gt2qvxxqger.html

Java: int t = a; a = b; b = t;
来源：http://dali.gotoacloud.top/Article/details/gt2vbluhudc.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gt2pznrlcms.html

Ruby: a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gt2rcngiess.html

C#:   (a, b) = (b, a);
来源：http://dali.xylfe.cn/Article/details/gt2ztqwlnxk.html

[A20] 读取标准输入
来源：http://dali.zhixingplan.top/Article/details/gt2yonxduzt.html

Py:   name = input("请输入：")
来源：http://dali.gotoacloud.top/Article/details/gt2slxhpstz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.guowangkeji.top/Article/details/gt2drbsexaq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urrryqyu.html

TS:   // Node.js：readline 模块
来源：http://dali.shuidangran.top/Article/details/gt2rggaizth.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xinyue.icu/Article/details/gt2rfkphogh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guannengcc.top/Article/details/gt2uivnqjgh.html

Ruby: gets.chomp
来源：http://dali.birdmap.top/Article/details/gt2nswuqihl.html

C#:   Console.ReadLine();
来源：http://dali.guannengcc.top/Article/details/gt2uweqaqgh.html

[A21] 保留指定小数位输出
来源：http://dali.c1oappe.top/Article/details/gt2nanywutk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhengqikj.top/Article/details/gt2qsbnezes.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gt2zvbtsnqv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gt2kzjsdzlg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gt2btfnrjgv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gt2lqvzmouk.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gt2ikomwnje.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gt2dxoqnhpa.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bouslrab.html

[A22] 获取字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2agoqcefp.html

Py:   len(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ukmrmtps.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenzaomai.com/Article/details/gt2ekemjvtp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yuanzhike.top/Article/details/gt2ohotvdwr.html

TS:   s.length
来源：http://dali.redwolf501.top/Article/details/gt2fibgtvqd.html

Java: s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2yviogsuc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ltibizwz.html

Ruby: s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwieozgr.html

C#:   s.Length
来源：http://dali.ydzc1.top/Article/details/gt2ymqqcexv.html

[A23] 大小写转换
来源：http://dali.tanke756.top/Article/details/gt2pvffypij.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hywenlv.cn/Article/details/gt2pyyulmwl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj202588.top/Article/details/gt2oyvrsrxn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gt2ibqdbbts.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigfzy.top/Article/details/gt2wcncyayo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gt2njsempes.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jiagoushi.top/Article/details/gt2jgangllu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2zwtaxxyh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.quarkkingdee.top/Article/details/gt2jvjiqtdx.html

[A24] 去除首尾空白
来源：http://dali.pycfn.com/Article/details/gt2wfyapzur.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.nwbrower.top/Article/details/gt2ypgtzjep.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.quarkkingdee.top/Article/details/gt2rwozfgxk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cucudq.cn/Article/details/gt2hsfinlgl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.haohaochexian.top/Article/details/gt2hfnjdvbl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xziqi.cn/Article/details/gt2stcjvvco.html

Go:   strings.TrimSpace(s)
来源：http://dali.guowangkeji.top/Article/details/gt2prampxxo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenlongwang.top/Article/details/gt2ovhxdamn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hammf.cn/Article/details/gt2gdzjjaik.html

[A25] 字符串比较
来源：http://dali.zhongyouzk.top/Article/details/gt2jvaivrhd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hongshengwenyu.top/Article/details/gt2yujkfcjw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zycfv.cn/Article/details/gt2fdufpkgj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guowangkeji.top/Article/details/gt2ehxyrvla.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2uostsheu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yueranfly.top/Article/details/gt2mbsaiyym.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gt2mpwlrdss.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gt2cmdbqdip.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gt2mmoeldqn.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sdwstxuy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ydzc1.top/Article/details/gt2fbcqweml.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guannengcc.top/Article/details/gt2fhsmidhq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aibaodan.cn/Article/details/gt2dozgimxn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrnluhjh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gt2wyxfgqai.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gt2omqzlfry.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gt2uozkbhlx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gt2npygtdtm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2dwubnojs.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gt2fsxyjnaq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2wiypiryt.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gt2lbpqxahd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dianchejie.cn/Article/details/gt2hxpixyfv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xdgqavpv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gt2cumerrfl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gt2gnytcdpg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2ztvmuttq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlpsoeks.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgbfffkm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2jjirmapo.html

[B02] 多分支 else if / elif
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smaokzjc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jianghu66.top/Article/details/gt2jjdsxeay.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.havefunace.top/Article/details/gt2mzzxldif.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvbjzxcb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clejnldm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2umblkeat.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nwbrower.top/Article/details/gt2lsiuabyr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.vqdsnc.cn/Article/details/gt2hudnmiou.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2bwcnaolr.html

[B03] switch / match / case
来源：http://dali.jinqigufen.top/Article/details/gt2bcdwxigk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.kuanghao11.cn/Article/details/gt2jgztdaag.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdlkzzbg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hdpuhjsv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2arvmvzxa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fucpqwzf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2tnhozzph.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gt2oxcmprwv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cheryme.top/Article/details/gt2kreptpoy.html

[B04] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2fesuwjqk.html

Py:   for i in range(10): print(i)
来源：http://dali.xuanzx.com/Article/details/gt2dggwlekh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jlsjyb.cn/Article/details/gt2quifscka.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfnyshhw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gt2uzppgkcx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gt2htdhomir.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenlongwang.top/Article/details/gt2xazohrmm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigfzy.top/Article/details/gt2yhmuzydy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yvedp.cn/Article/details/gt2rhkpfpfy.html

[B05] 遍历数组 / 列表
来源：http://dali.ydzc1.top/Article/details/gt2iqjuljdz.html

Py:   for item in arr: print(item)
来源：http://dali.ybcxt.top/Article/details/gt2drasrsma.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zxebjvkz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gt2bgmnofnw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2gkqjkjac.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2beaeaucc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gt2mqegilbs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigufen.top/Article/details/gt2lpcogela.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uhbjqwkk.html

[B06] 遍历字典 / 对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkjrbyrz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuanzhike.top/Article/details/gt2hbtmpxuf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258888.top/Article/details/gt2eihgfgsl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gt2tubvaqyi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gt2auicjrcw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sxryk.cn/Article/details/gt2qmtfftdx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ybcxt.top/Article/details/gt2dkfmcrnm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daxiang520.top/Article/details/gt2kutkoliu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shzxlz.cn/Article/details/gt2rwfuwxon.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgdrnude.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gt2vaephjxw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2wppvzyqr.html

JS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mueemphi.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2hhfmxtvk.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2bhqlggfh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xziqi.cn/Article/details/gt2mldlnmlj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gt2mufuticv.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2biikjgjq.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gt2qmtnhcsd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gt2hvcewrge.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kprxjcla.html

JS:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2fegtfoec.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gt2xyidnohh.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2kqhomwvd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqynuifa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixxzxqsg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnydjzod.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gt2hdjaawgo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gt2peqiaoms.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2wfaldutb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2nvycjgse.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gt2ddkewxgl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gt2walxnawx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sufxvd.cn/Article/details/gt2pzeovuqa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gt2vevqtivf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2hobzyjqs.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gt2yiilebpq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tgyosvkx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cqqwz.cn/Article/details/gt2grreurxt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzaspage.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2ynfkukeu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gt2hwtlmpcm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jyoumei.cn/Article/details/gt2eoggsqhf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gt2apjwwtyo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gt2kyudwolr.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gt2lggoixdy.html

Py:   list(range(0, 10, 2))
来源：http://dali.redwolf501.top/Article/details/gt2kesqtjyo.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2lwbhngra.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2ijgberjr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gt2lcjuprhf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2krkbbwrw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.smart0.xyz/Article/details/gt2lhaaisbz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwunmrls.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuxming.cn/Article/details/gt2awijigvn.html

[B12] 跳出多层循环
来源：http://dali.guannengcc.top/Article/details/gt2ycbxsxop.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gt2rgecgewb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gt2tzuynucc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2wuqqswkq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gt2qrtrsicr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gt2sozmotqn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.c1oappe.top/Article/details/gt2sasiapxp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gt2njbjpigg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyplutes.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvotniob.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gt2mpvphgmy.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gt2ocdwuvop.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyyitjkk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2gpzerfzw.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gt2gxgkobou.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gt2nxyasrop.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cucudq.cn/Article/details/gt2qmndaomp.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gt2ohksqezz.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gt2zgijvjty.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gt2eixqqfon.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gt2sgczhayr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gt2ypjjhwxo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2unmldnck.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pqquwyea.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gt2spmwbopg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2irnflhlh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gt2erglqocr.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gt2qgesfgay.html

Py:   a and b or not c
来源：http://dali.jqgfzy.top/Article/details/gt2yvqmqsjk.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbzphigl.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2ydxqhuvp.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2ygeeuiuk.html

Java: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2pdgicxjp.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2wzgrvgul.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2sadzsijw.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvbsojzx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xinyue.icu/Article/details/gt2aljhrdjd.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gt2vifracgo.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cyxtgnbp.html

JS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gt2yohoazrm.html

TS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gt2ocvksvvh.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2petwtfpf.html

Go:   if data == nil { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2bafbqzrw.html

Ruby: return if data.nil?
来源：http://dali.sufxvd.cn/Article/details/gt2kmbumdkg.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gt2ojkzbldg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtrdoqne.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rusdjbfg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2kialjuep.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2zxjplxca.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzudwsuo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2aedastlm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2ppfvriiw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pggspocj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2rdtollbn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2kfxdolpf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gt2khqaywyg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2bolrdoef.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gt2jicyvaqj.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gt2xocpknnn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsuslsl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2opdcorim.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2nzkbsqyy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gt2pdakwpix.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xziqi.cn/Article/details/gt2jrsvjwfx.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gt2rzfrcomy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gt2fbqimgma.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gt2wlgajter.html

Py:   def total(*args): return sum(args)
来源：http://dali.havefunace.top/Article/details/gt2jpkyyebj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigufen.top/Article/details/gt2fwfwwnai.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gt2lmjdxuuc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gt2tthbayby.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gt2awaqfijw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gt2xqbbqwej.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gt2udzqnvjb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gt2ohxdnybi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gt2ntggfdvc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuxbulcz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gt2hhqlvemf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2imbhflru.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gt2hbibzklt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gt2skyrgsrd.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gt2qygxtzpo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2zneoiyis.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2ewoqirti.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gt2pnewdpco.html

Py:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gt2utuyuirz.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gt2nllfgqcb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gt2uznwptnb.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2crnafwls.html


<!-- 参考信息 -->