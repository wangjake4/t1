代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtznyvsbdy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jqgufenzy.top/Article/details/gtjdprkriy.html

Go:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gthidstpjp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpdpopmc.html

C#:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtwcvdgehc.html

[A15] 空值判断与默认值
来源：http://dali.cashguo.top/Article/details/gtzxdkeuea.html

Py:   value = data or "默认值"
来源：http://dali.jqgfzy.top/Article/details/gtculwdhrt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtwdpodwob.html

JS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtcijginht.html

TS:   const value = data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtgcifecxv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.birdmap.top/Article/details/gtyzwxokrg.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shangyingyoupin.top/Article/details/gtmpmovdax.html

Ruby: value = data || "默认值"
来源：http://dali.xinyue.icu/Article/details/gtpocagrrs.html

C#:   var value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtuijsuibg.html

[A16] 真假值判断规则
来源：http://dali.jlsjyb.cn/Article/details/gththlhlaj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.redwolf501.top/Article/details/gtojjmgmjc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfiinsna.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtmwlwviyl.html

TS:   if (!x) {}
来源：http://dali.jlsjyb.cn/Article/details/gtsiosnkbd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ivvv.top/Article/details/gtnrphgqys.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.wangdashe.top/Article/details/gtcxqpfosf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhoulong.xyz/Article/details/gtanavynyh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cheryme.top/Article/details/gtkatilzkk.html

[A17] 位运算
来源：http://dali.wangshuangyany.cn/Article/details/gtpkocmskt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtsjufdgpe.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.316326.xyz/Article/details/gtvdizwria.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtmccdymtc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gttunygdhs.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtltqcabss.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtebkfxjyw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtprcblqxd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtgswytntm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cucudq.cn/Article/details/gtokietdyo.html

Py:   ord("A"); chr(65)
来源：http://dali.dashuyun.cn/Article/details/gtfyajtbom.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtzeaezqyv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gtuvjjlusf.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.haohaochexian.top/Article/details/gtwhgnvllg.html

Java: (int) 'A'; (char) 65
来源：http://dali.tian-w.cn/Article/details/gtfpfomwnr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shanyushiyangtech.top/Article/details/gtucizugat.html

Ruby: "A".ord; 65.chr
来源：http://dali.yvedp.cn/Article/details/gtaygrvjyv.html

C#:   (int)'A'; (char)65
来源：http://dali.dianchejie.cn/Article/details/gtynhlgmnb.html

[A19] 交换两个变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivsfhfxl.html

Py:   a, b = b, a
来源：http://dali.svipenyu.cn/Article/details/gtjwlphgxk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveackmez.html

JS:   [a, b] = [b, a];
来源：http://dali.vqdsnc.cn/Article/details/gtsdwwrecu.html

TS:   [a, b] = [b, a];
来源：http://dali.tanke756.top/Article/details/gtyspdkmzl.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gtfnivobzp.html

Go:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtotlqzbys.html

Ruby: a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gtzaawtvjy.html

C#:   (a, b) = (b, a);
来源：http://dali.yuxming.cn/Article/details/gtvwmwskah.html

[A20] 读取标准输入
来源：http://dali.mhx1999.top/Article/details/gtgbtfmavc.html

Py:   name = input("请输入：")
来源：http://dali.daxiang520.top/Article/details/gtgfdelold.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.quarkkingdee.top/Article/details/gtlihrevrm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sweek.top/Article/details/gtrkghwoxp.html

TS:   // Node.js：readline 模块
来源：http://dali.yj202588.top/Article/details/gtlwnlpkuh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jqgufenzy.top/Article/details/gtkyrhjfpq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.fzhhl.top/Article/details/gtnhssobla.html

Ruby: gets.chomp
来源：http://dali.gogol.net.cn/Article/details/gtzdwsptqp.html

C#:   Console.ReadLine();
来源：http://dali.chenjidiqi.icu/Article/details/gteqqgktns.html

[A21] 保留指定小数位输出
来源：http://dali.hongshengwenyu.top/Article/details/gtzyqahnuy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yonumen.top/Article/details/gtcltqdows.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtovediboi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtzgqhjivo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtgyzdrqnq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtrvdaxdhd.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtpavsxhph.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtxkujxygg.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnqzz.top/Article/details/gtfyuqfzeo.html

