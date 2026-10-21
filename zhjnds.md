代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gtustjbceq.html

TS:   const value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gttfkstuai.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ivvv.top/Article/details/gtgqclqdph.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.vqdsnc.cn/Article/details/gtaxeyumtn.html

Ruby: value = data || "默认值"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtboprcyil.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtvvvyrvyz.html

[A16] 真假值判断规则
来源：http://dali.zhongyouzk.top/Article/details/gtdpjrinby.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hfpthk.cn/Article/details/gtkegiwzhp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.andypj.xyz/Article/details/gtjazccjnb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aizwys.cn/Article/details/gtrglghmgw.html

TS:   if (!x) {}
来源：http://dali.nanxinkj.top/Article/details/gtzwvvthmp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangdashe.top/Article/details/gtieeexpja.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cdnleiting.top/Article/details/gtinvddcpf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258888.top/Article/details/gtekjcmcyc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtpumhmqtt.html

[A17] 位运算
来源：http://dali.zhengqikj.top/Article/details/gtqbsxrrco.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmujdcslg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtbohobxav.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtfsuwhmls.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtpsjuwpxo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtxhnbklap.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtecjjxero.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtyhmzckab.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtyaaytejq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gtgegasxyu.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gtvroekyxr.html

PHP:  ord("A"); chr(65)
来源：http://dali.xinyue.icu/Article/details/gtqrjjtnmb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtufhditeu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgokxonf.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gtbxuvipyz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.pengpengdd.cyou/Article/details/gtbbncqauj.html

Ruby: "A".ord; 65.chr
来源：http://dali.jqgufenzy.top/Article/details/gtolyhyhqr.html

C#:   (int)'A'; (char)65
来源：http://dali.havefunace.top/Article/details/gtvtwpfjot.html

[A19] 交换两个变量
来源：http://dali.yangfankeji.com/Article/details/gtpyefhaus.html

Py:   a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gtienxwuyo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aibaodan.cn/Article/details/gtsgyfziqf.html

JS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtlbhudvxc.html

TS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gterjiuing.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gtspwnxgvb.html

Go:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtnphtewpg.html

Ruby: a, b = b, a
来源：http://dali.yuxming.cn/Article/details/gtfsbaasai.html

C#:   (a, b) = (b, a);
来源：http://dali.andypj.xyz/Article/details/gtlpgjdnof.html

[A20] 读取标准输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnyraopp.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gtyjbnpprp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhengqikj.top/Article/details/gtmkwrexec.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdgcxqom.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gtfsaiczgl.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.mhx1999.top/Article/details/gtfeimudxh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xziqi.cn/Article/details/gtffzwennq.html

Ruby: gets.chomp
来源：http://dali.gogol.net.cn/Article/details/gtunazngpj.html

C#:   Console.ReadLine();
来源：http://dali.jlsjyb.cn/Article/details/gtljhfwklc.html

[A21] 保留指定小数位输出
来源：http://dali.yongpay.top/Article/details/gtovlhkgsm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ivvv.top/Article/details/gtisilvuan.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtqthcjzzg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtwmzdlesb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtmtmvpuwr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtwdeyybmr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwluisna.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtykamqxyb.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gtuhrecinj.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtrefnrrpr.html

Py:   len(s)
来源：http://dali.yj20258888.top/Article/details/gtnruazheu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gtrtyllfvw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gogol.net.cn/Article/details/gtmgjeyifa.html

TS:   s.length
来源：http://dali.dashuyun.cn/Article/details/gttnrdqorv.html

Java: s.length()
来源：http://dali.yangfankeji.com/Article/details/gtzljfjonz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.iojbl.cn/Article/details/gtypjspfec.html

Ruby: s.length
来源：http://dali.cucudq.cn/Article/details/gtvxuepthd.html

C#:   s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtbmygnwbi.html

[A23] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtcujzwedn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.vqdsnc.cn/Article/details/gtokwplrgy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gtrbabdvqh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtiebeyaqc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtnapduvvt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gtnikgwjem.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangdashe.top/Article/details/gtbtyunvaa.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtntuidyij.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zdqjudy.top/Article/details/gtloufrusu.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangtech.top/Article/details/gtngdetdnt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aibaodan.cn/Article/details/gtqrobrbaw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gtluisjctw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtonsgwbre.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gtmgtjgalo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.feifeiyinyue.top/Article/details/gtfvxzqncv.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhixingplan.top/Article/details/gtrlmcgils.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hysaishi.cn/Article/details/gtpiyvyjrg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtlyitrdcd.html

