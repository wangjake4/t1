代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jyoumei.cn/Article/details/gthkkrmrlp.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhoulong.xyz/Article/details/gtrszmrqwn.html

C#:   $"Hello, {name}!"
来源：http://dali.ybcxt.top/Article/details/gtqfbrxmnn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.andypj.xyz/Article/details/gtqwdotdrb.html

Py:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtbxaeszlc.html

PHP:  "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtdoxbiwiy.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtacqpecvy.html

TS:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gthacpbgib.html

Java: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtgsibbiyv.html

Go:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtiabvsuxl.html

Ruby: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtievdyevz.html

C#:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtovydmguv.html

[A14] 注释写法
来源：http://dali.cucudq.cn/Article/details/gtphbbcyrt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gogol.net.cn/Article/details/gtqemvdycm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtytubpxdl.html

JS:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtusfssbvi.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gttecyjyvg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnduxwako.html

Go:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabzlweir.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.pengpengdd.cyou/Article/details/gtxfhkspvl.html

C#:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtjfyvrsop.html

[A15] 空值判断与默认值
来源：http://dali.0kj1m.cn/Article/details/gtyyamsyva.html

Py:   value = data or "默认值"
来源：http://dali.feifeiyinyue.top/Article/details/gtcjbvmcre.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gtonpwyuay.html

JS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gtdkgzjtiu.html

TS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtjofppger.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.aizwys.cn/Article/details/gtyxdokhtx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.redwolf501.top/Article/details/gtjmaeqibp.html

Ruby: value = data || "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gtuapehdqp.html

C#:   var value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gturbomcxl.html

[A16] 真假值判断规则
来源：http://dali.zdqjudy.top/Article/details/gtysgaxejn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tianlin.xyz/Article/details/gtzdqfhftk.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.wangshuangyany.cn/Article/details/gtfvxhnqrg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.daxiang520.top/Article/details/gtpaqlbrmi.html

TS:   if (!x) {}
来源：http://dali.jinqigufen.top/Article/details/gtipujfksn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yuxming.cn/Article/details/gtypjlftbv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.dianchejie.cn/Article/details/gtywcdfzar.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhengqikj.top/Article/details/gtpzselhlu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cucudq.cn/Article/details/gtshqsvfef.html

[A17] 位运算
来源：http://dali.sxryk.cn/Article/details/gtxhfkppvz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtcpknuyxd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtohgiibwa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtihizkafj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtqyuxxtjk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtsqdiinjk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtgigrpods.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtjjpocfmk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtzkssqrxd.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ivvv.top/Article/details/gtzpeeupbc.html

Py:   ord("A"); chr(65)
来源：http://dali.meibo888.top/Article/details/gtkrkiqclo.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuanzhike.top/Article/details/gtwatxwvsv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrqfcdza.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.aizwys.cn/Article/details/gttnldzvyv.html

Java: (int) 'A'; (char) 65
来源：http://dali.sufxvd.cn/Article/details/gtkessbbum.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhoulong.xyz/Article/details/gtckugobsl.html

Ruby: "A".ord; 65.chr
来源：http://dali.smart0.xyz/Article/details/gtcelbjxqv.html

C#:   (int)'A'; (char)65
来源：http://dali.chenzaomai.com/Article/details/gthvscbghd.html

[A19] 交换两个变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoxfinun.html

Py:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gtsvbpkqkt.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shzxlz.cn/Article/details/gtgcclhaie.html

JS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtyeshszvj.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsrvpgbq.html

Java: int t = a; a = b; b = t;
来源：http://dali.bjfxy.top/Article/details/gtuuvckxim.html

Go:   a, b = b, a
来源：http://dali.gotoacloud.top/Article/details/gtrpeneyfh.html

Ruby: a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtnjovjbms.html

C#:   (a, b) = (b, a);
来源：http://dali.nwbrower.top/Article/details/gtwapsrnzp.html

[A20] 读取标准输入
来源：http://dali.sweek.top/Article/details/gtejbhryww.html

Py:   name = input("请输入：")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxirfnjxn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shuidangran.top/Article/details/gtqtfcxvpi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zdqjudy.top/Article/details/gtpfximsue.html

TS:   // Node.js：readline 模块
来源：http://dali.zhoulong.xyz/Article/details/gtoshrdazq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gtsuvztoli.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.pycfn.com/Article/details/gtkhtqcdzl.html

