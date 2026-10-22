代发 wailian999

[A14] 注释写法
来源：http://dali.fzhhl.top/Article/details/gtzicpeofd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.aibaodan.cn/Article/details/gtqrtlysqx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gtjtnhcpso.html

JS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtrknkcsno.html

TS:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtralnhzgi.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhengqikj.top/Article/details/gtrorlvquu.html

Go:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtbxbnflfx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.fzhhl.top/Article/details/gtsektbosc.html

C#:   // 单行；/* 多行 */
来源：http://dali.kuanghao11.cn/Article/details/gtjrciajtm.html

[A15] 空值判断与默认值
来源：http://dali.meibo888.top/Article/details/gtsvpmkgpv.html

Py:   value = data or "默认值"
来源：http://dali.cucudq.cn/Article/details/gtnjdrmojl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtgbnhtxbz.html

JS:   const value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtwxmpaocr.html

TS:   const value = data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtfmknmpye.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.haohaochexian.top/Article/details/gtglxyyadv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hywenlv.cn/Article/details/gtbupdlqfc.html

Ruby: value = data || "默认值"
来源：http://dali.xinyue.icu/Article/details/gthzdqmaxd.html

C#:   var value = data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gtijhumqck.html

[A16] 真假值判断规则
来源：http://dali.ehwqpu.com/Article/details/gtsoveubyx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xziqi.cn/Article/details/gtcrjwpmdo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhengqikj.top/Article/details/gtwcrpyjcu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.pycfn.com/Article/details/gtnunljfru.html

TS:   if (!x) {}
来源：http://dali.ppjwa.cn/Article/details/gtjgzzxnmy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.iojbl.cn/Article/details/gtnsqdbvga.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yonumen.top/Article/details/gtlzqtibmu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexzsglmw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gteemfjmtj.html

[A17] 位运算
来源：http://dali.hysaishi.cn/Article/details/gttpibwkty.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtetdhxjcg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtbjlofehs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtmbgitwpc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtxjgtdpcq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtkqufjidy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtohoyhfno.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtgkccrtwu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtrcffgbub.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ydzc1.top/Article/details/gtxnyetocc.html

Py:   ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gtwcjpenpv.html

PHP:  ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtdqdrcngs.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258888.top/Article/details/gtimdlmifn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj202588.top/Article/details/gtlrrsgkvv.html

Java: (int) 'A'; (char) 65
来源：http://dali.dashuyun.cn/Article/details/gttwyejyje.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigfzy.top/Article/details/gtjxwexbif.html

Ruby: "A".ord; 65.chr
来源：http://dali.yueranfly.top/Article/details/gthryjyidq.html

C#:   (int)'A'; (char)65
来源：http://dali.aizwys.cn/Article/details/gtxrrzgjyi.html

[A19] 交换两个变量
来源：http://dali.haohaochexian.top/Article/details/gtvfqlqsua.html

Py:   a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtdfslnnad.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ivvv.top/Article/details/gtevupeubj.html

JS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtqixjyucm.html

TS:   [a, b] = [b, a];
来源：http://dali.yj20258.top/Article/details/gtdxngxbss.html

Java: int t = a; a = b; b = t;
来源：http://dali.tianlin.xyz/Article/details/gtauwaarbo.html

Go:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtcubdnkvf.html

Ruby: a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gtoxkjdlwt.html

C#:   (a, b) = (b, a);
来源：http://dali.zycfv.cn/Article/details/gtvcnhemee.html

[A20] 读取标准输入
来源：http://dali.guowangkeji.top/Article/details/gtdhhfyviq.html

Py:   name = input("请输入：")
来源：http://dali.zhengqikj.top/Article/details/gtwtzanlub.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aibaodan.cn/Article/details/gttndvovxa.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jlsjyb.cn/Article/details/gttbuogaet.html

TS:   // Node.js：readline 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbuknobm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hysaishi.cn/Article/details/gtjjgkxzvx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangdashe.top/Article/details/gtauwhwdrb.html

Ruby: gets.chomp
来源：http://dali.cdnleiting.top/Article/details/gtmqbilchq.html

C#:   Console.ReadLine();
来源：http://dali.nanxuanxn.top/Article/details/gtqhykmdnq.html

[A21] 保留指定小数位输出
来源：http://dali.jinqigfzy.top/Article/details/gtyfqebmzi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hammf.cn/Article/details/gtyjwtfevt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtytvbxvpd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtyxxtmhlw.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtgvszxjct.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtfxgcuxgw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtshzbpjjb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gthzrxafev.html

