代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2obcfbdtk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.shzxlz.cn/Article/details/gt2efitgjlj.html

Go:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gt2ncczhupi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yonumen.top/Article/details/gt2rnijaixu.html

C#:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2fjikacmk.html

[A15] 空值判断与默认值
来源：http://dali.jinqigfzy.top/Article/details/gt2gmkpgcnj.html

Py:   value = data or "默认值"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjqvprhz.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gt2jtomurxk.html

JS:   const value = data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gt2rxwodaav.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2surzetlw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zycfv.cn/Article/details/gt2uemnhgzj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tanke756.top/Article/details/gt2azfspiuc.html

Ruby: value = data || "默认值"
来源：http://dali.ydzc1.top/Article/details/gt2siwhtrtw.html

C#:   var value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gt2heryuane.html

[A16] 真假值判断规则
来源：http://dali.jqgfzy.top/Article/details/gt2jmqbshen.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jyoumei.cn/Article/details/gt2luuhtyop.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxinkj.top/Article/details/gt2ikwxytme.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.mhx1999.top/Article/details/gt2csznkenc.html

TS:   if (!x) {}
来源：http://dali.shuidangran.top/Article/details/gt2aevgrlpp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2sfcdutpo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.haohaochexian.top/Article/details/gt2wonigxtv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.fzhhl.top/Article/details/gt2wafqlmrm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2tmquorkt.html

[A17] 位运算
来源：http://dali.yvedp.cn/Article/details/gt2aaxyofas.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2adhwxmci.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ydzc1.top/Article/details/gt2gsfmknza.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gt2rnrspyhj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gt2dwrgifja.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2daxexjwm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2gznswrtg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2znnxroba.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2hfktgshx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.c1oappe.top/Article/details/gt2lfyrcohb.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gt2hrszjtld.html

PHP:  ord("A"); chr(65)
来源：http://dali.fengsongda.top/Article/details/gt2hetfesjh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cdnleiting.top/Article/details/gt2iaxmadnk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.mhx1999.top/Article/details/gt2zzeczimj.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigfzy.top/Article/details/gt2tbebkrrz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.chenjidiqi.icu/Article/details/gt2ediqgbku.html

Ruby: "A".ord; 65.chr
来源：http://dali.jlsjyb.cn/Article/details/gt2cnyvukvx.html

C#:   (int)'A'; (char)65
来源：http://dali.birdmap.top/Article/details/gt2vnkjahxm.html

[A19] 交换两个变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgnzntuw.html

Py:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2ikwyiobj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ybcxt.top/Article/details/gt2rtcfpvux.html

JS:   [a, b] = [b, a];
来源：http://dali.cucudq.cn/Article/details/gt2fluyiruu.html

TS:   [a, b] = [b, a];
来源：http://dali.xylfe.cn/Article/details/gt2qkyxkmvd.html

Java: int t = a; a = b; b = t;
来源：http://dali.hnqzz.top/Article/details/gt2nbfpcmtj.html

Go:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gt2stneimkm.html

Ruby: a, b = b, a
来源：http://dali.yj202588.top/Article/details/gt2kardfunj.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigufen.top/Article/details/gt2wzamacxm.html

[A20] 读取标准输入
来源：http://dali.xuetiantiany.cn/Article/details/gt2zecflfmz.html

Py:   name = input("请输入：")
来源：http://dali.c1oappe.top/Article/details/gt2diljcuni.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.smart0.xyz/Article/details/gt2uysijcnq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgfzy.top/Article/details/gt2pguyetnj.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigufen.top/Article/details/gt2ijiytewj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.daria6918.cn/Article/details/gt2oyahvcul.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yuanzhike.top/Article/details/gt2jxedvcac.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gt2qeyplrim.html

C#:   Console.ReadLine();
来源：http://dali.mhx1999.top/Article/details/gt2eodyngqh.html

[A21] 保留指定小数位输出
来源：http://dali.bjfxy.top/Article/details/gt2mqbdridk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czfatfbs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gt2uepifwlz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2zgdxlxxb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gt2gyxqbthc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gt2zuysmpue.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2qxkallez.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gt2preqqzod.html

C#:   3.14159.ToString("F2")
来源：http://dali.zycfv.cn/Article/details/gt2jreiyjnp.html

[A22] 获取字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2azjyzesp.html

Py:   len(s)
来源：http://dali.9152youxi.cn/Article/details/gt2zqnirbis.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cqqwz.cn/Article/details/gt2bpvnlbox.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guowangkeji.top/Article/details/gt2oytcbopw.html

