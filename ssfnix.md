代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gt2oalsrqnj.html

JS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gt2tpuxbzep.html

TS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gt2yxrgumvm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sxryk.cn/Article/details/gt2zazofwcb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjrbpkeu.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgufenzy.top/Article/details/gt2ajngebtj.html

C#:   $"Hello, {name}!"
来源：http://dali.cashguo.top/Article/details/gt2ygbgfkzq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.dianchejie.cn/Article/details/gt2kctyirgy.html

Py:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2eqydbbos.html

PHP:  "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2bogzflyv.html

JS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2dggkvnmr.html

TS:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2mmtwqsdh.html

Java: "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2bpapnouz.html

Go:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gt2bodmfirt.html

Ruby: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2ryuuzuiy.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2dwxpqnrg.html

[A14] 注释写法
来源：http://dali.jiagoushi.top/Article/details/gt2kylbondp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yangfankeji.com/Article/details/gt2pkasergh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gt2qmikogme.html

JS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gt2hkoeaquk.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2pyycuigb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuanzhike.top/Article/details/gt2mpqvfcvn.html

Go:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2ygtnnwjv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cashguo.top/Article/details/gt2vmzripmb.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iucptrqj.html

[A15] 空值判断与默认值
来源：http://dali.cdnleiting.top/Article/details/gt2lrnjtauv.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gt2eddvdgda.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gt2smhuggze.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbgjkyoe.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gt2elxfzugk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2woszoncj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.xuanzx.com/Article/details/gt2idnmmixr.html

Ruby: value = data || "默认值"
来源：http://dali.sufxvd.cn/Article/details/gt2ozqxtoux.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqhxdygb.html

[A16] 真假值判断规则
来源：http://dali.xuetiantiany.cn/Article/details/gt2aaitoxkf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.9152youxi.cn/Article/details/gt2azsmpigc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.snrcjt.cn/Article/details/gt2jortoqxa.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.svipenyu.cn/Article/details/gt2hvhubrvv.html

TS:   if (!x) {}
来源：http://dali.nanxinkj.top/Article/details/gt2vmcrzlrm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuanzx.com/Article/details/gt2befxftdv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zdqjudy.top/Article/details/gt2aodjxrun.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hammf.cn/Article/details/gt2gmodsebl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tian-w.cn/Article/details/gt2ymgbzyww.html

[A17] 位运算
来源：http://dali.guannengcc.top/Article/details/gt2ejimutzg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2gslqujsd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2hssrakrn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrgrilek.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gt2haozscqk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gt2njmwlkus.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2rhkxnohi.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urtnxfdx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2wfialjce.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xziqi.cn/Article/details/gt2yxhwocwt.html

Py:   ord("A"); chr(65)
来源：http://dali.guannengcc.top/Article/details/gt2htymofpu.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnxiangtu.top/Article/details/gt2dtsarfot.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gt2rubrnvpx.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cheryme.top/Article/details/gt2lmrjggxe.html

Java: (int) 'A'; (char) 65
来源：http://dali.yueranfly.top/Article/details/gt2gxcsesal.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.wangdashe.top/Article/details/gt2wovmgbbp.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmmvdxwj.html

C#:   (int)'A'; (char)65
来源：http://dali.9152youxi.cn/Article/details/gt2exzfrvor.html

[A19] 交换两个变量
来源：http://dali.zhixingplan.top/Article/details/gt2xbwdmmoz.html

Py:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btuddxqb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sufxvd.cn/Article/details/gt2whnstqef.html

JS:   [a, b] = [b, a];
来源：http://dali.fzhhl.top/Article/details/gt2fiwhvvzb.html

TS:   [a, b] = [b, a];
来源：http://dali.yuxming.cn/Article/details/gt2ixddovxa.html

Java: int t = a; a = b; b = t;
来源：http://dali.mhx1999.top/Article/details/gt2dnapwzfe.html

Go:   a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gt2rgmrmssm.html

Ruby: a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gt2tpxhhzfg.html

C#:   (a, b) = (b, a);
来源：http://dali.nanxinkj.top/Article/details/gt2afrxqvpv.html

[A20] 读取标准输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2xpjclutm.html

Py:   name = input("请输入：")
来源：http://dali.jqgfzy.top/Article/details/gt2ilkyqxxy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hammf.cn/Article/details/gt2oekzselc.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbhzghfb.html

TS:   // Node.js：readline 模块
来源：http://dali.cashguo.top/Article/details/gt2hcsahnuf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.redwolf501.top/Article/details/gt2cxkcyffs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cashguo.top/Article/details/gt2oyjesupx.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gt2iyxieadg.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gt2rbihmciy.html

