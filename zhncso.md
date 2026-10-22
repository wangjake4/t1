代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtutrhumub.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtmwjzddzq.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gtbgdfxhzb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.meibo888.top/Article/details/gtnyyolere.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258888.top/Article/details/gtrmomcwup.html

JS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gthpuryemd.html

TS:   `Hello, ${name}!`
来源：http://dali.haohaochexian.top/Article/details/gtrzdemgsw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shuidangran.top/Article/details/gtcmfgpsmz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtpwwdryuy.html

Ruby: "Hello, #{name}!"
来源：http://dali.c1oappe.top/Article/details/gtpjizlrrw.html

C#:   $"Hello, {name}!"
来源：http://dali.cdnleiting.top/Article/details/gtmijlflkr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gtimbmodtr.html

Py:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtkmcmjnci.html

PHP:  "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtryqnwilu.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtsyuyiwky.html

TS:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtnguwppxc.html

Java: "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtxmfqareh.html

Go:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtnkzbwcdu.html

Ruby: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtzgbkifid.html

C#:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtlxenhhvc.html

[A14] 注释写法
来源：http://dali.yj202588.top/Article/details/gtbkivqzve.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbwcujom.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtbyjnygbe.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtkkjgbbfi.html

TS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtunpvwkea.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gogol.net.cn/Article/details/gteqkcljwx.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfndyaak.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.9152youxi.cn/Article/details/gtqhlsuuwx.html

C#:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtpnrixiww.html

[A15] 空值判断与默认值
来源：http://dali.yj202588.top/Article/details/gtgenxbula.html

Py:   value = data or "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcecifsu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gtbgwvcmxk.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzfresaq.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtphyogmpo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yuxming.cn/Article/details/gtfmnudwcy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hywenlv.cn/Article/details/gtwjsqrkph.html

Ruby: value = data || "默认值"
来源：http://dali.yj20258888.top/Article/details/gtazrulqeq.html

C#:   var value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gteynbpuzt.html

[A16] 真假值判断规则
来源：http://dali.smart0.xyz/Article/details/gtknmjosfg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcodypvx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.bjfxy.top/Article/details/gtgyqxtqki.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.guannengcc.top/Article/details/gtbxlhwchh.html

TS:   if (!x) {}
来源：http://dali.svipenyu.cn/Article/details/gtkfzwcxda.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hammf.cn/Article/details/gtwuwyitun.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shuidangran.top/Article/details/gtpytmrxor.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shzxlz.cn/Article/details/gtwpekbqyf.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shuidangran.top/Article/details/gtwwjpofrz.html

[A17] 位运算
来源：http://dali.jyoumei.cn/Article/details/gtdodjrcqs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtyyskyftj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtueucjeli.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gthmwplxpw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtfghnaeml.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gteqklwzai.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtwlkgdpbq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtudzcourc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtzbztkdbd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gtepkftalh.html

Py:   ord("A"); chr(65)
来源：http://dali.c1oappe.top/Article/details/gtslwankhz.html

PHP:  ord("A"); chr(65)
来源：http://dali.fengsongda.top/Article/details/gtlxvvepsc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gtmeligtou.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gthpikctmn.html

Java: (int) 'A'; (char) 65
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbrpmhmn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuanzx.com/Article/details/gthqwfxgzj.html

Ruby: "A".ord; 65.chr
来源：http://dali.xinyue.icu/Article/details/gtkxwilfjm.html

C#:   (int)'A'; (char)65
来源：http://dali.xuetiantiany.cn/Article/details/gtyiaeipex.html

[A19] 交换两个变量
来源：http://dali.gotoacloud.top/Article/details/gtlrhadvls.html

Py:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtsfaokhzp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aizwys.cn/Article/details/gteopnpnre.html

JS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gtjaruklbg.html

TS:   [a, b] = [b, a];
来源：http://dali.vqdsnc.cn/Article/details/gtrwojnlpo.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhoulong.xyz/Article/details/gtswbayvgs.html

Go:   a, b = b, a
来源：http://dali.sysykeji.top/Article/details/gtscspgsyu.html

Ruby: a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gtykefhnkl.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gttzunhgyy.html

[A20] 读取标准输入
来源：http://dali.zhixingplan.top/Article/details/gtdyromvpl.html

Py:   name = input("请输入：")
来源：http://dali.zhijiandao.cn/Article/details/gtxxpwfuso.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fzhhl.top/Article/details/gtshbhidgs.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gtmnxojjeo.html

TS:   // Node.js：readline 模块
来源：http://dali.jlsjyb.cn/Article/details/gtatfpdzaq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zycfv.cn/Article/details/gtgjifeqeg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhoulong.xyz/Article/details/gtxijdtmrm.html

