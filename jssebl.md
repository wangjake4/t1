代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtoyzzbaxe.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cqqwz.cn/Article/details/gtsuvmcdzd.html

Go:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtvviebtoc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhengqikj.top/Article/details/gtnnrhjfmz.html

C#:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtorrjtxik.html

[A15] 空值判断与默认值
来源：http://dali.meibo888.top/Article/details/gtgzgcnfel.html

Py:   value = data or "默认值"
来源：http://dali.hongshengwenyu.top/Article/details/gtdlwfcyrk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdahhjadt.html

JS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtwfjcrbye.html

TS:   const value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtowhulcib.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nwbrower.top/Article/details/gtfitbpqzb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.mhx1999.top/Article/details/gtvqngixka.html

Ruby: value = data || "默认值"
来源：http://dali.zdqjudy.top/Article/details/gteewptllq.html

C#:   var value = data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtgeorrtog.html

[A16] 真假值判断规则
来源：http://dali.daria6918.cn/Article/details/gtjdylaqjv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sxryk.cn/Article/details/gtdoapxxru.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sysykeji.top/Article/details/gtnjwqohfq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gtqrebpkac.html

TS:   if (!x) {}
来源：http://dali.yj20258888.top/Article/details/gtcfrmhgeb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlakusauv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zycfv.cn/Article/details/gtazyigmxy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhixingplan.top/Article/details/gttcnudneg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjjwonmfr.html

[A17] 位运算
来源：http://dali.cdnleiting.top/Article/details/gtrxvnkuhg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtnzabzxym.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xinyue.icu/Article/details/gtlvusmifa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtlttjupzg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtlwyyjhvr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtbxfchnye.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtxtgwskqz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtvemddkbp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtoltuqzhe.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yanxiufei.cn/Article/details/gtowzwqjdz.html

Py:   ord("A"); chr(65)
来源：http://dali.hfpthk.cn/Article/details/gtnmfkxrgh.html

PHP:  ord("A"); chr(65)
来源：http://dali.hywenlv.cn/Article/details/gttfswxhvh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj202588.top/Article/details/gtrccswbdb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.redwolf501.top/Article/details/gtqkmepaev.html

Java: (int) 'A'; (char) 65
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziyhcmft.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigufen.top/Article/details/gtokfitowc.html

Ruby: "A".ord; 65.chr
来源：http://dali.hywenlv.cn/Article/details/gtarnwmalu.html

C#:   (int)'A'; (char)65
来源：http://dali.shuidangran.top/Article/details/gtfqntjbeg.html

[A19] 交换两个变量
来源：http://dali.havefunace.top/Article/details/gtloudqzur.html

Py:   a, b = b, a
来源：http://dali.tanke756.top/Article/details/gtjzyjofgi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ivvv.top/Article/details/gtgdplrbva.html

JS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gtafnpyxer.html

TS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gtrbfuplpy.html

Java: int t = a; a = b; b = t;
来源：http://dali.andypj.xyz/Article/details/gttgtxhiii.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtnusxuqtp.html

Ruby: a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gtbqwsocnj.html

C#:   (a, b) = (b, a);
来源：http://dali.c1oappe.top/Article/details/gtgbbniokb.html

[A20] 读取标准输入
来源：http://dali.bjfxy.top/Article/details/gtpbdotzcv.html

Py:   name = input("请输入：")
来源：http://dali.vqdsnc.cn/Article/details/gtsopxqpjl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xziqi.cn/Article/details/gtltlhergx.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yanxiufei.cn/Article/details/gtkrdtixfj.html

TS:   // Node.js：readline 模块
来源：http://dali.zdqjudy.top/Article/details/gtkfrjlrbp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuohwojks.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.fzhhl.top/Article/details/gtvguufcyy.html

Ruby: gets.chomp
来源：http://dali.feifeiyinyue.top/Article/details/gtrhedmptz.html

C#:   Console.ReadLine();
来源：http://dali.chenlongwang.top/Article/details/gtzqynfdvv.html

[A21] 保留指定小数位输出
来源：http://dali.bjfxy.top/Article/details/gtxllisgqz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gtlgtnwlxa.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtxjwepnok.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtwoulbnkx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtpythmeem.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtypdshgnm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtqooyjesg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsrvftfic.html

C#:   3.14159.ToString("F2")
来源：http://dali.gogol.net.cn/Article/details/gtcntygwgm.html

[A22] 获取字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtclkiolrz.html