[A25] 字符串比较
来源：http://dali.meibo888.top/Article/details/gthrvxqlsa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhoulong.xyz/Article/details/gtriuabemi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cheryme.top/Article/details/gtoamztucz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jianghu66.top/Article/details/gtwzrtyylr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gthpmoyfjg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ivvv.top/Article/details/gtpojentlt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gthvrrruqe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangdashe.top/Article/details/gtedymtlcd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtnfiwqkvo.html

[A26] 类型转换总览
来源：http://dali.hammf.cn/Article/details/gtgkbgvjwn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcraecba.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cashguo.top/Article/details/gtbdvcishi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fzhhl.top/Article/details/gtcurfeiou.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fzhhl.top/Article/details/gtbdtkenhz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gttpadyfvu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.vqdsnc.cn/Article/details/gtekkliuai.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yanxiufei.cn/Article/details/gtimhmswgy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.quarkkingdee.top/Article/details/gtplxhkjou.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdwxootse.html

B. 流程控制
来源：http://dali.yj20258.top/Article/details/gtfywyolqw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gterjwreuh.html

[B01] 条件判断 if / else
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbonhiffq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jyoumei.cn/Article/details/gtmkbidagb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xinyue.icu/Article/details/gtdpprgrym.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtyxsqpmqb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gttsqneyan.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtpxobzppu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhongyouzk.top/Article/details/gtxsqiolue.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gtywvehneg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtvpjcehxu.html

[B02] 多分支 else if / elif
来源：http://dali.hysaishi.cn/Article/details/gtcivbokvz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhongyouzk.top/Article/details/gtxcqztmqw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlbcqeedz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtgxbpfjfs.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtdttekiav.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtsxppasub.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gthqyruaqp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guowangkeji.top/Article/details/gthefyovqw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtxqpuntim.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtfczvpzra.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fzhhl.top/Article/details/gtnzbyeoal.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtnhkkzmmw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtbjrvrpqf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcswbguhr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtiizclccz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tanke756.top/Article/details/gtqaukksmg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.kuanghao11.cn/Article/details/gthbqrmtfj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yvedp.cn/Article/details/gttfiaqagn.html

[B04] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gtpkmfiiwr.html

Py:   for i in range(10): print(i)
来源：http://dali.yanxiufei.cn/Article/details/gtogqkqmiz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.snrcjt.cn/Article/details/gtqbjwmjeg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gtfbbarhea.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gtbcaolkph.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gthboydatu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gtrpqnjvdd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yuxming.cn/Article/details/gteeuvgnza.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteyibgfga.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gturustmhx.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtftueaouy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gtfohjwypv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtsakqdkfh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtjulzgmju.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenlongwang.top/Article/details/gtszlqkjus.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtvupbrtmq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cdnleiting.top/Article/details/gtzammliyh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gtnjzvtyzp.html

[B06] 遍历字典 / 对象
来源：http://dali.zhiwuduotai.top/Article/details/gtbfejwaaw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tanke756.top/Article/details/gtdpuhmqcn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenlongwang.top/Article/details/gtnxahblqv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtchjrymha.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtjgadelvq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.quarkkingdee.top/Article/details/gtnecvkghn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.havefunace.top/Article/details/gtyfpmzleo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gtmufwuqre.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtcfwzhbhu.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtghseykfk.html

Py:   while i < 10: i += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzsucofhv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dashuyun.cn/Article/details/gtbtrfwipm.html

JS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtfifnyhrj.html

TS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtwyxssncv.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gttmsfxbfe.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gotoacloud.top/Article/details/gtbloopdpc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fengsongda.top/Article/details/gtgencyqtk.html

C#:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgkaciaic.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvcmlfpj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gtcsrmalgc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gthglqzrof.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtgsipevsc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtordnqvst.html

Java: do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtcyqjpnfc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gththozbcw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtqjjiplfr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtblxsqhdd.html