C#:   3.14159.ToString("F2")
来源：http://dali.shzxlz.cn/Article/details/gtwrmbxwez.html

[A22] 获取字符串长度
来源：http://dali.guannengcc.top/Article/details/gtolhjkfan.html

Py:   len(s)
来源：http://dali.jqgufenzy.top/Article/details/gtmmlprbzk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhiwuduotai.top/Article/details/gtayymnjge.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.0kj1m.cn/Article/details/gthtutrvfl.html

TS:   s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtojpajpyg.html

Java: s.length()
来源：http://dali.tanke756.top/Article/details/gtwepgmqib.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fzhhl.top/Article/details/gtnekspsyi.html

Ruby: s.length
来源：http://dali.daria6918.cn/Article/details/gtnhgrijxg.html

C#:   s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gteyonmony.html

[A23] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtlbfiwjex.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtyoykruhu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daxiang520.top/Article/details/gtojayrazc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtceoofypu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gtszdtrrtf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.svipenyu.cn/Article/details/gtzxwkdjwn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cheryme.top/Article/details/gtxpoxrtca.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtbejggffh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnqzz.top/Article/details/gtopkgleuk.html

[A24] 去除首尾空白
来源：http://dali.jiagoushi.top/Article/details/gtnsezbdkl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtoxwzyqsn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqfxvfnm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtrahgmvns.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gaohongyu789.top/Article/details/gtqpnhynkd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgfzy.top/Article/details/gtloofpgur.html

Go:   strings.TrimSpace(s)
来源：http://dali.hywenlv.cn/Article/details/gtkheutizx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinqigufen.top/Article/details/gtinlnrbkm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtedhthzei.html

[A25] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtbvvjutjv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.daxiang520.top/Article/details/gttqkiorrp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.quarkkingdee.top/Article/details/gttetdowpy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gtasnwbjwn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gtpvlfhsou.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenlongwang.top/Article/details/gtueiqqscm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtloytyaht.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.9152youxi.cn/Article/details/gtvthmcrbv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gtaraovdqm.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlufxiadu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.meibo888.top/Article/details/gtehbdlxaw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigufen.top/Article/details/gttgjqyolp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fzhhl.top/Article/details/gtipdwlxel.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gtkgrntxsb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtfwcadcix.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.bjfxy.top/Article/details/gtfcnjbfka.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gtejbbzfab.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtgdscjqtu.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwelotlfb.html

B. 流程控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgynifku.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthdlgcyzv.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gtomvzqkwh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dashuyun.cn/Article/details/gtxnvfimmv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258888.top/Article/details/gtgugfsgqc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gtzbfzrfmz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtonhiphwu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtlynmxbqe.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yvedp.cn/Article/details/gtlcqtdzcj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenlongwang.top/Article/details/gtxohwqvjf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtyszjekmg.html

[B02] 多分支 else if / elif
来源：http://dali.zhengqikj.top/Article/details/gtwhjrjgju.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cdnleiting.top/Article/details/gtfyqlegyd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.0kj1m.cn/Article/details/gtcmilwhdg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycbauuus.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtxunafrzr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtytbhftjo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuanzx.com/Article/details/gtrpqahfzm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhiwuduotai.top/Article/details/gtvvryphvv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtdshxcnxf.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtytwiqtwl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gtofjmemqi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtgbbqrjcz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtxfonjwzl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtnijkzgmm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.fengsongda.top/Article/details/gtpmrszcvi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdvfcxtj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gtjrezvjsz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sxryk.cn/Article/details/gtbmlouqlb.html

[B04] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gtalrcuquw.html

Py:   for i in range(10): print(i)
来源：http://dali.meibo888.top/Article/details/gtexjvuxid.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuanzhike.top/Article/details/gtzdhbovon.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtwdmamfgk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtvxgbnqib.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtssvpcyhu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.smart0.xyz/Article/details/gtjvnmdcls.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gtdinjnggh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtcmzkxwqd.html

[B05] 遍历数组 / 列表
来源：http://dali.andypj.xyz/Article/details/gtijcwoyiq.html

Py:   for item in arr: print(item)
来源：http://dali.sxryk.cn/Article/details/gtmhofrdhd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gtaennnpqx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtuzqeucmo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gttobuyieo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuanzx.com/Article/details/gtbvnxlvso.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ydzc1.top/Article/details/gtpznbcofk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.quarkkingdee.top/Article/details/gtvzepgbts.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.0kj1m.cn/Article/details/gtntggrjij.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtxhwfhpkk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yongpay.top/Article/details/gtfiopopmp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gtzeusvlvx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtrawhugqc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtrphevlti.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daxiang520.top/Article/details/gtbwjbqbio.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shangyingyoupin.top/Article/details/gtbxtplwpz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cdnleiting.top/Article/details/gtrfvmqssi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtucrylylv.html