[A21] 保留指定小数位输出
来源：http://dali.yj20258888.top/Article/details/gt2qvtrfrqk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wcufxveq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gt2cvsschsj.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gt2nfputjoj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gt2spvqbmwu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gt2pmuzyrzm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gt2hvnvingp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gt2gewumrju.html

C#:   3.14159.ToString("F2")
来源：http://dali.fzhhl.top/Article/details/gt2xtadpiby.html

[A22] 获取字符串长度
来源：http://dali.chenlongwang.top/Article/details/gt2eocuqruh.html

Py:   len(s)
来源：http://dali.sufxvd.cn/Article/details/gt2royxswux.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.svipenyu.cn/Article/details/gt2vwbbaqgv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zdqjudy.top/Article/details/gt2qdcyqohc.html

TS:   s.length
来源：http://dali.dianchejie.cn/Article/details/gt2isdraeiv.html

Java: s.length()
来源：http://dali.guowangkeji.top/Article/details/gt2farehlap.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2dtlrpgzf.html

Ruby: s.length
来源：http://dali.meibo888.top/Article/details/gt2tykqkshc.html

C#:   s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2zgjwjljm.html

[A23] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gt2bbkshqpq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2euqsbwix.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ealbzpjd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gt2smlwpihp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gt2afyjgbmm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwpthpt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhengqikj.top/Article/details/gt2cwwbjuvl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuanzhike.top/Article/details/gt2omjsynvs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj20258888.top/Article/details/gt2umeyqthu.html

[A24] 去除首尾空白
来源：http://dali.iojbl.cn/Article/details/gt2amswupro.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shuidangran.top/Article/details/gt2xxxskokw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhixingplan.top/Article/details/gt2tggmrzun.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gt2vcdpfein.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cwedtepk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shuidangran.top/Article/details/gt2dlprhdhu.html