TS:   s.length
来源：http://dali.fengsongda.top/Article/details/gt2cbotcqur.html

Java: s.length()
来源：http://dali.ivvv.top/Article/details/gt2juzyzkza.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hsnwdoxv.html

Ruby: s.length
来源：http://dali.sysykeji.top/Article/details/gt2omkrhyir.html

C#:   s.Length
来源：http://dali.daxiang520.top/Article/details/gt2wbeqhtae.html

[A23] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhvqwppj.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjkfxkry.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pycfn.com/Article/details/gt2mhlxmefs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gt2fsyxtikw.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktolgyta.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gt2peburiiz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkbvizso.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shuidangran.top/Article/details/gt2kcebotru.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvocgqsn.html

[A24] 去除首尾空白
来源：http://dali.zhixingplan.top/Article/details/gt2gbefcodf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqyicvay.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gt2qhyvpyff.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gt2rwgrlshh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gt2rvamkuvn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jyoumei.cn/Article/details/gt2xmuvyegk.html

Go:   strings.TrimSpace(s)
来源：http://dali.nwbrower.top/Article/details/gt2teyphnxg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.redwolf501.top/Article/details/gt2dcgqgfzv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ultpwmmj.html

[A25] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2fhatthly.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ydzc1.top/Article/details/gt2appmahlx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kaulyjdb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gt2ztzgujzr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gt2dlnghulk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenzaomai.com/Article/details/gt2katgsdve.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gt2bhepdtza.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gt2nsvxwdsr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gt2qgfaoauj.html

[A26] 类型转换总览
来源：http://dali.zhijiandao.cn/Article/details/gt2jmreypyd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gt2pzxwkwso.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhoulong.xyz/Article/details/gt2zgpyzgoz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tian-w.cn/Article/details/gt2efydskmj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ppjwa.cn/Article/details/gt2vppvvhol.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gt2tcdmbooa.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.iojbl.cn/Article/details/gt2ghldsiwj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2mtedvrbw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gt2rokalsqy.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2mopsicdy.html

B. 流程控制
来源：http://dali.zhijiandao.cn/Article/details/gt2scfizqpo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2urfxeizz.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gt2jphipwdn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ivvv.top/Article/details/gt2fwzpsxeh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cheryme.top/Article/details/gt2qxtcpakg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gt2laeercfw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gt2yceooktc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gt2ksokmlzw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gzhubu.top/Article/details/gt2yqtctrsy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258.top/Article/details/gt2pbcquwwf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2jphqkqnq.html

[B02] 多分支 else if / elif
来源：http://dali.yvedp.cn/Article/details/gt2bfwdrdvk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daria6918.cn/Article/details/gt2wjsgsdlj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gzhubu.top/Article/details/gt2vhiqgfat.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gt2spcxnexx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gt2kbfcfscz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gt2jpfggzmh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dashuyun.cn/Article/details/gt2ydzrcgbz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daria6918.cn/Article/details/gt2zxavgxqu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmqxsntm.html

[B03] switch / match / case
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohjjqopm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gt2mymqrqci.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangdashe.top/Article/details/gt2xbsgjgpa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gt2dignlkhu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fzhgtkwp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gt2hrsstche.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gt2xofamtbj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gt2utggckvt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gt2zwqredfx.html

[B04] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gt2pgtzscag.html

Py:   for i in range(10): print(i)
来源：http://dali.sysykeji.top/Article/details/gt2sronvwuh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ehwqpu.com/Article/details/gt2pgzrfnxo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gt2debvqpxq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gt2iteehnzm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.mhx1999.top/Article/details/gt2ximngnoo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gt2ecknontt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdrlktf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuxming.cn/Article/details/gt2fxsdfnnv.html

[B05] 遍历数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gt2yofatwgi.html