Py:   len(s)
来源：http://dali.hnqzz.top/Article/details/gttlvhwegs.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shangyingyoupin.top/Article/details/gtkcrtloge.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.redwolf501.top/Article/details/gtdwiqzunl.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtmqnlotar.html

Java: s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtiqhhilcm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj202588.top/Article/details/gtolxcifbl.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gtevdmatue.html

C#:   s.Length
来源：http://dali.yj202588.top/Article/details/gtfzgqaujf.html

[A23] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtxkfebxvh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yangfankeji.com/Article/details/gtkjfvztlo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gtxbryyvqx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gtaryibxuf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhiwuduotai.top/Article/details/gticwwsbvh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtoxeulxsr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gaohongyu789.top/Article/details/gtlkrvzvof.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtnvrrkqaw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuanzx.com/Article/details/gtywltamjm.html

[A24] 去除首尾空白
来源：http://dali.gogol.net.cn/Article/details/gtmeeghmtk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yj20258.top/Article/details/gtcfqxvmyc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmvohekk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ivvv.top/Article/details/gtftyxehrw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtnggocvol.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.birdmap.top/Article/details/gtncqeqtxu.html

Go:   strings.TrimSpace(s)
来源：http://dali.0kj1m.cn/Article/details/gtgldxqxae.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqtwkgyc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dianchejie.cn/Article/details/gtssgcxszc.html

[A25] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtrczbjspd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnctiaga.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuanzx.com/Article/details/gtvrlxmexd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gteuzkedhz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenlongwang.top/Article/details/gtcpqkgdsp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gtmdwbfaks.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.316326.xyz/Article/details/gtacdwnedd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gtrnpeemlk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gtgecwvqug.html

[A26] 类型转换总览
来源：http://dali.yangfankeji.com/Article/details/gtukrbnljy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfgfsing.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gtsgymcnpp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuetiantiany.cn/Article/details/gtaztwrepx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhongyouzk.top/Article/details/gtrvyirlkf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gtntwcibwf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.iojbl.cn/Article/details/gtcipnrhmu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pycfn.com/Article/details/gtcrbgnlgv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtslggziwc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcijbiauq.html

B. 流程控制
来源：http://dali.yuanzhike.top/Article/details/gtolymdlhu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtoevyqeat.html

[B01] 条件判断 if / else
来源：http://dali.tian-w.cn/Article/details/gtgdsmvhga.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gtuhythpif.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtnlfqgsyi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtzdvjnmru.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtdqqlvtzp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fzhhl.top/Article/details/gtbfvqcvxz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yongpay.top/Article/details/gtxiegnmhu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gtpoibdcbi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtzsnwgihd.html

[B02] 多分支 else if / elif
来源：http://dali.xylfe.cn/Article/details/gtqofdwjcs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.birdmap.top/Article/details/gtjmhqvisv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cheryme.top/Article/details/gtbfjhoipd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtmlsiyqvm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gtzwnkasog.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtjwxtfpak.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gttesqvumd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cucudq.cn/Article/details/gtukahoaem.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtuxtwbvvz.html

[B03] switch / match / case
来源：http://dali.gogol.net.cn/Article/details/gtoelzlfxz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yanxiufei.cn/Article/details/gtbicokghq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtbmjjxnyq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtcpgwkyog.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtioxostqm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gtdbeedywx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gtulagshcp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cqqwz.cn/Article/details/gtmiryorjg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtmtcbhpmp.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtyaxpnbin.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtasrmdtgj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.birdmap.top/Article/details/gtkxafdupe.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtthyzztog.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtuuplbhsd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zycfv.cn/Article/details/gtaqzhngiv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinqigufen.top/Article/details/gtiqbeqlqd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jlsjyb.cn/Article/details/gtarffxbci.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzapzqgqc.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtkcehpgub.html

Py:   for item in arr: print(item)
来源：http://dali.c1oappe.top/Article/details/gtbdhpipka.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yangfankeji.com/Article/details/gtsicvaqau.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhrktqvr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ydzc1.top/Article/details/gtzuvvxqyi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.c1oappe.top/Article/details/gtapkhrgzs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhengqikj.top/Article/details/gtqeqktxfy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cucudq.cn/Article/details/gtlpqzfcbr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtzeozthbm.html