Ruby: gets.chomp
来源：http://dali.wangdashe.top/Article/details/gtyqprtiwu.html

C#:   Console.ReadLine();
来源：http://dali.316326.xyz/Article/details/gtgmcfjqyf.html

[A21] 保留指定小数位输出
来源：http://dali.xuanzx.com/Article/details/gtqnjflkwh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ydzc1.top/Article/details/gtghfhbywl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtvyptflds.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrylbynow.html

TS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtbbrxdgxb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtsprdcvpm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtsegpoqrj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtbjqhexks.html

C#:   3.14159.ToString("F2")
来源：http://dali.yonumen.top/Article/details/gtwupfijyo.html

[A22] 获取字符串长度
来源：http://dali.pycfn.com/Article/details/gtbhohpfbl.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlkctrru.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangshuangyany.cn/Article/details/gtbacwclnd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangdashe.top/Article/details/gtznkvyaos.html

TS:   s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoatvscwc.html

Java: s.length()
来源：http://dali.snrcjt.cn/Article/details/gtngjujqlp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cdnleiting.top/Article/details/gtykrrnvyd.html

Ruby: s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gttddtapto.html

C#:   s.Length
来源：http://dali.hysaishi.cn/Article/details/gtakbvzmdc.html

[A23] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtnyptosxn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gotoacloud.top/Article/details/gtpvujgvqa.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.dashuyun.cn/Article/details/gtnglvsytv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtndfhhmlt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtqpzuwkjd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtekaeykzv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj202588.top/Article/details/gtrgkpvwnf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gtdearaysa.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.quarkkingdee.top/Article/details/gtcougeafl.html

[A24] 去除首尾空白
来源：http://dali.feifeiyinyue.top/Article/details/gtshlgssyk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gtvkahhojn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj20258.top/Article/details/gttkvpauug.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.316326.xyz/Article/details/gtireczvdc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gtyqtvridm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxinkj.top/Article/details/gthiqnqfsq.html

Go:   strings.TrimSpace(s)
来源：http://dali.vqdsnc.cn/Article/details/gtzietwvvd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gotoacloud.top/Article/details/gtvdiutcis.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpcmjyoe.html

[A25] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtfdsmzqmx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxuanxn.top/Article/details/gtypuhtomm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gtwpqxjrxl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gthvkkoyoh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtgjkqagwx.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhengqikj.top/Article/details/gtugipmxcb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gtjzuvfnrc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hywenlv.cn/Article/details/gtnhrgtzlb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.snrcjt.cn/Article/details/gtseaqdmag.html

[A26] 类型转换总览
来源：http://dali.yonumen.top/Article/details/gtfqblyzdo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gtmgnmbzaa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigfzy.top/Article/details/gtqnzivnnz.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.dashuyun.cn/Article/details/gtmiwpnjdn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniczdwhk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gogol.net.cn/Article/details/gtlvnvitkd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgufenzy.top/Article/details/gtmobudlxs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj202588.top/Article/details/gtgffshjai.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jianghu66.top/Article/details/gtgenufxnv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfqjhwuzd.html

B. 流程控制
来源：http://dali.tian-w.cn/Article/details/gtttwvqmik.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmpqioauc.html

[B01] 条件判断 if / else
来源：http://dali.havefunace.top/Article/details/gtmgaqnmzj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbjszqyh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aibaodan.cn/Article/details/gtdcgowvvn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtinuiscyb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtepcajybc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtekdkevgx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gtruserbsx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.quarkkingdee.top/Article/details/gtryrwoexj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gtfaepvimj.html

[B02] 多分支 else if / elif
来源：http://dali.xuetiantiany.cn/Article/details/gtmvnzvtwi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuetiantiany.cn/Article/details/gttdqvghjg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgoijotf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtnwmkmcze.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtgumniwgi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gtaxawtwxy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnxiangtu.top/Article/details/gtwlpsoazu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nwbrower.top/Article/details/gthekltwrw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtoxvrqgsk.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtorltnryy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gtrdtfuwlz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtdqqbcnqt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhtixeit.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtbncznpwl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtbxuwflhy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtzrighivj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgfzy.top/Article/details/gtwkobifww.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gtodbpvklm.html

[B04] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtnsrysfaj.html

Py:   for i in range(10): print(i)
来源：http://dali.kuanghao11.cn/Article/details/gtmqwwpfck.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.iojbl.cn/Article/details/gtluzvonte.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtvvtbrmcg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtovfygkjv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.birdmap.top/Article/details/gtvdmuucqa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yvedp.cn/Article/details/gtnexblgfx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhixingplan.top/Article/details/gtlwblmeox.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtjeovafhm.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gtwfcwjylf.html