[A22] 获取字符串长度
来源：http://dali.pycfn.com/Article/details/gtgykdcdsx.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gtjwppxjtw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nwbrower.top/Article/details/gtopacluta.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.fzhhl.top/Article/details/gtbglfhtve.html

TS:   s.length
来源：http://dali.xuanzx.com/Article/details/gttmzxcjgm.html

Java: s.length()
来源：http://dali.gotoacloud.top/Article/details/gtmcxqqxbk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.snrcjt.cn/Article/details/gtcaxybkgy.html

Ruby: s.length
来源：http://dali.yangfankeji.com/Article/details/gtoeytceik.html

C#:   s.Length
来源：http://dali.ivvv.top/Article/details/gtdvcistuq.html

[A23] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtjqsyites.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gotoacloud.top/Article/details/gtojfxsuuh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gzhubu.top/Article/details/gtmoyroiyp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gogol.net.cn/Article/details/gtqgoikclu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtfelfmqqk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtdtbopczu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jlsjyb.cn/Article/details/gtoqwlbnvt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yongpay.top/Article/details/gtbevtspoj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.daria6918.cn/Article/details/gtkxtzecbc.html

[A24] 去除首尾空白
来源：http://dali.9152youxi.cn/Article/details/gtvmxrupfi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ydzc1.top/Article/details/gtdxafmhen.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.pycfn.com/Article/details/gtwsvwscsj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtqasdhgqk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gtzqmssqao.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cheryme.top/Article/details/gtqflzrwvr.html

Go:   strings.TrimSpace(s)
来源：http://dali.fzhhl.top/Article/details/gtivzcmtob.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.quarkkingdee.top/Article/details/gthoohzyvw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.316326.xyz/Article/details/gtiwxdtudc.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtjcdtgkrv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jlsjyb.cn/Article/details/gtywnzydtm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ivvv.top/Article/details/gtkrnuvexz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfeamdrs.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtcddoqjsc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtspsrbpsl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gthcmbpnax.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhiwuduotai.top/Article/details/gtxsiolanx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gtymwdmqjn.html

[A26] 类型转换总览
来源：http://dali.yanxiufei.cn/Article/details/gtifvbxlyj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gaohongyu789.top/Article/details/gtadjxdopg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuanzhike.top/Article/details/gtjbroaihv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gtpbstldob.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvenecmdk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtriekrsdu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gtyiityisx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gtqdltvgzp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gtgakldezz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjhmpdbmn.html

B. 流程控制
来源：http://dali.c1oappe.top/Article/details/gtpvynswba.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttgcozecl.html

[B01] 条件判断 if / else
来源：http://dali.hnxiangtu.top/Article/details/gtopmjhohf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.iojbl.cn/Article/details/gtlbwwaovk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sufxvd.cn/Article/details/gtdgprxsks.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtjxdzuqbs.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtowiarlhn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gtlgrcefaq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.dashuyun.cn/Article/details/gtmoqisumb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.vqdsnc.cn/Article/details/gtkjfcjaww.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtosvjsqor.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gtzxxlksnd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.c1oappe.top/Article/details/gtuarwufcz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.bjfxy.top/Article/details/gtixgbkyvg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtovdxxxvf.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtgfqklesk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojxshmvw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gttwyrbuxv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xylfe.cn/Article/details/gthohglefc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtifgmwkfr.html

[B03] switch / match / case
来源：http://dali.dashuyun.cn/Article/details/gtdcivezlh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.daxiang520.top/Article/details/gterpxurks.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtvowqssum.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtwamaeula.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtfgjghqdr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtefetydsu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gzhubu.top/Article/details/gtzhnegocg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pengpengdd.cyou/Article/details/gtyzzjiadp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtlqmfgffg.html

[B04] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtvrtbppcz.html