Ruby: gets.chomp
来源：http://dali.nanxuanxn.top/Article/details/gtmowquund.html

C#:   Console.ReadLine();
来源：http://dali.chenzaomai.com/Article/details/gtdlpdiprb.html

[A21] 保留指定小数位输出
来源：http://dali.xuanzx.com/Article/details/gtwnxhdcpc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangdashe.top/Article/details/gtipxperbp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtsvzvckyq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtvuokyfql.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtvypuscql.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmninwhx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gttndpjlwk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gtzxwgdtvx.html

C#:   3.14159.ToString("F2")
来源：http://dali.yangfankeji.com/Article/details/gtlecvreui.html

[A22] 获取字符串长度
来源：http://dali.bjfxy.top/Article/details/gtgucwruzv.html

Py:   len(s)
来源：http://dali.hywenlv.cn/Article/details/gtzjouqhry.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gaohongyu789.top/Article/details/gtvsehgsdn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gotoacloud.top/Article/details/gtgxriaogw.html

TS:   s.length
来源：http://dali.cucudq.cn/Article/details/gtwdggufrf.html

Java: s.length()
来源：http://dali.jianghu66.top/Article/details/gtmcqqejck.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gtcnuidxiy.html

Ruby: s.length
来源：http://dali.meibo888.top/Article/details/gtwlrhjxea.html

C#:   s.Length
来源：http://dali.gotoacloud.top/Article/details/gtcmfkpjqw.html

[A23] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtcoktgzbr.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.0kj1m.cn/Article/details/gtictcevsi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ydzc1.top/Article/details/gtcckwwbrl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gtuaetluyz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gtbdgiubaq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtknhngmlt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tianlin.xyz/Article/details/gtqfusivhh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqeimzgw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.birdmap.top/Article/details/gtjzhhjzph.html

[A24] 去除首尾空白
来源：http://dali.jiagoushi.top/Article/details/gttwprlxfa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhongyouzk.top/Article/details/gttudyiavp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.vqdsnc.cn/Article/details/gtrgfhcrhy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtiaqxdwwp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gtorhuyxem.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cheryme.top/Article/details/gtnhlqgsdv.html

Go:   strings.TrimSpace(s)
来源：http://dali.pycfn.com/Article/details/gtgtxlyzfa.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxuanxn.top/Article/details/gtydsafhbm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.316326.xyz/Article/details/gtvmorpuhb.html

[A25] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtsyorayrc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nanxinkj.top/Article/details/gtefhxiaaa.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cqqwz.cn/Article/details/gtceqjgdwi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258.top/Article/details/gtwcoibcbg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtybgdcsym.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.tanke756.top/Article/details/gtjnqygqcu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gtpweomfad.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tian-w.cn/Article/details/gtkdflsnqt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.havefunace.top/Article/details/gtvhkldvll.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtzathxcbw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cashguo.top/Article/details/gtsnjosrrc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hfpthk.cn/Article/details/gtduyqrder.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gtvibxgqse.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jyoumei.cn/Article/details/gtlgowepio.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gtpmnmievn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gotoacloud.top/Article/details/gtfluhxodi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gtbgtbneup.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cashguo.top/Article/details/gtwwqcyhwe.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfbhynyyl.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtfxomsvpe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtoafsltll.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gtrjhgudrc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gtwkqamutq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gtstqxwjwo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gthkproybw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtnosojutu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtunjyevmq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnxiangtu.top/Article/details/gtkhplzkjv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gtznxqlsme.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtcviygjfo.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gtcqtdpklu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.birdmap.top/Article/details/gtnpypzzdm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xinyue.icu/Article/details/gtehusksfv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtptagyuzm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtpbtkhrwv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtaaisvfwy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gtktxlcwtg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxinkj.top/Article/details/gtrgeiorfe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtgseafrqu.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gtwcppdzwr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtadtapkxk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gttrdeovxa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtjpuktvml.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtquewikrw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtkayycnyv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gtzkwvzlun.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aizwys.cn/Article/details/gtvkssetdh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutwqjdxw.html

[B04] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gteolsdknd.html

Py:   for i in range(10): print(i)
来源：http://dali.ppjwa.cn/Article/details/gtkzveuonr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnqzz.top/Article/details/gtiwlsuvcr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtvstmvsoc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtjvjuawro.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gtnrqgucyi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fengsongda.top/Article/details/gtncsqeqlu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gtbbtpkznn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtaqcewcpc.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gteyckoguo.html