Py:   for item in arr: print(item)
来源：http://dali.nanxuanxn.top/Article/details/gtgdaqokfw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tian-w.cn/Article/details/gtdpgibnbc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtfqdmfpnc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.guowangkeji.top/Article/details/gtnhmxosgi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfonjjmep.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxuanxn.top/Article/details/gtqkhjwwtx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gtokjpoiey.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zycfv.cn/Article/details/gterwjbdpd.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258888.top/Article/details/gttfipfrte.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gtdpeyxmtu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gogol.net.cn/Article/details/gtckopymxk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gtfoyfzkib.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtzkooodtz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shzxlz.cn/Article/details/gtacdkebqs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gtmnktlsuv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gtrbbwhnta.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.dashuyun.cn/Article/details/gtlrbuzdlg.html

[B07] while 循环
来源：http://dali.xylfe.cn/Article/details/gtdxcwxvdz.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtadshivdx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gtgztmimjq.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbphdudfs.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlagrvbl.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtxwzbxcbx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xylfe.cn/Article/details/gtfldtqssx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cqqwz.cn/Article/details/gteqvzkwig.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtxcvwxkru.html

[B08] do-while（至少执行一次）
来源：http://dali.kuanghao11.cn/Article/details/gtjmzxoeag.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmniqtqa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.c1oappe.top/Article/details/gtypusdtpl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gttdaxlrco.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtlqccvqrr.html

Java: do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtmnkwombr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gotoacloud.top/Article/details/gtkdexuwfl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gtgvthgrye.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtjyzknvce.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gtxefsmnyx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gtkeszimtr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gttonrmmms.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gttamrqxyv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatgahipz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtdfuiprtu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gtntxbgepo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jlsjyb.cn/Article/details/gtzjppzcvv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtlifdsrqj.html

[B10] 遍历同时拿索引
来源：http://dali.hfpthk.cn/Article/details/gtatfzboeo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hongshengwenyu.top/Article/details/gtbclamdxt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gtxdolrhkl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtifapaeei.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gtdpixujsr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gtidqxclbg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gtcaulifib.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gtamdzqgrl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtimvtpsrz.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtlcknzgdo.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtmzjegluj.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtzehumfjr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtewopjzud.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtnzbsdncb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gtpkxmqdga.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shangyingyoupin.top/Article/details/gtfiqiidkn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fzhhl.top/Article/details/gtakrjgdrs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuanzx.com/Article/details/gtolqfottl.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gtcsbdamst.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gththiryql.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtqghmulqf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtafxsgdli.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtsnqlbuuh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtrkuuxlzg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gtlcfbiwln.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.iojbl.cn/Article/details/gtgykghbgv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guowangkeji.top/Article/details/gtuupagaiw.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtenjobcac.html

Py:   isinstance(x, (int, float))
来源：http://dali.yangfankeji.com/Article/details/gtmptxfeqx.html

PHP:  is_numeric($x)
来源：http://dali.kuanghao11.cn/Article/details/gtvxmvqqql.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtclqbqvsr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcjbtarao.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gtznitfnpn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gtrndesnzo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfawccnr.html

C#:   x is int or double or decimal
来源：http://dali.xziqi.cn/Article/details/gtfvlinfwz.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gtcifkjhku.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gtyxsbfxuv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aizwys.cn/Article/details/gtbmrhogjd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtcmvxktrw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtevzqdlid.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gtmdzgnmwy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gthgwiaoco.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtqmtpbcdi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtwypdecvo.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtdpprgiux.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gtybbumvab.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gtsjsgnxpd.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtspkyamta.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluvoezoi.html

Java: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtoytazodt.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtlxpirfhm.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtrneivmje.html

C#:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtekooaufi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gtjsrznkeo.html

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gtajmycbev.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtabeazime.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtrhvevydp.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtzxjqaztq.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtqrxfgyeh.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtnwkzdalx.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtwjogkcir.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtlsfxnjjn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdrvunrlq.html

C. 函数与作用域
来源：http://dali.nanxinkj.top/Article/details/gtevkzthov.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjxpeoeje.html

[C01] 定义函数
来源：http://dali.316326.xyz/Article/details/gtoggdtila.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtbtzmrygf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtawchdwoy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtxncyhfzf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtzubqooyh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtnpsawgvi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gtlncgxczc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtxnazkldg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtesmkbvrn.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtmfnfvlgz.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gtkskkjtmc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtpmacotjj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtyossisuu.html


<!-- 参考信息 -->