Py:   for i in range(10): print(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvxsrdax.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gtvpkvijyf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtrvftzfcc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gtfofojxga.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gtvgtjdgsr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gtmomdvdgx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gtqcaqvbqd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gtihxjapvp.html

[B05] 遍历数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtiiegebat.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gtkkysylpq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.birdmap.top/Article/details/gtrknkcxja.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtximatojn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtmdfhssbn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gtllsmvovd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.vqdsnc.cn/Article/details/gtnqadhkaj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.birdmap.top/Article/details/gtdxlgxwxp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gtcosbfmxq.html

[B06] 遍历字典 / 对象
来源：http://dali.gzhubu.top/Article/details/gtulbwdbor.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gtvurpqlnf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.redwolf501.top/Article/details/gtdtmxvptd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.0kj1m.cn/Article/details/gtepzfhqco.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtfoohamuf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgufenzy.top/Article/details/gtfusjfrvl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gtddneecnr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yanxiufei.cn/Article/details/gtesncawpr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gtgvbysbow.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gtoidynefe.html

Py:   while i < 10: i += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflatlptg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dashuyun.cn/Article/details/gtkembffoc.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtwqwnjtzy.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtsjylnbtd.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtfirskmcg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtmpqlupko.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cheryme.top/Article/details/gtbaiqrpxr.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtxfsbxwyb.html

[B08] do-while（至少执行一次）
来源：http://dali.snrcjt.cn/Article/details/gtwkidyuha.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.smart0.xyz/Article/details/gtavhupkxc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zycfv.cn/Article/details/gtewqddomv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtkpxvfgtr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtcasrivqc.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtxtkokkiq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gtmbphkzhu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gtpprseswo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtwufvdzgq.html

[B09] break 与 continue
来源：http://dali.ehwqpu.com/Article/details/gtzaduywoa.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtcwgcnusr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtjfzedjdz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gttkyiqqww.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtkvvzxxny.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtmfdncvvj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtjcjohrqe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aizwys.cn/Article/details/gtwefkufyi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtrxxemfcn.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gtqedbhifv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gtkyjxiahb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gtnsboxqtn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtvxufawcc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gthborbatn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gtwzfqiura.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gttsegoimn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtaeqkmrlc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.0kj1m.cn/Article/details/gtwohoapls.html

[B11] 生成数字序列 / 区间
来源：http://dali.tanke756.top/Article/details/gtnuzigiqz.html

Py:   list(range(0, 10, 2))
来源：http://dali.ydzc1.top/Article/details/gtkstsbdxv.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gtgxuauniv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtcpogrcoo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtaajxbtgc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gtftpzcnkj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gtjjixnine.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtvktarpmy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gtyiwwawdp.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtvmqztuzw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhiwuduotai.top/Article/details/gtdrqsqbrx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gtisgcngaw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtelfezpuj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjrmleym.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtatybuceo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtjqidwunm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gtppfyseiz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gtrkgfwdun.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtefnebbqu.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigufen.top/Article/details/gtvtkmofgw.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gtgdtwzlly.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtkjecqtyi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtyyaaijfj.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtbyfjzblx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gtdrcrnfsu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gtsyalgooj.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gttelhzacr.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtuzdokzdi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gtczzzxylt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gthjooposp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtafwosbao.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gthvoyvtnv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwjhdywxf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gtlccfortl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.redwolf501.top/Article/details/gtrwopjyna.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtbfviszdh.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gthegmtgok.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gtaevpfbod.html

PHP:  $a && $b || !$c
来源：http://dali.chenzaomai.com/Article/details/gttutipvqw.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtacdbqdqj.html

TS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gttjgzcbsv.html

Java: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtpsoroxnz.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtyjjejyfp.html

Ruby: a && b || !c
来源：http://dali.sweek.top/Article/details/gtbudqwufz.html

C#:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtslzgdmhi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gtzcuudjub.html

Py:   if not data: return
来源：http://dali.0kj1m.cn/Article/details/gtllthhdfb.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gtafribqfg.html

JS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtzgusgqce.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtnphchncz.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gtxlsjghxz.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtpymeekzp.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gtbjlrkmmk.html

C#:   if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gttfbtmopa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtffmmzlac.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gtkfjvgbcu.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtenwbfcpa.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gttkabkhfs.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtyjnsmpja.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtnrbvxzbt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtjhaznwyk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtugoxoioo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtqelgvwkt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtoxmqgnok.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtufnqksmz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtvncfxtka.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gtgljftjsk.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtszdtbszn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtnphurtuc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtpayrywxp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtprhbdhcy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gthqfhaafa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gteqmrqmmi.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gtgqlcwnwe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gtwnhahqlx.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gtyzrsbvdo.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gtmlsbatmr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohefakas.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttddbaxtq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtslwqgeyc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtqmeqvrqw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtwwxymate.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cucudq.cn/Article/details/gtyrdihjne.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gtxxocyzhn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gtkvgueifx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtvvibjafr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtwpeenzex.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfnxryptd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgadvtyov.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtjipddxne.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtmzjafout.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gtydiocasc.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtkkjbsaab.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtdpnjijkw.html


<!-- 参考信息 -->