Py:   for item in arr: print(item)
来源：http://dali.daria6918.cn/Article/details/gtiyvseuwe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cucudq.cn/Article/details/gtsmxnktec.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtgdsealas.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtphjegmgw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cqqwz.cn/Article/details/gtehkbcggs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.fzhhl.top/Article/details/gtqsgqspmt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yongpay.top/Article/details/gteqodilxu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfivcfpdn.html

[B06] 遍历字典 / 对象
来源：http://dali.meibo888.top/Article/details/gtdmkmbumd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.birdmap.top/Article/details/gtmpkyablp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtfcppuhgv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafjwlfgq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gtzjbwgihh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gtqctvblei.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigufen.top/Article/details/gtbfkimeyp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gthehyycgb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pycfn.com/Article/details/gtomafwhnh.html

[B07] while 循环
来源：http://dali.cashguo.top/Article/details/gtcxvfphnh.html

Py:   while i < 10: i += 1
来源：http://dali.yuxming.cn/Article/details/gtkkfxqyua.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gtwghathyo.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtztqkqnbp.html

TS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtagpcxuzg.html

Java: while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gtmwqopqzb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangdashe.top/Article/details/gtdnywbzwp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jianghu66.top/Article/details/gttmnqgqtq.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtkokcqjsx.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigfzy.top/Article/details/gtayewyehh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gtvpbfingr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gtdvyrnvup.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gttqllxmwl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtrsgutmvn.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtefmbrxrt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtvkvnfwli.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.snrcjt.cn/Article/details/gthuxtnlyc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtepccwkwj.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gtdcfdixrg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hongshengwenyu.top/Article/details/gtqqbhkexn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtznfwwnoj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtuacbfzmq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtkxnwusnj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gttcuslyxg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtixvwnucu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guowangkeji.top/Article/details/gtfnpoeuoh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtjoaeogdj.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gthqzyzpqq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.smart0.xyz/Article/details/gtrtxfgxgr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtjrkwwlgt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtnqcfuohy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtuzlzzfhy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtcmsfhaem.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gtuunyssij.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sxryk.cn/Article/details/gtqwukxckg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtktyphxsi.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gtnilmyecd.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gtntainxum.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gtrowmeaui.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtnvyxilfl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gtxqzfblyh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtoybeplio.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtvofraaxe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gtolkiydlm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigufen.top/Article/details/gtxufwovww.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gtkhpkunpd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gttdeqynwl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gtwdrctbek.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtakmgdvmk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtzlxavkkl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtcovpjovx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gtrogvttrd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gtkgtrmrhk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gtpinkgjff.html

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gtkzixfqsy.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gtbvcvovso.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrhpkycuo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtkehsizeb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtblramnnf.html

Java: x instanceof Number
来源：http://dali.yuanzhike.top/Article/details/gtbkqctjzg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtfesoakmu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangdashe.top/Article/details/gtsceauone.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gtxsyphkbu.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtqsljhdsh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gtooyiribd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gtfselvpht.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtjymkdhob.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtcgrmdilq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtclyqfcwo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gthasydlbl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtwayyeweo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtdzefppmk.html

[B15] 布尔运算与取反
来源：http://dali.cucudq.cn/Article/details/gtgdcllbuc.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gtbbflrjin.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gtjpmmenuz.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtyhhnsucm.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtnfyntlgf.html

Java: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtsyqvjpzv.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gttbrdonvi.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gttytrkrbl.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gttpxgnaaz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.0kj1m.cn/Article/details/gtylmlcxra.html

Py:   if not data: return
来源：http://dali.haohaochexian.top/Article/details/gtakdwezpy.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgvxscld.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtgjmikyhh.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gthzaivjoq.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtvfhtlvxz.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gtkbffnzmq.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gtxovqbpxl.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtrkgoeufd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnawdeznn.html

C. 函数与作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtkcjclviq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkqcghhrm.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtckomyxov.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtaeyjngyw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtmpvebhnb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtfxvzdsao.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtsrulsusl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqjfcktj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtpyyvbxgy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtfaaclsmg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtdtwkrqpm.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtdcbgtekk.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtbrkknlhj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslypqdpy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtgubtrzaj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmemsyjdv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gtuftzmtdj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtztkgkmpz.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gtturckkqn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gtplsdewjy.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtnijiwezs.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gtcupbpble.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gtpjpkzwdj.html


<!-- 参考信息 -->