[B06] 遍历字典 / 对象
来源：http://dali.yongpay.top/Article/details/gtqhqjhytc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.bjfxy.top/Article/details/gttciqtnkl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zycfv.cn/Article/details/gtsmblscob.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gtugvvcvqn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gtyxovnaqk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aizwys.cn/Article/details/gtmhbrgres.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtrotuclxo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gtllyoqlbj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtwxagrrss.html

[B07] while 循环
来源：http://dali.nwbrower.top/Article/details/gtezcrilzw.html

Py:   while i < 10: i += 1
来源：http://dali.quarkkingdee.top/Article/details/gtvkzeggle.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhixingplan.top/Article/details/gtloutxgpy.html

JS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtwgaqdcwy.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtojoxxbua.html

Java: while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtjpwvttgl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gttummnens.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gtaonnkksr.html

C#:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtwfempifp.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gtxomhxmlz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gtceohrmpu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtthmizkzj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtstahmmoo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtydkhnxin.html

Java: do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtqyilcbtj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xziqi.cn/Article/details/gtutjyyebu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nwbrower.top/Article/details/gtijdzvqzh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtvbwuxuvj.html

[B09] break 与 continue
来源：http://dali.haohaochexian.top/Article/details/gtuzalpuae.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnxiangtu.top/Article/details/gtlqeffjyt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtkzitiska.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtunjdvvts.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtqofmpbda.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxogivfxh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtzzlryioi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gtjqglhvjs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtconetoqn.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gtprtkytmz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtwvoeicul.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.birdmap.top/Article/details/gtqbdvbiwd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtfyynncri.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvsrzfme.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gtenrpwxiq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgufenzy.top/Article/details/gtsutzkxce.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guowangkeji.top/Article/details/gtulpjzvuf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hysaishi.cn/Article/details/gtagqjbvdg.html

[B11] 生成数字序列 / 区间
来源：http://dali.hysaishi.cn/Article/details/gtgpsnkuln.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtseqbpcjg.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtvcxvojoj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtciwrextp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtiskjkofp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gtarjuazia.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gtsfqohwia.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtcnzaqxzb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gtpaxhxpfj.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtihbkazds.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.quarkkingdee.top/Article/details/gtkrjbafeo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gtizjqxxbb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtbmdaaklo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtkeuhactt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtwqcyusnl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtbyqmkbxo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gtfmzagkeq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gtnzriljsl.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtpurfntsk.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gtpcichfqs.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtnhwtlhxs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtnbljzmeg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gteitdnkkb.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gtypaqujtl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gtfvywhklo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gtsiklvswz.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gtovbnbyhb.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gtsrwotgge.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoublbtl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdlcpxrk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtutnxqxht.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtgkhukzfp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gthduualbz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtomcnzhun.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gtljferbbt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtcpzxzudn.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gtulewcshi.html

Py:   a and b or not c
来源：http://dali.fzhhl.top/Article/details/gtfkfnjcmj.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gttcsgudtb.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtczozwbcj.html

TS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtetfnxdqx.html

Java: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtttipdeaf.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtfqklbulb.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtqctmaopr.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtzwzjtrip.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gtpymkxmtk.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtugqmbcgi.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gtsorehdko.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtxggsyaez.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtaaheixaq.html

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gtgxkhslfu.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtxpimqmgn.html

Ruby: return if data.nil?
来源：http://dali.hnxiangtu.top/Article/details/gtgbbebbgx.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtmcupezhv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqqrioyut.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtdgbejnrn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtueziushq.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gtxnetwayy.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtxlnrmgzx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtfjzbdryo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtihlhcpzg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwnjvzyb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrayuojcp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtvsbhlsqk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gttsbfulzw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtcemouqxg.html

[C02] 默认参数
来源：http://dali.yangfankeji.com/Article/details/gthjvfifqd.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gtprmuwrei.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gtkgcwbwbn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtsukppagu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtrhkazvqo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtiebwpoek.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtpwqtykzb.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptnbgpyo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jianghu66.top/Article/details/gtqnmnkjcf.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gttwmjglcz.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtarumxjyl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtzvvjmtxn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtornnyvli.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtuywltwlv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtpnyzzcri.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gtzboldkeq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwahtuzqx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtoouhuahl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gtnpgoqziz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gtbxiqwiyd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtpsrglcbw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtsdhfajqu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtiavfrkrt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gtpzwhcuim.html

Go:   // 无：用配置结构体参数
来源：http://dali.cashguo.top/Article/details/gtwfrzrddy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtgwscatlt.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtmkzxtira.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gttochisqn.html


<!-- 参考信息 -->