[B07] while 循环
来源：http://dali.jyoumei.cn/Article/details/gtsmuxhwon.html

Py:   while i < 10: i += 1
来源：http://dali.tanke756.top/Article/details/gtbskyudda.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtglunqchm.html

JS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtproqenur.html

TS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtykuxbdkt.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtgvdapbwd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jyoumei.cn/Article/details/gtoyyxagib.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtwfduwxdh.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbnhmpaq.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gtuukizdlr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gtgnbkcheo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nwbrower.top/Article/details/gtsymawddq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtpxjlopen.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtflrmtpfi.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtltwjereo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxinkj.top/Article/details/gtqwuvwlxf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gtgqxneout.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtkyuzmnwq.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfihpbwu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gtjwmpscje.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtaaeserrl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtvrwydixz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtaraqxiai.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtynfvpfjc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yangfankeji.com/Article/details/gttzdcrcyv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jianghu66.top/Article/details/gtyoknbovi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtfdcaujmg.html

[B10] 遍历同时拿索引
来源：http://dali.aibaodan.cn/Article/details/gtttomobbc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gtpcepeqrm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtwwltvnot.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtjrovoyrx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtscfpmqdj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gtwpqxudlx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sweek.top/Article/details/gtpzwvsoos.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cucudq.cn/Article/details/gtenwmtpsj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gtwdsgwuhn.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtwondauhw.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupskzbhb.html

PHP:  range(0, 10, 2);
来源：http://dali.gogol.net.cn/Article/details/gtvtqomokh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtjsrqjjkb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtxtrqkzmk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gtlclrfeoj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gtgokzihoa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gtrqcvorbi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yanxiufei.cn/Article/details/gtadkgpqwp.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gtuwfjwzhk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gtkfwfvqlo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gtvbbtuztx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtiolenoik.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gttefmcjlr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtgsqvvjtn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtpuhiinvw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gtgawohfyb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtqealtjov.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gtvjbitiwo.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gtonglvypw.html

PHP:  is_numeric($x)
来源：http://dali.sufxvd.cn/Article/details/gtgyclmzvi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtkqyofkrt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtsiorkrbm.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gtjirmrhmo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ppjwa.cn/Article/details/gtfgrxcnjv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkosmkgr.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gtmjnoynpz.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtgmikkpxu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daria6918.cn/Article/details/gtgemdrdkf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangdashe.top/Article/details/gtcdsfemxa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtaeckuqiy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gtpykhaygw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtbsteupfl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gtuxvdmphg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtnodfxtav.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gttawrhtdj.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gtftcwpzvd.html

Py:   a and b or not c
来源：http://dali.nwbrower.top/Article/details/gtrxdjyfje.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gtojojhdmn.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtnlqksvvo.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gthbilvjhn.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gttxnmmied.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtlinsuihs.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtxpndajlr.html

C#:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtekkheufh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.wangdashe.top/Article/details/gtisbaucmm.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gthogtzlku.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdadkijsx.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gtgmbazaqd.html

TS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gthelgyhav.html

Java: if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtatdbwnbx.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtclejcjpf.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtsdmhvapf.html

C#:   if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtozkwscrz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtchwidbpp.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gtzazwgztv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtlpygfcxv.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gtnyiwllxd.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtrlzvmprm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtrgxxvpvw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtkntyheqk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtfowwrhle.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtkzxvdfms.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gtpxihafab.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gtlejppuwm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtevwlmkff.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gtweuqvckp.html

Py:   def greet(name="World"): return name
来源：http://dali.sweek.top/Article/details/gteglrxsax.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gtihegykiw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtuyedqtip.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtigtiyjug.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.svipenyu.cn/Article/details/gtyievbxof.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtldnsgscv.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gtljjveamx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gtgiykuyyt.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtouzhcbeb.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gtwttdmprf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gtgrsghyed.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtwrrpbnzd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtcrirfsvn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pycfn.com/Article/details/gtoxebdwyt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtoeqvycuj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxinkj.top/Article/details/gtndhnpyxi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gtjypdbzmm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gtcokmjndu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gthcfjinia.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtqhuioolv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtmtuofkfe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtaluefdhw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahwtdqom.html


<!-- 参考信息 -->