Go:   strings.TrimSpace(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2paygytef.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cheryme.top/Article/details/gt2qhbstssf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gt2ncledeup.html

[A25] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2hwneqnhf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tianlin.xyz/Article/details/gt2jfrjrbjs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cdnleiting.top/Article/details/gt2whelomct.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgkqitgc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xziqi.cn/Article/details/gt2udyejxwi.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gt2eiqmwitq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iucwzbmt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gt2pznsvhvq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gt2uzygjrjq.html

[A26] 类型转换总览
来源：http://dali.tanke756.top/Article/details/gt2clopgkel.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziiyceea.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zncmikvj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yuxming.cn/Article/details/gt2ukmonzvp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ybcxt.top/Article/details/gt2vjxfcgbt.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hammf.cn/Article/details/gt2mtvjunvz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.pycfn.com/Article/details/gt2svotbgcc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gotoacloud.top/Article/details/gt2prlwtmzb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gt2uxwxnxoy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2yjhppojr.html

B. 流程控制
来源：http://dali.zycfv.cn/Article/details/gt2ejokwcne.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2ltcksgmn.html

[B01] 条件判断 if / else
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuciyane.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hnqzz.top/Article/details/gt2adlrxrok.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhixingplan.top/Article/details/gt2dxnnggpn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gt2hyiokzuh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ldwbdqte.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghhgsfgx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhongyouzk.top/Article/details/gt2pksualhm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqvkgsrl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gt2fddvnwao.html

[B02] 多分支 else if / elif
来源：http://dali.yangfankeji.com/Article/details/gt2gplsznye.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jiagoushi.top/Article/details/gt2nfhurmpa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ybcxt.top/Article/details/gt2tfubiggi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gt2eyewectm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gt2ixgjxhet.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gt2crwsfmma.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hywenlv.cn/Article/details/gt2zgqdmhyg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxinkj.top/Article/details/gt2pzlcozxu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gt2fbbdecqc.html

[B03] switch / match / case
来源：http://dali.dianchejie.cn/Article/details/gt2pcircyfe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gaohongyu789.top/Article/details/gt2yspssnbt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gt2jcavamdf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2ahotcszj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2ntrtqauv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gt2vlmeaeya.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gt2lriwyzgi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jianghu66.top/Article/details/gt2cloenbro.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gt2qgmkwylt.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gt2kgzsgufh.html

Py:   for i in range(10): print(i)
来源：http://dali.sxryk.cn/Article/details/gt2vhegjnlu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jiqixmqf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gt2nbprjuee.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gt2gififwgo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gt2qcqawdrv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gt2rcjfhfjy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jyoumei.cn/Article/details/gt2ksvwagqw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2drxxpwfl.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgnqhkfa.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gt2ktkylfge.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gt2oaeijpuy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2zducgkvh.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2lezggpho.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hywenlv.cn/Article/details/gt2xafebstg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cdnleiting.top/Article/details/gt2tkioscuj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.haohaochexian.top/Article/details/gt2bdmpbkxx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zdqjudy.top/Article/details/gt2okoucgaz.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gt2ydobopdo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sufxvd.cn/Article/details/gt2ylbtrimo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258888.top/Article/details/gt2lzvacciu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2qkvqqqgw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gt2xkhmzuls.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxinkj.top/Article/details/gt2guhycqck.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cqqwz.cn/Article/details/gt2lopvfixz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jianghu66.top/Article/details/gt2glwqfgfm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hfpthk.cn/Article/details/gt2lngkqnzl.html

[B07] while 循环
来源：http://dali.cqqwz.cn/Article/details/gt2eeqodyxm.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2izxgaqzt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.birdmap.top/Article/details/gt2hebcctrs.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gt2pzppmyud.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2djchqyyq.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2ititxnkc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gt2idhurhoo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gt2asuivlie.html

C#:   while (i < 10) { i++; }
来源：http://dali.316326.xyz/Article/details/gt2ftrkskky.html

[B08] do-while（至少执行一次）
来源：http://dali.hammf.cn/Article/details/gt2lapkxruh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gt2oxwoncmj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yonumen.top/Article/details/gt2akobvglz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gt2anildbdn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slcnqdph.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2qplqtprj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2oghmbfxv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yj20258888.top/Article/details/gt2dahrikvi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2exzbrzbt.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gt2moweyiwi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sweek.top/Article/details/gt2pdyxkoja.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2tzbwzxuw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2amkfukrn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2reqyddjq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2iugnllxm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnqzz.top/Article/details/gt2jhbezmzt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2diranuxo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2sbnysusi.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258.top/Article/details/gt2fmqclinm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gt2oszkcpur.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gt2znrqukfw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2xuiwifpm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gt2tabopoha.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.bjfxy.top/Article/details/gt2lxmfgoul.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtnyocbc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mipxrmkf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2brkjpsfc.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gt2vgswoxsr.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gt2yhsrnqlx.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2fqgiutap.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2dsfxgiqs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gt2svsrnrgi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhudfude.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gt2ucorpeps.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gt2pvmtizcb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gt2zkqxxvfv.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gt2nuymjmyj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gt2pqrceluh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aibaodan.cn/Article/details/gt2wnhijbxs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gt2ykneseqz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtupsquq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gt2aptfquxb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigufen.top/Article/details/gt2mtoojlzz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gt2geoqogcj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gt2rzpxrxiy.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2bktwzcge.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gt2sfvqgbqm.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gt2oytgefno.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2ozvqpxag.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gt2sibezljd.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gt2jkczphba.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gt2fokctacw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gt2ibkkoprx.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gt2ggcwpgcz.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2gurfcgmx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxuanxn.top/Article/details/gt2cvvlinfl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhegqbeb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gt2ddknnvcn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2felekuhx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gt2hkcldyeg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gt2bcelhwkh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2jihowiko.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vpbhigov.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gt2nfyxygxa.html

Py:   a and b or not c
来源：http://dali.0kj1m.cn/Article/details/gt2zdjtqwml.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gt2coqeqofp.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2mjzosaoz.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2qbgkrcqi.html

Java: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvbhpdhl.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2pyqiyuiq.html

Ruby: a && b || !c
来源：http://dali.sweek.top/Article/details/gt2vxwkmbzr.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2qumjkrip.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2qliysgcw.html

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gt2dyeurrnq.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gt2pfaltxin.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gt2tqqfzman.html

TS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suxtgojd.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gt2pezfgyjy.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gt2klihygom.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gt2lwfwnoxt.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gt2yiewdspn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jksfltkc.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gt2hvbjmivz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yycobzmh.html

[C01] 定义函数
来源：http://dali.daxiang520.top/Article/details/gt2pdasjnox.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2dcpxdkge.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2sqiwlejd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2qztydrzt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjmjoiz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2plmcdigv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gt2obzegihw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2mhrrcnna.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2omcjrwjs.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2eznrhewa.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gt2okkdokhn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhengqikj.top/Article/details/gt2rliyxdyv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2hqcwrdca.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2ubkrjyxm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gt2vjjlrhdp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwzksheq.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gt2xhhppqvz.html


<!-- 参考信息 -->