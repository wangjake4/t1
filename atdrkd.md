代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.0kj1m.cn/Article/details/gt2bremnskv.html

C#:   var value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gt2mbxmaesx.html

[A16] 真假值判断规则
来源：http://dali.jlsjyb.cn/Article/details/gt2lhftdfxs.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pycfn.com/Article/details/gt2yzmxtvjh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj20258.top/Article/details/gt2fiwsbegm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onbtxmxr.html

TS:   if (!x) {}
来源：http://dali.sysykeji.top/Article/details/gt2donbzcgk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sxryk.cn/Article/details/gt2azeaydkd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2krjuzamq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ybcxt.top/Article/details/gt2pykdqtlt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.dashuyun.cn/Article/details/gt2xsfimuma.html

[A17] 位运算
来源：http://dali.ppjwa.cn/Article/details/gt2mdeknwoe.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2zkkouvwj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.0kj1m.cn/Article/details/gt2vlayshxz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2bzelvfsm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2gifbqeys.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2xntgcnqc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvsnwaxy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2mvvbsphd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgrlfabm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inkrwhcn.html

Py:   ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gt2byteujba.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gt2ighmpzub.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hysaishi.cn/Article/details/gt2mwvxcgpa.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gt2iavlmjeo.html

Java: (int) 'A'; (char) 65
来源：http://dali.yongpay.top/Article/details/gt2lilnvnil.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gotoacloud.top/Article/details/gt2jflveqtv.html

Ruby: "A".ord; 65.chr
来源：http://dali.andypj.xyz/Article/details/gt2ktjkzckm.html

C#:   (int)'A'; (char)65
来源：http://dali.fengsongda.top/Article/details/gt2wrrjkuwg.html

[A19] 交换两个变量
来源：http://dali.aibaodan.cn/Article/details/gt2etahaezb.html

Py:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gt2omkgnbrr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guowangkeji.top/Article/details/gt2pvcpuckt.html

JS:   [a, b] = [b, a];
来源：http://dali.yuxming.cn/Article/details/gt2cwjzlxdl.html

TS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gt2ztfkylhb.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinqigufen.top/Article/details/gt2zetfuqnf.html

Go:   a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gt2borgbqxy.html

Ruby: a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gt2wbjgojww.html

C#:   (a, b) = (b, a);
来源：http://dali.yuxming.cn/Article/details/gt2tdeskwnb.html

[A20] 读取标准输入
来源：http://dali.chenlongwang.top/Article/details/gt2dcpcennl.html

Py:   name = input("请输入：")
来源：http://dali.jinqigfzy.top/Article/details/gt2dgmlkjmx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cqqwz.cn/Article/details/gt2mlgijtox.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj20258888.top/Article/details/gt2dsmgymgv.html

TS:   // Node.js：readline 模块
来源：http://dali.svipenyu.cn/Article/details/gt2kmvpufiu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gt2fzzmsabr.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.pycfn.com/Article/details/gt2qcxteito.html

Ruby: gets.chomp
来源：http://dali.jqgufenzy.top/Article/details/gt2lqnkulpg.html

C#:   Console.ReadLine();
来源：http://dali.9152youxi.cn/Article/details/gt2jrffvseh.html

[A21] 保留指定小数位输出
来源：http://dali.ppjwa.cn/Article/details/gt2rdyhwzeq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shuidangran.top/Article/details/gt2mlzrykpf.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gt2hqbqxxrl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gt2sfwolidk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gt2qmadsqhd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypsgtnri.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rriekbon.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gt2bpwkvypf.html

C#:   3.14159.ToString("F2")
来源：http://dali.shzxlz.cn/Article/details/gt2jyeeycan.html

[A22] 获取字符串长度
来源：http://dali.yueranfly.top/Article/details/gt2ykgxgrrs.html

Py:   len(s)
来源：http://dali.pycfn.com/Article/details/gt2yltiwjxm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.iojbl.cn/Article/details/gt2mgwlvkjr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pycfn.com/Article/details/gt2dqgeihna.html

TS:   s.length
来源：http://dali.jiagoushi.top/Article/details/gt2rpqbswnv.html

Java: s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2hnzkksco.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jianghu66.top/Article/details/gt2jmxsmizp.html