Py:   for item in arr: print(item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2epqkjbsv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gogol.net.cn/Article/details/gt2abvgdeok.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpthzeup.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gt2ptrsbzbg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kufpodci.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tianlin.xyz/Article/details/gt2yismivwt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jqgufenzy.top/Article/details/gt2ttruvncp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2skudeieq.html

[B06] 遍历字典 / 对象
来源：http://dali.ivvv.top/Article/details/gt2mtnawvqj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gaohongyu789.top/Article/details/gt2fcetzmbr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dianchejie.cn/Article/details/gt2kdtsqfef.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gt2nmxblbqn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gt2uykockkq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gt2oeremtfr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yueranfly.top/Article/details/gt2nxrmenew.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cheryme.top/Article/details/gt2zpnygjkd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sysykeji.top/Article/details/gt2elvcxhsn.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gt2mkdpbmic.html

Py:   while i < 10: i += 1
来源：http://dali.daxiang520.top/Article/details/gt2wihlwkmk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gt2zbittgyt.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gt2lidxailr.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2hpldkkse.html

Java: while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2ftesmafl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pengpengdd.cyou/Article/details/gt2uepsqnie.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hysaishi.cn/Article/details/gt2uroicitj.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2lqnfkarb.html

[B08] do-while（至少执行一次）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhckcvuh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gt2myeyfegx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2whbcypei.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2qplxsvdc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2jmsiatse.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2dhlqiyvn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wyomepav.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xinyue.icu/Article/details/gt2ozomerxj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2wzzxxlix.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gt2qewmngrw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuxming.cn/Article/details/gt2seeffgtf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2yoixyzog.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2gemwpzaw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpouuuhh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gt2ssfetsgv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gt2vgtkglqv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnxiangtu.top/Article/details/gt2ozfbcgri.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2dsymayfc.html

[B10] 遍历同时拿索引
来源：http://dali.fengsongda.top/Article/details/gt2rturlazi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gogol.net.cn/Article/details/gt2znzyttqr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ufhxcrkm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2kczwspje.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gt2yvsycsae.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gt2vnqyeuku.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gt2lljcqshb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gt2icdaqfol.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwekqsio.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gt2csukssqj.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gt2nnxrdsqn.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2tswpiazy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gt2cmtqhqtp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2zgwctuel.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2qzdqhawd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guowangkeji.top/Article/details/gt2rhxgkzdu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gt2rwixwyrt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gt2zhzxjzsx.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhoufdi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cqqwz.cn/Article/details/gt2tmfxrrzu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gt2tflwprow.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gt2wfkdiugn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmzlfbwn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2tdxyqeir.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gt2hnpxphum.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2wgbnkecs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jianghu66.top/Article/details/gt2lwsdeyxt.html

[B13] 判断是否为数字
来源：http://dali.tianlin.xyz/Article/details/gt2boveliij.html

Py:   isinstance(x, (int, float))
来源：http://dali.xziqi.cn/Article/details/gt2bpvqauih.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gt2ycgirnas.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2kcznbncf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gt2mqrynvvj.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gt2foykhueo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gt2cqcygpwc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gt2glbyxsfr.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gt2yiyqmgqm.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258.top/Article/details/gt2itaychmo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gt2dqsvhsyh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.andypj.xyz/Article/details/gt2uqtvfrwn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2rucjrvcp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2dahhplvf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2jngrxwtd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cheryme.top/Article/details/gt2rpoqsqbw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2omknicsh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gt2fphnpqjg.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gt2bjcfnirn.html

Py:   a and b or not c
来源：http://dali.hnxiangtu.top/Article/details/gt2onpmlzej.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gt2ohlfauuw.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2wkorttpd.html

TS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2gvhkiepz.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2rqhaldzd.html

Go:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2fcuebotp.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehtjxhwg.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gt2psfsticn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gt2qukjahll.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gt2tflzqbkq.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gt2npwvvkec.html

JS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gt2alipupxq.html

TS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfzddynn.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gt2menqdfom.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gt2hmzxxydh.html

Ruby: return if data.nil?
来源：http://dali.svipenyu.cn/Article/details/gt2kbyutrcy.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2fsbjqbdl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugiesgpj.html

C. 函数与作用域
来源：http://dali.guannengcc.top/Article/details/gt2fermzrsr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zwijdvec.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2sljtqeqj.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2jgdnsoxs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqscpdck.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2threstde.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2ngumpyjp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vinpqfvm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jssacpto.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgyzdlo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2ytzeowbm.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2glseqbla.html

Py:   def greet(name="World"): return name
来源：http://dali.yuanzhike.top/Article/details/gt2otiaekho.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gt2apgynrio.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2bedwjcja.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ixzezsbh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gt2psskbciw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gt2uymtssmc.html

Ruby: def greet(name = "World") = name
来源：http://dali.guannengcc.top/Article/details/gt2nxsoxrxs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hovdmsda.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gt2qptxbmjy.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gt2imvpuizo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gt2toboitet.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmnldefk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2dqyibdeu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gt2ztdlmzeo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gt2nzvxojlu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2yhadjxvb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gt2nvqwchei.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gt2aqkfambj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gt2ikwydypj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2tqjnowip.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2peduglbt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gt2rcbqfvhl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gt2wfanlsui.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gt2ybuvhgfq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2kdepjwgw.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2vacynack.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gt2hgdzynhi.html


<!-- 参考信息 -->