[B09] break 与 continue
来源：http://dali.zhoulong.xyz/Article/details/gtcjtcgqdi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gtbiymqrpm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gthklhmjrb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtyenxdpdo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtukoivuov.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtiaipggmi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gttpwctmsw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gtpumdozhs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtyjxycxuu.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtnwoalkio.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gtxhikwtft.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gttcjwediw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtssoxbyiz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gtnbfsjxnk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gtcfvpvtiu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yvedp.cn/Article/details/gtxljdnsjv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtiigxxhyw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yuanzhike.top/Article/details/gtzkzsdeyx.html

[B11] 生成数字序列 / 区间
来源：http://dali.bjfxy.top/Article/details/gthmkswjjh.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gtwonqjoro.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigufen.top/Article/details/gtdiklelim.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gttjugrdnv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtnigxcxqq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yueranfly.top/Article/details/gtnlzivhes.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gtohfjeyyr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gogol.net.cn/Article/details/gtjttrolhv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtyivdahyg.html

[B12] 跳出多层循环
来源：http://dali.redwolf501.top/Article/details/gtrzxsfnaw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zycfv.cn/Article/details/gttjzzkiiu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gtwqrzkevo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtuczzdlhy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtkeeforwr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtbxlqnlya.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gtrwmkpzsu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtgqixhvmt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhihcxjj.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gtvwetpotg.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtnzpzpifu.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtrulfeuym.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtaixkbqcz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtmffplbyg.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtyhbdlegy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gtohevpclh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shzxlz.cn/Article/details/gtiipvrlxk.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gticqxwgaa.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtgprqtcuu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shangyingyoupin.top/Article/details/gtrnwdmxfm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtvcshpqnt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtrhgmnowx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtzcggqrnn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtdzfxorxa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxuanxn.top/Article/details/gtmjiniyei.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtzgyrkdhd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gttcpvawgz.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtrlpsulek.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtpnozkhex.html

PHP:  $a && $b || !$c
来源：http://dali.hywenlv.cn/Article/details/gtudpxxxyj.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtmbgkbycj.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtwiukatwn.html

Java: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtzaywhygy.html

Go:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjytumkj.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gthrrdvizw.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtrufultqe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.snrcjt.cn/Article/details/gtqjszdnxp.html

Py:   if not data: return
来源：http://dali.yj20258888.top/Article/details/gtddbqwabm.html

PHP:  if (!$data) { return; }
来源：http://dali.xylfe.cn/Article/details/gtuknqwepb.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnayjkhuk.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtqtflfstl.html

Java: if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtftuadcsz.html

Go:   if data == nil { return }
来源：http://dali.gaohongyu789.top/Article/details/gteiomgyih.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtppzzxuoj.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtpmsjbntk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtosmwjril.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gtzkootvlp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgjdqssbz.html

[C01] 定义函数
来源：http://dali.tanke756.top/Article/details/gtsbwxeomu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtaanmyynr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtyenexhll.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtgrfisnri.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtyrivtqqv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtwzjimpks.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gtyzxtwcpf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cqqwz.cn/Article/details/gtfzetjlus.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtiedrnysc.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtynceuebb.html

Py:   def greet(name="World"): return name
来源：http://dali.gaohongyu789.top/Article/details/gtbohloacu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuxming.cn/Article/details/gtmglqpxli.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtawwvgmfm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtezlebixe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gtghdcigqo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gtfwoypimw.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gtuhvaiafr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gtbvznwpyr.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtbcokzvsl.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtxzwzxpom.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtzvizblqn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtosaoebza.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttftvkblp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtxiukqmzi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtbugdcygt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuanzx.com/Article/details/gtfcyufzfh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtjblgypiz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuanzhike.top/Article/details/gtvvpzndhq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gtenrkvtxb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xinyue.icu/Article/details/gtwtfknaax.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtqmdfzwnm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtqbqozymp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtfgyzcbie.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtqwfxoqfj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoujkmafa.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtgwssraqp.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtjydcgclo.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gttylwpded.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gtufkouuum.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyhzmtmr.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuydkgnb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtpppolelu.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gthakeenme.html

Ruby: return a, b
来源：http://dali.sufxvd.cn/Article/details/gtlqxzvzfb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnknnvli.html


<!-- 参考信息 -->