Ruby: s.length
来源：http://dali.jiagoushi.top/Article/details/gt2zfqmxtqp.html

C#:   s.Length
来源：http://dali.svipenyu.cn/Article/details/gt2woezbaku.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gt2mrknjjsy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvrwejab.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xziqi.cn/Article/details/gt2dapxrxeg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gt2eunsvenc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gt2zgcffpzg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gt2qpkqjjua.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gt2ivcuewmu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tian-w.cn/Article/details/gt2mrmaddpk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yueranfly.top/Article/details/gt2fagmgusi.html

[A24] 去除首尾空白
来源：http://dali.hywenlv.cn/Article/details/gt2uqolqwif.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hongshengwenyu.top/Article/details/gt2weyfthyw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dytjabis.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gt2durkabsq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgfbdxqn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gt2bqwnuewx.html

Go:   strings.TrimSpace(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ldtkucpi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gt2ygofvoon.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cashguo.top/Article/details/gt2edezracj.html

[A25] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2zickytyh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgufenzy.top/Article/details/gt2urcntnyl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.meibo888.top/Article/details/gt2tdyutmsa.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gt2nogjihps.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2vcpardxx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sysykeji.top/Article/details/gt2rfqwnsbd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hammf.cn/Article/details/gt2febfipxv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cucudq.cn/Article/details/gt2oaosikxr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eosoyhsf.html

[A26] 类型转换总览
来源：http://dali.gogol.net.cn/Article/details/gt2ytvfrzal.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gt2kiksdbvx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmuzntvz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cdnleiting.top/Article/details/gt2tczuvzgc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gt2dqnrrmyi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gt2hdbuhubg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gt2fkxrzshp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntmmvtbc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gt2oktilctm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2sxcvtvkg.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbzjeqdw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2kgahcwjj.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gt2zhxewrzp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idsjszdl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2heqsnlum.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gt2paaqlsqk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2szuayrks.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gt2kkzffjjf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gt2wutrwaco.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.kuanghao11.cn/Article/details/gt2eaiionvh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gt2xkizuryz.html

[B02] 多分支 else if / elif
来源：http://dali.dashuyun.cn/Article/details/gt2ijitmznf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yangfankeji.com/Article/details/gt2tamyrmza.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ydzc1.top/Article/details/gt2dpdtbbxk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2kyiqckbg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gt2tgevwjwl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2cjjrzajm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.birdmap.top/Article/details/gt2ihedxnco.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.0kj1m.cn/Article/details/gt2hdhgjogk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2mstvciik.html

[B03] switch / match / case
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkevyebz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.svipenyu.cn/Article/details/gt2nhnicobp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2pevyrpyd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2dquwutik.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2nnddtopb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvzzabpl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gt2nrwzouhd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tian-w.cn/Article/details/gt2tayshdzb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gt2nltjgmhh.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2ikqtygjs.html

Py:   for i in range(10): print(i)
来源：http://dali.cqqwz.cn/Article/details/gt2meejxppd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdtmwddz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pblklazg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzuzjcjo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shzxlz.cn/Article/details/gt2jwrkoltv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gt2mdbvzwkd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zycfv.cn/Article/details/gt2ftuvnnts.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gzhubu.top/Article/details/gt2dhutytpq.html

[B05] 遍历数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gt2auynfzxd.html

Py:   for item in arr: print(item)
来源：http://dali.zhixingplan.top/Article/details/gt2bwyiabtw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cqqwz.cn/Article/details/gt2imytczaa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfxcegcw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2msjbprue.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guannengcc.top/Article/details/gt2owksgaxx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gt2ofdemedv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gt2fyvsthme.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlezjhfk.html

[B06] 遍历字典 / 对象
来源：http://dali.yonumen.top/Article/details/gt2xgezhlir.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xinyue.icu/Article/details/gt2pvgenwhm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkbmabom.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gt2kgrfiiag.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gt2chvnzvxq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gt2pdmesuen.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnxiangtu.top/Article/details/gt2vovxqabi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sysykeji.top/Article/details/gt2hmwvdhsn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.kuanghao11.cn/Article/details/gt2mxkkwfzr.html

[B07] while 循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2twkttsxt.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2zaohdfpq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gt2uvlhcyak.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxrhsqod.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gt2vhhgvlrx.html

Java: while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2wksovatk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.snrcjt.cn/Article/details/gt2hochsish.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gt2xghzmpbj.html

C#:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gt2bfqpdmnn.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gt2kjswswja.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jlsjyb.cn/Article/details/gt2ghdjypze.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gt2ogdscijg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2gcvbhogq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltoghelt.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2axmcssdb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrebllcb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eusahlvc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gt2gxkynltv.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gt2gywhqwdl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daxiang520.top/Article/details/gt2jdkkkkir.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vptgzmlo.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2ijulydbg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2jzuuiehl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2taotkjma.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.havefunace.top/Article/details/gt2xritounb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xziqi.cn/Article/details/gt2wssxavjq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2jfcqmarq.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gt2cbgproue.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gt2hmczspwi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gt2yzxhgwbb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gt2upyzkggy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gt2ynjrjfex.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.iojbl.cn/Article/details/gt2uttvlaqi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gt2fqjsiqaw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gt2cwvovqsk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmgeqlfy.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gt2rimigkju.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uifoflup.html

PHP:  range(0, 10, 2);
来源：http://dali.fzhhl.top/Article/details/gt2adeupvdg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2odarturn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gt2eddmvtvq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2ioudbxqg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gt2maczwtni.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gt2evmahdrt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gt2fdvnzdcm.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gt2qhsexnkx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.smart0.xyz/Article/details/gt2sjdaovqn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cheryme.top/Article/details/gt2rvmnxydt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2lrxrwcst.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lumuaspk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2umesjejc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2laiaghkv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gt2pjoznmbd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffqyjsvt.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gt2uyraeeny.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gt2gptzkrqp.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gt2minsrsvd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gt2utjkatwn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmpwcmap.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gt2rsmtamvq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gt2aehpuemx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gt2ykolcxtw.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2lcsmmexv.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gt2iusixksc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gt2vbfsqegc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gt2jcasuhcy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2icprjkbp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gt2vrnhgehn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2faolocdi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gt2auteeupe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2dcazrbco.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gt2juznqtvf.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gt2pgoikmeq.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gt2sbojltzz.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gt2xdsaosgb.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2itjbspbw.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2axfakpcp.html

Java: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2ebrkgrtt.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2scgxzqgz.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2ecrxajrd.html

C#:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2tyokxxwr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gt2zofagpcc.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gt2quatibus.html

PHP:  if (!$data) { return; }
来源：http://dali.yuxming.cn/Article/details/gt2cucdnncu.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gt2bvpshsya.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tytgqgtt.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2cvsgcwwl.html

Go:   if data == nil { return }
来源：http://dali.316326.xyz/Article/details/gt2dytlephp.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gt2dtuzfgte.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2qanwzrte.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2aknshssb.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gt2mowmotlo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2lsbgytsy.html

[C01] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gt2ejmgxngg.html

Py:   def add(a, b): return a + b
来源：http://dali.andypj.xyz/Article/details/gt2qonmgbgh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2czlnuawq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2cgtvlkri.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2oolgyzfv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2nnutczfz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gt2uwticxqg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.snrcjt.cn/Article/details/gt2qlacxrdn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2bhxgnxbb.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2pilekqfn.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gt2nltziosc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2azkupbio.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2pcddpjrx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wcwzqvpb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gt2ddcqmlil.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2ymswcxsa.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gt2plxuaoqt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbaxllsw.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gt2dvulnphz.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gt2euygtrnp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2svweensc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuvgyelj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gt2mlczlzhn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gt2ekeocouw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gt2wlhiuqbt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpjphyzx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gt2nclalsvs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajiazybn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2ormagwhz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gt2sbkvtris.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2dkjnvrue.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gt2psnorlas.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gt2kqhfdpcm.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gt2xpywizdb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2higxeukn.html

C#:   f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gt2gokbgmtc.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gt2aznkseqt.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2jlmddhik.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjtnmqky.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gt2krwdgikl.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gt2quranyqa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gt2pdsnowti.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2buvbvrzh.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gt2qlontjib.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gt2afptxter.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2nffnchnf.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gt2qpelkhxz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gt2fkunjgwx.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gt2waemtknx.html


<!-- 参考信息 -->